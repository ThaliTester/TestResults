#### Test 829120309e2869a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 18:32:24.247   871  2078 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:32:24.993  3824  3824 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 18:32:24.998  3824  3824 D AndroidRuntime: CheckJNI is OFF
09-08 18:32:25.033  3824  3824 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 18:32:25.076  3824  3824 I Radio-JNI: register_android_hardware_Radio DONE
09-08 18:32:25.095  3824  3824 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 18:32:25.100   871  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 18:32:25.158   871  1970 I ActivityManager: Start proc 3833:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 18:32:25.164  3824  3824 D AndroidRuntime: Shutting down VM
09-08 18:32:25.261  3833  3833 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 18:32:25.294  3833  3833 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 18:32:25.304  3833  3833 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5636-5641)
09-08 18:32:25.304  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:32:25.328  3833  3833 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ccc151c}
09-08 18:32:25.328  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:32:25.329  3833  3833 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 18:32:25.338  3833  3833 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 18:32:25.339  3833  3833 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 18:32:25.367  3833  3833 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 18:32:25.383  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:32:25.383  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:32:25.383  3833  3833 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 18:32:25.383  3833  3833 I Adreno  : Build Date                       : 10/20/15
09-08 18:32:25.383  3833  3833 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 18:32:25.383  3833  3833 I Adreno  : Local Branch                     : M14
09-08 18:32:25.383  3833  3833 I Adreno  : Remote Branch                    : 
09-08 18:32:25.383  3833  3833 I Adreno  : Remote Branch                    : 
09-08 18:32:25.383  3833  3833 I Adreno  : Reconstruct Branch               : 
,09-08 18:32:25.467   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51a5fcc:true
,09-08 18:32:25.537  3833  3833 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 18:32:25.574  3833  3833 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 18:32:25.669  3833  3871 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 18:32:25.692  3833  3858 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 18:32:25.741  3833  3871 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 18:32:25.820   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +599ms (total +693ms)
,09-08 18:32:25.829  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-08 18:32:25.906  3833  3833 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3833
,09-08 18:32:26.048  3833  3833 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 18:32:26.250  3833  3873 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1694959312
,09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 18:32:26.259  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79005e3 added. We now have 1 listener(s)
,09-08 18:32:26.263  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 18:32:26.265  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:32:26.267  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:32:26.267  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 18:32:26.276  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 18:32:26.277  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@402055e added. We now have 1 listener(s)
,09-08 18:32:26.278  3833  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:32:26.283   871  1304 D WifiService: New client listening to asynchronous messages
,09-08 18:32:26.286  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:32:26.287  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 18:32:26.287  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 18:32:26.288  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 18:32:26.288  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 18:32:26.297  3833  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:32:26.298  3833  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 18:32:26.313  3833  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:26.316  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:32:26.316  3833  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-08 18:32:26.319  3833  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:32:26.322  3833  3873 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 18:32:26.323  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:32:26.324  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:26.358  3833  3833 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 18:32:27.308  3833  3880 W jxcore-log: Initializing JXcore engine
09-08 18:32:27.308  3833  3880 W jxcore-log: JXcore engine is ready
,09-08 18:32:27.344  3880  3880 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 18:32:27.344  3880  3880 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12684]" dev="sockfs" ino=12684 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 18:32:27.344  3880  3880 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 18:32:27.344  3880  3880 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29268]" dev="sockfs" ino=29268 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 18:32:27.359  3833  3880 W jxcore-log: Starting JXcore engine
,09-08 18:32:27.444  3833  3880 W jxcore-log: Platform android
09-08 18:32:27.444  3833  3880 W jxcore-log: 
,09-08 18:32:27.445  3833  3880 W jxcore-log: Process ARCH arm
09-08 18:32:27.445  3833  3880 W jxcore-log: 
,09-08 18:32:27.639  3833  3880 I jxcore-log: JXcore Cordova bridge is ready!
09-08 18:32:27.639  3833  3880 I jxcore-log: 
,09-08 18:32:27.639  3833  3880 W jxcore-log: JXcore engine is started
,09-08 18:32:27.652  3833  3873 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 18:32:27.657  3833  3833 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 18:32:32.733  3017  3881 V KeepSync: Connecting to GoogleApiClient
,09-08 18:32:32.734   871  1998 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 18:32:32.790  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:32:32.795  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:32:32.836  1502  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 18:32:32.836  1502  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 18:32:32.836  1502  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:32:32.836  1502  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:32:32.867  1716  3882 V BaseAuthAsyncOperation: access token request failed
,09-08 18:32:32.869  3017  3881 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 18:32:32.960  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 18:32:32.961  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 18:32:32.961  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:32:32.961  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:32:33.003  3017  3881 E KeepSync: IOException
09-08 18:32:33.003  3017  3881 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 18:32:33.003  3017  3881 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:32:33.003  3017  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 18:32:33.003  3017  3881 E KeepSync: 	... 10 more
,09-08 18:32:33.004  3017  3881 W KeepSync: Sync result 2
,09-08 18:32:33.019   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 283572, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:32:41.311  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 18:32:41.311  3833  3880 I jxcore-log: 
,09-08 18:32:41.314  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 18:32:41.314  3833  3880 I jxcore-log: 
,09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:41.324  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:32:41.329  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:32:41.331  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 18:32:41.331  3833  3880 I jxcore-log: 
,09-08 18:32:41.333  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 18:32:41.333  3833  3880 I jxcore-log: 
,09-08 18:32:41.682  3833  3880 I jxcore-log: Running unit tests
09-08 18:32:41.682  3833  3880 I jxcore-log: 
,09-08 18:32:41.683  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:32:41.683  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91a5863 added. We now have 2 listener(s)
09-08 18:32:41.684  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:32:41.685  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:32:41.685  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:32:41.685  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:32:41.685  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b7fc60 added. We now have 2 listener(s)
09-08 18:32:41.685  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:32:41.686  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:32:41.688  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:41.694  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:32:41.696  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:41.696  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:32:41.697  3833  3880 D executeNativeTests: Running unit tests
,09-08 18:32:41.702  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.709  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.759  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:32:41.759  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e added. We now have 3 listener(s)
09-08 18:32:41.760  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:32:41.760  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:32:41.760  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:32:41.760  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:32:41.760  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf added. We now have 3 listener(s)
09-08 18:32:41.760  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:32:41.761  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:32:41.763  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:41.773  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:32:41.778  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:32:41.778  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:32:41.780  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:32:41.782  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:32:41.782  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:32:41.782  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:32:41.784  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.787  3833  3880 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 18:32:41.788  3833  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
09-08 18:32:41.788  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:32:41.789  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 18:32:41.789  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 18:32:41.789  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:32:41.790  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:41.792  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:32:41.792  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:32:41.793  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.793  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:32:41.794  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.794  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:32:41.794  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:32:41.795  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e removed from the list
09-08 18:32:41.795  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.795  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf removed from the list
09-08 18:32:41.796  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:32:41.796  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.797  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.798  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.800  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:32:41.800  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:32:41.801  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.801  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:32:41.805  3833  3880 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 18:32:41.807  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:41.808  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:32:41.808  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:32:41.808  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:32:41.808  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.809  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.809  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:32:41.809  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.809  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:41.810  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:32:41.810  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:32:41.810  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.810  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:32:41.810  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:32:41.813  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:32:41.813  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:32:41.813  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.813  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:32:41.817  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:32:41.818  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:32:41.819  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:32:41.819  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:32:41.819  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:32:41.819  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:41.819  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:32:41.819  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:32:41.820  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:32:41.820  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.820  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.820  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
,09-08 18:32:41.820  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.820  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:41.820  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:32:41.820  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.820  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.820  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:41.820  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:41.822  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:32:41.822  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:32:41.822  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:41.822  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:41.823  3833  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:32:41.824  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:41.833  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:32:41.838  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:32:41.838  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:32:41.839  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:32:41.840  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.840  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 18:32:41.843  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 18:32:41.843  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:32:41.844  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:32:41.846  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:41.852  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:32:41.853  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:32:41.869  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:32:41.874  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 18:32:41.876  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:32:41.884  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 18:32:41.894  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 18:32:41.895  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:32:41.896  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:32:41.898  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:32:41.901  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:32:41.918  2430  2556 D BtGatt.GattService: registerClient() - UUID=44cc1c3a-9153-4f0a-9431-3ff554a02af8
,09-08 18:32:41.920  2430  2456 D BtGatt.GattService: onClientRegistered() - UUID=44cc1c3a-9153-4f0a-9431-3ff554a02af8, clientIf=5
,09-08 18:32:41.922  3833  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:32:41.926  2430  2446 D BtGatt.GattService: start scan with filters
,09-08 18:32:41.937  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:32:41.938  2430  2459 D BtGatt.ScanManager: handling starting scan
,09-08 18:32:41.939  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:32:41.940  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 18:32:41.940  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:32:41.943  2430  2459 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:32:41.951  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:32:41.952  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:32:41.953  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:32:41.961  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:32:41.963  2430  2456 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:32:41.963  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:41.965  2430  2459 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:32:41.966  3833  3880 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:32:41.975  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:32:41.975  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:41.977  2430  2459 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:32:41.977  2430  2459 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:32:42.001  2430  2456 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:32:42.002  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:42.016  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 18:32:42.016  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:42.457  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 18:32:42.457  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:32:42.458  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:32:43.524  2430  2430 D BtGatt.ScanManager: awakened up at time 323861
09-08 18:32:43.527  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:43.577  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-08 18:32:43.577  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:43.578  2430  2456 D BtGatt.GattService: current time is 323915416911
,09-08 18:32:43.580  2430  2456 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -95, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 18:32:43.585  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 18:32:43.588  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 18:32:43.589  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 18:32:43.590  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 18:32:43.590  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 18:32:43.591  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 18:32:45.080  2430  2430 D BtGatt.ScanManager: awakened up at time 325417
,09-08 18:32:45.084  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:45.101  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-08 18:32:45.101  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:45.102  2430  2456 D BtGatt.GattService: current time is 325439183943
,09-08 18:32:45.102  2430  2456 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 18:32:45.103  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 18:32:45.104  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 18:32:45.105  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 18:32:46.610  2430  2430 D BtGatt.ScanManager: awakened up at time 326947
,09-08 18:32:46.616  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:46.659  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 18:32:46.660  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:46.660  2430  2456 D BtGatt.GattService: current time is 326997335189
09-08 18:32:46.660  2430  2456 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -97, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 18:32:46.661  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 18:32:46.661  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 18:32:46.662  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 18:32:46.662  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 18:32:46.662  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 18:32:46.976  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:46.977  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:32:46.977  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:32:46.978  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:32:46.978  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 18:32:46.978  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:32:46.978  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:32:46.979  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:32:46.979  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:32:46.982  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:32:46.983  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:32:46.985  3833  3880 D BluetoothAdapter: STATE_ON
09-08 18:32:46.987  2430  2446 D BtGatt.GattService: stopScan() - queue size =1
09-08 18:32:46.990  2430  2556 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:32:46.991  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:32:46.992  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:32:46.992  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:32:46.993  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:32:46.993  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:32:46.996  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:32:46.997  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:32:46.997  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:32:46.998  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:32:47.000  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:32:47.003  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:32:47.003  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:32:47.003  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:32:47.003  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:32:47.004  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:32:47.004  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:32:47.004  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:32:47.004  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:32:47.004  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:47.005  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:32:47.005  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:47.011  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:32:47.011  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:47.012  2430  2459 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:32:47.022  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 18:32:47.022  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:47.023  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:47.031  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:32:47.031  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:47.505  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:32:52.010  3833  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:32:52.016  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:52.031  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:32:52.038  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:52.039  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:32:52.039  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:32:52.040  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:32:52.040  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:32:52.040  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:32:52.041  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:32:52.048  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:52.052  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 18:32:52.052  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:32:52.058  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:32:52.066  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:32:52.068  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:32:52.068  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:32:52.079  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:32:52.080  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:32:52.080  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:32:52.083  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:32:52.091  2430  2556 D BtGatt.GattService: registerClient() - UUID=235a39da-09db-4fe8-ac89-cdd1380d1e5e
,09-08 18:32:52.093  2430  2456 D BtGatt.GattService: onClientRegistered() - UUID=235a39da-09db-4fe8-ac89-cdd1380d1e5e, clientIf=5
,09-08 18:32:52.094  3833  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:32:52.095  2430  2446 D BtGatt.GattService: start scan with filters
,09-08 18:32:52.106  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:32:52.106  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:32:52.107  2430  2459 D BtGatt.ScanManager: handling starting scan
09-08 18:32:52.107  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:32:52.107  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:32:52.117  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:32:52.118  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:32:52.119  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:32:52.126  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:32:52.127  2430  2456 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:32:52.127  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:52.128  2430  2459 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:32:52.132  3833  3880 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:32:52.137  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:52.137  3833  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:32:52.137  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:32:52.137  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:32:52.137  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:52.137  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 18:32:52.137  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:32:52.137  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:32:52.137  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:32:52.137  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:32:52.138  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:32:52.138  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:32:52.139  3833  3880 D BluetoothAdapter: STATE_ON
09-08 18:32:52.139  2430  2443 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:32:52.140  2430  2556 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:32:52.140  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:32:52.141  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:32:52.141  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:32:52.141  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:32:52.141  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 18:32:52.142  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:32:52.142  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:32:52.143  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:32:52.143  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:32:52.143  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:32:52.148  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:32:52.149  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:32:52.149  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:32:52.149  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:32:52.149  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:52.150  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:32:52.150  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:32:52.150  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:52.150  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:52.150  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:32:52.150  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:32:52.151  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:52.151  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:32:52.154  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:32:52.154  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:32:52.154  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:32:52.154  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:32:52.154  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:32:52.154  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.156  2430  2459 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:32:52.156  2430  2459 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 18:32:52.157  3833  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:32:52.159  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:32:52.165  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:32:52.168  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:32:52.169  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:32:52.170  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:32:52.170  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:32:52.171  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:32:52.172  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:32:52.170  2430  2456 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 18:32:52.172  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:32:52.172  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:32:52.172  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.174  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:32:52.176  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:32:52.176  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:32:52.180  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:32:52.184  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:32:52.184  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:32:52.187  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:32:52.187  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.188  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:32:52.188  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:32:52.188  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:32:52.190  3833  3880 D BluetoothAdapter: STATE_ON
09-08 18:32:52.192  2430  2556 D BtGatt.GattService: registerClient() - UUID=e826f539-c76b-4db7-a27e-f9a0eebc2669
09-08 18:32:52.192  2430  2456 D BtGatt.GattService: onClientRegistered() - UUID=e826f539-c76b-4db7-a27e-f9a0eebc2669, clientIf=5
09-08 18:32:52.193  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 18:32:52.194  2430  2446 D BtGatt.GattService: start scan with filters
09-08 18:32:52.195  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:32:52.196  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.196  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:32:52.196  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:32:52.197  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:32:52.197  2430  2459 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:32:52.203  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 18:32:52.205  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:32:52.206  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:32:52.206  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:32:52.207  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 18:32:52.210  3833  3880 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:32:52.210  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:32:52.210  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.210  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:32:52.216  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 18:32:52.217  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.220  2430  2459 D BtGatt.ScanManager: handling starting scan
,09-08 18:32:52.228  2430  2456 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:32:52.228  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:52.229  2430  2459 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:32:52.238  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 18:32:52.238  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:52.239  2430  2459 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:32:52.239  2430  2459 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:32:52.258  2430  2456 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:32:52.259  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:52.270  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 18:32:52.271  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:52.707  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 18:32:52.707  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:32:52.708  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:32:53.034   871  2078 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 18:32:53.775  2430  2430 D BtGatt.ScanManager: awakened up at time 334112
,09-08 18:32:53.780  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:53.827  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-08 18:32:53.827  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:53.828  2430  2456 D BtGatt.GattService: current time is 334165115172
09-08 18:32:53.829  2430  2456 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -95, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -61, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -63, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,09-08 18:32:53.830  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 18:32:53.831  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 18:32:53.832  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 18:32:53.833  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 18:32:53.834  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-08 18:32:53.835  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-08 18:32:55.330  2430  2430 D BtGatt.ScanManager: awakened up at time 335666
,09-08 18:32:55.331  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:55.382  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-08 18:32:55.383  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:55.383  2430  2456 D BtGatt.GattService: current time is 335720647983
09-08 18:32:55.384  2430  2456 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 18:32:55.385  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 18:32:55.386  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 18:32:55.387  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 18:32:55.388  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 18:32:55.389  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 18:32:56.886  2430  2430 D BtGatt.ScanManager: awakened up at time 337222
,09-08 18:32:56.889  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:56.913  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-08 18:32:56.913  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:56.915  2430  2456 D BtGatt.GattService: current time is 337252277371
09-08 18:32:56.916  2430  2456 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -76, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -95, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -88, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 18:32:56.917  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 18:32:56.920  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 18:32:56.922  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 18:32:56.924  2430  2456 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 18:32:57.210  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:32:57.211  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:32:57.211  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 18:32:57.211  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:32:57.211  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 18:32:57.212  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:32:57.212  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:32:57.212  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:32:57.213  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:32:57.214  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:32:57.214  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:32:57.217  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:32:57.219  2430  2556 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:32:57.222  2430  2443 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:32:57.223  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:32:57.224  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:32:57.224  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:32:57.225  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:32:57.225  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 18:32:57.231  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:32:57.232  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:32:57.232  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:32:57.232  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:32:57.234  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:32:57.236  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:32:57.236  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:32:57.236  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:32:57.236  2430  2456 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:32:57.236  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:57.237  2430  2459 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:32:57.250  2430  2456 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 18:32:57.251  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:32:57.251  2430  2459 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:32:57.257  2430  2456 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:32:57.258  2430  2456 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:32:57.737  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:32:57.738  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:32:57.738  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:33:02.238  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:33:02.238  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:33:02.239  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:33:02.240  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:33:02.240  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:02.241  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:33:02.241  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.242  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.242  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.243  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.243  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.245  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.245  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.250  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.250  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.250  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.251  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.253  3833  3880 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 18:33:02.255  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:33:02.255  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.256  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:33:02.256  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:33:02.256  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.257  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.257  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
,09-08 18:33:02.257  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.258  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.258  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.258  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:02.258  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.259  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:02.259  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.261  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.261  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:33:02.261  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.261  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.262  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 18:33:02.262  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.262  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:33:02.262  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.262  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.263  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.263  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.263  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.263  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.263  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.263  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.263  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.263  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.263  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.263  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.265  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.265  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.265  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.265  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.266  3833  3880 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 18:33:02.266  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.266  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.266  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.266  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.267  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.267  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.267  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.267  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.267  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.267  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.267  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not ,exist in the list - probably already removed
09-08 18:33:02.267  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.267  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.267  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.268  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.268  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.268  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.269  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.269  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 18:33:02.269  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.269  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.269  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.270  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.270  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.270  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.270  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.270  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.270  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.270  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.270  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.270  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.270  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.270  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.273  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.273  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.273  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.274  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.275  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 18:33:02.279  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:33:02.279  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:33:02.279  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:33:02.280  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:33:02.280  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:33:02.280  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:33:02.280  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 18:33:02.280  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:33:02.280  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.280  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.280  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.281  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:33:02.281  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.281  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.282  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.282  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.282  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.282  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:02.282  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.282  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.283  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.283  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.285  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.285  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.286  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:02.286  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.293  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:33:02.293  3833  3880 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 18:33:02.293  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 18:33:02.298  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 18:33:02.299  3833  3880 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 18:33:02.299  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 18:33:02.299  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:33:02.300  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:33:02.301  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:33:02.302  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:33:02.303  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:33:02.303  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-08 18:33:02.303  3833  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:33:02.303  3833  3880 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 18:33:02.303  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:33:02.304  3833  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:33:02.304  3833  3880 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 18:33:02.304  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:33:02.304  3833  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:33:02.304  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 18:33:02.308  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 18:33:02.310  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 18:33:02.311  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 18:33:02.312  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-08 18:33:02.313  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 18:33:02.313  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 18:33:02.313  3833  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 18:33:02.314  3833  3880 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 18:33:02.314  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
,09-08 18:33:02.316  3833  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:02.316  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.317  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.317  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:33:02.317  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:33:02.318  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.318  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.318  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 18:33:02.320  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.321  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:02.321  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.321  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:02.322  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:02.323  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-08 18:33:02.323  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.323  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
09-08 18:33:02.323  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.324  2430  2533 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-08 18:33:02.324  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
,09-08 18:33:02.324  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.324  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
09-08 18:33:02.327  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.327  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.327  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.327  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.328  3833  3880 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 18:33:02.328  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.328  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.328  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:33:02.328  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.329  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.329  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.329  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.329  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.329  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.329  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.329  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.329  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.329  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.329  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.330  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.330  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.330  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.331  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:02.331  3833  3880 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 18:33:02.332  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:33:02.332  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.332  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.332  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.332  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.332  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:02.332  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.332  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.332  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.332  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.333  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.333  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.333  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.333  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.334  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:33:02.334  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.334  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.334  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.335  3833  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 18:33:02.335  3833  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 18:33:02.335  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:33:02.335  3833  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 18:33:02.335  3833  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:33:02.335  3833  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 18:33:02.336  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:33:02.336  3833  3880 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 18:33:02.336  3833  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:33:02.336  3833  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:33:02.336  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:33:02.336  3833  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 18:33:02.336  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:02.336  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:02.336  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:02.336  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.337  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.337  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.337  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.337  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.337  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.337  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.337  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.337  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.337  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.337  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.338  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:02.338  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:02.338  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.339  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.339  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:02.339  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:02.339  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:02.339  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:02.340  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:02.340  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:02.340  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:02.340  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 18:33:02.340  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:05.849  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:05.871  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:05.877  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:05.943  1502  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 18:33:05.943  1502  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 18:33:05.944  1502  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:33:05.944  1502  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:33:05.999  1502  2026 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 18:33:05.999  1502  2026 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 18:33:06.008  3499  3532 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 18:33:06.008  3499  3532 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 18:33:06.008  3499  3532 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 18:33:06.008  3499  3532 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 18:33:06.008  3499  3532 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 18:33:06.008  3499  3532 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 18:33:06.008  3499  3532 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 18:33:07.341  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.341  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.341  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.342  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.342  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.343  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
,09-08 18:33:07.343  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:07.343  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:33:07.344  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:07.344  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.344  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.345  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:07.345  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:07.345  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:07.346  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.346  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:07.346  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:07.347  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:07.347  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:07.347  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.351  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:33:07.351  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:33:07.351  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:07.352  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.356  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 18:33:07.357  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:33:07.361  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 18:33:07.363  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 18:33:07.363  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 18:33:07.364  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:33:07.364  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:33:07.364  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 18:33:07.365  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.365  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:33:07.365  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 18:33:07.365  3833  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:07.365  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 18:33:07.366  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:07.366  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 18:33:07.366  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:07.366  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 18:33:07.366  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.367  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:33:07.367  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:33:07.367  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:33:07.367  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.367  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.369  3833  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 18:33:07.369  3833  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:33:07.370  3833  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:33:07.370  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:33:07.370  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.371  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:33:07.371  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:07.371  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:33:07.371  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:33:07.371  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:07.371  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 18:33:07.372  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.372  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:33:07.372  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.372  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.372  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:07.373  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.373  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:07.373  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:07.373  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.374  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.374  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.374  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.376  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:07.376  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:07.376  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.377  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.380  3833  3880 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage,
09-08 18:33:07.380  3833  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:33:07.380  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:33:07.383  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 18:33:07.383  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:33:07.383  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:07.384  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:07.384  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:33:07.385  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.385  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.385  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:07.386  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
,09-08 18:33:07.386  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.389  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:07.389  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:07.389  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.390  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.390  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 18:33:07.390  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.393  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:07.393  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:07.393  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.393  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:07.401  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:33:07.401  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:07.401  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:07.401  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.401  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.401  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.401  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
,09-08 18:33:07.402  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.402  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.402  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:07.402  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.402  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.402  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:07.402  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.403  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:07.403  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:07.403  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.403  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
,09-08 18:33:07.405  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:33:07.405  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:33:07.405  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:33:07.406  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:33:07.406  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.406  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.406  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@648f68e not in the list
09-08 18:33:07.406  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.406  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.406  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:07.406  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.406  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.407  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:07.407  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:07.409  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:33:07.409  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:33:07.409  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:07.409  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8046eaf not in the list
09-08 18:33:07.410  3833  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 18:33:07.410  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 18:33:07.411  3833  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-08 18:33:07.411  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:33:07.411  3833  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-08 18:33:07.411  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 18:33:07.414  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 18:33:07.414  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 18:33:07.415  3833  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 18:33:07.415  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:33:07.415  3833  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 18:33:07.415  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:33:07.415  3833  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-08 18:33:07.416  3833  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 18:33:07.416  3833  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 18:33:07.416  3833  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 18:33:07.417  3833  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 18:33:07.417  3833  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-08 18:33:07.417  3833  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 18:33:07.417  3833  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 18:33:07.418  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:33:07.418  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afde3f9 added. We now have 3 listener(s)
09-08 18:33:07.419  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:07.422  3833  3880 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 18:33:07.422   871  2239 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,09-08 18:33:07.422   871  2239 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:07.450  2430  2513 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 18:33:07.451  2430  2513 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 18:33:07.873  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:33:12.433  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:33:12.433  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5261f3e added. We now have 4 listener(s)
09-08 18:33:12.434  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:12.451  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:12.451  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5261f3e removed from the list
,09-08 18:33:12.452  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:12.452  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:12.452  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:12.455  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:33:12.456  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b4619f added. We now have 4 listener(s)
09-08 18:33:12.456  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:12.460  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:12.461  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b4619f removed from the list
09-08 18:33:12.461  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:12.461  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:12.461  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:12.465  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:33:12.467  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8632ec added. We now have 4 listener(s)
,09-08 18:33:12.468  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:12.475   871  1704 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,09-08 18:33:12.475   871  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:12.483  2430  2452 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 18:33:12.484  2430  2452 D BluetoothAdapterProperties: Setting state to 13
,09-08 18:33:12.484  2430  2452 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 18:33:12.484  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:33:12.485  2430  2452 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:33:12.493  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:12.493  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:12.495  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:33:12.495  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.496  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:33:12.496  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:33:12.499   871  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 18:33:12.499   871  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 18:33:12.499   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 18:33:12.499   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:12.501  2430  2452 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:12.508  2430  2430 D BluetoothMapService: onReceive
,09-08 18:33:12.508  2430  2430 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:33:12.508  2430  2430 D BluetoothMapService: STATE_TURNING_OFF
,09-08 18:33:12.508   871  1303 E native  : do suspend true
,09-08 18:33:12.509  2430  2430 D BluetoothMapService: MAP Service closeService in
,09-08 18:33:12.509  2430  2430 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 18:33:12.510  2430  2430 D ObexServerSockets0: shutdown(block = true)
,09-08 18:33:12.510  2430  2430 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:33:12.510  2430  2559 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 18:33:12.510  2430  2430 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:33:12.510  2430  2560 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 18:33:12.511  2430  2533 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 18:33:12.512  2430  2430 I BtOppRfcommListener: stopping Accept Thread
09-08 18:33:12.512  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:12.512  2430  3418 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 18:33:12.513  2430  3418 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 18:33:12.515  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:12.518   871   884 I ActivityManager: Start proc 3897:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 18:33:12.518  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:12.518  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:12.518  2430  2456 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:33:12.519  2430  2452 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 18:33:12.520   871  2080 D DhcpClient: Clearing IP address
09-08 18:33:12.520   371   869 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:33:12.522  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.522  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:33:12.523  2430  2430 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:33:12.526   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:12.526  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:12.526  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:33:12.527  1940  2213 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:12.527  1502  2593 V NativeCrypto: Read error: ssl=0x9adb8600: I/O error during system call, Connection timed out
,09-08 18:33:12.527  1348  1360 D BluetoothHeadset: Proxy object disconnected
,09-08 18:33:12.527   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:12.527   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:12.527  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.527  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:12.527   371   869 D CommandListener: Setting iface cfg
09-08 18:33:12.529  2430  2430 D A2dpService: Received stop request...Stopping profile...
09-08 18:33:12.529  2430  2550 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:33:12.530  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:12.531  1348  1348 D HeadsetProfile: Bluetooth service disconnected
09-08 18:33:12.533  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:12.534   871   871 D BluetoothA2dp: Proxy object disconnected
,09-08 18:33:12.534   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 18:33:12.535   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 18:33:12.536   871  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 18:33:12.536  2430  2430 D HidService: Received stop request...Stopping profile...
09-08 18:33:12.536  2430  2430 D HidService: Stopping Bluetooth HidService
09-08 18:33:12.537   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 18:33:12.537   871  1303 E native  : do suspend true
09-08 18:33:12.537  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.538  2430  2430 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:12.538  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:12.538  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.538   469   469 E Parcel  : Reading a NULL string not supported here.
09-08 18:33:12.540  2430  2430 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:33:12.540  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.540  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.541  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.541  2430  2456 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 18:33:12.541  2430  2456 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 18:33:12.541  2430  2430 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:33:12.541  2430  2430 D HealthService: Received stop request...Stopping profile...
09-08 18:33:12.542  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:12.542  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:12.543  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.543  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.543   871  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 18:33:12.543  2430  2430 D PanService: Received stop request...Stopping profile...
09-08 18:33:12.545  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.545  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:12.546  1348  1348 D BluetoothA2dp: Proxy object disconnected
09-08 18:33:12.546  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.546  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.546  1348  1348 D BluetoothInputDevice: Proxy object disconnected
09-08 18:33:12.546  1348  1348 D HidProfile: Bluetooth service disconnected
,09-08 18:33:12.546  2430  2430 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:33:12.546  2430  2430 D BluetoothMapService: stop()
09-08 18:33:12.546  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:33:12.546  1348  1348 D PanProfile: Bluetooth service disconnected
09-08 18:33:12.547  2430  2430 D BluetoothMapAppObserver: deinitObservers()
09-08 18:33:12.547  2430  2430 D BluetoothMapAppObserver: removeReceiver()
09-08 18:33:12.548  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.548  2430  2430 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:12.548  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:12.548  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.550  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.550  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.551  2430  2513 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:33:12.551  2430  2513 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:33:12.551  2430  2513 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:33:12.551  2430  2513 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:33:12.551  2430  2456 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 18:33:12.552  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.552  2430  2430 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:33:12.553  1348  1348 D BluetoothMap: Proxy object disconnected
09-08 18:33:12.553  1348  1348 D MapProfile: Bluetooth service disconnected
09-08 18:33:12.555  1502  2593 V NativeCrypto: SSL shutdown failed: ssl=0x9adb8600: I/O error during system call, Broken pipe
09-08 18:33:12.552  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:12.557  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.558  2430  2430 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:33:12.559  2430  2456 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:33:12.559  2430  2430 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:33:12.559  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.559  2430  2430 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:12.559  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:12.559  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.559  2430  2430 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:33:12.559  2430  2456 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 18:33:12.560  2430  2430 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:33:12.563  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.563  2430  2430 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:12.563  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:12.563  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.566   871  2087 D DhcpClient: Receive thread stopped
09-08 18:33:12.568  2430  2430 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:33:12.568  2430  2430 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:33:12.569  2430  2430 D BluetoothMapService: MAP Service closeService in
09-08 18:33:12.569  2430  2430 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:12.569  2430  2430 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:12.569  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:12.569  2430  2430 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:12.570  2430  2452 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 18:33:12.570  2430  2452 D BluetoothAdapterProperties: Setting state to 15
,09-08 18:33:12.570  2430  2452 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 18:33:12.570  2430  2452 I BluetoothAdapterState: Entering BleOnState
09-08 18:33:12.570   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:12.570  1348  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:12.570  2430  2430 D BluetoothMapService: cleanup()
09-08 18:33:12.570  2430  2430 D BluetoothMapService: MAP Service closeService in
09-08 18:33:12.571  1348  2085 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:33:12.571  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:33:12.571  1348  1361 D BluetoothMap: onBluetoothStateChange: up=false
09-08 18:33:12.572   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:33:12.572   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:33:12.572  1940  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:12.572  1348  2085 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:33:12.573  1348  1360 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:33:12.574   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:12.574  2430  2452 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 18:33:12.574  2430  2452 D BluetoothAdapterProperties: Setting state to 16
09-08 18:33:12.574  2430  2452 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 18:33:12.574  2430  2452 D BluetoothAdapterProperties: onBleDisable
09-08 18:33:12.574  2430  2452 I BluetoothAdapterState: Entering PendingCommandState
09-08 18:33:12.575  2430  2453 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 18:33:12.576  2430  2513 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 18:33:12.576  2430  2513 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:12.577  2430  2456 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:33:12.583  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:12.584  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.584  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.585  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.585  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:12.586   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 18:33:12.586  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.586  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:12.587  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:12.588  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:12.589  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:12.603  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 18:33:12.604   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:12.605   371   869 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:33:12.605   871  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 18:33:12.605   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:12.606   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:33:12.609   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:12.610  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:12.612  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:12.613  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:12.613  3364  3364 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1cb0b86 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-08 18:33:12.623  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:33:12.626   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:12.628  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.628   871  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.628  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:12.629  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.629  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.630  2020  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:33:12.631  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:33:12.631  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.632  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:12.632  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.632  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.633  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:12.633  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:12.634  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:12.634  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:12.637   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff3eb31:true
,09-08 18:33:12.647   871  1966 I ActivityManager: Start proc 3916:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 18:33:12.655  3897  3897 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 18:33:12.658  3897  3897 D BluetoothMap: Create BluetoothMap proxy object
,09-08 18:33:12.663   371   869 E Netd    : netlink response contains error (No such file or directory)
,09-08 18:33:12.664   871  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 18:33:12.667  3897  3897 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 18:33:12.677  3916  3916 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 18:33:12.680  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:33:12.687   871   881 I ActivityManager: Killing 2956:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 18:33:12.776  2430  2456 I bt_hci  : shut_down
,09-08 18:33:12.787  2430  2460 D bt_hwcfg: hw_epilog_process
,09-08 18:33:12.788  2430  2460 I bt_vendor: low_power_mode_cb
,09-08 18:33:12.819  2430  2460 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 18:33:12.819  2430  2460 I bt_vendor: epilog_cb
09-08 18:33:12.819  2430  2460 I bt_hci  : epilog_finished_callback
,09-08 18:33:12.825  2430  2456 I bt_hci_h4: hal_close
,09-08 18:33:12.826  2430  2456 I bt_userial_vendor: device fd = 51 close
,09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:33:12.872  3916  3916 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.872  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:33:12.883  3916  3916 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.883  3916  3916 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:33:12.883  3916  3916 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:33:12.883  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:33:12.893  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:33:12.902  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:33:12.913  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:33:12.920  1716  1716 D SystemUpdateService: onCreate
,09-08 18:33:12.924  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:33:12.938  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 18:33:12.940  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:33:12.942  1716  2571 I iu.UploadsManager: num queued entries: 0
,09-08 18:33:12.943  1716  2571 I iu.UploadsManager: num updated entries: 0
,09-08 18:33:12.956  1716  3947 I SystemUpdateService: active receiver: enabled
,09-08 18:33:12.964  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:33:12.967  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 18:33:12.969  2430  2453 D bt_stack_manager: event_shut_down_stack finished.
,09-08 18:33:12.970  2430  2452 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 18:33:12.972  1716  3947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:33:12.978  1716  2571 I iu.SyncManager: NEXT; no task
,09-08 18:33:12.989  1716  3947 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 18:33:12.989  1716  3947 I SystemUpdateService: now status is 0 (complete)
,09-08 18:33:12.998   871   881 I ActivityManager: Start proc 3950:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 18:33:12.999  2430  2452 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 18:33:12.999  2430  2430 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:33:13.001  2430  2430 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 18:33:13.001  2430  2430 D BtGatt.GattService: stop()
,09-08 18:33:13.002  2430  2430 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 18:33:13.006  2430  2430 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:13.006  2430  2430 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:33:13.006  2430  2430 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:13.007  2430  2430 V BluetoothAdapterState: isBleTurningOff()=true
09-08 18:33:13.007  2430  2452 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 18:33:13.007  2430  2452 D BluetoothAdapterProperties: Setting state to 10
09-08 18:33:13.007  2430  2452 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10,
09-08 18:33:13.008  2430  2452 I BluetoothAdapterState: Entering OffState
09-08 18:33:13.009   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 18:33:13.023  2430  2430 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 18:33:13.023  2430  2430 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-08 18:33:13.023  2430  2430 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 18:33:13.024  2430  2453 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 18:33:13.027  2430  2453 D bt_stack_manager: event_clean_up_stack finished.
09-08 18:33:13.030  2430  2430 I art     : System.exit called, status: 0
09-08 18:33:13.030  2430  2430 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 18:33:13.052  3950  3950 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 18:33:13.064  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:12.989  1716  3947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 18:33:13.065  1716  3947 I SystemUpdateService: file has been verified
09-08 18:33:13.065  1716  3947 I SystemUpdateService: OTA package size = 12249756
,09-08 18:33:13.082  3950  3950 D SprintDMHelper: simOperator: 
,09-08 18:33:13.083  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:33:13.084  1716  3947 I SystemUpdateService: showing system update notification,
,09-08 18:33:13.105   871  1971 I ActivityManager: Start proc 3963:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 18:33:13.107   871  1971 I ActivityManager: Killing 3364:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 18:33:13.197  3916  3938 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 18:33:13.199   871  1970 I ActivityManager: Process com.android.bluetooth (pid 2430) has died
,09-08 18:33:13.214   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a0b638:true
,09-08 18:33:13.258  1716  1716 D SystemUpdateService: onDestroy
,09-08 18:33:13.359   871  1704 I ActivityManager: Start proc 3980:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 18:33:13.366  3036  3979 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-08 18:33:13.369   871  1970 I ActivityManager: Killing 3464:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 18:33:13.440  3980  3980 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 18:33:13.498  3980  3980 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 18:33:13.498  3980  3980 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 18:33:13.498  3980  3980 I GAv4    :   adb logcat -s GAv4
,09-08 18:33:13.515  3980  3980 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:33:13.520  3980  3980 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:33:13.543  3980  3997 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:33:13.664  3980  3980 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 18:33:13.705  3980  3980 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 18:33:13.713  3980  3980 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4047-4049)
,09-08 18:33:13.713  3980  3980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:33:13.724  3980  3980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ae1fd10}
,09-08 18:33:13.725  3980  3980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:33:13.725  3980  3980 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 18:33:13.734  3980  3980 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 18:33:13.735  3980  3980 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 18:33:13.752  3980  3980 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 18:33:13.763  3980  3980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 18:33:13.764  3980  3980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:33:13.764  3980  3980 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 18:33:13.764  3980  3980 I Adreno  : Build Date                       : 10/20/15
09-08 18:33:13.764  3980  3980 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 18:33:13.764  3980  3980 I Adreno  : Local Branch                     : M14
09-08 18:33:13.764  3980  3980 I Adreno  : Remote Branch                    : 
09-08 18:33:13.764  3980  3980 I Adreno  : Remote Branch                    : 
09-08 18:33:13.764  3980  3980 I Adreno  : Reconstruct Branch               : 
,09-08 18:33:13.826  3980  3980 I NSApplication: Starting up...
,09-08 18:33:13.836  3980  4026 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 18:33:13.881   871  1973 I ActivityManager: Start proc 4031:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 18:33:13.883   871  1973 I ActivityManager: Killing 1689:android.process.acore/u0a5 (adj 15): empty #17
,09-08 18:33:13.996  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 18:33:14.195   871  1970 I ActivityManager: Killing 3666:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 18:33:14.215  3542  3551 W art     : Suspending all threads took: 5.233ms
,09-08 18:33:14.284   871  1391 I ActivityManager: Start proc 4049:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 18:33:14.365  4049  4049 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 18:33:14.425  4049  4049 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 18:33:14.448   871  1704 I ActivityManager: Killing 3681:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 18:33:17.503   871  1966 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,09-08 18:33:17.504   871  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:17.518   871  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:33:17.547  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:17.547  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:17.547  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:17.547  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:17.548  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:17.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:17.548  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:17.548  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:17.549  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:17.549  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:17.549  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:17.550  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:17.562   871  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-08 18:33:17.563   871  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 18:33:17.564   871  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 18:33:17.565   871  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 18:33:17.565   871  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 18:33:17.565   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 18:33:17.565   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 18:33:17.583   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-08 18:33:17.583   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:17.584   371   869 D CommandListener: Setting iface cfg
09-08 18:33:17.585   871  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-08 18:33:17.585   871  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 18:33:17.592   871  1303 E native  : do suspend true
,09-08 18:33:17.592   871  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 18:33:17.597   871  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 18:33:17.605   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:18.396   871  2239 I ActivityManager: Killing 2208:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 18:33:18.895   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:18.960   871  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=14.06 delta 1000 -> 994
,09-08 18:33:18.961   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 18:33:18.961   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:18.974   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 18:33:19.017   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
09-08 18:33:19.018  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 18:33:19.439  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:33:19.478  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 18:33:19.479  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 18:33:19.483   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:19.496   871  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:33:19.496   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:33:19.496   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 18:33:19.519   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:19.528   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:19.529   871  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 18:33:19.539   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 18:33:19.553   871  4086 D DhcpClient: Receive thread started
,09-08 18:33:19.639   871  1303 E native  : do suspend false
,09-08 18:33:19.661   871  2080 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 18:33:19.684   871  4086 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172463, domain null
,09-08 18:33:19.685   871  2080 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172463 seconds
,09-08 18:33:19.690   871  2080 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 18:33:19.712   871  4086 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 18:33:19.714   871  2080 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 18:33:19.720   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:19.732   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 18:33:19.735   871  2080 D DhcpClient: Scheduling renewal in 86399s
09-08 18:33:19.735   871  1303 E native  : do suspend true
,09-08 18:33:19.757   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 18:33:19.761   871  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 18:33:19.763   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 18:33:19.765   871  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 18:33:19.774   871  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:33:19.827   871  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 18:33:19.828   871  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 18:33:19.832   871  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 18:33:19.836   871  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 18:33:19.840   871  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 18:33:19.862   871  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 18:33:19.872   871  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 18:33:19.872   871  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 18:33:19.872   871  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 18:33:19.872   871  1305 D ConnectivityService:    accepting network in place of null
09-08 18:33:19.872   871  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 18:33:19.873   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 18:33:19.874   871  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:33:19.886   871  4085 D NetlinkSocketObserver: NeighborEvent{elapsedMs=360223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:33:19.927   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:19.955   871  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 18:33:19.963   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:19.970   871  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 18:33:19.971   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:19.979   871   888 D Tethering: MasterInitialState.processMessage what=3
09-08 18:33:19.983   871  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 18:33:19.992  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:19.992  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:19.992  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:19.992  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:19.994  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:19.995  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:19.995  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:19.995  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:19.998  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:19.998  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:33:19.998  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:19.998  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:20.014  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 18:33:20.021  1716  1716 D SystemUpdateService: onCreate
09-08 18:33:20.023   871  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:33:20 GMT], X-Android-Received-Millis=[1473352400021], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473352399998]}
09-08 18:33:20.027   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 18:33:20.027   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 18:33:20.027   871  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 18:33:20.029   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 18:33:20.033  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-08 18:33:20.048  1716  4098 I SystemUpdateService: active receiver: enabled
09-08 18:33:20.058  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-08 18:33:20.060  1716  2571 I iu.UploadsManager: num queued entries: 0
09-08 18:33:20.061  1716  2571 I iu.UploadsManager: num updated entries: 0
09-08 18:33:20.061  1716  2571 I iu.SyncManager: NEXT; no task
09-08 18:33:20.071  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 18:33:20.073  1716  4098 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:33:20.076  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 18:33:20.078  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:20.084  1716  4100 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 18:33:20.084  1716  4100 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:33:20.084  1716  4098 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 18:33:20.084  1716  4098 I SystemUpdateService: now status is 0 (complete)
09-08 18:33:20.084  1716  4098 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 18:33:20.084  1716  4098 I SystemUpdateService: file has been verified
09-08 18:33:20.085  1716  4100 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com,
09-08 18:33:20.088  3950  3950 D SprintDMHelper: simOperator: 
09-08 18:33:20.088  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:33:20.092  1716  4098 I SystemUpdateService: OTA package size = 12249756
,09-08 18:33:20.099  1716  4098 I SystemUpdateService: showing system update notification
,09-08 18:33:20.102  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:20.104  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:20.195  1716  1716 D SystemUpdateService: onDestroy
,09-08 18:33:20.203  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 18:33:20.203  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 18:33:20.203  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:33:20.203  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:33:20.212  3036  4104 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 18:33:20.224  1716  4100 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-08 18:33:20.970   871  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 18:33:22.510   871  1391 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,09-08 18:33:22.511   871  1391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:22.542  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 18:33:22.552   871  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 18:33:22.552   871  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 18:33:22.553   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:33:22.553   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:22.576   871  1303 E native  : do suspend true
,09-08 18:33:22.593   871  2080 D DhcpClient: Clearing IP address
,09-08 18:33:22.594   371   869 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:33:22.599   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:22.611  1502  4109 V NativeCrypto: Read error: ssl=0x995fe200: I/O error during system call, Connection timed out
,09-08 18:33:22.613  1502  4109 V NativeCrypto: SSL shutdown failed: ssl=0x995fe200: I/O error during system call, Broken pipe
,09-08 18:33:22.615   871  4086 D DhcpClient: Receive thread stopped
09-08 18:33:22.618   871  1998 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-08 18:33:22.619   871  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-08 18:33:22.622   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 18:33:22.622   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 18:33:22.624   871  4084 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-08 18:33:22.624   469   469 E Parcel  : Reading a NULL string not supported here.
,09-08 18:33:22.626   871  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-08 18:33:22.627   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:33:22.627   871  1303 E native  : do suspend true
09-08 18:33:22.641   371   869 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:33:22.642   871  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 18:33:22.643   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:22.658   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:22.661  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:22.661  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:22.661  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:22.661  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:22.662  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:22.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:22.662  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:22.662  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:22.663  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:22.663  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:22.663  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:22.663  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:22.663   871  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 18:33:22.667  2020  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:33:22.680   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:22.699   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:22.700   871  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 18:33:22.700   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:22.704  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:22.705   871   888 D Tethering: MasterInitialState.processMessage what=3
09-08 18:33:22.705  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:22.706  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:22.720  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:33:22.730  1716  1716 D SystemUpdateService: onCreate
,09-08 18:33:22.733  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:33:22.742  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-08 18:33:22.743  1716  2571 I iu.UploadsManager: num queued entries: 0
,09-08 18:33:22.747  1716  4122 I SystemUpdateService: active receiver: enabled
,09-08 18:33:22.749  1716  2571 I iu.UploadsManager: num updated entries: 0
09-08 18:33:22.750  1716  2571 I iu.SyncManager: NEXT; no task
,09-08 18:33:22.751  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:33:22.754  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 18:33:22.755  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:22.760  3950  3950 D SprintDMHelper: simOperator: 
,09-08 18:33:22.760  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:33:22.787  1716  4122 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:33:22.797   371   869 E Netd    : netlink response contains error (No such file or directory)
,09-08 18:33:22.799   871  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent,
09-08 18:33:22.799   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 18:33:22.803  3036  4124 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 18:33:22.808  1716  4122 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 18:33:22.808  1716  4122 I SystemUpdateService: now status is 0 (complete)
09-08 18:33:22.808  1716  4122 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:33:22.808  1716  4122 I SystemUpdateService: file has been verified
,09-08 18:33:22.808  1716  4122 I SystemUpdateService: OTA package size = 12249756
,09-08 18:33:22.814  1716  4122 I SystemUpdateService: showing system update notification
,09-08 18:33:22.835  1716  1716 D SystemUpdateService: onDestroy
,09-08 18:33:25.870  1872  1913 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 18:33:25.870  1872  1913 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 18:33:25.919  1502  1502 I ConfigService: onCreate
,09-08 18:33:27.568   871   888 I ActivityManager: Start proc 4132:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 18:33:27.695  4132  4132 D AdapterServiceConfig: Adding HeadsetService
,09-08 18:33:27.696  4132  4132 D AdapterServiceConfig: Adding A2dpService
09-08 18:33:27.696  4132  4132 D AdapterServiceConfig: Adding HidService
,09-08 18:33:27.697  4132  4132 D AdapterServiceConfig: Adding HealthService
09-08 18:33:27.698  4132  4132 D AdapterServiceConfig: Adding PanService
,09-08 18:33:27.698  4132  4132 D AdapterServiceConfig: Adding GattService
09-08 18:33:27.698  4132  4132 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 18:33:27.711   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ebff17:true
,09-08 18:33:27.712  4132  4132 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 18:33:27.721  4132  4132 I bt_bluedroid: init
,09-08 18:33:27.721  4132  4144 I BluetoothAdapterState: Entering OffState
,09-08 18:33:27.728  4132  4145 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 18:33:27.728  4132  4145 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:33:27.728  4132  4145 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 18:33:27.729  4132  4145 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 18:33:27.730  4132  4132 I bt_bluedroid: get_profile_interface socket
,09-08 18:33:27.733  4132  4132 I bt_bluedroid: get_profile_interface sdp
,09-08 18:33:27.736  4132  4148 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:33:27.737  4132  4143 I bt_bluedroid: config_hci_snoop_log
,09-08 18:33:27.738   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 18:33:27.740  4132  4148 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:33:27.745  4132  4144 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 18:33:27.746  4132  4144 D BluetoothAdapterProperties: Setting state to 14
,09-08 18:33:27.746  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 18:33:27.750  4132  4144 D BluetoothBondStateMachine: make
,09-08 18:33:27.753  4132  4149 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:33:27.761  4132  4144 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:27.765  4132  4132 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 18:33:27.773  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:27.775  4132  4132 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:33:27.776  4132  4132 D BtGatt.GattService: Received start request. Starting profile...
,09-08 18:33:27.777  4132  4132 D BtGatt.GattService: start()
09-08 18:33:27.777  4132  4132 I bt_bluedroid: get_profile_interface gatt
,09-08 18:33:27.779  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
09-08 18:33:27.780  4132  4132 D BtGatt.AdvertiseManager: advertise manager created
,09-08 18:33:27.794  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:27.794  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:27.795  4132  4132 V BluetoothAdapterState: isBleTurningOn()=true
09-08 18:33:27.795  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:27.796  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 18:33:27.797  4132  4144 I bt_bluedroid: enable
09-08 18:33:27.798  4132  4145 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 18:33:27.799  4132  4145 I bt_hci  : start_up
,09-08 18:33:27.818  4132  4145 I bt_vendor: alloc value 0xb3a66189
09-08 18:33:27.818  4132  4145 I bt_vendor: init
,09-08 18:33:27.818  4132  4145 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 18:33:27.818  4132  4145 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 18:33:27.877   871  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-08 18:33:27.925  4132  4145 D bt_hci  : start_up starting async portion
,09-08 18:33:27.925  4132  4152 I bt_hci  : event_finish_startup
09-08 18:33:27.926  4132  4152 I bt_hci_h4: hal_open
,09-08 18:33:27.926  4132  4152 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 18:33:27.935  4132  4152 I bt_userial_vendor: device fd = 51 open
,09-08 18:33:27.967  4132  4152 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:33:27.999  4132  4152 D bt_hwcfg: Chipset BCM4354A2
,09-08 18:33:27.999  4132  4152 D bt_hwcfg: Target name = [BCM4354A2]
09-08 18:33:28.000  4132  4152 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 18:33:28.652  4132  4152 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 18:33:28.654  4132  4152 D bt_hwcfg: Settlement delay -- 100 ms
09-08 18:33:28.654  4132  4152 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 18:33:28.771  4132  4152 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:33:28.771  4132  4152 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 18:33:28.802  4132  4152 I bt_hwcfg: vendor lib fwcfg completed
,09-08 18:33:28.802  4132  4152 I bt_vendor: firmware callback
,09-08 18:33:28.802  4132  4152 I bt_hci  : firmware_config_callback
,09-08 18:33:28.814  4132  4154 I bt_btu  : btu_task pending for preload complete event
,09-08 18:33:28.814  4132  4154 I bt_btu_task: Bluetooth chip preload is complete
,09-08 18:33:28.814  4132  4154 I bt_btu  : btu_task received preload complete event
,09-08 18:33:28.824  4132  4154 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 18:33:28.825  4132  4154 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:33:28.825  4132  4154 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:33:28.825  4132  4154 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 18:33:28.825  4132  4154 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:33:28.826  4132  4154 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:33:28.826  4132  4154 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 18:33:28.826  4132  4154 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:33:28.827  4132  4154 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:33:28.827  4132  4154 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 18:33:28.827  4132  4154 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:33:28.827  4132  4154 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:33:28.828  4132  4154 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:33:28.828  4132  4154 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 18:33:28.829  4132  4154 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 18:33:28.963  4132  4154 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e3d9d
,09-08 18:33:28.964  4132  4154 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e3d9d 
,09-08 18:33:28.975  4132  4148 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 18:33:28.979  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 18:33:28.980  4132  4148 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:33:28.985  4132  4148 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:33:28.989  4132  4148 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:33:28.990  4132  4148 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 18:33:28.990  4132  4148 D bt_hci  : do_postload posting postload work item
09-08 18:33:28.990  4132  4152 I bt_hci  : event_postload
09-08 18:33:28.990  4132  4152 I bt_vendor: sco_config_cb
09-08 18:33:28.990  4132  4152 I bt_hci  : sco_config_callback postload finished.
09-08 18:33:28.994  4132  4148 D bt_bte_conf: Device ID record 1 : primary
09-08 18:33:28.994  4132  4148 D bt_bte_conf:   vendorId            = 000f
09-08 18:33:28.994  4132  4148 D bt_bte_conf:   vendorIdSource      = 0001
09-08 18:33:28.995  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:28.995  4132  4148 D bt_bte_conf:   product             = 1200
09-08 18:33:28.995  4132  4148 D bt_bte_conf:   version             = 1436
09-08 18:33:28.995  4132  4148 D bt_bte_conf:   clientExecutableURL = 
09-08 18:33:28.995  4132  4148 D bt_bte_conf:   serviceDescription  = 
09-08 18:33:28.995  4132  4148 D bt_bte_conf:   documentationURL    = 
09-08 18:33:28.996  4132  4148 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 18:33:28.996  4132  4145 D bt_stack_manager: event_start_up_stack finished
,09-08 18:33:28.997  4132  4152 I bt_vendor: low_power_mode_cb
09-08 18:33:28.997  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 18:33:28.998  4132  4144 D BluetoothAdapterProperties: Setting state to 15
09-08 18:33:28.998  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 18:33:29.000  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.001  4132  4144 I BluetoothAdapterState: Entering BleOnState
,09-08 18:33:29.004  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:29.006  4132  4144 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 18:33:29.006  4132  4144 D BluetoothAdapterProperties: Setting state to 11
09-08 18:33:29.006  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 18:33:29.015  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:29.015  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.015  4132  4132 D HeadsetService: Received start request. Starting profile...
,09-08 18:33:29.017  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.018  4132  4132 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 18:33:29.019  4132  4132 D HeadsetStateMachine: make
09-08 18:33:29.020  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.023  4132  4144 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:29.030  4132  4132 D HeadsetStateMachine: max_hf_connections = 1
,09-08 18:33:29.030  4132  4132 I bt_bluedroid: get_profile_interface handsfree
,09-08 18:33:29.030  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 18:33:29.031  4132  4148 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 18:33:29.034  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:29.035  4132  4132 D A2dpService: Received start request. Starting profile...
09-08 18:33:29.035  4132  4132 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 18:33:29.035  4132  4132 I bt_bluedroid: get_profile_interface avrcp
,09-08 18:33:29.042  4132  4132 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 18:33:29.043  4132  4132 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:33:29.043  4132  4132 D A2dpStateMachine: make
,09-08 18:33:29.044  4132  4132 I bt_bluedroid: get_profile_interface a2dp
09-08 18:33:29.044  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 18:33:29.046  4132  4132 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 18:33:29.046  4132  4164 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:33:29.047  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:29.048  4132  4132 D HidService: Received start request. Starting profile...
09-08 18:33:29.048  4132  4132 I bt_bluedroid: get_profile_interface hidhost
09-08 18:33:29.048  4132  4132 D HidService: setHidService(): set to: null
09-08 18:33:29.049  4132  4148 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c53e5
09-08 18:33:29.049  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 18:33:29.049  3897  3897 D BluetoothInputDevice: Proxy object connected
09-08 18:33:29.049  4132  4132 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 18:33:29.050  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
09-08 18:33:29.050  4132  4132 D HealthService: Received start request. Starting profile...
,09-08 18:33:29.051  3897  3897 D HidProfile: Bluetooth service connected
,09-08 18:33:29.053  4132  4132 I bt_bluedroid: get_profile_interface health
,09-08 18:33:29.055  4132  4132 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 18:33:29.055  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
09-08 18:33:29.057  4132  4132 D PanService: Received start request. Starting profile...
09-08 18:33:29.057  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:33:29.057  4132  4132 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 18:33:29.057  4132  4132 I bt_bluedroid: get_profile_interface pan
,09-08 18:33:29.056  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:33:29.058  4132  4148 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:33:29.060  4132  4132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
09-08 18:33:29.060  3897  3897 D PanProfile: Bluetooth service connected
,09-08 18:33:29.061  3897  3897 D BluetoothMap: Proxy object connected
09-08 18:33:29.061  4132  4132 D BluetoothMapService: Received start request. Starting profile...
,09-08 18:33:29.061  4132  4132 D BluetoothMapService: start()
09-08 18:33:29.061  3897  3897 D MapProfile: Bluetooth service connected
09-08 18:33:29.061  3897  3897 D BluetoothMap: getConnectedDevices()
09-08 18:33:29.062  3897  3897 D BluetoothMap: Bluetooth is Not enabled
09-08 18:33:29.064  4132  4132 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 18:33:29.066  4132  4132 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 18:33:29.066  4132  4132 D BluetoothMapAppObserver: createReceiver()
,09-08 18:33:29.069  4132  4132 D BluetoothMapAppObserver: initObservers()
,09-08 18:33:29.069  4132  4132 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 18:33:29.087  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:29.087  4132  4132 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:29.087  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.087  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:29.089  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:29.089  4132  4132 V BluetoothAdapterState: isTurningOn()=true,
09-08 18:33:29.089  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.089  4132  4162 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:33:29.089  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false,
,09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isTurningOff()=false
09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:29.090  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isTurningOff()=false
09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isTurningOn()=true,
09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:29.091  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:29.092  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 18:33:29.092  4132  4144 D BluetoothAdapterProperties: ScanMode =  20
,09-08 18:33:29.092  4132  4144 D BluetoothAdapterProperties: State =  11
,09-08 18:33:29.092  4132  4144 D BluetoothAdapterProperties: Setting state to 12
,09-08 18:33:29.092  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:33:29.093   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:29.094  4132  4144 I BluetoothAdapterState: Entering OnState
,09-08 18:33:29.094  1348  2085 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:29.094  1348  1360 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:33:29.095  4132  4148 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:33:29.095  4132  4148 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:29.099  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:29.100  1348  1348 D BluetoothA2dp: Proxy object connected
09-08 18:33:29.100  1348  2085 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:33:29.101  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:29.103  1348  1348 D BluetoothInputDevice: Proxy object connected
09-08 18:33:29.103  1348  1348 D HidProfile: Bluetooth service connected
09-08 18:33:29.104  1348  1361 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:29.105  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:29.105  1348  1348 D BluetoothMap: Proxy object connected
,09-08 18:33:29.105  1348  1348 D MapProfile: Bluetooth service connected
,09-08 18:33:29.106  1348  1348 D BluetoothMap: getConnectedDevices()
,09-08 18:33:29.106  3897  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:33:29.107  4132  4132 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 18:33:29.107  4132  4132 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 18:33:29.107  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:29.107   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:29.108   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:33:29.108  3897  3907 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:33:29.109   871   871 D BluetoothA2dp: Proxy object connected
,09-08 18:33:29.109  4132  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:29.111  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:29.111  1940  1951 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:29.112  1348  2085 D BluetoothPan: onBluetoothStateChange on: true
,09-08 18:33:29.113  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:29.114  4132  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:33:29.114  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:33:29.115  1348  1348 D PanProfile: Bluetooth service connected
09-08 18:33:29.115  3897  3908 D BluetoothPan: onBluetoothStateChange on: true
09-08 18:33:29.115  4132  4132 D ObexServerSockets: Succeed to create listening sockets 
09-08 18:33:29.115  4132  4132 D ObexServerSockets0: startAccept()
09-08 18:33:29.115  4132  4132 D ObexServerSockets0: prepareForNewConnect()
09-08 18:33:29.115  1348  1361 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 18:33:29.117  3897  3907 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:33:29.117   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:29.117  4132  4132 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 18:33:29.118  4132  4132 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 18:33:29.119   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 18:33:29.121  4132  4170 D ObexServerSockets0: Accepting socket connection...
09-08 18:33:29.121  4132  4171 D ObexServerSockets0: Accepting socket connection...
09-08 18:33:29.121  4132  4132 D BluetoothMapService: onReceive
,09-08 18:33:29.121  4132  4132 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:33:29.122  4132  4132 D BluetoothMapService: STATE_ON
09-08 18:33:29.122  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.123  3897  3897 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 18:33:29.123  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.125  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:29.127  3897  3897 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 18:33:29.134  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:33:29.140  3897  3897 D BluetoothA2dp: Proxy object connected
,09-08 18:33:29.144  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:33:29.150  1348  1348 D BluetoothPbap: Proxy object connected
,09-08 18:33:29.150  1348  1348 D PbapServerProfile: Bluetooth service connected
,09-08 18:33:29.150  4132  4132 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 18:33:29.150  4132  4132 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:33:29.154  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:33:29.154  3897  3897 D BluetoothPbap: Proxy object connected
09-08 18:33:29.155  3897  3897 D PbapServerProfile: Bluetooth service connected
,09-08 18:33:29.162  4132  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:29.174  4132  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:29.175  4132  4180 I BtOppRfcommListener: Accept thread started.
,09-08 18:33:29.195   871   871 D BluetoothHeadset: Proxy object connected
09-08 18:33:29.195  1940  2213 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.195  1348  1360 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.196   871   871 D BluetoothHeadset: Proxy object connected
09-08 18:33:29.196   871   871 D BluetoothHeadset: Proxy object connected
09-08 18:33:29.196  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 18:33:29.208   871   888 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.212  1940  1953 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.217   871   888 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.231  3897  3908 D BluetoothHeadset: Proxy object connected
,09-08 18:33:29.231  3897  3897 D HeadsetProfile: Bluetooth service connected
,09-08 18:33:30.995  1502  1502 I ConfigService: onDestroy
,09-08 18:33:32.528  4132  4144 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 18:33:32.529  4132  4144 D BluetoothAdapterProperties: Setting state to 13
,09-08 18:33:32.529  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 18:33:32.531  4132  4144 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 18:33:32.533  4132  4144 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:32.540  4132  4132 D BluetoothMapService: onReceive
09-08 18:33:32.541  4132  4132 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:33:32.541  4132  4132 D BluetoothMapService: STATE_TURNING_OFF
,09-08 18:33:32.542  4132  4132 D BluetoothMapService: MAP Service closeService in
09-08 18:33:32.542  4132  4132 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 18:33:32.542  4132  4132 D ObexServerSockets0: shutdown(block = true)
,09-08 18:33:32.547  4132  4170 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 18:33:32.548  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:32.548  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:32.550  4132  4132 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 18:33:32.551  4132  4132 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:33:32.551  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:32.551  4132  4157 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!,
09-08 18:33:32.551  4132  4171 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 18:33:32.551  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:32.553  4132  4132 I BtOppRfcommListener: stopping Accept Thread
09-08 18:33:32.554  4132  4180 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:33:32.556  4132  4148 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:33:32.557  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 18:33:32.557  4132  4180 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 18:33:32.558  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:32.558  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:32.560  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:32.560  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:32.562  4132  4132 D HeadsetService: Received stop request...Stopping profile...
09-08 18:33:32.562  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,09-08 18:33:32.564  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:32.564  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:32.565  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:33:32.565  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:32.567  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:32.568  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:32.569  4132  4132 D A2dpService: Received stop request...Stopping profile...
,09-08 18:33:32.570  4132  4164 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:33:32.571   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.572  1348  1348 D BluetoothA2dp: Proxy object disconnected
,09-08 18:33:32.572  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:32.573  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.573  1940  2213 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.573  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:32.573  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:32.573  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:32.574  3897  3908 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.574  1348  2085 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.574  1348  1348 D HeadsetProfile: Bluetooth service disconnected
,09-08 18:33:32.574   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.575   871   871 D BluetoothHeadset: Proxy object disconnected
09-08 18:33:32.575   871   871 D BluetoothA2dp: Proxy object disconnected
,09-08 18:33:32.575  4132  4132 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:33:32.575  4132  4132 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 18:33:32.576  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 18:33:32.576  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:33:32.576  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:32.576  4132  4132 D HidService: Received stop request...Stopping profile...
09-08 18:33:32.576  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-08 18:33:32.576  4132  4132 D HidService: Stopping Bluetooth HidService
09-08 18:33:32.578  4132  4148 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 18:33:32.579  1348  1348 D BluetoothInputDevice: Proxy object disconnected
,09-08 18:33:32.579  1348  1348 D HidProfile: Bluetooth service disconnected
,09-08 18:33:32.580  4132  4132 D HealthService: Received stop request...Stopping profile...
09-08 18:33:32.582  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.582  4132  4132 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:33:32.582  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:32.582  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:32.584  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 18:33:32.584  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:33:32.584  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:33:32.584  4132  4154 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:33:32.584  4132  4154 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:33:32.584  4132  4154 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:33:32.584  4132  4154 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:33:32.585  4132  4132 D PanService: Received stop request...Stopping profile...
,09-08 18:33:32.586  4132  4132 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:33:32.587  4132  4132 D BluetoothMapService: stop()
,09-08 18:33:32.588  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:33:32.588  1348  1348 D PanProfile: Bluetooth service disconnected
09-08 18:33:32.588  3897  3897 D DockEventReceiver: finishStartingService: stopping service
09-08 18:33:32.587  4132  4132 D BluetoothMapAppObserver: deinitObservers()
09-08 18:33:32.589  4132  4132 D BluetoothMapAppObserver: removeReceiver()
,09-08 18:33:32.590  1348  1348 D BluetoothMap: Proxy object disconnected
09-08 18:33:32.590  1348  1348 D MapProfile: Bluetooth service disconnected
09-08 18:33:32.591  3897  3897 D BluetoothA2dp: Proxy object disconnected
09-08 18:33:32.591  3897  3897 D HeadsetProfile: Bluetooth service disconnected
09-08 18:33:32.591  3897  3897 D BluetoothInputDevice: Proxy object disconnected
09-08 18:33:32.591  3897  3897 D HidProfile: Bluetooth service disconnected
09-08 18:33:32.593  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.593  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:32.593  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:32.593  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:32.595  4132  4132 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:33:32.595  4132  4148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:33:32.595  4132  4132 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:33:32.595  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.595  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:32.596  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:32.596  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:32.596  4132  4132 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:33:32.596  4132  4148 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 18:33:32.597  4132  4132 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:33:32.597  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.597  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:32.597  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:32.597  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:32.597  4132  4132 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 18:33:32.598  4132  4132 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:33:32.598  4132  4132 D BluetoothMapService: MAP Service closeService in
09-08 18:33:32.598  4132  4132 V BluetoothAdapterState: isTurningOff()=true
09-08 18:33:32.598  4132  4132 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:32.599  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:32.599  4132  4132 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:32.599  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 18:33:32.599  4132  4144 D BluetoothAdapterProperties: Setting state to 15
09-08 18:33:32.599  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 18:33:32.600   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:32.600  4132  4132 D BluetoothMapService: cleanup()
09-08 18:33:32.600  4132  4132 D BluetoothMapService: MAP Service closeService in
09-08 18:33:32.600  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:33:32.601  1348  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:33:32.601  4132  4144 I BluetoothAdapterState: Entering BleOnState
09-08 18:33:32.601  1348  1348 D BluetoothPbap: Proxy object disconnected
09-08 18:33:32.601  1348  1348 D PbapServerProfile: Bluetooth service disconnected
,09-08 18:33:32.603  3897  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:32.604  1348  2085 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:33:32.604  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:33:32.605  1348  1361 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:33:32.606  3897  3907 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:33:32.608   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:33:32.608   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:33:32.608  3897  3908 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 18:33:32.608  3897  3907 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:33:32.609  1940  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:32.609  1348  2085 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:33:32.610  3897  3908 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:33:32.611  1348  1360 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 18:33:32.611  3897  3907 D BluetoothMap: onBluetoothStateChange: up=false
09-08 18:33:32.612   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:33:32.612  4132  4144 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 18:33:32.612  4132  4144 D BluetoothAdapterProperties: Setting state to 16
,09-08 18:33:32.612  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 18:33:32.613  4132  4144 D BluetoothAdapterProperties: onBleDisable
09-08 18:33:32.613  4132  4144 I BluetoothAdapterState: Entering PendingCommandState
09-08 18:33:32.613  4132  4145 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 18:33:32.614  4132  4154 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 18:33:32.614  4132  4154 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:33:32.616  4132  4148 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:33:32.616  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:32.619  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:32.619  3897  3897 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:33:32.619  3897  3897 D PanProfile: Bluetooth service disconnected
,09-08 18:33:32.620  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:32.621  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:32.622  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:32.622  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:33:32.623  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:32.627  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:33:32.632  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:33:32.819  4132  4148 I bt_hci  : shut_down
,09-08 18:33:32.839  4132  4152 D bt_hwcfg: hw_epilog_process
,09-08 18:33:32.839  4132  4152 I bt_vendor: low_power_mode_cb
,09-08 18:33:32.858  4132  4152 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 18:33:32.858  4132  4152 I bt_vendor: epilog_cb
09-08 18:33:32.858  4132  4152 I bt_hci  : epilog_finished_callback
,09-08 18:33:32.866  4132  4148 I bt_hci_h4: hal_close
,09-08 18:33:32.868  4132  4148 I bt_userial_vendor: device fd = 51 close
,09-08 18:33:32.999  4132  4145 D bt_stack_manager: event_shut_down_stack finished.
,09-08 18:33:33.000  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 18:33:33.008  4132  4144 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 18:33:33.009  4132  4132 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:33:33.011  4132  4132 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:33:33.011  4132  4132 D BtGatt.GattService: stop()
,09-08 18:33:33.012  4132  4132 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 18:33:33.019  4132  4132 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:33.020  4132  4132 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:33:33.020  4132  4132 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:33.020  4132  4132 V BluetoothAdapterState: isBleTurningOff()=true
09-08 18:33:33.021  4132  4144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 18:33:33.022  4132  4144 D BluetoothAdapterProperties: Setting state to 10
09-08 18:33:33.022  4132  4144 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 18:33:33.024  4132  4144 I BluetoothAdapterState: Entering OffState
09-08 18:33:33.025   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 18:33:33.050  4132  4132 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 18:33:33.050  4132  4132 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 18:33:33.051  4132  4145 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 18:33:33.057  4132  4132 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 18:33:33.065  4132  4145 D bt_stack_manager: event_clean_up_stack finished.
,09-08 18:33:33.071  4132  4132 I art     : System.exit called, status: 0
,09-08 18:33:33.072  4132  4132 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 18:33:33.141   871   881 I ActivityManager: Process com.android.bluetooth (pid 4132) has died
,09-08 18:33:37.526  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:37.526  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:37.532  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:37.533  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8632ec removed from the list
,09-08 18:33:37.533  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:37.533  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:33:37.533  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:37.536  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:33:37.537  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e0f14a added. We now have 4 listener(s)
09-08 18:33:37.537  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:33:37.539  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:37.539  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e0f14a removed from the list
09-08 18:33:37.540  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:37.540  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:37.540  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:37.542  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:33:37.543  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8778bb added. We now have 4 listener(s)
,09-08 18:33:37.544  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:42.555  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:42.602   871   888 I ActivityManager: Start proc 4193:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 18:33:42.733  4193  4193 D AdapterServiceConfig: Adding HeadsetService
09-08 18:33:42.733  4193  4193 D AdapterServiceConfig: Adding A2dpService
09-08 18:33:42.734  4193  4193 D AdapterServiceConfig: Adding HidService
09-08 18:33:42.734  4193  4193 D AdapterServiceConfig: Adding HealthService
09-08 18:33:42.734  4193  4193 D AdapterServiceConfig: Adding PanService
09-08 18:33:42.734  4193  4193 D AdapterServiceConfig: Adding GattService
09-08 18:33:42.734  4193  4193 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 18:33:42.750   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bae7a18:true
09-08 18:33:42.750  4193  4193 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 18:33:42.755  4193  4193 I bt_bluedroid: init
,09-08 18:33:42.756  4193  4205 I BluetoothAdapterState: Entering OffState
,09-08 18:33:42.762  4193  4206 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 18:33:42.763  4193  4206 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 18:33:42.763  4193  4206 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 18:33:42.763  4193  4206 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 18:33:42.765  4193  4193 I bt_bluedroid: get_profile_interface socket
,09-08 18:33:42.769  4193  4193 I bt_bluedroid: get_profile_interface sdp
,09-08 18:33:42.771  4193  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:33:42.775  4193  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:33:42.775  4193  4204 I bt_bluedroid: config_hci_snoop_log
09-08 18:33:42.777   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 18:33:42.793  4193  4205 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 18:33:42.793  4193  4205 D BluetoothAdapterProperties: Setting state to 14
,09-08 18:33:42.794  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 18:33:42.799  4193  4205 D BluetoothBondStateMachine: make
,09-08 18:33:42.804  4193  4210 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:33:42.814  4193  4205 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:42.818  4193  4193 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 18:33:42.829  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:42.831  4193  4193 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 18:33:42.833  4193  4193 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:33:42.834  4193  4193 D BtGatt.GattService: start()
09-08 18:33:42.834  4193  4193 I bt_bluedroid: get_profile_interface gatt
,09-08 18:33:42.836  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:42.837  4193  4193 D BtGatt.AdvertiseManager: advertise manager created
,09-08 18:33:42.852  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:42.852  4193  4193 V BluetoothAdapterState: isTurningOn()=false
09-08 18:33:42.852  4193  4193 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 18:33:42.852  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:42.853  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 18:33:42.854  4193  4205 I bt_bluedroid: enable
,09-08 18:33:42.854  4193  4206 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 18:33:42.855  4193  4206 I bt_hci  : start_up
,09-08 18:33:42.875  4193  4206 I bt_vendor: alloc value 0xb3a66189
09-08 18:33:42.876  4193  4206 I bt_vendor: init
09-08 18:33:42.876  4193  4206 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 18:33:42.876  4193  4206 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 18:33:42.985  4193  4206 D bt_hci  : start_up starting async portion
,09-08 18:33:42.986  4193  4213 I bt_hci  : event_finish_startup
,09-08 18:33:42.988  4193  4213 I bt_hci_h4: hal_open
,09-08 18:33:42.988  4193  4213 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 18:33:42.998  4193  4213 I bt_userial_vendor: device fd = 51 open
,09-08 18:33:43.028  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:33:43.060  4193  4213 D bt_hwcfg: Chipset BCM4354A2
,09-08 18:33:43.060  4193  4213 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 18:33:43.061  4193  4213 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 18:33:43.936  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 18:33:43.937  4193  4213 D bt_hwcfg: Settlement delay -- 100 ms
09-08 18:33:43.938  4193  4213 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 18:33:44.055  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:33:44.057  4193  4213 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 18:33:44.086  4193  4213 I bt_hwcfg: vendor lib fwcfg completed
,09-08 18:33:44.086  4193  4213 I bt_vendor: firmware callback
09-08 18:33:44.087  4193  4213 I bt_hci  : firmware_config_callback
,09-08 18:33:44.101  4193  4215 I bt_btu  : btu_task pending for preload complete event
,09-08 18:33:44.101  4193  4215 I bt_btu_task: Bluetooth chip preload is complete
09-08 18:33:44.101  4193  4215 I bt_btu  : btu_task received preload complete event
,09-08 18:33:44.113  4193  4215 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 18:33:44.114  4193  4215 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:33:44.114  4193  4215 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 18:33:44.114  4193  4215 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 18:33:44.115  4193  4215 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:33:44.115  4193  4215 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:33:44.115  4193  4215 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 18:33:44.115  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:33:44.115  4193  4215 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:33:44.117  4193  4215 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 18:33:44.117  4193  4215 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:33:44.118  4193  4215 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:33:44.118  4193  4215 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 18:33:44.119  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 18:33:44.119  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 18:33:44.264  4193  4215 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e3d9d
,09-08 18:33:44.265  4193  4215 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e3d9d 
,09-08 18:33:44.288  4193  4209 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 18:33:44.290  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:33:44.291  4193  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:33:44.294  4193  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:33:44.297  4193  4209 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:33:44.297  4193  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 18:33:44.298  4193  4209 D bt_hci  : do_postload posting postload work item
09-08 18:33:44.298  4193  4213 I bt_hci  : event_postload
,09-08 18:33:44.299  4193  4213 I bt_vendor: sco_config_cb
09-08 18:33:44.299  4193  4213 I bt_hci  : sco_config_callback postload finished.
,09-08 18:33:44.300  4193  4209 D bt_bte_conf: Device ID record 1 : primary
,09-08 18:33:44.300  4193  4209 D bt_bte_conf:   vendorId            = 000f
09-08 18:33:44.300  4193  4209 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 18:33:44.300  4193  4209 D bt_bte_conf:   product             = 1200
,09-08 18:33:44.300  4193  4209 D bt_bte_conf:   version             = 1436
,09-08 18:33:44.301  4193  4209 D bt_bte_conf:   clientExecutableURL = 
,09-08 18:33:44.301  4193  4209 D bt_bte_conf:   serviceDescription  = 
,09-08 18:33:44.301  4193  4209 D bt_bte_conf:   documentationURL    = 
,09-08 18:33:44.301  4193  4209 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 18:33:44.301  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:44.302  4193  4206 D bt_stack_manager: event_start_up_stack finished
09-08 18:33:44.303  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 18:33:44.303  4193  4205 D BluetoothAdapterProperties: Setting state to 15
09-08 18:33:44.303  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 18:33:44.304  4193  4205 I BluetoothAdapterState: Entering BleOnState
,09-08 18:33:44.304  4193  4213 I bt_vendor: low_power_mode_cb
09-08 18:33:44.306  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:44.310  4193  4205 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 18:33:44.310  4193  4205 D BluetoothAdapterProperties: Setting state to 11
09-08 18:33:44.311  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 18:33:44.322  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:44.325  4193  4193 D HeadsetService: Received start request. Starting profile...
09-08 18:33:44.330  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:44.333  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:44.335  4193  4193 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:33:44.335  4193  4193 D HeadsetStateMachine: make
,09-08 18:33:44.345  4193  4205 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:33:44.346  4193  4193 D HeadsetStateMachine: max_hf_connections = 1
,09-08 18:33:44.347  4193  4193 I bt_bluedroid: get_profile_interface handsfree
,09-08 18:33:44.347  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 18:33:44.348  4193  4209 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 18:33:44.355  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:44.356  4193  4193 D A2dpService: Received start request. Starting profile...
09-08 18:33:44.356  4193  4193 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 18:33:44.357  4193  4193 I bt_bluedroid: get_profile_interface avrcp
,09-08 18:33:44.365  4193  4193 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 18:33:44.366  4193  4193 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-08 18:33:44.366  4193  4193 D A2dpStateMachine: make
,09-08 18:33:44.367  4193  4193 I bt_bluedroid: get_profile_interface a2dp
,09-08 18:33:44.369  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 18:33:44.372  4193  4224 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:33:44.373  4193  4193 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 18:33:44.374  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:44.375  4193  4193 D HidService: Received start request. Starting profile...
09-08 18:33:44.375  4193  4193 I bt_bluedroid: get_profile_interface hidhost
,09-08 18:33:44.376  4193  4193 D HidService: setHidService(): set to: null
,09-08 18:33:44.376  4193  4209 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c53e5
09-08 18:33:44.377  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-08 18:33:44.377  4193  4193 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 18:33:44.379  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
09-08 18:33:44.380  4193  4193 D HealthService: Received start request. Starting profile...
,09-08 18:33:44.383  4193  4193 I bt_bluedroid: get_profile_interface health
09-08 18:33:44.384  4193  4193 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 18:33:44.385  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:44.386  4193  4193 D PanService: Received start request. Starting profile...
09-08 18:33:44.386  4193  4193 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 18:33:44.387  4193  4193 I bt_bluedroid: get_profile_interface pan
09-08 18:33:44.387  4193  4209 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 18:33:44.395  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:33:44.396  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:33:44.399  4193  4193 D BluetoothMapService: Received start request. Starting profile...
09-08 18:33:44.399  4193  4193 D BluetoothMapService: start()
09-08 18:33:44.402  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 18:33:44.403  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 18:33:44.403  4193  4193 D BluetoothMapAppObserver: createReceiver()
,09-08 18:33:44.406  4193  4193 D BluetoothMapAppObserver: initObservers()
,09-08 18:33:44.406  4193  4193 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 18:33:44.422  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:44.423  4193  4193 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:44.423  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:44.423  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:44.428  4193  4222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 18:33:44.428  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:44.428  4193  4193 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:44.428  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isTurningOff()=false
09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false,
,09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:44.429  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:33:44.430  4193  4193 V BluetoothAdapterState: isTurningOff()=false
09-08 18:33:44.430  4193  4193 V BluetoothAdapterState: isTurningOn()=true
09-08 18:33:44.430  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:44.430  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:44.433  4193  4193 V BluetoothAdapterState: isTurningOff()=false
09-08 18:33:44.433  4193  4193 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:33:44.433  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:33:44.433  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:33:44.433  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 18:33:44.433  4193  4205 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:33:44.433  4193  4205 D BluetoothAdapterProperties: State =  11
09-08 18:33:44.434  4193  4205 D BluetoothAdapterProperties: Setting state to 12
09-08 18:33:44.434  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 18:33:44.435   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 18:33:44.435  1348  1361 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:44.436  4193  4205 I BluetoothAdapterState: Entering OnState
09-08 18:33:44.436  3897  3907 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:44.437  1348  2085 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:33:44.439  4193  4209 D BluetoothAdapterProperties: Scan Mode:21
,09-08 18:33:44.440  4193  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:33:44.441  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:33:44.441  1348  1348 D BluetoothA2dp: Proxy object connected
,09-08 18:33:44.443  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:44.445  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:44.445  4193  4193 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 18:33:44.447  1348  2085 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:33:44.451  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:44.452  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:44.453  3897  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:33:44.456  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:44.456   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 18:33:44.456   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:44.457  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:33:44.457   871   871 D BluetoothA2dp: Proxy object connected
09-08 18:33:44.457  3897  3907 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:33:44.460  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:33:44.460  4193  4193 D ObexServerSockets: Succeed to create listening sockets 
09-08 18:33:44.460  3897  3908 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:33:44.462  4193  4193 D ObexServerSockets0: startAccept()
,09-08 18:33:44.462  4193  4193 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:33:44.466  3897  3897 D BluetoothA2dp: Proxy object connected
,09-08 18:33:44.466  1940  1951 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:33:44.467  1348  1361 D BluetoothPan: onBluetoothStateChange on: true
,09-08 18:33:44.467  4193  4193 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 18:33:44.467  4193  4193 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 18:33:44.468  4193  4231 D ObexServerSockets0: Accepting socket connection...
09-08 18:33:44.469  1348  1348 D BluetoothInputDevice: Proxy object connected
09-08 18:33:44.469  1348  1348 D HidProfile: Bluetooth service connected
09-08 18:33:44.470  3897  3908 D BluetoothPan: onBluetoothStateChange on: true
,09-08 18:33:44.470  4193  4232 D ObexServerSockets0: Accepting socket connection...
09-08 18:33:44.471  1348  1348 D BluetoothMap: Proxy object connected
,09-08 18:33:44.471  1348  1348 D MapProfile: Bluetooth service connected
09-08 18:33:44.471  1348  1348 D BluetoothMap: getConnectedDevices()
,09-08 18:33:44.472  1348  2085 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:33:44.472  3897  3897 D BluetoothInputDevice: Proxy object connected
09-08 18:33:44.472  3897  3897 D HidProfile: Bluetooth service connected
,09-08 18:33:44.472  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:33:44.473  1348  1348 D PanProfile: Bluetooth service connected
09-08 18:33:44.473  3897  3907 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:33:44.475   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 18:33:44.475  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:33:44.475  3897  3897 D PanProfile: Bluetooth service connected
,09-08 18:33:44.475  3897  3897 D BluetoothMap: Proxy object connected
09-08 18:33:44.475  3897  3897 D MapProfile: Bluetooth service connected
09-08 18:33:44.476  3897  3897 D BluetoothMap: getConnectedDevices()
09-08 18:33:44.476   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 18:33:44.477  4193  4193 D BluetoothMapService: onReceive
09-08 18:33:44.477  4193  4193 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:33:44.477  4193  4193 D BluetoothMapService: STATE_ON
09-08 18:33:44.478  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:33:44.479  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:44.483  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:33:44.489  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:33:44.490  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:33:44.499  3897  3897 D BluetoothPbap: Proxy object connected
09-08 18:33:44.499  3897  3897 D PbapServerProfile: Bluetooth service connected
,09-08 18:33:44.505  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 18:33:44.505  4193  4193 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:33:44.507  1348  1348 D BluetoothPbap: Proxy object connected
09-08 18:33:44.508  1348  1348 D PbapServerProfile: Bluetooth service connected
,09-08 18:33:44.512  4193  4237 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:44.528  4193  4241 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:33:44.529  4193  4241 I BtOppRfcommListener: Accept thread started.
,09-08 18:33:44.540   871   871 D BluetoothHeadset: Proxy object connected
09-08 18:33:44.540  1940  2213 D BluetoothHeadset: Proxy object connected
,09-08 18:33:44.541  3897  3907 D BluetoothHeadset: Proxy object connected
,09-08 18:33:44.541  3897  3897 D HeadsetProfile: Bluetooth service connected
,09-08 18:33:44.541  1348  1360 D BluetoothHeadset: Proxy object connected
09-08 18:33:44.542   871   871 D BluetoothHeadset: Proxy object connected
09-08 18:33:44.542   871   871 D BluetoothHeadset: Proxy object connected
,09-08 18:33:44.542  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 18:33:44.557   871   888 D BluetoothHeadset: Proxy object connected
,09-08 18:33:44.567  1940  1953 D BluetoothHeadset: Proxy object connected
,09-08 18:33:44.575   871   888 D BluetoothHeadset: Proxy object connected
,09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:47.575  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:47.582  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:47.583  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:33:47.584  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8778bb removed from the list
,09-08 18:33:47.584  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:33:47.584  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:47.585  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:33:47.587  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:33:47.587  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1991d8 added. We now have 4 listener(s)
,09-08 18:33:47.588  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:33:47.592   871  1971 D WifiService: setWifiEnabled: false pid=3833, uid=10000
09-08 18:33:47.592   871  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:52.607  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:33:52.609   871   881 D WifiService: setWifiEnabled: true pid=3833, uid=10000
09-08 18:33:52.609   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:33:52.627   871  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:52.645  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:52.661  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:52.663   871  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-08 18:33:52.665   871  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 18:33:52.665   871  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 18:33:52.666   871  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 18:33:52.667   871  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 18:33:52.667   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 18:33:52.668   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:33:52.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:33:52.672  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:33:52.689   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 18:33:52.690   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:52.690   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:52.691   871  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 18:33:52.691   871  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 18:33:52.751   871  1303 E native  : do suspend true
,09-08 18:33:52.754   871  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 18:33:52.770   871  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 18:33:52.791   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:54.094   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 18:33:54.230   871  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.25 rxSuccessRate=15.62 delta 1000 -> 994
,09-08 18:33:54.232   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 18:33:54.232   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:54.247   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 18:33:54.284   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 18:33:54.285  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 18:33:54.728  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:33:54.772  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 18:33:54.772  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 18:33:54.780   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:33:54.794   871  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 18:33:54.795   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:33:54.795   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 18:33:54.818   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:33:54.838   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:54.840   871  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 18:33:54.849   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 18:33:54.864   871  4251 D DhcpClient: Receive thread started
,09-08 18:33:54.961   871  1303 E native  : do suspend false
,09-08 18:33:54.988   871  2080 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 18:33:55.004   871  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 18:33:55.005   871  2080 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 18:33:55.009   871  2080 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 18:33:55.029   871  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 18:33:55.030   871  2080 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 18:33:55.037   371   869 D CommandListener: Setting iface cfg
,09-08 18:33:55.050   871  2080 D DhcpClient: Scheduling renewal in 86399s
,09-08 18:33:55.051   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 18:33:55.054   871  1303 E native  : do suspend true
,09-08 18:33:55.073   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 18:33:55.077   871  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 18:33:55.078   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 18:33:55.080   871  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 18:33:55.086   871  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:33:55.134   871  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:33:55.134   871  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 18:33:55.136   871  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 18:33:55.137   871  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 18:33:55.138   871  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 18:33:55.155   871  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 18:33:55.166   871  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 18:33:55.167   871  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 18:33:55.167   871  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 18:33:55.167   871  1305 D ConnectivityService:    accepting network in place of null
,09-08 18:33:55.167   871  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 18:33:55.168   871  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:33:55.169   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:33:55.180   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=395517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:33:55.223   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:55.248   871  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 18:33:55.273   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:33:55.283   871  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 18:33:55.283   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:55.292   871  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 18:33:55.294   871   888 D Tethering: MasterInitialState.processMessage what=3,
,09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:55.308  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:33:55.311  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:55.317  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:33:55.319   871  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:33:55 GMT], X-Android-Received-Millis=[1473352435318], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473352435293]}
09-08 18:33:55.320  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:33:55.320   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 18:33:55.321   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 18:33:55.321   871  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 18:33:55.322   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:33:55.330  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:33:55.336  1716  1716 D SystemUpdateService: onCreate
,09-08 18:33:55.339  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:33:55.357  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 18:33:55.361  1716  2571 I iu.UploadsManager: num queued entries: 0
09-08 18:33:55.362  1716  2571 I iu.UploadsManager: num updated entries: 0
,09-08 18:33:55.362  1716  2571 I iu.SyncManager: NEXT; no task
,09-08 18:33:55.366  1716  4262 I SystemUpdateService: active receiver: enabled
,09-08 18:33:55.370  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:33:55.371  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 18:33:55.373  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:33:55.391  1716  4264 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 18:33:55.391  1716  4264 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:33:55.394  3950  3950 D SprintDMHelper: simOperator: 
,09-08 18:33:55.394  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:33:55.394  1716  4264 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 18:33:55.398  1716  4262 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:33:55.416  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:55.419  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:33:55.455  1716  4262 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 18:33:55.455  1716  4262 I SystemUpdateService: now status is 0 (complete)
09-08 18:33:55.455  1716  4262 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:33:55.455  1716  4262 I SystemUpdateService: file has been verified
09-08 18:33:55.455  1716  4262 I SystemUpdateService: OTA package size = 12249756
,09-08 18:33:55.496  1716  4262 I SystemUpdateService: showing system update notification
,09-08 18:33:55.544  1716  1716 D SystemUpdateService: onDestroy
,09-08 18:33:55.556  3036  4267 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 18:33:55.564  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 18:33:55.564  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 18:33:55.565  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:33:55.565  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:33:55.582  1716  4264 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-08 18:33:56.282   871  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:33:57.636  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:33:57.643  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:33:57.644  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:33:57.644  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1991d8 removed from the list
09-08 18:33:57.645  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:33:57.645  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:33:57.645  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:33:57.657  3833  4275 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 18:33:57.658  3833  4275 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 18:34:00.674  3833  4275 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 18:34:00.675  3833  4275 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 18:34:00.677  3833  4275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 18:34:00.680  3833  4276 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-08 18:34:00.680  3833  4276 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 18:34:00.681  3833  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 18:34:00.682  3833  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 18:34:00.683  3833  4275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 18:34:00.687  3833  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: IncomingSocketThread/Sender)
09-08 18:34:00.687  3833  4275 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 18:34:00.688  3833  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Sender)
,09-08 18:34:00.688  3833  4276 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 18:34:00.688  3833  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: OutgoingSocketThread/Receiver),
09-08 18:34:00.689  3833  4280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 424, thread name: OutgoingSocketThread/Receiver)
09-08 18:34:00.689  3833  4280 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 18:34:00.690  3833  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 424, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 18:34:00.692  3833  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Receiver)
09-08 18:34:00.693  3833  4281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: IncomingSocketThread/Receiver)
09-08 18:34:00.693  3833  4281 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 18:34:00.693  3833  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 18:34:03.174   871  1305 D ConnectivityService: handlePromptUnvalidated 102
,09-08 18:34:03.664  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 18:34:03.666  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 18:34:03.673  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ce20b52 Bundle[{}]
,09-08 18:34:03.675  3833  3880 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 18:34:03.676  3833  3880 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 18:34:03.678  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 18:34:03.680  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 18:34:03.682  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 18:34:03.685  3833  3880 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 18:34:03.689  3833  3880 I System.out: Running OutgoingSocketThread
,09-08 18:34:03.693  3833  4282 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 18:34:03.693  3833  4282 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 18:34:06.703  3833  4282 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 18:34:06.703  3833  4282 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 18:34:06.703  3833  4283 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 18:34:06.704  3833  4282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 18:34:06.704  3833  4283 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 18:34:06.706  3833  4283 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 18:34:06.706  3833  4282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 18:34:06.710  3833  4283 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 18:34:06.711  3833  4282 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 18:34:06.717  3833  4285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Sender)
,09-08 18:34:06.719  3833  4287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
09-08 18:34:06.722  3833  4286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Sender)
09-08 18:34:06.722  3833  4283 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 18:34:06.720  3833  4287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
09-08 18:34:06.723  3833  4287 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 18:34:06.723  3833  4287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 18:34:06.725  3833  4288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Receiver)
09-08 18:34:06.726  3833  4288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: IncomingSocketThread/Receiver)
09-08 18:34:06.726  3833  4288 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 18:34:06.727  3833  4288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 18:34:09.704  3833  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,09-08 18:34:09.706  3833  3880 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 18:34:09.707  3833  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,09-08 18:34:09.713  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:34:09.713  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6631931 added. We now have 3 listener(s)
09-08 18:34:09.715  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:34:09.715  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:34:09.715  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:34:09.715  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:34:09.715  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4d816 added. We now have 4 listener(s)
09-08 18:34:09.715  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:34:09.717  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:34:09.721  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:34:09.732  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:34:09.738  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:34:09.739  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:34:09.739  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:34:09.739  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:34:09.739  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:34:09.740  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:09.740  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:09.740  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:09.740  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:34:09.740  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6631931 removed from the list
09-08 18:34:09.740  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:09.740  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4d816 removed from the list
,09-08 18:34:09.744  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:09.751  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:09.751  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:34:09.752  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:09.753  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:09.753  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:09.757  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:34:09.757  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:09.758  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:09.758  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4d816 not in the list
09-08 18:34:09.758  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:09.759  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:09.765  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:34:09.765  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:09.765  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:09.766  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4d816 not in the list
09-08 18:34:09.766  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:09.766  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:09.766  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:09.767  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6631931 not in the list
09-08 18:34:09.770  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:34:09.770  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e81f384 added. We now have 3 listener(s)
,09-08 18:34:09.779  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:34:09.779  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:34:09.779  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:34:09.779  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:34:09.779  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f176d added. We now have 4 listener(s)
09-08 18:34:09.779  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:34:09.780  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:34:09.784  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:34:09.795  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:34:09.800  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:34:09.801  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:34:09.801  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:34:09.801  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:34:09.802  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:34:09.802  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:34:09.802  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:34:09.808  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:09.810  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:34:09.810  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:34:09.816  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:09.819  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:34:09.821  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:34:09.822  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:34:09.832  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:34:09.833  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:34:09.833  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:34:09.835  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:34:09.844  4193  4204 D BtGatt.GattService: registerClient() - UUID=e62722c3-f5cc-4de8-a484-e67cf8497e96
,09-08 18:34:09.846  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=e62722c3-f5cc-4de8-a484-e67cf8497e96, clientIf=5
,09-08 18:34:09.848  3833  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:34:09.850  4193  4203 D BtGatt.GattService: start scan with filters
,09-08 18:34:09.859  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:34:09.859  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:34:09.860  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 18:34:09.860  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 18:34:09.860  4193  4212 D BtGatt.ScanManager: handling starting scan
,09-08 18:34:09.866  4193  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dc28c6
,09-08 18:34:09.869  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:34:09.870  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:34:09.870  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:34:09.877  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:34:09.884  3833  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:34:09.884  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:34:09.884  4193  4209 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 18:34:09.885  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:09.886  4193  4212 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 18:34:09.887  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:34:09.887  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:09.887  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 18:34:09.887  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:34:09.887  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-08 18:34:09.888  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:34:09.888  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:34:09.888  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:34:09.888  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:34:09.890  3833  3880 D BluetoothAdapter: STATE_ON
09-08 18:34:09.892  4193  4204 D BtGatt.GattService: stopScan() - queue size =1
09-08 18:34:09.894  4193  4203 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:34:09.896  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:34:09.896  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 18:34:09.896  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 18:34:09.897  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:34:09.897  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:34:09.899  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:34:09.900  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:34:09.900  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 18:34:09.900  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:34:09.902  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:09.902  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:34:09.902  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:09.903  4193  4212 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:34:09.903  4193  4212 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 18:34:09.905  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:34:09.905  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:34:09.905  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:34:09.931  4193  4209 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:34:09.931  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:09.945  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 18:34:09.945  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:09.964  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 18:34:09.965  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:09.965  4193  4212 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:34:09.983  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:34:09.984  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:09.984  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:34:10.006  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:34:10.006  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:10.406  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:34:10.406  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:34:10.407  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:34:12.906  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:34:12.907  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:34:12.907  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:34:12.908  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:34:12.909  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:12.909  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:12.910  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:34:12.910  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e81f384 removed from the list
,09-08 18:34:12.910  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:12.911  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f176d removed from the list
09-08 18:34:12.911  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:34:12.911  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:12.913  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:12.913  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:12.917  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:34:12.917  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:34:12.917  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:12.918  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f176d not in the list
,09-08 18:34:12.918  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:12.918  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:12.921  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:12.922  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:12.922  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:12.923  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f176d not in the list
09-08 18:34:12.923  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:12.923  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:12.923  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:12.924  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e81f384 not in the list
09-08 18:34:12.926  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:34:12.927  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b6d3ee added. We now have 3 listener(s)
,09-08 18:34:12.929  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:34:12.929  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:34:12.929  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:34:12.929  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:34:12.930  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7ef08f added. We now have 4 listener(s)
09-08 18:34:12.930  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:34:12.930  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:34:12.934  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:34:12.939  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:34:12.941  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:34:12.941  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:34:12.942  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 18:34:12.943  3833  3880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 18:34:12.943  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 18:34:12.943  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 18:34:12.943  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 18:34:12.943  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 18:34:12.943  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:34:12.947  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 18:34:12.947  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 18:34:12.947  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 18:34:12.947  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:34:12.947  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 18:34:12.948  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:34:12.948  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:34:12.953  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:12.957  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 18:34:12.957  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:34:12.959  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:12.959  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 18:34:12.959  3833  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:34:12.963  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:34:12.965  3833  4289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 18:34:12.966  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 18:34:12.966  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:34:12.968  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 18:34:12.969  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:34:12.969  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-08 18:34:12.970  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 18:34:12.971  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 18:34:12.971  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 18:34:12.972  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:34:12.975  4193  4229 D BtGatt.GattService: registerClient() - UUID=0a5149f0-8a54-4d96-a502-deb2f8f09da4
,09-08 18:34:12.975  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=0a5149f0-8a54-4d96-a502-deb2f8f09da4, clientIf=5
,09-08 18:34:12.976  3833  3887 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-08 18:34:12.978  4193  4211 D BtGatt.AdvertiseManager: message : 0
,09-08 18:34:12.980  4193  4211 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 18:34:12.990  4193  4209 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 18:34:12.998  4193  4209 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 18:34:12.999  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-08 18:34:13.000  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:34:13.001  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:34:13.003  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 18:34:13.003  3833  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 18:34:13.003  3833  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 18:34:13.003  3833  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 18:34:13.003  3833  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 18:34:13.003  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 18:34:13.006  3833  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 18:34:13.006  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 18:34:13.006  3833  3880 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 18:34:13.006  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 18:34:13.506  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 18:34:16.008  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:34:16.008  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 18:34:16.009  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:34:16.009  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:34:16.009  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 18:34:16.010  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 18:34:16.010  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 18:34:16.010  3833  4289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 18:34:16.011  3833  4289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:34:16.011  3833  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 18:34:16.011  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:34:16.011  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 18:34:16.011  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:34:16.012  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:34:16.012  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:34:16.012  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:34:16.012  3833  4289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:34:16.015  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:34:16.015  3833  3880 D BluetoothLeScanner: could not find callback wrapper
,09-08 18:34:16.015  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:34:16.016  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 18:34:16.018  4193  4211 D BtGatt.AdvertiseManager: message : 1
09-08 18:34:16.020  4193  4211 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 18:34:16.031  4193  4209 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 18:34:16.031  4193  4209 D BtGatt.GattService: Client app is not null!
,09-08 18:34:16.034  4193  4221 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:34:16.034  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:34:16.034  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 18:34:16.034  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 18:34:16.035  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 18:34:16.035  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-08 18:34:16.036  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:34:16.036  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 18:34:16.036  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:34:16.037  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:34:16.038  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:16.038  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:16.038  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:16.038  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:34:16.039  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b6d3ee removed from the list
09-08 18:34:16.039  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:16.039  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7ef08f removed from the list
09-08 18:34:16.039  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:34:16.039  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:16.039  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:34:16.039  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:34:16.040  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 18:34:16.040  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:34:16.040  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:16.040  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:16.043  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:16.043  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:16.043  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:34:16.043  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7ef08f not in the list
09-08 18:34:16.044  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:16.044  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:16.047  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:34:16.047  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:16.047  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:16.047  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7ef08f not in the list
09-08 18:34:16.047  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:16.047  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:16.047  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:16.047  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b6d3ee not in the list
09-08 18:34:16.048  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:34:16.048  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1812108 added. We now have 3 listener(s)
09-08 18:34:16.050  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:34:16.050  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:34:16.051  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:34:16.051  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:34:16.051  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0a1 added. We now have 4 listener(s)
09-08 18:34:16.051  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:34:16.052  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:34:16.057  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:34:16.064  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:34:16.065  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:34:16.066  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:34:16.066  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:34:16.066  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 18:34:16.066  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:34:16.066  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:34:16.066  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:34:16.069  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:34:16.070  3833  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:34:16.070  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:34:16.072  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:16.077  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:34:16.078  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:34:16.078  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:34:16.082  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:34:16.082  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:34:16.082  3833  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:34:16.083  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:34:16.085  4193  4229 D BtGatt.GattService: registerClient() - UUID=bfcc4645-e2d2-4b09-ba0a-7df717186013
,09-08 18:34:16.086  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=bfcc4645-e2d2-4b09-ba0a-7df717186013, clientIf=5
,09-08 18:34:16.087  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 18:34:16.087  4193  4221 D BtGatt.GattService: start scan with filters
,09-08 18:34:16.090  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:34:16.090  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:34:16.090  4193  4212 D BtGatt.ScanManager: handling starting scan
09-08 18:34:16.090  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:34:16.090  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:34:16.095  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:34:16.095  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:34:16.096  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:34:16.098  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 18:34:16.098  4193  4209 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 18:34:16.099  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:16.100  4193  4212 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:34:16.108  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 18:34:16.109  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:16.110  4193  4212 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:34:16.111  4193  4212 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:34:16.125  4193  4209 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:34:16.125  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:16.133  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 18:34:16.133  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:16.541  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:34:16.596  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 18:34:16.596  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:34:16.596  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:34:17.645  4193  4193 D BtGatt.ScanManager: awakened up at time 417982
,09-08 18:34:17.647  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:34:17.718  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 18:34:17.718  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:17.718  4193  4209 D BtGatt.GattService: current time is 418055523269
09-08 18:34:17.719  4193  4209 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -93, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -75, 112, 8, 38, 113, -28, 1, 0, -105, 25, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -121, -84, -6, 2, 2, -25, 23, 62, -115, 69, 28, 28, 6, 8, 116, 105, 115, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 18:34:17.721  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 18:34:17.721  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 18:34:17.722  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -121, -84, -6, 2, 2, -25, 23, 62, -115, 69, 28, 6, 8, 116, 105, 115, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-08 18:34:17.722  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 18:34:17.722  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 18:34:17.722  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 18:34:17.72,3  4193  4209 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 18:34:19.109  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:34:19.110  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:34:19.110  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:34:19.111  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.111  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 18:34:19.111  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:34:19.111  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:34:19.112  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:34:19.112  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:34:19.112  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:34:19.113  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:34:19.115  3833  3880 D BluetoothAdapter: STATE_ON
,09-08 18:34:19.117  4193  4204 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:34:19.119  4193  4203 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:34:19.124  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:34:19.124  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:34:19.124  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:34:19.125  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:34:19.125  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 18:34:19.129  4193  4193 D BtGatt.ScanManager: awakened up at time 419466
09-08 18:34:19.129  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:34:19.130  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:34:19.130  3833  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:34:19.130  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:34:19.136  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:34:19.141  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:19.141  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:34:19.141  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:19.141  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:34:19.141  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:19.142  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:34:19.142  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:34:19.142  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1812108 removed from the list
09-08 18:34:19.142  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:19.143  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0a1 removed from the list
09-08 18:34:19.143  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:34:19.144  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:19.144  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.144  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:19.145  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:19.145  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:19.145  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:19.146  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0a1 not in the list
09-08 18:34:19.146  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.146  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:19.147  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:19.147  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:19.147  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:34:19.147  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0a1 not in the list
,09-08 18:34:19.147  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:19.147  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.147  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:19.147  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1812108 not in the list
09-08 18:34:19.148  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:34:19.148  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1f552 added. We now have 3 listener(s)
09-08 18:34:19.150  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:34:19.150  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:34:19.151  4193  4212 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:34:19.150  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:34:19.151  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:34:19.151  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:34:19.151  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:34:19.151  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290a023 added. We now have 4 listener(s)
09-08 18:34:19.151  3833  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:34:19.152  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:34:19.155  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:34:19.161  3833  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:34:19.164  3833  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:34:19.164  3833  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:34:19.164  3833  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:34:19.165  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:34:19.164  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:34:19.165  3833  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:34:19.165  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:19.165  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:19.165  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.165  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:34:19.165  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:34:19.165  3833  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:34:19.165  3833  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1f552 removed from the list
09-08 18:34:19.166  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:19.166  3833  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290a023 removed from the list
09-08 18:34:19.168  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:34:19.171  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:34:19.172  3833  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:34:19.173  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:19.176  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:34:19.176  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:34:19.175  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.177  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:19.180  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:34:19.180  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:34:19.180  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:34:19.181  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290a023 not in the list
09-08 18:34:19.182  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:34:19.183  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:34:19.184  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:34:19.184  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:34:19.185  3833  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:34:19.185  3833  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290a023 not in the list
09-08 18:34:19.185  3833  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:34:19.185  3833  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:34:19.185  3833  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:34:19.185  3833  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1f552 not in the list
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 18:34:19.187  3833  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:34:19.643  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:34:21.203  3833  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,09-08 18:34:23.201  3833  3880 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 455
,09-08 18:34:23.201  3833  3880 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 455, name: My test thread name)
,09-08 18:34:23.207  3833  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-08 18:34:23.208  3833  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
09-08 18:34:23.208  3833  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: My test thread name)
09-08 18:34:23.208  3833  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 18:34:23.213  3833  3880 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 18:34:23.223  3833  4292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-08 18:34:23.224  3833  4292 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 460, thread name: My test thread name): Test exception.
09-08 18:34:23.224  3833  4292 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 18:34:23.233  3833  3880 I jxcore-log: Total number of executed tests:  82
09-08 18:34:23.233  3833  3880 I jxcore-log: 
,09-08 18:34:23.234  3833  3880 I jxcore-log: Number of passed tests:  82
09-08 18:34:23.234  3833  3880 I jxcore-log: 
09-08 18:34:23.235  3833  3880 I jxcore-log: Number of failed tests:  0
09-08 18:34:23.235  3833  3880 I jxcore-log: 
,09-08 18:34:23.236  3833  3880 I jxcore-log: Number of ignored tests:  0
09-08 18:34:23.236  3833  3880 I jxcore-log: 
,09-08 18:34:23.237  3833  3880 I jxcore-log: Total duration:  101469
09-08 18:34:23.237  3833  3880 I jxcore-log: 
,09-08 18:34:23.248  3833  3880 I jxcore-log: Unit Test app is loaded
09-08 18:34:23.248  3833  3880 I jxcore-log: 
,09-08 18:34:23.265  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.265  3833  3880 I jxcore-log: 
,09-08 18:34:23.270  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.270  3833  3880 I jxcore-log: 
,09-08 18:34:23.271  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.271  3833  3880 I jxcore-log: 
,09-08 18:34:23.273  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.273  3833  3880 I jxcore-log: 
09-08 18:34:23.274  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 18:34:23.274  3833  3880 I jxcore-log: 
,09-08 18:34:23.277  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.277  3833  3880 I jxcore-log: 
,09-08 18:34:23.281  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.281  3833  3880 I jxcore-log: 
,09-08 18:34:23.283  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.283  3833  3880 I jxcore-log: 
09-08 18:34:23.284  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 18:34:23.284  3833  3880 I jxcore-log: 
,09-08 18:34:23.285  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.285  3833  3880 I jxcore-log: 
09-08 18:34:23.286  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.286  3833  3880 I jxcore-log: 
,09-08 18:34:23.287  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.287  3833  3880 I jxcore-log: 
09-08 18:34:23.288  3833  3833 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 18:34:23.289  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.289  3833  3880 I jxcore-log: 
,09-08 18:34:23.290  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.290  3833  3880 I jxcore-log: 
,09-08 18:34:23.291  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.291  3833  3880 I jxcore-log: 
09-08 18:34:23.292  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.292  3833  3880 I jxcore-log: 
09-08 18:34:23.293  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.293  3833  3880 I jxcore-log: 
09-08 18:34:23.294  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.294  3833  3880 I jxcore-log: 
,09-08 18:34:23.295  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.295  3833  3880 I jxcore-log: 
,09-08 18:34:23.295  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.295  3833  3880 I jxcore-log: 
,09-08 18:34:23.297  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.297  3833  3880 I jxcore-log: 
09-08 18:34:23.297  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.297  3833  3880 I jxcore-log: 
09-08 18:34:23.298  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.298  3833  3880 I jxcore-log: 
09-08 18:34:23.299  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.299  3833  3880 I jxcore-log: 
,09-08 18:34:23.301  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.301  3833  3880 I jxcore-log: 
,09-08 18:34:23.301  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.301  3833  3880 I jxcore-log: 
09-08 18:34:23.302  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.302  3833  3880 I jxcore-log: 
09-08 18:34:23.303  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.303  3833  3880 I jxcore-log: 
,09-08 18:34:23.303  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.303  3833  3880 I jxcore-log: 
,09-08 18:34:23.304  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.304  3833  3880 I jxcore-log: 
09-08 18:34:23.304  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.304  3833  3880 I jxcore-log: 
09-08 18:34:23.305  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.305  3833  3880 I jxcore-log: 
09-08 18:34:23.305  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.305  3833  3880 I jxcore-log: 
09-08 18:34:23.306  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.306  3833  3880 I jxcore-log: 
,09-08 18:34:23.306  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.306  3833  3880 I jxcore-log: 
09-08 18:34:23.307  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.307  3833  3880 I jxcore-log: 
09-08 18:34:23.307  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.307  3833  3880 I jxcore-log: 
09-08 18:34:23.308  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:34:23.308  3833  3880 I jxcore-log: 
,09-08 18:34:23.308  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.308  3833  3880 I jxcore-log: 
09-08 18:34:23.309  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:34:23.309  3833  3880 I jxcore-log: 
09-08 18:34:23.309  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.309  3833  3880 I jxcore-log: 
09-08 18:34:23.310  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.310  3833  3880 I jxcore-log: 
09-08 18:34:23.310  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.310  3833  3880 I jxcore-log: 
,09-08 18:34:23.311  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.311  3833  3880 I jxcore-log: 
09-08 18:34:23.311  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.311  3833  3880 I jxcore-log: 
09-08 18:34:23.312  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.312  3833  3880 I jxcore-log: 
09-08 18:34:23.312  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.312  3833  3880 I jxcore-log: 
,09-08 18:34:23.313  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 18:34:23.313  3833  3880 I jxcore-log: 
09-08 18:34:23.314  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.314  3833  3880 I jxcore-log: 
09-08 18:34:23.314  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.314  3833  3880 I jxcore-log: 
09-08 18:34:23.315  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 18:34:23.315  3833  3880 I jxcore-log: 
09-08 18:34:23.315  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:34:23.315  3833  3880 I jxcore-log: 
,09-08 18:34:23.316  3833  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:34:23.316  3833  3880 I jxcore-log: 
,09-08 18:34:23.318  3833  3880 I jxcore-log: My device name is: motorola-Nexus 6
09-08 18:34:23.318  3833  3880 I jxcore-log: 
09-08 18:34:23.319  3833  3880 I jxcore-log: WARN testUtils: myNameCallback not set!
09-08 18:34:23.319  3833  3880 I jxcore-log: 
,09-08 18:34:23.319  3833  3880 I jxcore-log: Running for WIFI network type
09-08 18:34:23.319  3833  3880 I jxcore-log: 
,09-08 18:34:25.732  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 18:34:25.732  3833  3880 I jxcore-log: 
,09-08 18:34:26.224  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 18:34:26.224  3833  3880 I jxcore-log: 
,09-08 18:34:26.258  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 18:34:26.258  3833  3880 I jxcore-log: 
,09-08 18:34:27.658  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 18:34:27.658  3833  3880 I jxcore-log: 
,09-08 18:34:27.906  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 18:34:27.906  3833  3880 I jxcore-log: 
,09-08 18:34:27.912  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 18:34:27.912  3833  3880 I jxcore-log: 
,09-08 18:34:27.918  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 18:34:27.918  3833  3880 I jxcore-log: 
,09-08 18:34:28.191  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 18:34:28.191  3833  3880 I jxcore-log: 
,09-08 18:34:28.207  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 18:34:28.207  3833  3880 I jxcore-log: 
,09-08 18:34:28.212  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 18:34:28.212  3833  3880 I jxcore-log: 
,09-08 18:34:28.936  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 18:34:28.936  3833  3880 I jxcore-log: 
,09-08 18:34:29.107  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 18:34:29.107  3833  3880 I jxcore-log: 
,09-08 18:34:29.446  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 18:34:29.446  3833  3880 I jxcore-log: 
,09-08 18:34:29.457  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 18:34:29.457  3833  3880 I jxcore-log: 
,09-08 18:34:29.465  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 18:34:29.465  3833  3880 I jxcore-log: 
,09-08 18:34:29.472  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 18:34:29.472  3833  3880 I jxcore-log: 
,09-08 18:34:29.514  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 18:34:29.514  3833  3880 I jxcore-log: 
,09-08 18:34:29.562  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 18:34:29.562  3833  3880 I jxcore-log: 
,09-08 18:34:29.570  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 18:34:29.570  3833  3880 I jxcore-log: 
,09-08 18:34:29.578  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 18:34:29.578  3833  3880 I jxcore-log: 
,09-08 18:34:29.598  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 18:34:29.598  3833  3880 I jxcore-log: 
,09-08 18:34:29.604  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 18:34:29.604  3833  3880 I jxcore-log: 
,09-08 18:34:29.610  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 18:34:29.610  3833  3880 I jxcore-log: 
,09-08 18:34:29.627  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 18:34:29.627  3833  3880 I jxcore-log: 
,09-08 18:34:29.654  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 18:34:29.654  3833  3880 I jxcore-log: 
,09-08 18:34:29.666  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 18:34:29.666  3833  3880 I jxcore-log: 
,09-08 18:34:29.680  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 18:34:29.680  3833  3880 I jxcore-log: 
,09-08 18:34:29.692  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 18:34:29.692  3833  3880 I jxcore-log: 
,09-08 18:34:29.709  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 18:34:29.709  3833  3880 I jxcore-log: 
,09-08 18:34:29.720  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 18:34:29.720  3833  3880 I jxcore-log: 
,09-08 18:34:29.725  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 18:34:29.725  3833  3880 I jxcore-log: 
,09-08 18:34:29.756  3833  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 18:34:29.756  3833  3880 I jxcore-log: 
,09-08 18:34:29.770  3833  3880 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 18:34:29.772  3833  3880 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 18:34:29.772  3833  3880 I jxcore-log: 
,09-08 18:34:29.774  3833  3880 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 18:34:29.774  3833  3880 I jxcore-log: 
,09-08 18:34:29.775  3833  3880 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 18:34:29.775  3833  3880 I jxcore-log: 
,09-08 18:34:29.780  3833  3880 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 18:34:29.780  3833  3880 I jxcore-log: 
,09-08 18:34:29.910  3833  3880 I jxcore-log: ThaliTape :: Connected to the test server
09-08 18:34:29.910  3833  3880 I jxcore-log: 
,09-08 18:35:06.000  1502  2122 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 18:35:32.426  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:35:32.429  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:35:32.498  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:35:32.499  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:35:32.499  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:35:32.499  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:35:32.538  3542  4305 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:35:32.538  3542  4305 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:35:32.538  3542  4305 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	... 12 more
09-08 18:35:32.538  3542  4305 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at fal.a(PG:38)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:35:32.538  3542  4305 E HttpOperation: 	... 14 more
,09-08 18:35:32.604  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:35:32.604  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:35:32.604  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:35:32.605  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:35:32.636  3542  4305 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 18:35:32.636  3542  4305 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at hec.a(PG:42)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at hee.a(PG:102)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at czr.a(PG:65)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at kka.a(PG:108)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at czp.a(PG:19176)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:35:32.636  3542  4305 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	... 15 more
09-08 18:35:32.636  3542  4305 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at fal.a(PG:38)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:35:32.636  3542  4305 E HttpOperation: 	... 17 more
,09-08 18:35:32.636  3542  4305 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 18:35:32.636  3542  4305 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at hec.a(PG:42)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at hee.a(PG:102)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at czr.a(PG:65)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at kka.a(PG:108)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: ,	... 15 more
09-08 18:35:32.636  3542  4305 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at fal.a(PG:38)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 18:35:32.636  3542  4305 E ExperimentLoader: 	... 17 more
,09-08 18:35:32.775   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 492444, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:36:03.819  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:03.820  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:03.857  1502  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:36:03.858  1502  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:36:03.858  1502  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:36:03.858  1502  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:36:03.881  3542  4309 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:36:03.881  3542  4309 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:36:03.881  3542  4309 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	... 12 more
09-08 18:36:03.881  3542  4309 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at fal.a(PG:38)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:36:03.881  3542  4309 E HttpOperation: 	... 14 more
,09-08 18:36:03.943  1502  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:36:03.943  1502  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:36:03.943  1502  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:36:03.943  1502  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:36:03.968  3542  4309 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 18:36:03.968  3542  4309 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at hec.a(PG:42)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at hee.a(PG:102)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at czr.a(PG:65)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at kka.a(PG:108)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at czp.a(PG:19176)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:36:03.968  3542  4309 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	... 15 more
09-08 18:36:03.968  3542  4309 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at fal.a(PG:38)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:36:03.968  3542  4309 E HttpOperation: 	... 17 more
09-08 18:36:03.969  3542  4309 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 18:36:03.969  3542  4309 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at hec.a(PG:42)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at hee.a(PG:102)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at czr.a(PG:65)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at kka.a(PG:108)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	... 15 more
09-08 18:36:03.969  3542  4309 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at fal.a(PG:38)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 18:36:03.969  3542  4309 E ExperimentLoader: 	... 17 more
,09-08 18:36:04.124   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 523850, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:36:34.209  3586  4312 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 18:36:34.254  3586  4313 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 18:36:34.270  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:34.275  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:34.314  1502  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:36:34.314  1502  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 18:36:34.315  1502  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:36:34.315  1502  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:36:34.353  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:34.359  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:36:34.397  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:36:34.398  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 18:36:34.398  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:36:34.398  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:36:34.448  3586  4313 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 18:36:34.449  3586  4312 E BooksSync: Soft error
09-08 18:36:34.449  3586  4312 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:36:34.449  3586  4312 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 18:36:34.450  3586  4312 E BooksSync: Sync error
09-08 18:36:34.450  3586  4312 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:36:34.450  3586  4312 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 18:36:34.450  3586  4312 I BooksSync: Finished books sync
,09-08 18:36:34.458   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 525640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:37:04.693  3017  4316 V KeepSync: Connecting to GoogleApiClient
09-08 18:37:04.693   871  1378 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 18:37:04.742  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:37:04.745  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:37:04.783  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 18:37:04.784  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 18:37:04.784  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:04.784  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:04.808  1716  4317 V BaseAuthAsyncOperation: access token request failed
09-08 18:37:04.809  3017  4316 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 18:37:04.880  1502  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 18:37:04.880  1502  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 18:37:04.880  1502  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:04.880  1502  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:04.904  3017  4316 E KeepSync: IOException
09-08 18:37:04.904  3017  4316 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 18:37:04.904  3017  4316 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:37:04.904  3017  4316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 18:37:04.904  3017  4316 E KeepSync: 	... 10 more
,09-08 18:37:04.904  3017  4316 W KeepSync: Sync result 2
,09-08 18:37:04.914   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 558292, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:37:35.218  3586  4320 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 18:37:35.339  3586  4322 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 18:37:35.354  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:37:35.368  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:37:35.442  1502  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 18:37:35.442  1502  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 18:37:35.442  1502  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.442  1502  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.474  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:37:35.474  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:37:35.474  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.474  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.500  3542  4321 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:37:35.500  3542  4321 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:37:35.500  3542  4321 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	... 12 more
09-08 18:37:35.500  3542  4321 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at fal.a(PG:38)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:37:35.500  3542  4321 E HttpOperation: 	... 14 more
,09-08 18:37:35.553  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:37:35.553  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:37:35.553  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.553  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.554  1502  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:37:35.554  1502  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 18:37:35.554  1502  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.554  1502  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.607  3542  4321 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 18:37:35.607  3542  4321 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:37:35.607  3542  4321 E HttpOperation: ,	at jdm.a(PG:82)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at hec.a(PG:42)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at hee.a(PG:102)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at czr.a(PG:65)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at kka.a(PG:108)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at czp.a(PG:19176)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:37:35.607  3542  4321 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	... 15 more
09-08 18:37:35.607  3542  4321 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at fal.a(PG:38)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:37:35.607  3542  4321 E HttpOperation: 	... 17 more
09-08 18:37:35.608  3542  4321 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 18:37:35.608  3542  4321 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at hec.a(PG:42)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at hee.a(PG:102)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at czr.a(PG:65)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at kka.a(PG:108)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	... 15 more
09-08 18:37:35.608  3542  4321 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 18:37:35.608  ,3542  4321 E ExperimentLoader: 	at fal.a(PG:38)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 18:37:35.608  3542  4321 E ExperimentLoader: 	... 17 more
09-08 18:37:35.614  3586  4322 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:37:35.614  3586  4320 E BooksSync: Soft error
09-08 18:37:35.614  3586  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:37:35.614  3586  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 18:37:35.615  3586  4320 E BooksSync: Sync error
09-08 18:37:35.615  3586  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:37:35.615  3586  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 18:37:35.615  3586  4320 I BooksSync: Finished books sync
,09-08 18:37:35.632   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 587731, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:37:35.699  3017  4324 V KeepSync: Connecting to GoogleApiClient
,09-08 18:37:35.700   871  1966 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 18:37:35.758   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 585935, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:37:35.774  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 18:37:35.774  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 18:37:35.775  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.775  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.798  1716  4325 V BaseAuthAsyncOperation: access token request failed
09-08 18:37:35.799  3017  4324 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 18:37:35.843  1502  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 18:37:35.843  1502  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 18:37:35.843  1502  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:37:35.843  1502  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:37:35.866  3017  4324 E KeepSync: IOException
09-08 18:37:35.866  3017  4324 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 18:37:35.866  3017  4324 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:37:35.866  3017  4324 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 18:37:35.866  3017  4324 E KeepSync: 	... 10 more
,09-08 18:37:35.866  3017  4324 W KeepSync: Sync result 2
,09-08 18:37:35.875   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 615414, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:38:48.056  3499  3499 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-08 18:38:48.080  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.094  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.099  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.173  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 18:38:48.173  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 18:38:48.174  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:38:48.174  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:38:48.232  3499  3499 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-08 18:38:48.254  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.335  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 18:38:48.336  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 18:38:48.336  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:38:48.336  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:38:48.380  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.425  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 18:38:48.425  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 18:38:48.425  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:38:48.426  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:38:48.480  3499  3499 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-08 18:38:48.701  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:38:48.742  1502  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-08 18:38:48.742  1502  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 18:38:48.743  1502  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:38:48.743  1502  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:38:48.780  3499  3499 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-08 18:38:48.780  3499  3499 D Finsky  : [1] WearSupportService.startHygiene: disabled
09-08 18:38:48.781  3499  3499 D Finsky  : [1] DailyHygiene.access$600: Logging device features
09-08 18:38:48.786  3499  3572 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-08 18:38:48.790  3499  3499 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,09-08 18:39:03.786  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:03.802  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:03.808  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:03.866  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:39:03.866  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 18:39:03.866  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:39:03.867  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:39:03.920  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:39:03.922  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:39:03.923  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-08 18:39:24.243  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:24.254  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:24.257  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:24.308  1502  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 18:39:24.308  1502  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 18:39:24.309  1502  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:39:24.309  1502  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:39:24.345  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:39:24.347  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:39:24.347  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-08 18:39:44.514  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:44.520  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:44.521  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:39:44.560  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:39:44.561  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 18:39:44.561  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:39:44.561  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:39:44.598  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 18:39:44.598  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 18:39:44.598  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-08 18:40:04.812  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:04.821  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:04.823  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:04.851  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:40:04.852  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 18:40:04.852  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:40:04.852  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:40:04.885  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 18:40:04.885  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 18:40:04.886  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 18:40:25.234  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:25.248  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:25.252  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:25.299  1502  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 18:40:25.299  1502  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 18:40:25.300  1502  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:40:25.300  1502  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:40:25.347  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:40:25.348  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:40:25.348  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 18:40:45.659  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:45.672  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:45.677  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:40:45.752  1502  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:40:45.752  1502  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 18:40:45.753  1502  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:40:45.753  1502  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:40:45.819  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:40:45.820  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:40:45.821  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 18:42:12.587   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=892923, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:42:31.314   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=911651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:42:37.580   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=917917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:42:56.367   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:43:02.647   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=942983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:43:21.447   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=961784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:43:27.713   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=968050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:43:46.514   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:43:52.780   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=993117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:44:11.581   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:44:17.873   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1018210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:44:36.660   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1036997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:44:42.940   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1043277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:45:01.727   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:45:08.007   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1068343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:45:26.794   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:45:33.073   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1093410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:45:51.860   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1112197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:45:58.140   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1118477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:46:16.941   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:46:23.207   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1143543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:46:42.007   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1162343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:46:48.273   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1168610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:47:07.074   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:47:11.713   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1192050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:47:32.141   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1212477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:47:36.780   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:47:38.011   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 18:47:57.207   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:48:01.834   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1242170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:48:22.260   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1262597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:48:26.900   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1267237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:48:47.327   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1287664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:48:51.953   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:49:12.407   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1312744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:49:17.047   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1317383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:49:37.460   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1337797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:49:42.100   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1342436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:50:02.527   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1362863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:50:07.167   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1367503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:50:27.594   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1387930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:50:32.221   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1392557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:50:52.647   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1412983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:50:57.287   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1417623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:51:17.714   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:51:22.340   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1442677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:51:42.767   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:51:47.394   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:52:07.820   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1488157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:52:21.474   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1501811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:52:32.887   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1513223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:52:46.540   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1526877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:52:57.967   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1538304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:53:11.607   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1551944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:53:23.047   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1563383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:53:36.674   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1577010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:53:48.113   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1588450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:54:01.740   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1602077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:54:13.181   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1613517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:54:26.807   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1627144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:54:38.234   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1638570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:54:51.874   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1652210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:55:03.300   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1663637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:55:16.940   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1677277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:55:28.353   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1688690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:55:42.007   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1702343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 18:55:53.420   871  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1713757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
