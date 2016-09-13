#### Test 85019474526c333_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 12:25:37.617   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-13 12:25:38.220   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:25:39.536  3802  3802 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:25:39.541  3802  3802 D AndroidRuntime: CheckJNI is OFF
09-13 12:25:39.577  3802  3802 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:25:39.621  3802  3802 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:25:39.642  3802  3802 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 12:25:39.651   874  1949 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 12:25:39.678  2096  2115 W SearchService: Abort, client detached.
09-13 12:25:39.683  2096  2096 I HotwordDetector: Closing mic
09-13 12:25:39.684  2096  2346 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8f3c7a9
09-13 12:25:39.685  2096  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 12:25:39.690  3802  3802 D AndroidRuntime: Shutting down VM
09-13 12:25:39.715   874  1678 I ActivityManager: Start proc 3811:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 12:25:39.733   377  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 12:25:39.734   377  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 12:25:39.739   377  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 12:25:39.742  2096  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 12:25:39.743  2096  2355 I MicroRecognitionRnrImpl: Detection finished
09-13 12:25:39.793  3811  3811 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 12:25:39.820  3811  3811 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 12:25:39.826  3811  3811 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5361-5363)
09-13 12:25:39.826  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:25:39.840  3811  3811 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {854c7c4}
09-13 12:25:39.840  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:25:39.840  3811  3811 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 12:25:39.846  3811  3811 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 12:25:39.847  3811  3811 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 12:25:39.882  3811  3811 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 12:25:39.893  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 12:25:39.893  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 12:25:39.893  3811  3811 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 12:25:39.893  3811  3811 I Adreno  : Build Date                       : 10/20/15
09-13 12:25:39.893  3811  3811 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 12:25:39.893  3811  3811 I Adreno  : Local Branch                     : M14
09-13 12:25:39.893  3811  3811 I Adreno  : Remote Branch                    : 
09-13 12:25:39.893  3811  3811 I Adreno  : Remote Branch                    : 
09-13 12:25:39.893  3811  3811 I Adreno  : Reconstruct Branch               : 
,09-13 12:25:39.943   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a154d32:true
,09-13 12:25:39.999  3811  3811 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 12:25:40.016  3811  3811 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 12:25:40.127  3811  3849 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 12:25:40.135  3811  3836 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 12:25:40.178  3811  3849 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 12:25:40.234   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +538ms
,09-13 12:25:40.244  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-13 12:25:40.334  3811  3811 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3811
,09-13 12:25:40.469  3811  3811 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:25:40.520   874  1678 I ActivityManager: Killing 3231:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 12:25:40.584   874  1678 I ActivityManager: Killing 2980:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-13 12:25:40.631   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 12:25:40.671  3811  3851 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1695876816
,09-13 12:25:40.677  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:25:40.677  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:25:40.677  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:25:40.677  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:25:40.677  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 12:25:40.678  3811  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7090fab added. We now have 1 listener(s)
,09-13 12:25:40.681  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 12:25:40.681  3811  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:25:40.682  3811  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:40.682  3811  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76,
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 12:25:40.685  3811  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6ccfc6 added. We now have 1 listener(s)
,09-13 12:25:40.685  3811  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:25:40.690   874  1312 D WifiService: New client listening to asynchronous messages
,09-13 12:25:40.691  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:25:40.691  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 12:25:40.691  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 12:25:40.691  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 12:25:40.691  3811  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 12:25:40.698  3811  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:40.699  3811  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 12:25:40.707  3811  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:40.708  3811  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:40.708  3811  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 12:25:40.708  3811  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:25:40.709  3811  3851 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 12:25:40.710  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:25:40.712  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:40.737  3811  3811 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:25:41.648  3811  3861 W jxcore-log: Initializing JXcore engine
,09-13 12:25:41.648  3811  3861 W jxcore-log: JXcore engine is ready
,09-13 12:25:41.695  3861  3861 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8955 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 12:25:41.695  3861  3861 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13029]" dev="sockfs" ino=13029 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 12:25:41.695  3861  3861 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-13 12:25:41.695  3861  3861 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21483]" dev="sockfs" ino=21483 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 12:25:41.724  3811  3861 W jxcore-log: Starting JXcore engine
,09-13 12:25:41.820  3811  3861 W jxcore-log: Platform android
09-13 12:25:41.820  3811  3861 W jxcore-log: 
,09-13 12:25:41.820  3811  3861 W jxcore-log: Process ARCH arm
09-13 12:25:41.820  3811  3861 W jxcore-log: 
,09-13 12:25:42.090  3811  3861 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:25:42.090  3811  3861 I jxcore-log: 
,09-13 12:25:42.090  3811  3861 W jxcore-log: JXcore engine is started
,09-13 12:25:42.097  3811  3851 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 12:25:42.101  3811  3811 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:25:47.116   874  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 12:25:49.898  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:25:49.904  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:25:49.905  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:25:49.924  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:25:49.924  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 12:25:49.924  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:25:49.924  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:25:49.951  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 12:25:49.956  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 12:25:49.956  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 12:25:50.001  3610  3872 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 12:25:50.017  3610  3873 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 12:25:50.047  1502  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 12:25:50.047  1502  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 12:25:50.047  1502  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:25:50.047  1502  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:25:50.083  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 12:25:50.083  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 12:25:50.083  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:25:50.083  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:25:50.095  3610  3873 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 12:25:50.096  3610  3872 E BooksSync: Soft error
09-13 12:25:50.096  3610  3872 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:25:50.096  3610  3872 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 12:25:50.096  3610  3872 E BooksSync: Sync error
09-13 12:25:50.096  3610  3872 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:25:50.096  3610  3872 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 12:25:50.096  3610  3872 I BooksSync: Finished books sync
,09-13 12:25:50.100   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125513, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:25:52.733   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 12:25:56.286  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:25:56.286  3811  3861 I jxcore-log: 
,09-13 12:25:56.289  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:25:56.289  3811  3861 I jxcore-log: 
,09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:56.300  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:56.305  3811  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:56.308  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:25:56.308  3811  3861 I jxcore-log: 
,09-13 12:25:56.310  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:25:56.310  3811  3861 I jxcore-log: 
,09-13 12:25:56.674  3811  3861 I jxcore-log: Running unit tests
09-13 12:25:56.674  3811  3861 I jxcore-log: 
,09-13 12:25:56.674  3811  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:25:56.674  3811  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3606821 added. We now have 2 listener(s)
,09-13 12:25:56.676  3811  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:25:56.676  3811  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:56.676  3811  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:56.676  3811  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 12:25:56.676  3811  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4c9446 added. We now have 2 listener(s)
09-13 12:25:56.676  3811  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:25:56.676  3811  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:25:56.679  3811  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:56.686  3811  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:56.688  3811  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:56.689  3811  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:25:56.693  3811  3861 D executeNativeTests: Running unit tests
,09-13 12:25:56.699  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:56.704  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:56.734  3811  3861 I jxcore-log: Total number of executed tests:  1
09-13 12:25:56.734  3811  3861 I jxcore-log: 
,09-13 12:25:56.734  3811  3861 I jxcore-log: Number of passed tests:  1
09-13 12:25:56.734  3811  3861 I jxcore-log: 
09-13 12:25:56.734  3811  3861 I jxcore-log: Number of failed tests:  0
09-13 12:25:56.734  3811  3861 I jxcore-log: 
09-13 12:25:56.734  3811  3861 I jxcore-log: Number of ignored tests:  0
09-13 12:25:56.734  3811  3861 I jxcore-log: 
09-13 12:25:56.734  3811  3861 I jxcore-log: Total duration:  3
09-13 12:25:56.734  3811  3861 I jxcore-log: 
,09-13 12:25:56.737  3811  3861 I jxcore-log: Unit Test app is loaded
09-13 12:25:56.737  3811  3861 I jxcore-log: 
09-13 12:25:56.744  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:56.744  3811  3861 I jxcore-log: 
,09-13 12:25:56.749  3811  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:56.749  3811  3861 I jxcore-log: 
,09-13 12:25:56.753  3811  3811 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 12:25:56.753  3811  3861 I jxcore-log: My device name is: motorola-Nexus 6,
09-13 12:25:56.753  3811  3861 I jxcore-log: 
,09-13 12:25:56.754  3811  3861 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 12:25:56.754  3811  3861 I jxcore-log: 
,09-13 12:25:56.755  3811  3861 I jxcore-log: Running for WIFI network type
09-13 12:25:56.755  3811  3861 I jxcore-log: 
,09-13 12:25:58.787   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 12:25:59.403  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 12:25:59.403  3811  3861 I jxcore-log: 
,09-13 12:25:59.861  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 12:25:59.861  3811  3861 I jxcore-log: 
,09-13 12:25:59.894  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 12:25:59.894  3811  3861 I jxcore-log: 
,09-13 12:26:01.300  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 12:26:01.300  3811  3861 I jxcore-log: 
,09-13 12:26:01.547  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 12:26:01.547  3811  3861 I jxcore-log: 
,09-13 12:26:01.552  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 12:26:01.552  3811  3861 I jxcore-log: 
,09-13 12:26:01.559  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 12:26:01.559  3811  3861 I jxcore-log: 
,09-13 12:26:01.637  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 12:26:01.637  3811  3861 I jxcore-log: 
,09-13 12:26:01.821   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 12:26:01.852  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 12:26:01.852  3811  3861 I jxcore-log: 
,09-13 12:26:01.858  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 12:26:01.858  3811  3861 I jxcore-log: 
,09-13 12:26:02.572  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 12:26:02.572  3811  3861 I jxcore-log: 
,09-13 12:26:02.747  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 12:26:02.747  3811  3861 I jxcore-log: 
,09-13 12:26:03.084  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 12:26:03.084  3811  3861 I jxcore-log: 
,09-13 12:26:03.095  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 12:26:03.095  3811  3861 I jxcore-log: 
,09-13 12:26:03.103  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 12:26:03.103  3811  3861 I jxcore-log: 
,09-13 12:26:03.110  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 12:26:03.110  3811  3861 I jxcore-log: 
,09-13 12:26:03.151  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 12:26:03.151  3811  3861 I jxcore-log: 
,09-13 12:26:03.199  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 12:26:03.199  3811  3861 I jxcore-log: 
,09-13 12:26:03.207  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 12:26:03.207  3811  3861 I jxcore-log: 
,09-13 12:26:03.214  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 12:26:03.214  3811  3861 I jxcore-log: 
,09-13 12:26:03.235  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 12:26:03.235  3811  3861 I jxcore-log: 
,09-13 12:26:03.240  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 12:26:03.240  3811  3861 I jxcore-log: 
,09-13 12:26:03.246  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 12:26:03.246  3811  3861 I jxcore-log: 
,09-13 12:26:03.263  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 12:26:03.263  3811  3861 I jxcore-log: 
,09-13 12:26:03.289  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 12:26:03.289  3811  3861 I jxcore-log: 
,09-13 12:26:03.301  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 12:26:03.301  3811  3861 I jxcore-log: 
,09-13 12:26:03.315  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 12:26:03.315  3811  3861 I jxcore-log: 
,09-13 12:26:03.327  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 12:26:03.327  3811  3861 I jxcore-log: 
,09-13 12:26:03.343  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 12:26:03.343  3811  3861 I jxcore-log: 
,09-13 12:26:03.354  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 12:26:03.354  3811  3861 I jxcore-log: 
,09-13 12:26:03.360  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 12:26:03.360  3811  3861 I jxcore-log: 
,09-13 12:26:03.390  3811  3861 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 12:26:03.390  3811  3861 I jxcore-log: 
,09-13 12:26:03.404  3811  3861 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 12:26:03.405  3811  3861 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 12:26:03.405  3811  3861 I jxcore-log: 
,09-13 12:26:03.408  3811  3861 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 12:26:03.408  3811  3861 I jxcore-log: 
09-13 12:26:03.408  3811  3861 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 12:26:03.408  3811  3861 I jxcore-log: 
,09-13 12:26:03.413  3811  3861 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 12:26:03.413  3811  3861 I jxcore-log: 
,09-13 12:26:04.341  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:04.341  3811  3861 I jxcore-log: 
,09-13 12:26:04.341  3811  3861 I jxcore-log: websocket error
09-13 12:26:04.341  3811  3861 I jxcore-log: 
09-13 12:26:04.342  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:04.342  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:04.342  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:04.342  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:04.342  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:04.342  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:04.342  3811  3861 I jxcore-log: 
,09-13 12:26:05.583  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:05.583  3811  3861 I jxcore-log: 
09-13 12:26:05.583  3811  3861 I jxcore-log: websocket error
09-13 12:26:05.583  3811  3861 I jxcore-log: 
09-13 12:26:05.583  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:05.583  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:05.583  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:05.583  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:05.583  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:05.583  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:05.583  3811  3861 I jxcore-log: 
,09-13 12:26:08.460   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 12:26:08.493  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:08.493  3811  3861 I jxcore-log: 
,09-13 12:26:08.493  3811  3861 I jxcore-log: websocket error
09-13 12:26:08.493  3811  3861 I jxcore-log: 
,09-13 12:26:08.494  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:08.494  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:08.494  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:08.494  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:08.494  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:08.494  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:08.494  3811  3861 I jxcore-log: 
,09-13 12:26:12.869  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:12.869  3811  3861 I jxcore-log: 
09-13 12:26:12.869  3811  3861 I jxcore-log: websocket error
09-13 12:26:12.869  3811  3861 I jxcore-log: 
,09-13 12:26:12.869  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:12.869  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:12.869  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:12.869  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:12.869  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:12.869  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:12.869  3811  3861 I jxcore-log: 
,09-13 12:26:14.617   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 12:26:14.625  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-13 12:26:14.633   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 12:26:14.633   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 12:26:14.633   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 12:26:14.633   874   894 I Adreno  : Local Branch                     : M14
09-13 12:26:14.633   874   894 I Adreno  : Remote Branch                    : 
09-13 12:26:14.633   874   894 I Adreno  : Remote Branch                    : 
09-13 12:26:14.633   874   894 I Adreno  : Reconstruct Branch               : 
,09-13 12:26:14.674   281   349 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (622 us)
,09-13 12:26:15.331  3811  3811 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 12:26:15.332  3811  3811 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 12:26:15.364   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 12:26:15.365  3811  3811 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d03573a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f621b8, 16908290=android.view.AbsSavedState$1@f621b8}, android:focusedViewId=100}]}]
,09-13 12:26:15.365  3811  3811 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 12:26:15.365  3811  3811 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 12:26:15.365  3811  3811 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 12:26:15.369   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 12:26:15.375   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 12:26:15.375   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-13 12:26:15.375   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 12:26:15.605   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 12:26:15.609   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-13 12:26:15.615   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-13 12:26:15.618   874   894 I DreamManagerService: Entering dreamland.
,09-13 12:26:15.619   874   894 I PowerManagerService: Dozing...
,09-13 12:26:15.619   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 12:26:15.663   377  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 12:26:15.663   377  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 12:26:15.677   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:26:15.690  1996  3880 D NfcService: Discovery configuration equal, not updating.
,09-13 12:26:15.693   874  1311 E native  : do suspend false
,09-13 12:26:15.693   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 12:26:15.716   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 12:26:15.731   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:26:15.735   874  1311 E native  : do suspend true
,09-13 12:26:15.805   377  1474 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 12:26:15.806   377  1474 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 12:26:16.183   874  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 12:26:17.926  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:17.926  3811  3861 I jxcore-log: 
,09-13 12:26:17.926  3811  3861 I jxcore-log: websocket error
09-13 12:26:17.926  3811  3861 I jxcore-log: 
09-13 12:26:17.927  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:17.927  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:17.927  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:17.927  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:17.927  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:17.927  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:17.927  3811  3861 I jxcore-log: 
,09-13 12:26:20.043  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:20.057  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:20.060  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:20.091  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:26:20.091  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 12:26:20.091  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:20.091  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:20.122  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 12:26:20.122  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 12:26:20.123  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 12:26:20.333  3035  3885 V KeepSync: Connecting to GoogleApiClient
,09-13 12:26:20.334   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 12:26:20.448  1502  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 12:26:20.448  1502  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 12:26:20.448  1502  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:20.448  1502  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:20.461  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:26:20.461  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:26:20.461  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:26:20.461  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:20.465  1708  3888 V BaseAuthAsyncOperation: access token request failed
,09-13 12:26:20.467  3035  3885 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 12:26:20.475  2996  3887 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 12:26:20.475  2996  3887 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at blb.a(PG:3937)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at czp.a(PG:18188)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:26:20.475  2996  3887 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	... 12 more
09-13 12:26:20.475  2996  3887 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at fal.a(PG:38)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:26:20.475  2996  3887 E HttpOperation: 	... 14 more
,09-13 12:26:20.509  1502  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:26:20.509  1502  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:26:20.509  1502  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:26:20.510  1502  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:20.524  2996  3887 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 12:26:20.524  2996  3887 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at hec.a(PG:42)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at hee.a(PG:102)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at czr.a(PG:65)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at kka.a(PG:108)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at czp.a(PG:19176)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:26:20.524  2996  3887 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	... 15 more
09-13 12:26:20.524  2996  3887 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at fal.a(PG:38)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:26:20.524  2996  3887 E HttpOperation: 	... 17 more
,09-13 12:26:20.524  2996  3887 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 12:26:20.524  2996  3887 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at hec.a(PG:42)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at hee.a(PG:102)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at czr.a(PG:65)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at kka.a(PG:108)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	... 15 more
09-13 12:26:20.524  2996  3887 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at fal.a(PG:38)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 12:26:20.524  2996  3887 E ExperimentLoader: 	... 17 more
,09-13 12:26:20.529  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 12:26:20.529  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 12:26:20.529  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:20.529  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:20.545  3035  3885 E KeepSync: IOException
09-13 12:26:20.545  3035  3885 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 12:26:20.545  3035  3885 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:26:20.545  3035  3885 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 12:26:20.545  3035  3885 E KeepSync: 	... 10 more
,09-13 12:26:20.546  3035  3885 W KeepSync: Sync result 2
,09-13 12:26:20.550   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 129977, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:26:20.605   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130694, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:26:20.719  1855  2650 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:26:22.997  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:22.997  3811  3861 I jxcore-log: 
,09-13 12:26:22.997  3811  3861 I jxcore-log: websocket error
09-13 12:26:22.997  3811  3861 I jxcore-log: 
09-13 12:26:22.997  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:22.997  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:22.997  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:22.997  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:22.997  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:22.997  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:22.997  3811  3861 I jxcore-log: 
,09-13 12:26:27.132   874  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-13 12:26:28.060  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:28.060  3811  3861 I jxcore-log: 
09-13 12:26:28.061  3811  3861 I jxcore-log: websocket error
09-13 12:26:28.061  3811  3861 I jxcore-log: 
,09-13 12:26:28.061  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:28.061  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:28.061  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:28.061  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:28.061  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:28.061  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:28.061  3811  3861 I jxcore-log: 
,09-13 12:26:33.137  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:33.137  3811  3861 I jxcore-log: 
,09-13 12:26:33.137  3811  3861 I jxcore-log: websocket error
09-13 12:26:33.137  3811  3861 I jxcore-log: 
09-13 12:26:33.137  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:33.137  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:33.137  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:33.137  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:33.137  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:33.137  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:33.137  3811  3861 I jxcore-log: 
,09-13 12:26:38.198  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:38.198  3811  3861 I jxcore-log: 
,09-13 12:26:38.199  3811  3861 I jxcore-log: websocket error
09-13 12:26:38.199  3811  3861 I jxcore-log: 
09-13 12:26:38.200  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:38.200  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:38.200  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:38.200  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:38.200  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:38.200  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:38.200  3811  3861 I jxcore-log: 
,09-13 12:26:43.273  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:43.273  3811  3861 I jxcore-log: 
09-13 12:26:43.273  3811  3861 I jxcore-log: websocket error
09-13 12:26:43.273  3811  3861 I jxcore-log: 
,09-13 12:26:43.273  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:43.273  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:43.273  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:43.273  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:43.273  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:43.273  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:43.273  3811  3861 I jxcore-log: 
,09-13 12:26:45.407   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=180944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:26:45.994  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:46.172  1502  3891 I VacuumService: Vacuum at: now=1473762406172 tag=VacuumService
,09-13 12:26:46.187  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:46.195  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:46.199  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:26:46.225  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:26:46.225  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 12:26:46.225  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:26:46.225  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:46.249  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 12:26:46.249  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 12:26:46.249  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 12:26:46.451  1502  3892 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 12:26:46.454  1502  3892 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:26:46.502  1502  3892 W Uploader:  no longer exists, so no auth token.
,09-13 12:26:48.301  1502  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 12:26:48.301  1502  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 12:26:48.301  1502  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:48.301  1502  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:48.320  1502  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:26:48.320  1502  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:26:48.320  1502  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:26:48.361  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:48.361  3811  3861 I jxcore-log: 
,09-13 12:26:48.361  3811  3861 I jxcore-log: websocket error
09-13 12:26:48.361  3811  3861 I jxcore-log: 
,09-13 12:26:48.361  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:48.361  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:48.361  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:48.361  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:48.361  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:48.361  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:48.361  3811  3861 I jxcore-log: 
,09-13 12:26:48.652  1502  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 12:26:48.652  1502  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 12:26:48.652  1502  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:48.653  1502  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:48.674  1502  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:26:48.674  1502  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:26:48.674  1502  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:26:49.376  1502  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 12:26:49.376  1502  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 12:26:49.376  1502  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:26:49.376  1502  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:49.402  1502  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:26:49.402  1502  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:26:49.402  1502  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:26:49.591  1502  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 12:26:49.591  1502  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-13 12:26:49.591  1502  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:26:49.592  1502  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:26:49.624  1502  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:26:49.624  1502  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:26:49.624  1502  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:26:50.994   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:26:53.440  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:53.440  3811  3861 I jxcore-log: 
,09-13 12:26:53.441  3811  3861 I jxcore-log: websocket error
09-13 12:26:53.441  3811  3861 I jxcore-log: 
09-13 12:26:53.441  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:53.441  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:53.441  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:53.441  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:53.441  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:53.441  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:53.441  3811  3861 I jxcore-log: 
,09-13 12:26:58.508  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:58.508  3811  3861 I jxcore-log: 
,09-13 12:26:58.509  3811  3861 I jxcore-log: websocket error
09-13 12:26:58.509  3811  3861 I jxcore-log: 
09-13 12:26:58.509  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:58.509  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:58.509  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:58.509  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:58.509  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:58.509  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:26:58.509  3811  3861 I jxcore-log: 
,09-13 12:27:03.570  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:03.570  3811  3861 I jxcore-log: 
,09-13 12:27:03.570  3811  3861 I jxcore-log: websocket error
09-13 12:27:03.570  3811  3861 I jxcore-log: 
09-13 12:27:03.570  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:03.570  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:03.570  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:03.570  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:03.570  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:03.570  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:03.570  3811  3861 I jxcore-log: 
,09-13 12:27:06.531  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:06.542  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:06.545  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:06.599  1502  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:27:06.600  1502  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 12:27:06.600  1502  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:27:06.601  1502  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:27:06.660  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 12:27:06.661  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 12:27:06.662  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 12:27:06.719   874   883 I art     : Background partial concurrent mark sweep GC freed 42735(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.170ms total 102.969ms
,09-13 12:27:08.658  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:08.658  3811  3861 I jxcore-log: 
,09-13 12:27:08.658  3811  3861 I jxcore-log: websocket error
09-13 12:27:08.658  3811  3861 I jxcore-log: 
09-13 12:27:08.658  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:08.658  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:08.658  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:08.658  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:08.658  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:08.658  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:08.658  3811  3861 I jxcore-log: 
,09-13 12:27:13.710  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:13.710  3811  3861 I jxcore-log: 
,09-13 12:27:13.710  3811  3861 I jxcore-log: websocket error
09-13 12:27:13.710  3811  3861 I jxcore-log: 
09-13 12:27:13.711  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:13.711  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:13.711  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:13.711  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:13.711  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:13.711  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:13.711  3811  3861 I jxcore-log: 
,09-13 12:27:14.666  1897  1980 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-13 12:27:14.667  1897  1980 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-13 12:27:14.720  1502  1502 I ConfigService: onCreate
,09-13 12:27:18.783  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:18.783  3811  3861 I jxcore-log: 
,09-13 12:27:18.784  3811  3861 I jxcore-log: websocket error
09-13 12:27:18.784  3811  3861 I jxcore-log: 
09-13 12:27:18.784  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:18.784  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:18.784  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:18.784  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:18.784  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:18.784  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:18.784  3811  3861 I jxcore-log: 
,09-13 12:27:19.800  1502  1502 I ConfigService: onDestroy
,09-13 12:27:22.434   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:27:23.850  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:23.850  3811  3861 I jxcore-log: 
,09-13 12:27:23.850  3811  3861 I jxcore-log: websocket error
09-13 12:27:23.850  3811  3861 I jxcore-log: 
09-13 12:27:23.851  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:23.851  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:23.851  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:23.851  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:23.851  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:23.851  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:23.851  3811  3861 I jxcore-log: 
,09-13 12:27:28.821   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=224357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 12:27:28.913  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:28.913  3811  3861 I jxcore-log: 
,09-13 12:27:28.913  3811  3861 I jxcore-log: websocket error
09-13 12:27:28.913  3811  3861 I jxcore-log: 
,09-13 12:27:28.914  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:28.914  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:28.914  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:28.914  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:28.914  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:28.914  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:28.914  3811  3861 I jxcore-log: 
,09-13 12:27:33.970  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:33.970  3811  3861 I jxcore-log: 
,09-13 12:27:33.970  3811  3861 I jxcore-log: websocket error
09-13 12:27:33.970  3811  3861 I jxcore-log: 
09-13 12:27:33.971  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:33.971  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:33.971  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:33.971  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:33.971  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:33.971  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:33.971  3811  3861 I jxcore-log: 
,09-13 12:27:39.033  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:39.033  3811  3861 I jxcore-log: 
,09-13 12:27:39.033  3811  3861 I jxcore-log: websocket error
09-13 12:27:39.033  3811  3861 I jxcore-log: 
,09-13 12:27:39.034  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:39.034  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:39.034  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:39.034  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:39.034  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:39.034  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:39.034  3811  3861 I jxcore-log: 
,09-13 12:27:44.092  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:44.092  3811  3861 I jxcore-log: 
09-13 12:27:44.092  3811  3861 I jxcore-log: websocket error
09-13 12:27:44.092  3811  3861 I jxcore-log: 
09-13 12:27:44.092  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:44.092  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:44.092  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:44.092  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:44.092  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:44.092  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:44.092  3811  3861 I jxcore-log: 
,09-13 12:27:49.145  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:49.145  3811  3861 I jxcore-log: 
09-13 12:27:49.145  3811  3861 I jxcore-log: websocket error
09-13 12:27:49.145  3811  3861 I jxcore-log: 
09-13 12:27:49.146  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:49.146  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:49.146  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:49.146  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:49.146  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:49.146  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:49.146  3811  3861 I jxcore-log: 
,09-13 12:27:51.472  3610  3911 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 12:27:51.514  3610  3912 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 12:27:51.537  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:51.542  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:51.599  1502  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 12:27:51.599  1502  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 12:27:51.599  1502  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:27:51.599  1502  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:27:51.626  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:51.629  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:27:51.657  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 12:27:51.658  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 12:27:51.658  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:27:51.658  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:27:51.674  3610  3912 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 12:27:51.675  3610  3911 E BooksSync: Soft error
09-13 12:27:51.675  3610  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:27:51.675  3610  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 12:27:51.675  3610  3911 E BooksSync: Sync error
09-13 12:27:51.675  3610  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:27:51.675  3610  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 12:27:51.675  3610  3911 I BooksSync: Finished books sync
,09-13 12:27:51.687   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246861, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:27:54.203  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:54.203  3811  3861 I jxcore-log: 
09-13 12:27:54.203  3811  3861 I jxcore-log: websocket error
09-13 12:27:54.203  3811  3861 I jxcore-log: 
,09-13 12:27:54.204  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:54.204  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:54.204  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:54.204  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:54.204  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:54.204  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:54.204  3811  3861 I jxcore-log: 
,09-13 12:27:59.266  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:59.266  3811  3861 I jxcore-log: 
09-13 12:27:59.266  3811  3861 I jxcore-log: websocket error
09-13 12:27:59.266  3811  3861 I jxcore-log: 
09-13 12:27:59.266  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:59.266  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:59.266  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:59.266  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:59.266  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:59.266  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:27:59.266  3811  3861 I jxcore-log: 
,09-13 12:28:01.474   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:28:04.320  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:04.320  3811  3861 I jxcore-log: 
,09-13 12:28:04.321  3811  3861 I jxcore-log: websocket error
09-13 12:28:04.321  3811  3861 I jxcore-log: 
09-13 12:28:04.321  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:04.321  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:04.321  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:04.321  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:04.321  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:04.321  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:04.321  3811  3861 I jxcore-log: 
,09-13 12:28:09.301   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 12:28:09.382  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:09.382  3811  3861 I jxcore-log: 
09-13 12:28:09.382  3811  3861 I jxcore-log: websocket error
09-13 12:28:09.382  3811  3861 I jxcore-log: 
09-13 12:28:09.382  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:09.382  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:09.382  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:09.382  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:09.382  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:09.382  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:09.382  3811  3861 I jxcore-log: 
,09-13 12:28:19.978  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:19.978  3811  3861 I jxcore-log: 
09-13 12:28:19.979  3811  3861 I jxcore-log: websocket error
09-13 12:28:19.979  3811  3861 I jxcore-log: 
09-13 12:28:19.980  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:19.980  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:19.980  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:19.980  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.980  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:19.980  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.980  3811  3861 I jxcore-log: 
,09-13 12:28:25.037  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:25.037  3811  3861 I jxcore-log: 
,09-13 12:28:25.037  3811  3861 I jxcore-log: websocket error
09-13 12:28:25.037  3811  3861 I jxcore-log: 
09-13 12:28:25.037  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:25.037  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:25.037  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:25.037  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:25.037  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:25.037  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:25.037  3811  3861 I jxcore-log: 
,09-13 12:28:29.266  3035  3918 V KeepSync: Connecting to GoogleApiClient
09-13 12:28:29.267   874  1397 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 12:28:29.303  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:28:29.305  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:28:29.323  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 12:28:29.324  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 12:28:29.324  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:28:29.324  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:28:29.337  1708  3919 V BaseAuthAsyncOperation: access token request failed
,09-13 12:28:29.338  3035  3918 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 12:28:29.375  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 12:28:29.376  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 12:28:29.376  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:28:29.376  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:28:29.390  3035  3918 E KeepSync: IOException
09-13 12:28:29.390  3035  3918 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 12:28:29.390  3035  3918 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:28:29.390  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 12:28:29.390  3035  3918 E KeepSync: 	... 10 more
,09-13 12:28:29.390  3035  3918 W KeepSync: Sync result 2
,09-13 12:28:29.399   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 284628, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:28:30.321  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:30.321  3811  3861 I jxcore-log: 
09-13 12:28:30.322  3811  3861 I jxcore-log: websocket error
09-13 12:28:30.322  3811  3861 I jxcore-log: 
09-13 12:28:30.323  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:30.323  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:30.323  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:30.323  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:30.323  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:30.323  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:30.323  3811  3861 I jxcore-log: 
,09-13 12:28:35.381  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:35.381  3811  3861 I jxcore-log: 
09-13 12:28:35.381  3811  3861 I jxcore-log: websocket error
09-13 12:28:35.381  3811  3861 I jxcore-log: 
,09-13 12:28:35.381  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:35.381  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:35.381  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:35.381  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:35.381  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:35.381  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:35.381  3811  3861 I jxcore-log: 
,09-13 12:28:40.445  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:40.445  3811  3861 I jxcore-log: 
,09-13 12:28:40.446  3811  3861 I jxcore-log: websocket error
09-13 12:28:40.446  3811  3861 I jxcore-log: 
09-13 12:28:40.447  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:40.447  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:40.447  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:40.447  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:40.447  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:40.447  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:40.447  3811  3861 I jxcore-log: 
,09-13 12:28:41.900   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:28:45.527  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:45.527  3811  3861 I jxcore-log: 
,09-13 12:28:45.527  3811  3861 I jxcore-log: websocket error
09-13 12:28:45.527  3811  3861 I jxcore-log: 
,09-13 12:28:45.528  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:45.528  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:45.528  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:45.528  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.528  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:45.528  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.528  3811  3861 I jxcore-log: 
,09-13 12:28:50.487   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 12:28:50.590  3811  3861 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:50.590  3811  3861 I jxcore-log: 
,09-13 12:28:50.590  3811  3861 I jxcore-log: websocket error
09-13 12:28:50.590  3811  3861 I jxcore-log: 
,09-13 12:28:50.590  3811  3861 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:50.590  3811  3861 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:50.590  3811  3861 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:50.590  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.590  3811  3861 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:50.590  3811  3861 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.590  3811  3861 I jxcore-log: 
,09-13 12:28:55.731  3811  3861 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 12:28:55.731  3811  3861 I jxcore-log: 
,09-13 12:28:55.768  3811  3861 I jxcore-log: ThaliTape :: Connected to the test server
09-13 12:28:55.768  3811  3861 I jxcore-log: 
,09-13 12:28:59.782  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:28:59.785  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:28:59.815  1502  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:28:59.815  1502  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:28:59.815  1502  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:28:59.816  1502  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:28:59.835  2996  3935 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 12:28:59.835  2996  3935 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at blb.a(PG:3937)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at czp.a(PG:18188)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:28:59.835  2996  3935 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	... 12 more
09-13 12:28:59.835  2996  3935 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at fal.a(PG:38)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:28:59.835  2996  3935 E HttpOperation: 	... 14 more
,09-13 12:28:59.921  1502  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:28:59.921  1502  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:28:59.921  1502  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:28:59.921  1502  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:28:59.941  2996  3935 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 12:28:59.941  2996  3935 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at hec.a(PG:42)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at hee.a(PG:102)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at czr.a(PG:65)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at kka.a(PG:108)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at czp.a(PG:19176)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:28:59.941  2996  3935 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	... 15 more
09-13 12:28:59.941  2996  3935 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at fal.a(PG:38)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:28:59.941  2996  3935 E HttpOperation: 	... 17 more
,09-13 12:28:59.942  2996  3935 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 12:28:59.942  2996  3935 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at hec.a(PG:42)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at hee.a(PG:102)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at czr.a(PG:65)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at kka.a(PG:108)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	... 15 more
09-13 12:28:59.942  2996  3935 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at fal.a(PG:38)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 12:28:59.942  2996  3935 E ExperimentLoader: 	... 17 more
,09-13 12:29:00.064   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286831, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:29:06.685  1502  2277 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:29:26.349  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:29:26.360  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:29:26.363  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:29:26.424  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 12:29:26.424  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 12:29:26.424  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:29:26.425  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:29:26.466  1502  2522 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 12:29:26.466  1502  2522 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 12:29:26.481  3535  3564 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:29:26.481  3535  3564 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 12:29:26.481  3535  3564 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 12:29:26.481  3535  3564 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 12:29:26.481  3535  3564 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 12:29:26.481  3535  3564 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 12:29:26.481  3535  3564 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 12:31:54.340  3610  3948 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 12:31:54.374  3610  3949 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 12:31:54.393  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:31:54.395  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:31:54.451  1502  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 12:31:54.452  1502  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 12:31:54.452  1502  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:31:54.452  1502  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:31:54.508  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:31:54.513  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:31:54.554  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 12:31:54.554  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 12:31:54.554  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:31:54.554  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:31:54.582  3610  3949 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 12:31:54.583  3610  3948 E BooksSync: Soft error
09-13 12:31:54.583  3610  3948 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:31:54.583  3610  3948 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 12:31:54.584  3610  3948 E BooksSync: Sync error
09-13 12:31:54.584  3610  3948 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:31:54.584  3610  3948 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 12:31:54.584  3610  3948 I BooksSync: Finished books sync
,09-13 12:31:54.600   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 489673, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:32:46.619  3035  3952 V KeepSync: Connecting to GoogleApiClient
,09-13 12:32:46.619   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 12:32:46.688  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:32:46.694  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:32:46.758  1502  2522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 12:32:46.758  1502  2522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 12:32:46.758  1502  2522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:32:46.758  1502  2522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:32:46.795  1708  3953 V BaseAuthAsyncOperation: access token request failed
,09-13 12:32:46.797  3035  3952 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 12:32:46.896  1502  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 12:32:46.896  1502  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 12:32:46.896  1502  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:32:46.897  1502  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:32:46.929  3035  3952 E KeepSync: IOException
09-13 12:32:46.929  3035  3952 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 12:32:46.929  3035  3952 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:32:46.929  3035  3952 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 12:32:46.929  3035  3952 E KeepSync: 	... 10 more
,09-13 12:32:46.929  3035  3952 W KeepSync: Sync result 2
,09-13 12:32:46.945   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 542017, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:33:21.749  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:33:21.754  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:33:21.797  1502  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:33:21.797  1502  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 12:33:21.797  1502  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:33:21.797  1502  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:33:21.827  2996  3957 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 12:33:21.827  2996  3957 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at blb.a(PG:3937)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at czp.a(PG:18188)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:33:21.827  2996  3957 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	... 12 more
09-13 12:33:21.827  2996  3957 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at fal.a(PG:38)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:33:21.827  2996  3957 E HttpOperation: 	... 14 more
,09-13 12:33:21.896  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:33:21.896  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:33:21.896  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:33:21.896  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:33:21.910  2996  3957 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 12:33:21.910  2996  3957 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at hec.a(PG:42)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at hee.a(PG:102)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at czr.a(PG:65)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at kka.a(PG:108)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at czp.a(PG:19176)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:33:21.910  2996  3957 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	... 15 more
09-13 12:33:21.910  2996  3957 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at fal.a(PG:38)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:33:21.910  2996  3957 E HttpOperation: 	... 17 more
09-13 12:33:21.911  2996  3957 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 12:33:21.911  2996  3957 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at hec.a(PG:42)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at hee.a(PG:102)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at czr.a(PG:65)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at kka.a(PG:108)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	... 15 more
09-13 12:33:21.911  2996  3957 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at fal.a(PG:38)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 12:33:21.911  2996  3957 E ExperimentLoader: 	... 17 more
,09-13 12:33:21.997   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 576978, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:38:23.900   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=879437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:38:38.727   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=894263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:38:49.367   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=904903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:39:04.220   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=919757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:39:14.487   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=930024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:39:29.301   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=944837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:39:39.553   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=955090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:39:54.380   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:40:04.620   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=980157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:40:19.447   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=994983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:40:29.687   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1005224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:40:44.501   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:40:54.727   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1030263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:41:09.554   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1045090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:41:19.793   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1055330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:41:34.620   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1070157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:41:44.834   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1080370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:41:59.700   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1095237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:42:09.927   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1105463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:42:24.754   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1120290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:42:34.993   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1130530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:42:49.820   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1145357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:43:00.246   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1155783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:43:15.087   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1170623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:43:25.314   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1180850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:43:40.140   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1195677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:43:50.167   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1205703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:43:50.974  1708  3988 I EventLogService: Opted in for usage reporting
,09-13 12:43:50.975  1708  3988 I EventLogService: Aggregate from 1473761630738 (log), 1473761630738 (data)
,09-13 12:43:51.000  1708  1708 I GCM     : Message from null null
,09-13 12:43:51.001  1708  1708 E GCM     : Dropping message from null
,09-13 12:43:51.048  1708  3988 W EventLogAggregator: Unknown tag: snet_gcore
,09-13 12:43:51.048  1708  3988 W EventLogAggregator: Unknown tag: snet_launch_service
,09-13 12:43:51.105  1708  3988 I ServiceDumpSys: dumping service [account]
,09-13 12:43:55.927   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1211464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:44:02.491   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 12:44:15.234   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1230771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:44:30.260   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:44:40.300   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1255837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:44:55.340   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:45:05.367   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1280903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:45:20.407   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:45:30.433   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1305970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:45:45.460   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:45:55.501   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1331037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:46:10.514   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1346050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:46:20.540   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1356077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:46:35.580   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1371117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:46:45.607   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1381143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:47:00.647   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1396183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:47:10.673   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1406210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:47:25.713   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1421250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:47:35.740   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1431277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:47:50.780   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1446317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:48:00.807   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:48:15.834   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1471370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:48:25.873   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1481410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:48:40.940   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1496477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:48:44.193   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1499730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 12:49:06.034   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:49:09.253   874  2101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1524790, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-13 12:49:10.426  4008  4008 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:49:10.431  4008  4008 D AndroidRuntime: CheckJNI is OFF
09-13 12:49:10.473  4008  4008 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:49:10.520  4008  4008 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:49:10.542  4008  4008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 12:49:10.551   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-13 12:49:10.552   874   887 I ActivityManager: Killing 3811:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-13 12:49:10.676   874  2004 D GraphicsStats: Buffer count: 2
09-13 12:49:10.678   874  1677 I WindowState: WIN DEATH: Window{e5766e2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 12:49:10.678   874  1312 D WifiService: Client connection lost with reason: 4
09-13 12:49:10.685   874   897 W PackageSettings: Skipping PackageSetting{e22803 com.example.hello/10273} due to missing metadata
09-13 12:49:10.717   874   897 I art     : Starting a blocking GC Explicit
09-13 12:49:10.773   874   887 E libprocessgroup: failed to kill 1 processes for processgroup 3811
09-13 12:49:10.773   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 12:49:10.773   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 12:49:10.774   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 12:49:10.774   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 12:49:10.774   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:10.774   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:10.774   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:10.774   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:49:10.775   874   887 I ActivityManager:   Force finishing activity ActivityRecord{c265f1b u0 com.test.thalitest/.MainActivity t4}
09-13 12:49:10.790   874  2028 W ActivityManager: Spurious death for ProcessRecord{bae6afe 0:com.test.thalitest/u0a0}, curProc for 3811: null
09-13 12:49:10.789   874   897 I art     : Explicit concurrent mark sweep GC freed 42702(3MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 29MB/43MB, paused 1.002ms total 71.484ms
09-13 12:49:10.822   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 12:49:10.827   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-13 12:49:10.829  4008  4008 I art     : System.exit called, status: 0
09-13 12:49:10.829  4008  4008 I AndroidRuntime: VM exiting with result code 0.
09-13 12:49:10.850   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-13 12:49:10.855   874  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 12:49:10.856  1855  2250 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 12:49:10.859  2713  2713 D BluetoothMapAppObserver: onReceive
09-13 12:49:10.859  2713  2713 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 12:49:10.864  3679  3679 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-13 12:49:10.865  1897  1897 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 12:49:10.869  1897  4023 I Keyboard.Facilitator.DecoderInitializer: run()
09-13 12:49:10.870  1897  4023 I Decoder : createOrResetDecoder
09-13 12:49:10.897  2013  2013 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 12:49:10.923  3517  4025 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 12:49:10.938  1502  1502 I ConfigService: onCreate
09-13 12:49:10.956  1502  1502 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-13 12:49:10.956  1502  1502 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-13 12:49:10.960  1897  4023 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-13 12:49:10.963   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 12:49:10.969  3517  4025 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-13 12:49:10.970  3517  4025 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 12:49:10.970  3517  4025 E AndroidRuntime: Process: android.process.acore, PID: 3517
09-13 12:49:10.970  3517  4025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:10.970  3517  4025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:10.974  2029  2136 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 12:49:10.977   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 12:49:10.978   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 12:49:10.978   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 12:49:10.978   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 12:49:10.978   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 12:49:10.978   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 12:49:10.978   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 12:49:10.978   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:10.978   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:10.978   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:49:10.980   874  4030 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:49:10.980   874  4030 E DropBoxManagerService: 	... 5 more
09-13 12:49:10.980   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 12:49:10.980   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:49:10.980   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:49:10.980   874   887 E DropBoxManagerService: 	... 13 more
09-13 12:49:10.987   874   884 I ActivityManager: Start proc 4031:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-13 12:49:10.988  2029  2136 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 12:49:10.988  2029  2136 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2029
09-13 12:49:10.988  2029  2136 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:10.988  2029  2136 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:10.991   874  1949 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 12:49:10.992   874  4037 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:49:10.992   874  4037 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:49:10.992   874  4037 E DropBoxManagerService: 	... 5 more
09-13 12:49:10.995  2029  2136 I Process : Sending signal. PID: 2029 SIG: 9
09-13 12:49:11.005  3517  4025 I Process : Sending signal. PID: 3517 SIG: 9
09-13 12:49:11.026  1708  4044 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 12:49:11.026  1708  4044 D AccountUtils: Clearing selected account for com.test.thalitest
09-13 12:49:11.035  1897  4023 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-13 12:49:11.036  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 12:49:11.036  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-13 12:49:11.038  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-13 12:49:11.038  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 12:49:11.039  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 12:49:11.039  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 12:49:11.041  1897  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 12:49:11.041  1897  4023 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 12:49:11.041  1897  4023 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 12:49:11.041  1897  4023 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 12:49:11.041  1897  4023 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 12:49:11.041  1897  4023 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-13 12:49:11.052   874  2004 I ActivityManager: Process android.process.acore (pid 3517) has died
09-13 12:49:11.052   874  2004 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-13 12:49:11.055  1708  4044 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.071  1708  4044 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.071  1708  4044 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:11.072  1708  4044 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
09-13 12:49:11.077   874  1678 D GraphicsStats: Buffer count: 1
09-13 12:49:11.077   874  1951 I WindowState: WIN DEATH: Window{c597833 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 12:49:11.088   874  2004 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2029) has died
09-13 12:49:11.089   874  2004 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 12:49:11.112  1708  4051 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 12:49:11.112  1708  4051 E DriveAsyncService: disk I/O error (code 3850)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:49:11.112  1708  4051 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:49:11.116  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 12:49:11.116  1708  1708 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 12:49:11.123  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 12:49:11.123  1708  1708 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 12:49:11.143  1708  4055 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.147  1708  4052 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.147  1708  4052 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:11.150  2096  4056 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 12:49:11.158   874  1677 I ActivityManager: Start proc 4059:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
09-13 12:49:11.177  1708  1708 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 12:49:11.177  1708  2523 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
09-13 12:49:11.202  1708  4055 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-13 12:49:11.202  1708  4055 E AndroidRuntime: Process: com.google.android.gms, PID: 1708
09-13 12:49:11.202  1708  4055 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:49:11.202  1708  4055 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:49:11.205   874  4073 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:49:11.205   874  4073 E DropBoxManagerService: 	... 5 more
09-13 12:49:11.206  1708  1708 I ConfigFetchService: service connected
09-13 12:49:11.208  1708  4052 W SQLiteOpenHelper: Opened metrics.db in read-only mode
09-13 12:49:11.209  1708  4052 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
09-13 12:49:11.209  1708  4052 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
09-13 12:49:11.216  1708  4055 I Process : Sending signal. PID: 1708 SIG: 9
09-13 12:49:11.224  4031  4031 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2456)
09-13 12:49:11.242  2096  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 12:49:11.257   874  2027 I ActivityManager: Delaying start of: ServiceRecord{18ef582 u0 com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService}
09-13 12:49:11.261  2096  4056 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
09-13 12:49:11.262  2096  4056 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-13 12:49:11.262  2096  4056 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2096
09-13 12:49:11.262  2096  4056 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.262  2096  4056 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:49:11.263   874  1677 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
09-13 12:49:11.264   874  1677 I ActivityManager: Killing 2096:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
09-13 12:49:11.268   874  4076 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:49:11.268   874  4076 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:49:11.268   874  4076 E DropBoxManagerService: 	... 5 more
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:49:11.308  4059  4059 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:49:11.308  4059  4059 D AndroidRuntime: Shutting down VM

```
