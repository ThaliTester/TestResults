#### Test 721454319a152ff_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-05 15:08:38.976   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:08:39.700  3731  3731 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:08:39.705  3731  3731 D AndroidRuntime: CheckJNI is OFF
07-05 15:08:39.740  3731  3731 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:08:39.782  3731  3731 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:08:39.803  3731  3731 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 15:08:39.808   874  1757 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 15:08:39.859   874  1757 I ActivityManager: Start proc 3740:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-05 15:08:39.868  3731  3731 D AndroidRuntime: Shutting down VM
07-05 15:08:40.061  3740  3740 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-05 15:08:40.098  3740  3740 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-05 15:08:40.108  3740  3740 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8579-8583)
07-05 15:08:40.108  3740  3740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 15:08:40.127  3740  3740 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cd383}
,07-05 15:08:40.128  3740  3740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 15:08:40.129  3740  3740 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 15:08:40.137  3740  3740 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 15:08:40.138  3740  3740 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 15:08:40.158  3740  3740 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 15:08:40.172  3740  3740 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 15:08:40.172  3740  3740 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 15:08:40.172  3740  3740 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 15:08:40.172  3740  3740 I Adreno  : Build Date                       : 10/20/15
07-05 15:08:40.172  3740  3740 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 15:08:40.172  3740  3740 I Adreno  : Local Branch                     : M14
07-05 15:08:40.172  3740  3740 I Adreno  : Remote Branch                    : 
07-05 15:08:40.172  3740  3740 I Adreno  : Remote Branch                    : 
07-05 15:08:40.172  3740  3740 I Adreno  : Reconstruct Branch               : 
,07-05 15:08:40.259   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@da1dad4:true
,07-05 15:08:40.303  3740  3740 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 15:08:40.320  3740  3740 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-05 15:08:40.422  3740  3777 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 15:08:40.467  3740  3764 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-05 15:08:40.538  3740  3777 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 15:08:40.719   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +739ms (total +877ms)
,07-05 15:08:40.723  3740  3740 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3740
,07-05 15:08:40.729  1654  1654 I Keyboard.Facilitator: onFinishInput()
,07-05 15:08:40.786  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:40.788  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:40.797  3701  3783 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:08:40.807  3740  3740 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 15:08:40.822  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:08:40.822  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:08:40.822  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:08:40.822  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:08:40.842  3701  3783 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:08:40.843  3701  3783 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:08:41.008  3740  3779 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1665578704
,07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 15:08:41.016  3740  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a95b16 added. We now have 1 listener(s)
,07-05 15:08:41.019  3740  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-05 15:08:41.020  3740  3779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-05 15:08:41.020  3740  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 15:08:41.020  3740  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 15:08:41.025  3740  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@463b66d added. We now have 1 listener(s)
07-05 15:08:41.025  3740  3779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 15:08:41.030   874  1306 D WifiService: New client listening to asynchronous messages
,07-05 15:08:41.031  3740  3779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 15:08:41.032  3740  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 15:08:41.032  3740  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 15:08:41.032  3740  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 15:08:41.032  3740  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 15:08:41.035  3740  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 15:08:41.035  3740  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:08:41.047  3740  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 15:08:41.047  3740  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-05 15:08:41.047  3740  3779 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 15:08:41.048  3740  3779 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 15:08:41.049  3740  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 15:08:41.053  3740  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 15:08:41.070  3740  3740 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 15:08:41.573  3740  3749 I art     : Background sticky concurrent mark sweep GC freed 69926(6MB) AllocSpace objects, 17(1584KB) LOS objects, 31% free, 22MB/32MB, paused 689us total 107.395ms
,07-05 15:08:42.521  3740  3787 W jxcore-log: Initializing JXcore engine
,07-05 15:08:42.521  3740  3787 W jxcore-log: JXcore engine is ready
,07-05 15:08:42.557  3787  3787 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8838 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-05 15:08:42.561  3787  3787 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11235]" dev="sockfs" ino=11235 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 15:08:42.561  3787  3787 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-05 15:08:42.561  3787  3787 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24940]" dev="sockfs" ino=24940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 15:08:42.572  3740  3787 W jxcore-log: Starting JXcore engine
,07-05 15:08:42.652  3740  3787 W jxcore-log: Platform android
07-05 15:08:42.652  3740  3787 W jxcore-log: 
,07-05 15:08:42.652  3740  3787 W jxcore-log: Process ARCH arm
07-05 15:08:42.652  3740  3787 W jxcore-log: 
,07-05 15:08:42.848  3740  3787 I jxcore-log: JXcore Cordova bridge is ready!
07-05 15:08:42.848  3740  3787 I jxcore-log: 
,07-05 15:08:42.848  3740  3787 W jxcore-log: JXcore engine is started
,07-05 15:08:42.859  3740  3779 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 15:08:42.865  3740  3740 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 15:08:50.778  3470  3789 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:08:50.797  3470  3790 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:08:50.818  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:50.821  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:50.849  1487  2004 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 15:08:50.849  1487  2004 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 15:08:50.850  1487  2004 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:08:50.850  1487  2004 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:08:50.887  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:50.890  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:08:50.924  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:08:50.924  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:08:50.925  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:08:50.925  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:08:50.947  3470  3790 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:08:50.949  3470  3789 E BooksSync: Soft error
07-05 15:08:50.949  3470  3789 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:08:50.949  3470  3789 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:08:50.949  3470  3789 E BooksSync: Sync error
07-05 15:08:50.949  3470  3789 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:08:50.949  3470  3789 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:08:50.950  3470  3789 I BooksSync: Finished books sync
07-05 15:08:50.960   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279210, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:08:52.673  3740  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 15:08:52.673  3740  3787 I jxcore-log: 
,07-05 15:08:52.676  3740  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 15:08:52.676  3740  3787 I jxcore-log: 
,07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:08:52.688  3740  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 15:08:52.693  3740  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 15:08:52.695  3740  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 15:08:52.695  3740  3787 I jxcore-log: 
,07-05 15:08:52.697  3740  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 15:08:52.697  3740  3787 I jxcore-log: 
,07-05 15:08:53.065  3740  3787 I jxcore-log: Unit Test app is loaded
07-05 15:08:53.065  3740  3787 I jxcore-log: 
,07-05 15:08:53.070  3740  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 15:08:53.070  3740  3787 I jxcore-log: 
,07-05 15:08:53.075  3740  3787 I jxcore-log: My device name is: motorola-Nexus 6
07-05 15:08:53.075  3740  3787 I jxcore-log: 
,07-05 15:08:53.077  3740  3787 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 15:08:53.077  3740  3787 I jxcore-log: 
,07-05 15:08:53.092  3740  3740 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 15:08:56.906  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 15:08:56.906  3740  3787 I jxcore-log: 
,07-05 15:08:57.307  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 15:08:57.307  3740  3787 I jxcore-log: 
,07-05 15:08:57.333  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 15:08:57.333  3740  3787 I jxcore-log: 
,07-05 15:08:57.338  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 15:08:57.338  3740  3787 I jxcore-log: 
,07-05 15:08:57.354  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 15:08:57.354  3740  3787 I jxcore-log: 
,07-05 15:08:57.359  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 15:08:57.359  3740  3787 I jxcore-log: 
,07-05 15:08:59.302  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 15:08:59.302  3740  3787 I jxcore-log: 
,07-05 15:08:59.314  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 15:08:59.314  3740  3787 I jxcore-log: 
,07-05 15:08:59.323  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 15:08:59.323  3740  3787 I jxcore-log: 
,07-05 15:08:59.478  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 15:08:59.478  3740  3787 I jxcore-log: 
,07-05 15:08:59.559  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 15:08:59.559  3740  3787 I jxcore-log: 
,07-05 15:08:59.615  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 15:08:59.615  3740  3787 I jxcore-log: 
,07-05 15:08:59.622  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 15:08:59.622  3740  3787 I jxcore-log: 
,07-05 15:08:59.813  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 15:08:59.813  3740  3787 I jxcore-log: 
,07-05 15:08:59.834  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 15:08:59.834  3740  3787 I jxcore-log: 
,07-05 15:08:59.839  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 15:08:59.839  3740  3787 I jxcore-log: 
,07-05 15:08:59.845  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 15:08:59.845  3740  3787 I jxcore-log: 
,07-05 15:08:59.861  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 15:08:59.861  3740  3787 I jxcore-log: 
,07-05 15:08:59.880  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 15:08:59.880  3740  3787 I jxcore-log: 
,07-05 15:08:59.964  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 15:08:59.964  3740  3787 I jxcore-log: 
,07-05 15:08:59.970  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 15:08:59.970  3740  3787 I jxcore-log: 
,07-05 15:08:59.996  3740  3787 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 15:08:59.996  3740  3787 I jxcore-log: 
,07-05 15:09:00.011  3740  3787 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-05 15:09:00.012  3740  3787 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 15:09:00.012  3740  3787 I jxcore-log: 
,07-05 15:09:11.028   874  1759 I ActivityManager: Start proc 3795:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 15:09:11.063  3795  3795 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-05 15:09:11.117  3795  3807 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 15:09:11.225  3795  3807 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 15:09:11.294  3795  3807 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 15:09:11.341  3795  3795 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 15:09:11.552  3795  3795 W InstanceID/Rpc: Found 10011
,07-05 15:09:11.720   874  1708 I ActivityManager: Killing 2354:com.google.android.talk/u0a61 (adj 15): empty #17
,07-05 15:09:11.731  3827  3827 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads293462088.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads293462088.dex
,07-05 15:09:11.787  3827  3827 I dex2oat : dex2oat took 67.531ms (threads: 4) arena alloc=282KB java alloc=37KB native alloc=1515KB free=1300KB
,07-05 15:09:29.644  3003  3878 V KeepSync: Connecting to GoogleApiClient
,07-05 15:09:29.644   874  1707 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 15:09:29.703  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:29.705  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:29.739  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 15:09:29.739  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 15:09:29.739  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:09:29.740  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:09:29.762  1828  3879 V BaseAuthAsyncOperation: access token request failed
,07-05 15:09:29.764  3003  3878 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 15:09:29.823  1487  2004 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 15:09:29.823  1487  2004 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 15:09:29.823  1487  2004 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:09:29.823  1487  2004 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:09:29.844  3003  3878 E KeepSync: IOException
07-05 15:09:29.844  3003  3878 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 15:09:29.844  3003  3878 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:09:29.844  3003  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 15:09:29.844  3003  3878 E KeepSync: 	... 10 more
,07-05 15:09:29.844  3003  3878 W KeepSync: Sync result 2
,07-05 15:09:29.856   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 318011, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:09:40.730  1654  1785 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 15:09:40.731  1654  1785 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 15:09:40.780  1487  1487 I ConfigService: onCreate
,07-05 15:09:41.704  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:41.708  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:41.721  3701  3883 V GoogleAuthProtoRequest: [319] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:09:41.784  1487  2832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:09:41.784  1487  2832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:09:41.784  1487  2832 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:09:41.784  1487  2832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:09:41.819  3701  3883 W ExperimentUpdateService: [319] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: [319] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:09:41.821  3701  3883 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:09:45.856  1487  1487 I ConfigService: onDestroy
,07-05 15:09:47.682   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=336157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:09:53.421  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:53.433  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:53.435  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:09:53.475  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-05 15:09:53.476  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 15:09:53.476  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:09:53.476  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:09:53.498  1487  2003 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 15:09:53.498  1487  2003 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 15:09:53.505  3401  3431 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 15:09:53.505  3401  3431 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 15:09:53.505  3401  3431 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 15:09:53.505  3401  3431 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 15:09:53.505  3401  3431 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 15:09:53.505  3401  3431 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 15:09:53.505  3401  3431 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 15:09:53.922   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 15:10:00.788  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:10:00.792  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:10:00.848  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:10:00.849  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:10:00.849  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:10:00.849  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:10:00.881  2858  3890 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:10:00.881  2858  3890 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:10:00.881  2858  3890 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	... 12 more
07-05 15:10:00.881  2858  3890 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at fal.a(PG:38)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:10:00.881  2858  3890 E HttpOperation: 	... 14 more
,07-05 15:10:00.953  1487  2832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:10:00.954  1487  2832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:10:00.954  1487  2832 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:10:00.954  1487  2832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:10:00.975  2858  3890 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:10:00.975  2858  3890 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at hec.a(PG:42)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at hee.a(PG:102)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at czr.a(PG:65)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at kka.a(PG:108)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:10:00.975  2858  3890 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	... 15 more
07-05 15:10:00.975  2858  3890 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at fal.a(PG:38)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:10:00.975  2858  3890 E HttpOperation: 	... 17 more
07-05 15:10:00.975  2858  3890 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
07-05 15:10:00.975  2858  3890 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at hec.a(PG:42)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	... 15 more
07-05 15:10:00.975  2858  3890 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:10:00.975  2858  3890 E ExperimentLoader: 	... 17 more
,07-05 15:10:01.115   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 348983, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:10:29.282   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:10:39.522   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=387997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:11:15.043   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:11:41.998  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:11:42.001  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:11:42.016  3701  3896 V GoogleAuthProtoRequest: [320] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:11:42.044  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:11:42.044  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:11:42.044  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:11:42.044  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:11:42.065  3701  3896 W ExperimentUpdateService: [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:11:42.066  3701  3896 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:11:59.856   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:12:35.363   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:12:56.267  3470  3902 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:12:56.288  3470  3903 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:12:56.300  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:12:56.302  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:12:56.340  1487  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 15:12:56.341  1487  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:12:56.341  1487  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:12:56.341  1487  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:12:56.382  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:12:56.384  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:12:56.417  1487  2004 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:12:56.417  1487  2004 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:12:56.417  1487  2004 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:12:56.417  1487  2004 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:12:56.441  3470  3903 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:12:56.442  3470  3902 E BooksSync: Soft error
07-05 15:12:56.442  3470  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:12:56.442  3470  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 15:12:56.443  3470  3902 E BooksSync: Sync error
07-05 15:12:56.443  3470  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:12:56.443  3470  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:12:56.445  3470  3902 I BooksSync: Finished books sync
,07-05 15:12:56.453   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 524707, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:13:52.149  3003  3906 V KeepSync: Connecting to GoogleApiClient
,07-05 15:13:52.149   874  1707 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 15:13:52.208  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:13:52.214  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:13:52.273  1487  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-05 15:13:52.273  1487  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 15:13:52.274  1487  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:13:52.274  1487  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:13:52.311  1828  3907 V BaseAuthAsyncOperation: access token request failed
,07-05 15:13:52.313  3003  3906 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 15:13:52.391  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 15:13:52.391  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 15:13:52.391  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:13:52.391  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:13:52.431  3003  3906 E KeepSync: IOException
07-05 15:13:52.431  3003  3906 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 15:13:52.431  3003  3906 E KeepSync: 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 15:13:52.431  3003  3906 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:13:52.431  3003  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 15:13:52.431  3003  3906 E KeepSync: 	... 10 more
07-05 15:13:52.432  3003  3906 W KeepSync: Sync result 2
,07-05 15:13:52.452   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 580452, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:13:58.976   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:14:24.019  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:14:24.024  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:14:24.067  1487  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:14:24.068  1487  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:14:24.068  1487  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:14:24.068  1487  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:14:24.088  2858  3912 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:14:24.088  2858  3912 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:14:24.088  2858  3912 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	... 12 more
07-05 15:14:24.088  2858  3912 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at fal.a(PG:38)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:14:24.088  2858  3912 E HttpOperation: 	... 14 more
,07-05 15:14:24.153  1487  2004 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:14:24.154  1487  2004 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:14:24.154  1487  2004 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:14:24.154  1487  2004 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:14:24.174  2858  3912 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:14:24.174  2858  3912 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at hec.a(PG:42)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at hee.a(PG:102)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at czr.a(PG:65)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at kka.a(PG:108)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:14:24.174  2858  3912 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	... 15 more
07-05 15:14:24.174  2858  3912 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at fal.a(PG:38)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:14:24.174  2858  3912 E HttpOperation: 	... 17 more
,07-05 15:14:24.175  2858  3912 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 15:14:24.175  2858  3912 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at hec.a(PG:42)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	... 15 more
07-05 15:14:24.175  2858  3912 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:14:24.175  2858  3912 E ExperimentLoader: 	... 17 more
,07-05 15:14:24.296   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 612270, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:14:34.509   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=622984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:14:58.802   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:15:34.242   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=682717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:15:42.256  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:15:42.261  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:15:42.276  3701  3920 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:15:42.311  1487  2832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 15:15:42.311  1487  2832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:15:42.311  1487  2832 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:15:42.311  1487  2832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:15:42.333  3701  3920 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:15:52.464  1487  2024 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 15:21:07.153  3470  3937 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:21:07.202  3470  3938 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:21:07.230  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:21:07.239  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:21:07.320  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:21:07.321  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:21:07.321  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:21:07.321  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:21:07.361  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:21:07.365  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:21:07.405  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:21:07.405  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:21:07.406  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:21:07.406  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:21:07.441  3470  3938 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:21:07.442  3470  3937 E BooksSync: Soft error
07-05 15:21:07.442  3470  3937 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:21:07.442  3470  3937 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:21:07.442  3470  3937 E BooksSync: Sync error
07-05 15:21:07.442  3470  3937 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:21:07.442  3470  3937 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 15:21:07.442  3470  3937 I BooksSync: Finished books sync
,07-05 15:21:07.455   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1015472, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:22:37.116  3003  3943 V KeepSync: Connecting to GoogleApiClient
,07-05 15:22:37.117   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 15:22:37.166  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:22:37.169  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:22:37.209  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 15:22:37.210  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 15:22:37.210  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:22:37.210  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:22:37.236  1828  3944 V BaseAuthAsyncOperation: access token request failed
,07-05 15:22:37.238  3003  3943 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 15:22:37.342  1487  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 15:22:37.344  1487  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 15:22:37.344  1487  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:22:37.346  1487  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:22:37.387  3003  3943 E KeepSync: IOException
07-05 15:22:37.387  3003  3943 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 15:22:37.387  3003  3943 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:22:37.387  3003  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 15:22:37.387  3003  3943 E KeepSync: 	... 10 more
07-05 15:22:37.387  3003  3943 W KeepSync: Sync result 2
,07-05 15:22:37.408   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1105167, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:23:10.003  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:23:10.009  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:23:10.074  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:23:10.075  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:23:10.075  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:23:10.075  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:23:10.096  2858  3947 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:23:10.096  2858  3947 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:23:10.096  2858  3947 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	... 12 more
07-05 15:23:10.096  2858  3947 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at fal.a(PG:38)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:23:10.096  2858  3947 E HttpOperation: 	... 14 more
,07-05 15:23:10.150  1487  1948 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:23:10.150  1487  1948 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:23:10.150  1487  1948 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:23:10.150  1487  1948 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:23:10.174  2858  3947 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:23:10.174  2858  3947 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at hec.a(PG:42)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at hee.a(PG:102)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at czr.a(PG:65)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at kka.a(PG:108)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:23:10.174  2858  3947 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	... 15 more
07-05 15:23:10.174  2858  3947 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at fal.a(PG:38)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:23:10.174  2858  3947 E HttpOperation: 	... 17 more
07-05 15:23:10.174  2858  3947 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 15:23:10.174  2858  3947 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at hec.a(PG:42)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	... 15 more
07-05 15:23:10.174  2858  3947 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:23:10.174  2858  3947 E ExperimentLoader: 	... 17 more
,07-05 15:23:10.343   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1138132, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:23:42.416  1828  3951 I EventLogService: Opted in for usage reporting
,07-05 15:23:42.429  1828  3951 I EventLogService: Aggregate from 1467723130147 (log), 1467723130147 (data)
,07-05 15:23:42.463  1828  3951 W EventLogAggregator: Unknown tag: snet_gcore
,07-05 15:23:42.463  1828  3951 W EventLogAggregator: Unknown tag: snet_launch_service
,07-05 15:23:42.512  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:23:42.515  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:23:42.531  3701  3953 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:23:42.588  1828  3951 I ServiceDumpSys: dumping service [account]
,07-05 15:23:42.595  1487  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:23:42.595  1487  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:23:42.595  1487  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:23:42.595  1487  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:23:42.617  3701  3953 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:23:42.618  3701  3953 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:23:47.362   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1175837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 15:23:59.362   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:24:29.535   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 15:29:13.309   874  1286 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
07-05 15:29:13.310   874  1286 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,07-05 15:29:14.002   874  1295 I PowerManagerService: Waking up from dozing (uid 1000)...
,07-05 15:29:14.003   874   874 V KeyguardServiceDelegate: onStartedWakingUp()
07-05 15:29:14.004   874   894 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 15:29:14.011   874   894 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@27717ea)
,07-05 15:29:14.012  3740  3740 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 15:29:14.012  3740  3740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-05 15:29:14.018   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-05 15:29:14.018   280   280 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-05 15:29:14.019   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,07-05 15:29:14.031   874  3000 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-05 15:29:14.037   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 15:29:14.043   874  1305 E native  : do suspend false
,07-05 15:29:14.043  1814  1814 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-05 15:29:14.051  1728  1849 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-05 15:29:14.051  1728  1849 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
,07-05 15:29:14.052   874  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 15:29:14.053  3740  3740 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 15:29:14.053  3740  3740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 15:29:14.054  1728  1849 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-05 15:29:14.054  1728  1835 D BrcmNfcJni: RoutingManager::commitRouting
,07-05 15:29:14.055  1728  1849 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT,
,07-05 15:29:14.068   874  1367 I ActivityManager: Start proc 3976:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-05 15:29:14.078   373  1503 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-05 15:29:14.078   373  1503 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-05 15:29:14.113  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-05 15:29:14.131   874  3000 I ActivityManager: Killing 3444:com.google.process.gapps/u0a99 (adj 15): empty #17
,07-05 15:29:14.195   874   894 I DisplayPowerController: Unblocked screen on after 191 ms
,07-05 15:29:14.196   874   894 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-05 15:29:14.196   874   894 I DreamManagerService: Gently waking up from dream.
07-05 15:29:14.197   874  1759 I DreamManagerService: Leaving dreamland.
07-05 15:29:14.197   874   889 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-05 15:29:14.267   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 15:29:14.267   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
07-05 15:29:14.271   874  1328 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
,07-05 15:29:14.338   874  3990 V AudioService.RotationHelper: publishing device rotation =1 (x90deg)
,07-05 15:29:14.339   373  1276 D audio_hw_primary: adev_set_parameters: enter: rotation=90
07-05 15:29:14.339   373  1276 D mot_vr_audio_hw: adev_set_parameters: rotation=90
,07-05 15:29:14.342   874   888 I ActivityManager: Config changes=480 {1.0 ?mcc?mnc en_US ldltr sw411dp w683dp h387dp 560dpi nrml land finger -keyb/v/h -nav/h s.5}
,07-05 15:29:14.342   874  1295 I InputReader: Reconfiguring input devices.  changes=0x00000004
07-05 15:29:14.342   874  1295 I InputReader: Device reconfigured: id=5, name='atmel_mxt_ts', size 1440x2560, orientation 1, mode 1, display id 0
,07-05 15:29:14.367  1743  1743 D ImsConfigImpl: onConfigurationChange
,07-05 15:29:14.520   874   892 I WindowManager: Screen frozen for +193ms due to Window{b8449e0 u0 NavigationBar}
,07-05 15:29:14.873  1728  2106 D NfcService: Discovery configuration equal, not updating.
,07-05 15:29:16.526   874   892 I art     : Starting a blocking GC Explicit
,07-05 15:29:16.586   874   892 I art     : Explicit concurrent mark sweep GC freed 7169(356KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/43MB, paused 1.114ms total 59.588ms
,07-05 15:29:19.042   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1507517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:29:27.122   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:30:12.461  1487  2284 I GCM     : GCM message com.google.android.gms 0:1467725412261836%136ddda6f9fd7ecd
,07-05 15:30:12.481  1828  1828 I GCM     : Message from 745476177629 null
,07-05 15:30:12.524  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:30:12.530  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:30:12.680  1487  4012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.me
,07-05 15:30:12.680  1487  4012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 15:30:12.680  1487  4012 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:30:12.682  1487  4012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: Failed to update the notification(s) read state.
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: com.google.android.gms.auth.ae: BadAuthentication
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:60)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:403)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:284)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:262)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.notifications.a.a(SourceFile:45)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.a(SourceFile:199)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.onHandleIntent(SourceFile:73)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at android.os.Looper.loop(Looper.java:148)
07-05 15:30:12.727  1487  4012 W GnotsSRSOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 15:30:12.727  1487  4012 W WakefulBroadcastReceiver: No active wake lock id #6
,07-05 15:30:17.349   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1565823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:30:25.415   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1573890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:31:14.086  1814  2477 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 15:31:14.996   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 15:31:15.007  1654  1654 I Keyboard.Facilitator: onFinishInput()
,07-05 15:31:15.617  3740  3740 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 15:31:15.617  3740  3740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 15:31:15.649   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 15:31:15.649  3740  3740 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dd5c271 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ea0b5ae, 16908290=android.view.AbsSavedState$1@ea0b5ae}, android:Panels={0=com.android.internal.policy.PhoneWindow$PanelFeatureState$SavedState@45c8f4f}, android:focusedViewId=100}]}]
,07-05 15:31:15.649  3740  3740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 15:31:15.650  3740  3740 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-05 15:31:15.650  3740  3740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-05 15:31:15.657   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,07-05 15:31:15.657   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
07-05 15:31:15.657   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 15:31:15.892   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 15:31:15.896   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-05 15:31:15.897   874  1328 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,07-05 15:31:15.900   874   894 I DreamManagerService: Entering dreamland.
,07-05 15:31:15.900   874   894 I PowerManagerService: Dozing...
,07-05 15:31:15.901   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-05 15:31:15.955   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 15:31:15.959   874  1305 E native  : do suspend true
,07-05 15:31:16.080   373  1806 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-05 15:31:16.080   373  1806 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,07-05 15:31:50.949   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1659424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:31:59.015   874  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1667490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms)
```
