#### Test 800380637c16410_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-04 10:47:35.051  3047  3826 V KeepSync: Connecting to GoogleApiClient
,--------- beginning of system
08-04 10:47:35.052   873  1688 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-04 10:47:35.150  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 10:47:35.155  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 10:47:35.193  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-04 10:47:35.193  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-04 10:47:35.193  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:47:35.193  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-04 10:47:35.213  1844  3827 V BaseAuthAsyncOperation: access token request failed
08-04 10:47:35.215  3047  3826 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-04 10:47:35.261  1523  1806 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-04 10:47:35.261  1523  1806 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-04 10:47:35.261  1523  1806 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:47:35.261  1523  1806 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-04 10:47:35.275  3047  3826 E KeepSync: IOException
08-04 10:47:35.275  3047  3826 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-04 10:47:35.275  3047  3826 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-04 10:47:35.275  3047  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-04 10:47:35.275  3047  3826 E KeepSync: 	... 10 more
08-04 10:47:35.275  3047  3826 W KeepSync: Sync result 2
08-04 10:47:35.286   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 248889, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-04 10:47:35.702  3828  3828 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 10:47:35.707  3828  3828 D AndroidRuntime: CheckJNI is OFF
08-04 10:47:35.749  3828  3828 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 10:47:35.800  3828  3828 I Radio-JNI: register_android_hardware_Radio DONE
08-04 10:47:35.822  3828  3828 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 10:47:35.826   873  1763 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 10:47:35.889   873  1763 I ActivityManager: Start proc 3838:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 10:47:35.896  3828  3828 D AndroidRuntime: Shutting down VM
08-04 10:47:35.988  3838  3838 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 10:47:36.014  3838  3838 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 10:47:36.026  3838  3838 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 133-136)
08-04 10:47:36.026  3838  3838 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:47:36.050  3838  3838 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8ced93d}
08-04 10:47:36.050  3838  3838 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:47:36.051  3838  3838 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 10:47:36.062  3838  3838 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 10:47:36.065  3838  3838 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 10:47:36.089  3838  3838 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-04 10:47:36.107  3838  3838 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 10:47:36.108  3838  3838 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 10:47:36.108  3838  3838 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 10:47:36.108  3838  3838 I Adreno  : Build Date                       : 10/20/15
08-04 10:47:36.108  3838  3838 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 10:47:36.108  3838  3838 I Adreno  : Local Branch                     : M14
08-04 10:47:36.108  3838  3838 I Adreno  : Remote Branch                    : 
08-04 10:47:36.108  3838  3838 I Adreno  : Remote Branch                    : 
08-04 10:47:36.108  3838  3838 I Adreno  : Reconstruct Branch               : 
,08-04 10:47:36.184   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ada9d3d:true
,08-04 10:47:36.239  3838  3838 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 10:47:36.256  3838  3838 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-04 10:47:36.311  3838  3875 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 10:47:36.321  3838  3862 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-04 10:47:36.354  3838  3875 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 10:47:36.369  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-04 10:47:36.411   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +464ms (total +558ms)
,08-04 10:47:36.466  3838  3838 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3838
,08-04 10:47:36.582  3838  3838 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 10:47:36.731  3838  3878 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681458896
,08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 10:47:36.743  3838  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76b5fd8 added. We now have 1 listener(s)
,08-04 10:47:36.748  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-04 10:47:36.749  3838  3878 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 10:47:36.749  3838  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:47:36.750  3838  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
,08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 10:47:36.756  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 10:47:36.757  3838  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc98b97 added. We now have 1 listener(s)
08-04 10:47:36.757  3838  3878 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:47:36.762   873  1315 D WifiService: New client listening to asynchronous messages
08-04 10:47:36.762  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:47:36.762  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-04 10:47:36.762  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 10:47:36.763  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-04 10:47:36.763  3838  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-04 10:47:36.765  3838  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:47:36.766  3838  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-04 10:47:36.775  3838  3878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:36.775  3838  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:36.775  3838  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 10:47:36.775  3838  3878 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:47:36.776  3838  3878 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 10:47:36.786  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:36.788  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:36.800  3838  3838 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 10:47:37.535  3838  3885 W jxcore-log: Initializing JXcore engine
08-04 10:47:37.535  3838  3885 W jxcore-log: JXcore engine is ready
,08-04 10:47:37.569  3885  3885 W Thread-350: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-04 10:47:37.569  3885  3885 W Thread-350: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10924]" dev="sockfs" ino=10924 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-04 10:47:37.569  3885  3885 W Thread-350: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-04 10:47:37.569  3885  3885 W Thread-350: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26913]" dev="sockfs" ino=26913 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 10:47:37.584  3838  3885 W jxcore-log: Starting JXcore engine
,08-04 10:47:37.662  3838  3885 W jxcore-log: Platform android
08-04 10:47:37.662  3838  3885 W jxcore-log: 
,08-04 10:47:37.663  3838  3885 W jxcore-log: Process ARCH arm
08-04 10:47:37.663  3838  3885 W jxcore-log: 
,08-04 10:47:37.828  3838  3885 I jxcore-log: JXcore Cordova bridge is ready!
08-04 10:47:37.828  3838  3885 I jxcore-log: 
,08-04 10:47:37.828  3838  3885 W jxcore-log: JXcore engine is started
,08-04 10:47:37.837  3838  3878 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 10:47:37.841  3838  3838 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 10:47:47.803  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 10:47:47.803  3838  3885 I jxcore-log: 
,08-04 10:47:47.805  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 10:47:47.805  3838  3885 I jxcore-log: 
,08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:47.817  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:47.824  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:47:47.826  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 10:47:47.826  3838  3885 I jxcore-log: 
,08-04 10:47:47.828  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 10:47:47.828  3838  3885 I jxcore-log: 
,08-04 10:47:48.152  3838  3885 D ExecuteNativeTests: Running unit tests
,08-04 10:47:48.209  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:47:48.210  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 added. We now have 2 listener(s)
08-04 10:47:48.211  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:47:48.211  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:47:48.211  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:47:48.211  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:47:48.211  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 added. We now have 2 listener(s)
08-04 10:47:48.211  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:47:48.212  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:47:48.215  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.228  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:48.236  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:47:48.237  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 10:47:48.239  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-04 10:47:48.239  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:47:48.239  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 10:47:48.240  3838  3885 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-04 10:47:48.240  3838  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:47:48.241  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:47:48.241  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:47:48.241  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:47:48.241  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.242  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.242  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.242  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 10:47:48.242  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.242  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:47:48.242  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:47:48.243  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 removed from the list
,08-04 10:47:48.243  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.243  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 removed from the list
08-04 10:47:48.244  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.247  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:48.247  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop,
08-04 10:47:48.247  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.248  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.248  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.249  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.249  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.249  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.249  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.251  3838  3885 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 10:47:48.251  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.251  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.251  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.252  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.252  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.252  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.252  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.252  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.252  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.252  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.253  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.253  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.253  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.253  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.257  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.257  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.257  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.257  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.274  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-04 10:47:48.274  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:47:48.274  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-04 10:47:48.274  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:47:48.275  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:47:48.276  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:47:48.277  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:47:48.277  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:47:48.277  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.277  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.277  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.277  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.277  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.277  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.277  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.277  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.277  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.277  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.277  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.278  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.278  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.278  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.279  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.279  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.279  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.279  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.280  3838  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 10:47:48.281  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.288  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:48.292  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.292  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:47:48.292  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:47:48.293  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:47:48.293  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:47:48.293  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:47:48.293  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:47:48.294  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.297  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.299  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:47:48.299  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:47:48.306  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:47:48.309  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 10:47:48.309  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:47:48.313  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-04 10:47:48.316  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-04 10:47:48.316  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 10:47:48.317  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 10:47:48.317  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 10:47:48.319  3838  3885 D BluetoothAdapter: STATE_ON
08-04 10:47:48.328  2570  2769 D BtGatt.GattService: registerClient() - UUID=d044581c-2d5e-423d-8a98-94bca96a377a
08-04 10:47:48.329  2570  2621 D BtGatt.GattService: onClientRegistered() - UUID=d044581c-2d5e-423d-8a98-94bca96a377a, clientIf=5
08-04 10:47:48.332  3838  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 10:47:48.333  2570  2581 D BtGatt.GattService: start scan with filters
08-04 10:47:48.339  2570  2626 D BtGatt.ScanManager: handling starting scan
08-04 10:47:48.339  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:47:48.340  2570  2626 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
08-04 10:47:48.340  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 10:47:48.341  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 10:47:48.342  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 10:47:48.347  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:47:48.347  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 10:47:48.347  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:47:48.349  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 10:47:48.351  2570  2621 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 10:47:48.351  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.351  2570  2626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 10:47:48.353  3838  3885 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 10:47:48.357  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 10:47:48.357  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.357  2570  2626 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 10:47:48.357  2570  2626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 10:47:48.357  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:47:48.358  3838  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 10:47:48.358  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.358  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 10:47:48.358  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.358  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 10:47:48.358  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 10:47:48.358  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:47:48.358  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:47:48.358  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:47:48.361  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:47:48.361  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 10:47:48.362  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:47:48.363  2570  2769 D BtGatt.GattService: stopScan() - queue size =1
08-04 10:47:48.363  2570  2581 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 10:47:48.364  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:47:48.364  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 10:47:48.366  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 10:47:48.367  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 10:47:48.367  2570  2621 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 10:47:48.367  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.367  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 10:47:48.374  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.374  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 10:47:48.374  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:47:48.374  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:47:48.375  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 10:47:48.375  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.376  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:47:48.377  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.377  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.377  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.377  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:47:48.377  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.377  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.377  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.378  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.378  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.378  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.378  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.379  3838  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 10:47:48.382  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:47:48.382  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 10:47:48.382  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.382  2570  2626 D BtGatt.ScanManager: stopping BLe Batch
,08-04 10:47:48.391  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 10:47:48.391  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.391  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:48.391  2570  2626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 10:47:48.394  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.394  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:47:48.395  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 10:47:48.395  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:47:48.396  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:47:48.396  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:47:48.396  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:47:48.396  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.397  2570  2621 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 10:47:48.398  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.399  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:47:48.399  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 10:47:48.400  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:48.404  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 10:47:48.405  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 10:47:48.405  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:47:48.411  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 10:47:48.411  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 10:47:48.411  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 10:47:48.412  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:47:48.416  2570  2581 D BtGatt.GattService: registerClient() - UUID=1910a28a-1763-4957-bc95-c3c7ad89e31b
,08-04 10:47:48.417  2570  2621 D BtGatt.GattService: onClientRegistered() - UUID=1910a28a-1763-4957-bc95-c3c7ad89e31b, clientIf=5
,08-04 10:47:48.417  3838  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 10:47:48.418  2570  2584 D BtGatt.GattService: start scan with filters
,08-04 10:47:48.421  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:47:48.421  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 10:47:48.421  2570  2626 D BtGatt.ScanManager: handling starting scan
08-04 10:47:48.421  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 10:47:48.421  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 10:47:48.426  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 10:47:48.426  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 10:47:48.426  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 10:47:48.428  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 10:47:48.428  2570  2621 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 10:47:48.429  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.429  2570  2626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 10:47:48.432  3838  3885 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 10:47:48.435  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:47:48.435  3838  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 10:47:48.435  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.435  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 10:47:48.436  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.436  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 10:47:48.436  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 10:47:48.436  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:47:48.436  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:47:48.436  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:47:48.436  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:47:48.436  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 10:47:48.436  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 10:47:48.436  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.437  2570  2626 D BtGatt.ScanManager: Starting BLE batch scan
08-04 10:47:48.437  2570  2626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 10:47:48.437  3838  3885 D BluetoothAdapter: STATE_ON
08-04 10:47:48.438  2570  2769 D BtGatt.GattService: stopScan() - queue size =1
08-04 10:47:48.439  2570  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 10:47:48.439  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:47:48.439  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 10:47:48.439  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 10:47:48.439  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 10:47:48.440  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 10:47:48.441  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.441  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 10:47:48.441  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:47:48.442  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:47:48.442  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:47:48.443  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.443  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.443  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.444  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:47:48.444  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.444  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.444  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.444  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.444  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.444  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.444  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.444  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.445  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.446  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.446  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.446  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.446  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.447  3838  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 10:47:48.449  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.455  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:48.458  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:47:48.459  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 10:47:48.460  2570  2621 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 10:47:48.460  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 10:47:48.460  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 10:47:48.460  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.460  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 10:47:48.460  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:47:48.460  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:47:48.462  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.465  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:48.466  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 10:47:48.466  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.467  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:47:48.467  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 10:47:48.476  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 10:47:48.477  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 10:47:48.477  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:47:48.478  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 10:47:48.478  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.479  2570  2626 D BtGatt.ScanManager: stopping BLe Batch
,08-04 10:47:48.482  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 10:47:48.482  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 10:47:48.482  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 10:47:48.483  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:47:48.485  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 10:47:48.485  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.486  2570  2626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 10:47:48.488  2570  2769 D BtGatt.GattService: registerClient() - UUID=f949b35e-eb7c-478b-aac8-dafaacef152d
,08-04 10:47:48.489  2570  2621 D BtGatt.GattService: onClientRegistered() - UUID=f949b35e-eb7c-478b-aac8-dafaacef152d, clientIf=5
,08-04 10:47:48.489  3838  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
08-04 10:47:48.490  2570  2768 D BtGatt.GattService: start scan with filters,
,08-04 10:47:48.492  2570  2621 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 10:47:48.492  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.494  2570  2626 D BtGatt.ScanManager: handling starting scan
08-04 10:47:48.494  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:47:48.495  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 10:47:48.495  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 10:47:48.496  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 10:47:48.501  2570  2621 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 10:47:48.501  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:47:48.501  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.501  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 10:47:48.501  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:47:48.501  2570  2626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 10:47:48.504  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 10:47:48.507  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 10:47:48.507  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.507  2570  2626 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 10:47:48.507  2570  2626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 10:47:48.508  3838  3885 I io.jxcore.node.ConnectionHelper: start: OK
08-04 10:47:48.508  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.509  3838  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 10:47:48.509  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.509  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 10:47:48.509  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.509  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 10:47:48.509  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 10:47:48.509  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:47:48.509  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:47:48.510  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:47:48.510  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:47:48.510  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 10:47:48.511  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:47:48.512  2570  2581 D BtGatt.GattService: stopScan() - queue size =1
,08-04 10:47:48.513  2570  2769 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 10:47:48.514  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:47:48.515  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 10:47:48.515  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 10:47:48.515  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 10:47:48.516  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 10:47:48.518  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.519  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 10:47:48.519  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:47:48.519  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:47:48.521  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:47:48.522  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.522  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.522  2570  2621 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 10:47:48.522  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.523  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.523  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.523  3838  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 10:47:48.523  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.523  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.523  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.523  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.523  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:47:48.523  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.524  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.524  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.524  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.524  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.524  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.524  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.526  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.526  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.527  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.527  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.528  3838  3885 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 10:47:48.528  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.529  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.529  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.529  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 10:47:48.529  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.529  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.530  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.530  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.530  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.530  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.530  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.530  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.530  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.530  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 10:47:48.530  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.530  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:47:48.531  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.532  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.532  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.532  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.534  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-04 10:47:48.534  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.535  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.535  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.536  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.536  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.536  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.536  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.536  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.537  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.537  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.537  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.537  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.537  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.537  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.538  2570  2621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 10:47:48.538  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.538  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.538  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.538  2570  2626 D BtGatt.ScanManager: stopping BLe Batch
08-04 10:47:48.539  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.539  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.542  3838  3885 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-04 10:47:48.543  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.543  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.543  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.544  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.544  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.544  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.545  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.545  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.545  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.546  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.546  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.546  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.546  2570  2621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 10:47:48.546  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.546  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.547  2570  2626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 10:47:48.547  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.549  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.550  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.551  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.551  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.553  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-04 10:47:48.554  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.554  2570  2621 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 10:47:48.554  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.554  2570  2621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:47:48.554  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.555  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.556  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.556  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.556  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
,08-04 10:47:48.556  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.557  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.557  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.557  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.557  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.558  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.558  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.560  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.561  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:47:48.561  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.561  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.563  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:47:48.564  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:47:48.564  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:47:48.564  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:47:48.565  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:47:48.565  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:47:48.566  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:47:48.566  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.566  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.566  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.566  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.566  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.566  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.567  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.567  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.567  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.567  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.567  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.567  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.567  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.568  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.568  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.568  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.568  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.569  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:47:48.569  3838  3885 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:47:48.569  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 10:47:48.573  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:47:48.573  3838  3885 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-04 10:47:48.573  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:47:48.574  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:47:48.575  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:47:48.575  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 10:47:48.575  3838  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:47:48.575  3838  3885 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 10:47:48.576  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:47:48.576  3838  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:47:48.576  3838  3885 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-04 10:47:48.576  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:47:48.576  3838  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:47:48.576  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-04 10:47:48.580  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-04 10:47:48.580  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 10:47:48.580  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-04 10:47:48.581  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 10:47:48.581  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 10:47:48.581  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 10:47:48.581  3838  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-04 10:47:48.582  3838  3885 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-04 10:47:48.582  3838  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 414)
08-04 10:47:48.582  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:47:48.582  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.582  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.583  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.583  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.583  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.583  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 10:47:48.583  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
,08-04 10:47:48.584  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.584  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.584  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.584  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.584  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.584  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.584  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.584  3838  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:47:48.585  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.585  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.585  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.585  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.586  3838  3885 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-04 10:47:48.587  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.587  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.587  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.587  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.587  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.587  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.587  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.587  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.587  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.587  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.587  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.587  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.587  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.587  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.588  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.588  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.588  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.588  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.589  3838  3885 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 10:47:48.589  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.589  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.589  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.590  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.590  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.590  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.590  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.590  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.590  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.590  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.590  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.590  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.590  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.590  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.591  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.591  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.591  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.592  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.592  3838  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 414
,08-04 10:47:48.592  3838  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 10:47:48.592  3838  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 414)
08-04 10:47:48.593  3838  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 10:47:48.593  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:47:48.593  3838  3885 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 10:47:48.593  3838  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:47:48.593  3838  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 10:47:48.593  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:47:48.593  3838  3885 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 10:47:48.593  3838  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:47:48.593  3838  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:47:48.593  3838  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 414)
,08-04 10:47:48.593  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:47:48.593  3838  3885 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 10:47:48.594  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.594  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:47:48.594  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.594  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.594  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.594  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.594  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.594  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.594  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.594  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.594  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.594  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.595  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.595  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.596  2570  2765 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-04 10:47:48.596  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.596  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.596  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.596  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.596  3838  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 414)
08-04 10:47:48.596  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.596  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.597  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.597  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
,08-04 10:47:48.597  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.597  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.597  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.597  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.597  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.597  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.597  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.597  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.597  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.597  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.597  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
,08-04 10:47:48.597  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.598  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.598  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.598  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.598  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.598  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.598  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.598  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.598  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.598  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.598  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.598  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.598  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.598  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.599  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.599  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.599  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.599  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.601  3838  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 10:47:48.601  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:47:48.603  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-04 10:47:48.604  3838  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 10:47:48.604  3838  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-04 10:47:48.604  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 10:47:48.604  3838  3838 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 10:47:48.604  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 10:47:48.605  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.605  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 10:47:48.605  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-04 10:47:48.605  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 10:47:48.605  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.605  3838  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 10:47:48.605  3838  3838 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 10:47:48.605  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.605  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.605  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:47:48.606  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 10:47:48.606  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:47:48.606  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.606  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.606  3838  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 10:47:48.606  3838  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-04 10:47:48.607  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.607  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.607  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.607  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:47:48.607  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.607  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:47:48.607  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.607  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.607  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.607  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.607  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.607  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.607  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.607  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.607  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.607  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.608  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.608  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.608  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.608  3838  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 10:47:48.609  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.609  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.609  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.610  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.611  3838  3885 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 10:47:48.611  3838  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:47:48.611  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-04 10:47:48.612  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 10:47:48.612  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.612  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.612  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.613  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.613  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.613  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.613  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.613  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.613  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.613  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.613  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.613  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.613  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.613  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.614  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.614  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.614  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:47:48.614  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.617  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:47:48.617  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.617  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:47:48.618  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.618  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.618  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.618  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.618  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.618  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.618  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.618  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.618  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.618  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.618  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:47:48.619  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.619  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.619  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.619  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.620  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:47:48.620  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:47:48.620  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:47:48.620  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:47:48.620  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.620  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.620  3838  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97172c1 not in the list
08-04 10:47:48.620  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.620  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
08-04 10:47:48.620  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:47:48.620  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:47:48.620  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.620  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:47:48.621  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:47:48.621  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:47:48.621  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:47:48.621  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:47:48.622  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ada66 not in the list
,08-04 10:47:48.622  3838  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 10:47:48.622  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:47:48.623  3838  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 10:47:48.623  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:47:48.623  3838  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 10:47:48.623  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-04 10:47:48.624  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 10:47:48.624  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-04 10:47:48.625  3838  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 10:47:48.625  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 10:47:48.625  3838  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 10:47:48.625  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 10:47:48.625  3838  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 10:47:48.625  3838  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-04 10:47:48.626  3838  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 10:47:48.626  3838  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 10:47:48.626  3838  3885 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 10:47:48.626  3838  3885 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 10:47:48.627  3838  3885 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-04 10:47:48.627  3838  3885 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 10:47:48.627  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:47:48.628  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc6bad8 added. We now have 2 listener(s)
08-04 10:47:48.628  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:47:48.629  3838  3885 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 10:47:48.629   873  1783 D WifiService: setWifiEnabled: true pid=3838, uid=10000
08-04 10:47:48.629   873  1783 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:47:48.630  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:47:48.630  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59b8e31 added. We now have 3 listener(s)
08-04 10:47:48.630  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:47:48.635  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:47:48.635  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@374a916 added. We now have 4 listener(s)
08-04 10:47:48.635  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:47:48.636  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:47:48.636  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@134e297 added. We now have 5 listener(s)
,08-04 10:47:48.636  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:47:48.638   873   883 D WifiService: setWifiEnabled: false pid=3838, uid=10000
08-04 10:47:48.638   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:47:48.642  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:47:48.642  2570  2617 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 10:47:48.643  2570  2617 D BluetoothAdapterProperties: Setting state to 13
08-04 10:47:48.643  2570  2617 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-04 10:47:48.644  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.645  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:48.645  2570  2617 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 10:47:48.645  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.645  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:47:48.646  2570  2617 I BluetoothAdapterState: Entering PendingCommandState
08-04 10:47:48.646  2570  2621 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:47:48.646  2570  2617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 10:47:48.646  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 10:47:48.648  2570  2570 D HeadsetService: Received stop request...Stopping profile...
08-04 10:47:48.650  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.652  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.653  1750  1765 D BluetoothHeadset: Proxy object disconnected
,08-04 10:47:48.655  2570  2570 D A2dpService: Received stop request...Stopping profile...
,08-04 10:47:48.655  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:48.655  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:48.655  2570  2772 D A2dpStateMachine: Exit Disconnected: -1
08-04 10:47:48.656  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.656  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:48.657  1358  1377 D BluetoothHeadset: Proxy object disconnected
08-04 10:47:48.657  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-04 10:47:48.657   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 10:47:48.657   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 10:47:48.657   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 10:47:48.658  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-04 10:47:48.658  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.658   873   873 D BluetoothA2dp: Proxy object disconnected
08-04 10:47:48.659  2570  2570 D HidService: Received stop request...Stopping profile...
08-04 10:47:48.659  2570  2570 D HidService: Stopping Bluetooth HidService
08-04 10:47:48.660  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-04 10:47:48.660  1358  1358 D HidProfile: Bluetooth service disconnected
08-04 10:47:48.661  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.661  2570  2570 V BluetoothAdapterState: isTurningOn()=false
,08-04 10:47:48.661  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.661  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 10:47:48.662  2570  2570 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 10:47:48.662  2570  2621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 10:47:48.663  2570  2570 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:47:48.663  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:47:48.663  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:47:48.663  2570  2570 D HealthService: Received stop request...Stopping profile...
08-04 10:47:48.663  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:47:48.663  2570  2621 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-04 10:47:48.665  2570  2570 D PanService: Received stop request...Stopping profile...
,08-04 10:47:48.666  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 10:47:48.666  1358  1358 D PanProfile: Bluetooth service disconnected
08-04 10:47:48.666  2570  2570 D BluetoothMapService: Received stop request...Stopping profile...
08-04 10:47:48.667  2570  2570 D BluetoothMapService: stop()
08-04 10:47:48.667  2570  2570 D BluetoothMapAppObserver: deinitObservers()
08-04 10:47:48.667  2570  2570 D BluetoothMapAppObserver: removeReceiver()
,08-04 10:47:48.668  1358  1358 D BluetoothMap: Proxy object disconnected
08-04 10:47:48.668  1358  1358 D MapProfile: Bluetooth service disconnected
,08-04 10:47:48.669  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.669  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:48.669  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.669  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:48.671  2570  2621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-04 10:47:48.671  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 10:47:48.671  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 10:47:48.672  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.672  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:48.672  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.672  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:48.672  2570  2752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-04 10:47:48.672  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 10:47:48.672  2570  2752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:47:48.673  2570  2570 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:47:48.673  2570  2752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:47:48.673  2570  2621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 10:47:48.673  2570  2752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:47:48.673  2570  2570 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:47:48.674  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.674  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:48.674  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.675  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:48.676   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 10:47:48.676  2570  2570 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 10:47:48.676   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-04 10:47:48.676  2570  2621 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 10:47:48.676   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 10:47:48.676   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:47:48.677  2570  2570 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:47:48.677  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.677  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:48.677  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.677  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:48.678  2570  2570 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:47:48.678  2570  2570 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 10:47:48.679  2570  2570 D BluetoothMapService: MAP Service closeService in
08-04 10:47:48.679  2570  2570 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 10:47:48.679  2570  2570 D ObexServerSockets0: shutdown(block = true)
08-04 10:47:48.679  2570  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 10:47:48.680  2570  2570 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 10:47:48.680  2570  2788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 10:47:48.681  2570  2765 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 10:47:48.681  2570  2570 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 10:47:48.681  2570  2570 V BluetoothAdapterState: isTurningOff()=true
08-04 10:47:48.681  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:48.681  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:48.681  2570  2570 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:48.681  2570  2617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 10:47:48.681  2570  2617 D BluetoothAdapterProperties: Setting state to 15
08-04 10:47:48.682  2570  2617 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 10:47:48.683  2570  2617 I BluetoothAdapterState: Entering BleOnState
08-04 10:47:48.683  2570  2570 D BluetoothMapService: cleanup()
08-04 10:47:48.683  2570  2570 D BluetoothMapService: MAP Service closeService in
,08-04 10:47:48.688   873  1314 E native  : do suspend true
,08-04 10:47:48.693  1358  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 10:47:48.695  2570  2570 I BtOppRfcommListener: stopping Accept Thread
,08-04 10:47:48.696  2570  3368 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:47:48.697  2570  3368 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 10:47:48.697  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.699  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.700  1358  3837 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:47:48.702   873  2009 D DhcpClient: Clearing IP address
,08-04 10:47:48.702   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:47:48.707   373   872 D CommandListener: Setting iface cfg
08-04 10:47:48.708  1523  2322 V NativeCrypto: Read error: ssl=0x9af64c00: I/O error during system call, Connection timed out
08-04 10:47:48.710  1523  2322 V NativeCrypto: SSL shutdown failed: ssl=0x9af64c00: I/O error during system call, Broken pipe
,08-04 10:47:48.713   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-04 10:47:48.714   873  2001 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-04 10:47:48.715   873  2001 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-04 10:47:48.716   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-04 10:47:48.716   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-04 10:47:48.717   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 10:47:48.721   873   886 I ActivityManager: Start proc 3892:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-04 10:47:48.722  1358  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 10:47:48.723   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-04 10:47:48.723   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 10:47:48.723   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 10:47:48.723   873  1314 E native  : do suspend true
08-04 10:47:48.723   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-04 10:47:48.727  1358  3837 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 10:47:48.728  1358  1859 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 10:47:48.728   401   401 E Parcel  : Reading a NULL string not supported here.
,08-04 10:47:48.729  1358  1375 D BluetoothPan: onBluetoothStateChange on: false
,08-04 10:47:48.729   873  2010 D DhcpClient: Receive thread stopped
,08-04 10:47:48.729   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 10:47:48.729  1750  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:47:48.730   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:47:48.730   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:47:48.730   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:47:48.730  2570  2617 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-04 10:47:48.730  2570  2617 D BluetoothAdapterProperties: Setting state to 16
,08-04 10:47:48.730  2570  2617 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-04 10:47:48.731  2570  2617 D BluetoothAdapterProperties: onBleDisable
08-04 10:47:48.731  2570  2617 I BluetoothAdapterState: Entering PendingCommandState
08-04 10:47:48.731  2570  2618 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 10:47:48.732  2570  2621 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:47:48.732  2570  2752 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 10:47:48.732  2570  2752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:47:48.736  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:48.736  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:48.737  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.737  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:47:48.738   373   872 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:47:48.740  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.740   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:48.740  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:48.741  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.741  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:47:48.742   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 10:47:48.746  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.749  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Chec,king support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:48.749  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:47:48.761   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 10:47:48.765   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 10:47:48.766  1832  2077 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:47:48.767  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:48.767  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:47:48.768  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.768  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:48.771  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:48.772  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:48.772  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:48.772  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:48.781   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:47:48.788  3892  3892 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-04 10:47:48.801  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:47:48.806   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 10:47:48.806   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e9e88e:true
08-04 10:47:48.806   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 10:47:48.807   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:48.808  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:47:48.814   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 10:47:48.817  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:48.817  3067  3067 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5349d9d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-04 10:47:48.818  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:48.819  1819  1819 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-04 10:47:48.829   873   883 I ActivityManager: Start proc 3909:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-04 10:47:48.838  3892  3892 D LocalBluetoothProfileManager: Adding local MAP profile
,08-04 10:47:48.840  3892  3892 D BluetoothMap: Create BluetoothMap proxy object
,08-04 10:47:48.844  3892  3892 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-04 10:47:48.849  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:47:48.852   873  1764 I ActivityManager: Killing 3067:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-04 10:47:48.876   373   872 E Netd    : netlink response contains error (No such file or directory)
,08-04 10:47:48.877   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 10:47:48.930  3909  3909 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-04 10:47:48.941  2570  2621 I bt_hci  : shut_down
,08-04 10:47:48.942  2570  2627 D bt_hwcfg: hw_epilog_process
,08-04 10:47:48.943  2570  2627 I bt_vendor: low_power_mode_cb
,08-04 10:47:48.973  2570  2627 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 10:47:48.973  2570  2627 I bt_vendor: epilog_cb
,08-04 10:47:48.973  2570  2627 I bt_hci  : epilog_finished_callback
,08-04 10:47:48.977  2570  2621 I bt_hci_h4: hal_close
,08-04 10:47:48.977  2570  2621 I bt_userial_vendor: device fd = 51 close
,08-04 10:47:49.094  2570  2618 D bt_stack_manager: event_shut_down_stack finished.
,08-04 10:47:49.094  2570  2617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
,08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2,
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 10:47:49.098  3909  3909 D StrictMode: 	,at com.google.r.k.d(PG:1187)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: ,	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290),
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.k.d(PG:583)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.098  3909  3909 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:47:49.098  3909  3909 D StrictMode: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.098  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.099  2570  2617 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-04 10:47:49.099  2570  2570 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:47:49.100  2570  2570 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 10:47:49.101  2570  2570 D BtGatt.GattService: stop()
08-04 10:47:49.101  2570  2570 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 10:47:49.104  2570  2570 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:47:49.105  2570  2570 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:49.105  2570  2570 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:47:49.105  2570  2570 V BluetoothAdapterState: isBleTurningOff()=true
08-04 10:47:49.106  2570  2617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 10:47:49.106  2570  2617 D BluetoothAdapterProperties: Setting state to 10
,08-04 10:47:49.106  2570  2617 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-04 10:47:49.107  3838  3838 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 10:47:49.108  2570  2617 I BluetoothAdapterState: Entering OffState
08-04 10:47:49.108  3909  3909 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.108  3909  3909 D StrictMode: 	,at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.108  3909  3909 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:47:49.108  3909  3909 D StrictMode: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:47:49.108  3909  3909 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:47:49.109   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-04 10:47:49.122  2570  2570 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-04 10:47:49.122  2570  2570 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-04 10:47:49.122  2570  2570 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 10:47:49.123  2570  2618 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-04 10:47:49.126  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:47:49.132  2570  2618 D bt_stack_manager: event_clean_up_stack finished.
,08-04 10:47:49.134  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:47:49.136   873  1774 I ActivityManager: Killing 3562:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-04 10:47:49.148  2570  2570 I art     : System.exit called, status: 0
,08-04 10:47:49.148  2570  2570 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 10:47:49.211   873  1763 I ActivityManager: Process com.android.bluetooth (pid 2570) has died
,08-04 10:47:49.220  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:47:49.248   873  1783 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,08-04 10:47:49.361  3944  3944 D AdapterServiceConfig: Adding HeadsetService
08-04 10:47:49.361  3944  3944 D AdapterServiceConfig: Adding A2dpService
08-04 10:47:49.361  3944  3944 D AdapterServiceConfig: Adding HidService
,08-04 10:47:49.362  3944  3944 D AdapterServiceConfig: Adding HealthService
08-04 10:47:49.362  3944  3944 D AdapterServiceConfig: Adding PanService
08-04 10:47:49.362  3944  3944 D AdapterServiceConfig: Adding GattService
08-04 10:47:49.362  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 10:47:49.382  3909  3929 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-04 10:47:49.400   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0d3769:true
,08-04 10:47:49.400   873  1688 I ActivityManager: Start proc 3958:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-04 10:47:49.457  3958  3958 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-04 10:47:49.500  3958  3958 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-04 10:47:49.530   873  1749 I ActivityManager: Killing 3384:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-04 10:47:49.606  1844  1844 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 10:47:49.610  1844  1844 D SystemUpdateService: onCreate
,08-04 10:47:49.619  1844  1844 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 10:47:49.625  1844  3982 I SystemUpdateService: active receiver: enabled
,08-04 10:47:49.632  1844  3982 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 10:47:49.635  1844  3982 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 10:47:49.635  1844  3982 I SystemUpdateService: now status is 0 (complete)
08-04 10:47:49.635  1844  3982 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-04 10:47:49.635  1844  3982 I SystemUpdateService: file has been verified
,08-04 10:47:49.635  1844  3982 I SystemUpdateService: OTA package size = 12249756
08-04 10:47:49.637  1844  1844 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-04 10:47:49.639  1844  2350 I iu.UploadsManager: num queued entries: 0
,08-04 10:47:49.640  1844  2350 I iu.UploadsManager: num updated entries: 0
08-04 10:47:49.642  1844  2350 I iu.SyncManager: NEXT; no task
08-04 10:47:49.642  1844  3982 I SystemUpdateService: showing system update notification
,08-04 10:47:49.652  1844  1844 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 10:47:49.653  1844  1844 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 10:47:49.675   873  1735 I ActivityManager: Start proc 3984:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-04 10:47:49.677  1844  1844 D SystemUpdateService: onDestroy
,08-04 10:47:49.733  3984  3984 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-04 10:47:49.737  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:49.743  3984  3984 D SprintDMHelper: simOperator: 
08-04 10:47:49.743  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 10:47:49.773   873  1688 I ActivityManager: Start proc 3996:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-04 10:47:49.775   873  1688 I ActivityManager: Killing 3486:android.process.acore/u0a5 (adj 15): empty #17
,08-04 10:47:49.894  3454  4010 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 10:47:49.920   873  1688 I ActivityManager: Start proc 4011:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-04 10:47:49.923   873  1763 I ActivityManager: Killing 3683:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-04 10:47:50.010  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-04 10:47:50.060  4011  4011 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-04 10:47:50.060  4011  4011 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-04 10:47:50.060  4011  4011 I GAv4    :   adb logcat -s GAv4
,08-04 10:47:50.071  4011  4011 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-04 10:47:50.077  4011  4011 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-04 10:47:50.109  4011  4028 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-04 10:47:50.220  4011  4011 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-04 10:47:50.262  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 10:47:50.273  4011  4011 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4381-4383)
08-04 10:47:50.273  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 10:47:50.286  4011  4011 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d6de6a1}
,08-04 10:47:50.286  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 10:47:50.287  4011  4011 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 10:47:50.296  4011  4011 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 10:47:50.297  4011  4011 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 10:47:50.314  4011  4011 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 10:47:50.330  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 10:47:50.331  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 10:47:50.331  4011  4011 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 10:47:50.331  4011  4011 I Adreno  : Build Date                       : 10/20/15
08-04 10:47:50.331  4011  4011 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 10:47:50.331  4011  4011 I Adreno  : Local Branch                     : M14
08-04 10:47:50.331  4011  4011 I Adreno  : Remote Branch                    : 
08-04 10:47:50.331  4011  4011 I Adreno  : Remote Branch                    : 
08-04 10:47:50.331  4011  4011 I Adreno  : Reconstruct Branch               : 
,08-04 10:47:50.396  4011  4011 I NSApplication: Starting up...
,08-04 10:47:50.411  4011  4057 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 10:47:50.443   873  1688 I ActivityManager: Start proc 4062:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-04 10:47:50.445   873  1688 I ActivityManager: Killing 3699:com.android.musicfx/u0a18 (adj 15): empty #17
,08-04 10:47:50.517  4062  4062 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-04 10:47:50.720   873  1783 I ActivityManager: Killing 3404:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-04 10:47:51.649   873  1783 D WifiService: setWifiEnabled: true pid=3838, uid=10000
,08-04 10:47:51.650   873  1783 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:47:51.661   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-04 10:47:51.671  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:51.671  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:51.671  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:51.672  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:47:51.676  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:51.676  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:51.677  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:51.677  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:51.694   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-04 10:47:51.695   873  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 10:47:51.695   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-04 10:47:51.696   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 10:47:51.697   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 10:47:51.697   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 10:47:51.698   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 10:47:51.698   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 10:47:51.711   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-04 10:47:51.711   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 10:47:51.713   373   872 D CommandListener: Setting iface cfg
,08-04 10:47:51.721   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-04 10:47:51.721   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:47:51.722   873  1314 E native  : do suspend true
,08-04 10:47:51.732   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 10:47:51.738   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 10:47:51.738   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 10:47:53.135   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 10:47:53.194   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=12.31 delta 1000 -> 994
,08-04 10:47:53.197   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 10:47:53.197   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:47:53.218   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 10:47:53.265   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 10:47:53.268  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 10:47:53.690  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 10:47:53.726  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 10:47:53.726  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 10:47:53.732   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 10:47:53.741   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 10:47:53.742   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:47:53.742   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 10:47:53.763   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:47:53.784   373   872 D CommandListener: Setting iface cfg
,08-04 10:47:53.786   873  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-04 10:47:53.795   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 10:47:53.838   873  4085 D DhcpClient: Receive thread started
,08-04 10:47:53.923   873  1314 E native  : do suspend false
,08-04 10:47:53.943   873  2009 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 10:47:53.956   873  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172554, domain null
,08-04 10:47:53.957   873  2009 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172554 seconds
,08-04 10:47:53.960   873  2009 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 10:47:53.972   873  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 10:47:53.973   873  2009 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 10:47:53.977   373   872 D CommandListener: Setting iface cfg
,08-04 10:47:53.985   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 10:47:53.987   873  2009 D DhcpClient: Scheduling renewal in 86399s
,08-04 10:47:53.988   873  1314 E native  : do suspend true
,08-04 10:47:54.009   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 10:47:54.013   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 10:47:54.014   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 10:47:54.016   873  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-04 10:47:54.022   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 10:47:54.087   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 10:47:54.088   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 10:47:54.090   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 10:47:54.091   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-04 10:47:54.093   873  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-04 10:47:54.101   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 10:47:54.108   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-04 10:47:54.108   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-04 10:47:54.109   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-04 10:47:54.111   873  1316 D ConnectivityService:    accepting network in place of null
08-04 10:47:54.111   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-04 10:47:54.113   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 10:47:54.113   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 10:47:54.124   873  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268234, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 10:47:54.139   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:47:54.165   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:47:54.174   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 10:47:54.174   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:54.181   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-04 10:47:54.185   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 10:47:54.193   873  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 10:47:54.203  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:54.203  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:47:54.203  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.203  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:47:54.205  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:47:54.205  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:47:54.205  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.205  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:47:54.210  1819  1819 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-04 10:47:54.212  1844  1844 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 10:47:54.215  1844  1844 D SystemUpdateService: onCreate
,08-04 10:47:54.217  3595  4094 I BooksSync: Starting books sync for 61035162, extras: ade
,08-04 10:47:54.218  1844  1844 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 10:47:54.221  1844  4096 I SystemUpdateService: active receiver: enabled
,08-04 10:47:54.223  1844  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 10:47:54.225  1844  4096 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 10:47:54.225  1844  4096 I SystemUpdateService: now status is 0 (complete)
08-04 10:47:54.225  1844  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 10:47:54.225  1844  4096 I SystemUpdateService: file has been verified
,08-04 10:47:54.225  1844  4096 I SystemUpdateService: OTA package size = 12249756
,08-04 10:47:54.231  1844  4096 I SystemUpdateService: showing system update notification
,08-04 10:47:54.233  1844  1844 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 10:47:54.237  1844  2350 I iu.UploadsManager: num queued entries: 0
,08-04 10:47:54.238  1844  2350 I iu.UploadsManager: num updated entries: 0
08-04 10:47:54.239  1844  2350 I iu.SyncManager: NEXT; no task
,08-04 10:47:54.241  1844  1844 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 10:47:54.242  1844  1844 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 10:47:54.244  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:54.247  1844  4101 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 10:47:54.247  1844  4101 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 10:47:54.248  1844  4101 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
08-04 10:47:54.248  1844  1844 D SystemUpdateService: onDestroy
,08-04 10:47:54.251  3984  3984 D SprintDMHelper: simOperator: 
,08-04 10:47:54.251  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 10:47:54.254  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 10:47:54.256  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 10:47:54.288  3595  4104 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-04 10:47:54.289  1523  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-04 10:47:54.289  1523  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 10:47:54.289  1523  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:47:54.289  1523  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:47:54.294   873  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 08:47:54 GMT], X-Android-Received-Millis=[1470300474293], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470300474251]}
,08-04 10:47:54.295   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 10:47:54.295   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-04 10:47:54.295   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 10:47:54.296   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 10:47:54.312  1844  4101 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-04 10:47:54.318  1523  1806 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-04 10:47:54.318  1523  1806 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-04 10:47:54.319  1523  1806 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:47:54.319  1523  1806 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:47:54.359  1523  2085 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-04 10:47:54.359  1523  2085 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-04 10:47:54.360  1523  2085 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:47:54.360  1523  2085 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:47:54.380  3595  4104 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-04 10:47:54.381  3595  4094 E BooksSync: Soft error
08-04 10:47:54.381  3595  4094 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-04 10:47:54.381  3595  4094 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-04 10:47:54.382  3595  4094 E BooksSync: Sync error
08-04 10:47:54.382  3595  4094 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-04 10:47:54.382  3595  4094 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-04 10:47:54.382  3595  4094 I BooksSync: Finished books sync
,08-04 10:47:54.388   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 250472, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-04 10:47:54.411  3454  4103 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 10:47:54.478   873  1749 I ActivityManager: Killing 3722:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-04 10:47:54.655   873  1764 D WifiService: setWifiEnabled: false pid=3838, uid=10000
08-04 10:47:54.656   873  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:47:54.685  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 10:47:54.694   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 10:47:54.695   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-04 10:47:54.696   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 10:47:54.699   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:47:54.718   873  1314 E native  : do suspend true
,08-04 10:47:54.732   873  2009 D DhcpClient: Clearing IP address
,08-04 10:47:54.732   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:47:54.738   373   872 D CommandListener: Setting iface cfg
,08-04 10:47:54.747  1523  4109 V NativeCrypto: Read error: ssl=0x9a498c00: I/O error during system call, Connection timed out
08-04 10:47:54.761   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 10:47:54.762   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
08-04 10:47:54.763   401   401 E Parcel  : Reading a NULL string not supported here.
08-04 10:47:54.763   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 10:47:54.763   873  1314 E native  : do suspend true
,08-04 10:47:54.774  1523  4109 V NativeCrypto: SSL shutdown failed: ssl=0x9a498c00: I/O error during system call, Broken pipe
,08-04 10:47:54.785   873  4085 D DhcpClient: Receive thread stopped
08-04 10:47:54.762   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-04 10:47:54.787   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:47:54.790   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 10:47:54.792   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-04 10:47:54.804   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 10:47:54.806  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:54.806  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:54.806  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.806  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:54.807  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:54.807  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:54.807  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:47:54.807  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:54.808  1832  2077 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:47:54.809   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 10:47:54.829   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:47:54.855   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:47:54.856   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 10:47:54.856   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:54.860   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 10:47:54.861  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:54.862  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:47:54.869  1819  1819 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-04 10:47:54.872  1844  1844 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-04 10:47:54.881  1844  1844 D SystemUpdateService: onCreate
,08-04 10:47:54.889  1844  1844 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 10:47:54.912  1844  1844 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 10:47:54.914  1844  2350 I iu.UploadsManager: num queued entries: 0
08-04 10:47:54.915  1844  2350 I iu.UploadsManager: num updated entries: 0
,08-04 10:47:54.925  1844  1844 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 10:47:54.926  1844  4120 I SystemUpdateService: active receiver: enabled
,08-04 10:47:54.928  1844  1844 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-04 10:47:54.930  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:47:54.915  1844  2350 I iu.SyncManager: NEXT; no task
,08-04 10:47:54.933  1844  4120 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 10:47:54.936  3984  3984 D SprintDMHelper: simOperator: 
08-04 10:47:54.936  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 10:47:54.938  1844  4120 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 10:47:54.938  1844  4120 I SystemUpdateService: now status is 0 (complete)
08-04 10:47:54.938  1844  4120 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 10:47:54.938  1844  4120 I SystemUpdateService: file has been verified
08-04 10:47:54.938  1844  4120 I SystemUpdateService: OTA package size = 12249756
,08-04 10:47:54.955   373   872 E Netd    : netlink response contains error (No such file or directory)
,08-04 10:47:54.966  3454  4124 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 10:47:54.970  1844  4120 I SystemUpdateService: showing system update notification
,08-04 10:47:54.980  1844  1844 D SystemUpdateService: onDestroy
,08-04 10:47:55.173   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 10:47:57.694   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5de223b:true
,08-04 10:47:57.696  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 10:47:57.701  3944  3944 I bt_bluedroid: init
,08-04 10:47:57.702  3944  4126 I BluetoothAdapterState: Entering OffState
,08-04 10:47:57.704  3944  4127 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 10:47:57.704  3944  4127 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-04 10:47:57.704  3944  4127 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 10:47:57.704  3944  4127 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 10:47:57.705  3944  3944 I bt_bluedroid: get_profile_interface socket
,08-04 10:47:57.707  3944  3944 I bt_bluedroid: get_profile_interface sdp
08-04 10:47:57.710  3944  3955 I bt_bluedroid: config_hci_snoop_log
08-04 10:47:57.710  3944  4130 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-04 10:47:57.714   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 10:47:57.716  3944  4130 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 10:47:57.723  3944  4126 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 10:47:57.723  3944  4126 D BluetoothAdapterProperties: Setting state to 14
08-04 10:47:57.724  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 10:47:57.728  3944  4126 D BluetoothBondStateMachine: make
,08-04 10:47:57.732  3944  4131 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 10:47:57.739  3944  4126 I BluetoothAdapterState: Entering PendingCommandState
,08-04 10:47:57.740  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 10:47:57.747  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:57.748  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:47:57.749  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
,08-04 10:47:57.750  3944  3944 D BtGatt.GattService: start()
,08-04 10:47:57.750  3944  3944 I bt_bluedroid: get_profile_interface gatt
,08-04 10:47:57.752  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
08-04 10:47:57.752  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,08-04 10:47:57.762  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:47:57.763  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:47:57.763  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
08-04 10:47:57.763  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:57.764  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-04 10:47:57.764  3944  4126 I bt_bluedroid: enable
08-04 10:47:57.765  3944  4127 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-04 10:47:57.765  3944  4127 I bt_hci  : start_up
,08-04 10:47:57.771  3944  4127 I bt_vendor: alloc value 0xb39a9189
08-04 10:47:57.771  3944  4127 I bt_vendor: init
08-04 10:47:57.771  3944  4127 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 10:47:57.771  3944  4127 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 10:47:57.877  3944  4127 D bt_hci  : start_up starting async portion
,08-04 10:47:57.878  3944  4134 I bt_hci  : event_finish_startup
08-04 10:47:57.878  3944  4134 I bt_hci_h4: hal_open
08-04 10:47:57.878  3944  4134 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 10:47:57.888  3944  4134 I bt_userial_vendor: device fd = 51 open
,08-04 10:47:57.919  3944  4134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:47:57.951  3944  4134 D bt_hwcfg: Chipset BCM4354A2
,08-04 10:47:57.952  3944  4134 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 10:47:57.952  3944  4134 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 10:47:58.606  3944  4134 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 10:47:58.607  3944  4134 D bt_hwcfg: Settlement delay -- 100 ms
08-04 10:47:58.608  3944  4134 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 10:47:58.724  3944  4134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:47:58.726  3944  4134 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 10:47:58.755  3944  4134 I bt_hwcfg: vendor lib fwcfg completed
,08-04 10:47:58.755  3944  4134 I bt_vendor: firmware callback
08-04 10:47:58.756  3944  4134 I bt_hci  : firmware_config_callback
,08-04 10:47:58.768  3944  4136 I bt_btu  : btu_task pending for preload complete event
,08-04 10:47:58.768  3944  4136 I bt_btu_task: Bluetooth chip preload is complete
08-04 10:47:58.768  3944  4136 I bt_btu  : btu_task received preload complete event
,08-04 10:47:58.781  3944  4136 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 10:47:58.781  3944  4136 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 10:47:58.781  3944  4136 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 10:47:58.781  3944  4136 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-04 10:47:58.782  3944  4136 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 10:47:58.782  3944  4136 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:47:58.782  3944  4136 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 10:47:58.783  3944  4136 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:47:58.783  3944  4136 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 10:47:58.783  3944  4136 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 10:47:58.783  3944  4136 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 10:47:58.784  3944  4136 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 10:47:58.784  3944  4136 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:47:58.784  3944  4136 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 10:47:58.784  3944  4136 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 10:47:58.918  3944  4136 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,08-04 10:47:58.918  3944  4136 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-04 10:47:58.949  3944  4130 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-04 10:47:58.950  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 10:47:58.951  3944  4130 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 10:47:58.954  3944  4130 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 10:47:58.957  3944  4130 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:47:58.957  3944  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:47:58.958  3944  4130 D bt_hci  : do_postload posting postload work item
,08-04 10:47:58.958  3944  4134 I bt_hci  : event_postload
08-04 10:47:58.958  3944  4134 I bt_vendor: sco_config_cb
,08-04 10:47:58.959  3944  4134 I bt_hci  : sco_config_callback postload finished.
08-04 10:47:58.962  3944  4130 D bt_bte_conf: Device ID record 1 : primary
,08-04 10:47:58.963  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:58.963  3944  4130 D bt_bte_conf:   vendorId            = 000f
08-04 10:47:58.963  3944  4130 D bt_bte_conf:   vendorIdSource      = 0001
08-04 10:47:58.963  3944  4130 D bt_bte_conf:   product             = 1200
08-04 10:47:58.963  3944  4130 D bt_bte_conf:   version             = 1436
08-04 10:47:58.964  3944  4130 D bt_bte_conf:   clientExecutableURL = 
08-04 10:47:58.964  3944  4130 D bt_bte_conf:   serviceDescription  = 
08-04 10:47:58.964  3944  4130 D bt_bte_conf:   documentationURL    = 
08-04 10:47:58.964  3944  4130 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 10:47:58.965  3944  4127 D bt_stack_manager: event_start_up_stack finished
08-04 10:47:58.966  3944  4134 I bt_vendor: low_power_mode_cb
08-04 10:47:58.966  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-04 10:47:58.966  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:58.967  3944  4126 D BluetoothAdapterProperties: Setting state to 15
08-04 10:47:58.967  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-04 10:47:58.970  3944  4126 I BluetoothAdapterState: Entering BleOnState
08-04 10:47:58.974  3944  4126 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 10:47:58.974  3944  4126 D BluetoothAdapterProperties: Setting state to 11
08-04 10:47:58.974  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 10:47:58.988  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:58.989  3944  3944 D HeadsetService: Received start request. Starting profile...
08-04 10:47:58.991  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:58.994  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:58.994  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 10:47:58.995  3944  3944 D HeadsetStateMachine: make
08-04 10:47:59.003  3944  4126 I BluetoothAdapterState: Entering PendingCommandState
08-04 10:47:59.005  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
08-04 10:47:59.006  3944  3944 I bt_bluedroid: get_profile_interface handsfree
08-04 10:47:59.006  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 10:47:59.006  3944  4130 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 10:47:59.012  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:59.012  3944  3944 D A2dpService: Received start request. Starting profile...
,08-04 10:47:59.013  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 10:47:59.014  3944  3944 I bt_bluedroid: get_profile_interface avrcp
,08-04 10:47:59.020  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 10:47:59.021  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:47:59.021  3944  3944 D A2dpStateMachine: make
,08-04 10:47:59.022  3944  3944 I bt_bluedroid: get_profile_interface a2dp
,08-04 10:47:59.023  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 10:47:59.027  3944  4145 D A2dpStateMachine: Enter Disconnected: -2
,08-04 10:47:59.030  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:47:59.031  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 10:47:59.033  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:59.035  3892  3892 D BluetoothInputDevice: Proxy object connected
,08-04 10:47:59.035  3944  3944 D HidService: Received start request. Starting profile...
,08-04 10:47:59.035  3944  3944 I bt_bluedroid: get_profile_interface hidhost
08-04 10:47:59.035  3944  3944 D HidService: setHidService(): set to: null
08-04 10:47:59.035  3944  4130 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
,08-04 10:47:59.036  3892  3892 D HidProfile: Bluetooth service connected
08-04 10:47:59.036  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 10:47:59.036  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 10:47:59.037  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:59.038  3944  3944 D HealthService: Received start request. Starting profile...
,08-04 10:47:59.040  3944  3944 I bt_bluedroid: get_profile_interface health
,08-04 10:47:59.041  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 10:47:59.042  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:59.044  3892  3892 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 10:47:59.044  3944  3944 D PanService: Received start request. Starting profile...
08-04 10:47:59.044  3892  3892 D PanProfile: Bluetooth service connected
,08-04 10:47:59.044  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:47:59.044  3944  3944 I bt_bluedroid: get_profile_interface pan
08-04 10:47:59.045  3944  4130 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 10:47:59.056  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:47:59.058  3892  3892 D BluetoothMap: Proxy object connected
,08-04 10:47:59.058  3892  3892 D MapProfile: Bluetooth service connected
08-04 10:47:59.058  3944  3944 D BluetoothMapService: Received start request. Starting profile...
08-04 10:47:59.059  3892  3892 D BluetoothMap: getConnectedDevices()
,08-04 10:47:59.059  3944  3944 D BluetoothMapService: start()
08-04 10:47:59.060  3892  3892 D BluetoothMap: Bluetooth is Not enabled
,08-04 10:47:59.065  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 10:47:59.066  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 10:47:59.066  3944  3944 D BluetoothMapAppObserver: createReceiver()
,08-04 10:47:59.067  3944  3944 D BluetoothMapAppObserver: initObservers()
08-04 10:47:59.068  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 10:47:59.074  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:47:59.075  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-04 10:47:59.075  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:59.075  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:59.077  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-04 10:47:59.077  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-04 10:47:59.077  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:47:59.077  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 10:47:59.077  3944  4143 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 10:47:59.079  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-04 10:47:59.079  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-04 10:47:59.079  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:47:59.079  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:47:59.080  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:59.081  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-04 10:47:59.081  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-04 10:47:59.081  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:47:59.081  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:47:59.081  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 10:47:59.081  3944  4126 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:47:59.082  3944  4126 D BluetoothAdapterProperties: State =  11
08-04 10:47:59.082  3944  4126 D BluetoothAdapterProperties: Setting state to 12
08-04 10:47:59.082  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 10:47:59.082  3944  4126 I BluetoothAdapterState: Entering OnState
,08-04 10:47:59.083  3944  4130 D BluetoothAdapterProperties: Scan Mode:21
08-04 10:47:59.083  3944  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 10:47:59.083  1358  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 10:47:59.089  3892  3902 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:47:59.090  1358  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:59.092  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:47:59.094  1358  3837 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 10:47:59.095  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:47:59.096  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 10:47:59.096  1358  1358 D BluetoothInputDevice: Proxy object connected
,08-04 10:47:59.097  1358  1358 D HidProfile: Bluetooth service connected
,08-04 10:47:59.097  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-04 10:47:59.097  1358  1377 D BluetoothMap: onBluetoothStateChange: up=true
08-04 10:47:59.099  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:47:59.100  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:47:59.101  1358  1358 D BluetoothMap: Proxy object connected
08-04 10:47:59.101  1358  1358 D MapProfile: Bluetooth service connected
,08-04 10:47:59.101  1358  1358 D BluetoothMap: getConnectedDevices()
08-04 10:47:59.101  3892  3903 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 10:47:59.102  3892  3902 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 10:47:59.103  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:47:59.103  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:47:59.104  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
08-04 10:47:59.104  3944  3944 D ObexServerSockets0: startAccept()
08-04 10:47:59.104  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-04 10:47:59.106  1358  1859 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 10:47:59.107  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 10:47:59.108  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 10:47:59.109  1358  1358 D BluetoothA2dp: Proxy object connected
,08-04 10:47:59.109  1358  1377 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:47:59.109  3944  4151 D ObexServerSockets0: Accepting socket connection...
08-04 10:47:59.110  3944  4152 D ObexServerSockets0: Accepting socket connection...
,08-04 10:47:59.112  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:47:59.112  1358  1358 D PanProfile: Bluetooth service connected
,08-04 10:47:59.112  3892  3903 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 10:47:59.113   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:47:59.113  1750  3440 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:47:59.113   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:47:59.114   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:47:59.114   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:47:59.115   873   873 D BluetoothA2dp: Proxy object connected
,08-04 10:47:59.116  3944  3944 D BluetoothMapService: onReceive
,08-04 10:47:59.116  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:47:59.116  3944  3944 D BluetoothMapService: STATE_ON
,08-04 10:47:59.118  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:59.119  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:47:59.120  3892  3892 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 10:47:59.120   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 10:47:59.125  3892  3892 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-04 10:47:59.130  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:47:59.133  3892  3892 D BluetoothA2dp: Proxy object connected
,08-04 10:47:59.136  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:47:59.142  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:47:59.146  1358  1358 D BluetoothPbap: Proxy object connected
,08-04 10:47:59.146  3892  3892 D BluetoothPbap: Proxy object connected
08-04 10:47:59.146  1358  1358 D PbapServerProfile: Bluetooth service connected
08-04 10:47:59.146  3892  3892 D PbapServerProfile: Bluetooth service connected
08-04 10:47:59.146  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 10:47:59.146  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-04 10:47:59.156  3944  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:47:59.169  3944  4161 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:47:59.171  3944  4161 I BtOppRfcommListener: Accept thread started.
,08-04 10:47:59.187  1750  1762 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.188  1358  1859 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.188  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-04 10:47:59.188   873   873 D BluetoothHeadset: Proxy object connected
08-04 10:47:59.188   873   873 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.188   873   873 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.213   873   890 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.214  1750  1923 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.214   873   890 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.214   873   890 D BluetoothHeadset: Proxy object connected,
,08-04 10:47:59.228  3892  3902 D BluetoothHeadset: Proxy object connected
,08-04 10:47:59.233  3892  3892 D HeadsetProfile: Bluetooth service connected
,08-04 10:48:00.672  3944  4126 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 10:48:00.673  3944  4126 D BluetoothAdapterProperties: Setting state to 13
08-04 10:48:00.673  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 10:48:00.675  3944  4126 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 10:48:00.679  3944  4126 I BluetoothAdapterState: Entering PendingCommandState
,08-04 10:48:00.685  3944  3944 D BluetoothMapService: onReceive
,08-04 10:48:00.686  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:48:00.686  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
08-04 10:48:00.687  3944  3944 D BluetoothMapService: MAP Service closeService in
08-04 10:48:00.687  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 10:48:00.687  3944  3944 D ObexServerSockets0: shutdown(block = true)
08-04 10:48:00.688  3944  4151 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 10:48:00.691  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:00.691  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:00.691  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 10:48:00.692  3944  4152 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-04 10:48:00.694  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:48:00.694  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:48:00.694  3944  4130 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:48:00.695  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 10:48:00.695  3944  4139 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 10:48:00.696  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 10:48:00.697  3944  3944 I BtOppRfcommListener: stopping Accept Thread
08-04 10:48:00.698  3944  4161 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 10:48:00.700  3944  4161 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 10:48:00.703  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:00.703  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:48:00.704  3944  3944 D HeadsetService: Received stop request...Stopping profile...
,08-04 10:48:00.704  3838  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:48:00.704  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:48:00.707  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 10:48:00.709  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:00.710  3892  3902 D BluetoothHeadset: Proxy object disconnected
08-04 10:48:00.710  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:00.710  1750  1765 D BluetoothHeadset: Proxy object disconnected
08-04 10:48:00.711  1358  1859 D BluetoothHeadset: Proxy object disconnected
08-04 10:48:00.711   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 10:48:00.711   873   873 D BluetoothHeadset: Proxy object disconnected
,08-04 10:48:00.711   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 10:48:00.712  3944  3944 D A2dpService: Received stop request...Stopping profile...
08-04 10:48:00.712  3944  4145 D A2dpStateMachine: Exit Disconnected: -1
08-04 10:48:00.715   873   873 D BluetoothA2dp: Proxy object disconnected
08-04 10:48:00.716  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-04 10:48:00.716  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-04 10:48:00.717  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.717  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-04 10:48:00.717  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:00.717  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:00.718  3944  3944 D HidService: Received stop request...Stopping profile...
08-04 10:48:00.718  3944  3944 D HidService: Stopping Bluetooth HidService
08-04 10:48:00.719  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-04 10:48:00.719  1358  1358 D HidProfile: Bluetooth service disconnected
,08-04 10:48:00.720  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-04 10:48:00.720  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:48:00.720  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:48:00.721  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:48:00.721  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:48:00.721  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 10:48:00.721  3944  4130 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-04 10:48:00.721  3944  3944 D HealthService: Received stop request...Stopping profile...
,08-04 10:48:00.721  3892  3892 D HeadsetProfile: Bluetooth service disconnected
08-04 10:48:00.723  3944  3944 D PanService: Received stop request...Stopping profile...
,08-04 10:48:00.725  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 10:48:00.725  1358  1358 D PanProfile: Bluetooth service disconnected
08-04 10:48:00.725  3892  3892 D DockEventReceiver: finishStartingService: stopping service
08-04 10:48:00.725  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.725  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:00.725  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:00.726  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 10:48:00.726  3892  3892 D BluetoothA2dp: Proxy object disconnected
,08-04 10:48:00.727  3892  3892 D BluetoothInputDevice: Proxy object disconnected
08-04 10:48:00.727  3892  3892 D HidProfile: Bluetooth service disconnected
,08-04 10:48:00.729  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 10:48:00.729  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 10:48:00.729  3944  4136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:48:00.729  3944  4136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:48:00.729  3944  4136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:48:00.729  3944  4136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:48:00.729  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-04 10:48:00.730  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:48:00.730  3892  3892 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 10:48:00.730  3892  3892 D PanProfile: Bluetooth service disconnected
08-04 10:48:00.730  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 10:48:00.731  3944  3944 D BluetoothMapService: stop()
08-04 10:48:00.731  3944  3944 D BluetoothMapAppObserver: deinitObservers()
08-04 10:48:00.731  3944  3944 D BluetoothMapAppObserver: removeReceiver()
08-04 10:48:00.733  3892  3892 D BluetoothMap: Proxy object disconnected
08-04 10:48:00.733  3892  3892 D MapProfile: Bluetooth service disconnected
08-04 10:48:00.733  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.733  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:00.733  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:00.733  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:00.734  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:48:00.734  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:48:00.734  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.734  3944  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 10:48:00.734  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:00.734  1358  1358 D BluetoothMap: Proxy object disconnected
,08-04 10:48:00.734  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:00.734  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:00.734  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 10:48:00.734  3944  4130 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 10:48:00.734  1358  1358 D MapProfile: Bluetooth service disconnected
08-04 10:48:00.735  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:48:00.735  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.735  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:00.736  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:00.736  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:00.736  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:48:00.736  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 10:48:00.739  1358  1358 D BluetoothPbap: Proxy object disconnected
,08-04 10:48:00.739  1358  1358 D PbapServerProfile: Bluetooth service disconnected
08-04 10:48:00.740  3892  3892 D BluetoothPbap: Proxy object disconnected
08-04 10:48:00.740  3892  3892 D PbapServerProfile: Bluetooth service disconnected
,08-04 10:48:00.742  3944  3944 D BluetoothMapService: MAP Service closeService in
,08-04 10:48:00.742  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-04 10:48:00.743  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:00.743  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:00.743  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:00.743  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 10:48:00.743  3944  4126 D BluetoothAdapterProperties: Setting state to 15
,08-04 10:48:00.743  3944  3944 D BluetoothMapService: cleanup()
08-04 10:48:00.743  3944  3944 D BluetoothMapService: MAP Service closeService in
08-04 10:48:00.743  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 10:48:00.743  3944  4126 I BluetoothAdapterState: Entering BleOnState
08-04 10:48:00.744  1358  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:48:00.744  3892  4166 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:48:00.745  3892  3903 D BluetoothPan: onBluetoothStateChange on: false
08-04 10:48:00.745  1358  1859 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:48:00.746  1358  3837 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 10:48:00.746  1358  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-04 10:48:00.747  3892  3902 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 10:48:00.747  3892  4166 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 10:48:00.748  1358  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 10:48:00.748  1358  1859 D BluetoothPan: onBluetoothStateChange on: false
,08-04 10:48:00.749  3892  3903 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 10:48:00.750   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:48:00.750  1750  3440 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:48:00.750   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:48:00.750   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 10:48:00.750  3892  3902 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:48:00.751   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:48:00.751  3944  4126 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 10:48:00.751  3944  4126 D BluetoothAdapterProperties: Setting state to 16
,08-04 10:48:00.751  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-04 10:48:00.752  3944  4126 D BluetoothAdapterProperties: onBleDisable
08-04 10:48:00.752  3944  4126 I BluetoothAdapterState: Entering PendingCommandState
08-04 10:48:00.753  3944  4127 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 10:48:00.754  3944  4136 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-04 10:48:00.754  3944  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 10:48:00.755  3944  4130 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:48:00.756  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:00.757  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:00.757  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 10:48:00.758  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:00.759  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:00.763  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:48:00.765  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:48:00.954  3944  4130 I bt_hci  : shut_down
08-04 10:48:00.955  3944  4134 D bt_hwcfg: hw_epilog_process
,08-04 10:48:00.957  3944  4134 I bt_vendor: low_power_mode_cb
,08-04 10:48:00.985  3944  4134 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 10:48:00.986  3944  4134 I bt_vendor: epilog_cb
08-04 10:48:00.986  3944  4134 I bt_hci  : epilog_finished_callback
,08-04 10:48:00.996  3944  4130 I bt_hci_h4: hal_close
,08-04 10:48:00.997  3944  4130 I bt_userial_vendor: device fd = 51 close
,08-04 10:48:01.117  3944  4127 D bt_stack_manager: event_shut_down_stack finished.
,08-04 10:48:01.119  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 10:48:01.125  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:48:01.125  3944  4126 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 10:48:01.127  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
,08-04 10:48:01.127  3944  3944 D BtGatt.GattService: stop()
,08-04 10:48:01.128  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 10:48:01.132  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:01.132  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-04 10:48:01.133  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:01.133  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
08-04 10:48:01.134  3944  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-04 10:48:01.134  3944  4126 D BluetoothAdapterProperties: Setting state to 10
,08-04 10:48:01.135  3944  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-04 10:48:01.137  3944  4126 I BluetoothAdapterState: Entering OffState
08-04 10:48:01.138   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-04 10:48:01.168  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 10:48:01.169  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 10:48:01.169  3944  4127 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 10:48:01.180  3944  4127 D bt_stack_manager: event_clean_up_stack finished.
,08-04 10:48:01.180  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 10:48:01.188  3944  3944 I art     : System.exit called, status: 0
,08-04 10:48:01.188  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 10:48:01.249   873  1794 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,08-04 10:48:02.116   873  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-04 10:48:03.589  1523  1988 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-04 10:48:03.669  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 10:48:03.669  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:06.678  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:48:06.678  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@469dc6d added. We now have 6 listener(s)
,08-04 10:48:06.679  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:48:06.683  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:48:06.683  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8a40a2 added. We now have 7 listener(s)
,08-04 10:48:06.683  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:48:06.686  3838  3885 I System.out: IsBluetoothEnabled
,08-04 10:48:06.696  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:06.733   873   890 I ActivityManager: Start proc 4173:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 10:48:06.844  4173  4173 D AdapterServiceConfig: Adding HeadsetService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding A2dpService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding HidService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding HealthService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding PanService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding GattService
,08-04 10:48:06.845  4173  4173 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 10:48:06.859   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc59f2c:true
,08-04 10:48:06.859  4173  4173 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 10:48:06.863  4173  4173 I bt_bluedroid: init
,08-04 10:48:06.864  4173  4185 I BluetoothAdapterState: Entering OffState
,08-04 10:48:06.869  4173  4186 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 10:48:06.869  4173  4186 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-04 10:48:06.870  4173  4186 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 10:48:06.870  4173  4186 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 10:48:06.872  4173  4173 I bt_bluedroid: get_profile_interface socket
,08-04 10:48:06.874  4173  4173 I bt_bluedroid: get_profile_interface sdp
,08-04 10:48:06.876  4173  4189 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 10:48:06.877  4173  4189 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 10:48:06.880  4173  4184 I bt_bluedroid: config_hci_snoop_log
,08-04 10:48:06.882   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 10:48:06.890  4173  4185 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 10:48:06.891  4173  4185 D BluetoothAdapterProperties: Setting state to 14
,08-04 10:48:06.891  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 10:48:06.896  4173  4185 D BluetoothBondStateMachine: make
,08-04 10:48:06.901  4173  4190 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 10:48:06.908  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
,08-04 10:48:06.912  4173  4173 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 10:48:06.921  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:06.923  4173  4173 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:48:06.924  4173  4173 D BtGatt.GattService: Received start request. Starting profile...
,08-04 10:48:06.925  4173  4173 D BtGatt.GattService: start(),
08-04 10:48:06.925  4173  4173 I bt_bluedroid: get_profile_interface gatt
08-04 10:48:06.927  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
08-04 10:48:06.928  4173  4173 D BtGatt.AdvertiseManager: advertise manager created
,08-04 10:48:06.936  4173  4173 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:48:06.936  4173  4173 V BluetoothAdapterState: isTurningOn()=false
,08-04 10:48:06.936  4173  4173 V BluetoothAdapterState: isBleTurningOn()=true
,08-04 10:48:06.937  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:06.937  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-04 10:48:06.938  4173  4185 I bt_bluedroid: enable
08-04 10:48:06.938  4173  4186 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-04 10:48:06.939  4173  4186 I bt_hci  : start_up
,08-04 10:48:06.947  4173  4186 I bt_vendor: alloc value 0xb39fc189
,08-04 10:48:06.947  4173  4186 I bt_vendor: init
,08-04 10:48:06.947  4173  4186 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf,
,08-04 10:48:06.947  4173  4186 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 10:48:07.054  4173  4186 D bt_hci  : start_up starting async portion
,08-04 10:48:07.055  4173  4193 I bt_hci  : event_finish_startup
08-04 10:48:07.055  4173  4193 I bt_hci_h4: hal_open
08-04 10:48:07.055  4173  4193 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 10:48:07.064  4173  4193 I bt_userial_vendor: device fd = 51 open
,08-04 10:48:07.096  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:48:07.128  4173  4193 D bt_hwcfg: Chipset BCM4354A2
,08-04 10:48:07.128  4173  4193 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 10:48:07.129  4173  4193 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 10:48:07.785  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 10:48:07.786  4173  4193 D bt_hwcfg: Settlement delay -- 100 ms
08-04 10:48:07.786  4173  4193 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 10:48:07.903  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:48:07.904  4173  4193 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 10:48:07.934  4173  4193 I bt_hwcfg: vendor lib fwcfg completed
,08-04 10:48:07.934  4173  4193 I bt_vendor: firmware callback
08-04 10:48:07.934  4173  4193 I bt_hci  : firmware_config_callback
,08-04 10:48:07.945  4173  4195 I bt_btu  : btu_task pending for preload complete event
,08-04 10:48:07.945  4173  4195 I bt_btu_task: Bluetooth chip preload is complete
08-04 10:48:07.946  4173  4195 I bt_btu  : btu_task received preload complete event
,08-04 10:48:07.957  4173  4195 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 10:48:07.958  4173  4195 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 10:48:07.960  4173  4195 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-04 10:48:07.960  4173  4195 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 10:48:07.960  4173  4195 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 10:48:07.961  4173  4195 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:48:07.961  4173  4195 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 10:48:07.961  4173  4195 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:48:07.961  4173  4195 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 10:48:07.962  4173  4195 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 10:48:07.962  4173  4195 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 10:48:07.962  4173  4195 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 10:48:07.963  4173  4195 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:48:07.963  4173  4195 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 10:48:07.963  4173  4195 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 10:48:08.102  4173  4195 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3979d9d
,08-04 10:48:08.103  4173  4195 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3979d9d 
,08-04 10:48:08.118  4173  4189 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 10:48:08.120  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-04 10:48:08.121  4173  4189 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
08-04 10:48:08.123  4173  4189 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 10:48:08.129  4173  4189 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:48:08.130  4173  4189 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:48:08.130  4173  4189 D bt_hci  : do_postload posting postload work item
,08-04 10:48:08.130  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:08.130  4173  4193 I bt_hci  : event_postload
08-04 10:48:08.131  4173  4193 I bt_vendor: sco_config_cb,
08-04 10:48:08.131  4173  4193 I bt_hci  : sco_config_callback postload finished.
08-04 10:48:08.134  4173  4189 D bt_bte_conf: Device ID record 1 : primary
08-04 10:48:08.134  4173  4189 D bt_bte_conf:   vendorId            = 000f
08-04 10:48:08.134  4173  4189 D bt_bte_conf:   vendorIdSource      = 0001
,08-04 10:48:08.135  4173  4189 D bt_bte_conf:   product             = 1200
08-04 10:48:08.135  4173  4189 D bt_bte_conf:   version             = 1436
08-04 10:48:08.136  4173  4189 D bt_bte_conf:   clientExecutableURL = 
08-04 10:48:08.136  4173  4189 D bt_bte_conf:   serviceDescription  = 
08-04 10:48:08.136  4173  4189 D bt_bte_conf:   documentationURL    = 
08-04 10:48:08.136  4173  4189 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 10:48:08.136  4173  4193 I bt_vendor: low_power_mode_cb
08-04 10:48:08.137  4173  4186 D bt_stack_manager: event_start_up_stack finished
08-04 10:48:08.138  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 10:48:08.138  4173  4185 D BluetoothAdapterProperties: Setting state to 15
,08-04 10:48:08.138  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 10:48:08.138  4173  4185 I BluetoothAdapterState: Entering BleOnState
,08-04 10:48:08.144  4173  4185 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 10:48:08.144  4173  4185 D BluetoothAdapterProperties: Setting state to 11
08-04 10:48:08.144  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 10:48:08.149  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:08.150  4173  4173 D HeadsetService: Received start request. Starting profile...
08-04 10:48:08.153  4173  4173 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 10:48:08.154  4173  4173 D HeadsetStateMachine: make
,08-04 10:48:08.167  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:08.174  4173  4173 D HeadsetStateMachine: max_hf_connections = 1
,08-04 10:48:08.174  4173  4173 I bt_bluedroid: get_profile_interface handsfree
08-04 10:48:08.175  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 10:48:08.176  4173  4189 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 10:48:08.181  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:08.182  4173  4173 D A2dpService: Received start request. Starting profile...
,08-04 10:48:08.183  4173  4173 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-04 10:48:08.184  4173  4173 I bt_bluedroid: get_profile_interface avrcp
,08-04 10:48:08.189  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
,08-04 10:48:08.198  4173  4173 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 10:48:08.198  4173  4173 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:48:08.198  4173  4173 D A2dpStateMachine: make
,08-04 10:48:08.201  4173  4173 I bt_bluedroid: get_profile_interface a2dp
,08-04 10:48:08.202  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 10:48:08.208  4173  4173 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 10:48:08.209  4173  4205 D A2dpStateMachine: Enter Disconnected: -2
,08-04 10:48:08.210  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:08.211  4173  4173 D HidService: Received start request. Starting profile...
08-04 10:48:08.211  4173  4173 I bt_bluedroid: get_profile_interface hidhost
,08-04 10:48:08.212  4173  4189 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395b3e5
08-04 10:48:08.212  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 10:48:08.212  4173  4173 D HidService: setHidService(): set to: null
,08-04 10:48:08.214  4173  4173 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 10:48:08.215  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
08-04 10:48:08.216  4173  4173 D HealthService: Received start request. Starting profile...
,08-04 10:48:08.219  4173  4173 I bt_bluedroid: get_profile_interface health
,08-04 10:48:08.220  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:08.220  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-04 10:48:08.220  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:08.220  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 10:48:08.224  4173  4203 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 10:48:08.227  4173  4173 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 10:48:08.228  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:08.229  4173  4173 D PanService: Received start request. Starting profile...
,08-04 10:48:08.230  4173  4173 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:48:08.230  4173  4173 I bt_bluedroid: get_profile_interface pan
,08-04 10:48:08.231  4173  4189 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 10:48:08.231  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:48:08.233  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
08-04 10:48:08.234  4173  4173 D BluetoothMapService: Received start request. Starting profile...,
08-04 10:48:08.234  4173  4173 D BluetoothMapService: start()
08-04 10:48:08.237  4173  4173 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 10:48:08.238  4173  4173 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 10:48:08.238  4173  4173 D BluetoothMapAppObserver: createReceiver()
,08-04 10:48:08.239  4173  4173 D BluetoothMapAppObserver: initObservers()
08-04 10:48:08.239  4173  4173 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 10:48:08.246  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:08.246  4173  4173 V BluetoothAdapterState: isTurningOn()=true
,08-04 10:48:08.246  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:08.246  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOff()=false
,08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:08.247  4173  4173 V BluetoothAdapterState: isTurningOn()=true
,08-04 10:48:08.248  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:08.248  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:08.251  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-04 10:48:08.251  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-04 10:48:08.251  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 10:48:08.251  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-04 10:48:08.252  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 10:48:08.252  4173  4185 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:48:08.252  4173  4185 D BluetoothAdapterProperties: State =  11
08-04 10:48:08.252  4173  4185 D BluetoothAdapterProperties: Setting state to 12
08-04 10:48:08.252  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 10:48:08.256  4173  4185 I BluetoothAdapterState: Entering OnState
08-04 10:48:08.256  1358  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 10:48:08.257  3892  3903 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 10:48:08.258  3892  3902 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:48:08.258  4173  4189 D BluetoothAdapterProperties: Scan Mode:21
,08-04 10:48:08.259  4173  4189 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:48:08.261  1358  3837 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:48:08.263  3892  3892 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:48:08.263  1358  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 10:48:08.263  3892  3892 D PanProfile: Bluetooth service connected
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:08.265  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:08.265  1358  1358 D BluetoothA2dp: Proxy object connected
08-04 10:48:08.266  1358  1377 D BluetoothMap: onBluetoothStateChange: up=true
08-04 10:48:08.267  4173  4173 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 10:48:08.268  4173  4173 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-04 10:48:08.270  3892  3903 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 10:48:08.270  4173  4173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:48:08.272  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:08.272  3892  3902 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 10:48:08.273  4173  4173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:48:08.274  1358  3837 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 10:48:08.275  4173  4173 D ObexServerSockets: Succeed to create listening sockets 
08-04 10:48:08.275  4173  4173 D ObexServerSockets0: startAccept()
08-04 10:48:08.275  4173  4173 D ObexServerSockets0: prepareForNewConnect()
08-04 10:48:08.276  1358  1859 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:48:08.277  4173  4173 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-04 10:48:08.278  4173  4173 D BluetoothSdpJni: SDP Create record success - handle: 0
08-04 10:48:08.278  4173  4212 D ObexServerSockets0: Accepting socket connection...
08-04 10:48:08.278  4173  4213 D ObexServerSockets0: Accepting socket connection...
08-04 10:48:08.278  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:48:08.278  1358  1358 D PanProfile: Bluetooth service connected
08-04 10:48:08.279  1358  1358 D BluetoothInputDevice: Proxy object connected
08-04 10:48:08.279  1358  1358 D HidProfile: Bluetooth service connected
08-04 10:48:08.279  3892  4166 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 10:48:08.281  1358  1358 D BluetoothMap: Proxy object connected
08-04 10:48:08.281  1358  1358 D MapProfile: Bluetooth service connected
08-04 10:48:08.281  1358  1358 D BluetoothMap: getConnectedDevices()
08-04 10:48:08.282   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 10:48:08.283  3892  3892 D BluetoothInputDevice: Proxy object connected
,08-04 10:48:08.283  1750  3440 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:48:08.283   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:48:08.284   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:48:08.284  3892  3903 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:48:08.286   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:48:08.286   873   873 D BluetoothA2dp: Proxy object connected
,08-04 10:48:08.283  3892  3892 D HidProfile: Bluetooth service connected
,08-04 10:48:08.290  4173  4173 D BluetoothMapService: onReceive
,08-04 10:48:08.290  4173  4173 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:48:08.290  4173  4173 D BluetoothMapService: STATE_ON
08-04 10:48:08.291  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:08.292   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 10:48:08.293  3892  3892 D BluetoothMap: Proxy object connected
08-04 10:48:08.293  3892  3892 D MapProfile: Bluetooth service connected
,08-04 10:48:08.293  3892  3892 D BluetoothMap: getConnectedDevices()
,08-04 10:48:08.295  3892  3892 D BluetoothA2dp: Proxy object connected
,08-04 10:48:08.300  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:48:08.305  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:48:08.306  3892  3892 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:48:08.313  3892  3892 D BluetoothPbap: Proxy object connected
,08-04 10:48:08.313  3892  3892 D PbapServerProfile: Bluetooth service connected
08-04 10:48:08.313  1358  1358 D BluetoothPbap: Proxy object connected
08-04 10:48:08.313  1358  1358 D PbapServerProfile: Bluetooth service connected
,08-04 10:48:08.317  4173  4173 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 10:48:08.317  4173  4173 D ObexServerSockets0: prepareForNewConnect()
,08-04 10:48:08.321  4173  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:48:08.335  4173  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:48:08.336  4173  4221 I BtOppRfcommListener: Accept thread started.
,08-04 10:48:08.358  3892  3902 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.358  3892  3892 D HeadsetProfile: Bluetooth service connected
,08-04 10:48:08.359  1750  1762 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.360  1358  3837 D BluetoothHeadset: Proxy object connected
08-04 10:48:08.360  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-04 10:48:08.361   873   873 D BluetoothHeadset: Proxy object connected
08-04 10:48:08.361   873   873 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.361   873   873 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.383   873   890 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.384  1750  1923 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.385   873   890 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.385   873   890 D BluetoothHeadset: Proxy object connected
,08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:08.718  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:08.725  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:08.729  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:48:08.729  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8db1133 added. We now have 8 listener(s)
,08-04 10:48:08.730  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:48:08.736   873  1749 D WifiService: setWifiEnabled: false pid=3838, uid=10000
,08-04 10:48:08.736   873  1749 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:48:08.748  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:08.749   873  1791 D WifiService: setWifiEnabled: true pid=3838, uid=10000
,08-04 10:48:08.750   873  1791 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:48:08.763   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:08.781  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:08.785   873  1314 D WifiConfigStore: loaded 0 passpoint configs
08-04 10:48:08.785   873  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 10:48:08.786   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-04 10:48:08.787   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-04 10:48:08.787  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:08.788   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-04 10:48:08.789   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-04 10:48:08.789   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-04 10:48:08.789   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 10:48:08.810   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 10:48:08.812   373   872 D CommandListener: Setting iface cfg
08-04 10:48:08.812   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-04 10:48:08.812   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:48:08.813   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 10:48:08.817   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 10:48:08.818   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 10:48:08.878   873  1314 E native  : do suspend true
,08-04 10:48:08.919   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:09.772  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:09.779  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:09.793  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 10:48:09.795  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 10:48:09.803  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fd1efb Bundle[{}]
,08-04 10:48:09.805  3838  3885 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 10:48:09.806  3838  3885 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 10:48:09.808  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-04 10:48:09.810  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 10:48:09.812  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 10:48:09.817  3838  3885 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 10:48:09.822  3838  3885 I System.out: Running OutgoingSocketThread
,08-04 10:48:09.825  3838  4227 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 444)
,08-04 10:48:09.827  3838  4227 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48883
,08-04 10:48:09.827  3838  4227 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 10:48:10.291   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 10:48:10.445   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.06 rxSuccessRate=13.81 delta 1000 -> 994
,08-04 10:48:10.446   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 10:48:10.447   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:48:10.468   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 10:48:10.513   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 10:48:10.515  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 10:48:10.825  3838  3885 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 445)
,08-04 10:48:10.826  3838  3885 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 445)
,08-04 10:48:10.838  3838  3885 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-04 10:48:10.841  3838  3885 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 10:48:10.842  3838  3885 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,08-04 10:48:10.846  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:10.846  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f60cf0 added. We now have 2 listener(s)
,08-04 10:48:10.848  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:10.848  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:10.848  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:10.848  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:10.848  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@654d269 added. We now have 9 listener(s)
08-04 10:48:10.849  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:10.850  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:48:10.859  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:10.865  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:10.868  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:10.868  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:48:10.869  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 10:48:10.869  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bab8d8f added. We now have 3 listener(s)
08-04 10:48:10.870  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:10.871  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:10.871  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:10.871  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:10.871  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c7081c added. We now have 10 listener(s)
,08-04 10:48:10.871  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:10.871  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:48:10.871  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:10.871  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:48:10.872  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:10.872  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.872  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:48:10.872  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:10.872  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:10.872  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f60cf0 removed from the list
08-04 10:48:10.872  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.872  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@654d269 removed from the list
08-04 10:48:10.875  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:10.876  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:48:10.876  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:10.877  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.877  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:10.880  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 10:48:10.880  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:10.881  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.881  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@654d269 not in the list,
08-04 10:48:10.881  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.881  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:10.884  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:48:10.884  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:10.884  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.885  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c7081c removed from the list,
08-04 10:48:10.885  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:10.885  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.886  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:10.886  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:10.886  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bab8d8f removed from the list
,08-04 10:48:10.888  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 10:48:10.889  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df2c25 added. We now have 2 listener(s)
,08-04 10:48:10.894  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 10:48:10.894  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:10.895  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:10.895  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:48:10.896  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21741fa added. We now have 9 listener(s)
,08-04 10:48:10.896  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:48:10.897  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:48:10.902  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:10.910  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:10.914  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:10.914  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:48:10.915  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:10.915  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a8a08 added. We now have 3 listener(s)
,08-04 10:48:10.917  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:10.919  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:10.920  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 10:48:10.921  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:10.921  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 10:48:10.922  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:48:10.922  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfb65a1 added. We now have 10 listener(s)
,08-04 10:48:10.922  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:10.923  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:10.923  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:48:10.923  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 10:48:10.924  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:48:10.924  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:48:10.930  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:48:10.930  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:48:10.934  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:48:10.935  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 10:48:10.935  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:48:10.939  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 10:48:10.939  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 10:48:10.939  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 10:48:10.940  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:48:10.943  4173  4211 D BtGatt.GattService: registerClient() - UUID=bf2d5f9b-a600-4412-a26c-0dc2cba850ae
,08-04 10:48:10.945  4173  4189 D BtGatt.GattService: onClientRegistered() - UUID=bf2d5f9b-a600-4412-a26c-0dc2cba850ae, clientIf=5
,08-04 10:48:10.946  3838  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 10:48:10.947  4173  4210 D BtGatt.GattService: start scan with filters
,08-04 10:48:10.951  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:48:10.952  4173  4192 D BtGatt.ScanManager: handling starting scan
08-04 10:48:10.952  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 10:48:10.952  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 10:48:10.952  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 10:48:10.955  4173  4192 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@69023df
,08-04 10:48:10.956  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 10:48:10.957  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 10:48:10.957  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 10:48:10.958  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 10:48:10.961  4173  4189 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 10:48:10.961  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:48:10.963  4173  4192 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 10:48:10.965  3838  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 10:48:10.966  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:48:10.966  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 10:48:10.966  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:48:10.966  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 10:48:10.966  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 10:48:10.967  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 10:48:10.967  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 10:48:10.967  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:48:10.968  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 10:48:10.968  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 10:48:10.970  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:48:10.971  4173  4210 D BtGatt.GattService: stopScan() - queue size =1
08-04 10:48:10.972  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 10:48:10.972  4173  4184 D BtGatt.GattService: unregisterClient() - clientIf=5,
,08-04 10:48:10.972  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 10:48:10.973  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:48:10.973  4173  4192 D BtGatt.ScanManager: Starting BLE batch scan
08-04 10:48:10.973  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 10:48:10.973  4173  4192 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 10:48:10.973  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 10:48:10.974  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 10:48:10.974  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 10:48:10.975  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:48:10.975  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 10:48:10.976  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:48:10.976  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:48:10.976  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:48:10.977  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-04 10:48:10.978  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:10.978  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:10.978  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:48:10.981  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:48:10.981  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:10.981  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:48:10.981  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:10.981  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.981  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:48:10.981  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:10.981  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df2c25 removed from the list
,08-04 10:48:10.981  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.981  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21741fa removed from the list
08-04 10:48:10.982  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:48:10.982  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:10.985  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.985  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:10.986  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 10:48:10.986  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:10.987  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.987  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21741fa not in the list
08-04 10:48:10.987  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.987  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:10.989  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:10.989  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:10.989  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:10.990  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfb65a1 removed from the list
08-04 10:48:10.990  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:10.990  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:10.990  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:48:10.990  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:10.990  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a8a08 removed from the list
08-04 10:48:10.992  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:10.992  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a47badd added. We now have 2 listener(s)
08-04 10:48:10.994  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:10.994  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:10.994  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:10.994  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:10.994  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f681652 added. We now have 9 listener(s)
08-04 10:48:10.994  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:48:10.995  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:48:10.995  4173  4189 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 10:48:10.996  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-04 10:48:10.997  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:11.002  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,08-04 10:48:11.004  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:48:11.004  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:48:11.005  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 10:48:11.005  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de9220 added. We now have 3 listener(s),
08-04 10:48:11.006  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:11.007  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:11.007  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:48:11.007  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:11.007  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:11.007  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a27d9 added. We now have 10 listener(s)
08-04 10:48:11.007  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-04 10:48:11.007  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:11.008  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:11.008  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:11.008  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:48:11.008  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:48:11.008  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-04 10:48:11.008  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:48:11.011  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 10:48:11.012  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:48:11.012  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:48:11.012  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.014  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:48:11.014  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-04 10:48:11.017   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.,
,08-04 10:48:11.023   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 10:48:11.024   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:48:11.023  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:48:11.025   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 10:48:11.026  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 10:48:11.026  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 10:48:11.026  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:48:11.026  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.026  4173  4192 D BtGatt.ScanManager: stopping BLe Batch
,08-04 10:48:11.030  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 10:48:11.030  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 10:48:11.030  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 10:48:11.031  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:48:11.032  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 10:48:11.032  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.033  4173  4192 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 10:48:11.035  4173  4211 D BtGatt.GattService: registerClient() - UUID=dac8b28e-0cd2-4540-9b53-0a2676269607
08-04 10:48:11.035  4173  4189 D BtGatt.GattService: onClientRegistered() - UUID=dac8b28e-0cd2-4540-9b53-0a2676269607, clientIf=5
,08-04 10:48:11.036  3838  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 10:48:11.036  4173  4210 D BtGatt.GattService: start scan with filters
,08-04 10:48:11.038  4173  4189 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 10:48:11.038   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:48:11.038  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.040  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:48:11.040  4173  4192 D BtGatt.ScanManager: handling starting scan
08-04 10:48:11.040  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 10:48:11.040  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 10:48:11.041  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 10:48:11.045  4173  4189 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 10:48:11.045  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.046  4173  4192 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 10:48:11.046   373   872 D CommandListener: Setting iface cfg
,08-04 10:48:11.047  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:48:11.047  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 10:48:11.047  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:48:11.047   873  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-04 10:48:11.051  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 10:48:11.051  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.051  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 10:48:11.052  4173  4192 D BtGatt.ScanManager: Starting BLE batch scan
08-04 10:48:11.052  4173  4192 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 10:48:11.054   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 10:48:11.057  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:11.057  3838  3885 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-04 10:48:11.057  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:48:11.057  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:11.057  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:48:11.057  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.057  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.057  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 10:48:11.057  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.058  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a47badd removed from the list
08-04 10:48:11.058  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.058  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f681652 removed from the list
08-04 10:48:11.058  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:48:11.058  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:48:11.058  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.058  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 10:48:11.058  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.058  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:48:11.060  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.061  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.061  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.061  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f681652 not in the list
,08-04 10:48:11.061  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:48:11.061  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:48:11.061  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:48:11.061  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:48:11.061  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 10:48:11.061  3838  3885 D BluetoothAdapter: STATE_ON
,08-04 10:48:11.062  4173  4211 D BtGatt.GattService: stopScan() - queue size =1
,08-04 10:48:11.064  4173  4210 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 10:48:11.064   873  4230 D DhcpClient: Receive thread started
,08-04 10:48:11.064  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:48:11.064  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 10:48:11.064  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 10:48:11.064  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 10:48:11.064  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 10:48:11.066  4173  4189 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 10:48:11.066  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.066  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:48:11.066  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 10:48:11.066  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:48:11.066  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:48:11.067  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.068  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.068  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.068  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.068  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:11.068  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a27d9 removed from the list
,08-04 10:48:11.068  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.068  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:11.068  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.068  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.068  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 10:48:11.068  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.068  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de9220 removed from the list
08-04 10:48:11.069  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:11.069  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fec6895 added. We now have 2 listener(s)
08-04 10:48:11.070  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 10:48:11.070  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.072  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 10:48:11.073  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:48:11.073  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:11.073  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:11.073  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c41daa added. We now have 9 listener(s)
08-04 10:48:11.073  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:11.074  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:48:11.080  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:48:11.080  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 10:48:11.080  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.081  4173  4192 D BtGatt.ScanManager: stopping BLe Batch
,08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:11.083  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:48:11.085  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:48:11.085  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 10:48:11.085  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.086  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:48:11.086  4173  4192 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 10:48:11.086  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:11.086  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b88538 added. We now have 3 listener(s)
08-04 10:48:11.088  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:11.088  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:48:11.088  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:11.088  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:11.088  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@677f911 added. We now have 10 listener(s)
08-04 10:48:11.088  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:11.088  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:11.088  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:48:11.088  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:48:11.088  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:48:11.088  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:48:11.089  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:11.090  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:48:11.092  4173  4189 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 10:48:11.092  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.092  3838  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 10:48:11.092  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:48:11.096  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:48:11.097  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 10:48:11.097  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:48:11.106  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 10:48:11.106  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 10:48:11.106  3838  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 10:48:11.106  3838  3885 D BluetoothAdapter: STATE_ON
08-04 10:48:11.108  4173  4211 D BtGatt.GattService: registerClient() - UUID=8943fca2-09a6-48cb-bd33-d14e1b24702b
08-04 10:48:11.108  4173  4189 D BtGatt.GattService: onClientRegistered() - UUID=8943fca2-09a6-48cb-bd33-d14e1b24702b, clientIf=5
08-04 10:48:11.109  3838  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 10:48:11.109  4173  4184 D BtGatt.GattService: start scan with filters
08-04 10:48:11.113  4173  4192 D BtGatt.ScanManager: handling starting scan
08-04 10:48:11.113  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 10:48:11.113  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 10:48:11.113  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 10:48:11.113  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 10:48:11.117  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:48:11.117  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 10:48:11.117  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 10:48:11.118  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 10:48:11.119  4173  4189 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 10:48:11.119  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.120  4173  4192 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 10:48:11.123  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:48:11.123  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:11.123  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:48:11.123  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.123  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.123  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 10:48:11.123  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.124  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fec6895 removed from the list
08-04 10:48:11.124  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.124  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c41daa removed from the list
08-04 10:48:11.124  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:48:11.124  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:48:11.124  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.124  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 10:48:11.124  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.125  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:48:11.125  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.125  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.125  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.125  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c41daa not in the list
08-04 10:48:11.125  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:48:11.125  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:48:11.125  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:48:11.126  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:48:11.126  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 10:48:11.126  3838  3885 D BluetoothAdapter: STATE_ON
08-04 10:48:11.128  4173  4184 D BtGatt.GattService: stopScan() - queue size =1
08-04 10:48:11.128  4173  4183 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 10:48:11.128  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:48:11.129  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 10:48:11.129  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 10:48:11.129  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 10:48:11.129  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 10:48:11.130  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:48:11.130  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 10:48:11.130  3838  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:48:11.130  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:48:11.130  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.131  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:11.131  3838  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:48:11.131  3838  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:48:11.131  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.131  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.131  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.131  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@677f911 removed from the list
08-04 10:48:11.131  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.132  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 10:48:11.132  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.131  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.132  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.132  4173  4192 D BtGatt.ScanManager: Starting BLE batch scan
08-04 10:48:11.132  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.132  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b88538 removed from the list
08-04 10:48:11.132  4173  4192 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 10:48:11.133  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:11.133  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d52154d added. We now have 2 listener(s)
08-04 10:48:11.134  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:11.134  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:48:11.134  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:11.134  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:11.134  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4feb802 added. We now have 9 listener(s)
08-04 10:48:11.134  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:11.135  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:48:11.138  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:48:11.140  3838  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:48:11.142  3838  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:48:11.142  3838  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:48:11.143  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:11.144  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:48:11.144  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ac350 added. We now have 3 listener(s)
08-04 10:48:11.144  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:48:11.146  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 10:48:11.146  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:48:11.146  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:48:11.146  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:48:11.146  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@737b949 added. We now have 10 listener(s)
08-04 10:48:11.146  3838  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:48:11.146  3838  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:48:11.146  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:11.147  3838  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:48:11.147  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.147  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.147  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:48:11.147  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.147  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d52154d removed from the list
08-04 10:48:11.147  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.147  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4feb802 removed from the list
08-04 10:48:11.147  3838  3885 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:48:11.147  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.148  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.148  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.148  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.148  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.148  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.148  3838  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4feb802 not in the list
08-04 10:48:11.148  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.149  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.149   873  1314 E native  : do suspend false
08-04 10:48:11.150  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:48:11.150  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:48:11.150  3838  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:48:11.150  3838  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@737b949 removed from the list
08-04 10:48:11.150  3838  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:48:11.150  3838  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:48:11.150  3838  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:48:11.150  3838  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:48:11.150  4173  4189 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 10:48:11.150  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.150  3838  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ac350 removed from the list
08-04 10:48:11.151  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 10:48:11.151  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 10:48:11.151  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 10:48:11.151  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:48:11.151  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 10:48:11.152  3838  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:48:11.156  3838  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
08-04 10:48:11.156  3838  4231 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: My test thread name)
08-04 10:48:11.156  3838  4231 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:48:11.158  3838  4232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
08-04 10:48:11.158  3838  4232 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
08-04 10:48:11.158  3838  4232 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:48:11.160  3838  3885 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 10:48:11.160  3838  3885 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 10:48:11.160  3838  3885 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 10:48:11.160  3838  3885 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 10:48:11.160  3838  3885 D com.test.thalitest.ThaliTestRunner: Total duration: 22953 ms
08-04 10:48:11.162   873  2009 D DhcpClient: Broadcasting DHCPDISCOVER
08-04 10:48:11.162  3838  3885 I jxcore-log: Total number of executed tests:  80
08-04 10:48:11.162  3838  3885 I jxcore-log: 
08-04 10:48:11.163  3838  3885 I jxcore-log: Number of passed tests:  80
08-04 10:48:11.163  3838  3885 I jxcore-log: 
08-04 10:48:11.163  3838  3885 I jxcore-log: Number of failed tests:  0
08-04 10:48:11.163  3838  3885 I jxcore-log: 
08-04 10:48:11.163  3838  3885 I jxcore-log: Number of ignored tests:  0
08-04 10:48:11.163  3838  3885 I jxcore-log: 
08-04 10:48:11.163  3838  3885 I jxcore-log: Total duration:  22953
08-04 10:48:11.163  3838  3885 I jxcore-log: 
08-04 10:48:11.164  3838  3885 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-04 10:48:11.164  3838  3885 I jxcore-log: 
08-04 10:48:11.164  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 10:48:11.165  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.166  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.166  3838  3885 I jxcore-log: 
,08-04 10:48:11.169  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.169  3838  3885 I jxcore-log: 
08-04 10:48:11.170  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.170  3838  3885 I jxcore-log: 
08-04 10:48:11.171  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.171  3838  3885 I jxcore-log: 
08-04 10:48:11.172  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.172  3838  3885 I jxcore-log: 
08-04 10:48:11.174  3838  3838 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 10:48:11.174  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.174  3838  3885 I jxcore-log: 
08-04 10:48:11.174  4173  4189 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 10:48:11.175  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.175  4173  4192 D BtGatt.ScanManager: stopping BLe Batch
08-04 10:48:11.176  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.176  3838  3885 I jxcore-log: 
08-04 10:48:11.177  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.177  3838  3885 I jxcore-log: 
08-04 10:48:11.178  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.178  3838  3885 I jxcore-log: 
08-04 10:48:11.178   873  4230 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
08-04 10:48:11.178  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.178  3838  3885 I jxcore-log: 
08-04 10:48:11.179   873  2009 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
08-04 10:48:11.179   873  2009 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
08-04 10:48:11.180  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.180  3838  3885 I jxcore-log: 
08-04 10:48:11.181  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:48:11.181  3838  3885 I jxcore-log: 
08-04 10:48:11.182  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.182  3838  3885 I jxcore-log: 
08-04 10:48:11.182  4173  4189 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 10:48:11.182  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:1,1.183  4173  4192 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 10:48:11.183  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.183  3838  3885 I jxcore-log: 
08-04 10:48:11.183  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.183  3838  3885 I jxcore-log: 
08-04 10:48:11.184  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.184  3838  3885 I jxcore-log: 
08-04 10:48:11.184  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.184  3838  3885 I jxcore-log: 
08-04 10:48:11.185  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.185  3838  3885 I jxcore-log: 
08-04 10:48:11.185  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.185  3838  3885 I jxcore-log: 
08-04 10:48:11.186  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.186  3838  3885 I jxcore-log: 
08-04 10:48:11.186  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.186  3838  3885 I jxcore-log: 
08-04 10:48:11.187  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.187  3838  3885 I jxcore-log: 
08-04 10:48:11.187  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.187  3838  3885 I jxcore-log: 
08-04 10:48:11.188  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:48:11.188  3838  3885 I jxcore-log: 
08-04 10:48:11.189  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.189  3838  3885 I jxcore-log: 
08-04 10:48:11.189  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.189  3838  3885 I jxcore-log: 
08-04 10:48:11.190  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.190  3838  3885 I jxcore-log: 
08-04 10:48:11.190  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.190  3838  3885 I jxcore-log: 
08-04 10:48:11.190  4173  4189 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 10:48:11.190  4173  4189 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 10:48:11.191  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.191  3838  3885 I jxcore-log: 
08-04 10:48:11.191  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare",}
08-04 10:48:11.191  3838  3885 I jxcore-log: 
08-04 10:48:11.192  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:48:11.192  3838  3885 I jxcore-log: 
08-04 10:48:11.198   873  4230 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-04 10:48:11.198   873  2009 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-04 10:48:11.199   373   872 D CommandListener: Setting iface cfg
08-04 10:48:11.201   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-04 10:48:11.203   873  2009 D DhcpClient: Scheduling renewal in 86399s
08-04 10:48:11.203   873  1314 E native  : do suspend true
,08-04 10:48:11.213   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 10:48:11.213   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 10:48:11.214   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 10:48:11.215   873  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-04 10:48:11.218   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 10:48:11.256   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 10:48:11.256   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-04 10:48:11.258   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-04 10:48:11.258   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-04 10:48:11.259   873  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-04 10:48:11.267   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 10:48:11.271   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-04 10:48:11.271   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-04 10:48:11.271   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-04 10:48:11.272   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 10:48:11.272   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-04 10:48:11.272   873  1316 D ConnectivityService:    accepting network in place of null
,08-04 10:48:11.273   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 10:48:11.299   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:48:11.325   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 10:48:11.328   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-04 10:48:11.328   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:48:11.332   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:48:11.336  3838  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:48:11.338  3838  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:48:11.339  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:48:11.339  3838  3885 I jxcore-log: 
08-04 10:48:11.339   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-04 10:48:11.362  1819  1819 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-04 10:48:11.370  1844  1844 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 10:48:11.379  1844  1844 D SystemUpdateService: onCreate
,08-04 10:48:11.384  1844  1844 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 10:48:11.409  1844  4245 I SystemUpdateService: active receiver: enabled
,08-04 10:48:11.446  1844  1844 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 10:48:11.479  3838  3838 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 10:48:11.480  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:48:11.480  3838  3885 I jxcore-log: 
08-04 10:48:11.481  1844  2350 I iu.UploadsManager: num queued entries: 0
,08-04 10:48:11.492  1844  1844 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 10:48:11.494  1844  1844 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 10:48:11.497  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:48:11.518  3984  3984 D SprintDMHelper: simOperator: 
,08-04 10:48:11.518  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 10:48:11.524  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 10:48:11.526  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 10:48:11.537  1844  4245 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 10:48:11.545  1844  4248 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 10:48:11.545  1844  4248 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 10:48:11.558  1844  4248 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 10:48:11.569  3838  3838 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-04 10:48:11.570  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:48:11.570  3838  3885 I jxcore-log: 
,08-04 10:48:11.582  1844  2350 I iu.UploadsManager: num updated entries: 0
,08-04 10:48:11.599  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-04 10:48:11.599  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-04 10:48:11.599  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:48:11.599  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:48:11.617  1844  2350 I iu.SyncManager: NEXT; no task
08-04 10:48:11.617  1844  4245 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-04 10:48:11.617  1844  4245 I SystemUpdateService: now status is 0 (complete)
08-04 10:48:11.617  1844  4245 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 10:48:11.617  1844  4245 I SystemUpdateService: file has been verified
08-04 10:48:11.617  1844  4245 I SystemUpdateService: OTA package size = 12249756
08-04 10:48:11.624  3543  4244 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-04 10:48:11.624  3543  4244 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jdm.a(PG:82)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jcs.o(PG:406)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jcn.a(PG:1379)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jcs.i(PG:143)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at blb.a(PG:3937)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at czp.a(PG:18188)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at czp.a(PG:9081)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at czq.run(PG:1686)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-04 10:48:11.624  3543  4244 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jdj.a(PG:4091)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jdj.a(PG:1125)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jdm.a(PG:77)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	... 12 more
08-04 10:48:11.624  3543  4244 E HttpOperation: Caused by: faj: BadAuthentication
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at fal.a(PG:38)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	at jdj.a(PG:4089)
08-04 10:48:11.624  3543  4244 E HttpOperation: 	... 14 more
08-04 10:48:11.631  3838  3838 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 10:48:11.632  3838  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:48:11.632  3838  3885 I jxcore-log: 
,08-04 10:48:11.669  1523  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-04 10:48:11.669  1523  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-04 10:48:11.669  1523  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 10:48:11.669  1523  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:48:11.678   873   882 I art     : Background partial concurrent mark sweep GC freed 43626(2MB) AllocSpace objects, 7(188KB) LOS objects, 33% free, 29MB/43MB, paused 5.676ms total 95.245ms
,08-04 10:48:11.688  1844  4245 I SystemUpdateService: showing system update notification
,08-04 10:48:11.691  3543  4244 E HttpOperation: [getmobileexperiments] Unexpected exception
08-04 10:48:11.691  3543  4244 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jdm.a(PG:82)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jcs.o(PG:406)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jcn.a(PG:1379)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jcs.i(PG:143)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at hec.a(PG:42)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at hee.a(PG:102)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at czr.a(PG:65)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at kka.a(PG:108)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at czp.a(PG:19176)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at czp.a(PG:9081)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at czq.run(PG:1686)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-04 10:48:11.691  3543  4244 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jdj.a(PG:4091)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jdj.a(PG:1125)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jdm.a(PG:77)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	... 15 more
08-04 10:48:11.691  3543  4244 E HttpOperation: Caused by: faj: BadAuthentication
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at fal.a(PG:38)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	at jdj.a(PG:4089)
08-04 10:48:11.691  3543  4244 E HttpOperation: 	... 17 more
,08-04 10:48:11.692  3543  4244 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-04 10:48:11.692  3543  4244 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jdm.a(PG:82)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jcs.o(PG:406)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jcn.a(PG:1379)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jcs.i(PG:143)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at hec.a(PG:42)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at hee.a(PG:102)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at czr.a(PG:65)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at kka.a(PG:108)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at czp.a(PG:19176)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at czp.a(PG:9081)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at czq.run(PG:1686)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jdj.a(PG:4091)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jdj.a(PG:1125)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jdm.a(PG:77)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	... 15 more
08-04 10:48:11.692  3543  4244 E ExperimentLoader: Caused by: faj: BadAuthentication
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at fal.a(PG:38)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	at jdj.a(PG:4089)
08-04 10:48:11.692  3543  4244 E ExperimentLoader: 	... 17 more
,08-04 10:48:11.773   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 282998, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-04 10:48:11.775  1523  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 10:48:11.776  1523  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 10:48:11.776  1523  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-04 10:48:11.777  1523  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 10:48:11.790  1844  1844 D SystemUpdateService: onDestroy
,08-04 10:48:11.802  1844  4248 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-04 10:48:11.853  4234  4234 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 10:48:11.857  4234  4234 D AndroidRuntime: CheckJNI is OFF
,08-04 10:48:11.900  4234  4234 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 10:48:11.947  4234  4234 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 10:48:11.970  4234  4234 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 10:48:11.991   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-04 10:48:11.992   873   886 I ActivityManager: Killing 3838:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-04 10:48:12.063   873  4229 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286174, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 10:48:12.077   873  1783 D GraphicsStats: Buffer count: 2
,08-04 10:48:12.077   873  1688 I WindowState: WIN DEATH: Window{d124fad u0 com.test.thalitest/com.test.thalitest.MainActivity},
08-04 10:48:12.079   873  1315 D WifiService: Client connection lost with reason: 4
,08-04 10:48:12.133   873   896 W PackageSettings: Skipping PackageSetting{9655f50 com.example.hello/10273} due to missing metadata
,08-04 10:48:12.161   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-04 10:48:12.161   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-04 10:48:12.161   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-04 10:48:12.161   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-04 10:48:12.161   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.161   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.161   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 10:48:12.161   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-04 10:48:12.162   873   886 I ActivityManager:   Force finishing activity ActivityRecord{edabdce u0 com.test.thalitest/.MainActivity t2}
,08-04 10:48:12.165   873   896 I art     : Starting a blocking GC Explicit
,08-04 10:48:12.186   873  1783 W ActivityManager: Spurious death for ProcessRecord{38c5a2d 0:com.test.thalitest/u0a0}, curProc for 3838: null
,08-04 10:48:12.234   873   896 I art     : Explicit concurrent mark sweep GC freed 19003(1283KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 836us total 69.358ms
,08-04 10:48:12.293   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 10:48:12.302  4234  4234 I art     : System.exit called, status: 0
,08-04 10:48:12.302  4234  4234 I AndroidRuntime: VM exiting with result code 0.
,08-04 10:48:12.311   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 10:48:12.330   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-04 10:48:12.341  4173  4173 D BluetoothMapAppObserver: onReceive
08-04 10:48:12.341  4173  4173 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-04 10:48:12.343   873  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 10:48:12.345  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
08-04 10:48:12.346  1832  2038 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 10:48:12.346  3669  3669 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-04 10:48:12.360   873  1749 I ActivityManager: Start proc 4269:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-04 10:48:12.393  1750  1750 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-04 10:48:12.418  4269  4269 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-04 10:48:12.420  1662  4276 I Keyboard.Facilitator.DecoderInitializer: run()
08-04 10:48:12.420  1662  4276 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-04 10:48:12.420  1662  4276 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-04 10:48:12.420  1662  4276 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-04 10:48:12.420  1662  4276 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-04 10:48:12.421  1662  4276 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-04 10:48:12.421  1662  4276 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-04 10:48:12.426  1662  4276 I Decoder : createOrResetDecoder
,08-04 10:48:12.442  1523  1523 I ConfigService: onCreate
,08-04 10:48:12.446   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3838 uid 10000
,08-04 10:48:12.448  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-04 10:48:12.448  1523  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 10:48:12.448  1523  4283 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 10:48:12.448  1523  4283 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-04 10:48:12.452  1523  4283 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-04 10:48:12.458   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 10:48:12.469  1662  4276 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-04 10:48:12.479  1768  1869 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-04 10:48:12.479   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-04 10:48:12.480   873   885 E PackageManager: Failed to write settings, restoring backup
08-04 10:48:12.480   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 10:48:12.480   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 10:48:12.480   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 10:48:12.480   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 10:48:12.480   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 10:48:12.480   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.480   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.480   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 10:48:12.484   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-04 10:48:12.484   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 10:48:12.484   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 10:48:12.484   873   886 E DropBoxManagerService: 	... 13 more
,08-04 10:48:12.492   873  1764 I ActivityManager: Start proc 4286:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-04 10:48:12.492  1768  1869 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 10:48:12.492  1768  1869 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1768
08-04 10:48:12.492  1768  1869 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.492  1768  1869 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 10:48:12.494   873  1735 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 10:48:12.495   873  4292 E DropBoxManagerService: Can't write: system_app_crash
08-04 10:48:12.495   873  4292 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 10:48:12.495   873  4292 E DropBoxManagerService: 	... 5 more
08-04 10:48:12.500  1768  1869 I Process : Sending signal. PID: 1768 SIG: 9,
,08-04 10:48:12.513  1662  4276 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-04 10:48:12.515  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-04 10:48:12.515  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-04 10:48:12.517  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-04 10:48:12.517  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-04 10:48:12.517  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-04 10:48:12.517  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-04 10:48:12.518  1662  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-04 10:48:12.518  1662  4276 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-04 10:48:12.518  1662  4276 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-04 10:48:12.518  1662  4276 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-04 10:48:12.518  1662  4276 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-04 10:48:12.518  1662  4276 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-04 10:48:12.520  4269  4269 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-04 10:48:12.553   873  1763 I ActivityManager: Start proc 4302:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-04 10:48:12.560   280   280 E lowmemorykiller: Error writing /proc/1768/oom_score_adj; errno=22
,08-04 10:48:12.551  4269  4307 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 10:48:12.589  4302  4302 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-04 10:48:12.600   280   280 E lowmemorykiller: Error writing /proc/1768/oom_score_adj; errno=22
,08-04 10:48:12.613   873  1677 D GraphicsStats: Buffer count: 1
08-04 10:48:12.613   873  1764 I WindowState: WIN DEATH: Window{7900c07 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-04 10:48:12.624   873  1763 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1768) has died
,08-04 10:48:12.624   873  1763 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-04 10:48:12.626   873  1763 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 10:48:12.630  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-04 10:48:12.632  1523  1523 D AndroidRuntime: Shutting down VM
08-04 10:48:12.633  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
08-04 10:48:12.633  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
,08-04 10:48:12.633  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-04 10:48:12.633  1523  1523 E AndroidRuntime: 	... 8 more
08-04 10:48:12.640   873   886 I ActivityManager: Start proc 4321:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 10:48:12.644   873  4327 E DropBoxManagerService: Can't write: system_app_crash,
08-04 10:48:12.644   873  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 10:48:12.644   873  4327 E DropBoxManagerService: 	... 5 more
08-04 10:48:12.645  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
,08-04 10:48:12.663  4269  4285 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.663  4269  4285 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.664  4269  4285 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 10:48:12.691   873  1315 D WifiService: Client connection lost with reason: 4
08-04 10:48:12.692  1844  4317 E BulkCursor: Unable to get window because the remote process is dead
08-04 10:48:12.693  1844  4317 W BulkCursor: Remote process exception when closing
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:48:12.693  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-,04 10:48:12.693  4321  4321 D AndroidRuntime: Shutting down VM
08-04 10:48:12.697   873  1791 I ActivityManager: Process com.google.process.gapps (pid 1523) has died
08-04 10:48:12.697   873  1791 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-04 10:48:12.698   873  1791 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-04 10:48:12.698   873  1791 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
08-04 10:48:12.698   873  1791 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
08-04 10:48:12.698   873  1791 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 40999ms
08-04 10:48:12.699   873  1791 I ActivityManager: Killing 1844:com.google.android.gms/u0a11 (adj 5): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
08-04 10:48:12.709  4269  4285 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-04 10:48:12.725  4269  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.725  4269  4307 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-04 10:48:12.725  4269  4307 E AndroidRuntime: Process: android.process.acore, PID: 4269
08-04 10:48:12.725  4269  4307 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.725  4269  4307 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.725  4269  4307 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 10:48:12.727  4269  4285 I Process : Sending signal. PID: 4269 SIG: 9
,08-04 10:48:12.755   873  1794 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@7836091)
,08-04 10:48:12.755   873  1316 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:48:12.756   873  1316 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 10:48:12.761  3543  3543 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,08-04 10:48:12.773   873  1764 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 50924ms
,08-04 10:48:12.773   873  1764 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 50924ms
08-04 10:48:12.773   873  1764 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 60924ms
,08-04 10:48:12.796   873   886 I ActivityManager: Start proc 4336:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
,08-04 10:48:12.797   873  1783 I ActivityManager: Process android.process.acore (pid 4269) has died
08-04 10:48:12.798   873  1783 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 70900ms
08-04 10:48:12.799   873  1735 W ActivityManager: Can't find mystery application for Crash from pid=4269 uid=10005: android.os.BinderProxy@d07085
08-04 10:48:12.800   873  1735 E DropBoxManagerService: Can't write: system_server_crash
08-04 10:48:12.800   873  1735 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop80.tmp: open failed: EROFS (Read-only file system)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 10:48:12.800   873  1735 E DropBoxManagerService: 	... 11 more
,08-04 10:48:12.803  4321  4321 E AndroidRuntime: FATAL EXCEPTION: main
08-04 10:48:12.803  4321  4321 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4321
08-04 10:48:12.803  4321  4321 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 10:48:12.803  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP
```
