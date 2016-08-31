#### Test 828833414094bc4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 11:03:11.132  3763  3982 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
08-31 11:03:11.133   871  1432 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 11:03:11.207  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:03:11.212  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:03:11.266  1534  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-31 11:03:11.266  1534  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 11:03:11.266  1534  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:03:11.266  1534  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:03:11.320  1756  3983 V BaseAuthAsyncOperation: access token request failed
08-31 11:03:11.321  3763  3982 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-31 11:03:11.394  1534  2053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-31 11:03:11.394  1534  2053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 11:03:11.394  1534  2053 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:03:11.394  1534  2053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:03:11.406  3763  3982 E KeepSync: IOException
08-31 11:03:11.406  3763  3982 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 11:03:11.406  3763  3982 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:03:11.406  3763  3982 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 11:03:11.406  3763  3982 E KeepSync: 	... 10 more
08-31 11:03:11.406  3763  3982 W KeepSync: Sync result 2
08-31 11:03:11.410   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 163791, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-31 11:03:11.831  3984  3984 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 11:03:11.835  3984  3984 D AndroidRuntime: CheckJNI is OFF
08-31 11:03:11.870  3984  3984 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 11:03:11.945  3984  3984 I Radio-JNI: register_android_hardware_Radio DONE
08-31 11:03:11.971  3984  3984 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:03:11.976   871  2010 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:03:12.032   871  2010 I ActivityManager: Start proc 3993:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 11:03:12.040  3984  3984 D AndroidRuntime: Shutting down VM
,08-31 11:03:12.287  3993  3993 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 11:03:12.317  3993  3993 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 11:03:12.325  3993  3993 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4708-4711)
08-31 11:03:12.325  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:03:12.346  3993  3993 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {640f69}
,08-31 11:03:12.346  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:03:12.347  3993  3993 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:03:12.355  3993  3993 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 11:03:12.357  3993  3993 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:03:12.383  3993  3993 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 11:03:12.400  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:03:12.400  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:03:12.400  3993  3993 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:03:12.400  3993  3993 I Adreno  : Build Date                       : 10/20/15
08-31 11:03:12.400  3993  3993 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:03:12.400  3993  3993 I Adreno  : Local Branch                     : M14
08-31 11:03:12.400  3993  3993 I Adreno  : Remote Branch                    : 
08-31 11:03:12.400  3993  3993 I Adreno  : Remote Branch                    : 
08-31 11:03:12.400  3993  3993 I Adreno  : Reconstruct Branch               : 
,08-31 11:03:12.486   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af3d5d2:true
,08-31 11:03:12.561  3993  3993 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 11:03:12.581  3993  3993 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 11:03:12.692  3993  4031 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 11:03:12.706   871   884 W ActivityManager: Activity pause timeout for ActivityRecord{ac0cf0f u0 com.test.thalitest/.MainActivity t2}
,08-31 11:03:12.723  3993  4018 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 11:03:12.768  3993  4031 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 11:03:12.797  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-31 11:03:12.864   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +659ms (total +851ms)
,08-31 11:03:12.939  3993  3993 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3993
,08-31 11:03:13.082  3993  3993 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:03:13.265  3993  4033 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682769616
,08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 11:03:13.275  3993  4033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82e0074 added. We now have 1 listener(s)
,08-31 11:03:13.280  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 11:03:13.280  3993  4033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:03:13.281  3993  4033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:13.282  3993  4033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 11:03:13.286  3993  4033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83a9e3 added. We now have 1 listener(s)
08-31 11:03:13.286  3993  4033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:03:13.291   871  1314 D WifiService: New client listening to asynchronous messages
08-31 11:03:13.291  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:13.292  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 11:03:13.292  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:03:13.292  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:03:13.292  3993  4033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 11:03:13.295  3993  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:13.295  3993  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 11:03:13.308  3993  4033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:13.308  3993  4033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:13.308  3993  4033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:03:13.308  3993  4033 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:03:13.311  3993  4033 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:03:13.316  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:13.321  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:13.354  3993  3993 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:03:14.644  3993  4039 W jxcore-log: Initializing JXcore engine
,08-31 11:03:14.644  3993  4039 W jxcore-log: JXcore engine is ready
,08-31 11:03:14.683  4039  4039 W Thread-356: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8862 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 11:03:14.683  4039  4039 W Thread-356: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10622]" dev="sockfs" ino=10622 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 11:03:14.683  4039  4039 W Thread-356: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 11:03:14.683  4039  4039 W Thread-356: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27574]" dev="sockfs" ino=27574 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 11:03:14.698  3993  4039 W jxcore-log: Starting JXcore engine
,08-31 11:03:14.779  3993  4039 W jxcore-log: Platform android
08-31 11:03:14.779  3993  4039 W jxcore-log: 
,08-31 11:03:14.780  3993  4039 W jxcore-log: Process ARCH arm
08-31 11:03:14.780  3993  4039 W jxcore-log: 
,08-31 11:03:14.973  3993  4039 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:03:14.973  3993  4039 I jxcore-log: 
,08-31 11:03:14.973  3993  4039 W jxcore-log: JXcore engine is started
,08-31 11:03:14.984  3993  4033 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:03:14.992  3993  3993 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:03:17.558   871  1886 D NetlinkSocketObserver: NeighborEvent{elapsedMs=199943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-31 11:03:24.449  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:03:24.449  3993  4039 I jxcore-log: 
,08-31 11:03:24.451  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:03:24.451  3993  4039 I jxcore-log: 
,08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:24.462  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:24.467  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:24.469  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:03:24.469  3993  4039 I jxcore-log: 
,08-31 11:03:24.471  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:03:24.471  3993  4039 I jxcore-log: 
,08-31 11:03:24.972  3993  4039 I jxcore-log: Unit Test app is loaded
08-31 11:03:24.972  3993  4039 I jxcore-log: 
,08-31 11:03:24.978  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:03:24.978  3993  4039 I jxcore-log: 
,08-31 11:03:24.983  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:03:24.983  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae8dcbd added. We now have 2 listener(s)
,08-31 11:03:24.984  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:03:24.984  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:24.984  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:03:24.984  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:03:24.985  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95c2b2 added. We now have 2 listener(s)
,08-31 11:03:24.985  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:24.985  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:24.988  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:24.997  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:25.000  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:25.001  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:25.001  3993  4039 D ExecuteNativeTests: Running unit tests
,08-31 11:03:25.007  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:25.013  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:25.014  3993  3993 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:03:25.059  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:03:25.059  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 added. We now have 3 listener(s)
08-31 11:03:25.060  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:03:25.060  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:03:25.060  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:03:25.060  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:03:25.061  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 added. We now have 3 listener(s)
,08-31 11:03:25.061  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:03:25.061  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:03:25.064  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:25.080  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:25.083  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:25.083  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:03:25.087  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:03:25.091  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:03:25.091  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:03:25.092  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:03:25.092  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:25.095  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:25.097  3993  4039 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 11:03:25.098  3993  4039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:03:25.098  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:03:25.099  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:03:25.100  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:03:25.100  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:03:25.100  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:25.100  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:25.101  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:25.101  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:03:25.101  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 removed from the list
08-31 11:03:25.101  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:03:25.101  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 removed from the list
08-31 11:03:25.101  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:25.101  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:25.103  3993  4039 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:03:25.104  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:25.104  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:25.104  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:25.104  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:25.104  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:25.104  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:25.104  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:25.104  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:25.104  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:03:25.111  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
08-31 11:03:25.112  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-31 11:03:25.113  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-31 11:03:25.113  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:03:25.113  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:03:25.113  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-31 11:03:25.113  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:25.113  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:25.113  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list,
08-31 11:03:25.113  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:03:25.113  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list,
,08-31 11:03:25.113  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:03:25.113  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:25.113  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:25.117  3993  4039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true,
08-31 11:03:25.119  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:25.123  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:25.124  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:25.125  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:03:25.125  3993  4039 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-31 11:03:25.126  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-31 11:03:25.126  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:25.127  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:03:25.128  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-31 11:03:25.128  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:03:25.128  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:25.129  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-31 11:03:25.130  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:03:25.130  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-31 11:03:25.131  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:03:25.131  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:03:25.132  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-31 11:03:25.132  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-31 11:03:25.132  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:25.132  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:03:25.133  3993  4041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:03:25.135  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:03:25.135  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:03:25.136  3993  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-31 11:03:25.140  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:03:25.141  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:03:25.142  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:03:25.145  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-31 11:03:25.145  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:03:25.145  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-31 11:03:25.146  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:03:25.146  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:03:25.147  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-31 11:03:25.147  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:25.154  2651  2840 D BtGatt.GattService: registerClient() - UUID=3cfa5ca9-41f7-4d24-8a7b-de84bb0a2cdc
,08-31 11:03:25.155  2651  2680 D BtGatt.GattService: onClientRegistered() - UUID=3cfa5ca9-41f7-4d24-8a7b-de84bb0a2cdc, clientIf=5
,08-31 11:03:25.155  3993  4004 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-31 11:03:25.157  2651  2683 D BtGatt.AdvertiseManager: message : 0
,08-31 11:03:25.162  2651  2683 D BtGatt.AdvertiseManager: starting multi advertising
,08-31 11:03:25.174  2651  2680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-31 11:03:25.182  2651  2680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-31 11:03:25.183  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-31 11:03:25.184  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:03:25.186  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:03:25.189  3993  4039 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:03:25.189  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-31 11:03:25.189  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-31 11:03:25.189  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-31 11:03:25.189  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-31 11:03:25.190  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-31 11:03:25.190  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-31 11:03:25.191  3993  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-31 11:03:25.192  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-31 11:03:25.693  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-31 11:03:25.694  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:03:25.694  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:03:30.204  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-31 11:03:30.205  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
08-31 11:03:30.205  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:03:35.215  3993  4039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-31 11:03:35.216  3993  4039 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-31 11:03:35.216  3993  4039 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-31 11:03:35.216  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-31 11:03:35.218  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:03:35.218  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:03:35.219  3993  4039 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:03:40.229  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:40.230  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-31 11:03:40.230  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-31 11:03:40.230  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:03:40.235  3993  4041 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-31 11:03:40.235  3993  4041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:03:40.235  3993  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:03:40.237  3993  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 11:03:40.238  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:03:40.238  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:03:40.239  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:03:40.239  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:40.240  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:40.240  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:03:40.240  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:03:40.241  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:03:40.243  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:03:40.248  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:40.248  3993  4039 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:40.249  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:03:40.249  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-31 11:03:40.253  2651  2683 D BtGatt.AdvertiseManager: message : 1
08-31 11:03:40.255  2651  2683 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-31 11:03:40.277  2651  2680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-31 11:03:40.277  2651  2680 D BtGatt.GattService: Client app is not null!
08-31 11:03:40.280  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:03:40.282  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:03:40.283  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:03:40.283  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-31 11:03:40.284  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-31 11:03:40.285  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-31 11:03:40.291  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:03:40.292  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:03:40.293  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:03:40.296  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:03:40.300  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:03:40.301  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:03:40.301  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:03:40.302  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:40.302  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:40.302  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:40.306  3993  4039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:03:40.315  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:40.332  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:40.342  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:40.343  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:40.344  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:03:40.344  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:03:40.345  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:03:40.345  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:40.345  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:03:40.353  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:40.357  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:03:40.357  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:03:40.361  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:40.373  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:03:40.375  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 11:03:40.376  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:03:40.386  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 11:03:40.398  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 11:03:40.398  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:03:40.399  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:03:40.401  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:03:40.404  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:40.412  2651  2841 D BtGatt.GattService: registerClient() - UUID=bb1628e5-35c3-4383-9cf8-60ce221c7ea2
,08-31 11:03:40.414  2651  2680 D BtGatt.GattService: onClientRegistered() - UUID=bb1628e5-35c3-4383-9cf8-60ce221c7ea2, clientIf=5
,08-31 11:03:40.415  3993  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 11:03:40.418  2651  2664 D BtGatt.GattService: start scan with filters,
,08-31 11:03:40.424  2651  2695 D BtGatt.ScanManager: handling starting scan
,08-31 11:03:40.426  2651  2695 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
08-31 11:03:40.426  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:03:40.428  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:03:40.430  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:03:40.431  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:03:40.433  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:03:40.434  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:03:40.434  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:03:40.438  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:03:40.441  3993  4039 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:03:40.442  2651  2680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:03:40.443  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:40.444  2651  2695 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:03:40.453  2651  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:03:40.453  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:40.454  2651  2695 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:03:40.455  2651  2695 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:03:40.469  2651  2680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:03:40.469  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:40.479  2651  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:03:40.479  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:40.935  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-31 11:03:40.936  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:03:40.936  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:03:41.985  2651  2651 D BtGatt.ScanManager: awakened up at time 224371
,08-31 11:03:41.987  2651  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:03:42.026  2651  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
08-31 11:03:42.027  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:03:42.027  2651  2680 D BtGatt.GattService: current time is 224413853827
,08-31 11:03:42.029  2651  2680 D BtGatt.GattService: Batch record : [-126, -22, -96, 83, -39, -56, 1, -128, -60, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 8, -20, -87, 80, 117, 65, 0, 87, 45, 110, 28, -13, -4, 1, -128, -69, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 55, -106, -85, 0, 35, 97, 126, -92, 22, -56, 1, -128, -95, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 53, 33, -121, 80, 73, -44, 1, 0, -105, 10, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -103, -8, -17, 2, 2, -29, 21, 63, -64, -40, -128, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -92, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-31 11:03:42.033  2651  2680 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 8, -20, -87, 80, 117, 65]
,08-31 11:03:42.035  2651  2680 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 55, -106, -85]
,08-31 11:03:42.036  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-31 11:03:42.037  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-31 11:03:42.038  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-31 11:03:42.039  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-31 11:03:42.039  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -103, -8, -17, 2, 2, -29, 21, 63, -64, -40, -128, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-31 11:03:42.040  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-31 11:03:42.041  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-31 11:03:42.055  3993  3993 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 4], added - the peer count is 1
,08-31 11:03:42.056  3993  3993 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 4], added - the peer count is 2
,08-31 11:03:42.057  3993  3993 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 4], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,08-31 11:03:42.059  3993  3993 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 4], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: '',
,08-31 11:03:43.533  2651  2651 D BtGatt.ScanManager: awakened up at time 225918
,08-31 11:03:43.535  2651  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:03:43.587  2651  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-31 11:03:43.587  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:43.588  2651  2680 D BtGatt.GattService: current time is 225974095169
,08-31 11:03:43.589  2651  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -91, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-31 11:03:43.590  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-31 11:03:43.591  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-31 11:03:43.593  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-31 11:03:43.594  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-31 11:03:45.091  2651  2651 D BtGatt.ScanManager: awakened up at time 227477
,08-31 11:03:45.093  2651  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:03:45.146  2651  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-31 11:03:45.146  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:45.148  2651  2680 D BtGatt.GattService: current time is 227534688010
,08-31 11:03:45.149  2651  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -91, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-31 11:03:45.150  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-31 11:03:45.151  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-31 11:03:45.152  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-31 11:03:45.153  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-31 11:03:45.154  2651  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-31 11:03:45.441  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:03:45.442  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:45.442  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 11:03:45.442  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:45.443  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:03:45.443  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:03:45.443  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:03:45.444  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:03:45.444  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:03:45.445  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:03:45.446  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:03:45.448  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:45.450  2651  2664 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:03:45.453  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:03:45.454  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:45.454  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:03:45.455  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:03:45.455  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:03:45.455  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:03:45.459  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:03:45.459  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:03:45.460  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:03:45.460  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:03:45.462  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:45.463  3993  4039 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-31 11:03:45.466  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:03:45.466  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:03:45.466  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:03:45.469  2651  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:03:45.470  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:03:45.470  2651  2695 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:03:45.480  2651  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:03:45.481  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:45.481  2651  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:03:45.490  2651  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:03:45.490  2651  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:03:45.967  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:03:45.967  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:03:45.968  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:03:50.467  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:50.467  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.468  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:50.468  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
,08-31 11:03:50.468  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.469  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.469  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.469  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.473  3993  4039 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 11:03:50.475  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.475  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.475  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.476  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.476  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.476  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:50.477  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.477  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.477  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.481  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 11:03:50.481  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.481  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:50.482  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.482  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.482  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.483  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:50.483  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.483  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.484  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.485  3993  4039 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:03:50.486  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:50.486  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.486  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.486  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.486  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.486  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.486  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.486  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.486  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.487  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:03:50.487  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.487  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.487  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.487  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
,08-31 11:03:50.487  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.488  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.488  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.488  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.488  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.488  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:03:50.489  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:03:50.489  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:03:50.489  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:03:50.489  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.489  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.490  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.490  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.490  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.490  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.490  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.490  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.490  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.491  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 11:03:50.491  3993  4039 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:03:50.491  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:03:50.495  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:03:50.495  3993  4039 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:03:50.495  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:03:50.495  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:03:50.495  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:03:50.495  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:03:50.496  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-31 11:03:50.496  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:03:50.496  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:03:50.496  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:03:50.496  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:03:50.497  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:03:50.498  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:03:50.499  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:03:50.499  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:03:50.499  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:03:50.499  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:03:50.499  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:03:50.499  3993  4039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:03:50.500  3993  4039 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:03:50.500  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:03:50.500  3993  4039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:03:50.500  3993  4039 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:03:50.501  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:03:50.501  3993  4039 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 11:03:50.501  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:03:50.504  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:03:50.505  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:03:50.506  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-31 11:03:50.507  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:03:50.507  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:03:50.507  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:03:50.507  3993  4039 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:03:50.507  3993  4039 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:03:50.508  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.508  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.508  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.508  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 11:03:50.512  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list,
,08-31 11:03:50.512  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:03:50.512  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.513  3993  4043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 421)
08-31 11:03:50.513  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.513  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.513  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.514  3993  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 421
08-31 11:03:50.515  3993  4043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 421)
08-31 11:03:50.516  3993  4039 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:03:50.517  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.517  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.517  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.517  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.517  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.517  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:50.517  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.519  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.519  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.522  3993  4039 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:03:50.522  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.523  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:03:50.523  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.523  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.523  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.523  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:50.523  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.525  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.525  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.528  3993  4039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-31 11:03:50.528  3993  4039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:03:50.528  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-31 11:03:50.528  3993  4039 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:03:50.528  3993  4039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:03:50.528  3993  4039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:03:50.528  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:03:50.529  3993  4039 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:03:50.529  3993  4039 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:03:50.529  3993  4039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:03:50.529  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:03:50.529  3993  4039 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:03:50.529  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:03:50.529  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.529  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:50.530  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:50.530  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:50.530  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:03:50.530  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:50.530  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:03:50.530  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:03:50.534  3993  4039 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-31 11:03:50.536  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:03:50.542  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:03:50.544  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:03:50.544  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:03:50.545  3993  4039 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-31 11:03:50.545  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,08-31 11:03:50.547  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-31 11:03:50.547  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-31 11:03:50.547  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:03:50.547  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:03:50.547  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:03:50.548  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-31 11:03:50.549  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:03:50.549  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:03:50.549  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:03:50.549  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-31 11:03:50.549  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:03:50.549  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:03:50.552  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:03:50.552  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:03:50.553  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:03:50.553  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:03:50.554  3993  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:03:50.558  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:03:50.559  3993  4045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-31 11:03:50.559  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:03:50.559  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:03:50.561  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-31 11:03:50.561  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:03:50.561  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-31 11:03:50.561  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:03:50.561  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:03:50.562  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-31 11:03:50.562  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:50.564  2651  2662 D BtGatt.GattService: registerClient() - UUID=e7239259-c1d0-4749-9163-f7b857f72a96
,08-31 11:03:50.565  2651  2680 D BtGatt.GattService: onClientRegistered() - UUID=e7239259-c1d0-4749-9163-f7b857f72a96, clientIf=5
,08-31 11:03:50.566  3993  4004 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-31 11:03:50.570  2651  2683 D BtGatt.AdvertiseManager: message : 0
,08-31 11:03:50.573  2651  2683 D BtGatt.AdvertiseManager: starting multi advertising
,08-31 11:03:50.598  2651  2680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-31 11:03:50.605  2651  2680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-31 11:03:50.606  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-31 11:03:50.606  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:03:50.608  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:03:50.609  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-31 11:03:50.609  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-31 11:03:50.609  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-31 11:03:50.609  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-31 11:03:50.609  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-31 11:03:50.609  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-31 11:03:50.610  3993  4039 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:03:50.613  3993  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-31 11:03:50.614  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-31 11:03:51.115  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-31 11:03:51.115  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:03:51.116  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:03:52.971   871  1886 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-31 11:03:55.610  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:03:55.611  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:03:55.611  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-31 11:03:55.611  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:03:55.613  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-31 11:03:55.613  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:03:55.614  3993  4045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:03:55.614  3993  4045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:03:55.614  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:03:55.614  3993  4045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:03:55.615  3993  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 11:03:55.615  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:03:55.616  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:03:55.616  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:03:55.616  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:03:55.616  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:03:55.618  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:03:55.621  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:03:55.622  3993  4039 D BluetoothLeScanner: could not find callback wrapper
08-31 11:03:55.622  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:03:55.623  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-31 11:03:55.626  2651  2683 D BtGatt.AdvertiseManager: message : 1
,08-31 11:03:55.629  2651  2683 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-31 11:03:55.640  2651  2680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-31 11:03:55.640  2651  2680 D BtGatt.GattService: Client app is not null!
,08-31 11:03:55.642  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:03:55.644  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:03:55.644  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:03:55.644  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-31 11:03:55.645  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-31 11:03:55.645  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-31 11:03:55.647  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:03:55.648  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:03:55.648  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:03:55.649  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:03:55.652  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:03:55.652  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:03:55.653  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:03:55.654  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:03:55.654  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:03:55.655  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:03:56.156  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:04:00.656  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:04:00.657  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:04:00.657  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:04:00.658  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.658  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:00.658  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.659  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:04:00.659  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.659  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.660  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
,08-31 11:04:00.660  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:00.660  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:04:00.661  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:04:00.661  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:04:00.661  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:00.666  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-31 11:04:00.666  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:04:00.669  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:04:00.670  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:04:00.670  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:04:00.671  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:04:00.672  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:04:00.672  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:04:00.673  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:04:00.674  3993  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:04:00.673  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:04:00.675  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-31 11:04:00.675  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:04:00.675  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.675  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:04:00.675  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:04:00.675  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.675  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:04:00.675  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:04:00.676  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:04:00.676  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:04:00.676  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.676  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.677  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:04:00.677  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:04:00.678  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:04:00.678  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:04:00.678  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
,08-31 11:04:00.678  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:04:00.678  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.678  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.678  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.678  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:04:00.678  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:04:00.679  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:00.679  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.679  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.680  3993  4046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:04:00.680  3993  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:04:00.680  3993  4046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:04:00.681  3993  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:04:00.681  3993  4039 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:04:00.682  3993  4039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 11:04:00.682  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:04:00.682  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:04:00.682  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:04:00.682  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:04:00.683  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.683  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.683  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.683  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:04:00.683  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:04:00.683  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:00.683  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.683  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:00.696  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:04:00.696  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.696  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.697  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.697  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:00.697  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:04:00.698  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:00.698  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.698  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:00.700  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:04:00.700  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.701  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:00.701  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ebceb0 not in the list
08-31 11:04:00.701  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:00.701  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180d129 not in the list
08-31 11:04:00.702  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:00.702  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:00.702  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:00.705  3993  4039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:04:00.705  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-31 11:04:00.705  3993  4039 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:04:00.706  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:04:00.706  3993  4039 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:04:00.706  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 11:04:00.711  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:04:00.712  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-31 11:04:00.714  3993  4039 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-31 11:04:00.714  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:04:00.715  3993  4039 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:04:00.715  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:04:00.715  3993  4039 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-31 11:04:00.715  3993  4039 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 11:04:00.717  3993  4039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-31 11:04:00.718  3993  4039 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:04:00.719  3993  4039 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:04:00.719  3993  4039 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:04:00.719  3993  4039 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:04:00.719  3993  4039 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 11:04:00.720  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:04:00.720  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e935699 added. We now have 3 listener(s)
08-31 11:04:00.720  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:04:00.723  3993  4039 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 11:04:00.723   871  1432 D WifiService: setWifiEnabled: true pid=3993, uid=10000
08-31 11:04:00.723   871  1432 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:01.179  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:04:05.731  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:04:05.731  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c74ad5e added. We now have 4 listener(s)
08-31 11:04:05.732  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:04:05.748  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:05.748  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c74ad5e removed from the list
08-31 11:04:05.749  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:05.749  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:04:05.750  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:05.753  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:04:05.753  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f34a53f added. We now have 4 listener(s)
,08-31 11:04:05.753  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:04:05.757  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:05.757  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f34a53f removed from the list
08-31 11:04:05.758  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:05.758  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:05.758  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:05.761  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:04:05.761  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17dbe0c added. We now have 4 listener(s)
08-31 11:04:05.762  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:04:05.768   871  2389 D WifiService: setWifiEnabled: false pid=3993, uid=10000
,08-31 11:04:05.769   871  2389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:05.780  2651  2676 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 11:04:05.780  2651  2676 D BluetoothAdapterProperties: Setting state to 13
08-31 11:04:05.781  2651  2676 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 11:04:05.782  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:04:05.782  2651  2676 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:04:05.786  2651  2676 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:05.789  2651  2651 D BluetoothMapService: onReceive
,08-31 11:04:05.789  2651  2651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:04:05.791  2651  2651 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:04:05.792  2651  2651 D BluetoothMapService: MAP Service closeService in
08-31 11:04:05.792  2651  2651 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 11:04:05.792  2651  2651 D ObexServerSockets0: shutdown(block = true)
08-31 11:04:05.793  1481  1481 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:04:05.794  2651  2842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 11:04:05.795  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:05.795  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:05.796   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:04:05.796   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 11:04:05.796   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:04:05.796   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:04:05.799  2651  2651 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:04:05.800  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.801  2651  2843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 11:04:05.802  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:05.802  2651  2829 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:04:05.803  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:04:05.803  2651  2651 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 11:04:05.804  2651  2651 I BtOppRfcommListener: stopping Accept Thread
08-31 11:04:05.805  2651  3569 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:04:05.806  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.806  2651  3569 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:04:05.810  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.813   871  1313 E native  : do suspend true
,08-31 11:04:05.816  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:05.817  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:05.818  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.818  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:05.820   871   884 I ActivityManager: Start proc 4051:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 11:04:05.821  2651  2680 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:04:05.822  2651  2676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 11:04:05.824  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:05.824  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:05.825  2651  2651 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:04:05.825  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:05.825  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:05.825   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:04:05.825   871  1888 D DhcpClient: Clearing IP address
08-31 11:04:05.828   371   869 D CommandListener: Setting iface cfg
08-31 11:04:05.829  1373  1384 D BluetoothHeadset: Proxy object disconnected
,08-31 11:04:05.829  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-31 11:04:05.829   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:05.829   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:05.830  1932  1955 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:05.830   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:05.830  2651  2651 D A2dpService: Received stop request...Stopping profile...
08-31 11:04:05.831  2651  2835 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:04:05.832  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.833   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:04:05.833   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-31 11:04:05.833   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-31 11:04:05.834   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:04:05.834   871  1313 E native  : do suspend true
08-31 11:04:05.835   871  1889 D DhcpClient: Receive thread stopped
,08-31 11:04:05.831  1534  2225 V NativeCrypto: Read error: ssl=0x9b779a00: I/O error during system call, Connection timed out
,08-31 11:04:05.839  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:05.839  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:05.839  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-31 11:04:05.839   871   871 D BluetoothA2dp: Proxy object disconnected
08-31 11:04:05.840  2651  2651 D HidService: Received stop request...Stopping profile...
08-31 11:04:05.840  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.840  2651  2651 D HidService: Stopping Bluetooth HidService
,08-31 11:04:05.840  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:05.840   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 11:04:05.840   394   394 E Parcel  : Reading a NULL string not supported here.
08-31 11:04:05.841  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-31 11:04:05.841  1373  1373 D HidProfile: Bluetooth service disconnected
08-31 11:04:05.841  2651  2651 D HealthService: Received stop request...Stopping profile...
08-31 11:04:05.842  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:05.842  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:05.842  2651  2651 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:05.842  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.842  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:05.842  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.843  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.843  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:05.845  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:05.845  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:05.846  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:04:05.846  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:04:05.846  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:05.846  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:05.846  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 11:04:05.847  2651  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:04:05.847  2651  2680 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 11:04:05.847  2651  2651 D PanService: Received stop request...Stopping profile...
08-31 11:04:05.847  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.847  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:05.849  2651  2651 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:04:05.849  2651  2651 D BluetoothMapService: stop()
08-31 11:04:05.849  2651  2651 D BluetoothMapAppObserver: deinitObservers()
08-31 11:04:05.849  2651  2651 D BluetoothMapAppObserver: removeReceiver()
08-31 11:04:05.851  2651  2651 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:05.851  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.851  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:05.851  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.852  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.852  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.852  2651  2802 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:04:05.852  2651  2802 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:04:05.852  2651  2802 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:04:05.852  2651  2802 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:04:05.852  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:04:05.852  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:04:05.852  2651  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.852  2651  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:05.852  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.853  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:04:05.853  2651  2680 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-31 11:04:05.853  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:04:05.854  2651  2651 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:05.854  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.854  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:05.854  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.854  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:04:05.854  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:04:05.855  2651  2651 D BluetoothMapService: MAP Service closeService in
,08-31 11:04:05.855  2651  2651 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:05.855  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:05.855  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:05.855  2651  2651 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:05.855  2651  2676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 11:04:05.855  2651  2676 D BluetoothAdapterProperties: Setting state to 15
08-31 11:04:05.855  2651  2676 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:04:05.856  2651  2651 D BluetoothMapService: cleanup()
08-31 11:04:05.856  2651  2651 D BluetoothMapService: MAP Service closeService in
08-31 11:04:05.856  2651  2676 I BluetoothAdapterState: Entering BleOnState
,08-31 11:04:05.859  1373  2032 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:05.859   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:04:05.859   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:05.860  1373  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:04:05.860   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:05.860  1373  2025 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:04:05.861  1932  2227 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:05.861  1373  1387 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:04:05.861  1534  2225 V NativeCrypto: SSL shutdown failed: ssl=0x9b779a00: I/O error during system call, Broken pipe
08-31 11:04:05.862   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:05.862  1373  2032 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:04:05.863  1373  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:04:05.864  2651  2676 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:04:05.864  2651  2676 D BluetoothAdapterProperties: Setting state to 16
08-31 11:04:05.864  2651  2676 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 11:04:05.865  2651  2676 D BluetoothAdapterProperties: onBleDisable
08-31 11:04:05.865  2651  2676 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:04:05.866  2651  2677 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 11:04:05.868  2651  2680 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:04:05.868  2651  2802 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 11:04:05.868  2651  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:05.869  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:05.869  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:05.872  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:05.872  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:05.873  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:05.873  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:05.874  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.875  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.876  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.879   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
08-31 11:04:05.891  4051  4051 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 11:04:05.897   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 11:04:05.897   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:04:05.898   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 11:04:05.898   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:04:05.900   871   888 D Tethering: MasterInitialState.processMessage what=3
08-31 11:04:05.901  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.902  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.903  3571  3571 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d71b99d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-31 11:04:05.905  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:05.909  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:04:05.913  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:05.916   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c99483a:true
08-31 11:04:05.925   871   882 I ActivityManager: Start proc 4068:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 11:04:05.934  4051  4051 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 11:04:05.935  4051  4051 D BluetoothMap: Create BluetoothMap proxy object
,08-31 11:04:05.940  4051  4051 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 11:04:05.945  4051  4051 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:04:05.950   871   882 I ActivityManager: Killing 3134:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-31 11:04:05.970   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-31 11:04:05.970  4068  4068 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 11:04:05.976   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:05.994   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:05.995   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:04:05.999  2203  2352 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:04:06.004  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:06.004  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:06.004  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:06.004  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:06.006  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:06.006  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:06.008  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:06.008  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:06.014  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:06.014  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:06.014  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:06.014  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:06.071  2651  2680 I bt_hci  : shut_down
,08-31 11:04:06.071  2651  2697 D bt_hwcfg: hw_epilog_process
,08-31 11:04:06.079  2651  2697 I bt_vendor: low_power_mode_cb
,08-31 11:04:06.099  2651  2697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 11:04:06.099  2651  2697 I bt_vendor: epilog_cb
08-31 11:04:06.099  2651  2697 I bt_hci  : epilog_finished_callback
,08-31 11:04:06.103  2651  2680 I bt_hci_h4: hal_close
,08-31 11:04:06.104  2651  2680 I bt_userial_vendor: device fd = 51 close
,08-31 11:04:06.129  4068  4068 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:04:06.129  4068  4068 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.129  4068  4068 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.129  4068  4068 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.129  4068  4068 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.129  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.130  4068  4068 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.130  4068  4068 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.130  4068  4068 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:04:06.130  4068  4068 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:04:06.134  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:04:06.144  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:06.156  4051  4051 D DockEventReceiver: finishStartingService: stopping service
08-31 11:04:06.163   871  1949 I ActivityManager: Killing 3571:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 11:04:06.242  2651  2677 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:04:06.244  2651  2676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:04:06.245  2651  2651 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:04:06.245  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 11:04:06.245  2651  2676 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-31 11:04:06.246  2651  2651 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:04:06.246  2651  2651 D BtGatt.GattService: stop()
08-31 11:04:06.246  2651  2651 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:04:06.249  1756  1756 D SystemUpdateService: onCreate
,08-31 11:04:06.250  2651  2651 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:06.250  2651  2651 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:06.250  2651  2651 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:06.251  2651  2651 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:04:06.251  2651  2676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 11:04:06.251  2651  2676 D BluetoothAdapterProperties: Setting state to 10
08-31 11:04:06.251  2651  2676 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 11:04:06.258  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 11:04:06.258  2651  2676 I BluetoothAdapterState: Entering OffState
08-31 11:04:06.258   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 11:04:06.267  2651  2651 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:04:06.267  2651  2651 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 11:04:06.267  2651  2651 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:04:06.268  2651  2677 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:04:06.271  2651  2677 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:04:06.276  1756  4102 I SystemUpdateService: active receiver: enabled
,08-31 11:04:06.277  2651  2651 I art     : System.exit called, status: 0
,08-31 11:04:06.277  2651  2651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:04:06.280  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:04:06.294  1756  2451 I iu.UploadsManager: num queued entries: 0
,08-31 11:04:06.295  1756  2451 I iu.UploadsManager: num updated entries: 0
,08-31 11:04:06.302  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:04:06.303  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:04:06.310  1756  4102 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:04:06.315  1756  2451 I iu.SyncManager: NEXT; no task
,08-31 11:04:06.316  1756  4102 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:04:06.316  1756  4102 I SystemUpdateService: now status is 0 (complete)
08-31 11:04:06.316  1756  4102 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:04:06.317  1756  4102 I SystemUpdateService: file has been verified
,08-31 11:04:06.318  1756  4102 I SystemUpdateService: OTA package size = 12249756
,08-31 11:04:06.325  1756  4102 I SystemUpdateService: showing system update notification
,08-31 11:04:06.334   871  2010 I ActivityManager: Start proc 4105:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 11:04:06.346   871  2010 I ActivityManager: Process com.android.bluetooth (pid 2651) has died
,08-31 11:04:06.353  1756  1756 D SystemUpdateService: onDestroy
,08-31 11:04:06.397  4105  4105 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 11:04:06.399  4105  4105 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:06.421  4105  4105 D SprintDMHelper: simOperator: 
,08-31 11:04:06.421  4105  4105 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:04:06.458   871   881 I ActivityManager: Start proc 4118:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 11:04:06.459   871   881 I ActivityManager: Killing 3614:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 11:04:06.474  4068  4094 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:04:06.484   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b6f7845:true
,08-31 11:04:06.619   871  3896 I ActivityManager: Start proc 4135:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 11:04:06.622  3192  4134 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 11:04:06.652  4135  4135 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 11:04:06.700  4135  4135 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:04:06.700  4135  4135 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:04:06.700  4135  4135 I GAv4    :   adb logcat -s GAv4
,08-31 11:04:06.713  4135  4135 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:04:06.719  4135  4135 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:04:06.748  4135  4152 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:04:06.857  4135  4135 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 11:04:06.902  4135  4135 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 11:04:06.914  4135  4135 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9293-9296)
,08-31 11:04:06.915  4135  4135 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:04:06.924  4135  4135 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d59440d}
,08-31 11:04:06.925  4135  4135 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:04:06.925  4135  4135 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:04:06.934  4135  4135 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 11:04:06.936  4135  4135 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:04:06.953  4135  4135 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 11:04:06.969  4135  4135 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:04:06.969  4135  4135 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:04:06.969  4135  4135 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:04:06.969  4135  4135 I Adreno  : Build Date                       : 10/20/15
08-31 11:04:06.969  4135  4135 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:04:06.969  4135  4135 I Adreno  : Local Branch                     : M14
08-31 11:04:06.969  4135  4135 I Adreno  : Remote Branch                    : 
08-31 11:04:06.969  4135  4135 I Adreno  : Remote Branch                    : 
08-31 11:04:06.969  4135  4135 I Adreno  : Reconstruct Branch               : 
,08-31 11:04:07.039  4135  4135 I NSApplication: Starting up...
,08-31 11:04:07.051  4135  4181 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 11:04:07.085   871   882 I ActivityManager: Start proc 4186:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 11:04:07.087   871   882 I ActivityManager: Killing 1703:android.process.acore/u0a5 (adj 15): empty #17
,08-31 11:04:07.185  4186  4186 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 11:04:07.404   871  3896 I ActivityManager: Killing 3808:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 11:04:07.496   871   882 I ActivityManager: Start proc 4200:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 11:04:07.555  4200  4200 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 11:04:07.609  4200  4200 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 11:04:07.663   871   882 I ActivityManager: Killing 3823:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 11:04:10.806   871  1926 D WifiService: setWifiEnabled: true pid=3993, uid=10000
,08-31 11:04:10.806   871  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:10.824   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:04:10.832  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:10.832  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:10.833  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:10.833  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:10.837  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:10.837  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:10.837  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:10.838  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:10.841  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:10.841  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:10.841  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:10.842  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:10.856   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-31 11:04:10.857   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 11:04:10.858   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 11:04:10.859   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:04:10.859   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 11:04:10.859   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 11:04:10.859   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 11:04:10.873   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:04:10.873   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:10.875   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:10.885   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '138 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 138 Failed to set address (No such device)'
,08-31 11:04:10.885   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:04:10.886   871  1313 E native  : do suspend true
,08-31 11:04:10.898   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:04:10.898   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:04:10.916   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:11.679   871  3896 I ActivityManager: Killing 2261:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 11:04:12.301   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:12.838  1869  1959 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-31 11:04:12.839  1869  1959 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-31 11:04:12.881  1534  1534 I ConfigService: onCreate
,08-31 11:04:13.947   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.69 rxSuccessRate=4.91 delta 1000 -> 1000
,08-31 11:04:13.951   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 11:04:13.951   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:04:13.971   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:04:14.016   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:04:14.018  1481  1481 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:04:14.479  1481  1481 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:04:14.532  1481  1481 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:04:14.532  1481  1481 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:04:14.541   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:14.551   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:04:14.551   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:04:14.551   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:04:14.566   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:04:14.575   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:14.576   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 11:04:14.583   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:04:14.618   871  4236 D DhcpClient: Receive thread started
,08-31 11:04:14.717   871  1313 E native  : do suspend false
,08-31 11:04:14.741   871  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:04:14.774   871  4236 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172565, domain null
,08-31 11:04:14.776   871  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172565 seconds
,08-31 11:04:14.779   871  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:04:14.802   871  4236 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:04:14.803   871  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:04:14.809   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:14.820   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-31 11:04:14.822   871  1888 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:04:14.823   871  1313 E native  : do suspend true
,08-31 11:04:14.855   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:04:14.858   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:04:14.860   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:04:14.862   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 11:04:14.873   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:04:14.938   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 11:04:14.939   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 11:04:14.943   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 11:04:14.945   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 11:04:14.947   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 11:04:14.964   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:04:14.968   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-31 11:04:14.968   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-31 11:04:14.969   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-31 11:04:14.969   871  1315 D ConnectivityService:    accepting network in place of null
08-31 11:04:14.969   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 11:04:14.970   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 11:04:14.971   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:04:15.004   871  4235 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257389, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 11:04:15.020   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:15.052   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:15.059   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 11:04:15.059   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:15.061   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 11:04:15.068   871   888 D Tethering: MasterInitialState.processMessage what=3
08-31 11:04:15.071  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:15.071  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:15.072  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.072  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:15.075  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:15.075  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:15.075  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:15.075  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:15.078  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:15.078  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:04:15.078  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.078  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:15.094  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:04:15.100  1756  1756 D SystemUpdateService: onCreate
,08-31 11:04:15.104  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:04:15.127  1756  4246 I SystemUpdateService: active receiver: enabled
,08-31 11:04:15.142   871  4234 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,08-31 11:04:15.142  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 11:04:15.151  1756  4246 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:04:15.152  1756  2451 I iu.UploadsManager: num queued entries: 0
08-31 11:04:15.152  1756  2451 I iu.UploadsManager: num updated entries: 0
,08-31 11:04:15.154  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:04:15.156  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:04:15.158  4105  4105 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:15.163  1756  4246 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 11:04:15.163  1756  4246 I SystemUpdateService: now status is 0 (complete)
08-31 11:04:15.164  1756  4246 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:04:15.164  1756  4246 I SystemUpdateService: file has been verified
,08-31 11:04:15.164  1756  4246 I SystemUpdateService: OTA package size = 12249756
08-31 11:04:15.155  1756  2451 I iu.SyncManager: NEXT; no task
,08-31 11:04:15.165  1756  4249 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 11:04:15.165  1756  4249 W BaseAppContext: Using Auth Proxy for data requests.
08-31 11:04:15.166  1756  4249 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 11:04:15.168  4105  4105 D SprintDMHelper: simOperator: 
08-31 11:04:15.168  4105  4105 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:04:15.187  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:04:15.189  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:04:15.193  1756  4246 I SystemUpdateService: showing system update notification
,08-31 11:04:15.267  1756  1756 D SystemUpdateService: onDestroy
,08-31 11:04:15.277  1534  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:04:15.277  1534  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 11:04:15.277  1534  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:04:15.278  1534  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:04:15.295  1756  4249 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-31 11:04:15.484   871  4234 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:04:15 GMT], X-Android-Received-Millis=[1472634255482], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472634255363]}
,08-31 11:04:15.489   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 11:04:15.490   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-31 11:04:15.491   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:04:15.497   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:04:15.535  3192  4253 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 11:04:15.819   871  3896 D WifiService: setWifiEnabled: false pid=3993, uid=10000
,08-31 11:04:15.819   871  3896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:15.845  1481  1481 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:04:15.852   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 11:04:15.852   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 11:04:15.853   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:04:15.853   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:04:15.872   871  1313 E native  : do suspend true
,08-31 11:04:15.878   871  1888 D DhcpClient: Clearing IP address
08-31 11:04:15.878   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:04:15.881   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:15.889  1534  4260 V NativeCrypto: Read error: ssl=0x9a71a000: I/O error during system call, Connection timed out
,08-31 11:04:15.892  1534  4260 V NativeCrypto: SSL shutdown failed: ssl=0x9a71a000: I/O error during system call, Broken pipe
08-31 11:04:15.897   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:04:15.897   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-31 11:04:15.903   394   394 E Parcel  : Reading a NULL string not supported here.
,08-31 11:04:15.908   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-31 11:04:15.909   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:04:15.909   871  1313 E native  : do suspend true
08-31 11:04:15.909   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 11:04:15.911   871  4236 D DhcpClient: Receive thread stopped
,08-31 11:04:15.952   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:15.985   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:15.987   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 11:04:15.987   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:15.987   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:04:15.990   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:04:15.994  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:15.994  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:15.994  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:15.994  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:15.995  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:15.995  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:15.996  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.996  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:15.997  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:15.997  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:15.997  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:15.997  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:16.010   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:16.018  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:04:16.025  1756  1756 D SystemUpdateService: onCreate
,08-31 11:04:16.028  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 11:04:16.033   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:16.037  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:16.037  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:16.037  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:16.037  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:16.038  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:16.038  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:16.038  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:16.038  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:16.039   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:04:16.039  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:16.039  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:16.039  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:16.039  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:16.042  2203  2352 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:04:16.047  1756  4268 I SystemUpdateService: active receiver: enabled
,08-31 11:04:16.049  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:04:16.054  1756  2451 I iu.UploadsManager: num queued entries: 0
,08-31 11:04:16.054  1756  2451 I iu.UploadsManager: num updated entries: 0
08-31 11:04:16.055  1756  2451 I iu.SyncManager: NEXT; no task
,08-31 11:04:16.055  1756  4268 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:04:16.057  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:04:16.058  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:04:16.061  4105  4105 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:16.062  1756  4268 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:04:16.063  1756  4268 I SystemUpdateService: now status is 0 (complete)
08-31 11:04:16.063  1756  4268 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:04:16.063  1756  4268 I SystemUpdateService: file has been verified
,08-31 11:04:16.063  1756  4268 I SystemUpdateService: OTA package size = 12249756
08-31 11:04:16.065  4105  4105 D SprintDMHelper: simOperator: 
,08-31 11:04:16.065  4105  4105 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:04:16.078  3192  4272 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 11:04:16.091  1756  4268 I SystemUpdateService: showing system update notification
,08-31 11:04:16.103   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-31 11:04:16.104   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:04:16.105   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 11:04:16.110  1756  1756 D SystemUpdateService: onDestroy
,08-31 11:04:17.946  1534  1534 I ConfigService: onDestroy
,08-31 11:04:20.864   871   888 I ActivityManager: Start proc 4278:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 11:04:20.968  4278  4278 D AdapterServiceConfig: Adding HeadsetService
,08-31 11:04:20.968  4278  4278 D AdapterServiceConfig: Adding A2dpService
,08-31 11:04:20.968  4278  4278 D AdapterServiceConfig: Adding HidService
08-31 11:04:20.969  4278  4278 D AdapterServiceConfig: Adding HealthService
08-31 11:04:20.969  4278  4278 D AdapterServiceConfig: Adding PanService
08-31 11:04:20.969  4278  4278 D AdapterServiceConfig: Adding GattService
,08-31 11:04:20.969  4278  4278 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:04:20.985   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a7ec3c8:true
,08-31 11:04:20.986  4278  4278 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:04:20.994  4278  4278 I bt_bluedroid: init
,08-31 11:04:20.995  4278  4290 I BluetoothAdapterState: Entering OffState
,08-31 11:04:21.001  4278  4291 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 11:04:21.001  4278  4291 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:04:21.001  4278  4291 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:04:21.002  4278  4291 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:04:21.004  4278  4278 I bt_bluedroid: get_profile_interface socket
,08-31 11:04:21.006  4278  4278 I bt_bluedroid: get_profile_interface sdp
,08-31 11:04:21.009  4278  4294 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 11:04:21.011  4278  4294 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:04:21.012  4278  4289 I bt_bluedroid: config_hci_snoop_log
08-31 11:04:21.015   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:04:21.023  4278  4290 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:04:21.024  4278  4290 D BluetoothAdapterProperties: Setting state to 14
08-31 11:04:21.025  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:04:21.029  4278  4290 D BluetoothBondStateMachine: make
,08-31 11:04:21.037  4278  4295 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:04:21.042  4278  4290 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:21.043  4278  4278 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:04:21.047  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:21.048  4278  4278 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:04:21.049  4278  4278 D BtGatt.GattService: Received start request. Starting profile...
,08-31 11:04:21.049  4278  4278 D BtGatt.GattService: start()
08-31 11:04:21.049  4278  4278 I bt_bluedroid: get_profile_interface gatt
08-31 11:04:21.050  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:21.050  4278  4278 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:04:21.063  4278  4278 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:21.063  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:21.063  4278  4278 V BluetoothAdapterState: isBleTurningOn()=true
08-31 11:04:21.063  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:21.064  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 11:04:21.064  4278  4290 I bt_bluedroid: enable
08-31 11:04:21.065  4278  4291 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:04:21.067  4278  4291 I bt_hci  : start_up
,08-31 11:04:21.091  4278  4291 I bt_vendor: alloc value 0xb3a79189
,08-31 11:04:21.092  4278  4291 I bt_vendor: init
08-31 11:04:21.092  4278  4291 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-31 11:04:21.092  4278  4291 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:04:21.202  4278  4291 D bt_hci  : start_up starting async portion
,08-31 11:04:21.203  4278  4298 I bt_hci  : event_finish_startup
08-31 11:04:21.203  4278  4298 I bt_hci_h4: hal_open
,08-31 11:04:21.204  4278  4298 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:04:21.213  4278  4298 I bt_userial_vendor: device fd = 51 open
,08-31 11:04:21.244  4278  4298 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:04:21.276  4278  4298 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:04:21.277  4278  4298 D bt_hwcfg: Target name = [BCM4354A2]
08-31 11:04:21.278  4278  4298 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:04:21.932  4278  4298 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:04:21.934  4278  4298 D bt_hwcfg: Settlement delay -- 100 ms
08-31 11:04:21.934  4278  4298 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:04:22.051  4278  4298 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:04:22.052  4278  4298 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:04:22.081  4278  4298 I bt_hwcfg: vendor lib fwcfg completed
,08-31 11:04:22.082  4278  4298 I bt_vendor: firmware callback
08-31 11:04:22.082  4278  4298 I bt_hci  : firmware_config_callback
,08-31 11:04:22.093  4278  4300 I bt_btu  : btu_task pending for preload complete event
,08-31 11:04:22.093  4278  4300 I bt_btu_task: Bluetooth chip preload is complete
08-31 11:04:22.094  4278  4300 I bt_btu  : btu_task received preload complete event
,08-31 11:04:22.104  4278  4300 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:04:22.104  4278  4300 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:04:22.104  4278  4300 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 11:04:22.105  4278  4300 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:04:22.105  4278  4300 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:04:22.105  4278  4300 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:04:22.106  4278  4300 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:04:22.106  4278  4300 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:04:22.106  4278  4300 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 11:04:22.106  4278  4300 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:04:22.106  4278  4300 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:04:22.107  4278  4300 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:04:22.107  4278  4300 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:04:22.107  4278  4300 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:04:22.108  4278  4300 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:04:22.242  4278  4300 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,08-31 11:04:22.243  4278  4300 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-31 11:04:22.253  4278  4294 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-31 11:04:22.255  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 11:04:22.256  4278  4294 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:04:22.260  4278  4294 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:04:22.264  4278  4294 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:04:22.265  4278  4294 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:04:22.265  4278  4294 D bt_hci  : do_postload posting postload work item
08-31 11:04:22.265  4278  4298 I bt_hci  : event_postload
08-31 11:04:22.265  4278  4298 I bt_vendor: sco_config_cb
,08-31 11:04:22.265  4278  4298 I bt_hci  : sco_config_callback postload finished.
08-31 11:04:22.269  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.271  4278  4298 I bt_vendor: low_power_mode_cb
,08-31 11:04:22.273  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.273  4278  4294 D bt_bte_conf: Device ID record 1 : primary
,08-31 11:04:22.273  4278  4294 D bt_bte_conf:   vendorId            = 000f
08-31 11:04:22.274  4278  4294 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 11:04:22.274  4278  4294 D bt_bte_conf:   product             = 1200
,08-31 11:04:22.275  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.274  4278  4294 D bt_bte_conf:   version             = 1436
,08-31 11:04:22.276  4278  4294 D bt_bte_conf:   clientExecutableURL = 
08-31 11:04:22.276  4278  4294 D bt_bte_conf:   serviceDescription  = 
,08-31 11:04:22.276  4278  4294 D bt_bte_conf:   documentationURL    = 
08-31 11:04:22.278  4278  4294 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:04:22.278  4278  4291 D bt_stack_manager: event_start_up_stack finished
08-31 11:04:22.280  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 11:04:22.280  4278  4290 D BluetoothAdapterProperties: Setting state to 15
08-31 11:04:22.281  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 11:04:22.283  4278  4290 I BluetoothAdapterState: Entering BleOnState
,08-31 11:04:22.286  4278  4290 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 11:04:22.286  4278  4290 D BluetoothAdapterProperties: Setting state to 11
08-31 11:04:22.286  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:04:22.291  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:22.292  4278  4278 D HeadsetService: Received start request. Starting profile...
,08-31 11:04:22.298  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:22.299  4278  4278 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:04:22.300  4278  4278 D HeadsetStateMachine: make
,08-31 11:04:22.301  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:22.304  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:22.310  4278  4290 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:22.310  4278  4278 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:04:22.310  4278  4278 I bt_bluedroid: get_profile_interface handsfree
08-31 11:04:22.311  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 11:04:22.311  4278  4294 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:04:22.314  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:22.315  4278  4278 D A2dpService: Received start request. Starting profile...
,08-31 11:04:22.316  4278  4278 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:04:22.316  4278  4278 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:04:22.321  4278  4278 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:04:22.321  4278  4278 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:04:22.321  4278  4278 D A2dpStateMachine: make
,08-31 11:04:22.323  4278  4278 I bt_bluedroid: get_profile_interface a2dp
08-31 11:04:22.323  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 11:04:22.327  4278  4308 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:04:22.327  4278  4278 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:04:22.328  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:22.329  4278  4278 D HidService: Received start request. Starting profile...
08-31 11:04:22.329  4051  4051 D BluetoothInputDevice: Proxy object connected
08-31 11:04:22.329  4278  4278 I bt_bluedroid: get_profile_interface hidhost
08-31 11:04:22.330  4278  4278 D HidService: setHidService(): set to: null
08-31 11:04:22.330  4278  4294 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
08-31 11:04:22.330  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 11:04:22.331  4278  4278 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:04:22.331  4051  4051 D HidProfile: Bluetooth service connected
08-31 11:04:22.331  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:22.332  4278  4278 D HealthService: Received start request. Starting profile...
08-31 11:04:22.332  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:22.333  4278  4278 I bt_bluedroid: get_profile_interface health
,08-31 11:04:22.333  4278  4278 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:04:22.334  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
08-31 11:04:22.335  4278  4278 D PanService: Received start request. Starting profile...
08-31 11:04:22.335  4051  4051 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:04:22.335  4278  4278 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:04:22.335  4278  4278 I bt_bluedroid: get_profile_interface pan
08-31 11:04:22.336  4278  4294 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:04:22.336  4051  4051 D PanProfile: Bluetooth service connected
,08-31 11:04:22.342  4278  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:22.344  4051  4051 D BluetoothMap: Proxy object connected
,08-31 11:04:22.344  4278  4278 D BluetoothMapService: Received start request. Starting profile...
08-31 11:04:22.344  4278  4278 D BluetoothMapService: start()
08-31 11:04:22.344  4051  4051 D MapProfile: Bluetooth service connected
08-31 11:04:22.344  4051  4051 D BluetoothMap: getConnectedDevices()
08-31 11:04:22.345  4051  4051 D BluetoothMap: Bluetooth is Not enabled
,08-31 11:04:22.347  4278  4278 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 11:04:22.348  4278  4278 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 11:04:22.348  4278  4278 D BluetoothMapAppObserver: createReceiver()
08-31 11:04:22.350  4278  4278 D BluetoothMapAppObserver: initObservers()
08-31 11:04:22.350  4278  4278 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:04:22.361  4278  4278 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:22.361  4278  4278 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:22.362  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:22.362  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:22.362  4278  4306 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:04:22.364  4278  4278 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:22.364  4278  4278 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:22.364  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:22.365  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:22.367  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:22.368  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:22.368  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 11:04:22.368  4278  4290 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:04:22.368  4278  4290 D BluetoothAdapterProperties: State =  11
08-31 11:04:22.369  4278  4290 D BluetoothAdapterProperties: Setting state to 12
08-31 11:04:22.370  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:04:22.371  4051  4061 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:04:22.372  4278  4290 I BluetoothAdapterState: Entering OnState
08-31 11:04:22.372  4051  4062 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:04:22.372  4278  4294 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:04:22.372  4278  4294 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:04:22.372  1373  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:04:22.374   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:04:22.375   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:22.375  4051  4061 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:04:22.375   871   871 D BluetoothA2dp: Proxy object connected
08-31 11:04:22.376  1373  2032 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:22.377  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:22.377  1373  1373 D BluetoothMap: Proxy object connected
08-31 11:04:22.377  1373  1373 D MapProfile: Bluetooth service connected
08-31 11:04:22.377  1373  1373 D BluetoothMap: getConnectedDevices()
,08-31 11:04:22.378   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:22.378  1373  1384 D BluetoothPan: onBluetoothStateChange on: true
,08-31 11:04:22.379  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:22.380  1932  2073 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:22.381  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:04:22.381  1373  1373 D PanProfile: Bluetooth service connected
08-31 11:04:22.381  4278  4278 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 11:04:22.381  4278  4278 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 11:04:22.382  4051  4062 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:04:22.383  4278  4278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:04:22.384  1373  2025 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:04:22.385  4278  4278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:22.386   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:22.387  4278  4278 D ObexServerSockets: Succeed to create listening sockets 
08-31 11:04:22.387  1373  2032 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:04:22.387  4278  4278 D ObexServerSockets0: startAccept()
08-31 11:04:22.387  4278  4278 D ObexServerSockets0: prepareForNewConnect()
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:22.387  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:22.388  1373  1373 D BluetoothInputDevice: Proxy object connected
,08-31 11:04:22.389  1373  1373 D HidProfile: Bluetooth service connected
08-31 11:04:22.389  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:22.390  1373  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:04:22.392  4278  4278 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 11:04:22.392  4278  4278 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 11:04:22.392  1373  1373 D BluetoothA2dp: Proxy object connected
08-31 11:04:22.392  4278  4317 D ObexServerSockets0: Accepting socket connection...
08-31 11:04:22.392  4278  4318 D ObexServerSockets0: Accepting socket connection...
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:22.393  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:22.394   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:04:22.394  4278  4278 D BluetoothMapService: onReceive
,08-31 11:04:22.394  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:22.394  4278  4278 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:04:22.394  4278  4278 D BluetoothMapService: STATE_ON
08-31 11:04:22.396  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.397  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.398  4051  4051 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 11:04:22.398  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:22.401  4051  4051 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 11:04:22.407  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:04:22.410  4051  4051 D BluetoothA2dp: Proxy object connected
,08-31 11:04:22.413  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:04:22.418  4051  4051 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:04:22.421  4051  4051 D BluetoothPbap: Proxy object connected
,08-31 11:04:22.421  1373  1373 D BluetoothPbap: Proxy object connected
08-31 11:04:22.421  1373  1373 D PbapServerProfile: Bluetooth service connected
08-31 11:04:22.421  4278  4278 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:04:22.421  4051  4051 D PbapServerProfile: Bluetooth service connected
08-31 11:04:22.421  4278  4278 D ObexServerSockets0: prepareForNewConnect()
,08-31 11:04:22.430  4278  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:22.439  4278  4326 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:22.440  4278  4326 I BtOppRfcommListener: Accept thread started.
,08-31 11:04:22.476  1373  1384 D BluetoothHeadset: Proxy object connected
,08-31 11:04:22.476  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-31 11:04:22.476   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:22.476   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:22.477  1932  1955 D BluetoothHeadset: Proxy object connected
08-31 11:04:22.477   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:22.478   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:04:22.482  1932  1943 D BluetoothHeadset: Proxy object connected
,08-31 11:04:22.487   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:04:22.505  4051  4062 D BluetoothHeadset: Proxy object connected
,08-31 11:04:22.506  4051  4051 D HeadsetProfile: Bluetooth service connected
,08-31 11:04:22.969   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-31 11:04:25.836  4278  4290 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 11:04:25.837  4278  4290 D BluetoothAdapterProperties: Setting state to 13
,08-31 11:04:25.837  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:04:25.839  4278  4290 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:04:25.841  4278  4290 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:25.846  4278  4294 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:04:25.846  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 11:04:25.851  4278  4278 D BluetoothMapService: onReceive
,08-31 11:04:25.851  4278  4278 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:04:25.851  4278  4278 D BluetoothMapService: STATE_TURNING_OFF
,08-31 11:04:25.852  4278  4278 D BluetoothMapService: MAP Service closeService in
,08-31 11:04:25.852  4278  4278 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 11:04:25.853  4278  4278 D ObexServerSockets0: shutdown(block = true)
08-31 11:04:25.853  4278  4317 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 11:04:25.856  4278  4278 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 11:04:25.857  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:25.857  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:25.857  4278  4318 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 11:04:25.858  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:25.858  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:25.860  4278  4303 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:04:25.861  4278  4278 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:04:25.861  4278  4278 I BtOppRfcommListener: stopping Accept Thread
08-31 11:04:25.862  4278  4326 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:04:25.862  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:25.862  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:25.863  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:25.863  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:25.864  4278  4326 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:04:25.865  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:04:25.867  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:25.867  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:25.868  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:04:25.868  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:25.871  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:25.871  4278  4278 D HeadsetService: Received stop request...Stopping profile...
08-31 11:04:25.873  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:25.874  1373  1384 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:25.875   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:25.875   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:25.875  1932  2227 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:25.876  4051  4062 D BluetoothHeadset: Proxy object disconnected
,08-31 11:04:25.876   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:04:25.876  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:25.878  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-31 11:04:25.879  4051  4051 D DockEventReceiver: finishStartingService: stopping service
08-31 11:04:25.879  4278  4278 D A2dpService: Received stop request...Stopping profile...
08-31 11:04:25.880  4278  4308 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:04:25.882  4051  4051 D HeadsetProfile: Bluetooth service disconnected
08-31 11:04:25.883  4051  4051 D BluetoothA2dp: Proxy object disconnected
08-31 11:04:25.883  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-31 11:04:25.883   871   871 D BluetoothA2dp: Proxy object disconnected
08-31 11:04:25.885  4278  4278 D HidService: Received stop request...Stopping profile...
08-31 11:04:25.885  4278  4278 D HidService: Stopping Bluetooth HidService
08-31 11:04:25.887  4278  4278 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:25.887  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-31 11:04:25.887  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:25.887  1373  1373 D HidProfile: Bluetooth service disconnected
08-31 11:04:25.887  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.887  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:25.887  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:25.889  4051  4051 D BluetoothInputDevice: Proxy object disconnected
08-31 11:04:25.889  4051  4051 D HidProfile: Bluetooth service disconnected
08-31 11:04:25.889  4278  4278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:04:25.889  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:25.889  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:25.889  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:25.889  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:04:25.889  4278  4294 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 11:04:25.890  4278  4278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:04:25.890  4278  4278 D HealthService: Received stop request...Stopping profile...
08-31 11:04:25.892  4278  4278 D PanService: Received stop request...Stopping profile...
08-31 11:04:25.893  4051  4051 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:04:25.893  4051  4051 D PanProfile: Bluetooth service disconnected
08-31 11:04:25.893  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:04:25.893  1373  1373 D PanProfile: Bluetooth service disconnected
08-31 11:04:25.894  4278  4278 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:04:25.894  4278  4278 D BluetoothMapService: stop()
08-31 11:04:25.894  4278  4278 D BluetoothMapAppObserver: deinitObservers()
08-31 11:04:25.894  4278  4278 D BluetoothMapAppObserver: removeReceiver()
,08-31 11:04:25.895  4051  4051 D BluetoothMap: Proxy object disconnected
08-31 11:04:25.895  4051  4051 D MapProfile: Bluetooth service disconnected
08-31 11:04:25.896  4278  4278 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:25.896  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:25.896  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.896  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:25.896  1373  1373 D BluetoothMap: Proxy object disconnected
08-31 11:04:25.896  1373  1373 D MapProfile: Bluetooth service disconnected
08-31 11:04:25.897  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 11:04:25.897  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:25.897  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:04:25.897  4278  4300 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:04:25.897  4278  4300 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:04:25.897  4278  4300 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:04:25.897  4278  4300 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 11:04:25.899  4051  4051 D BluetoothPbap: Proxy object disconnected
08-31 11:04:25.899  4051  4051 D PbapServerProfile: Bluetooth service disconnected
08-31 11:04:25.900  1373  1373 D BluetoothPbap: Proxy object disconnected
08-31 11:04:25.900  1373  1373 D PbapServerProfile: Bluetooth service disconnected
,08-31 11:04:25.900  4278  4278 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:04:25.900  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:25.900  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.900  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:25.900  4278  4278 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:04:25.901  4278  4278 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:04:25.901  4278  4294 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:04:25.901  4278  4278 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:04:25.901  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:25.901  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.901  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:25.901  4278  4278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:04:25.901  4278  4294 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 11:04:25.902  4278  4278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:04:25.902  4278  4278 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:25.902  4278  4278 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:04:25.902  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.902  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:25.902  4278  4278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:04:25.902  4278  4278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:04:25.903  4278  4278 D BluetoothMapService: MAP Service closeService in
08-31 11:04:25.903  4278  4278 V BluetoothAdapterState: isTurningOff()=true
08-31 11:04:25.903  4278  4278 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:04:25.903  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:25.903  4278  4278 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:25.903  4278  4278 D BluetoothMapService: cleanup()
08-31 11:04:25.904  4278  4278 D BluetoothMapService: MAP Service closeService in
08-31 11:04:25.904  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 11:04:25.904  4278  4290 D BluetoothAdapterProperties: Setting state to 15
08-31 11:04:25.904  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:04:25.904  4278  4290 I BluetoothAdapterState: Entering BleOnState
,08-31 11:04:25.905  4051  4062 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:25.905  4051  4061 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:04:25.905  4051  4062 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:04:25.906  1373  2025 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:25.906   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:04:25.906   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:04:25.906  4051  4061 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:04:25.909  1373  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:04:25.910   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:25.910  1373  1387 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:04:25.911  4051  4062 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:04:25.911  1932  2073 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:04:25.912  4051  4061 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:04:25.912  1373  2032 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:04:25.913   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:04:25.913  1373  2025 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:04:25.913  1373  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:04:25.914  4278  4290 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:04:25.914  4278  4290 D BluetoothAdapterProperties: Setting state to 16
08-31 11:04:25.914  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-31 11:04:25.915  4278  4290 D BluetoothAdapterProperties: onBleDisable
,08-31 11:04:25.915  4278  4290 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:04:25.916  4278  4291 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 11:04:25.917  4278  4300 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 11:04:25.917  4278  4300 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 11:04:25.917  4278  4294 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:04:25.919  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:25.920  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:04:25.921  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:25.924  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:25.924  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:25.925  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:25.926  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:25.927  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:25.932  4051  4051 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:04:26.120  4278  4294 I bt_hci  : shut_down
,08-31 11:04:26.121  4278  4298 D bt_hwcfg: hw_epilog_process
,08-31 11:04:26.133  4278  4298 I bt_vendor: low_power_mode_cb
,08-31 11:04:26.162  4278  4298 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 11:04:26.163  4278  4298 I bt_vendor: epilog_cb
08-31 11:04:26.163  4278  4298 I bt_hci  : epilog_finished_callback
,08-31 11:04:26.171  4278  4294 I bt_hci_h4: hal_close
,08-31 11:04:26.172  4278  4294 I bt_userial_vendor: device fd = 51 close
,08-31 11:04:26.293  4278  4291 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:04:26.295  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:04:26.301  4278  4290 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 11:04:26.301  4278  4278 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:04:26.303  4278  4278 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:04:26.303  4278  4278 D BtGatt.GattService: stop()
,08-31 11:04:26.304  4278  4278 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:04:26.309  4278  4278 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:26.310  4278  4278 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:26.310  4278  4278 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:26.310  4278  4278 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:04:26.311  4278  4290 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 11:04:26.312  4278  4290 D BluetoothAdapterProperties: Setting state to 10
08-31 11:04:26.313  4278  4290 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 11:04:26.316   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-31 11:04:26.318  4278  4290 I BluetoothAdapterState: Entering OffState
,08-31 11:04:26.336  4278  4278 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:04:26.337  4278  4278 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 11:04:26.337  4278  4291 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:04:26.346  4278  4291 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:04:26.347  4278  4278 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 11:04:26.354  4278  4278 I art     : System.exit called, status: 0
,08-31 11:04:26.355  4278  4278 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:04:26.412   871  1393 I ActivityManager: Process com.android.bluetooth (pid 4278) has died
,08-31 11:04:30.835  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:04:30.836  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:30.840  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:30.841  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17dbe0c removed from the list
08-31 11:04:30.841  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:30.841  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:30.842  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:30.845  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:04:30.845  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a416a added. We now have 4 listener(s)
08-31 11:04:30.846  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:04:30.847  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:30.848  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a416a removed from the list
08-31 11:04:30.848  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:04:30.848  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:30.849  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:30.851  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:04:30.851  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@858565b added. We now have 4 listener(s)
08-31 11:04:30.852  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:04:35.866  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:35.914   871   888 I ActivityManager: Start proc 4339:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 11:04:36.053  4339  4339 D AdapterServiceConfig: Adding HeadsetService
08-31 11:04:36.054  4339  4339 D AdapterServiceConfig: Adding A2dpService
08-31 11:04:36.054  4339  4339 D AdapterServiceConfig: Adding HidService
,08-31 11:04:36.054  4339  4339 D AdapterServiceConfig: Adding HealthService
08-31 11:04:36.054  4339  4339 D AdapterServiceConfig: Adding PanService
08-31 11:04:36.054  4339  4339 D AdapterServiceConfig: Adding GattService
,08-31 11:04:36.055  4339  4339 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:04:36.069   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@385f0a5:true
,08-31 11:04:36.069  4339  4339 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:04:36.073  4339  4339 I bt_bluedroid: init
,08-31 11:04:36.075  4339  4351 I BluetoothAdapterState: Entering OffState
,08-31 11:04:36.082  4339  4352 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 11:04:36.083  4339  4352 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:04:36.083  4339  4352 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:04:36.083  4339  4352 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:04:36.086  4339  4339 I bt_bluedroid: get_profile_interface socket
,08-31 11:04:36.088  4339  4339 I bt_bluedroid: get_profile_interface sdp
,08-31 11:04:36.092  4339  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:04:36.096  4339  4350 I bt_bluedroid: config_hci_snoop_log
,08-31 11:04:36.096  4339  4355 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 11:04:36.099   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:04:36.110  4339  4351 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:04:36.111  4339  4351 D BluetoothAdapterProperties: Setting state to 14
08-31 11:04:36.112  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:04:36.117  4339  4351 D BluetoothBondStateMachine: make
,08-31 11:04:36.121  4339  4356 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:04:36.128  4339  4351 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:36.130  4339  4339 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:04:36.139  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:36.141  4339  4339 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:04:36.143  4339  4339 D BtGatt.GattService: Received start request. Starting profile...
,08-31 11:04:36.144  4339  4339 D BtGatt.GattService: start()
,08-31 11:04:36.144  4339  4339 I bt_bluedroid: get_profile_interface gatt
,08-31 11:04:36.146  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
08-31 11:04:36.147  4339  4339 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:04:36.159  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:36.160  4339  4339 V BluetoothAdapterState: isTurningOn()=false
08-31 11:04:36.160  4339  4339 V BluetoothAdapterState: isBleTurningOn()=true
08-31 11:04:36.160  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:36.161  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 11:04:36.162  4339  4351 I bt_bluedroid: enable
08-31 11:04:36.163  4339  4352 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:04:36.163  4339  4352 I bt_hci  : start_up
,08-31 11:04:36.171  4339  4352 I bt_vendor: alloc value 0xb3a79189
08-31 11:04:36.171  4339  4352 I bt_vendor: init
08-31 11:04:36.171  4339  4352 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 11:04:36.171  4339  4352 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:04:36.278  4339  4352 D bt_hci  : start_up starting async portion
,08-31 11:04:36.279  4339  4359 I bt_hci  : event_finish_startup
08-31 11:04:36.279  4339  4359 I bt_hci_h4: hal_open
08-31 11:04:36.279  4339  4359 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:04:36.291  4339  4359 I bt_userial_vendor: device fd = 51 open
,08-31 11:04:36.322  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:04:36.353  4339  4359 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:04:36.354  4339  4359 D bt_hwcfg: Target name = [BCM4354A2]
08-31 11:04:36.355  4339  4359 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:04:37.201  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:04:37.202  4339  4359 D bt_hwcfg: Settlement delay -- 100 ms
08-31 11:04:37.202  4339  4359 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:04:37.319  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:04:37.321  4339  4359 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:04:37.351  4339  4359 I bt_hwcfg: vendor lib fwcfg completed
08-31 11:04:37.351  4339  4359 I bt_vendor: firmware callback
,08-31 11:04:37.351  4339  4359 I bt_hci  : firmware_config_callback
,08-31 11:04:37.364  4339  4363 I bt_btu  : btu_task pending for preload complete event
,08-31 11:04:37.364  4339  4363 I bt_btu_task: Bluetooth chip preload is complete
08-31 11:04:37.365  4339  4363 I bt_btu  : btu_task received preload complete event
,08-31 11:04:37.375  4339  4363 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:04:37.375  4339  4363 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 11:04:37.375  4339  4363 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 11:04:37.376  4339  4363 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:04:37.376  4339  4363 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:04:37.376  4339  4363 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 11:04:37.376  4339  4363 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:04:37.377  4339  4363 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:04:37.377  4339  4363 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 11:04:37.377  4339  4363 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:04:37.377  4339  4363 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:04:37.378  4339  4363 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:04:37.378  4339  4363 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:04:37.378  4339  4363 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:04:37.378  4339  4363 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:04:37.530  4339  4363 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,08-31 11:04:37.530  4339  4363 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-31 11:04:37.556  4339  4355 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 11:04:37.559  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:04:37.560  4339  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 11:04:37.563  4339  4355 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:04:37.566  4339  4355 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:04:37.568  4339  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:04:37.568  4339  4355 D bt_hci  : do_postload posting postload work item
,08-31 11:04:37.570  4339  4359 I bt_hci  : event_postload
,08-31 11:04:37.570  4339  4359 I bt_vendor: sco_config_cb
,08-31 11:04:37.570  4339  4359 I bt_hci  : sco_config_callback postload finished.
,08-31 11:04:37.573  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:37.576  4339  4355 D bt_bte_conf: Device ID record 1 : primary
08-31 11:04:37.576  4339  4355 D bt_bte_conf:   vendorId            = 000f
08-31 11:04:37.576  4339  4355 D bt_bte_conf:   vendorIdSource      = 0001
08-31 11:04:37.576  4339  4355 D bt_bte_conf:   product             = 1200
08-31 11:04:37.577  4339  4355 D bt_bte_conf:   version             = 1436
08-31 11:04:37.577  4339  4355 D bt_bte_conf:   clientExecutableURL = 
08-31 11:04:37.577  4339  4355 D bt_bte_conf:   serviceDescription  = 
08-31 11:04:37.577  4339  4355 D bt_bte_conf:   documentationURL    = 
08-31 11:04:37.578  4339  4355 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 11:04:37.578  4339  4359 I bt_vendor: low_power_mode_cb
08-31 11:04:37.578  4339  4352 D bt_stack_manager: event_start_up_stack finished
08-31 11:04:37.579  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 11:04:37.579  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:37.580  4339  4351 D BluetoothAdapterProperties: Setting state to 15
08-31 11:04:37.580  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 11:04:37.581  4339  4351 I BluetoothAdapterState: Entering BleOnState
,08-31 11:04:37.585  4339  4351 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 11:04:37.585  4339  4351 D BluetoothAdapterProperties: Setting state to 11
08-31 11:04:37.585  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:04:37.590  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:37.591  4339  4339 D HeadsetService: Received start request. Starting profile...
,08-31 11:04:37.595  4339  4339 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:04:37.596  4339  4339 D HeadsetStateMachine: make
08-31 11:04:37.600  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:37.602  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:04:37.608  4339  4351 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:04:37.611  4339  4339 D HeadsetStateMachine: max_hf_connections = 1
,08-31 11:04:37.611  4339  4339 I bt_bluedroid: get_profile_interface handsfree
08-31 11:04:37.612  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 11:04:37.612  4339  4355 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:04:37.615  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:37.616  4339  4339 D A2dpService: Received start request. Starting profile...
,08-31 11:04:37.617  4339  4339 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:04:37.618  4339  4339 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:04:37.626  4339  4339 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:04:37.627  4339  4339 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:04:37.627  4339  4339 D A2dpStateMachine: make
,08-31 11:04:37.629  4339  4339 I bt_bluedroid: get_profile_interface a2dp
,08-31 11:04:37.630  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 11:04:37.632  4339  4372 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:04:37.633  4339  4339 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:04:37.634  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:37.635  4339  4339 D HidService: Received start request. Starting profile...
08-31 11:04:37.635  4339  4339 I bt_bluedroid: get_profile_interface hidhost
08-31 11:04:37.635  4339  4355 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
08-31 11:04:37.636  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 11:04:37.636  4339  4339 D HidService: setHidService(): set to: null
,08-31 11:04:37.640  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:04:37.641  4339  4339 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 11:04:37.642  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
08-31 11:04:37.643  4339  4339 D HealthService: Received start request. Starting profile...
,08-31 11:04:37.645  4339  4339 I bt_bluedroid: get_profile_interface health
08-31 11:04:37.646  4339  4339 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:04:37.646  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
08-31 11:04:37.647  4339  4339 D PanService: Received start request. Starting profile...
,08-31 11:04:37.648  4339  4339 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:04:37.648  4339  4339 I bt_bluedroid: get_profile_interface pan
,08-31 11:04:37.649  4339  4355 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:04:37.654  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:04:37.654  4339  4339 D BluetoothMapService: Received start request. Starting profile...
08-31 11:04:37.655  4339  4339 D BluetoothMapService: start()
,08-31 11:04:37.659  4339  4339 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 11:04:37.661  4339  4339 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 11:04:37.661  4339  4339 D BluetoothMapAppObserver: createReceiver()
,08-31 11:04:37.662  4339  4339 D BluetoothMapAppObserver: initObservers()
,08-31 11:04:37.662  4339  4339 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:04:37.671  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:37.671  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.671  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:37.671  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:04:37.673  4339  4369 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:37.674  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:37.675  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:37.675  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.675  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:04:37.675  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:37.676  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:37.676  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.676  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:37.676  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:37.677  4339  4339 V BluetoothAdapterState: isTurningOff()=false
08-31 11:04:37.677  4339  4339 V BluetoothAdapterState: isTurningOn()=true
08-31 11:04:37.677  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:04:37.677  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:04:37.677  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 11:04:37.677  4339  4351 D BluetoothAdapterProperties: ScanMode =  20
,08-31 11:04:37.677  4339  4351 D BluetoothAdapterProperties: State =  11
08-31 11:04:37.678  4339  4351 D BluetoothAdapterProperties: Setting state to 12
08-31 11:04:37.678  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:04:37.678  4339  4351 I BluetoothAdapterState: Entering OnState
08-31 11:04:37.679  4051  4062 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:37.680  4051  4061 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:04:37.683  4339  4355 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:04:37.684  4339  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:04:37.686  4051  4062 D BluetoothPan: onBluetoothStateChange on: true
,08-31 11:04:37.688  4051  4051 D BluetoothMap: Proxy object connected
,08-31 11:04:37.688  4051  4051 D MapProfile: Bluetooth service connected
08-31 11:04:37.688  4051  4051 D BluetoothMap: getConnectedDevices()
08-31 11:04:37.689  1373  2032 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:37.689  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:37.689  4339  4339 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:04:37.690   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:04:37.690   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:37.691  4051  4061 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:04:37.691  4339  4339 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 11:04:37.693  1373  1384 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:04:37.693  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:37.694  4339  4339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:37.696  1373  1373 D BluetoothMap: Proxy object connected
,08-31 11:04:37.696   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:37.696  1373  1373 D MapProfile: Bluetooth service connected
08-31 11:04:37.696  1373  1373 D BluetoothMap: getConnectedDevices()
08-31 11:04:37.697  1373  2025 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:04:37.699  4051  4062 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:37.700  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:04:37.700  4339  4339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:37.702  1932  1955 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:04:37.702  4051  4061 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:04:37.702  4339  4339 D ObexServerSockets: Succeed to create listening sockets 
08-31 11:04:37.703  4339  4339 D ObexServerSockets0: startAccept()
,08-31 11:04:37.703  4339  4339 D ObexServerSockets0: prepareForNewConnect()
08-31 11:04:37.704  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:37.704  1373  2032 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:04:37.705  4339  4339 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 11:04:37.706  4339  4339 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 11:04:37.706   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:04:37.706  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:04:37.708  1373  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:04:37.709  4339  4379 D ObexServerSockets0: Accepting socket connection...
08-31 11:04:37.709  4339  4380 D ObexServerSockets0: Accepting socket connection...
08-31 11:04:37.709  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:04:37.709  1373  1373 D PanProfile: Bluetooth service connected
08-31 11:04:37.710   871   871 D BluetoothA2dp: Proxy object connected
08-31 11:04:37.711  1373  1373 D BluetoothA2dp: Proxy object connected
,08-31 11:04:37.713  4051  4051 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:04:37.713  4051  4051 D PanProfile: Bluetooth service connected
08-31 11:04:37.713  4051  4051 D BluetoothA2dp: Proxy object connected
,08-31 11:04:37.718  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:37.719  4339  4339 D BluetoothMapService: onReceive
08-31 11:04:37.719  4339  4339 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:04:37.719  4339  4339 D BluetoothMapService: STATE_ON
08-31 11:04:37.719  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:37.720   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:04:37.720  1373  1373 D BluetoothInputDevice: Proxy object connected
08-31 11:04:37.721  1373  1373 D HidProfile: Bluetooth service connected
,08-31 11:04:37.726  4051  4051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:04:37.729  4051  4051 D BluetoothInputDevice: Proxy object connected
,08-31 11:04:37.730  4051  4051 D HidProfile: Bluetooth service connected
,08-31 11:04:37.733  1534  1534 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:04:37.743  4051  4051 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:04:37.747  4051  4051 D BluetoothPbap: Proxy object connected
08-31 11:04:37.748  4051  4051 D PbapServerProfile: Bluetooth service connected
,08-31 11:04:37.750  1373  1373 D BluetoothPbap: Proxy object connected
,08-31 11:04:37.750  1373  1373 D PbapServerProfile: Bluetooth service connected
08-31 11:04:37.751  4339  4339 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 11:04:37.751  4339  4339 D ObexServerSockets0: prepareForNewConnect()
,08-31 11:04:37.753  4339  4387 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:37.772  4339  4391 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:04:37.774  4339  4391 I BtOppRfcommListener: Accept thread started.
,08-31 11:04:37.782  1373  1387 D BluetoothHeadset: Proxy object connected
,08-31 11:04:37.782   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.782   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.783  1932  1943 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.782  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-31 11:04:37.783  4051  4377 D BluetoothHeadset: Proxy object connected
,08-31 11:04:37.783   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.784  4051  4051 D HeadsetProfile: Bluetooth service connected
,08-31 11:04:37.789  1373  2025 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.790   871   888 D BluetoothHeadset: Proxy object connected
08-31 11:04:37.790  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-31 11:04:37.796   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:04:37.802  1932  2227 D BluetoothHeadset: Proxy object connected
,08-31 11:04:37.807   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:40.886  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:40.892  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:40.894  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:40.895  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@858565b removed from the list
08-31 11:04:40.895  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:04:40.895  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:04:40.895  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:04:40.898  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:04:40.898  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4eaef8 added. We now have 4 listener(s)
08-31 11:04:40.899  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:04:40.903   871  2217 D WifiService: setWifiEnabled: false pid=3993, uid=10000
,08-31 11:04:40.903   871  2217 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:45.918  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:04:45.921   871  2389 D WifiService: setWifiEnabled: true pid=3993, uid=10000
,08-31 11:04:45.922   871  2389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:04:45.938   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:45.958  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:45.964  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:04:45.969   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:04:45.969  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:04:45.971   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 11:04:45.972   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 11:04:45.973  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:04:45.974   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:04:45.974   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 11:04:45.975   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 11:04:45.975   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 11:04:45.991   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:04:45.992   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:45.992   371   869 D CommandListener: Setting iface cfg
08-31 11:04:45.993   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '163 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 163 Failed to set address (No such device)'
08-31 11:04:45.993   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:04:46.051   871  1313 E native  : do suspend true
,08-31 11:04:46.052   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:04:46.054   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:04:46.117   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:47.501   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:04:47.614   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.12 rxSuccessRate=11.38 delta 1000 -> 994
,08-31 11:04:47.616   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 11:04:47.616   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:04:47.638   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:04:47.688   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:04:47.689  1481  1481 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:04:48.129  1481  1481 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:04:48.185  1481  1481 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:04:48.186  1481  1481 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:04:48.196   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:04:48.214   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 11:04:48.214   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:04:48.214   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:04:48.233   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:04:48.248   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:48.251   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:04:48.258   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:04:48.292   871  4403 D DhcpClient: Receive thread started
,08-31 11:04:48.385   871  1313 E native  : do suspend false
,08-31 11:04:48.410   871  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:04:48.429   871  4403 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172766, domain null
,08-31 11:04:48.430   871  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172766 seconds
,08-31 11:04:48.433   871  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:04:48.455   871  4403 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:04:48.456   871  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:04:48.462   371   869 D CommandListener: Setting iface cfg
,08-31 11:04:48.474   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-31 11:04:48.475   871  1888 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:04:48.477   871  1313 E native  : do suspend true
,08-31 11:04:48.506   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:04:48.510   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:04:48.512   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:04:48.515   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 11:04:48.529   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:04:48.611   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:04:48.611   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 11:04:48.612   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 11:04:48.613   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 11:04:48.614   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 11:04:48.626   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:04:48.634   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 11:04:48.635   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 11:04:48.635   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 11:04:48.635   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-31 11:04:48.635   871  1315 D ConnectivityService:    accepting network in place of null
08-31 11:04:48.635   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:04:48.637   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:04:48.659   871  4402 D NetlinkSocketObserver: NeighborEvent{elapsedMs=291044, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 11:04:48.667   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:48.712   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:04:48.717   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 11:04:48.717   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:48.720   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-31 11:04:48.723   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:48.734  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:48.739  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:48.743   871  4401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:48.747  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:48.750  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:48.761  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:04:48.774  1756  1756 D SystemUpdateService: onCreate
,08-31 11:04:48.779  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:04:48.791  1756  4412 I SystemUpdateService: active receiver: enabled
,08-31 11:04:48.800  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 11:04:48.803  1756  4412 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:04:48.811  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:04:48.810   871  4401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:04:48 GMT], X-Android-Received-Millis=[1472634288809], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472634288786]}
,08-31 11:04:48.815  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:04:48.816   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 11:04:48.817   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-31 11:04:48.817   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:04:48.818  4105  4105 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:04:48.827   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:04:48.828  1756  4414 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 11:04:48.828  1756  4414 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 11:04:48.833  4105  4105 D SprintDMHelper: simOperator: 
,08-31 11:04:48.833  4105  4105 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:04:48.837  1756  4414 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 11:04:48.866  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:04:48.872  1534  1534 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:04:48.873  3907  4419 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 11:04:48.878  1756  2451 I iu.UploadsManager: num queued entries: 0
,08-31 11:04:48.879  1756  2451 I iu.UploadsManager: num updated entries: 0
,08-31 11:04:48.891  1756  4412 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 11:04:48.891  1756  4412 I SystemUpdateService: now status is 0 (complete)
08-31 11:04:48.891  1756  4412 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 11:04:48.891  1756  4412 I SystemUpdateService: file has been verified
,08-31 11:04:48.891  1756  4412 I SystemUpdateService: OTA package size = 12249756
,08-31 11:04:48.927  1756  2451 I iu.SyncManager: NEXT; no task
,08-31 11:04:48.974  1756  4412 I SystemUpdateService: showing system update notification
,08-31 11:04:49.049  1534  2053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 11:04:49.049  1534  2053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 11:04:49.049  1534  2053 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:04:49.049  1534  2053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:04:49.049  1534  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:04:49.049  1534  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 11:04:49.049  1534  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:04:49.049  1534  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:04:49.058  3192  4420 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 11:04:49.071  3689  4422 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 11:04:49.071  3689  4422 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jdm.a(PG:82)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jcs.o(PG:406)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jcn.a(PG:1379)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jcs.i(PG:143)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at blb.a(PG:3937)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at czp.a(PG:18188)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at czp.a(PG:9081)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at czq.run(PG:1686)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:04:49.071  3689  4422 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jdj.a(PG:4091)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jdj.a(PG:1125)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jdm.a(PG:77)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	... 12 more
08-31 11:04:49.071  3689  4422 E HttpOperation: Caused by: faj: BadAuthentication
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at fal.a(PG:38)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	at jdj.a(PG:4089)
08-31 11:04:49.071  3689  4422 E HttpOperation: 	... 14 more
,08-31 11:04:49.075  1756  1756 D SystemUpdateService: onDestroy
,08-31 11:04:49.083  3907  4425 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 11:04:49.146  1534  2349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 11:04:49.147  1534  2349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 11:04:49.147  1534  2349 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:04:49.147  1534  2349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:04:49.148  1534  2053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-31 11:04:49.148  1534  2053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 11:04:49.148  1534  2053 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:04:49.148  1534  2053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:04:49.193  3689  4422 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 11:04:49.193  3689  4422 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jdm.a(PG:82)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jcs.o(PG:406)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jcn.a(PG:1379)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jcs.i(PG:143)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at hec.a(PG:42)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at hee.a(PG:102)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at czr.a(PG:65)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at kka.a(PG:108)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at czp.a(PG:19176)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at czp.a(PG:9081)
,08-31 11:04:49.193  3689  4422 E HttpOperation: 	at czq.run(PG:1686)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:04:49.193  3689  4422 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jdj.a(PG:4091)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jdj.a(PG:1125)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jdm.a(PG:77)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	... 15 more
08-31 11:04:49.193  3689  4422 E HttpOperation: Caused by: faj: BadAuthentication
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at fal.a(PG:38)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	at jdj.a(PG:4089)
08-31 11:04:49.193  3689  4422 E HttpOperation: 	... 17 more
08-31 11:04:49.194  3689  4422 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 11:04:49.194  3689  4422 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at hec.a(PG:42)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at hee.a(PG:102)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at czr.a(PG:65)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at kka.a(PG:108)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	... 15 more
08-31 11:04:49.194  3689  4422 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at fal.a(PG:38)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 11:04:49.194  3689  4422 E ExperimentLoader: 	... 17 more
,08-31 11:04:49.227  1534  2053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-31 11:04:49.227  1534  2053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 11:04:49.227  1534  2053 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:04:49.227  1534  2053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:04:49.252  3907  4425 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-31 11:04:49.258  3907  4419 E BooksSync: Soft error
08-31 11:04:49.258  3907  4419 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 11:04:49.258  3907  4419 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-31 11:04:49.261  1756  4414 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-31 11:04:49.263  3907  4419 E BooksSync: Sync error
08-31 11:04:49.263  3907  4419 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 11:04:49.263  3907  4419 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 11:04:49.263  3907  4419 I BooksSync: Finished books sync
,08-31 11:04:49.266   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289819, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 11:04:49.407   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 259953, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:04:50.948  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:04:50.956  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:04:50.957  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:04:50.957  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4eaef8 removed from the list
08-31 11:04:50.958  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:04:50.958  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:04:50.959  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:04:50.971  3993  4431 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-31 11:04:50.971  3993  4431 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:04:53.978  3993  4431 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-31 11:04:53.980  3993  4431 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-31 11:04:53.981  3993  4432 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-31 11:04:53.982  3993  4432 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:04:53.982  3993  4432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:04:53.982  3993  4431 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:04:53.984  3993  4432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:04:53.985  3993  4431 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:04:53.989  3993  4434 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: IncomingSocketThread/Sender)
,08-31 11:04:53.989  3993  4432 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-31 11:04:53.991  3993  4431 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-31 11:04:53.991  3993  4435 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: OutgoingSocketThread/Sender)
08-31 11:04:53.994  3993  4436 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: IncomingSocketThread/Receiver)
,08-31 11:04:53.997  3993  4436 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: IncomingSocketThread/Receiver)
,08-31 11:04:53.997  3993  4436 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-31 11:04:53.997  3993  4437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: OutgoingSocketThread/Receiver)
08-31 11:04:53.998  3993  4436 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-31 11:04:53.999  3993  4437 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 457, thread name: OutgoingSocketThread/Receiver)
,08-31 11:04:54.000  3993  4437 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-31 11:04:54.001  3993  4437 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-31 11:04:56.642   871  1315 D ConnectivityService: handlePromptUnvalidated 102
,08-31 11:04:56.977  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 11:04:56.979  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:04:56.989  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a8b4487 Bundle[{}]
,08-31 11:04:56.990  3993  4039 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:04:56.990  3993  4039 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 11:04:56.990  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 11:04:56.991  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:04:56.991  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 11:04:56.992  3993  4039 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 11:04:56.996  3993  4039 I System.out: Running OutgoingSocketThread
08-31 11:04:56.999  3993  4438 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-31 11:04:57.000  3993  4438 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:05:00.008  3993  4439 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-31 11:05:00.009  3993  4439 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-31 11:05:00.009  3993  4439 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:05:00.012  3993  4438 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-31 11:05:00.012  3993  4438 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-31 11:05:00.012  3993  4439 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:05:00.013  3993  4438 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:05:00.014  3993  4439 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-31 11:05:00.021  3993  4438 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-31 11:05:00.021  3993  4441 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: IncomingSocketThread/Sender)
08-31 11:05:00.024  3993  4442 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: IncomingSocketThread/Receiver)
,08-31 11:05:00.026  3993  4438 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-31 11:05:00.026  3993  4442 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: IncomingSocketThread/Receiver)
08-31 11:05:00.027  3993  4442 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-31 11:05:00.027  3993  4442 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-31 11:05:00.028  3993  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: OutgoingSocketThread/Sender)
,08-31 11:05:00.040  3993  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: OutgoingSocketThread/Receiver)
,08-31 11:05:00.042  3993  4444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 469, thread name: OutgoingSocketThread/Receiver)
,08-31 11:05:00.043  3993  4444 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-31 11:05:00.043  3993  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 469, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-31 11:05:03.019  3993  4039 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 478)
,08-31 11:05:03.020  3993  4039 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 11:05:03.020  3993  4039 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 479)
08-31 11:05:03.023  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:05:03.023  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa03fd1 added. We now have 3 listener(s)
,08-31 11:05:03.025  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:05:03.025  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:05:03.025  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:05:03.025  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:05:03.025  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530a36 added. We now have 4 listener(s)
08-31 11:05:03.025  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:05:03.026  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:05:03.030  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:05:03.039  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:05:03.043  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:05:03.043  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:05:03.044  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:05:03.044  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:05:03.044  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:05:03.044  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:05:03.044  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:03.045  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:03.045  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:05:03.045  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa03fd1 removed from the list
,08-31 11:05:03.045  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:03.045  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530a36 removed from the list
08-31 11:05:03.048  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:05:03.050  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:05:03.050  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:05:03.051  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:03.052  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:03.052  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:03.053  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:03.053  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:03.053  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:03.053  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530a36 not in the list
,08-31 11:05:03.053  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:03.053  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:03.054  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:03.054  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:03.054  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:05:03.054  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530a36 not in the list
08-31 11:05:03.054  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:03.054  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:03.054  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:03.054  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa03fd1 not in the list
08-31 11:05:03.055  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:05:03.055  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3bc2a4 added. We now have 3 listener(s)
,08-31 11:05:03.057  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:05:03.057  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:05:03.057  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:05:03.058  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:05:03.058  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98080d added. We now have 4 listener(s)
08-31 11:05:03.058  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:05:03.058  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:05:03.060  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:05:03.068  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:05:03.072  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:05:03.073  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:05:03.073  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:05:03.073  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:05:03.074  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:05:03.074  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:05:03.074  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:05:03.075  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:05:03.078  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:05:03.082  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:05:03.082  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:05:03.092  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:05:03.094  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:05:03.094  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:05:03.102  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:05:03.103  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:05:03.103  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:05:03.104  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:05:03.108  4339  4370 D BtGatt.GattService: registerClient() - UUID=08f52fa5-22a6-4759-b6a2-215d5ce75902
,08-31 11:05:03.109  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=08f52fa5-22a6-4759-b6a2-215d5ce75902, clientIf=5
,08-31 11:05:03.110  3993  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 11:05:03.112  4339  4381 D BtGatt.GattService: start scan with filters
,08-31 11:05:03.121  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:05:03.121  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:05:03.121  4339  4358 D BtGatt.ScanManager: handling starting scan
08-31 11:05:03.121  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:05:03.122  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:05:03.125  4339  4358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deac8ab
,08-31 11:05:03.130  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:05:03.130  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:05:03.131  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:05:03.135  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:05:03.139  4339  4355 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:05:03.140  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:03.141  4339  4358 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:05:03.142  3993  4039 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:05:03.143  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:05:03.143  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 11:05:03.143  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:03.143  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:05:03.144  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:05:03.144  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:05:03.144  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:05:03.145  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:05:03.145  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:05:03.145  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:05:03.148  3993  4039 D BluetoothAdapter: STATE_ON
08-31 11:05:03.150  4339  4350 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:05:03.151  4339  4349 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:05:03.152  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:05:03.152  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:05:03.152  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:05:03.152  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:05:03.153  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:05:03.155  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:05:03.155  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:05:03.156  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:05:03.156  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:05:03.157  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:05:03.159  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:05:03.159  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:03.160  4339  4358 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:05:03.160  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:03.161  4339  4358 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:05:03.161  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:03.162  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:05:03.182  4339  4355 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:05:03.182  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:03.196  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:05:03.196  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:03.211  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:05:03.211  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:05:03.211  4339  4358 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:05:03.223  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 11:05:03.223  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:05:03.224  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:05:03.242  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:05:03.242  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:03.663  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-31 11:05:03.664  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:05:03.664  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:05:06.161  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:05:06.162  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:05:06.162  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:05:06.162  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:06.163  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:06.163  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:06.163  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:05:06.164  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3bc2a4 removed from the list
,08-31 11:05:06.164  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:06.164  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98080d removed from the list
08-31 11:05:06.165  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:05:06.165  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:06.167  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:06.167  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:06.170  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:06.170  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:05:06.171  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:06.171  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98080d not in the list
08-31 11:05:06.171  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:06.172  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:06.175  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:06.175  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:06.175  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:06.176  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98080d not in the list
,08-31 11:05:06.176  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:06.176  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:06.177  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:06.177  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3bc2a4 not in the list
08-31 11:05:06.179  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:05:06.180  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f552a0e added. We now have 3 listener(s)
,08-31 11:05:06.187  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:05:06.187  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:05:06.187  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:05:06.188  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:05:06.189  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee75c2f added. We now have 4 listener(s)
,08-31 11:05:06.189  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:05:06.191  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:05:06.198  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:05:06.212  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:05:06.219  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:05:06.221  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:05:06.221  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:05:06.224  3993  4039 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
08-31 11:05:06.224  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,08-31 11:05:06.227  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:05:06.228  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-31 11:05:06.228  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:05:06.228  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:05:06.231  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:05:06.234  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:05:06.235  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:05:06.235  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:05:06.236  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:05:06.236  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-31 11:05:06.236  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:05:06.237  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:05:06.240  3993  4446 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:05:06.242  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:05:06.242  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:05:06.246  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:05:06.246  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:05:06.248  3993  4446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-31 11:05:06.251  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:05:06.252  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:05:06.252  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:05:06.255  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-31 11:05:06.255  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:05:06.255  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-31 11:05:06.255  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:05:06.256  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-31 11:05:06.256  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-31 11:05:06.256  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:05:06.259  4339  4349 D BtGatt.GattService: registerClient() - UUID=f51824a7-a6f9-44cc-8925-2b05e575eb6c
,08-31 11:05:06.260  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=f51824a7-a6f9-44cc-8925-2b05e575eb6c, clientIf=5
08-31 11:05:06.260  3993  4004 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-31 11:05:06.263  4339  4357 D BtGatt.AdvertiseManager: message : 0
,08-31 11:05:06.267  4339  4357 D BtGatt.AdvertiseManager: starting multi advertising
,08-31 11:05:06.277  4339  4355 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-31 11:05:06.285  4339  4355 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-31 11:05:06.287  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-31 11:05:06.287  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:05:06.289  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:05:06.290  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-31 11:05:06.290  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-31 11:05:06.290  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-31 11:05:06.291  3993  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-31 11:05:06.291  3993  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-31 11:05:06.291  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-31 11:05:06.292  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-31 11:05:06.294  3993  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-31 11:05:06.294  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-31 11:05:06.795  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-31 11:05:06.796  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:05:06.796  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:05:09.294  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:05:09.294  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-31 11:05:09.295  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:05:09.295  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:05:09.295  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:05:09.295  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:05:09.296  3993  4446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:05:09.296  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:05:09.297  3993  4446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-31 11:05:09.297  3993  4039 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:05:09.297  3993  4446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:05:09.297  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:05:09.297  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:05:09.298  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:05:09.298  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:05:09.298  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:05:09.298  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:05:09.301  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:05:09.301  3993  4039 D BluetoothLeScanner: could not find callback wrapper
08-31 11:05:09.301  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:05:09.302  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-31 11:05:09.304  4339  4357 D BtGatt.AdvertiseManager: message : 1
,08-31 11:05:09.306  4339  4357 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-31 11:05:09.318  4339  4355 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-31 11:05:09.318  4339  4355 D BtGatt.GattService: Client app is not null!
,08-31 11:05:09.320  4339  4381 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:05:09.322  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:05:09.322  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-31 11:05:09.322  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-31 11:05:09.323  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-31 11:05:09.323  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-31 11:05:09.326  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:05:09.327  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:05:09.327  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:05:09.329  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:05:09.332  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:05:09.332  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:09.333  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:09.333  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:05:09.333  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f552a0e removed from the list
08-31 11:05:09.334  3993  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 11:05:09.334  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:09.334  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:09.335  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee75c2f removed from the list
08-31 11:05:09.335  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:09.335  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:05:09.335  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:09.335  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:05:09.336  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:09.337  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:09.339  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:09.339  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:09.339  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:09.340  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee75c2f not in the list
,08-31 11:05:09.340  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:09.340  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:09.343  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:09.343  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:09.343  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:05:09.344  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee75c2f not in the list
08-31 11:05:09.344  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:09.344  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:09.345  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:09.345  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f552a0e not in the list
08-31 11:05:09.348  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:05:09.348  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b47c628 added. We now have 3 listener(s)
08-31 11:05:09.352  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:05:09.352  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:05:09.352  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:05:09.353  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:05:09.353  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dfbf41 added. We now have 4 listener(s)
08-31 11:05:09.353  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:05:09.354  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:05:09.357  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:05:09.362  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:05:09.365  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:05:09.365  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:05:09.365  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:05:09.365  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:05:09.365  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:05:09.365  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:05:09.366  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:05:09.369  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:05:09.370  3993  4039 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:05:09.370  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:05:09.371  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:05:09.374  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:05:09.375  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:05:09.375  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:05:09.379  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:05:09.379  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:05:09.379  3993  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:05:09.380  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:05:09.382  4339  4382 D BtGatt.GattService: registerClient() - UUID=cc28ac79-8b04-4bdd-b792-bc89c66125d9
,08-31 11:05:09.383  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=cc28ac79-8b04-4bdd-b792-bc89c66125d9, clientIf=5
,08-31 11:05:09.384  3993  4004 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:05:09.385  4339  4350 D BtGatt.GattService: start scan with filters
,08-31 11:05:09.388  4339  4358 D BtGatt.ScanManager: handling starting scan
,08-31 11:05:09.388  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:05:09.388  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:05:09.389  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:05:09.389  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:05:09.393  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:05:09.394  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:05:09.394  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:05:09.395  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:05:09.398  4339  4355 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:05:09.399  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:09.399  4339  4358 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:05:09.408  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:05:09.409  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:09.409  4339  4358 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:05:09.409  4339  4358 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:05:09.427  4339  4355 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:05:09.427  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:09.438  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:05:09.439  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:09.837  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:05:09.894  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-31 11:05:09.895  3993  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:05:09.895  3993  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:05:10.946  4339  4339 D BtGatt.ScanManager: awakened up at time 313332
,08-31 11:05:10.951  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:05:10.988  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-31 11:05:10.988  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:10.988  4339  4355 D BtGatt.GattService: current time is 313374539535
08-31 11:05:10.989  4339  4355 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -94, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 53, 33, -121, 80, 73, -44, 1, 0, -106, 26, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -15, -8, -17, 2, 2, -29, 21, 63, 61, 63, -44, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-31 11:05:10.990  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-31 11:05:10.991  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -15, -8, -17, 2, 2, -29, 21, 63, 61, 63, -44, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-31 11:05:10.991  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-31 11:05:10.992  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-31 11:05:10.992  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-31 11:05:10.992  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-31 11:05:12.407  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:05:12.407  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:05:12.408  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:05:12.408  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.408  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-31 11:05:12.409  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:05:12.409  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:05:12.409  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:05:12.409  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:05:12.410  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:05:12.410  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:05:12.412  3993  4039 D BluetoothAdapter: STATE_ON
,08-31 11:05:12.414  4339  4383 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:05:12.417  4339  4370 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:05:12.419  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:05:12.419  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:05:12.419  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:05:12.420  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:05:12.420  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:05:12.424  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:05:12.424  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:05:12.425  3993  4039 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:05:12.425  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:05:12.429  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:12.429  4339  4339 D BtGatt.ScanManager: awakened up at time 314814
08-31 11:05:12.433  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:12.433  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:12.433  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:12.433  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:05:12.433  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:12.434  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:05:12.434  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:05:12.434  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b47c628 removed from the list
08-31 11:05:12.434  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:12.435  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dfbf41 removed from the list
08-31 11:05:12.435  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:05:12.435  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:12.437  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.437  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:12.441  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:12.441  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:12.441  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:12.441  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:05:12.441  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dfbf41 not in the list
08-31 11:05:12.441  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:05:12.441  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:12.441  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:12.441  4339  4358 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:05:12.442  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:12.442  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:12.442  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:05:12.442  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dfbf41 not in the list
08-31 11:05:12.442  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:12.442  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.443  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-31 11:05:12.443  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b47c628 not in the list
08-31 11:05:12.444  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 11:05:12.444  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a67172 added. We now have 3 listener(s)
08-31 11:05:12.446  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:05:12.446  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:05:12.446  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:05:12.446  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:05:12.446  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9b39c3 added. We now have 4 listener(s)
08-31 11:05:12.446  3993  4039 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:05:12.447  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:05:12.449  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 11:05:12.450  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:12.450  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:05:12.452  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:05:12.457  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:05:12.457  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:05:12.458  3993  4039 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:05:12.460  3993  4039 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:05:12.461  3993  4039 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:05:12.462  3993  4039 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:05:12.462  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:05:12.462  3993  4039 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:05:12.462  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:12.462  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.462  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:05:12.462  3993  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:05:12.463  3993  4039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a67172 removed from the list
,08-31 11:05:12.463  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:12.463  3993  4039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9b39c3 removed from the list
08-31 11:05:12.465  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:05:12.469  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:05:12.469  3993  4039 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:05:12.469  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:12.469  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:05:12.470  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:05:12.471  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:05:12.471  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:12.471  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:12.471  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9b39c3 not in the list
,08-31 11:05:12.471  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.471  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:12.472  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:05:12.472  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:05:12.472  3993  4039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:05:12.472  3993  4039 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9b39c3 not in the list
08-31 11:05:12.472  3993  4039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:05:12.473  3993  4039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:05:12.473  3993  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:05:12.473  3993  4039 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a67172 not in the list
,08-31 11:05:12.474  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:05:12.474  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:05:12.474  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-31 11:05:12.474  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:05:12.474  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:05:12.475  3993  4039 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:05:12.935  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:05:14.489  3993  4447 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
,08-31 11:05:16.487  3993  4039 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 488
,08-31 11:05:16.488  3993  4039 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 488, name: My test thread name)
,08-31 11:05:16.494  3993  4448 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 489, name: My test thread name)
,08-31 11:05:16.495  3993  4448 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 489, thread name: My test thread name)
08-31 11:05:16.495  3993  4448 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 489, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-31 11:05:16.499  3993  4039 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-31 11:05:16.508  3993  4449 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: My test thread name)
,08-31 11:05:16.509  3993  4449 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 493, thread name: My test thread name): Test exception.
,08-31 11:05:16.510  3993  4449 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 493, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-31 11:05:16.521  3993  4039 I jxcore-log: Total number of executed tests:  82
08-31 11:05:16.521  3993  4039 I jxcore-log: 
,08-31 11:05:16.522  3993  4039 I jxcore-log: Number of passed tests:  82
08-31 11:05:16.522  3993  4039 I jxcore-log: 
08-31 11:05:16.523  3993  4039 I jxcore-log: Number of failed tests:  0
08-31 11:05:16.523  3993  4039 I jxcore-log: 
,08-31 11:05:16.525  3993  4039 I jxcore-log: Number of ignored tests:  0
08-31 11:05:16.525  3993  4039 I jxcore-log: 
,08-31 11:05:16.526  3993  4039 I jxcore-log: Total duration:  111459
08-31 11:05:16.526  3993  4039 I jxcore-log: 
,08-31 11:05:16.531  3993  4039 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:05:16.531  3993  4039 I jxcore-log: 
,08-31 11:05:16.534  3993  4039 I jxcore-log: My device name is: motorola-Nexus 6
08-31 11:05:16.534  3993  4039 I jxcore-log: 
08-31 11:05:16.543  3993  4039 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:05:16.543  3993  4039 I jxcore-log: 
,08-31 11:05:16.551  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.551  3993  4039 I jxcore-log: 
,08-31 11:05:16.554  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.554  3993  4039 I jxcore-log: 
,08-31 11:05:16.558  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.558  3993  4039 I jxcore-log: 
,08-31 11:05:16.563  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-31 11:05:16.563  3993  4039 I jxcore-log: 
,08-31 11:05:16.566  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.566  3993  4039 I jxcore-log: 
,08-31 11:05:16.568  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-31 11:05:16.568  3993  4039 I jxcore-log: 
08-31 11:05:16.569  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-31 11:05:16.569  3993  4039 I jxcore-log: 
08-31 11:05:16.570  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-31 11:05:16.570  3993  4039 I jxcore-log: 
,08-31 11:05:16.571  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.571  3993  4039 I jxcore-log: 
,08-31 11:05:16.572  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.572  3993  4039 I jxcore-log: 
08-31 11:05:16.573  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-31 11:05:16.573  3993  4039 I jxcore-log: 
08-31 11:05:16.573  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.573  3993  4039 I jxcore-log: 
08-31 11:05:16.574  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.574  3993  4039 I jxcore-log: 
,08-31 11:05:16.574  3993  4447 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
08-31 11:05:16.575  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.575  3993  4039 I jxcore-log: 
08-31 11:05:16.576  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.576  3993  4039 I jxcore-log: 
08-31 11:05:16.577  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.577  3993  4039 I jxcore-log: 
,08-31 11:05:16.578  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.578  3993  4039 I jxcore-log: 
08-31 11:05:16.579  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.579  3993  4039 I jxcore-log: 
08-31 11:05:16.580  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.580  3993  4039 I jxcore-log: 
08-31 11:05:16.581  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.581  3993  4039 I jxcore-log: 
,08-31 11:05:16.582  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.582  3993  4039 I jxcore-log: 
08-31 11:05:16.583  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.583  3993  4039 I jxcore-log: 
08-31 11:05:16.584  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.584  3993  4039 I jxcore-log: 
,08-31 11:05:16.584  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.584  3993  4039 I jxcore-log: 
08-31 11:05:16.585  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.585  3993  4039 I jxcore-log: 
,08-31 11:05:16.586  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.586  3993  4039 I jxcore-log: 
08-31 11:05:16.587  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.587  3993  4039 I jxcore-log: 
,08-31 11:05:16.587  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.587  3993  4039 I jxcore-log: 
,08-31 11:05:16.588  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.588  3993  4039 I jxcore-log: 
,08-31 11:05:16.589  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.589  3993  4039 I jxcore-log: 
08-31 11:05:16.590  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.590  3993  4039 I jxcore-log: 
08-31 11:05:16.591  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.591  3993  4039 I jxcore-log: 
08-31 11:05:16.591  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.591  3993  4039 I jxcore-log: 
,08-31 11:05:16.592  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.592  3993  4039 I jxcore-log: 
,08-31 11:05:16.593  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.593  3993  4039 I jxcore-log: 
,08-31 11:05:16.594  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.594  3993  4039 I jxcore-log: 
08-31 11:05:16.595  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.595  3993  4039 I jxcore-log: 
,08-31 11:05:16.595  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.595  3993  4039 I jxcore-log: 
,08-31 11:05:16.596  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.596  3993  4039 I jxcore-log: 
,08-31 11:05:16.597  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.597  3993  4039 I jxcore-log: 
08-31 11:05:16.598  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.598  3993  4039 I jxcore-log: 
,08-31 11:05:16.598  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.598  3993  4039 I jxcore-log: 
,08-31 11:05:16.599  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:05:16.599  3993  4039 I jxcore-log: 
,08-31 11:05:16.600  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.600  3993  4039 I jxcore-log: 
08-31 11:05:16.601  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:05:16.601  3993  4039 I jxcore-log: 
08-31 11:05:16.601  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.601  3993  4039 I jxcore-log: 
,08-31 11:05:16.602  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.602  3993  4039 I jxcore-log: 
,08-31 11:05:16.604  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.604  3993  4039 I jxcore-log: 
,08-31 11:05:16.605  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.605  3993  4039 I jxcore-log: 
08-31 11:05:16.605  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.605  3993  4039 I jxcore-log: 
08-31 11:05:16.606  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.606  3993  4039 I jxcore-log: 
08-31 11:05:16.607  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.607  3993  4039 I jxcore-log: 
08-31 11:05:16.607  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-31 11:05:16.607  3993  4039 I jxcore-log: 
08-31 11:05:16.608  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.608  3993  4039 I jxcore-log: 
08-31 11:05:16.608  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.608  3993  4039 I jxcore-log: 
08-31 11:05:16.609  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-31 11:05:16.609  3993  4039 I jxcore-log: 
08-31 11:05:16.609  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:05:16.609  3993  4039 I jxcore-log: 
08-31 11:05:16.610  3993  4039 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:05:16.610  3993  4039 I jxcore-log: 
,08-31 11:05:17.187  4450  4450 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 11:05:17.192  4450  4450 D AndroidRuntime: CheckJNI is OFF
,08-31 11:05:17.236  4450  4450 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 11:05:17.283  4450  4450 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 11:05:17.307  4450  4450 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:05:17.317   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 11:05:17.317   871   884 I ActivityManager: Killing 3993:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 11:05:17.382   871   881 D GraphicsStats: Buffer count: 2
08-31 11:05:17.383   871  1314 D WifiService: Client connection lost with reason: 4
,08-31 11:05:17.383   871  2217 I WindowState: WIN DEATH: Window{b95782 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:05:17.420   871   894 W PackageSettings: Skipping PackageSetting{d5b656c com.example.hello/10273} due to missing metadata
,08-31 11:05:17.446   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-31 11:05:17.446   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 11:05:17.447   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-31 11:05:17.447   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 11:05:17.447   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.447   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.447   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:05:17.447   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 11:05:17.448   871   884 I ActivityManager:   Force finishing activity ActivityRecord{ac0cf0f u0 com.test.thalitest/.MainActivity t2}
08-31 11:05:17.449   871   894 I art     : Starting a blocking GC Explicit
,08-31 11:05:17.457   871  1432 W ActivityManager: Spurious death for ProcessRecord{d405b50 0:com.test.thalitest/u0a0}, curProc for 3993: null
,08-31 11:05:17.491   871   894 I art     : Explicit concurrent mark sweep GC freed 22537(1372KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 738us total 41.688ms
,08-31 11:05:17.514   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 11:05:17.518  4450  4450 I art     : System.exit called, status: 0
,08-31 11:05:17.519  4450  4450 I AndroidRuntime: VM exiting with result code 0.
08-31 11:05:17.520   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 11:05:17.535   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 11:05:17.539  4339  4339 D BluetoothMapAppObserver: onReceive
08-31 11:05:17.539  4339  4339 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 11:05:17.544  2203  2317 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 11:05:17.545   871  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 11:05:17.545  1869  1869 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 11:05:17.546  3794  3794 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-31 11:05:17.555  1869  4461 I Keyboard.Facilitator.DecoderInitializer: run()
08-31 11:05:17.558  1869  4461 I Decoder : createOrResetDecoder
,08-31 11:05:17.560  1932  1932 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 11:05:17.597   871   884 I ActivityManager: Start proc 4464:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 11:05:17.607  1534  1534 I ConfigService: onCreate
,08-31 11:05:17.630  1869  4461 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 11:05:17.653  4464  4464 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 11:05:17.660  1869  4461 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 11:05:17.662   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 11:05:17.663   871   882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3993 uid 10000
08-31 11:05:17.664  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-31 11:05:17.665  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-31 11:05:17.665  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 11:05:17.667  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 11:05:17.667  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-31 11:05:17.668  1944  2030 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 11:05:17.668  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-31 11:05:17.668  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 11:05:17.669   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-31 11:05:17.669   871   883 E PackageManager: Failed to write settings, restoring backup
08-31 11:05:17.669   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 11:05:17.669   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 11:05:17.669   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 11:05:17.669   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 11:05:17.669   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 11:05:17.669   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.669   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.669   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.670  1869  4461 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-31 11:05:17.670  1869  4461 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 11:05:17.671  1869  4461 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-31 11:05:17.673  1869  4461 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 11:05:17.673  1869  4461 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 11:05:17.673  1869  4461 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 11:05:17.681   871  2217 I ActivityManager: Start proc 4479:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-31 11:05:17.681  1944  2030 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 11:05:17.681  1944  2030 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-31 11:05:17.681  1944  2030 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.681  1944  2030 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.683   871  1949 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:05:17.688  1944  2030 I Process : Sending signal. PID: 1944 SIG: 9,
,08-31 11:05:17.690   871  4484 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:05:17.690   871  4484 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.690   871  4484 E DropBoxManagerService: 	... 5 more
,08-31 11:05:17.691   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-31 11:05:17.691   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 11:05:17.691   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.691   871   884 E DropBoxManagerService: 	... 13 more
,08-31 11:05:17.722  4464  4464 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 11:05:17.738  4464  4495 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 11:05:17.741   871   882 I ActivityManager: Start proc 4496:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 11:05:17.745   871  2389 D GraphicsStats: Buffer count: 1
,08-31 11:05:17.745   871  1949 I WindowState: WIN DEATH: Window{8ac40a2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 11:05:17.756   871  2389 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1944) has died
,08-31 11:05:17.756   871  2389 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-31 11:05:17.757   871  2389 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:05:17.774   871   881 I ActivityManager: Start proc 4509:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:05:17.798  4496  4496 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 11:05:17.819  4509  4509 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:05:17.819  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:05:17.819  4509  4509 D AndroidRuntime: Shutting down VM
08-31 11:05:17.824  4509  4509 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:05:17.824  4509  4509 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4509
08-31 11:05:17.824  4509  4509 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:05:17.824  4509  4509 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:05:17.824  4509  4509 E AndroidRuntime: 	... 10 more
08-31 11:05:17.828   871  2389 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:05:17.829  4509  4509 I Process : Sending signal. PID: 4509 SIG: 9
08-31 11:05:17.830   871  4525 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:05:17.830   871  4525 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.830   871  4525 E DropBoxManagerService: 	... 5 more
,08-31 11:05:17.841  1534  1534 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 11:05:17.842  1534  1534 D AndroidRuntime: Shutting down VM
08-31 11:05:17.842  1534  1534 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:05:17.842  1534  1534 E AndroidRuntime: Process: com.google.process.gapps, PID: 1534
08-31 11:05:17.842  1534  1534 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 11:05:17.842  1534  1534 E AndroidRuntime: 	... 8 more
,08-31 11:05:17.845   871  4526 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:05:17.845   871  4526 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.845   871  4526 E DropBoxManagerService: 	... 5 more
,08-31 11:05:17.847  1534  1534 I Process : Sending signal. PID: 1534 SIG: 9
,08-31 11:05:17.851   871  1926 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4509) has died
,08-31 11:05:17.852   871  1926 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:05:17.866   871   884 I ActivityManager: Start proc 4527:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:05:17.866  4464  4493 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.866  4464  4493 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.878  4464  4493 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.885   871  2183 I ActivityManager: Killing 3846:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 11:05:17.908  4527  4527 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:05:17.908  4527  4527 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:05:17.908  4527  4527 D AndroidRuntime: Shutting down VM
,08-31 11:05:17.916  4464  4493 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 11:05:17.922  4464  4495 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.922  4464  4495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.922  4464  4495 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 11:05:17.922  4464  4495 E AndroidRuntime: Process: android.process.acore, PID: 4464
08-31 11:05:17.922  4464  4495 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.922  4464  4495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:05:17.923  4464  4493 I Process : Sending signal. PID: 4464 SIG: 9
,08-31 11:05:17.932   871  1314 D WifiService: Client connection lost with reason: 4
,08-31 11:05:17.933  1756  4524 E BulkCursor: Unable to get window because the remote process is dead
08-31 11:05:17.933  1756  4524 W BulkCursor: Remote process exception when closing
,08-31 11:05:17.969   871  2217 I ActivityManager: Process com.google.process.gapps (pid 1534) has died
,08-31 11:05:17.969   871  2217 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-31 11:05:17.969   871  2217 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-31 11:05:17.969   871  2217 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-31 11:05:17.971  1756  4524 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 11:05:17.972  1756  4524 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 11:05:17.976   871  4540 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:05:17.976   871  4540 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.976   871  4540 E DropBoxManagerService: 	... 5 more
,08-31 11:05:17.977  1756  4524 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 11:05:17.977  1756  4524 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 11:05:17.978  4527  4527 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:05:17.978  4527  4527 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4527
08-31 11:05:17.978  4527  4527 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at com.,android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:05:17.978  4527  4527 E AndroidRuntime: 	... 10 more
08-31 11:05:17.978  1756  1756 W RocketImpressions: ClearcutLogger connection suspended: 1
08-31 11:05:17.982   871  2010 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:05:17.983   871  4541 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:05:17.983   871  4541 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:05:17.983   871  4541 E DropBoxManagerService: 	... 5 more
,08-31 11:05:17.988   871   881 I ActivityManager: Process android.process.acore (pid 4464) has died
,08-31 11:05:17.988   871   881 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30981ms
,08-31 11:05:17.992  4527  4527 I Process : Sending signal. PID: 4527 SIG: 9
,08-31 11:05:18.006   871   882 I ActivityManager: Start proc 4543:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-31 11:05:18.012  1756  4524 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-31 11:05:18.013  1756  4524 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 11:05:18.015   871   881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4527) has died
,08-31 11:05:18.016   871   881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:05:18.026   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
