#### Test 82642184ea62b6e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 23:11:03.786  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:03.806  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 23:11:03.813  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 23:11:03.909  1494  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 23:11:03.909  1494  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 23:11:03.909  1494  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 23:11:03.909  1494  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 23:11:03.924  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 23:11:03.924  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 23:11:03.925  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 23:11:04.421  3915  3915 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 23:11:04.426  3915  3915 D AndroidRuntime: CheckJNI is OFF
08-30 23:11:04.468  3915  3915 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 23:11:04.520  3915  3915 I Radio-JNI: register_android_hardware_Radio DONE
08-30 23:11:04.543  3915  3915 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 23:11:04.547   872  1385 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 23:11:04.582  2093  2408 W SearchService: Abort, client detached.
08-30 23:11:04.588  2093  2093 I HotwordDetector: Closing mic
08-30 23:11:04.589  2093  2296 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4c62b7c
08-30 23:11:04.591  2093  2304 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 23:11:04.626  3915  3915 D AndroidRuntime: Shutting down VM
08-30 23:11:04.662   872  2059 I ActivityManager: Start proc 3925:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 23:11:04.669   376  2306 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 23:11:04.673   376  2306 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 23:11:04.693   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 23:11:04.696  2093  2303 I MicroRecognitionRnrImpl: Detection finished
08-30 23:11:04.696  2093  2302 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 23:11:04.748  3925  3925 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 23:11:04.771  3925  3925 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 23:11:04.778  3925  3925 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2293-2296)
08-30 23:11:04.778  3925  3925 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:11:04.791  3925  3925 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c581aa}
08-30 23:11:04.791  3925  3925 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:11:04.791  3925  3925 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 23:11:04.806  3925  3925 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 23:11:04.810  3925  3925 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 23:11:04.824  3925  3925 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 23:11:04.834  3925  3925 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:11:04.834  3925  3925 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:11:04.835  3925  3925 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 23:11:04.835  3925  3925 I Adreno  : Build Date                       : 10/20/15
08-30 23:11:04.835  3925  3925 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 23:11:04.835  3925  3925 I Adreno  : Local Branch                     : M14
08-30 23:11:04.835  3925  3925 I Adreno  : Remote Branch                    : 
08-30 23:11:04.835  3925  3925 I Adreno  : Remote Branch                    : 
08-30 23:11:04.835  3925  3925 I Adreno  : Reconstruct Branch               : 
,08-30 23:11:04.882   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f282f31:true
,08-30 23:11:04.922  3925  3925 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 23:11:04.934  3925  3925 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 23:11:04.996  3925  3963 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 23:11:05.005  3925  3950 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 23:11:05.026  3925  3963 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 23:11:05.106   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +478ms
,08-30 23:11:05.110  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-30 23:11:05.183  3925  3925 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3925
,08-30 23:11:05.350  3925  3925 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 23:11:05.448  3925  3966 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1697973968
,08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 23:11:05.456  3925  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e8b09 added. We now have 1 listener(s)
,08-30 23:11:05.458   872  3048 I ActivityManager: Killing 3178:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 23:11:05.460  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 23:11:05.462  3925  3966 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 23:11:05.462  3925  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 23:11:05.462  3925  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 23:11:05.466  3925  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cac113c added. We now have 1 listener(s)
08-30 23:11:05.466  3925  3966 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 23:11:05.470   872  1307 D WifiService: New client listening to asynchronous messages
,08-30 23:11:05.471  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 23:11:05.471  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 23:11:05.471  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:11:05.471  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 23:11:05.472  3925  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 23:11:05.495   872  3048 I ActivityManager: Killing 3537:com.google.process.gapps/u0a99 (adj 15): empty #18
,08-30 23:11:05.545  3925  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 23:11:05.546  3925  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 23:11:05.559  3925  3966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:05.559  3925  3966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 23:11:05.559  3925  3966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:11:05.559  3925  3966 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 23:11:05.560  3925  3966 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 23:11:05.625  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:11:05.627  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:11:05.631  3925  3925 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 23:11:05.769   872  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 23:11:06.557  3925  3975 W jxcore-log: Initializing JXcore engine
,08-30 23:11:06.557  3925  3975 W jxcore-log: JXcore engine is ready
,08-30 23:11:06.590  3975  3975 W Thread-357: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 23:11:06.590  3975  3975 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13097]" dev="sockfs" ino=13097 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 23:11:06.590  3975  3975 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 23:11:06.590  3975  3975 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27795]" dev="sockfs" ino=27795 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 23:11:06.606  3925  3975 W jxcore-log: Starting JXcore engine
,08-30 23:11:06.699  3925  3975 W jxcore-log: Platform android
08-30 23:11:06.699  3925  3975 W jxcore-log: 
,08-30 23:11:06.699  3925  3975 W jxcore-log: Process ARCH arm
08-30 23:11:06.699  3925  3975 W jxcore-log: 
,08-30 23:11:06.904  3925  3975 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:11:06.904  3925  3975 I jxcore-log: 
,08-30 23:11:06.904  3925  3975 W jxcore-log: JXcore engine is started
,08-30 23:11:06.910  3925  3966 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 23:11:06.914  3925  3925 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 23:11:09.343  3702  3977 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 23:11:09.367  3702  3978 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 23:11:09.383  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:09.388  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:09.424  1494  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 23:11:09.424  1494  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 23:11:09.424  1494  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 23:11:09.424  1494  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 23:11:09.461  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:09.466  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:09.503  1494  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 23:11:09.503  1494  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 23:11:09.503  1494  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 23:11:09.504  1494  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 23:11:09.531  3702  3978 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 23:11:09.533  3702  3977 E BooksSync: Soft error
08-30 23:11:09.533  3702  3977 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 23:11:09.533  3702  3977 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 23:11:09.533  3702  3977 E BooksSync: Sync error
08-30 23:11:09.533  3702  3977 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 23:11:09.533  3702  3977 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 23:11:09.533  3702  3977 I BooksSync: Finished books sync
,08-30 23:11:09.543   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125401, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 23:11:21.620  3925  3975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 23:11:21.620  3925  3975 I jxcore-log: 
,08-30 23:11:21.623  3925  3975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 23:11:21.623  3925  3975 I jxcore-log: 
,08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:21.635  3925  3975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 23:11:21.641  3925  3975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 23:11:21.647  3925  3975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:11:21.647  3925  3975 I jxcore-log: 
,08-30 23:11:21.654  3925  3975 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:11:21.654  3925  3975 I jxcore-log: 
,08-30 23:11:22.111  3925  3975 I jxcore-log: Running unit tests
08-30 23:11:22.111  3925  3975 I jxcore-log: 
,08-30 23:11:22.112  3925  3975 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:11:22.112  3925  3975 I jxcore-log: Failed to execute UT.
08-30 23:11:22.112  3925  3975 I jxcore-log: 
,08-30 23:11:22.114  3925  3975 I jxcore-log: Unit Test app is loaded
08-30 23:11:22.114  3925  3975 I jxcore-log: 
,08-30 23:11:22.119  3925  3975 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 23:11:22.119  3925  3975 I jxcore-log: 
,08-30 23:11:22.124  3925  3975 I jxcore-log: My device name is: motorola-Nexus 6
08-30 23:11:22.124  3925  3975 I jxcore-log: 
,08-30 23:11:22.126  3925  3975 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 23:11:22.126  3925  3975 I jxcore-log: 
,08-30 23:11:22.138  3925  3925 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 23:11:23.561   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 23:11:24.109  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:24.116  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 23:11:24.118  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 23:11:24.157  1494  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 23:11:24.158  1494  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 23:11:24.159  1494  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 23:11:24.160  1494  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 23:11:24.183  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 23:11:24.184  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 23:11:24.184  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 23:11:24.679  3925  3975 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 23:11:24.679  3925  3975 I jxcore-log: 
,08-30 23:11:25.154  3925  3975 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 23:11:25.154  3925  3975 I jxcore-log: 
,08-30 23:11:25.179  3925  3975 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 23:11:25.179  3925  3975 I jxcore-log: 
,08-30 23:11:26.574   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 23:11:26.660  3925  3975 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 23:11:26.660  3925  3975 I jxcore-log: 
,08-30 23:11:26.906  3925  3975 I jxcore-log: ERROR runTests: 
08-30 23:11:26.906  3925  3975 I jxcore-log: 
,08-30 23:11:26.909  3925  3975 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:26.909  3925  3975 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 23:11:26.910  3925  3975 I jxcore-log: WARN testUtils: logCallback not set!
08-30 23:11:26.910  3925  3975 I jxcore-log: 
,08-30 23:11:26.921  3925  3975 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-30 23:11:26.921  3925  3975 I jxcore-log:     _functionName: 'loadFile',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _lineNumber: '26',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _columnNumber: '11',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 23:11:26.921  3925  3975 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _functionName: '',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _lineNumber: '38',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _columnNumber: '7',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:11:26.921  3925  3975 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _functionName: '',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _lineNumber: '35',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _columnNumber: '3',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:11:26.921  3925  3975 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _lineNumber: '621',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _columnNumber: '8',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:11:26.921  3925  3975 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _lineNumber: '651',
08-30 23:11:26.921  3925  3975 I jxcore-log:     _columnNumber: '1',
08-30 23:11:26.921  3925  3975 I jxcore-log:    
,08-30 23:11:26.921  3925  3975 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:11:26.921  3925  3975 I jxcore-log: 
,08-30 23:11:26.922  3925  3975 E jxcore-log: Error: 
08-30 23:11:26.922  3925  3975 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:26.922  3925  3975 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 23:11:26.922  3925  3975 E jxcore-log: 
,08-30 23:11:27.552  3989  3989 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 23:11:27.557  3989  3989 D AndroidRuntime: CheckJNI is OFF
,08-30 23:11:27.599  3989  3989 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 23:11:27.647  3989  3989 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 23:11:27.670  3989  3989 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 23:11:27.679   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-30 23:11:27.681   872   885 I ActivityManager: Killing 3925:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 23:11:27.796   872   895 W PackageSettings: Skipping PackageSetting{976b021 com.example.hello/10273} due to missing metadata
,08-30 23:11:27.812   872  3817 D GraphicsStats: Buffer count: 2
08-30 23:11:27.812   872  1683 I WindowState: WIN DEATH: Window{77246a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:11:27.813   872  1307 D WifiService: Client connection lost with reason: 4
,08-30 23:11:27.830   872   895 I art     : Starting a blocking GC Explicit
,08-30 23:11:27.857   872   885 W ActivityManager: Force removing ActivityRecord{3ae148e u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-30 23:11:27.871   872   882 W ActivityManager: Spurious death for ProcessRecord{7994eb0 0:com.test.thalitest/u0a0}, curProc for 3925: null
,08-30 23:11:27.885   872   895 I art     : Explicit concurrent mark sweep GC freed 43197(2MB) AllocSpace objects, 15(384KB) LOS objects, 33% free, 29MB/43MB, paused 1.769ms total 52.017ms
,08-30 23:11:27.897   872  3048 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3925 uid 10000
,08-30 23:11:27.898  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-30 23:11:27.904   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 23:11:27.907  3989  3989 I art     : System.exit called, status: 0
,08-30 23:11:27.907  3989  3989 I AndroidRuntime: VM exiting with result code 0.
,08-30 23:11:27.910   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 23:11:27.922  2613  2613 D BluetoothMapAppObserver: onReceive
08-30 23:11:27.922  2613  2613 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 23:11:27.928   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 23:11:27.931  3770  3770 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 23:11:27.936  1856  2216 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 23:11:27.937  1894  1894 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 23:11:27.944  1894  4002 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 23:11:27.948  1894  4002 I Decoder : createOrResetDecoder
,08-30 23:11:27.993  2011  2011 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 23:11:28.001  3479  4007 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 23:11:28.005  1494  1494 I ConfigService: onCreate
,08-30 23:11:28.014  2093  4010 I MicroRecognitionRnrImpl: Starting detection.
08-30 23:11:28.015  2093  4011 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@465bfa
,08-30 23:11:28.018   376  4013 I AudioFlinger: AudioFlinger's thread 0xb1c40000 ready to run
,08-30 23:11:28.024   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-30 23:11:28.030  2093  4011 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@465bfa
08-30 23:11:28.031  1494  1494 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 23:11:28.031  1494  1494 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-30 23:11:28.032  1494  1494 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:11:28.032  1494  1494 E AndroidRuntime: Process: com.google.process.gapps, PID: 1494
08-30 23:11:28.032  1494  1494 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 23:11:28.032  1494  1494 E AndroidRuntime: 	... 8 more
,08-30 23:11:28.036   376  4013 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-30 23:11:28.036   376  4013 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-30 23:11:28.036   376  4013 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-30 23:11:28.039  1894  4002 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-30 23:11:28.046   376  4013 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
08-30 23:11:28.060   872  4015 E DropBoxManagerService: Can't write: system_app_crash
08-30 23:11:28.060   872  4015 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-30 23:11:28.060   872  4015 E DropBoxManagerService: 	... 8 more
08-30 23:11:28.064   872  4016 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 23:11:28.069   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 23:11:28.081  3479  4007 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-30 23:11:28.082  3479  4007 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 23:11:28.082  3479  4007 E AndroidRuntime: Process: android.process.acore, PID: 3479
08-30 23:11:28.082  3479  4007 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 23:11:28.082  3479  4007 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 23:11:28.086  1894  4002 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 23:11:28.088   872  4016 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 23:11:28.088   872  4016 I Adreno  : Build Date                       : 10/20/15
08-30 23:11:28.088   872  4016 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 23:11:28.088   872  4016 I Adreno  : Local Branch                     : M14
08-30 23:11:28.088   872  4016 I Adreno  : Remote Branch                    : 
08-30 23:11:28.088   872  4016 I Adreno  : Remote Branch                    : 
08-30 23:11:28.088   872  4016 I Adreno  : Reconstruct Branch               : 
,08-30 23:11:28.090  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 23:11:28.090  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 23:11:28.095   872  4016 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 23:11:28.096   872  4018 E DropBoxManagerService: Can't write: system_app_crash
08-30 23:11:28.096   872  4018 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 23:11:28.096   872  4018 E DropBoxManagerService: 	... 5 more
,08-30 23:11:28.098  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 23:11:28.099  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 23:11:28.099  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 23:11:28.100  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-30 23:11:28.101  1894  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 23:11:28.104  1894  4002 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 23:11:28.104  1894  4002 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-30 23:11:28.105  1894  4002 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 23:11:28.105  1894  4002 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 23:11:28.105  1894  4002 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 23:11:28.120  2093  2093 I HotwordWorkerImpl: onReady
,08-30 23:11:28.194   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 23:11:28.194  2030  2117 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 23:11:28.194   872   884 E PackageManager: Failed to write settings, restoring backup
08-30 23:11:28.194   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 23:11:28.194   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 23:11:28.194   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 23:11:28.194   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 23:11:28.194   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 23:11:28.194   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:28.194   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 23:11:28.194   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 23:11:28.198   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-30 23:11:28.198   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 23:11:28.198   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 23:11:28.198   872   885 E DropBoxManagerService: 	... 13 more
,08-30 23:11:28.206  2093  2093 I HotwordDetector: Closing mic
,08-30 23:11:28.207  2093  2296 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@465bfa
08-30 23:11:28.207  2093  4011 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-30 23:11:28.216   872  1935 I ActivityManager: Start proc 4022:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 23:11:28.216  2030  2117 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 23:11:28.216  2030  2117 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2030
08-30 23:11:28.216  2030  2117 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 23:11:28.216  2030  2117 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 23:11:28.240   872  2027 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 23:11:28.243   872  4034 E DropBoxManagerService: Can't write: system_app_crash
08-30 23:11:28.243   872  4034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 23:11:28.243   872  4034 E DropBoxManagerService: 	... 5 more
,08-30 23:11:28.254  2093  4035 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-30 23:11:28.266   376  4013 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-30 23:11:28.268   376  4013 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-30 23:11:28.274   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 23:11:28.280  2093  4010 I MicroRecognitionRnrImpl: Detection finished
08-30 23:11:28.280  2093  2302 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-30 23:11:28.312   872  2029 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 23:11:28.325  2030  2030 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@c5094d new=com.google.android.velvet.VelvetApplication@c5094d
,08-30 23:11:28.368  1708  4041 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 23:11:28.369  1708  4041 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 23:11:28.375  2030  2030 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-30 23:11:28.437   872   890 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +121ms
,08-30 23:11:28.439   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-30 23:11:28.439   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-30 23:11:28.439   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-30 23:11:28.439   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-30 23:11:28.439   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-30 23:11:28.439   281   281 E qdoverlay: MdpCtrl close error in unset
,08-30 23:11:28.701   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 23:11:28.702   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-30 23:11:28.702   281   281 E qdoverlay: MdpCtrl close error in unset

```
