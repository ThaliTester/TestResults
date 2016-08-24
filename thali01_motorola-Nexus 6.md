#### Test 82337235c6facd5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 14:32:17.612  1697  3845 I EventLogService: Opted in for usage reporting
08-24 14:32:17.615  1697  3845 I EventLogService: Aggregate from 1472040137456 (log), 1472040137456 (data)
,08-24 14:32:17.660  1697  3845 W EventLogAggregator: Unknown tag: snet_gcore
08-24 14:32:17.660  1697  3845 W EventLogAggregator: Unknown tag: snet_launch_service
08-24 14:32:17.719  1697  3845 I ServiceDumpSys: dumping service [account]
08-24 14:32:17.785  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:32:17.792  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:32:17.794  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:32:17.828  1505  3833 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 14:32:17.829  1505  3833 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 14:32:17.829  1505  3833 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:32:17.829  1505  3833 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 14:32:17.869  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 14:32:17.869  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 14:32:17.869  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-24 14:32:18.334  3848  3848 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 14:32:18.338  3848  3848 D AndroidRuntime: CheckJNI is OFF
08-24 14:32:18.375  3848  3848 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 14:32:18.418  3848  3848 I Radio-JNI: register_android_hardware_Radio DONE
08-24 14:32:18.436  3848  3848 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:32:18.439   873  1991 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:32:18.502   873  1991 I ActivityManager: Start proc 3857:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 14:32:18.511  3848  3848 D AndroidRuntime: Shutting down VM
08-24 14:32:18.645  3857  3857 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 14:32:18.675  3857  3857 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 14:32:18.683  3857  3857 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5065-5068)
08-24 14:32:18.683  3857  3857 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:32:18.701  3857  3857 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9dc5466}
08-24 14:32:18.702  3857  3857 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:32:18.702  3857  3857 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:32:18.708  3857  3857 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 14:32:18.710  3857  3857 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 14:32:18.735  3857  3857 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 14:32:18.769  3857  3857 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:32:18.769  3857  3857 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:32:18.769  3857  3857 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:32:18.769  3857  3857 I Adreno  : Build Date                       : 10/20/15
08-24 14:32:18.769  3857  3857 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:32:18.769  3857  3857 I Adreno  : Local Branch                     : M14
08-24 14:32:18.769  3857  3857 I Adreno  : Remote Branch                    : 
08-24 14:32:18.769  3857  3857 I Adreno  : Remote Branch                    : 
08-24 14:32:18.769  3857  3857 I Adreno  : Reconstruct Branch               : 
08-24 14:32:18.857   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4b1247:true
08-24 14:32:18.949  3857  3857 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 14:32:18.975  3857  3857 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-24 14:32:19.063  3857  3894 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-24 14:32:19.082  3857  3881 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-24 14:32:19.130  3857  3894 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:32:19.230   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +647ms (total +760ms)
08-24 14:32:19.235  1864  1864 I Keyboard.Facilitator: onFinishInput()
08-24 14:32:19.342  3857  3857 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3857
08-24 14:32:19.537  3857  3857 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-24 14:32:19.805  3857  3897 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680148176
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:32:19.815  3857  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a95775 added. We now have 1 listener(s)
08-24 14:32:19.820  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-24 14:32:19.821  3857  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:32:19.821  3857  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:32:19.822  3857  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:32:19.826  3857  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219e998 added. We now have 1 listener(s)
08-24 14:32:19.827  3857  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:19.832   873  1306 D WifiService: New client listening to asynchronous messages
08-24 14:32:19.833  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:32:19.833  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:32:19.833  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:32:19.833  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:32:19.833  3857  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 14:32:19.836  3857  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:19.836  3857  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-24 14:32:19.846  3857  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:19.847  3857  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:32:19.847  3857  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:32:19.847  3857  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:32:19.848  3857  3897 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:32:19.851  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:19.857  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:19.888  3857  3857 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:32:20.779  3857  3904 W jxcore-log: Initializing JXcore engine
08-24 14:32:20.779  3857  3904 W jxcore-log: JXcore engine is ready
,08-24 14:32:20.816  3904  3904 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8946 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 14:32:20.816  3904  3904 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11536]" dev="sockfs" ino=11536 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 14:32:20.816  3904  3904 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 14:32:20.816  3904  3904 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26364]" dev="sockfs" ino=26364 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 14:32:20.829  3857  3904 W jxcore-log: Starting JXcore engine
,08-24 14:32:20.908  3857  3904 W jxcore-log: Platform android
08-24 14:32:20.908  3857  3904 W jxcore-log: 
08-24 14:32:20.908  3857  3904 W jxcore-log: Process ARCH arm
08-24 14:32:20.908  3857  3904 W jxcore-log: 
,08-24 14:32:21.092  3857  3904 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:32:21.092  3857  3904 I jxcore-log: 
,08-24 14:32:21.093  3857  3904 W jxcore-log: JXcore engine is started
,08-24 14:32:21.104  3857  3897 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:32:21.109  3857  3857 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:32:25.183  3744  3906 V KeepSync: Connecting to GoogleApiClient
,08-24 14:32:25.183   873  1990 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 14:32:25.249  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:32:25.253  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:32:25.290  1505  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 14:32:25.290  1505  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 14:32:25.290  1505  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:32:25.290  1505  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:32:25.324  1697  3907 V BaseAuthAsyncOperation: access token request failed
,08-24 14:32:25.326  3744  3906 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 14:32:25.389  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 14:32:25.389  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 14:32:25.389  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 14:32:25.389  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:32:25.413  3744  3906 E KeepSync: IOException
08-24 14:32:25.413  3744  3906 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 14:32:25.413  3744  3906 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 14:32:25.413  3744  3906 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 14:32:25.413  3744  3906 E KeepSync: 	... 10 more
08-24 14:32:25.413  3744  3906 W KeepSync: Sync result 2
,08-24 14:32:25.416   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 162578, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 14:32:31.686  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 14:32:31.686  3857  3904 I jxcore-log: 
,08-24 14:32:33.432  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 14:32:33.432  3857  3904 I jxcore-log: 
,08-24 14:32:33.462  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 14:32:33.462  3857  3904 I jxcore-log: 
,08-24 14:32:33.479  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 14:32:33.479  3857  3904 I jxcore-log: 
,08-24 14:32:33.503  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 14:32:33.503  3857  3904 I jxcore-log: 
,08-24 14:32:33.508  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 14:32:33.508  3857  3904 I jxcore-log: 
,08-24 14:32:36.243  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 14:32:36.243  3857  3904 I jxcore-log: 
,08-24 14:32:36.246  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 14:32:36.246  3857  3904 I jxcore-log: 
,08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:36.254  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:32:36.259  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:32:36.261  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 14:32:36.261  3857  3904 I jxcore-log: 
,08-24 14:32:36.263  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 14:32:36.263  3857  3904 I jxcore-log: 
,08-24 14:32:38.892   873  1863 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 14:32:39.816  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 14:32:39.816  3857  3904 I jxcore-log: 
,08-24 14:32:39.827  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 14:32:39.827  3857  3904 I jxcore-log: 
,08-24 14:32:39.835  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 14:32:39.835  3857  3904 I jxcore-log: 
,08-24 14:32:39.992  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 14:32:39.992  3857  3904 I jxcore-log: 
,08-24 14:32:40.766  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 14:32:40.766  3857  3904 I jxcore-log: 
,08-24 14:32:40.826  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 14:32:40.826  3857  3904 I jxcore-log: 
,08-24 14:32:40.834  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 14:32:40.834  3857  3904 I jxcore-log: 
,08-24 14:32:41.030  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 14:32:41.030  3857  3904 I jxcore-log: 
,08-24 14:32:41.053  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 14:32:41.053  3857  3904 I jxcore-log: 
,08-24 14:32:41.058  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 14:32:41.058  3857  3904 I jxcore-log: 
,08-24 14:32:41.064  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 14:32:41.064  3857  3904 I jxcore-log: 
,08-24 14:32:41.083  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 14:32:41.083  3857  3904 I jxcore-log: 
,08-24 14:32:41.103  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 14:32:41.103  3857  3904 I jxcore-log: 
,08-24 14:32:41.190  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 14:32:41.190  3857  3904 I jxcore-log: 
,08-24 14:32:41.196  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 14:32:41.196  3857  3904 I jxcore-log: 
,08-24 14:32:41.203  3857  3904 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 14:32:41.203  3857  3904 I jxcore-log: 
,08-24 14:32:41.219  3857  3904 D ExecuteNativeTests: Running unit tests
,08-24 14:32:41.273  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:32:41.273  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 added. We now have 2 listener(s)
,08-24 14:32:41.274  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:32:41.274  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:32:41.274  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:32:41.274  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:41.274  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a added. We now have 2 listener(s)
08-24 14:32:41.274  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:41.275  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:32:41.279  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.294  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:32:41.297  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:32:41.297  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:32:41.300  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 14:32:41.300  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:32:41.300  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 14:32:41.301  3857  3904 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-24 14:32:41.301  3857  3904 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:32:41.301  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 14:32:41.301  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:32:41.301  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 14:32:41.302  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.303  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:32:41.303  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.303  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:32:41.303  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.303  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:32:41.303  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:32:41.303  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 removed from the list
08-24 14:32:41.303  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:32:41.303  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a removed from the list
,08-24 14:32:41.303  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.304  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.304  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:32:41.305  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.305  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:32:41.307  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:32:41.307  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:32:41.307  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.307  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
,08-24 14:32:41.309  3857  3904 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 14:32:41.309  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:32:41.309  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.309  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.309  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:32:41.310  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.310  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:32:41.310  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
,08-24 14:32:41.310  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.310  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
,08-24 14:32:41.310  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.311  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.311  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.311  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.311  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.311  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.312  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.312  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.312  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.312  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-24 14:32:41.316  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:32:41.317  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:32:41.318  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:32:41.318  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.318  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.318  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:32:41.318  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.318  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.318  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.318  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.318  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.319  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.319  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.319  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.319  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.319  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.319  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.320  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.320  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.320  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.320  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.321  3857  3904 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:32:41.323  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.327  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:32:41.329  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.329  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:32:41.330  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:32:41.331  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 14:32:41.331  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:41.331  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 14:32:41.331  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.331  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:32:41.332  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.337  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:32:41.337  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:32:41.343  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:32:41.345  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:32:41.345  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:32:41.347  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-24 14:32:41.348  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-24 14:32:41.348  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:32:41.349  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 14:32:41.349  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:32:41.350  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:32:41.353  2623  2635 D BtGatt.GattService: registerClient() - UUID=534bf0c2-3057-4329-9543-d6daf8ed9f6c
,08-24 14:32:41.354  2623  2651 D BtGatt.GattService: onClientRegistered() - UUID=534bf0c2-3057-4329-9543-d6daf8ed9f6c, clientIf=5
08-24 14:32:41.355  3857  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 14:32:41.356  2623  2719 D BtGatt.GattService: start scan with filters
,08-24 14:32:41.358  2623  2659 D BtGatt.ScanManager: handling starting scan
,08-24 14:32:41.358  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:32:41.359  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:32:41.359  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 14:32:41.359  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:32:41.362  2623  2659 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:41.363  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:32:41.363  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:32:41.363  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:32:41.364  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:32:41.366  3857  3904 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 14:32:41.368  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.368  3857  3904 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 14:32:41.368  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.368  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:32:41.368  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.368  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:32:41.368  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:32:41.368  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:32:41.368  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:32:41.368  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:32:41.369  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 14:32:41.369  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:32:41.370  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:32:41.371  2623  2635 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:32:41.371  2623  2719 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:32:41.371  2623  2651 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:32:41.371  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:32:41.371  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:32:41.371  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:32:41.372  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:32:41.372  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:32:41.372  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:32:41.372  2623  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:32:41.376  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:32:41.376  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:32:41.376  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:32:41.377  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:32:41.378  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:32:41.379  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:32:41.379  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:32:41.380  2623  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:32:41.380  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 14:32:41.380  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.380  2623  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:32:41.380  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.380  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.380  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.380  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:32:41.380  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.380  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:32:41.380  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.380  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.380  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:32:41.381  3857  3904 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:32:41.385  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.391  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:32:41.393  2623  2651 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:32:41.394  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:32:41.395  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.395  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:32:41.395  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:32:41.396  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 14:32:41.396  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 14:32:41.396  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:32:41.396  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:32:41.397  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.401  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.402  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:32:41.402  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.403  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:32:41.403  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:32:41.408  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:32:41.408  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:32:41.409  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:32:41.411  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 14:32:41.411  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.411  2623  2659 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:32:41.413  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:32:41.413  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:32:41.413  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:32:41.414  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:32:41.418  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 14:32:41.418  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:32:41.418  2623  2635 D BtGatt.GattService: registerClient() - UUID=23961689-9f15-4ca0-ae56-81bd8cf9d7b5
,08-24 14:32:41.418  2623  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:32:41.419  2623  2651 D BtGatt.GattService: onClientRegistered() - UUID=23961689-9f15-4ca0-ae56-81bd8cf9d7b5, clientIf=5
,08-24 14:32:41.420  3857  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:32:41.420  2623  2634 D BtGatt.GattService: start scan with filters
,08-24 14:32:41.423  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:32:41.423  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-24 14:32:41.423  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:32:41.423  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:32:41.425  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:32:41.425  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:32:41.425  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:32:41.426  2623  2651 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:32:41.426  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:32:41.426  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:32:41.428  2623  2659 D BtGatt.ScanManager: handling starting scan
,08-24 14:32:41.429  3857  3904 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 14:32:41.431  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.431  3857  3904 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:32:41.431  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.431  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:32:41.431  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.431  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:32:41.431  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:32:41.431  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:32:41.431  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:32:41.431  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:32:41.431  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:32:41.431  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:32:41.433  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:32:41.434  2623  3471 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:32:41.434  2623  2719 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:32:41.434  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:32:41.434  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:32:41.434  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:32:41.435  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:32:41.434  2623  2651 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:32:41.435  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:32:41.435  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.435  2623  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:32:41.435  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.435  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:32:41.435  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:32:41.435  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:32:41.436  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:32:41.440  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.440  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.440  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.441  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.441  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.441  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:32:41.441  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.441  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.441  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.442  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.442  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:32:41.442  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.442  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.442  2623  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:32:41.442  2623  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:32:41.446  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.446  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.449  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.449  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.449  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.449  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.451  3857  3904 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:32:41.454  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.458  2623  2651 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:32:41.459  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.462  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:32:41.464  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.465  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:32:41.465  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:32:41.465  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.465  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:32:41.465  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:32:41.466  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:32:41.466  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.466  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:32:41.468  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:41.470  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.471  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:32:41.471  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:32:41.474  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:32:41.474  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:32:41.474  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:32:41.476  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:32:41.476  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:32:41.476  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:32:41.476  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:32:41.477  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:32:41.477  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.477  2623  2659 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:32:41.483  2623  2635 D BtGatt.GattService: registerClient() - UUID=d73a5da0-adab-4232-9503-900d1b429329
08-24 14:32:41.484  2623  2651 D BtGatt.GattService: onClientRegistered() - UUID=d73a5da0-adab-4232-9503-900d1b429329, clientIf=5
08-24 14:32:41.485  3857  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:32:41.485  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:32:41.485  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.485  2623  3471 D BtGatt.GattService: start scan with filters
08-24 14:32:41.485  2623  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:32:41.490  2623  2651 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:32:41.490  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.492  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:32:41.492  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:32:41.492  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:32:41.492  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 14:32:41.494  2623  2659 D BtGatt.ScanManager: handling starting scan
08-24 14:32:41.497  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:32:41.497  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:32:41.497  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:32:41.500  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 14:32:41.501  2623  2651 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:32:41.501  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.501  2623  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:32:41.505  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:32:41.506  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.506  2623  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:32:41.506  2623  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:32:41.509  3857  3904 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:32:41.509  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.509  3857  3904 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:32:41.510  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.510  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:32:41.510  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.510  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:32:41.510  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:32:41.510  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:32:41.510  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 14:32:41.510  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:32:41.514  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:32:41.514  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:32:41.514  2623  2651 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:32:41.515  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.515  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:32:41.516  2623  2635 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:32:41.516  2623  3471 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:32:41.516  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:32:41.516  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:32:41.517  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:32:41.517  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:32:41.517  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:32:41.518  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.519  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:32:41.519  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:32:41.519  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:32:41.519  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:32:41.519  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.520  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:32:41.520  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.521  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.521  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.522  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.522  3857  3904 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:32:41.522  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.522  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.522  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.522  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.522  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:32:41.522  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.523  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.523  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.523  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.523  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.523  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.523  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.524  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.524  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.524  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.524  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.524  3857  3904 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 14:32:41.525  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.525  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.525  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.525  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.525  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.525  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.525  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.525  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.525  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.525  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.525  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.525  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.525  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.525  2623  2651 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:32:41.525  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.525  2623  2659 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:32:41.525  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.526  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.526  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.526  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.526  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.527  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:32:41.527  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.527  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.527  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.527  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.527  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.527  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.527  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.528  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.528  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.528  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.528  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.528  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.528  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.528  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.529  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.529  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.529  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.529  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.530  3857  3904 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 14:32:41.530  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.530  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.530  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.530  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.530  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.530  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.531  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.531  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.531  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.531  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.531  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.531  2623  2651 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:32:41.531  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.531  2623  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:32:41.531  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.532  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.532  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.533  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.533  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.533  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.533  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.533  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 14:32:41.534  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.534  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.534  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.534  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.534  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.534  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.534  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.534  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.534  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.534  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.534  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.534  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.534  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.535  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.536  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.536  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.536  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.536  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.536  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:32:41.537  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:32:41.537  2623  2651 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:32:41.537  2623  2651 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:32:41.537  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:32:41.537  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:32:41.537  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:32:41.537  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:32:41.537  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.537  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.537  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.537  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.537  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.538  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.538  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.538  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.538  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.538  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.538  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.538  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.538  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.538  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.540  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.540  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.540  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.540  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.541  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:32:41.541  3857  3904 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:32:41.541  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:32:41.544  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:32:41.544  3857  3904 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:32:41.545  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:32:41.546  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:32:41.547  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:32:41.547  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 14:32:41.547  3857  3904 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:32:41.547  3857  3904 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 14:32:41.547  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:32:41.547  3857  3904 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:32:41.547  3857  3904 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 14:32:41.547  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:32:41.547  3857  3904 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:32:41.548  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 14:32:41.551  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 14:32:41.552  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 14:32:41.552  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 14:32:41.552  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 14:32:41.552  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 14:32:41.552  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 14:32:41.552  3857  3904 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:32:41.553  3857  3904 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 14:32:41.553  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.553  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.553  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.553  3857  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-24 14:32:41.553  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.553  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.553  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.554  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 14:32:41.554  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.554  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.554  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.554  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.554  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.554  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.554  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.554  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.555  3857  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-24 14:32:41.555  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.555  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.555  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.555  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.556  3857  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:32:41.556  3857  3904 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 14:32:41.556  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.556  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.556  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.557  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.557  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.557  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.557  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.557  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.557  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.557  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.557  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.557  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.557  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.557  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.558  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.558  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.558  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.558  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.558  3857  3904 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 14:32:41.558  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.558  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.558  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.559  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.559  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.559  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.559  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.559  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.559  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.559  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.559  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.559  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.559  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.559  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.560  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.560  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.560  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.560  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 14:32:41.561  3857  3904 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:32:41.561  3857  3904 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:32:41.561  3857  3904 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:32:41.561  3857  3904 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:32:41.561  3857  3904 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:32:41.561  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:32:41.561  3857  3904 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 14:32:41.562  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.562  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.562  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.562  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.562  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.562  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.562  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.562  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.562  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.562  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.562  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.562  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.562  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:32:41.562  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.563  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.563  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.563  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.563  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.563  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.563  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.563  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.563  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.563  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.564  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.564  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.564  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.564  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.564  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.564  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.564  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.564  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.564  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.564  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.564  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.564  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.564  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.564  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.564  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.564  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.564  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.565  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.565  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.565  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.565  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.565  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.565  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.565  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.565  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.565  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.565  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.565  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.566  3857  3904 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 14:32:41.566  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.567  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 14:32:41.567  3857  3904 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 14:32:41.568  3857  3904 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 14:32:41.568  3857  3857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 14:32:41.568  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 14:32:41.568  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:32:41.568  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.568  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 14:32:41.568  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 14:32:41.568  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 14:32:41.568  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.568  3857  3904 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 14:32:41.569  3857  3857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 14:32:41.569  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.569  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.569  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:32:41.569  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:32:41.569  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:32:41.569  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.569  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.569  3857  3911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:32:41.570  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.570  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.570  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:32:41.570  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:32:41.570  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.570  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.570  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.570  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.570  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.570  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.570  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.571  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.571  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.571  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.571  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.571  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.571  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.571  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.571  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.571  3857  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 14:32:41.571  3857  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 14:32:41.571  3857  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 14:32:41.572  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.572  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.572  3857  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 14:32:41.572  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.572  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.573  3857  3904 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 14:32:41.573  3857  3904 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:32:41.573  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:32:41.575  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:32:41.575  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.575  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.575  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.575  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.575  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.575  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.575  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.575  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.575  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.576  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.576  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.576  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.576  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.576  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.577  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.577  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.577  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.577  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.579  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.579  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.580  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.580  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.580  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.580  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.580  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.580  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.580  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.580  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.580  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.580  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.580  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.580  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.581  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.581  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.581  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.581  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.582  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:32:41.582  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:32:41.582  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:32:41.582  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:32:41.582  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.582  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.582  3857  3904 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ffe705 not in the list
08-24 14:32:41.582  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.582  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.582  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:41.582  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.582  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.582  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:32:41.582  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:32:41.583  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:32:41.583  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:32:41.583  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:32:41.583  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37135a not in the list
08-24 14:32:41.584  3857  3904 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 14:32:41.584  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:32:41.584  3857  3904 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 14:32:41.584  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:32:41.584  3857  3904 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 14:32:41.584  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:32:41.585  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:32:41.585  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 14:32:41.586  3857  3904 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 14:32:41.586  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:32:41.586  3857  3904 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 14:32:41.586  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:32:41.586  3857  3904 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 14:32:41.586  3857  3904 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 14:32:41.586  3857  3904 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 14:32:41.587  3857  3904 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 14:32:41.587  3857  3904 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 14:32:41.587  3857  3904 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 14:32:41.587  3857  3904 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 14:32:41.587  3857  3904 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 14:32:41.588  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:41.588  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7b62ac added. We now have 2 listener(s)
08-24 14:32:41.588  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:41.590  3857  3904 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 14:32:41.590   873  2062 D WifiService: setWifiEnabled: true pid=3857, uid=10000
08-24 14:32:41.590   873  2062 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:32:41.590  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:41.591  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba19b75 added. We now have 3 listener(s)
08-24 14:32:41.591  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:41.597  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:41.597  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ab070a added. We now have 4 listener(s)
08-24 14:32:41.597  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:41.599  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:41.599  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab33b7b added. We now have 5 listener(s)
08-24 14:32:41.599  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:32:41.602   873  1987 D WifiService: setWifiEnabled: false pid=3857, uid=10000
08-24 14:32:41.602   873  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:32:41.606  2623  2646 D BluetoothAdapterState: Current state: ON, message: 23
08-24 14:32:41.606  2623  2646 D BluetoothAdapterProperties: Setting state to 13
08-24 14:32:41.606  2623  2646 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:32:41.606  2623  2646 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:32:41.607  2623  2646 I BluetoothAdapterState: Entering PendingCommandState
08-24 14:32:41.608  2623  2651 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:32:41.608  2623  2646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-24 14:32:41.609  2623  2623 D HeadsetService: Received stop request...Stopping profile...
08-24 14:32:41.611  1349  1361 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:41.612  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-24 14:32:41.612  1929  1943 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:41.613  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.613   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:41.613   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:41.613  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.613  2623  2623 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:41.613   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:41.613  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.614  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.614  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:32:41.615  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.615  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:32:41.618  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 14:32:41.622  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.622   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 14:32:41.622   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 14:32:41.622   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:32:41.622   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:32:41.628   873  1305 E native  : do suspend true
,08-24 14:32:41.630   873   886 I ActivityManager: Start proc 3914:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-24 14:32:41.632  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:32:41.635  2623  2623 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 14:32:41.635  2623  2623 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:32:41.635  2623  2623 D BluetoothMapService: onReceive
08-24 14:32:41.635  2623  2623 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:32:41.635  2623  2623 D BluetoothMapService: STATE_TURNING_OFF
,08-24 14:32:41.635  2623  2651 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 14:32:41.635  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:32:41.635  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:32:41.636  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:41.636  2623  2651 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 14:32:41.636  2623  2623 D A2dpService: Received stop request...Stopping profile...
08-24 14:32:41.637  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:41.637  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:32:41.637  2623  2722 D A2dpStateMachine: Exit Disconnected: -1
08-24 14:32:41.637  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.637  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:41.638  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:32:41.640   873   873 D BluetoothA2dp: Proxy object disconnected
,08-24 14:32:41.642  2623  2623 D HidService: Received stop request...Stopping profile...
,08-24 14:32:41.642  2623  2623 D HidService: Stopping Bluetooth HidService
08-24 14:32:41.642   873  1877 D DhcpClient: Clearing IP address
08-24 14:32:41.643  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:41.643   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:32:41.643  2623  2623 D BluetoothMapService: MAP Service closeService in
,08-24 14:32:41.644  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-24 14:32:41.644  1349  1349 D BluetoothInputDevice: Proxy object disconnected
,08-24 14:32:41.644  1349  1349 D HidProfile: Bluetooth service disconnected
08-24 14:32:41.644  2623  2623 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 14:32:41.645  2623  2623 D ObexServerSockets0: shutdown(block = true)
08-24 14:32:41.645  2623  2729 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 14:32:41.645  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.645  2623  2623 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:32:41.645  2623  2730 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 14:32:41.646  2623  2715 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-24 14:32:41.646  2623  2623 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:32:41.646  2623  2623 I BtOppRfcommListener: stopping Accept Thread
,08-24 14:32:41.646  2623  3408 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:32:41.647  2623  3408 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 14:32:41.647   372   871 D CommandListener: Setting iface cfg
,08-24 14:32:41.648  2623  2623 D HealthService: Received stop request...Stopping profile...
08-24 14:32:41.649  2623  2623 D PanService: Received stop request...Stopping profile...
08-24 14:32:41.649  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 14:32:41.649  1349  1349 D PanProfile: Bluetooth service disconnected
08-24 14:32:41.650  2623  2623 D BluetoothMapService: Received stop request...Stopping profile...
08-24 14:32:41.650  2623  2623 D BluetoothMapService: stop()
,08-24 14:32:41.650  2623  2623 D BluetoothMapAppObserver: deinitObservers()
,08-24 14:32:41.650  2623  2623 D BluetoothMapAppObserver: removeReceiver()
08-24 14:32:41.651   873  1880 D DhcpClient: Receive thread stopped
08-24 14:32:41.652  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.652  2623  2623 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:41.652  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.652  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:41.652  1349  1349 D BluetoothMap: Proxy object disconnected
08-24 14:32:41.652  1349  1349 D MapProfile: Bluetooth service disconnected
,08-24 14:32:41.653  2623  2651 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 14:32:41.653  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:41.653  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.653  2623  2623 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:41.653  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:41.653  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.653  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:41.653  2623  2711 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:32:41.653  2623  2711 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:32:41.653  2623  2711 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:32:41.653  2623  2623 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:32:41.653  2623  2711 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 14:32:41.654  2623  2623 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:32:41.654  2623  2651 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 14:32:41.654   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-24 14:32:41.655  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.655  2623  2623 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:41.655  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.655  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:32:41.655   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:32:41.655  2623  2623 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:32:41.655   873  1305 E native  : do suspend true
08-24 14:32:41.655  2623  2651 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 14:32:41.656  2623  2623 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:32:41.656  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.656  2623  2623 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:41.657  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.657  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:41.657   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 14:32:41.657   401   401 E Parcel  : Reading a NULL string not supported here.
08-24 14:32:41.657   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-24 14:32:41.662   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 14:32:41.662  2623  2623 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:32:41.662  1505  2468 V NativeCrypto: Read error: ssl=0x9b1b6e00: I/O error during system call, Connection timed out
,08-24 14:32:41.663  2623  2623 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 14:32:41.669  2623  2623 D BluetoothMapService: MAP Service closeService in
08-24 14:32:41.669  2623  2623 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:41.669  2623  2623 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:41.669  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:41.669  2623  2623 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:41.669  2623  2646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 14:32:41.669  2623  2646 D BluetoothAdapterProperties: Setting state to 15
,08-24 14:32:41.669  2623  2646 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 14:32:41.669  2623  2623 D BluetoothMapService: cleanup()
08-24 14:32:41.669  2623  2623 D BluetoothMapService: MAP Service closeService in
08-24 14:32:41.669  2623  2646 I BluetoothAdapterState: Entering BleOnState
08-24 14:32:41.669   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:41.670   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:32:41.670  1349  1362 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:32:41.670  1929  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:41.671  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 14:32:41.671   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:32:41.672  1349  2056 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:32:41.672  1349  1362 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:41.672  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
08-24 14:32:41.673   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:41.673  1349  2056 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 14:32:41.673  2623  2646 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-24 14:32:41.673  2623  2646 D BluetoothAdapterProperties: Setting state to 16
08-24 14:32:41.673  2623  2646 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 14:32:41.675  2623  2646 D BluetoothAdapterProperties: onBleDisable
08-24 14:32:41.675  2623  2646 I BluetoothAdapterState: Entering PendingCommandState
08-24 14:32:41.675  2623  2647 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 14:32:41.676  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:41.676  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:41.676  3857  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-24 14:32:41.676  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:41.676  2623  2711 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 14:32:41.676  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:41.676  2623  2711 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:32:41.677  2623  2651 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:32:41.678  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:41.678  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:41.678  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.678  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:41.683  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:41.686  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.697   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-24 14:32:41.667  1505  2468 V NativeCrypto: SSL shutdown failed: ssl=0x9b1b6e00: I/O error during system call, Broken pipe
,08-24 14:32:41.713  3914  3914 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-24 14:32:41.721  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:32:41.723   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:32:41.723   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:32:41.724   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 14:32:41.725   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:32:41.726   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:32:41.727   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:32:41.731  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:41.732  3396  3396 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@53e130a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-24 14:32:41.732  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:41.735  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:32:41.742   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aaf6b93:true
,08-24 14:32:41.747   873  2062 I ActivityManager: Start proc 3932:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-24 14:32:41.749   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:32:41.751   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 14:32:41.752  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:41.752  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:41.752  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:41.752  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:41.753  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:41.754  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:41.754  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:41.754  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:32:41.762  2009  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:32:41.771  3914  3914 D LocalBluetoothProfileManager: Adding local MAP profile
,08-24 14:32:41.776  3914  3914 D BluetoothMap: Create BluetoothMap proxy object
,08-24 14:32:41.783  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-24 14:32:41.784   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-24 14:32:41.785  3914  3914 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-24 14:32:41.803  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:32:41.806   873  1688 I ActivityManager: Killing 3223:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-24 14:32:41.878  2623  2651 I bt_hci  : shut_down
,08-24 14:32:41.878  2623  2661 D bt_hwcfg: hw_epilog_process
,08-24 14:32:41.882  2623  2661 I bt_vendor: low_power_mode_cb
,08-24 14:32:41.911  2623  2661 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 14:32:41.911  2623  2661 I bt_vendor: epilog_cb
,08-24 14:32:41.911  2623  2661 I bt_hci  : epilog_finished_callback
,08-24 14:32:41.916  2623  2651 I bt_hci_h4: hal_close
,08-24 14:32:41.917  2623  2651 I bt_userial_vendor: device fd = 51 close
,08-24 14:32:41.946  3932  3932 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:32:41.946  3932  3932 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.946  3932  3932 D StrictMode: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:32:41.946  3932  3932 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.946  3932  3932 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 14:32:41.946  3,932  3932 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.946  3932  3932 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 1,4:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.946  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.947  3932  3932 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.947  3932  3932 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.947  3932  3932 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:32:41.947  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:32:41.951  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:32:41.960  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:32:41.962  3914  3914 D DockEventReceiver: finishStartingService: stopping service
08-24 14:32:41.968   873  2061 I ActivityManager: Killing 3396:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 14:32:42.013   873  2061 I ActivityManager: Start proc 3965:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-24 14:32:42.030  2623  2647 D bt_stack_manager: event_shut_down_stack finished.
08-24 14:32:42.030  2623  2646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-24 14:32:42.032  2623  2646 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 14:32:42.032  2623  2623 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:32:42.033  2623  2623 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:32:42.034  2623  2623 D BtGatt.GattService: stop()
08-24 14:32:42.034  2623  2623 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 14:32:42.038  2623  2623 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:32:42.040  2623  2623 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:42.040  2623  2623 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:42.040  2623  2623 V BluetoothAdapterState: isBleTurningOff()=true
08-24 14:32:42.041  2623  2646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 14:32:42.041  2623  2646 D BluetoothAdapterProperties: Setting state to 10
08-24 14:32:42.041  2623  2646 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-24 14:32:42.045  2623  2646 I BluetoothAdapterState: Entering OffState
,08-24 14:32:42.045   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 14:32:42.071  3857  3857 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:32:42.076  2623  2623 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 14:32:42.076  2623  2623 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-24 14:32:42.076  2623  2647 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 14:32:42.078  2623  2647 D bt_stack_manager: event_clean_up_stack finished.
,08-24 14:32:42.079  2623  2623 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 14:32:42.084  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-24 14:32:42.085  2623  2623 I art     : System.exit called, status: 0
,08-24 14:32:42.085  2623  2623 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 14:32:42.132   873  2062 I ActivityManager: Process com.android.bluetooth (pid 2623) has died
,08-24 14:32:42.307  3965  3984 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-24 14:32:42.307  3965  3984 I Babel_SMS: MmsConfig.loadMmsSettings
,08-24 14:32:42.308  3965  3984 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-24 14:32:42.311  3965  3984 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 14:32:42.395  3965  3984 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-24 14:32:42.395  3965  3984 I Babel_SMS: MmsConfig.loadFromResources
,08-24 14:32:42.397  3965  3984 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-24 14:32:42.398  3965  3984 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-24 14:32:42.482  3965  3965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:32:42.485  3965  3965 I Babel_Crash: startup - clean
,08-24 14:32:42.513  3965  3965 I Babel_telephony: TeleModule.launchCompleted
,08-24 14:32:42.526   873  1382 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 14:32:42.536  3965  3965 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-24 14:32:42.552  3965  3965 W Babel   : BAM#gBA: invalid account id: -1
,08-24 14:32:42.552  3965  3965 W Babel   : BAM#gBA: invalid account id: -1
,08-24 14:32:42.552  3965  3965 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-24 14:32:42.576  3965  3990 I Babel   : deleted: false for 0
,08-24 14:32:42.582   873  2062 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 14:32:42.657  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:32:42.661  1697  1697 D SystemUpdateService: onCreate
,08-24 14:32:42.666  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:32:42.671  1697  3992 I SystemUpdateService: active receiver: enabled
,08-24 14:32:42.675  1697  3992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:32:42.681  1697  3992 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 14:32:42.681  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-24 14:32:42.683  1697  3992 I SystemUpdateService: now status is 0 (complete)
08-24 14:32:42.683  1697  3992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 14:32:42.683  1697  3992 I SystemUpdateService: file has been verified
08-24 14:32:42.684  1697  3992 I SystemUpdateService: OTA package size = 12249756
,08-24 14:32:42.686  1697  2444 I iu.UploadsManager: num queued entries: 0
08-24 14:32:42.686  1697  2444 I iu.UploadsManager: num updated entries: 0
,08-24 14:32:42.689  1697  2444 I iu.SyncManager: NEXT; no task
,08-24 14:32:42.692  1697  3992 I SystemUpdateService: showing system update notification
,08-24 14:32:42.703  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:32:42.704  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:32:42.713  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:32:42.731   873  2061 I ActivityManager: Start proc 3994:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
08-24 14:32:42.734  1697  1697 D SystemUpdateService: onDestroy
,08-24 14:32:42.767  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 14:32:42.773  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:32:42.795  3994  3994 D SprintDMHelper: simOperator: 
,08-24 14:32:42.795  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:32:42.805  3965  3965 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 14:32:42.811  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:32:42.822  3932  3954 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 14:32:42.824  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:32:42.827  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:32:42.832  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:32:42.839   873  1382 I ActivityManager: Start proc 4006:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 14:32:42.842   873  1938 I ActivityManager: Killing 3560:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 14:32:42.856   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14669c7:true
,08-24 14:32:42.901  3965  3965 I vclib   : onServiceConnected
,08-24 14:32:43.002   873  1938 I ActivityManager: Start proc 4021:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 14:32:43.006  3965  4020 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-24 14:32:43.010   873  1688 I ActivityManager: Killing 3445:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 14:32:43.080  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 14:32:43.129  4021  4021 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 14:32:43.129  4021  4021 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:32:43.129  4021  4021 I GAv4    :   adb logcat -s GAv4
,08-24 14:32:43.144  4021  4021 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:32:43.149  4021  4021 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:32:43.178  4021  4038 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:32:43.269  4021  4021 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 14:32:43.303  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 14:32:43.310  4021  4021 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9692-9695)
,08-24 14:32:43.310  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 14:32:43.323  4021  4021 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60952ba}
,08-24 14:32:43.323  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 14:32:43.323  4021  4021 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:32:43.330  4021  4021 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-24 14:32:43.332  4021  4021 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 14:32:43.344  4021  4021 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 14:32:43.354  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:32:43.354  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:32:43.354  4021  4021 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:32:43.354  4021  4021 I Adreno  : Build Date                       : 10/20/15
08-24 14:32:43.354  4021  4021 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:32:43.354  4021  4021 I Adreno  : Local Branch                     : M14
08-24 14:32:43.354  4021  4021 I Adreno  : Remote Branch                    : 
08-24 14:32:43.354  4021  4021 I Adreno  : Remote Branch                    : 
08-24 14:32:43.354  4021  4021 I Adreno  : Reconstruct Branch               : 
,08-24 14:32:43.400  4021  4067 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 14:32:43.413  4021  4021 I NSApplication: Starting up...
,08-24 14:32:43.457   873   883 I ActivityManager: Start proc 4072:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 14:32:43.458   873   883 I ActivityManager: Killing 3482:android.process.acore/u0a5 (adj 15): empty #17
,08-24 14:32:43.546  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 14:32:43.696   873  2062 I ActivityManager: Killing 3647:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 14:32:43.785   873  1688 I ActivityManager: Start proc 4086:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-24 14:32:43.890  4086  4086 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-24 14:32:43.942  4086  4086 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 14:32:44.020   873  1938 I ActivityManager: Killing 3662:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 14:32:44.640   873  1987 D WifiService: setWifiEnabled: true pid=3857, uid=10000
,08-24 14:32:44.640   873  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:32:44.653   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-24 14:32:44.664  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:44.664  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:44.664  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:44.665  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:32:44.667  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:44.667  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:44.668  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:44.668  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:32:44.675   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-24 14:32:44.676   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 14:32:44.678   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 14:32:44.679   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 14:32:44.679   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 14:32:44.680   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 14:32:44.680   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 14:32:44.700   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 14:32:44.700   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 14:32:44.704   372   871 D CommandListener: Setting iface cfg
,08-24 14:32:44.709   873  1305 E native  : do suspend true
08-24 14:32:44.709   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-24 14:32:44.711   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 14:32:44.722   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:32:44.741   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 14:32:44.745   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 14:32:46.099   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:32:46.173   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.62 rxSuccessRate=8.31 delta 1000 -> 994
,08-24 14:32:46.175   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 14:32:46.175   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:32:46.192   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 14:32:46.248   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 14:32:46.250  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 14:32:46.676  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 14:32:46.720  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 14:32:46.720  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 14:32:46.724   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:32:46.735   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:32:46.735   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:32:46.735   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 14:32:46.754   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:32:46.767   372   871 D CommandListener: Setting iface cfg
,08-24 14:32:46.768   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 14:32:46.776   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 14:32:46.805   873  4119 D DhcpClient: Receive thread started
,08-24 14:32:46.889   873  1305 E native  : do suspend false
,08-24 14:32:46.911   873  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 14:32:46.923   873  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172609, domain null
,08-24 14:32:46.923   873  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172609 seconds
,08-24 14:32:46.927   873  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 14:32:46.939   873  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 14:32:46.940   873  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 14:32:46.945   372   871 D CommandListener: Setting iface cfg
,08-24 14:32:46.951   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 14:32:46.954   873  1305 E native  : do suspend true
,08-24 14:32:46.955   873  1877 D DhcpClient: Scheduling renewal in 86399s
,08-24 14:32:46.971   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 14:32:46.972   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 14:32:46.973   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 14:32:46.983   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:32:46.985   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 14:32:47.061   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 14:32:47.061   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 14:32:47.063   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-24 14:32:47.064   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-24 14:32:47.065   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 14:32:47.072   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 14:32:47.079   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 14:32:47.079   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-24 14:32:47.079   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-24 14:32:47.079   873  1308 D ConnectivityService:    accepting network in place of null
08-24 14:32:47.079   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 14:32:47.080   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:32:47.080   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 14:32:47.095   873  4118 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213479, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 14:32:47.127   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:32:47.159   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:32:47.164   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 14:32:47.164   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:32:47.165   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 14:32:47.168   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:32:47.183  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:47.183  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:32:47.183  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:47.184  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:47.185   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
,08-24 14:32:47.187  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:32:47.187  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:32:47.187  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:47.188  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-24 14:32:47.193  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:32:47.196  1697  1697 D SystemUpdateService: onCreate
,08-24 14:32:47.198  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:32:47.201  1697  4129 I SystemUpdateService: active receiver: enabled
,08-24 14:32:47.205  1697  4129 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:32:47.207  1697  4129 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 14:32:47.207  1697  4129 I SystemUpdateService: now status is 0 (complete)
08-24 14:32:47.207  1697  4129 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip,
08-24 14:32:47.207  1697  4129 I SystemUpdateService: file has been verified
08-24 14:32:47.207  1697  4129 I SystemUpdateService: OTA package size = 12249756
,08-24 14:32:47.214  1697  4129 I SystemUpdateService: showing system update notification
,08-24 14:32:47.217  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 14:32:47.218  1697  2444 I iu.UploadsManager: num queued entries: 0
08-24 14:32:47.218  1697  2444 I iu.UploadsManager: num updated entries: 0
,08-24 14:32:47.220  1697  2444 I iu.SyncManager: NEXT; no task
,08-24 14:32:47.223  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:32:47.224  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:32:47.225  1697  4133 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 14:32:47.226  1697  4133 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:32:47.227  1697  4133 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-24 14:32:47.227  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:32:47.232  3994  3994 D SprintDMHelper: simOperator: 
,08-24 14:32:47.231  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:32:47.232  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:32:47.233  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:32:47.235  1697  1697 D SystemUpdateService: onDestroy
,08-24 14:32:47.270  1505  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 14:32:47.270   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:32:47 GMT], X-Android-Received-Millis=[1472041967269], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472041967239]}
08-24 14:32:47.270  1505  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 14:32:47.270  1505  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:32:47.270  1505  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:32:47.270   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 14:32:47.270   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 14:32:47.270   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 14:32:47.272   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 14:32:47.293  1697  4133 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-24 14:32:47.366  3965  4136 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 14:32:47.647   873  1987 D WifiService: setWifiEnabled: false pid=3857, uid=10000
,08-24 14:32:47.648   873  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:32:47.676  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 14:32:47.681   873  1382 I ActivityManager: Killing 2219:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
08-24 14:32:47.681   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 14:32:47.683   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 14:32:47.683   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:32:47.684   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:32:47.703   873  1305 E native  : do suspend true
,08-24 14:32:47.712   873  1877 D DhcpClient: Clearing IP address
,08-24 14:32:47.712   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:32:47.714   372   871 D CommandListener: Setting iface cfg
,08-24 14:32:47.718   873  4119 D DhcpClient: Receive thread stopped
,08-24 14:32:47.719  1505  4141 V NativeCrypto: Read error: ssl=0x9b1b6e00: I/O error during system call, Connection timed out
,08-24 14:32:47.721  1505  4141 V NativeCrypto: SSL shutdown failed: ssl=0x9b1b6e00: I/O error during system call, Broken pipe
,08-24 14:32:47.726   873   884 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-24 14:32:47.726   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-24 14:32:47.727   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
,08-24 14:32:47.733   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-24 14:32:47.735   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-24 14:32:47.735   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 14:32:47.737   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 14:32:47.744   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-24 14:32:47.745   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 14:32:47.745   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-24 14:32:47.746   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:32:47.746   873  1305 E native  : do suspend true
,08-24 14:32:47.758   401   401 E Parcel  : Reading a NULL string not supported here.
,08-24 14:32:47.759   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:32:47.766   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-24 14:32:47.767   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:32:47.782   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:32:47.784  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:47.784  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:47.784  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:32:47.784  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:47.785  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:47.785  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:47.785  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:47.785  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:32:47.789   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 14:32:47.791  2009  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:32:47.802   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:32:47.828   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:32:47.829   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 14:32:47.829   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:32:47.833   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:32:47.834  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:47.835  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:47.844  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:32:47.848  1697  1697 D SystemUpdateService: onCreate
,08-24 14:32:47.851  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:32:47.864  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 14:32:47.866  1697  4152 I SystemUpdateService: active receiver: enabled
,08-24 14:32:47.867  1697  2444 I iu.UploadsManager: num queued entries: 0
08-24 14:32:47.867  1697  2444 I iu.UploadsManager: num updated entries: 0
,08-24 14:32:47.870  1697  4152 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:32:47.875  1697  2444 I iu.SyncManager: NEXT; no task
,08-24 14:32:47.875  1697  4152 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 14:32:47.875  1697  4152 I SystemUpdateService: now status is 0 (complete)
,08-24 14:32:47.875  1697  4152 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 14:32:47.875  1697  4152 I SystemUpdateService: file has been verified
,08-24 14:32:47.876  1697  4152 I SystemUpdateService: OTA package size = 12249756
,08-24 14:32:47.878  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:32:47.879  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:32:47.882  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-24 14:32:47.886  3994  3994 D SprintDMHelper: simOperator: ,
08-24 14:32:47.886  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:32:47.906   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-24 14:32:47.909   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 14:32:47.921  3965  4157 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 14:32:47.924  1697  4152 I SystemUpdateService: showing system update notification
,08-24 14:32:47.930  1697  1697 D SystemUpdateService: onDestroy
,08-24 14:32:48.165   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 14:32:50.703   873   890 I ActivityManager: Start proc 4160:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 14:32:50.842  4160  4160 D AdapterServiceConfig: Adding HeadsetService
,08-24 14:32:50.843  4160  4160 D AdapterServiceConfig: Adding A2dpService
08-24 14:32:50.843  4160  4160 D AdapterServiceConfig: Adding HidService
08-24 14:32:50.844  4160  4160 D AdapterServiceConfig: Adding HealthService
08-24 14:32:50.847  4160  4160 D AdapterServiceConfig: Adding PanService
08-24 14:32:50.848  4160  4160 D AdapterServiceConfig: Adding GattService
08-24 14:32:50.849  4160  4160 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 14:32:50.865  4160  4160 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 14:32:50.865   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40b2a68:true
,08-24 14:32:50.870  4160  4160 I bt_bluedroid: init
,08-24 14:32:50.871  4160  4172 I BluetoothAdapterState: Entering OffState
,08-24 14:32:50.876  4160  4173 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 14:32:50.877  4160  4173 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 14:32:50.877  4160  4173 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 14:32:50.877  4160  4173 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 14:32:50.879  4160  4160 I bt_bluedroid: get_profile_interface socket
,08-24 14:32:50.883  4160  4160 I bt_bluedroid: get_profile_interface sdp
,08-24 14:32:50.885  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:32:50.889  4160  4170 I bt_bluedroid: config_hci_snoop_log
08-24 14:32:50.889  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:32:50.891   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 14:32:50.899  4160  4172 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 14:32:50.899  4160  4172 D BluetoothAdapterProperties: Setting state to 14
,08-24 14:32:50.900  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 14:32:50.904  4160  4172 D BluetoothBondStateMachine: make
,08-24 14:32:50.909  4160  4177 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 14:32:50.918  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:32:50.921  4160  4160 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 14:32:50.930  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:50.932  4160  4160 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:32:50.934  4160  4160 D BtGatt.GattService: Received start request. Starting profile...
,08-24 14:32:50.934  4160  4160 D BtGatt.GattService: start()
,08-24 14:32:50.934  4160  4160 I bt_bluedroid: get_profile_interface gatt
,08-24 14:32:50.937  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:32:50.937  4160  4160 D BtGatt.AdvertiseManager: advertise manager created
,08-24 14:32:50.952  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:32:50.953  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:50.953  4160  4160 V BluetoothAdapterState: isBleTurningOn()=true
08-24 14:32:50.953  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:32:50.954  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 14:32:50.955  4160  4172 I bt_bluedroid: enable
,08-24 14:32:50.956  4160  4173 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 14:32:50.957  4160  4173 I bt_hci  : start_up
,08-24 14:32:50.980  4160  4173 I bt_vendor: alloc value 0xb39e5189
,08-24 14:32:50.980  4160  4173 I bt_vendor: init
08-24 14:32:50.980  4160  4173 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 14:32:50.980  4160  4173 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 14:32:51.090  4160  4173 D bt_hci  : start_up starting async portion
,08-24 14:32:51.091  4160  4180 I bt_hci  : event_finish_startup
,08-24 14:32:51.091  4160  4180 I bt_hci_h4: hal_open
08-24 14:32:51.091  4160  4180 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 14:32:51.108  4160  4180 I bt_userial_vendor: device fd = 51 open
,08-24 14:32:51.132  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:32:51.164  4160  4180 D bt_hwcfg: Chipset BCM4354A2
,08-24 14:32:51.164  4160  4180 D bt_hwcfg: Target name = [BCM4354A2]
,08-24 14:32:51.165  4160  4180 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 14:32:51.832  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 14:32:51.833  4160  4180 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 14:32:51.833  4160  4180 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 14:32:51.950  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:32:51.951  4160  4180 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 14:32:51.981  4160  4180 I bt_hwcfg: vendor lib fwcfg completed
,08-24 14:32:51.982  4160  4180 I bt_vendor: firmware callback
08-24 14:32:51.982  4160  4180 I bt_hci  : firmware_config_callback
,08-24 14:32:51.993  4160  4182 I bt_btu  : btu_task pending for preload complete event
,08-24 14:32:51.993  4160  4182 I bt_btu_task: Bluetooth chip preload is complete
,08-24 14:32:51.993  4160  4182 I bt_btu  : btu_task received preload complete event
,08-24 14:32:52.005  4160  4182 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 14:32:52.006  4160  4182 I         : BTE_InitTraceLevels -- TRC_L2CAP,
,08-24 14:32:52.006  4160  4182 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 14:32:52.006  4160  4182 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 14:32:52.006  4160  4182 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 14:32:52.007  4160  4182 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 14:32:52.007  4160  4182 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 14:32:52.008  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 14:32:52.008  4160  4182 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:32:52.008  4160  4182 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:32:52.009  4160  4182 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:32:52.009  4160  4182 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 14:32:52.009  4160  4182 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 14:32:52.010  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:32:52.010  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 14:32:52.142  4160  4182 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-24 14:32:52.142  4160  4182 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-24 14:32:52.152  4160  4176 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 14:32:52.154  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 14:32:52.155  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 14:32:52.158  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:32:52.162  4160  4176 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:32:52.162  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:32:52.162  4160  4176 D bt_hci  : do_postload posting postload work item
,08-24 14:32:52.163  4160  4180 I bt_hci  : event_postload
,08-24 14:32:52.163  4160  4180 I bt_vendor: sco_config_cb
,08-24 14:32:52.163  4160  4180 I bt_hci  : sco_config_callback postload finished.
08-24 14:32:52.164  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.165  4160  4176 D bt_bte_conf: Device ID record 1 : primary
08-24 14:32:52.166  4160  4176 D bt_bte_conf:   vendorId            = 000f
08-24 14:32:52.166  4160  4176 D bt_bte_conf:   vendorIdSource      = 0001
,08-24 14:32:52.166  4160  4176 D bt_bte_conf:   product             = 1200
08-24 14:32:52.166  4160  4176 D bt_bte_conf:   version             = 1436
08-24 14:32:52.166  4160  4176 D bt_bte_conf:   clientExecutableURL = 
08-24 14:32:52.167  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.167  4160  4176 D bt_bte_conf:   serviceDescription  = 
08-24 14:32:52.167  4160  4176 D bt_bte_conf:   documentationURL    = 
,08-24 14:32:52.167  4160  4176 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 14:32:52.168  4160  4173 D bt_stack_manager: event_start_up_stack finished
08-24 14:32:52.169  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-24 14:32:52.170  4160  4172 D BluetoothAdapterProperties: Setting state to 15
08-24 14:32:52.170  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-24 14:32:52.172  4160  4172 I BluetoothAdapterState: Entering BleOnState
08-24 14:32:52.172  4160  4180 I bt_vendor: low_power_mode_cb
08-24 14:32:52.175  4160  4172 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 14:32:52.175  4160  4172 D BluetoothAdapterProperties: Setting state to 11
08-24 14:32:52.176  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 14:32:52.182  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.184  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.184  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:32:52.185  4160  4160 D HeadsetService: Received start request. Starting profile...
,08-24 14:32:52.188  4160  4160 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 14:32:52.188  4160  4160 D HeadsetStateMachine: make
,08-24 14:32:52.197  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:32:52.200  4160  4160 D HeadsetStateMachine: max_hf_connections = 1
,08-24 14:32:52.200  4160  4160 I bt_bluedroid: get_profile_interface handsfree
,08-24 14:32:52.200  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 14:32:52.200  4160  4176 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-24 14:32:52.206  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:52.207  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:32:52.207  4160  4160 D A2dpService: Received start request. Starting profile...
08-24 14:32:52.208  4160  4160 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 14:32:52.208  4160  4160 I bt_bluedroid: get_profile_interface avrcp
,08-24 14:32:52.214  4160  4160 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 14:32:52.214  4160  4160 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:32:52.214  4160  4160 D A2dpStateMachine: make
,08-24 14:32:52.215  4160  4160 I bt_bluedroid: get_profile_interface a2dp
08-24 14:32:52.216  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 14:32:52.217  4160  4191 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:32:52.218  4160  4160 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 14:32:52.219  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:52.220  4160  4160 D HidService: Received start request. Starting profile...
08-24 14:32:52.220  4160  4160 I bt_bluedroid: get_profile_interface hidhost
08-24 14:32:52.220  3914  3914 D BluetoothInputDevice: Proxy object connected
08-24 14:32:52.221  4160  4160 D HidService: setHidService(): set to: null
,08-24 14:32:52.221  4160  4160 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:32:52.221  3914  3914 D HidProfile: Bluetooth service connected
08-24 14:32:52.222  4160  4176 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
08-24 14:32:52.222  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-24 14:32:52.222  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:32:52.222  4160  4160 D HealthService: Received start request. Starting profile...
,08-24 14:32:52.224  4160  4160 I bt_bluedroid: get_profile_interface health
08-24 14:32:52.225  4160  4160 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 14:32:52.225  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:52.226  4160  4160 D PanService: Received start request. Starting profile...
08-24 14:32:52.227  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:32:52.227  4160  4160 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-24 14:32:52.227  4160  4160 I bt_bluedroid: get_profile_interface pan
08-24 14:32:52.227  3914  3914 D PanProfile: Bluetooth service connected
08-24 14:32:52.227  4160  4176 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 14:32:52.230  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:52.231  4160  4160 D BluetoothMapService: Received start request. Starting profile...
08-24 14:32:52.231  4160  4160 D BluetoothMapService: start()
08-24 14:32:52.231  3914  3914 D BluetoothMap: Proxy object connected
,08-24 14:32:52.231  3914  3914 D MapProfile: Bluetooth service connected
08-24 14:32:52.232  3914  3914 D BluetoothMap: getConnectedDevices()
,08-24 14:32:52.232  3914  3914 D BluetoothMap: Bluetooth is Not enabled
08-24 14:32:52.233  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 14:32:52.234  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 14:32:52.234  4160  4160 D BluetoothMapAppObserver: createReceiver()
,08-24 14:32:52.235  4160  4160 D BluetoothMapAppObserver: initObservers()
08-24 14:32:52.235  4160  4160 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 14:32:52.243  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:32:52.243  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.243  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.243  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:32:52.245  4160  4189 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:32:52.247  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.248  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.249  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:52.249  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-24 14:32:52.249  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-24 14:32:52.249  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:52.249  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:32:52.249  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 14:32:52.249  4160  4172 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:32:52.249  4160  4172 D BluetoothAdapterProperties: State =  11
08-24 14:32:52.250  4160  4172 D BluetoothAdapterProperties: Setting state to 12
08-24 14:32:52.250  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:32:52.250   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:32:52.250   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:32:52.251  4160  4172 I BluetoothAdapterState: Entering OnState
,08-24 14:32:52.253  4160  4176 D BluetoothAdapterProperties: Scan Mode:21
,08-24 14:32:52.253  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:32:52.256  3914  3924 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:52.257  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:52.258  3914  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:32:52.259  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:32:52.259  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:52.261  1929  1943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:32:52.262  1349  1362 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:52.263  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:52.263  3914  3924 D BluetoothPan: onBluetoothStateChange on: true
,08-24 14:32:52.264  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 14:32:52.264   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:32:52.264  1349  2056 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:32:52.264  4160  4160 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 14:32:52.266  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:32:52.266  1349  1349 D BluetoothMap: Proxy object connected
08-24 14:32:52.266  1349  1349 D MapProfile: Bluetooth service connected
08-24 14:32:52.266  1349  1349 D BluetoothMap: getConnectedDevices()
08-24 14:32:52.266  1349  1362 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:32:52.267  1349  1361 D BluetoothPan: onBluetoothStateChange on: true
,08-24 14:32:52.267  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:32:52.268  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:32:52.269  4160  4160 D ObexServerSockets: Succeed to create listening sockets 
08-24 14:32:52.269  4160  4160 D ObexServerSockets0: startAccept()
,08-24 14:32:52.269  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:32:52.269   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:32:52.269  4160  4160 D ObexServerSockets0: prepareForNewConnect()
08-24 14:32:52.269  1349  1349 D PanProfile: Bluetooth service connected
,08-24 14:32:52.270  3914  3926 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:32:52.270  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 14:32:52.271  4160  4160 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 14:32:52.271  4160  4160 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 14:32:52.272   873   873 D BluetoothA2dp: Proxy object connected
08-24 14:32:52.272  4160  4197 D ObexServerSockets0: Accepting socket connection...
08-24 14:32:52.273  4160  4198 D ObexServerSockets0: Accepting socket connection...
08-24 14:32:52.273  1349  1349 D BluetoothInputDevice: Proxy object connected
08-24 14:32:52.273  1349  1349 D HidProfile: Bluetooth service connected
08-24 14:32:52.275   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 14:32:52.277  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.278  4160  4160 D BluetoothMapService: onReceive
08-24 14:32:52.278  4160  4160 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:32:52.278  4160  4160 D BluetoothMapService: STATE_ON
08-24 14:32:52.279  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:52.280  1349  1349 D BluetoothA2dp: Proxy object connected
08-24 14:32:52.280  3914  3914 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 14:32:52.283  3914  3914 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-24 14:32:52.291  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:32:52.293  3914  3914 D BluetoothA2dp: Proxy object connected
,08-24 14:32:52.305  1349  1349 D BluetoothPbap: Proxy object connected
,08-24 14:32:52.305  1349  1349 D PbapServerProfile: Bluetooth service connected
08-24 14:32:52.305  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 14:32:52.305  4160  4160 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:32:52.305  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:32:52.307  4160  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:32:52.311  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:32:52.312  3914  3914 D BluetoothPbap: Proxy object connected
,08-24 14:32:52.313  3914  3914 D PbapServerProfile: Bluetooth service connected
,08-24 14:32:52.336  4160  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:32:52.337  4160  4208 I BtOppRfcommListener: Accept thread started.
,08-24 14:32:52.352  1349  1361 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.352  1349  1349 D HeadsetProfile: Bluetooth service connected
08-24 14:32:52.353  1929  2121 D BluetoothHeadset: Proxy object connected
08-24 14:32:52.353   873   873 D BluetoothHeadset: Proxy object connected
08-24 14:32:52.353   873   873 D BluetoothHeadset: Proxy object connected
08-24 14:32:52.353   873   873 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.361  1929  1952 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.367  1349  2056 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.367  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-24 14:32:52.370   873   890 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.386  3914  3926 D BluetoothHeadset: Proxy object connected
,08-24 14:32:52.387  3914  3914 D HeadsetProfile: Bluetooth service connected
,08-24 14:32:53.665  4160  4172 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 14:32:53.666  4160  4172 D BluetoothAdapterProperties: Setting state to 13
,08-24 14:32:53.666  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-24 14:32:53.668  4160  4172 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:32:53.674  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:32:53.682  4160  4160 D BluetoothMapService: onReceive
,08-24 14:32:53.682  4160  4160 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:32:53.682  4160  4160 D BluetoothMapService: STATE_TURNING_OFF
,08-24 14:32:53.683  4160  4160 D BluetoothMapService: MAP Service closeService in
,08-24 14:32:53.683  4160  4160 D BluetoothMapMasInstance0: MAP Service shutdown
,08-24 14:32:53.684  4160  4160 D ObexServerSockets0: shutdown(block = true)
,08-24 14:32:53.685  4160  4160 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 14:32:53.686  4160  4198 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 14:32:53.686  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:53.686  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:32:53.687  4160  4197 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 14:32:53.689  4160  4184 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 14:32:53.689  4160  4160 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:32:53.690  4160  4160 I BtOppRfcommListener: stopping Accept Thread
,08-24 14:32:53.690  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:53.690  4160  4176 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:32:53.691  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:53.691  4160  4208 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:32:53.691  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 14:32:53.692  4160  4208 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 14:32:53.696  4160  4160 D HeadsetService: Received stop request...Stopping profile...
08-24 14:32:53.700  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:32:53.700  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:32:53.701  1349  1361 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:53.701  1929  2121 D BluetoothHeadset: Proxy object disconnected
,08-24 14:32:53.702   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:53.702  3857  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:32:53.702   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:53.702  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:32:53.702  3914  3924 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:53.703   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 14:32:53.704  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:53.704  4160  4160 D A2dpService: Received stop request...Stopping profile...
08-24 14:32:53.705  4160  4191 D A2dpStateMachine: Exit Disconnected: -1
08-24 14:32:53.706  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:53.706  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:32:53.707  1349  1349 D HeadsetProfile: Bluetooth service disconnected
,08-24 14:32:53.710   873   873 D BluetoothA2dp: Proxy object disconnected
,08-24 14:32:53.710  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-24 14:32:53.711  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.711  4160  4160 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:53.711  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:53.711  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.712  4160  4160 D HidService: Received stop request...Stopping profile...
08-24 14:32:53.712  4160  4160 D HidService: Stopping Bluetooth HidService
,08-24 14:32:53.714  3914  3914 D HeadsetProfile: Bluetooth service disconnected
,08-24 14:32:53.714  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-24 14:32:53.714  1349  1349 D HidProfile: Bluetooth service disconnected
08-24 14:32:53.715  4160  4160 D HealthService: Received stop request...Stopping profile...
,08-24 14:32:53.717  4160  4160 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 14:32:53.717  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-24 14:32:53.717  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:32:53.717  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:53.717  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:53.717  4160  4176 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-24 14:32:53.717  4160  4160 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:32:53.718  3914  3914 D DockEventReceiver: finishStartingService: stopping service
08-24 14:32:53.718  4160  4160 D PanService: Received stop request...Stopping profile...
08-24 14:32:53.719  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:32:53.719  1349  1349 D PanProfile: Bluetooth service disconnected
08-24 14:32:53.720  3914  3914 D BluetoothA2dp: Proxy object disconnected
08-24 14:32:53.720  4160  4160 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 14:32:53.720  4160  4160 D BluetoothMapService: stop()
08-24 14:32:53.720  3914  3914 D BluetoothInputDevice: Proxy object disconnected
08-24 14:32:53.720  3914  3914 D HidProfile: Bluetooth service disconnected
,08-24 14:32:53.721  3914  3914 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:32:53.721  3914  3914 D PanProfile: Bluetooth service disconnected
08-24 14:32:53.721  4160  4160 D BluetoothMapAppObserver: deinitObservers(),
08-24 14:32:53.722  4160  4160 D BluetoothMapAppObserver: removeReceiver()
,08-24 14:32:53.723  1349  1349 D BluetoothMap: Proxy object disconnected,
,08-24 14:32:53.723  1349  1349 D MapProfile: Bluetooth service disconnected
,08-24 14:32:53.723  3914  3914 D BluetoothMap: Proxy object disconnected
,08-24 14:32:53.723  3914  3914 D MapProfile: Bluetooth service disconnected
,08-24 14:32:53.723  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.723  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:53.723  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:53.723  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.725  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 14:32:53.725  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:53.725  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:32:53.725  4160  4182 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:32:53.725  4160  4182 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:32:53.725  4160  4182 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:32:53.725  4160  4182 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:32:53.726  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.726  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:53.726  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:53.726  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.728  4160  4160 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-24 14:32:53.728  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 14:32:53.728  4160  4160 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:32:53.729  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.729  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:53.729  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:32:53.729  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.729  4160  4160 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:32:53.729  4160  4176 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 14:32:53.730  4160  4160 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:32:53.730  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.730  4160  4160 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:53.730  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:53.730  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.730  4160  4160 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:32:53.730  4160  4160 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 14:32:53.731  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:32:53.731  4160  4160 D BluetoothMapService: MAP Service closeService in
08-24 14:32:53.731  4160  4160 V BluetoothAdapterState: isTurningOff()=true
08-24 14:32:53.731  4160  4160 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:32:53.732  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:53.732  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:53.732  4160  4160 D BluetoothMapService: cleanup()
08-24 14:32:53.732  4160  4160 D BluetoothMapService: MAP Service closeService in
08-24 14:32:53.732  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-24 14:32:53.732  4160  4172 D BluetoothAdapterProperties: Setting state to 15
08-24 14:32:53.733  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 14:32:53.733  4160  4172 I BluetoothAdapterState: Entering BleOnState
08-24 14:32:53.736  3914  3914 D BluetoothPbap: Proxy object disconnected
,08-24 14:32:53.736  3914  3914 D PbapServerProfile: Bluetooth service disconnected
08-24 14:32:53.736   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.736   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.736  3914  3926 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 14:32:53.737  1349  1349 D BluetoothPbap: Proxy object disconnected
,08-24 14:32:53.737  1349  1349 D PbapServerProfile: Bluetooth service disconnected
08-24 14:32:53.739  3914  3924 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 14:32:53.740  1349  1362 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:32:53.741  1929  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.741  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 14:32:53.743  3914  3926 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.743  3914  3924 D BluetoothPan: onBluetoothStateChange on: false
,08-24 14:32:53.744  3914  4215 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:32:53.744   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:32:53.744  1349  2056 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:32:53.745  1349  1362 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.745  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
,08-24 14:32:53.746   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:32:53.746  3914  3926 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:32:53.746  1349  2056 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 14:32:53.747  4160  4172 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 14:32:53.747  4160  4172 D BluetoothAdapterProperties: Setting state to 16
,08-24 14:32:53.747  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 14:32:53.747  4160  4172 D BluetoothAdapterProperties: onBleDisable
08-24 14:32:53.748  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
08-24 14:32:53.748  4160  4173 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 14:32:53.750  4160  4182 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 14:32:53.750  4160  4182 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:32:53.753  4160  4176 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:32:53.754  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:53.755  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:32:53.755  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:32:53.756  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:53.757  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:53.759  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:32:53.766  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:32:53.951  4160  4176 I bt_hci  : shut_down
,08-24 14:32:53.952  4160  4180 D bt_hwcfg: hw_epilog_process
,08-24 14:32:53.953  4160  4180 I bt_vendor: low_power_mode_cb
,08-24 14:32:53.974  4160  4180 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 14:32:53.975  4160  4180 I bt_vendor: epilog_cb
08-24 14:32:53.975  4160  4180 I bt_hci  : epilog_finished_callback
,08-24 14:32:53.976  4160  4176 I bt_hci_h4: hal_close
,08-24 14:32:53.977  4160  4176 I bt_userial_vendor: device fd = 51 close
,08-24 14:32:54.100  4160  4173 D bt_stack_manager: event_shut_down_stack finished.
08-24 14:32:54.102  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 14:32:54.107  4160  4172 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 14:32:54.108  4160  4160 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:32:54.110  4160  4160 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:32:54.111  4160  4160 D BtGatt.GattService: stop()
,08-24 14:32:54.111  4160  4160 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 14:32:54.120  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:32:54.120  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:54.120  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:32:54.121  4160  4160 V BluetoothAdapterState: isBleTurningOff()=true
,08-24 14:32:54.122  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-24 14:32:54.123  4160  4172 D BluetoothAdapterProperties: Setting state to 10
,08-24 14:32:54.123  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 14:32:54.125  4160  4172 I BluetoothAdapterState: Entering OffState
08-24 14:32:54.126   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 14:32:54.142  4160  4160 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 14:32:54.142  4160  4160 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-24 14:32:54.143  4160  4173 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 14:32:54.143  4160  4160 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 14:32:54.155  4160  4173 D bt_stack_manager: event_clean_up_stack finished.
,08-24 14:32:54.161  4160  4160 I art     : System.exit called, status: 0
,08-24 14:32:54.162  4160  4160 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 14:32:54.229   873  2062 I ActivityManager: Process com.android.bluetooth (pid 4160) has died
,08-24 14:32:55.087   873  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-24 14:32:56.663  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:32:56.663  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:32:59.671  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:32:59.671  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fd79f1 added. We now have 6 listener(s)
08-24 14:32:59.672  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:32:59.676  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:32:59.677  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27a89d6 added. We now have 7 listener(s)
08-24 14:32:59.677  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:32:59.679  3857  3904 I System.out: IsBluetoothEnabled
,08-24 14:32:59.690  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:32:59.736   873   890 I ActivityManager: Start proc 4220:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 14:32:59.880  4220  4220 D AdapterServiceConfig: Adding HeadsetService
,08-24 14:32:59.880  4220  4220 D AdapterServiceConfig: Adding A2dpService
08-24 14:32:59.880  4220  4220 D AdapterServiceConfig: Adding HidService
08-24 14:32:59.880  4220  4220 D AdapterServiceConfig: Adding HealthService
,08-24 14:32:59.880  4220  4220 D AdapterServiceConfig: Adding PanService
08-24 14:32:59.881  4220  4220 D AdapterServiceConfig: Adding GattService
08-24 14:32:59.881  4220  4220 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 14:32:59.898   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f6a0c5:true
,08-24 14:32:59.900  4220  4220 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 14:32:59.910  4220  4220 I bt_bluedroid: init
,08-24 14:32:59.911  4220  4232 I BluetoothAdapterState: Entering OffState
,08-24 14:32:59.917  4220  4233 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 14:32:59.918  4220  4233 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 14:32:59.918  4220  4233 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 14:32:59.918  4220  4233 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 14:32:59.921  4220  4220 I bt_bluedroid: get_profile_interface socket
,08-24 14:32:59.924  4220  4236 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 14:32:59.926  4220  4236 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:32:59.926  4220  4220 I bt_bluedroid: get_profile_interface sdp
,08-24 14:32:59.934  4220  4231 I bt_bluedroid: config_hci_snoop_log
,08-24 14:32:59.938   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 14:32:59.952  4220  4232 D BluetoothAdapterState: Current state: OFF, message: 0
08-24 14:32:59.952  4220  4232 D BluetoothAdapterProperties: Setting state to 14
,08-24 14:32:59.953  4220  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 14:32:59.957  4220  4232 D BluetoothBondStateMachine: make
,08-24 14:32:59.966  4220  4237 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 14:32:59.972  4220  4232 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:32:59.975  4220  4220 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 14:32:59.980  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:32:59.982  4220  4220 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:32:59.983  4220  4220 D BtGatt.GattService: Received start request. Starting profile...
,08-24 14:32:59.983  4220  4220 D BtGatt.GattService: start()
08-24 14:32:59.983  4220  4220 I bt_bluedroid: get_profile_interface gatt
,08-24 14:32:59.985  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:32:59.985  4220  4220 D BtGatt.AdvertiseManager: advertise manager created
,08-24 14:32:59.996  4220  4220 V BluetoothAdapterState: isTurningOff()=false
08-24 14:32:59.996  4220  4220 V BluetoothAdapterState: isTurningOn()=false
08-24 14:32:59.996  4220  4220 V BluetoothAdapterState: isBleTurningOn()=true
08-24 14:32:59.996  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:32:59.997  4220  4232 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 14:32:59.998  4220  4232 I bt_bluedroid: enable
08-24 14:32:59.998  4220  4233 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-24 14:32:59.999  4220  4233 I bt_hci  : start_up
,08-24 14:33:00.020  4220  4233 I bt_vendor: alloc value 0xb39e5189,
08-24 14:33:00.020  4220  4233 I bt_vendor: init,
08-24 14:33:00.021  4220  4233 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-24 14:33:00.021  4220  4233 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 14:33:00.131  4220  4233 D bt_hci  : start_up starting async portion
,08-24 14:33:00.132  4220  4240 I bt_hci  : event_finish_startup
08-24 14:33:00.132  4220  4240 I bt_hci_h4: hal_open
,08-24 14:33:00.133  4220  4240 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 14:33:00.143  4220  4240 I bt_userial_vendor: device fd = 51 open
,08-24 14:33:00.173  4220  4240 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:33:00.205  4220  4240 D bt_hwcfg: Chipset BCM4354A2
,08-24 14:33:00.205  4220  4240 D bt_hwcfg: Target name = [BCM4354A2]
08-24 14:33:00.206  4220  4240 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 14:33:01.047  4220  4240 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 14:33:01.048  4220  4240 D bt_hwcfg: Settlement delay -- 100 ms
08-24 14:33:01.049  4220  4240 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 14:33:01.166  4220  4240 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:33:01.168  4220  4240 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 14:33:01.196  4220  4240 I bt_hwcfg: vendor lib fwcfg completed
,08-24 14:33:01.196  4220  4240 I bt_vendor: firmware callback
,08-24 14:33:01.197  4220  4240 I bt_hci  : firmware_config_callback
,08-24 14:33:01.210  4220  4242 I bt_btu  : btu_task pending for preload complete event
,08-24 14:33:01.211  4220  4242 I bt_btu_task: Bluetooth chip preload is complete
,08-24 14:33:01.211  4220  4242 I bt_btu  : btu_task received preload complete event
,08-24 14:33:01.223  4220  4242 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 14:33:01.223  4220  4242 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 14:33:01.223  4220  4242 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 14:33:01.224  4220  4242 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 14:33:01.224  4220  4242 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-24 14:33:01.224  4220  4242 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 14:33:01.225  4220  4242 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 14:33:01.225  4220  4242 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 14:33:01.225  4220  4242 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:33:01.226  4220  4242 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:33:01.226  4220  4242 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:33:01.226  4220  4242 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 14:33:01.226  4220  4242 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 14:33:01.226  4220  4242 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:33:01.227  4220  4242 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 14:33:01.374  4220  4242 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-24 14:33:01.374  4220  4242 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-24 14:33:01.382  4220  4236 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 14:33:01.385  4220  4236 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 14:33:01.387  4220  4236 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:33:01.392  4220  4236 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:33:01.396  4220  4236 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:33:01.397  4220  4236 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:33:01.398  4220  4236 D bt_hci  : do_postload posting postload work item
,08-24 14:33:01.399  4220  4240 I bt_hci  : event_postload
08-24 14:33:01.399  4220  4240 I bt_vendor: sco_config_cb
,08-24 14:33:01.399  4220  4240 I bt_hci  : sco_config_callback postload finished.
,08-24 14:33:01.403  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:01.405  4220  4240 I bt_vendor: low_power_mode_cb
08-24 14:33:01.406  4220  4236 D bt_bte_conf: Device ID record 1 : primary
08-24 14:33:01.407  4220  4236 D bt_bte_conf:   vendorId            = 000f
,08-24 14:33:01.407  4220  4236 D bt_bte_conf:   vendorIdSource      = 0001
08-24 14:33:01.408  4220  4236 D bt_bte_conf:   product             = 1200
,08-24 14:33:01.408  4220  4236 D bt_bte_conf:   version             = 1436
08-24 14:33:01.410  4220  4236 D bt_bte_conf:   clientExecutableURL = 
08-24 14:33:01.410  4220  4236 D bt_bte_conf:   serviceDescription  = 
,08-24 14:33:01.410  4220  4236 D bt_bte_conf:   documentationURL    = 
08-24 14:33:01.412  4220  4236 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 14:33:01.412  4220  4233 D bt_stack_manager: event_start_up_stack finished
,08-24 14:33:01.413  4220  4232 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 14:33:01.414  4220  4232 D BluetoothAdapterProperties: Setting state to 15
08-24 14:33:01.414  4220  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 14:33:01.415  4220  4232 I BluetoothAdapterState: Entering BleOnState
,08-24 14:33:01.420  4220  4232 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 14:33:01.420  4220  4232 D BluetoothAdapterProperties: Setting state to 11
08-24 14:33:01.421  4220  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 14:33:01.428  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:01.429  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:33:01.430  4220  4220 D HeadsetService: Received start request. Starting profile...
08-24 14:33:01.433  4220  4220 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 14:33:01.434  4220  4220 D HeadsetStateMachine: make
,08-24 14:33:01.438  4220  4232 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:33:01.446  4220  4220 D HeadsetStateMachine: max_hf_connections = 1
08-24 14:33:01.447  4220  4220 I bt_bluedroid: get_profile_interface handsfree
08-24 14:33:01.447  4220  4236 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-24 14:33:01.448  4220  4236 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 14:33:01.459  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:33:01.460  4220  4220 D A2dpService: Received start request. Starting profile...
,08-24 14:33:01.462  4220  4220 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 14:33:01.463  4220  4220 I bt_bluedroid: get_profile_interface avrcp
,08-24 14:33:01.473  4220  4220 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 14:33:01.473  4220  4220 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:33:01.473  4220  4220 D A2dpStateMachine: make
,08-24 14:33:01.475  4220  4220 I bt_bluedroid: get_profile_interface a2dp
08-24 14:33:01.475  4220  4236 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 14:33:01.479  4220  4251 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:33:01.480  4220  4220 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 14:33:01.481  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:33:01.481  4220  4220 D HidService: Received start request. Starting profile...
,08-24 14:33:01.481  4220  4220 I bt_bluedroid: get_profile_interface hidhost
08-24 14:33:01.482  4220  4220 D HidService: setHidService(): set to: null
08-24 14:33:01.482  4220  4236 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
08-24 14:33:01.482  4220  4236 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 14:33:01.482  4220  4220 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:33:01.483  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:33:01.484  4220  4220 D HealthService: Received start request. Starting profile...
08-24 14:33:01.485  4220  4220 I bt_bluedroid: get_profile_interface health
08-24 14:33:01.486  4220  4220 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 14:33:01.487  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:33:01.488  4220  4220 D PanService: Received start request. Starting profile...
08-24 14:33:01.488  4220  4220 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:33:01.488  4220  4220 I bt_bluedroid: get_profile_interface pan
,08-24 14:33:01.489  4220  4236 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 14:33:01.493  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:33:01.493  4220  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
08-24 14:33:01.494  4220  4220 D BluetoothMapService: Received start request. Starting profile...
08-24 14:33:01.494  4220  4220 D BluetoothMapService: start()
,08-24 14:33:01.497  4220  4220 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 14:33:01.498  4220  4220 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 14:33:01.498  4220  4220 D BluetoothMapAppObserver: createReceiver()
08-24 14:33:01.499  4220  4220 D BluetoothMapAppObserver: initObservers()
,08-24 14:33:01.499  4220  4220 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 14:33:01.508  4220  4220 V BluetoothAdapterState: isTurningOff()=false
08-24 14:33:01.508  4220  4220 V BluetoothAdapterState: isTurningOn()=true
08-24 14:33:01.508  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:33:01.508  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:33:01.509  4220  4249 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isTurningOn()=true
08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isTurningOff()=false
08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isTurningOn()=true
,08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:33:01.511  4220  4220 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isTurningOn()=true
08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isTurningOff()=false
08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isTurningOn()=true
08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:33:01.512  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:33:01.515  4220  4220 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:33:01.515  4220  4220 V BluetoothAdapterState: isTurningOn()=true
,08-24 14:33:01.515  4220  4220 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:33:01.515  4220  4220 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:33:01.516  4220  4232 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 14:33:01.516  4220  4232 D BluetoothAdapterProperties: ScanMode =  20
,08-24 14:33:01.516  4220  4232 D BluetoothAdapterProperties: State =  11
,08-24 14:33:01.520  4220  4236 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:33:01.520  4220  4232 D BluetoothAdapterProperties: Setting state to 12
08-24 14:33:01.520  4220  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:33:01.520  4220  4236 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:33:01.521   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:33:01.521  4220  4232 I BluetoothAdapterState: Entering OnState
08-24 14:33:01.521   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:33:01.522  3914  3924 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:01.525  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:01.526  3914  4215 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 14:33:01.527  4220  4220 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 14:33:01.528  4220  4220 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-24 14:33:01.529  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:33:01.531  1349  1362 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:33:01.531  4220  4220 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:33:01.533  1929  2090 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:33:01.535  1349  2056 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:33:01.535  4220  4220 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:33:01.537  4220  4220 D ObexServerSockets: Succeed to create listening sockets 
08-24 14:33:01.537  4220  4220 D ObexServerSockets0: startAccept()
08-24 14:33:01.537  4220  4220 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:33:01.537  3914  3926 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:33:01.539  3914  3924 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:33:01.540  4220  4220 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 14:33:01.541  4220  4220 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-24 14:33:01.542  3914  4215 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:33:01.543  4220  4256 D ObexServerSockets0: Accepting socket connection...
08-24 14:33:01.543  4220  4257 D ObexServerSockets0: Accepting socket connection...
,08-24 14:33:01.544  1349  1349 D BluetoothA2dp: Proxy object connected
,08-24 14:33:01.545  3914  3914 D BluetoothInputDevice: Proxy object connected
,08-24 14:33:01.545  3914  3914 D HidProfile: Bluetooth service connected
,08-24 14:33:01.547   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:33:01.547   873   873 D BluetoothA2dp: Proxy object connected
08-24 14:33:01.548  1349  1362 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:33:01.548  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 14:33:01.548  3914  3914 D PanProfile: Bluetooth service connected
08-24 14:33:01.548  3914  3914 D BluetoothA2dp: Proxy object connected
,08-24 14:33:01.551  1349  2056 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:33:01.552  1349  1349 D BluetoothMap: Proxy object connected
08-24 14:33:01.552  1349  1349 D MapProfile: Bluetooth service connected
08-24 14:33:01.552  1349  1349 D BluetoothMap: getConnectedDevices()
08-24 14:33:01.552  1349  1361 D BluetoothPan: onBluetoothStateChange on: true
,08-24 14:33:01.555  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:33:01.555  1349  1349 D PanProfile: Bluetooth service connected
08-24 14:33:01.555   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:33:01.555  3914  3924 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:33:01.558  3914  3914 D BluetoothMap: Proxy object connected
,08-24 14:33:01.558  3914  3914 D MapProfile: Bluetooth service connected
08-24 14:33:01.558  3914  3914 D BluetoothMap: getConnectedDevices()
08-24 14:33:01.558  1349  2056 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:33:01.561  1349  1349 D BluetoothInputDevice: Proxy object connected
08-24 14:33:01.561  1349  1349 D HidProfile: Bluetooth service connected
,08-24 14:33:01.566   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 14:33:01.566  4220  4220 D BluetoothMapService: onReceive
,08-24 14:33:01.566  4220  4220 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:33:01.567  4220  4220 D BluetoothMapService: STATE_ON
,08-24 14:33:01.567  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:01.572  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:33:01.579  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:33:01.581  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:33:01.591  3914  3914 D BluetoothPbap: Proxy object connected
,08-24 14:33:01.591  3914  3914 D PbapServerProfile: Bluetooth service connected
,08-24 14:33:01.593  1349  1349 D BluetoothPbap: Proxy object connected
08-24 14:33:01.593  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-24 14:33:01.600  4220  4220 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 14:33:01.600  4220  4220 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:33:01.605  4220  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:33:01.628  1349  1361 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.628  1349  1349 D HeadsetProfile: Bluetooth service connected
08-24 14:33:01.629  1929  1943 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.629   873   873 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.630   873   873 D BluetoothHeadset: Proxy object connected
08-24 14:33:01.630  3914  3926 D BluetoothHeadset: Proxy object connected
08-24 14:33:01.631   873   873 D BluetoothHeadset: Proxy object connected
08-24 14:33:01.634  3914  3914 D HeadsetProfile: Bluetooth service connected
08-24 14:33:01.635  1929  2121 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.638  3914  3924 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.639  3914  3914 D HeadsetProfile: Bluetooth service connected
,08-24 14:33:01.641  4220  4267 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:33:01.644  4220  4267 I BtOppRfcommListener: Accept thread started.
,08-24 14:33:01.652  1349  2056 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.653  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-24 14:33:01.655   873   890 D BluetoothHeadset: Proxy object connected
,08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:01.713  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:01.720  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:33:01.723  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:01.724  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b01457 added. We now have 8 listener(s)
,08-24 14:33:01.724  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:33:01.730   873  1938 D WifiService: setWifiEnabled: false pid=3857, uid=10000
,08-24 14:33:01.730   873  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:33:01.741  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:01.742   873  1688 D WifiService: setWifiEnabled: true pid=3857, uid=10000
08-24 14:33:01.742   873  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:33:01.753   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:01.773  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:01.781  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:33:01.788   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-24 14:33:01.789   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-24 14:33:01.790   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 14:33:01.791   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 14:33:01.791   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 14:33:01.792   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 14:33:01.792   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 14:33:01.804   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:33:01.804   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 14:33:01.806   372   871 D CommandListener: Setting iface cfg
,08-24 14:33:01.856   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-24 14:33:01.856   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 14:33:01.862   873  1305 E native  : do suspend true
,08-24 14:33:01.865   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 14:33:01.881   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 14:33:01.899   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:33:02.238   873   882 I art     : Background partial concurrent mark sweep GC freed 30422(1634KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 29MB/43MB, paused 799us total 102.352ms
,08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:02.764  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:02.771  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:33:02.783  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 14:33:02.786  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 14:33:02.792  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e915ec Bundle[{}]
,08-24 14:33:02.793  3857  3904 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:33:02.793  3857  3904 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 14:33:02.794  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 14:33:02.794  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 14:33:02.795  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 14:33:02.796  3857  3904 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:33:02.800  3857  3904 I System.out: Running OutgoingSocketThread
,08-24 14:33:02.802  3857  4275 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-24 14:33:02.804  3857  4275 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49745
,08-24 14:33:02.805  3857  4275 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 14:33:03.306   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:33:03.439   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.25 rxSuccessRate=9.81 delta 1000 -> 994
,08-24 14:33:03.443   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-24 14:33:03.443   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:33:03.458   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 14:33:03.538   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 14:33:03.540  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 14:33:03.803  3857  3904 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
08-24 14:33:03.803  3857  3904 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-24 14:33:03.813  3857  3904 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-24 14:33:03.815  3857  3904 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-24 14:33:03.815  3857  3904 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-24 14:33:03.820  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:33:03.820  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4755b44 added. We now have 2 listener(s)
,08-24 14:33:03.822  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:33:03.822  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:33:03.823  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:03.823  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:03.823  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ec42d added. We now have 9 listener(s)
,08-24 14:33:03.823  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:03.824  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:33:03.830  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:03.836  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:03.840  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:33:03.840  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:33:03.840  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:33:03.840  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d379ef3 added. We now have 3 listener(s)
,08-24 14:33:03.849  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:03.850  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:33:03.850  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:33:03.851  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:03.851  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:03.852  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60ee7b0 added. We now have 10 listener(s)
08-24 14:33:03.852  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:03.852  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:03.853  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:33:03.853  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:33:03.853  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:33:03.853  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:03.854  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.854  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:33:03.855  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:03.855  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4755b44 removed from the list
08-24 14:33:03.855  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.855  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ec42d removed from the list
08-24 14:33:03.856  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:33:03.856  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.857  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.857  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.860  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:03.860  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:03.860  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.860  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ec42d not in the list
08-24 14:33:03.861  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.862  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:33:03.863  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:03.863  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:03.863  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.864  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60ee7b0 removed from the list
08-24 14:33:03.864  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:03.864  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:03.864  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.864  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:03.864  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d379ef3 removed from the list
08-24 14:33:03.865  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:03.865  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1107629 added. We now have 2 listener(s)
,08-24 14:33:03.868  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:33:03.868  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:33:03.869  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:03.869  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:03.869  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8fdae added. We now have 9 listener(s)
08-24 14:33:03.869  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:33:03.870  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:33:03.875  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:03.883  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:03.887  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:33:03.888  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:33:03.889  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:33:03.891  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:03.890  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72cedc added. We now have 3 listener(s)
,08-24 14:33:03.893  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:03.900  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:33:03.900  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:33:03.902  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:33:03.903  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:33:03.904  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6114be5 added. We now have 10 listener(s)
08-24 14:33:03.904  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:03.905  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:33:03.905  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:33:03.905  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:33:03.906  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:33:03.906  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:33:03.914  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:33:03.914  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:33:03.920  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:33:03.921  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:33:03.921  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:33:03.927  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:33:03.927  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:33:03.927  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:33:03.928  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:33:03.933  4220  4230 D BtGatt.GattService: registerClient() - UUID=f90c49a1-ce64-41a3-9978-369ae6e51467
,08-24 14:33:03.935  4220  4236 D BtGatt.GattService: onClientRegistered() - UUID=f90c49a1-ce64-41a3-9978-369ae6e51467, clientIf=5
,08-24 14:33:03.936  3857  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 14:33:03.938  4220  4259 D BtGatt.GattService: start scan with filters
,08-24 14:33:03.945  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:33:03.945  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:33:03.946  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:33:03.946  4220  4239 D BtGatt.ScanManager: handling starting scan
08-24 14:33:03.946  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:33:03.949  4220  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c3ddc0
,08-24 14:33:03.954  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:33:03.956  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:33:03.957  4220  4236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:33:03.957  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:33:03.957  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:03.960  4220  4239 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:33:03.963  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 14:33:03.965  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:33:03.977  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 14:33:03.977  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:03.978  4220  4239 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 14:33:03.979  3857  3904 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:33:03.979  4220  4239 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:33:03.979  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:33:03.979  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 14:33:03.979  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.979  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:33:03.979  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:33:03.979  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-24 14:33:03.979  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:33:03.979  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:33:03.980  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:33:03.980  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:33:03.982  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:33:03.982  4220  4230 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:33:03.984  4220  4259 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:33:03.984  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:33:03.985  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:33:03.985  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:33:03.985  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:33:03.985  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:33:03.988  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:03.988  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:33:03.988  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:33:03.988  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:33:03.989  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:33:03.990  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:33:03.990  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:33:03.990  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:03.993  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:33:03.994  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:33:03.994  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:33:03.994  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:03.994  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:03.994  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:33:03.994  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:33:03.994  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1107629 removed from the list
08-24 14:33:03.994  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.994  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8fdae removed from the list
08-24 14:33:03.995  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:33:03.995  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.995  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.995  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.995  4220  4236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:33:03.996  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:03.997  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:03.997  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:03.997  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.997  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8fdae not in the list
08-24 14:33:03.997  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.997  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:03.998  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:33:03.998  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:03.998  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:03.998  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6114be5 removed from the list
08-24 14:33:03.998  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:03.998  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:03.999  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:33:03.999  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:03.999  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72cedc removed from the list
08-24 14:33:03.999  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:03.999  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8fc161 added. We now have 2 listener(s)
,08-24 14:33:04.001  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:33:04.002  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:33:04.002  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:04.002  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:33:04.002  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f271486 added. We now have 9 listener(s)
08-24 14:33:04.002  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:04.002  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 14:33:04.002  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.002  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:33:04.005  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:04.008  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:04.010  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 14:33:04.010  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.010  4220  4239 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:33:04.010  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:33:04.010  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:33:04.011  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:04.011  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6081d74 added. We now have 3 listener(s)
08-24 14:33:04.012  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:04.013  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:33:04.013  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:33:04.013  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:04.014  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:04.014  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626129d added. We now have 10 listener(s)
,08-24 14:33:04.014  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:04.014  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-24 14:33:04.014  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 14:33:04.015  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 14:33:04.015  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 14:33:04.015  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:33:04.015  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:33:04.015  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:33:04.017  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
,08-24 14:33:04.017  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.017  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:33:04.017  4220  4239 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-24 14:33:04.017  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 14:33:04.021  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:33:04.021  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:33:04.023   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:33:04.024  4220  4236 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:33:04.024  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-24 14:33:04.024  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:33:04.025  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
08-24 14:33:04.025  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:33:04.028  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:33:04.028  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:33:04.028  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:33:04.029  3857  3904 D BluetoothAdapter: STATE_ON
,08-24 14:33:04.029   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:33:04.029   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 14:33:04.029   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:33:04.031  4220  4259 D BtGatt.GattService: registerClient() - UUID=b6c29bec-2183-41f5-8f9a-d16afe3b694d
08-24 14:33:04.031  4220  4236 D BtGatt.GattService: onClientRegistered() - UUID=b6c29bec-2183-41f5-8f9a-d16afe3b694d, clientIf=5
,08-24 14:33:04.032  3857  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:33:04.032  4220  4231 D BtGatt.GattService: start scan with filters
,08-24 14:33:04.034  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:33:04.034  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 14:33:04.035  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:33:04.035  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:33:04.035  4220  4239 D BtGatt.ScanManager: handling starting scan
08-24 14:33:04.038  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:33:04.038  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:33:04.038  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:33:04.039   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:33:04.040  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:33:04.042  4220  4236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 14:33:04.043  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.043  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:33:04.043  3857  3904 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 14:33:04.043  4220  4239 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:33:04.043  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:33:04.043  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:33:04.043  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:33:04.043  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:04.043  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:04.043  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:33:04.043  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:33:04.044  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8fc161 removed from the list
08-24 14:33:04.044  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.044  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f271486 removed from the list
,08-24 14:33:04.044  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:33:04.044  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:33:04.044  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:04.044  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 14:33:04.044  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.045  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:33:04.047  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:04.047  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:33:04.047  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.047   372   871 D CommandListener: Setting iface cfg
08-24 14:33:04.047  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f271486 not in the list
08-24 14:33:04.047  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:33:04.047  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:33:04.047  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:33:04.048  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:33:04.048  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 14:33:04.048  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:33:04.048  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.048   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3,
08-24 14:33:04.048  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:33:04.048  4220  4239 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:33:04.049  4220  4239 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 14:33:04.049  4220  4231 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:33:04.049  4220  4248 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:33:04.050  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 14:33:04.050  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:33:04.050  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 14:33:04.050  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:33:04.050  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:33:04.051  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:04.051  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:33:04.051  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:33:04.051  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:33:04.052  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.053  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:33:04.053  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 14:33:04.053  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:04.053  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:04.053  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:33:04.053  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.053  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626129d removed from the list
08-24 14:33:04.053  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:04.053  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.054  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.054  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:33:04.054  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6081d74 removed from the list
08-24 14:33:04.054  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:04.054   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-24 14:33:04.054  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d63b99 added. We now have 2 listener(s)
,08-24 14:33:04.056  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:33:04.056  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:33:04.056  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:04.056  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:33:04.056  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db62e5e added. We now have 9 listener(s)
08-24 14:33:04.056  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:04.056  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:33:04.059  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:33:04.060  4220  4236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:33:04.060  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:04.061  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:04.063  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:33:04.063  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:33:04.063  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:04.063  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef5a70c added. We now have 3 listener(s)
08-24 14:33:04.064  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:04.064  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:33:04.065  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.065  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:33:04.066  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:33:04.066  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:33:04.066  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:04.066  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:04.066  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c5f855 added. We now have 10 listener(s)
08-24 14:33:04.066  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:04.066  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:33:04.066  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:33:04.066  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:33:04.067  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:33:04.067  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:33:04.069  3857  3904 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:33:04.069  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:33:04.069   873  4278 D DhcpClient: Receive thread started
,08-24 14:33:04.070  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 14:33:04.070  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.071  4220  4239 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:33:04.072  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:33:04.072  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:33:04.073  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:33:04.075  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:33:04.075  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:33:04.075  3857  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:33:04.076  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:33:04.076  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:33:04.076  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.076  4220  4239 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 14:33:04.077  4220  4248 D BtGatt.GattService: registerClient() - UUID=990e0924-3b6c-4cb9-8b04-508e7cb9257c
,08-24 14:33:04.077  4220  4236 D BtGatt.GattService: onClientRegistered() - UUID=990e0924-3b6c-4cb9-8b04-508e7cb9257c, clientIf=5
08-24 14:33:04.078  3857  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:33:04.078  4220  4231 D BtGatt.GattService: start scan with filters
,08-24 14:33:04.080  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:33:04.080  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:33:04.080  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:33:04.080  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:33:04.081  4220  4236 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 14:33:04.081  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.082  4220  4239 D BtGatt.ScanManager: handling starting scan
08-24 14:33:04.082  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:33:04.082  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:33:04.082  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:33:04.084  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:33:04.087  4220  4236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 14:33:04.087  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.087  4220  4239 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:33:04.089  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:33:04.089  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:33:04.089  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:33:04.089  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:33:04.089  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.089  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 14:33:04.089  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:04.089  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d63b99 removed from the list
,08-24 14:33:04.089  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.090  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db62e5e removed from the list
08-24 14:33:04.090  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop,
08-24 14:33:04.090  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:33:04.090  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.090  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-24 14:33:04.090  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.090  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-24 14:33:04.091  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:33:04.091  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.091  4220  4239 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:33:04.091  4220  4239 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.092  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db62e5e not in the list
08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:33:04.092  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:33:04.092  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:33:04.092  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:33:04.093  3857  3904 D BluetoothAdapter: STATE_ON
08-24 14:33:04.093  4220  4248 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:33:04.094  4220  4230 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:33:04.094  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:33:04.094  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:33:04.094  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 14:33:04.094  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:33:04.094  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:33:04.095  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:04.095  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:33:04.095  3857  3904 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:33:04.095  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:33:04.096  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.097  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:33:04.097  3857  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 14:33:04.097  3857  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:33:04.097  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:04.097  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:04.097  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.097  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c5f855 removed from the list
08-24 14:33:04.097  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-24 14:33:04.097  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.098  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.098  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:33:04.098  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef5a70c removed from the list
08-24 14:33:04.098  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:04.098  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bac4d1 added. We now have 2 listener(s)
,08-24 14:33:04.100  4220  4236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:33:04.100  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.100  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:33:04.100  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:33:04.100  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:33:04.100  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:04.100  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23ab36 added. We now have 9 listener(s)
08-24 14:33:04.100  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:04.101  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:33:04.103  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:33:04.104  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:33:04.104  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:33:04.107  3857  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:33:04.109  3857  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-24 14:33:04.109  3857  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:33:04.110  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:04.110  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:33:04.110  4220  4236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 14:33:04.110  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.110  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7cba4 added. We now have 3 listener(s)
08-24 14:33:04.110  4220  4239 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:33:04.111  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:33:04.112  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:33:04.113  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:33:04.113  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:33:04.113  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:33:04.113  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c55dd0d added. We now have 10 listener(s)
08-24 14:33:04.113  3857  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:33:04.113  3857  3904 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:33:04.113  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:33:04.113  3857  3904 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:33:04.113  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:33:04.114  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.114  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:33:04.114  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:04.114  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bac4d1 removed from the list
,08-24 14:33:04.114  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.114  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23ab36 removed from the list
08-24 14:33:04.114  3857  3904 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:33:04.114  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.114  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:04.114  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.115  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:04.115  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:04.115  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.115  3857  3904 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23ab36 not in the list
08-24 14:33:04.115  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:33:04.115  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:33:04.116  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:33:04.116  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:33:04.116  3857  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:33:04.116  4220  4236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 14:33:04.116  3857  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c55dd0d removed from the list
,08-24 14:33:04.116  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.116  3857  3904 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:33:04.116  3857  3904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:33:04.116  4220  4239 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 14:33:04.116  3857  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:33:04.116  3857  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:33:04.116  3857  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7cba4 removed from the list
08-24 14:33:04.117  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-24 14:33:04.117  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 14:33:04.117  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 14:33:04.117  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:33:04.118  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-24 14:33:04.118  3857  3904 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:33:04.121  4220  4236 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:33:04.121  4220  4236 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:33:04.123  3857  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
08-24 14:33:04.123  3857  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-24 14:33:04.123  3857  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
,08-24 14:33:04.124  3857  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
08-24 14:33:04.125  3857  4280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
08-24 14:33:04.125  3857  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 14:33:04.126  3857  3904 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 14:33:04.126  3857  3904 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 14:33:04.126  3857  3904 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 14:33:04.126  3857  3904 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 14:33:04.126  3857  3904 D com.test.thalitest.ThaliTestRunner: Total duration: 22855 ms
,08-24 14:33:04.128  3857  3904 I jxcore-log: Total number of executed tests:  80
08-24 14:33:04.128  3857  3904 I jxcore-log: 
,08-24 14:33:04.128  3857  3904 I jxcore-log: Number of passed tests:  80
08-24 14:33:04.128  3857  3904 I jxcore-log: 
08-24 14:33:04.128  3857  3904 I jxcore-log: Number of failed tests:  0
08-24 14:33:04.128  3857  3904 I jxcore-log: 
08-24 14:33:04.128  3857  3904 I jxcore-log: Number of ignored tests:  0
08-24 14:33:04.128  3857  3904 I jxcore-log: 
08-24 14:33:04.128  3857  3904 I jxcore-log: Total duration:  22855
08-24 14:33:04.128  3857  3904 I jxcore-log: 
,08-24 14:33:04.128  3857  3904 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 14:33:04.128  3857  3904 I jxcore-log: 
,08-24 14:33:04.132  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.132  3857  3904 I jxcore-log: 
08-24 14:33:04.134  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.134  3857  3904 I jxcore-log: 
08-24 14:33:04.135  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.135  3857  3904 I jxcore-log: 
08-24 14:33:04.136  3857  3857 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 14:33:04.136  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.136  3857  3904 I jxcore-log: 
08-24 14:33:04.137  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.137  3857  3904 I jxcore-log: 
08-24 14:33:04.139  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.139  3857  3904 I jxcore-log: 
08-24 14:33:04.141  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.141  3857  3904 I jxcore-log: 
,08-24 14:33:04.142  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.142  3857  3904 I jxcore-log: 
,08-24 14:33:04.143  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.143  3857  3904 I jxcore-log: 
08-24 14:33:04.143  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.143  3857  3904 I jxcore-log: 
,08-24 14:33:04.144  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.144  3857  3904 I jxcore-log: 
,08-24 14:33:04.145  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:33:04.145  3857  3904 I jxcore-log: 
,08-24 14:33:04.146  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.146  3857  3904 I jxcore-log: 
08-24 14:33:04.147  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.147  3857  3904 I jxcore-log: 
,08-24 14:33:04.147  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.147  3857  3904 I jxcore-log: 
08-24 14:33:04.148  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.148  3857  3904 I jxcore-log: 
,08-24 14:33:04.148  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.148  3857  3904 I jxcore-log: 
,08-24 14:33:04.149  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.149  3857  3904 I jxcore-log: 
08-24 14:33:04.150  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.150  3857  3904 I jxcore-log: 
,08-24 14:33:04.150  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.150  3857  3904 I jxcore-log: 
08-24 14:33:04.151  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.151  3857  3904 I jxcore-log: 
,08-24 14:33:04.151  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.151  3857  3904 I jxcore-log: 
,08-24 14:33:04.152  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.152  3857  3904 I jxcore-log: 
,08-24 14:33:04.153  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:33:04.153  3857  3904 I jxcore-log: 
08-24 14:33:04.153  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.153  3857  3904 I jxcore-log: 
08-24 14:33:04.154   873  1305 E native  : do suspend false
,08-24 14:33:04.154  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.154  3857  3904 I jxcore-log: 
,08-24 14:33:04.154  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.154  3857  3904 I jxcore-log: 
,08-24 14:33:04.155  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.155  3857  3904 I jxcore-log: 
08-24 14:33:04.156  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.156  3857  3904 I jxcore-log: 
,08-24 14:33:04.156  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.156  3857  3904 I jxcore-log: 
,08-24 14:33:04.157  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:33:04.157  3857  3904 I jxcore-log: 
,08-24 14:33:04.164   873  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 14:33:04.199   873  4278 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-24 14:33:04.199   873  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
08-24 14:33:04.201   873  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 14:33:04.214   873  4278 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 14:33:04.215   873  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 14:33:04.219   372   871 D CommandListener: Setting iface cfg
,08-24 14:33:04.222   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 14:33:04.227   873  1305 E native  : do suspend true
,08-24 14:33:04.228   873  1877 D DhcpClient: Scheduling renewal in 86399s
,08-24 14:33:04.237   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 14:33:04.238   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 14:33:04.238   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 14:33:04.241   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
08-24 14:33:04.243   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:33:04.295   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 14:33:04.295   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-24 14:33:04.296   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-24 14:33:04.298   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-24 14:33:04.299   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 14:33:04.305   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 14:33:04.308   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 14:33:04.309   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-24 14:33:04.309   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-24 14:33:04.309   873  1308 D ConnectivityService:    accepting network in place of null
08-24 14:33:04.310   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:33:04.316   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-24 14:33:04.319   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 14:33:04.330   873  4277 D NetlinkSocketObserver: NeighborEvent{elapsedMs=230715, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 14:33:04.350   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:33:04.375   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:33:04.380   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-24 14:33:04.380   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:33:04.382   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 14:33:04.383   873   890 D Tethering: MasterInitialState.processMessage what=3
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:33:04.393  3857  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:33:04.395  3857  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:33:04.396  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:33:04.396  3857  3904 I jxcore-log: 
,08-24 14:33:04.400   873  4276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:816::200e
,08-24 14:33:04.405  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:33:04.410  1697  1697 D SystemUpdateService: onCreate
,08-24 14:33:04.414  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:33:04.435  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 14:33:04.442  1697  4291 I SystemUpdateService: active receiver: enabled
,08-24 14:33:04.444  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:33:04.438  1697  2444 I iu.UploadsManager: num queued entries: 0
,08-24 14:33:04.446  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:33:04.452  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:33:04.458  1697  4293 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 14:33:04.459  1697  4293 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:33:04.460  3994  3994 D SprintDMHelper: simOperator: 
,08-24 14:33:04.461  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-24 14:33:04.464  1697  4293 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
08-24 14:33:04.466  1697  2444 I iu.UploadsManager: num updated entries: 0
08-24 14:33:04.468  1697  4291 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:33:04.483   873  4276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:33:04 GMT], X-Android-Received-Millis=[1472041984482], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472041984452]}
,08-24 14:33:04.483   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 14:33:04.483   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-24 14:33:04.484   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 14:33:04.484   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 14:33:04.491  3857  3857 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:33:04.492  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:33:04.492  3857  3904 I jxcore-log: 
,08-24 14:33:04.505  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:33:04.511  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:33:04.525  1697  4291 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 14:33:04.527  1697  2444 I iu.SyncManager: NEXT; no task
,08-24 14:33:04.529  1697  4291 I SystemUpdateService: now status is 0 (complete)
08-24 14:33:04.529  1697  4291 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 14:33:04.529  1697  4291 I SystemUpdateService: file has been verified
08-24 14:33:04.529  1697  4291 I SystemUpdateService: OTA package size = 12249756
,08-24 14:33:04.551  1697  4291 I SystemUpdateService: showing system update notification
,08-24 14:33:04.553  3857  3857 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:33:04.554  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:33:04.554  3857  3904 I jxcore-log: 
,08-24 14:33:04.571  1505  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-24 14:33:04.571  1505  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 14:33:04.571  1505  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:33:04.571  1505  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:33:04.582  1697  1697 D SystemUpdateService: onDestroy
,08-24 14:33:04.590  1697  4293 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-24 14:33:04.597  3857  3857 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:33:04.598  3857  3904 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:33:04.598  3857  3904 I jxcore-log: 
,08-24 14:33:04.629  3965  4297 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 14:33:04.806  4281  4281 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 14:33:04.811  4281  4281 D AndroidRuntime: CheckJNI is OFF
,08-24 14:33:04.855  4281  4281 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 14:33:04.905  4281  4281 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 14:33:04.930  4281  4281 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:33:04.942   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-24 14:33:04.943   873   886 I ActivityManager: Killing 3857:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-24 14:33:05.044   873   898 W PackageSettings: Skipping PackageSetting{85bf40d com.example.hello/10273} due to missing metadata
,08-24 14:33:05.055   873  1990 D GraphicsStats: Buffer count: 2
,08-24 14:33:05.056   873  1306 D WifiService: Client connection lost with reason: 4
08-24 14:33:05.056   873  1688 I WindowState: WIN DEATH: Window{6971b37 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:33:05.083   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-24 14:33:05.084   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-24 14:33:05.085   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-24 14:33:05.085   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 14:33:05.085   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.085   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.085   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:33:05.085   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 14:33:05.086   873   886 I ActivityManager:   Force finishing activity ActivityRecord{f86f4b0 u0 com.test.thalitest/.MainActivity t2}
,08-24 14:33:05.086   873   898 I art     : Starting a blocking GC Explicit
,08-24 14:33:05.106   873  1954 W ActivityManager: Spurious death for ProcessRecord{e7210b6 0:com.test.thalitest/u0a0}, curProc for 3857: null
,08-24 14:33:05.142   873   898 I art     : Explicit concurrent mark sweep GC freed 43628(2MB) AllocSpace objects, 8(200KB) LOS objects, 33% free, 29MB/43MB, paused 750us total 56.222ms
,08-24 14:33:05.169   873   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 14:33:05.173   873   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 14:33:05.175  4281  4281 I art     : System.exit called, status: 0
,08-24 14:33:05.175  4281  4281 I AndroidRuntime: VM exiting with result code 0.
,08-24 14:33:05.193   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-24 14:33:05.197  4220  4220 D BluetoothMapAppObserver: onReceive
08-24 14:33:05.197  4220  4220 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 14:33:05.198  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 14:33:05.204   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 14:33:05.205  3632  3632 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-24 14:33:05.207  2009  2283 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:33:05.221   873  2062 I ActivityManager: Start proc 4314:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-24 14:33:05.243  1864  4312 I Keyboard.Facilitator.DecoderInitializer: run()
,08-24 14:33:05.246  1929  1929 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-24 14:33:05.262  1864  4312 I Decoder : createOrResetDecoder
,08-24 14:33:05.273  4314  4314 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-24 14:33:05.277  1505  1505 I ConfigService: onCreate
,08-24 14:33:05.294   873  1954 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3857 uid 10000
,08-24 14:33:05.295  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-24 14:33:05.301   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 14:33:05.309  1864  4312 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 14:33:05.343   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-24 14:33:05.344  1947  2031 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-24 14:33:05.344   873   885 E PackageManager: Failed to write settings, restoring backup
08-24 14:33:05.344   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 14:33:05.344   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 14:33:05.344   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 14:33:05.344   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 14:33:05.344   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 14:33:05.344   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.344   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.344   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:33:05.347  4314  4314 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-24 14:33:05.348   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-24 14:33:05.348   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 14:33:05.348   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:33:05.348   873   886 E DropBoxManagerService: 	... 13 more
,08-24 14:33:05.356  1864  4312 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-24 14:33:05.358   873  1954 I ActivityManager: Start proc 4332:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-24 14:33:05.359  1947  2031 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 14:33:05.359  1947  2031 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1947
08-24 14:33:05.359  1947  2031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.359  1947  2031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:33:05.361   873  1990 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 14:33:05.362  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 14:33:05.362  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-24 14:33:05.364  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 14:33:05.364  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-24 14:33:05.365   873  4338 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:33:05.365   873  4338 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:33:05.365   873  4338 E DropBoxManagerService: 	... 5 more
,08-24 14:33:05.368  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 14:33:05.368  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 14:33:05.369  1864  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 14:33:05.369  1864  4312 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-24 14:33:05.369  1864  4312 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 14:33:05.369  1864  4312 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 14:33:05.369  1864  4312 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-24 14:33:05.369  1864  4312 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 14:33:05.372  4314  4343 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-24 14:33:05.375   873   884 I ActivityManager: Start proc 4347:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-24 14:33:05.380  1947  2031 I Process : Sending signal. PID: 1947 SIG: 9
,08-24 14:33:05.354  4314  4329 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.354  4314  4329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.388  4314  4329 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:33:05.447  4347  4347 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-24 14:33:05.501  1505  1505 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-24 14:33:05.503  1505  1505 D AndroidRuntime: Shutting down VM
,08-24 14:33:05.505  1505  1505 E AndroidRuntime: FATAL EXCEPTION: main
08-24 14:33:05.505  1505  1505 E AndroidRuntime: Process: com.google.process.gapps, PID: 1505
08-24 14:33:05.505  1505  1505 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 14:33:05.505  1505  1505 E AndroidRuntime: 	... 8 more
,08-24 14:33:05.512   873  4364 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:33:05.512   873  4364 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:33:05.512   873  4364 E DropBoxManagerService: 	... 5 more
,08-24 14:33:05.518  1505  1505 I Process : Sending signal. PID: 1505 SIG: 9
,08-24 14:33:05.543   873   883 I ActivityManager: Killing 3685:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-24 14:33:05.622   873  1306 D WifiService: Client connection lost with reason: 4
,08-24 14:33:05.661   873  1382 I ActivityManager: Process com.google.process.gapps (pid 1505) has died
,08-24 14:33:05.662   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-24 14:33:05.662   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-24 14:33:05.662   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,08-24 14:33:05.662   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-24 14:33:05.666  1697  4365 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@79804e3
,08-24 14:33:05.687  1697  1697 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-24 14:33:05.651  4314  4329 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-24 14:33:05.691   873  1688 I ActivityManager: Start proc 4366:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-24 14:33:05.703  4314  4343 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:33:05.703  4314  4343 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
