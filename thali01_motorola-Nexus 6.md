#### Test 8291203064a8f9d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 14:40:25.865   874  1879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=301917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:40:26.562  3996  3996 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 14:40:26.567  3996  3996 D AndroidRuntime: CheckJNI is OFF
09-08 14:40:26.610  3996  3996 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 14:40:26.661  3996  3996 I Radio-JNI: register_android_hardware_Radio DONE
09-08 14:40:26.683  3996  3996 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 14:40:26.687   874  1945 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 14:40:26.745   874  1945 I ActivityManager: Start proc 4005:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 14:40:26.748  3996  3996 D AndroidRuntime: Shutting down VM
09-08 14:40:26.898  4005  4005 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 14:40:26.920  4005  4005 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 14:40:26.928  4005  4005 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2977-2980)
09-08 14:40:26.928  4005  4005 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:40:26.944  4005  4005 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e2f743}
09-08 14:40:26.945  4005  4005 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:40:26.946  4005  4005 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:40:26.954  4005  4005 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:40:26.955  4005  4005 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:40:26.986  4005  4005 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 14:40:27.006  4005  4005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:40:27.007  4005  4005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:40:27.007  4005  4005 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 14:40:27.007  4005  4005 I Adreno  : Build Date                       : 10/20/15
09-08 14:40:27.007  4005  4005 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 14:40:27.007  4005  4005 I Adreno  : Local Branch                     : M14
09-08 14:40:27.007  4005  4005 I Adreno  : Remote Branch                    : 
09-08 14:40:27.007  4005  4005 I Adreno  : Remote Branch                    : 
09-08 14:40:27.007  4005  4005 I Adreno  : Reconstruct Branch               : 
,09-08 14:40:27.072   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff1a31d:true
,09-08 14:40:27.119  4005  4005 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 14:40:27.134  4005  4005 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 14:40:27.180  4005  4043 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 14:40:27.192  4005  4029 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 14:40:27.221  4005  4043 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 14:40:27.237  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-08 14:40:27.287   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +442ms (total +580ms)
,09-08 14:40:27.315  4005  4005 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4005
,09-08 14:40:27.397  4005  4005 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 14:40:27.568  4005  4044 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1659111120
,09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 14:40:27.576  4005  4044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b879d6 added. We now have 1 listener(s)
,09-08 14:40:27.581  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 14:40:27.582  4005  4044 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:40:27.582  4005  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:40:27.583  4005  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 14:40:27.587  4005  4044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469742d added. We now have 1 listener(s)
09-08 14:40:27.587  4005  4044 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:40:27.591   874  1312 D WifiService: New client listening to asynchronous messages
09-08 14:40:27.592  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:40:27.592  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 14:40:27.592  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 14:40:27.592  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 14:40:27.592  4005  4044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 14:40:27.601  4005  4044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:40:27.601  4005  4044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 14:40:27.617  4005  4044 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:27.618  4005  4044 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:27.618  4005  4044 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-08 14:40:27.618  4005  4044 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:40:27.618  4005  4044 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 14:40:27.627  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:27.630  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:27.648  4005  4005 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 14:40:28.493  4005  4051 W jxcore-log: Initializing JXcore engine
,09-08 14:40:28.493  4005  4051 W jxcore-log: JXcore engine is ready
,09-08 14:40:28.528  4051  4051 W Thread-361: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 14:40:28.528  4051  4051 W Thread-361: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11827]" dev="sockfs" ino=11827 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 14:40:28.528  4051  4051 W Thread-361: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 14:40:28.528  4051  4051 W Thread-361: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[29716]" dev="sockfs" ino=29716 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 14:40:28.542  4005  4051 W jxcore-log: Starting JXcore engine
,09-08 14:40:28.620  4005  4051 W jxcore-log: Platform android
09-08 14:40:28.620  4005  4051 W jxcore-log: 
,09-08 14:40:28.621  4005  4051 W jxcore-log: Process ARCH arm
09-08 14:40:28.621  4005  4051 W jxcore-log: 
,09-08 14:40:28.817  4005  4051 I jxcore-log: JXcore Cordova bridge is ready!
09-08 14:40:28.817  4005  4051 I jxcore-log: 
,09-08 14:40:28.817  4005  4051 W jxcore-log: JXcore engine is started
,09-08 14:40:28.826  4005  4044 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 14:40:28.833  4005  4005 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 14:40:40.294  3252  4053 V KeepSync: Connecting to GoogleApiClient
09-08 14:40:40.294   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:40:40.356  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 14:40:40.359  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:40:40.395  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 14:40:40.395  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 14:40:40.395  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:40:40.395  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:40:40.415  1717  4054 V BaseAuthAsyncOperation: access token request failed
09-08 14:40:40.416  3252  4053 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:40:40.469  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 14:40:40.469  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 14:40:40.470  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:40:40.470  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:40:40.496  3252  4053 E KeepSync: IOException
09-08 14:40:40.496  3252  4053 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:40:40.496  3252  4053 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:40:40.496  3252  4053 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:40:40.496  3252  4053 E KeepSync: 	... 10 more
09-08 14:40:40.496  3252  4053 W KeepSync: Sync result 2
,09-08 14:40:40.509   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 316212, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:40:42.633  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 14:40:42.633  4005  4051 I jxcore-log: 
,09-08 14:40:42.636  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 14:40:42.636  4005  4051 I jxcore-log: 
,09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:42.649  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:42.655  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:40:42.657  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 14:40:42.657  4005  4051 I jxcore-log: 
,09-08 14:40:42.659  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 14:40:42.659  4005  4051 I jxcore-log: 
,09-08 14:40:43.007  4005  4051 I jxcore-log: Running unit tests
09-08 14:40:43.007  4005  4051 I jxcore-log: 
,09-08 14:40:43.008  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:40:43.008  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ca9e56 added. We now have 2 listener(s)
09-08 14:40:43.009  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:40:43.009  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:40:43.009  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:40:43.010  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:40:43.010  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ced7 added. We now have 2 listener(s)
09-08 14:40:43.010  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:40:43.011  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:40:43.013  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:43.019  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:43.022  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:43.022  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:40:43.023  4005  4051 D executeNativeTests: Running unit tests
,09-08 14:40:43.029  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.031  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.120  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:40:43.120  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d added. We now have 3 listener(s)
,09-08 14:40:43.121  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:40:43.121  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:40:43.121  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:40:43.121  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:40:43.122  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 added. We now have 3 listener(s)
09-08 14:40:43.122  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:40:43.122  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:40:43.124  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:43.139  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:43.152  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:40:43.152  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:40:43.155  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.158  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.160  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:40:43.161  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:40:43.161  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:40:43.161  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:40:43.162  4005  4051 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 14:40:43.163  4005  4051 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 14:40:43.164  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:40:43.164  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:40:43.164  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:40:43.164  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:40:43.165  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:40:43.165  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:43.165  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:40:43.166  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:40:43.166  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.166  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:40:43.166  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:40:43.166  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d removed from the list
09-08 14:40:43.166  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:43.166  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 removed from the list
09-08 14:40:43.166  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:40:43.166  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.167  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.167  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:40:43.170  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:40:43.170  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:40:43.170  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:43.171  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:40:43.176  4005  4051 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 14:40:43.178  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:40:43.178  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:43.179  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:40:43.179  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:40:43.179  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.179  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.180  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
,09-08 14:40:43.180  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:43.180  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:40:43.180  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:40:43.181  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.181  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:40:43.181  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.181  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.183  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:40:43.183  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:40:43.183  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:40:43.183  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:40:43.188  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:40:43.188  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:40:43.189  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:40:43.190  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-08 14:40:43.191  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:40:43.191  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:43.191  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:40:43.191  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:40:43.191  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.191  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:40:43.191  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:43.191  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:40:43.191  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:40:43.191  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.191  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:43.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:43.192  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:40:43.192  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:40:43.192  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:43.192  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:40:43.193  4005  4051 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:40:43.195  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:43.203  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:43.207  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:43.208  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:40:43.208  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:40:43.209  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 14:40:43.209  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:40:43.209  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:40:43.210  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.210  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:40:43.212  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:43.218  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:40:43.218  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:40:43.228  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:40:43.233  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:40:43.235  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:40:43.241  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 14:40:43.248  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 14:40:43.249  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 14:40:43.249  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 14:40:43.250  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:40:43.252  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:40:43.264  2872  3026 D BtGatt.GattService: registerClient() - UUID=83e24548-0fab-48f4-ba25-40081608b00d
,09-08 14:40:43.265  2872  2893 D BtGatt.GattService: onClientRegistered() - UUID=83e24548-0fab-48f4-ba25-40081608b00d, clientIf=5
,09-08 14:40:43.266  4005  4015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:40:43.267  2872  2883 D BtGatt.GattService: start scan with filters
,09-08 14:40:43.274  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:40:43.275  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:40:43.275  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:40:43.275  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:40:43.275  2872  2897 D BtGatt.ScanManager: handling starting scan
,09-08 14:40:43.278  2872  2897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:40:43.286  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:40:43.288  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 14:40:43.288  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:40:43.292  2872  2893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 14:40:43.293  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:43.293  2872  2897 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:40:43.296  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:40:43.303  4005  4051 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:40:43.312  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 14:40:43.312  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:43.312  2872  2897 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:40:43.312  2872  2897 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:40:43.349  2872  2893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 14:40:43.349  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:43.373  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:40:43.374  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:43.791  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:40:43.791  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:40:43.792  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:40:44.875  2872  2872 D BtGatt.ScanManager: awakened up at time 320927
,09-08 14:40:44.878  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:44.930  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 14:40:44.930  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:44.931  2872  2893 D BtGatt.GattService: current time is 320984090324
,09-08 14:40:44.933  2872  2893 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -98, 6, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -94, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:40:44.939  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 14:40:44.942  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:40:44.943  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 14:40:44.945  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:40:44.946  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:40:44.947  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:40:44.949  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:40:46.432  2872  2872 D BtGatt.ScanManager: awakened up at time 322485
,09-08 14:40:46.434  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:46.448  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:40:46.448  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:47.951  2872  2872 D BtGatt.ScanManager: awakened up at time 324003
,09-08 14:40:47.953  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:48.007  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 14:40:48.008  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:48.008  2872  2893 D BtGatt.GattService: current time is 324061071874
,09-08 14:40:48.009  2872  2893 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -67, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -80, 2, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0]
,09-08 14:40:48.010  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:40:48.011  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 14:40:48.012  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 14:40:48.012  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:40:48.013  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 14:40:48.014  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 14:40:48.312  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:40:48.313  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:48.313  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 14:40:48.314  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:48.314  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:40:48.314  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:40:48.315  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:40:48.315  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 14:40:48.316  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:40:48.318  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:40:48.318  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 14:40:48.321  4005  4051 D BluetoothAdapter: STATE_ON
09-08 14:40:48.323  2872  3026 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:40:48.326  2872  2883 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:40:48.328  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:40:48.329  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 14:40:48.329  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:40:48.329  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:40:48.330  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:40:48.333  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:40:48.334  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:40:48.335  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:40:48.335  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:40:48.337  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:40:48.340  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:40:48.341  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:40:48.341  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:40:48.342  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:40:48.342  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:48.343  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:40:48.343  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
,09-08 14:40:48.343  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:48.343  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:40:48.344  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:40:48.346  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:40:48.347  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 14:40:48.347  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:48.347  2872  2897 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:40:48.366  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:40:48.366  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:48.366  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:48.385  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:40:48.385  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:48.843  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:40:51.865   874  1879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 14:40:53.348  4005  4051 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 14:40:53.354  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:53.368  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:53.374  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:40:53.375  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:40:53.376  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:40:53.378  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:40:53.379  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 14:40:53.380  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:40:53.381  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:40:53.383  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:53.390  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:40:53.398  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 14:40:53.398  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:40:53.413  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:40:53.415  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:40:53.416  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:40:53.426  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:40:53.427  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:40:53.427  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:40:53.430  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:40:53.437  2872  3026 D BtGatt.GattService: registerClient() - UUID=1f9223f1-407c-4a25-8965-c4d62f4318ad
,09-08 14:40:53.439  2872  2893 D BtGatt.GattService: onClientRegistered() - UUID=1f9223f1-407c-4a25-8965-c4d62f4318ad, clientIf=5
09-08 14:40:53.440  4005  4016 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:40:53.441  2872  2883 D BtGatt.GattService: start scan with filters
,09-08 14:40:53.450  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:40:53.451  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:40:53.451  2872  2897 D BtGatt.ScanManager: handling starting scan
09-08 14:40:53.451  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 14:40:53.451  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:40:53.464  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:40:53.465  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:40:53.466  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:40:53.468  2872  2893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:40:53.469  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.469  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:40:53.469  2872  2897 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:40:53.472  4005  4051 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:40:53.476  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:40:53.476  4005  4051 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 14:40:53.476  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:53.476  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:40:53.476  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:53.476  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:40:53.476  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:40:53.476  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:40:53.477  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:40:53.477  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:40:53.477  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:40:53.477  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 14:40:53.478  4005  4051 D BluetoothAdapter: STATE_ON
09-08 14:40:53.479  2872  3026 D BtGatt.GattService: stopScan() - queue size =1
09-08 14:40:53.479  2872  2883 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:40:53.480  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:40:53.480  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 14:40:53.480  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:40:53.480  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:40:53.480  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 14:40:53.481  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:40:53.481  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:40:53.482  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:40:53.482  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:40:53.483  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:40:53.486  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:40:53.486  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:40:53.486  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:40:53.486  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:40:53.486  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:53.486  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:40:53.486  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:40:53.487  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.487  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:40:53.487  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:40:53.488  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:40:53.488  2872  2897 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:40:53.488  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:40:53.488  2872  2897 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 14:40:53.488  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:53.489  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:53.489  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:40:53.491  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:40:53.491  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:40:53.491  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:40:53.491  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:40:53.493  4005  4051 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 14:40:53.496  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:40:53.502  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:40:53.504  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:40:53.505  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:40:53.505  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:40:53.505  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:40:53.506  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:40:53.506  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:40:53.506  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:40:53.511  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:40:53.511  2872  2893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 14:40:53.511  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:53.518  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:40:53.518  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:40:53.522  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:40:53.522  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.522  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:40:53.524  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:40:53.525  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:40:53.525  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:40:53.529  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 14:40:53.529  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:40:53.529  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.529  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:40:53.529  2872  2897 D BtGatt.ScanManager: stopping BLe Batch
09-08 14:40:53.529  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:40:53.530  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:40:53.533  2872  3042 D BtGatt.GattService: registerClient() - UUID=fefb5a8a-3260-4d4c-b060-88fe067e5826
09-08 14:40:53.533  2872  2893 D BtGatt.GattService: onClientRegistered() - UUID=fefb5a8a-3260-4d4c-b060-88fe067e5826, clientIf=5
09-08 14:40:53.533  4005  4016 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 14:40:53.533  2872  2884 D BtGatt.GattService: start scan with filters
,09-08 14:40:53.536  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:40:53.536  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:40:53.536  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:40:53.536  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 14:40:53.536  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.537  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 14:40:53.537  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:53.539  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:40:53.539  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:40:53.539  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:40:53.541  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 14:40:53.542  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 14:40:53.542  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:53.543  2872  2897 D BtGatt.ScanManager: handling starting scan
,09-08 14:40:53.544  4005  4051 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:40:53.550  2872  2893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 14:40:53.550  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:53.550  2872  2897 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:40:53.555  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 14:40:53.555  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:53.555  2872  2897 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:40:53.555  2872  2897 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:40:53.565  2872  2893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 14:40:53.565  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:53.572  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:40:53.572  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:54.040  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:40:54.041  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:40:54.041  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:40:55.077  2872  2872 D BtGatt.ScanManager: awakened up at time 331130
,09-08 14:40:55.082  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:55.120  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 14:40:55.120  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:55.121  2872  2893 D BtGatt.GattService: current time is 331173774145
09-08 14:40:55.122  2872  2893 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -95, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -101, 1, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:40:55.123  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 14:40:55.124  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 14:40:55.124  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 14:40:55.125  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:40:55.126  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:40:55.127  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 14:40:55.127  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:40:56.626  2872  2872 D BtGatt.ScanManager: awakened up at time 332679
,09-08 14:40:56.628  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:56.640  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:40:56.640  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:58.142  2872  2872 D BtGatt.ScanManager: awakened up at time 334194
,09-08 14:40:58.143  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:58.198  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 14:40:58.198  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:58.199  2872  2893 D BtGatt.GattService: current time is 334251413178
09-08 14:40:58.200  2872  2893 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -101, 29, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 14:40:58.200  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 14:40:58.201  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 14:40:58.202  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:40:58.203  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 14:40:58.204  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 14:40:58.205  2872  2893 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 14:40:58.544  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:40:58.544  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:40:58.545  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:40:58.545  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:40:58.545  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:40:58.546  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 14:40:58.546  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:40:58.546  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:40:58.547  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:40:58.548  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:40:58.548  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:40:58.550  4005  4051 D BluetoothAdapter: STATE_ON
09-08 14:40:58.552  2872  2883 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:40:58.555  2872  3026 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:40:58.558  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:40:58.559  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:40:58.559  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 14:40:58.560  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:40:58.560  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 14:40:58.562  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:40:58.563  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:40:58.563  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:40:58.563  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:40:58.565  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:40:58.567  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:40:58.567  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:40:58.567  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:40:58.575  2872  2893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:40:58.575  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:58.576  2872  2897 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:40:58.588  2872  2893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:40:58.589  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:40:58.589  2872  2897 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:40:58.599  2872  2893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:40:58.600  2872  2893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:40:59.068  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:40:59.069  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:40:59.069  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:41:03.568  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:41:03.569  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.569  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:41:03.571  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.571  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.571  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:41:03.572  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.572  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.572  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.572  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:03.573  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.575  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.575  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:03.578  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.579  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.579  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:03.579  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:41:03.582  4005  4051 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 14:41:03.584  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.584  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:41:03.584  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.585  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.586  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:03.586  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.586  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.587  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.587  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:41:03.588  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.588  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.589  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.589  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:03.589  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.590  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.590  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.590  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:03.591  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.592  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 14:41:03.592  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.592  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:41:03.592  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.592  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.592  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.592  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.592  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
,09-08 14:41:03.592  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.593  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.593  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.593  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:03.593  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.593  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.593  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.596  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:41:03.596  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.596  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.596  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.597  4005  4051 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-08 14:41:03.597  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.597  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.597  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.597  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:41:03.597  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.597  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.597  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.598  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.598  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.598  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.598  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.598  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.598  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.598  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.599  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:41:03.599  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.599  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.599  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.600  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 14:41:03.600  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:41:03.600  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.600  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.600  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.600  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.600  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.601  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.601  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.601  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.601  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:03.601  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.601  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.601  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.601  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.602  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.602  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.602  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.602  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.603  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:41:03.603  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:41:03.603  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:41:03.603  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:41:03.603  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:41:03.603  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:41:03.604  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:41:03.604  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:41:03.604  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:41:03.604  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:41:03.604  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.604  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.604  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.604  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.605  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.605  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.605  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:03.605  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.605  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.605  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.605  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.605  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.605  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.606  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.606  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:41:03.606  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.606  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.607  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:41:03.607  4005  4051 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:41:03.608  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:41:03.611  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:41:03.611  4005  4051 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-08 14:41:03.612  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:41:03.613  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:41:03.614  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:41:03.614  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 14:41:03.615  4005  4051 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:41:03.615  4005  4051 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-08 14:41:03.615  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:41:03.615  4005  4051 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:41:03.615  4005  4051 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 14:41:03.615  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:41:03.615  4005  4051 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:41:03.615  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 14:41:03.618  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 14:41:03.619  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 14:41:03.619  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-08 14:41:03.620  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 14:41:03.620  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 14:41:03.620  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 14:41:03.620  4005  4051 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:41:03.620  4005  4051 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 14:41:03.620  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 425)
,09-08 14:41:03.621  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.621  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.622  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.622  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.622  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.622  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:03.622  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 14:41:03.623  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
,09-08 14:41:03.623  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.623  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.623  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.623  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:03.623  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.623  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.623  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.624  4005  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:03.625  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.625  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.625  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:03.625  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.628  4005  4051 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 14:41:03.629  4005  4057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 425
09-08 14:41:03.629  4005  4057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 425)
09-08 14:41:03.629  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 425)
09-08 14:41:03.631  2872  3019 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-08 14:41:03.631  4005  4057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 425)
,09-08 14:41:03.633  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.633  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.633  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.633  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.633  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.634  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.634  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
,09-08 14:41:03.634  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.634  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.635  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.635  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.635  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.635  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.636  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.637  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.637  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.637  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.637  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.640  4005  4051 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 14:41:03.641  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.641  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.642  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.642  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.642  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.642  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.642  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.643  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.643  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.643  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.643  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.643  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.644  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.644  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:03.645  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.645  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.645  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.645  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.646  4005  4051 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 14:41:03.647  4005  4051 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 14:41:03.647  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:41:03.647  4005  4051 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 14:41:03.648  4005  4051 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:41:03.648  4005  4051 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 14:41:03.648  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:41:03.648  4005  4051 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 14:41:03.648  4005  4051 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:41:03.648  4005  4051 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:41:03.648  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:41:03.648  4005  4051 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 14:41:03.648  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:03.648  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:03.648  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:03.648  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.649  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.649  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.649  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.649  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.649  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.649  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.649  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.649  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.649  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.649  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.650  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:03.650  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:03.650  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.650  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.650  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:03.651  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.651  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:03.651  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:03.651  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:03.651  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:03.651  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:03.651  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:03.651  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:08.652  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:08.652  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.653  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:08.653  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.653  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.654  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.654  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:08.655  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:08.655  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:08.655  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:08.656  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.656  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.656  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.657  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.657  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.657  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:08.658  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.658  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.658  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:08.659  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:08.662  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:41:08.662  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:08.663  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.663  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:41:08.668  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:41:08.669  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:41:08.672  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 14:41:08.674  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 14:41:08.675  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 14:41:08.676  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:41:08.677  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 14:41:08.678  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 14:41:08.678  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:41:08.678  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:41:08.679  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:41:08.679  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:41:08.679  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.679  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:41:08.679  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:41:08.679  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.679  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.679  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:41:08.679  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:41:08.680  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:41:08.680  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.680  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.681  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:41:08.682  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:41:08.682  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:41:08.682  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:41:08.682  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:41:08.682  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:08.682  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:08.682  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:08.683  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:41:08.683  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.683  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.683  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.683  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.683  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.683  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:08.683  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.683  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.683  4005  4058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:08.683  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:08.683  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.692  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:08.692  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:08.693  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.693  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.694  4005  4058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:41:08.694  4005  4058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:41:08.694  4005  4058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 14:41:08.695  4005  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:41:08.695  4005  4051 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 14:41:08.695  4005  4051 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:41:08.696  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 14:41:08.697  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:41:08.699  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 14:41:08.699  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:08.699  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:08.699  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:08.700  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:41:08.700  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.700  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.700  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.700  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:08.700  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.700  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:08.700  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.701  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.701  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.701  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:08.702  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:08.702  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:08.702  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.703  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
,09-08 14:41:08.707  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:08.707  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:08.707  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:08.708  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:08.708  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.708  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.708  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.708  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.708  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.708  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:08.708  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.708  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.708  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.709  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.710  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:41:08.710  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:41:08.710  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.710  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.711  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:41:08.711  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:41:08.711  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:41:08.711  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:41:08.711  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.712  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.712  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af311d not in the list
09-08 14:41:08.712  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.712  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@,8fcef92 not in the list
09-08 14:41:08.712  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:08.712  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.712  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.712  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:08.712  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:08.713  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:41:08.713  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:41:08.714  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:08.714  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fcef92 not in the list
09-08 14:41:08.715  4005  4051 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 14:41:08.715  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:41:08.715  4005  4051 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 14:41:08.715  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 14:41:08.715  4005  4051 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 14:41:08.716  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:41:08.718  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 14:41:08.718  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 14:41:08.720  4005  4051 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 14:41:08.720  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:41:08.720  4005  4051 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 14:41:08.721  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
09-08 14:41:08.721  4005  4051 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 14:41:08.721  4005  4051 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 14:41:08.721  4005  4051 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 14:41:08.722  4005  4051 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 14:41:08.722  4005  4051 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 14:41:08.722  4005  4051 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 14:41:08.722  4005  4051 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-08 14:41:08.723  4005  4051 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 14:41:08.724  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:41:08.724  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb37424 added. We now have 3 listener(s)
09-08 14:41:08.724  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:08.727  4005  4051 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 14:41:08.727  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:08.727   874   884 D WifiService: setWifiEnabled: true pid=4005, uid=10000
09-08 14:41:08.727   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:41:08.735  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:08.737  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:08.754  2872  2989 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 14:41:08.754  2872  2989 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 14:41:08.763  1510  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 14:41:08.763  1510  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 14:41:08.763  1510  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:41:08.763  1510  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:41:08.777  1510  2083 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 14:41:08.777  1510  2083 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 14:41:08.782  3697  3728 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 14:41:08.782  3697  3728 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 14:41:08.782  3697  3728 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 14:41:08.782  3697  3728 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 14:41:08.782  3697  3728 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 14:41:08.782  3697  3728 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 14:41:08.782  3697  3728 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 14:41:09.182  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:41:13.735  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:41:13.735  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a39b8d added. We now have 4 listener(s)
,09-08 14:41:13.736  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:13.752  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:13.753  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a39b8d removed from the list
,09-08 14:41:13.753  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:13.753  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:13.754  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:13.759  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:41:13.760  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1c6142 added. We now have 4 listener(s)
,09-08 14:41:13.760  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:13.765  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:13.766  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1c6142 removed from the list
,09-08 14:41:13.766  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:13.766  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:13.767  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:13.769  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:41:13.769  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc3b553 added. We now have 4 listener(s)
09-08 14:41:13.770  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:13.775   874  1376 D WifiService: setWifiEnabled: false pid=4005, uid=10000
,09-08 14:41:13.776   874  1376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:41:13.787  2872  2888 D BluetoothAdapterState: Current state: ON, message: 23
09-08 14:41:13.787  2872  2888 D BluetoothAdapterProperties: Setting state to 13
,09-08 14:41:13.787  2872  2888 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 14:41:13.788  2872  2888 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 14:41:13.788  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:41:13.789  2872  2888 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:13.794  2872  2872 D BluetoothMapService: onReceive
,09-08 14:41:13.794  2872  2872 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:41:13.795  2872  2872 D BluetoothMapService: STATE_TURNING_OFF
09-08 14:41:13.795  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:13.795  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:13.795  2872  2872 D BluetoothMapService: MAP Service closeService in
09-08 14:41:13.796  2872  2872 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 14:41:13.796  2872  2872 D ObexServerSockets0: shutdown(block = true)
09-08 14:41:13.796  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 14:41:13.796  2872  3055 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 14:41:13.797  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.798  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.799  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:41:13.799  2872  2872 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 14:41:13.800  2872  3056 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 14:41:13.801  2872  3019 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-08 14:41:13.801   874  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:41:13.801   874  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 14:41:13.802   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:41:13.802   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:41:13.803  2872  2872 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 14:41:13.805  2872  2872 I BtOppRfcommListener: stopping Accept Thread
,09-08 14:41:13.805  2872  3634 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:41:13.806  2872  3634 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 14:41:13.811  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:13.815  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:13.818   874  1311 E native  : do suspend true
,09-08 14:41:13.822  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:13.822  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:13.823   874   887 I ActivityManager: Start proc 4065:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 14:41:13.823  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.823  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.824  2872  2893 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:41:13.824  2872  2888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 14:41:13.829  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:13.830  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:41:13.830  2872  2872 D HeadsetService: Received stop request...Stopping profile...
09-08 14:41:13.830  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.830  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:13.832   874  1897 D DhcpClient: Clearing IP address
09-08 14:41:13.833   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:41:13.833  1370  1387 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:13.833  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-08 14:41:13.834  1982  2259 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:13.834  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.834   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:13.834   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:13.834   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:13.835  2872  2872 D A2dpService: Received stop request...Stopping profile...
,09-08 14:41:13.836   374   872 D CommandListener: Setting iface cfg
09-08 14:41:13.836  2872  3032 D A2dpStateMachine: Exit Disconnected: -1
09-08 14:41:13.836  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.837   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 14:41:13.837  1370  1370 D BluetoothA2dp: Proxy object disconnected
09-08 14:41:13.837  2872  2872 D HidService: Received stop request...Stopping profile...
09-08 14:41:13.838  2872  2872 D HidService: Stopping Bluetooth HidService
,09-08 14:41:13.838  1370  1370 D BluetoothInputDevice: Proxy object disconnected
09-08 14:41:13.838  1370  1370 D HidProfile: Bluetooth service disconnected
09-08 14:41:13.838  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.839  2872  2872 D HealthService: Received stop request...Stopping profile...
09-08 14:41:13.839  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.839  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.839  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:13.839  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:13.840  2872  2872 D PanService: Received stop request...Stopping profile...
09-08 14:41:13.840  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.840  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:41:13.841  1370  1370 D PanProfile: Bluetooth service disconnected
09-08 14:41:13.842  2872  2872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 14:41:13.842  2872  2872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:41:13.842  2872  2893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 14:41:13.842  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.842  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.842  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.842  2872  2893 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 14:41:13.843  2872  2872 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 14:41:13.843  2872  2872 D BluetoothMapService: stop()
09-08 14:41:13.843  2872  2872 D BluetoothMapAppObserver: deinitObservers()
09-08 14:41:13.843  2872  2872 D BluetoothMapAppObserver: removeReceiver()
09-08 14:41:13.845  1370  1370 D BluetoothMap: Proxy object disconnected
,09-08 14:41:13.845  1370  1370 D MapProfile: Bluetooth service disconnected
09-08 14:41:13.847  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.847  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.847  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:13.847  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:13.848  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.848  2872  2893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-08 14:41:13.848  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.848  2872  2989 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:41:13.848  2872  2989 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 14:41:13.848  2872  2989 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:41:13.848  2872  2989 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 14:41:13.849  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.849  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.849  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:13.851  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:13.851  2872  2872 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:41:13.851  2872  2893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 14:41:13.851  2872  2872 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:41:13.852  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.852  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.852  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:13.852  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:13.852  2872  2872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 14:41:13.852  2872  2893 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-08 14:41:13.854   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 14:41:13.854   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 14:41:13.854  2872  2872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:41:13.854  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.854  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.855  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:13.855  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:13.855  2872  2872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:41:13.856  2872  2872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 14:41:13.857   402   402 E Parcel  : Reading a NULL string not supported here.
09-08 14:41:13.858   874  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 14:41:13.858  2872  2872 D BluetoothMapService: MAP Service closeService in
09-08 14:41:13.859   874  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 14:41:13.859  2872  2872 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:13.859  2872  2872 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:13.860  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:13.860  2872  2872 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:13.863   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:41:13.863   874  1311 E native  : do suspend true
09-08 14:41:13.864  2872  2888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 14:41:13.865  2872  2888 D BluetoothAdapterProperties: Setting state to 15
,09-08 14:41:13.865  2872  2888 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 14:41:13.866  1370  2107 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:41:13.866  2872  2888 I BluetoothAdapterState: Entering BleOnState
09-08 14:41:13.866  2872  2872 D BluetoothMapService: cleanup()
09-08 14:41:13.867  2872  2872 D BluetoothMapService: MAP Service closeService in
,09-08 14:41:13.867   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:13.868  1370  1393 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:41:13.871   874  1898 D DhcpClient: Receive thread stopped
09-08 14:41:13.873   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:13.873  1370  1387 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 14:41:13.874  1370  2107 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:41:13.876  1370  1393 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:41:13.878   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:13.878  1982  1992 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:13.878  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:41:13.879   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:41:13.879  2872  2888 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 14:41:13.879  2872  2888 D BluetoothAdapterProperties: Setting state to 16
09-08 14:41:13.879  2872  2888 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 14:41:13.879  2872  2888 D BluetoothAdapterProperties: onBleDisable
09-08 14:41:13.879  2872  2888 I BluetoothAdapterState: Entering PendingCommandState
09-08 14:41:13.879  2872  2889 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 14:41:13.880  2872  2989 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 14:41:13.880  2872  2989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:13.881  2872  2893 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:41:13.883  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.883  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.884  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.884  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.885  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.885  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.885  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.886  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.887  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.887  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.887  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.887  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.888  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.889  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.890  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.890   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 14:41:13.906   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 14:41:13.906   374   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:41:13.907   874  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 14:41:13.907   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:41:13.908   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 14:41:13.909   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 14:41:13.912  3585  3585 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@92f4457 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 14:41:13.914  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.915  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.916  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:13.917  4065  4065 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-08 14:41:13.928   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 14:41:13.931  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.931  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.932  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.932  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.933   874  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:41:13.933  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.933  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.934  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.934  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.935  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:13.935  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:13.935  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:13.936  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:13.936  1867  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:41:13.948   374   872 E Netd    : netlink response contains error (No such file or directory)
09-08 14:41:13.948   874  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 14:41:13.960  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:41:13.964   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22da0b9:true
09-08 14:41:13.976  4065  4065 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 14:41:13.978  4065  4065 D BluetoothMap: Create BluetoothMap proxy object
09-08 14:41:13.982  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 14:41:13.983  1510  2438 V NativeCrypto: Read error: ssl=0x9b259000: I/O error during system call, Connection timed out
09-08 14:41:13.983  1510  2438 I art     : Waiting for a blocking GC DisableMovingGc
09-08 14:41:13.986  1510  2438 I art     : Starting a blocking GC DisableMovingGc
09-08 14:41:13.987  1510  2438 V NativeCrypto: SSL shutdown failed: ssl=0x9b259000: I/O error during system call, Broken pipe
09-08 14:41:13.994   874  2175 I ActivityManager: Start proc 4086:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 14:41:14.000  4065  4065 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 14:41:14.005  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:14.008   874  1693 I ActivityManager: Killing 3385:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 14:41:14.058  4086  4086 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 14:41:14.081  2872  2893 I bt_hci  : shut_down
09-08 14:41:14.081  2872  2898 D bt_hwcfg: hw_epilog_process
,09-08 14:41:14.090  2872  2898 I bt_vendor: low_power_mode_cb
,09-08 14:41:14.115  2872  2898 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 14:41:14.116  2872  2898 I bt_vendor: epilog_cb
,09-08 14:41:14.116  2872  2898 I bt_hci  : epilog_finished_callback
,09-08 14:41:14.118  2872  2893 I bt_hci_h4: hal_close
,09-08 14:41:14.119  2872  2893 I bt_userial_vendor: device fd = 51 close
,09-08 14:41:14.242  2872  2889 D bt_stack_manager: event_shut_down_stack finished.
09-08 14:41:14.243  2872  2888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 14:41:14.246  2872  2872 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:41:14.246  2872  2888 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 14:41:14.247  2872  2872 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 14:41:14.247  2872  2872 D BtGatt.GattService: stop()
,09-08 14:41:14.247  2872  2872 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 14:41:14.250  2872  2872 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:14.251  2872  2872 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:41:14.251  2872  2872 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:14.251  2872  2872 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 14:41:14.252  2872  2888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 14:41:14.252  2872  2888 D BluetoothAdapterProperties: Setting state to 10
,09-08 14:41:14.252  2872  2888 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 14:41:14.252  2872  2888 I BluetoothAdapterState: Entering OffState
,09-08 14:41:14.254   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.,
,09-08 14:41:14.285  4086  4086 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:41:14.285  4086  4086 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.285  4086  4086 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.285  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 14:41:14.286  4086  4086 D StrictMode: 	,at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616),
09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:170)
,09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(Ac,tivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:41:14.286  4086  4086 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:41:14.286  4086  4086 D StrictMode: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:41:14.286  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:41:14.289  2872  2872 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 14:41:14.289  2872  2872 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 14:41:14.289  2872  2889 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-08 14:41:14.291  2872  2889 D bt_stack_manager: event_clean_up_stack finished.
09-08 14:41:14.291  2872  2872 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 14:41:14.293  2872  2872 I art     : System.exit called, status: 0
09-08 14:41:14.293  2872  2872 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 14:41:14.312  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:41:14.348   874  1376 I ActivityManager: Process com.android.bluetooth (pid 2872) has died
,09-08 14:41:14.353  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:14.357   874   884 I ActivityManager: Killing 3653:com.google.android.talk/u0a61 (adj 15): empty #17
,09-08 14:41:14.366  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:14.465  4086  4110 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 14:41:14.488   874   884 I ActivityManager: Start proc 4119:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-08 14:41:14.492   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fbcf561:true
,09-08 14:41:14.578  4119  4119 D AdapterServiceConfig: Adding HeadsetService
,09-08 14:41:14.578  4119  4119 D AdapterServiceConfig: Adding A2dpService
,09-08 14:41:14.580  4119  4119 D AdapterServiceConfig: Adding HidService
09-08 14:41:14.580  4119  4119 D AdapterServiceConfig: Adding HealthService
09-08 14:41:14.580  4119  4119 D AdapterServiceConfig: Adding PanService
09-08 14:41:14.580  4119  4119 D AdapterServiceConfig: Adding GattService
09-08 14:41:14.580  4119  4119 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 14:41:14.590  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:41:14.594  1717  1717 D SystemUpdateService: onCreate
,09-08 14:41:14.597  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:41:14.604  1717  4132 I SystemUpdateService: active receiver: enabled
,09-08 14:41:14.608  1717  4132 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:41:14.610  1717  4132 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 14:41:14.610  1717  4132 I SystemUpdateService: now status is 0 (complete)
09-08 14:41:14.610  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 14:41:14.610  1717  4132 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:41:14.610  1717  4132 I SystemUpdateService: file has been verified
09-08 14:41:14.610  1717  4132 I SystemUpdateService: OTA package size = 12249756
,09-08 14:41:14.614  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-08 14:41:14.615  1717  4132 I SystemUpdateService: showing system update notification
,09-08 14:41:14.616  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-08 14:41:14.618  1717  2410 I iu.SyncManager: NEXT; no task
,09-08 14:41:14.627  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 14:41:14.629  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:41:14.647   874  2058 I ActivityManager: Start proc 4134:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 14:41:14.650  1717  1717 D SystemUpdateService: onDestroy
,09-08 14:41:14.691  4134  4134 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 14:41:14.695  4134  4134 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:14.701  4134  4134 D SprintDMHelper: simOperator: 
09-08 14:41:14.701  4134  4134 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:41:14.726   874   884 I ActivityManager: Start proc 4146:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 14:41:14.728   874   884 I ActivityManager: Killing 3585:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 14:41:14.875   874   884 I ActivityManager: Start proc 4160:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-08 14:41:14.877   874   884 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 14:41:14.934  4160  4160 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-08 14:41:15.108  4160  4177 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-08 14:41:15.108  4160  4177 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 14:41:15.109  4160  4177 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 14:41:15.110  4160  4177 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 14:41:15.148  4160  4177 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-08 14:41:15.148  4160  4177 I Babel_SMS: MmsConfig.loadFromResources
,09-08 14:41:15.149  4160  4177 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 14:41:15.150  4160  4177 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 14:41:15.190  4160  4160 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:41:15.193  4160  4160 I Babel_Crash: startup - clean
,09-08 14:41:15.217  4160  4160 I Babel_telephony: TeleModule.launchCompleted
,09-08 14:41:15.230   874  2058 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 14:41:15.242  4160  4160 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-08 14:41:15.249  4160  4160 W Babel   : BAM#gBA: invalid account id: -1
,09-08 14:41:15.250  4160  4160 W Babel   : BAM#gBA: invalid account id: -1
,09-08 14:41:15.250  4160  4160 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-08 14:41:15.253  4160  4182 I Babel   : deleted: false for 0
,09-08 14:41:15.270   874  2055 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 14:41:15.317   874  2001 I ActivityManager: Start proc 4184:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 14:41:15.331  4160  4160 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:41:15.381  4184  4184 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 14:41:15.400  4160  4160 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 14:41:15.410  4160  4160 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:41:15.412  4160  4160 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:41:15.429  4160  4160 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:41:15.443  4160  4160 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:41:15.465  4160  4160 I vclib   : onServiceConnected
,09-08 14:41:15.469  4160  4196 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 14:41:15.482   874  1376 I ActivityManager: Killing 3240:android.process.acore/u0a5 (adj 15): empty #17
,09-08 14:41:15.556  4184  4184 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:41:15.556  4184  4184 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:41:15.556  4184  4184 I GAv4    :   adb logcat -s GAv4
,09-08 14:41:15.571  4184  4184 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:41:15.577  4184  4184 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:41:15.593  4184  4202 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:41:15.716  4184  4184 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 14:41:15.761  4184  4184 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 14:41:15.773  4184  4184 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1819-1825)
,09-08 14:41:15.773  4184  4184 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:41:15.783  4184  4184 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b33f147}
,09-08 14:41:15.783  4184  4184 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:41:15.783  4184  4184 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 14:41:15.792  4184  4184 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 14:41:15.793  4184  4184 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:41:15.813  4184  4184 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 14:41:15.827  4184  4184 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:41:15.828  4184  4184 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:41:15.828  4184  4184 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 14:41:15.828  4184  4184 I Adreno  : Build Date                       : 10/20/15
09-08 14:41:15.828  4184  4184 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 14:41:15.828  4184  4184 I Adreno  : Local Branch                     : M14
09-08 14:41:15.828  4184  4184 I Adreno  : Remote Branch                    : 
09-08 14:41:15.828  4184  4184 I Adreno  : Remote Branch                    : 
09-08 14:41:15.828  4184  4184 I Adreno  : Reconstruct Branch               : 
,09-08 14:41:15.892  4184  4184 I NSApplication: Starting up...
,09-08 14:41:15.895  4184  4231 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 14:41:15.926   874   885 I ActivityManager: Start proc 4236:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 14:41:15.928   874   885 I ActivityManager: Killing 3837:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 14:41:15.994  4236  4236 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 14:41:16.182   874  1376 I ActivityManager: Killing 3852:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 14:41:16.265   874  2175 I ActivityManager: Start proc 4250:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 14:41:16.335  4250  4250 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 14:41:16.379  4250  4250 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 14:41:16.437   874  2001 I ActivityManager: Killing 2128:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 14:41:18.805   874  1945 D WifiService: setWifiEnabled: true pid=4005, uid=10000
09-08 14:41:18.805   874  1945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:41:18.819   874  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 14:41:18.830  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:18.831  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:18.831  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:18.831  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:18.846  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:18.846  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:18.846  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:18.846  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:18.847  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:18.847  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:18.847  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:18.848  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:18.859   874  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 14:41:18.860   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 14:41:18.862   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 14:41:18.863   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:41:18.863   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 14:41:18.863   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 14:41:18.863   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 14:41:18.883   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 14:41:18.883   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:41:18.883   374   872 D CommandListener: Setting iface cfg
09-08 14:41:18.884   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-08 14:41:18.884   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 14:41:18.894   874  1311 E native  : do suspend true
,09-08 14:41:18.900   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 14:41:18.901   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 14:41:18.908   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:41:19.621   874  1694 I ActivityManager: Killing 3875:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-08 14:41:20.185   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:41:20.269   874  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.00 rxSuccessRate=11.25 delta 1000 -> 994
,09-08 14:41:20.274   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 14:41:20.275   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:20.297   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 14:41:20.360   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 14:41:20.363  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 14:41:20.783  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:41:20.824  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 14:41:20.825  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 14:41:20.829   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:41:20.842   874  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 14:41:20.842   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 14:41:20.843   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:20.863   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:20.879   374   872 D CommandListener: Setting iface cfg
,09-08 14:41:20.879   874  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 14:41:20.891   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 14:41:20.923   874  4286 D DhcpClient: Receive thread started
,09-08 14:41:21.012   874  1311 E native  : do suspend false
,09-08 14:41:21.029   874  1897 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 14:41:21.045   874  4286 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172466, domain null
,09-08 14:41:21.046   874  1897 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172466 seconds
,09-08 14:41:21.049   874  1897 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 14:41:21.061   874  4286 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 14:41:21.061   874  1897 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 14:41:21.065   374   872 D CommandListener: Setting iface cfg
,09-08 14:41:21.073   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 14:41:21.074   874  1897 D DhcpClient: Scheduling renewal in 86399s
,09-08 14:41:21.078   874  1311 E native  : do suspend true
,09-08 14:41:21.095   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 14:41:21.096   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
09-08 14:41:21.097   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 14:41:21.100   874  1313 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 14:41:21.108   874  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:41:21.157   874  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 14:41:21.157   874  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 14:41:21.160   874  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 14:41:21.163   874  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 14:41:21.167   874  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 14:41:21.185   874  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:21.195   874  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 14:41:21.196   874  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:21.196   874  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 14:41:21.197   874  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:21.198   874  1313 D ConnectivityService:    accepting network in place of null
09-08 14:41:21.199   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 14:41:21.201   874  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 14:41:21.205   874  4285 D NetlinkSocketObserver: NeighborEvent{elapsedMs=357257, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:41:21.248   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:21.287   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:21.288   874  4284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-08 14:41:21.296   874  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 14:41:21.297   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:21.305   874  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:21.306   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:41:21.321  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:21.321  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:21.321  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.321  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:21.323  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:21.324  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:21.324  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.324  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:21.327  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:21.327  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:21.327  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:21.327  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:21.338  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:41:21.343  1717  1717 D SystemUpdateService: onCreate
,09-08 14:41:21.351  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:41:21.377   874  4284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:41:21 GMT], X-Android-Received-Millis=[1473338481377], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473338481342]}
,09-08 14:41:21.378   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 14:41:21.378   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 14:41:21.378   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:21.379   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:41:21.382  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:41:21.384  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-08 14:41:21.386  1717  4295 I SystemUpdateService: active receiver: enabled
,09-08 14:41:21.392  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:41:21.393  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:41:21.399  4134  4134 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:21.402  1717  4297 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 14:41:21.402  1717  4297 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 14:41:21.404  1717  4297 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:41:21.406  4134  4134 D SprintDMHelper: simOperator: 
,09-08 14:41:21.406  4134  4134 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:41:21.415  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-08 14:41:21.415  1717  2410 I iu.SyncManager: NEXT; no task,
,09-08 14:41:21.422  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:21.428  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:21.438  1717  4295 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:41:21.469  1717  4295 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 14:41:21.469  1717  4295 I SystemUpdateService: now status is 0 (complete)
,09-08 14:41:21.469  1717  4295 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 14:41:21.469  1717  4295 I SystemUpdateService: file has been verified
,09-08 14:41:21.469  1717  4295 I SystemUpdateService: OTA package size = 12249756
,09-08 14:41:21.485  1717  4295 I SystemUpdateService: showing system update notification
,09-08 14:41:21.510  1717  1717 D SystemUpdateService: onDestroy
,09-08 14:41:21.514  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 14:41:21.514  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 14:41:21.514  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:41:21.514  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:41:21.534  1717  4297 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-08 14:41:22.295   874  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 14:41:22.822  4160  4301 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:41:23.814   874  2175 D WifiService: setWifiEnabled: false pid=4005, uid=10000
,09-08 14:41:23.815   874  2175 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,09-08 14:41:23.848  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:41:23.856   874  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 14:41:23.856   874  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 14:41:23.857   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:41:23.857   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:23.895   874  1311 E native  : do suspend true
,09-08 14:41:23.906   874  1897 D DhcpClient: Clearing IP address
,09-08 14:41:23.906   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:41:23.911   374   872 D CommandListener: Setting iface cfg
,09-08 14:41:23.913  1510  4306 V NativeCrypto: Read error: ssl=0x9aefc000: I/O error during system call, Connection timed out
,09-08 14:41:23.918  1510  4306 V NativeCrypto: SSL shutdown failed: ssl=0x9aefc000: I/O error during system call, Broken pipe
,09-08 14:41:23.925   874  4286 D DhcpClient: Receive thread stopped
,09-08 14:41:23.929   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 14:41:23.930   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 14:41:23.937   874  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-08 14:41:23.939   402   402 E Parcel  : Reading a NULL string not supported here.
09-08 14:41:23.943   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
09-08 14:41:23.943   874  1311 E native  : do suspend true
,09-08 14:41:23.944   874  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 14:41:23.975   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:24.004   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:24.004   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:41:24.006   874  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 14:41:24.006   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:24.009   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:41:24.012  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.013  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:24.013  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:24.013  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,09-08 14:41:24.014  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.014  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:24.014  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.014  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:24.016  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.016  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:24.016  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.016  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:24.019   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:41:24.039  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:41:24.042   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:41:24.045  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.045  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:24.045  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.045  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:24.046   874  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:41:24.046  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:24.046  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.046  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:24.047  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:24.047  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:24.047  1867  2321 W Settings: Setting airplane_mode_on has moved from android.,provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:41:24.048  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:24.048  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:24.048  1717  1717 D SystemUpdateService: onCreate
,09-08 14:41:24.058  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-08 14:41:24.068  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 14:41:24.078  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:41:24.079  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 14:41:24.081  4134  4134 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:24.086  4134  4134 D SprintDMHelper: simOperator: 
,09-08 14:41:24.086  4134  4134 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 14:41:24.087   374   872 E Netd    : netlink response contains error (No such file or directory)
09-08 14:41:24.088   874  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 14:41:24.075  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-08 14:41:24.093  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-08 14:41:24.096  1717  4318 I SystemUpdateService: active receiver: enabled
,09-08 14:41:24.114  4160  4321 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 14:41:24.124  1717  2410 I iu.SyncManager: NEXT; no task
,09-08 14:41:24.126  1717  4318 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:41:24.131  1717  4318 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 14:41:24.132  1717  4318 I SystemUpdateService: now status is 0 (complete)
09-08 14:41:24.132  1717  4318 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:41:24.132  1717  4318 I SystemUpdateService: file has been verified
09-08 14:41:24.132  1717  4318 I SystemUpdateService: OTA package size = 12249756
,09-08 14:41:24.162  1717  4318 I SystemUpdateService: showing system update notification
,09-08 14:41:24.174  1717  1717 D SystemUpdateService: onDestroy
,09-08 14:41:27.278  1902  1938 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-08 14:41:27.278  1902  1938 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 14:41:27.309  1510  1510 I ConfigService: onCreate
,09-08 14:41:28.868   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd06530:true
,09-08 14:41:28.869  4119  4119 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 14:41:28.874  4119  4119 I bt_bluedroid: init
,09-08 14:41:28.874  4119  4327 I BluetoothAdapterState: Entering OffState
,09-08 14:41:28.881  4119  4328 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 14:41:28.881  4119  4328 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 14:41:28.882  4119  4328 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 14:41:28.882  4119  4328 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-08 14:41:28.884  4119  4119 I bt_bluedroid: get_profile_interface socket
09-08 14:41:28.886  4119  4119 I bt_bluedroid: get_profile_interface sdp
09-08 14:41:28.889  4119  4331 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:41:28.892  4119  4331 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:41:28.893  4119  4131 I bt_bluedroid: config_hci_snoop_log
,09-08 14:41:28.897   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 14:41:28.912  4119  4327 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 14:41:28.913  4119  4327 D BluetoothAdapterProperties: Setting state to 14
,09-08 14:41:28.913  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 14:41:28.919  4119  4327 D BluetoothBondStateMachine: make
,09-08 14:41:28.926  4119  4332 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 14:41:28.934  4119  4327 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:28.936  4119  4119 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 14:41:28.941  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:28.942  4119  4119 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:41:28.943  4119  4119 D BtGatt.GattService: Received start request. Starting profile...
,09-08 14:41:28.943  4119  4119 D BtGatt.GattService: start()
,09-08 14:41:28.943  4119  4119 I bt_bluedroid: get_profile_interface gatt
09-08 14:41:28.945  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:28.945  4119  4119 D BtGatt.AdvertiseManager: advertise manager created
,09-08 14:41:28.957  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:28.957  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:41:28.957  4119  4119 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 14:41:28.957  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:28.958  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 14:41:28.959  4119  4327 I bt_bluedroid: enable
,09-08 14:41:28.960  4119  4328 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 14:41:28.961  4119  4328 I bt_hci  : start_up
,09-08 14:41:28.984  4119  4328 I bt_vendor: alloc value 0xb39a9189
,09-08 14:41:28.984  4119  4328 I bt_vendor: init
,09-08 14:41:28.984  4119  4328 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 14:41:28.984  4119  4328 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 14:41:29.093  4119  4328 D bt_hci  : start_up starting async portion
09-08 14:41:29.093  4119  4335 I bt_hci  : event_finish_startup
,09-08 14:41:29.094  4119  4335 I bt_hci_h4: hal_open
,09-08 14:41:29.094  4119  4335 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 14:41:29.101  4119  4335 I bt_userial_vendor: device fd = 51 open
,09-08 14:41:29.136  4119  4335 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:41:29.167  4119  4335 D bt_hwcfg: Chipset BCM4354A2
,09-08 14:41:29.168  4119  4335 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 14:41:29.168  4119  4335 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 14:41:29.201   874  1313 D ConnectivityService: handlePromptUnvalidated 101
,09-08 14:41:29.835  4119  4335 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 14:41:29.836  4119  4335 D bt_hwcfg: Settlement delay -- 100 ms
09-08 14:41:29.837  4119  4335 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 14:41:29.953  4119  4335 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:41:29.955  4119  4335 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 14:41:29.984  4119  4335 I bt_hwcfg: vendor lib fwcfg completed
,09-08 14:41:29.984  4119  4335 I bt_vendor: firmware callback
,09-08 14:41:29.985  4119  4335 I bt_hci  : firmware_config_callback
,09-08 14:41:29.997  4119  4338 I bt_btu  : btu_task pending for preload complete event
,09-08 14:41:29.997  4119  4338 I bt_btu_task: Bluetooth chip preload is complete
,09-08 14:41:29.998  4119  4338 I bt_btu  : btu_task received preload complete event
,09-08 14:41:30.009  4119  4338 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 14:41:30.009  4119  4338 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 14:41:30.009  4119  4338 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 14:41:30.009  4119  4338 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 14:41:30.010  4119  4338 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 14:41:30.010  4119  4338 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 14:41:30.010  4119  4338 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 14:41:30.011  4119  4338 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 14:41:30.011  4119  4338 I         : BTE_InitTraceLevels -- TRC_GAP
,09-08 14:41:30.011  4119  4338 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 14:41:30.011  4119  4338 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 14:41:30.012  4119  4338 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 14:41:30.012  4119  4338 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 14:41:30.012  4119  4338 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 14:41:30.012  4119  4338 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 14:41:30.156  4119  4338 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
09-08 14:41:30.156  4119  4338 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,09-08 14:41:30.172  4119  4331 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 14:41:30.173  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 14:41:30.173  4119  4331 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:41:30.180  4119  4331 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:41:30.181  4119  4331 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:41:30.181  4119  4331 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:41:30.182  4119  4331 D bt_hci  : do_postload posting postload work item
09-08 14:41:30.182  4119  4335 I bt_hci  : event_postload
09-08 14:41:30.182  4119  4335 I bt_vendor: sco_config_cb
,09-08 14:41:30.182  4119  4335 I bt_hci  : sco_config_callback postload finished.
,09-08 14:41:30.184  4119  4331 D bt_bte_conf: Device ID record 1 : primary
,09-08 14:41:30.184  4119  4331 D bt_bte_conf:   vendorId            = 000f
,09-08 14:41:30.184  4119  4331 D bt_bte_conf:   vendorIdSource      = 0001
09-08 14:41:30.184  4119  4331 D bt_bte_conf:   product             = 1200
09-08 14:41:30.184  4119  4331 D bt_bte_conf:   version             = 1436
,09-08 14:41:30.184  4119  4331 D bt_bte_conf:   clientExecutableURL = 
,09-08 14:41:30.185  4119  4331 D bt_bte_conf:   serviceDescription  = 
,09-08 14:41:30.185  4119  4331 D bt_bte_conf:   documentationURL    = 
09-08 14:41:30.185  4119  4331 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 14:41:30.185  4119  4328 D bt_stack_manager: event_start_up_stack finished
09-08 14:41:30.185  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 14:41:30.186  4119  4327 D BluetoothAdapterProperties: Setting state to 15
09-08 14:41:30.186  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 14:41:30.186  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:30.188  4119  4327 I BluetoothAdapterState: Entering BleOnState
09-08 14:41:30.190  4119  4335 I bt_vendor: low_power_mode_cb
09-08 14:41:30.191  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.193  4119  4327 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 14:41:30.194  4119  4327 D BluetoothAdapterProperties: Setting state to 11
09-08 14:41:30.193  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.195  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 14:41:30.204  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:30.207  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:30.207  4119  4119 D HeadsetService: Received start request. Starting profile...
09-08 14:41:30.208  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.210  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.213  4119  4119 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:41:30.214  4119  4119 D HeadsetStateMachine: make
09-08 14:41:30.214  4119  4327 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:30.222  4119  4119 D HeadsetStateMachine: max_hf_connections = 1
,09-08 14:41:30.222  4119  4119 I bt_bluedroid: get_profile_interface handsfree
09-08 14:41:30.222  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 14:41:30.223  4119  4331 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-08 14:41:30.226  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:30.226  4119  4119 D A2dpService: Received start request. Starting profile...
09-08 14:41:30.227  4119  4119 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 14:41:30.227  4119  4119 I bt_bluedroid: get_profile_interface avrcp
,09-08 14:41:30.233  4119  4119 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 14:41:30.234  4119  4119 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:41:30.234  4119  4119 D A2dpStateMachine: make
,09-08 14:41:30.235  4119  4119 I bt_bluedroid: get_profile_interface a2dp
09-08 14:41:30.235  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 14:41:30.237  4119  4347 D A2dpStateMachine: Enter Disconnected: -2
,09-08 14:41:30.238  4119  4119 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 14:41:30.239  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:30.240  4065  4065 D BluetoothInputDevice: Proxy object connected
,09-08 14:41:30.240  4119  4119 D HidService: Received start request. Starting profile...
09-08 14:41:30.240  4119  4119 I bt_bluedroid: get_profile_interface hidhost
09-08 14:41:30.240  4119  4119 D HidService: setHidService(): set to: null
09-08 14:41:30.240  4119  4331 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
09-08 14:41:30.241  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 14:41:30.241  4119  4119 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 14:41:30.241  4065  4065 D HidProfile: Bluetooth service connected
09-08 14:41:30.242  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:30.242  4119  4119 D HealthService: Received start request. Starting profile...
,09-08 14:41:30.244  4119  4119 I bt_bluedroid: get_profile_interface health
09-08 14:41:30.244  4119  4119 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 14:41:30.245  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:30.246  4119  4119 D PanService: Received start request. Starting profile...
09-08 14:41:30.246  4065  4065 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:41:30.246  4119  4119 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 14:41:30.247  4119  4119 I bt_bluedroid: get_profile_interface pan
,09-08 14:41:30.247  4119  4331 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 14:41:30.247  4065  4065 D PanProfile: Bluetooth service connected
09-08 14:41:30.249  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:30.250  4065  4065 D BluetoothMap: Proxy object connected
,09-08 14:41:30.251  4119  4119 D BluetoothMapService: Received start request. Starting profile...
09-08 14:41:30.251  4119  4119 D BluetoothMapService: start()
,09-08 14:41:30.251  4065  4065 D MapProfile: Bluetooth service connected
09-08 14:41:30.251  4065  4065 D BluetoothMap: getConnectedDevices()
09-08 14:41:30.252  4065  4065 D BluetoothMap: Bluetooth is Not enabled
09-08 14:41:30.253  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 14:41:30.254  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 14:41:30.254  4119  4119 D BluetoothMapAppObserver: createReceiver()
,09-08 14:41:30.255  4119  4119 D BluetoothMapAppObserver: initObservers()
09-08 14:41:30.255  4119  4119 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 14:41:30.264  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:30.264  4119  4119 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:30.264  4119  4119 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:30.264  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:30.264  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:30.267  4119  4345 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:30.268  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOn()=true
,09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:30.269  4119  4119 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:30.270  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:30.270  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:30.270  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 14:41:30.270  4119  4327 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:41:30.270  4119  4327 D BluetoothAdapterProperties: State =  11
09-08 14:41:30.272  4119  4327 D BluetoothAdapterProperties: Setting state to 12
09-08 14:41:30.272  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 14:41:30.273  1370  1387 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 14:41:30.273  4119  4327 I BluetoothAdapterState: Entering OnState
09-08 14:41:30.275  4119  4331 D BluetoothAdapterProperties: Scan Mode:21
09-08 14:41:30.275  4119  4331 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:41:30.276  4065  4077 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:41:30.276  1370  1370 D BluetoothMap: Proxy object connected
,09-08 14:41:30.276  1370  1370 D MapProfile: Bluetooth service connected
09-08 14:41:30.276  1370  1370 D BluetoothMap: getConnectedDevices()
09-08 14:41:30.276   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:30.277  1370  1387 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:41:30.279  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:41:30.279  1370  1370 D PanProfile: Bluetooth service connected
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:30.279  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:30.279   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:30.279  4065  4075 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 14:41:30.280  1370  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:30.280  1370  2107 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:41:30.281  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:30.282  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:41:30.282  1370  1370 D BluetoothInputDevice: Proxy object connected
09-08 14:41:30.282  1370  1370 D HidProfile: Bluetooth service connected
,09-08 14:41:30.282  1370  2107 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:41:30.283  4119  4119 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 14:41:30.284  4065  4077 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:41:30.285  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:30.285  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:30.286   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:30.286  4065  4075 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:41:30.286  1982  2259 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:30.287  1370  1393 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:41:30.287  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:30.287  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:30.288  4119  4119 D ObexServerSockets: Succeed to create listening sockets 
,09-08 14:41:30.288  4119  4119 D ObexServerSockets0: startAccept()
09-08 14:41:30.288  4119  4119 D ObexServerSockets0: prepareForNewConnect()
09-08 14:41:30.288   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:41:30.290   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:30.291  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:30.292  4119  4119 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 14:41:30.292  4119  4119 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 14:41:30.293   874   874 D BluetoothA2dp: Proxy object connected
,09-08 14:41:30.293  4119  4119 D BluetoothMapService: onReceive
09-08 14:41:30.293  1370  1370 D BluetoothA2dp: Proxy object connected
09-08 14:41:30.293  4119  4119 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:41:30.293  4119  4119 D BluetoothMapService: STATE_ON
09-08 14:41:30.293  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:30.294  4119  4354 D ObexServerSockets0: Accepting socket connection...
09-08 14:41:30.294  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.295  4119  4355 D ObexServerSockets0: Accepting socket connection...
09-08 14:41:30.296  4065  4065 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 14:41:30.297  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.298  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:30.299  4065  4065 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 14:41:30.305  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:41:30.309  4065  4065 D BluetoothA2dp: Proxy object connected
09-08 14:41:30.311  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:30.318  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:30.323  1370  1370 D BluetoothPbap: Proxy object connected
,09-08 14:41:30.323  1370  1370 D PbapServerProfile: Bluetooth service connected
09-08 14:41:30.323  4065  4065 D BluetoothPbap: Proxy object connected
09-08 14:41:30.323  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:41:30.323  4065  4065 D PbapServerProfile: Bluetooth service connected
09-08 14:41:30.323  4119  4119 D ObexServerSockets0: prepareForNewConnect()
,09-08 14:41:30.331  4119  4360 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:41:30.351  4119  4364 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:41:30.352  4119  4364 I BtOppRfcommListener: Accept thread started.
,09-08 14:41:30.378  1370  2107 D BluetoothHeadset: Proxy object connected
,09-08 14:41:30.379  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:30.379  1982  1995 D BluetoothHeadset: Proxy object connected
,09-08 14:41:30.379   874   874 D BluetoothHeadset: Proxy object connected
09-08 14:41:30.379   874   874 D BluetoothHeadset: Proxy object connected
09-08 14:41:30.379   874   874 D BluetoothHeadset: Proxy object connected
09-08 14:41:30.380   874   891 D BluetoothHeadset: Proxy object connected
09-08 14:41:30.380  1370  1393 D BluetoothHeadset: Proxy object connected
,09-08 14:41:30.383  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:30.386   874   891 D BluetoothHeadset: Proxy object connected
,09-08 14:41:30.387  1982  1992 D BluetoothHeadset: Proxy object connected
,09-08 14:41:30.402  4065  4077 D BluetoothHeadset: Proxy object connected
09-08 14:41:30.404  4065  4065 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:32.359  1510  1510 I ConfigService: onDestroy
,09-08 14:41:33.833  4119  4327 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 14:41:33.834  4119  4327 D BluetoothAdapterProperties: Setting state to 13
,09-08 14:41:33.834  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 14:41:33.836  4119  4327 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 14:41:33.839  4119  4327 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:33.848  4119  4119 D BluetoothMapService: onReceive
,09-08 14:41:33.849  4119  4119 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:41:33.849  4119  4119 D BluetoothMapService: STATE_TURNING_OFF
09-08 14:41:33.850  4119  4119 D BluetoothMapService: MAP Service closeService in
09-08 14:41:33.850  4119  4119 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 14:41:33.851  4119  4119 D ObexServerSockets0: shutdown(block = true)
09-08 14:41:33.852  4119  4354 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 14:41:33.855  4119  4119 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 14:41:33.855  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:33.855  4119  4355 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:33.855  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:33.857  4119  4340 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-08 14:41:33.857  4119  4119 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 14:41:33.858  4119  4119 I BtOppRfcommListener: stopping Accept Thread
,09-08 14:41:33.858  4119  4364 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:41:33.859  4119  4364 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 14:41:33.858  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:33.859  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:33.863  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:33.867  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:33.866  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:41:33.868  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:33.868  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:33.863  4119  4331 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:41:33.869  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 14:41:33.871  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:33.871  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:33.872  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:41:33.872  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:33.875  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.876  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.877  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.878  4119  4119 D HeadsetService: Received stop request...Stopping profile...
09-08 14:41:33.878  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:33.882  1370  1387 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:33.882  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-08 14:41:33.883  4119  4119 D A2dpService: Received stop request...Stopping profile...
09-08 14:41:33.883  1982  2189 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:33.883  4119  4347 D A2dpStateMachine: Exit Disconnected: -1
,09-08 14:41:33.883   874   874 D BluetoothHeadset: Proxy object disconnected
,09-08 14:41:33.883   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:33.883   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:33.884  4065  4075 D BluetoothHeadset: Proxy object disconnected
09-08 14:41:33.885   874   874 D BluetoothA2dp: Proxy object disconnected
,09-08 14:41:33.885  4065  4065 D HeadsetProfile: Bluetooth service disconnected
09-08 14:41:33.885  4065  4065 D BluetoothA2dp: Proxy object disconnected
09-08 14:41:33.885  1370  1370 D BluetoothA2dp: Proxy object disconnected
,09-08 14:41:33.887  4119  4119 D HidService: Received stop request...Stopping profile...
09-08 14:41:33.887  4119  4119 D HidService: Stopping Bluetooth HidService
,09-08 14:41:33.889  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:33.889  1370  1370 D BluetoothInputDevice: Proxy object disconnected
09-08 14:41:33.889  1370  1370 D HidProfile: Bluetooth service disconnected
09-08 14:41:33.890  4119  4119 D HealthService: Received stop request...Stopping profile...
09-08 14:41:33.889  4065  4065 D BluetoothInputDevice: Proxy object disconnected
09-08 14:41:33.891  4065  4065 D HidProfile: Bluetooth service disconnected
09-08 14:41:33.892  4119  4119 D PanService: Received stop request...Stopping profile...
,09-08 14:41:33.893  4065  4065 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:41:33.893  4065  4065 D PanProfile: Bluetooth service disconnected
,09-08 14:41:33.893  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:41:33.893  1370  1370 D PanProfile: Bluetooth service disconnected
09-08 14:41:33.894  4119  4119 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:33.894  4119  4119 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:33.894  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:33.894  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:33.894  4119  4119 D BluetoothMapService: Received stop request...Stopping profile...
09-08 14:41:33.894  4119  4119 D BluetoothMapService: stop()
09-08 14:41:33.895  4119  4119 D BluetoothMapAppObserver: deinitObservers()
09-08 14:41:33.895  4119  4119 D BluetoothMapAppObserver: removeReceiver()
,09-08 14:41:33.896  4065  4065 D BluetoothMap: Proxy object disconnected
09-08 14:41:33.896  1370  1370 D BluetoothMap: Proxy object disconnected
09-08 14:41:33.896  1370  1370 D MapProfile: Bluetooth service disconnected
09-08 14:41:33.896  4065  4065 D MapProfile: Bluetooth service disconnected
,09-08 14:41:33.898  4119  4119 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:41:33.898  4119  4119 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:41:33.898  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 14:41:33.898  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:33.898  4119  4119 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:33.898  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:33.898  4119  4119 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:33.898  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:33.898  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:33.898  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:33.898  4119  4331 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 14:41:33.900  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 14:41:33.900  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:33.900  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:41:33.900  4119  4338 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:41:33.900  4119  4338 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:41:33.900  4119  4338 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 14:41:33.900  4119  4338 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:41:33.902  1370  1370 D BluetoothPbap: Proxy object disconnected
,09-08 14:41:33.902  1370  1370 D PbapServerProfile: Bluetooth service disconnected
09-08 14:41:33.902  4119  4119 V BluetoothAdapterState: isTurningOff()=true
,09-08 14:41:33.902  4119  4119 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:33.902  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:33.902  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:33.903  4065  4065 D BluetoothPbap: Proxy object disconnected
09-08 14:41:33.903  4065  4065 D PbapServerProfile: Bluetooth service disconnected
09-08 14:41:33.903  4119  4119 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 14:41:33.903  4119  4119 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:41:33.903  4119  4331 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 14:41:33.906  4119  4119 V BluetoothAdapterState: isTurningOff()=true
09-08 14:41:33.906  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:41:33.906  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:33.907  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:33.907  4119  4119 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 14:41:33.907  4119  4331 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-08 14:41:33.907  4119  4119 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:41:33.907  4119  4119 V BluetoothAdapterState: isTurningOff()=true
,09-08 14:41:33.908  4119  4119 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:33.908  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:33.908  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:33.908  4119  4119 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:41:33.908  4119  4119 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 14:41:33.909  4119  4119 D BluetoothMapService: MAP Service closeService in
,09-08 14:41:33.909  4119  4119 V BluetoothAdapterState: isTurningOff()=true
,09-08 14:41:33.909  4119  4119 V BluetoothAdapterState: isTurningOn()=false
09-08 14:41:33.911  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:33.911  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:33.911  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 14:41:33.911  4119  4327 D BluetoothAdapterProperties: Setting state to 15
09-08 14:41:33.911  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 14:41:33.911  4119  4119 D BluetoothMapService: cleanup()
,09-08 14:41:33.911  4119  4119 D BluetoothMapService: MAP Service closeService in
09-08 14:41:33.912  4119  4327 I BluetoothAdapterState: Entering BleOnState
09-08 14:41:33.912  1370  1393 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 14:41:33.913  4065  4077 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:41:33.913   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.913  1370  1387 D BluetoothPan: onBluetoothStateChange on: false
,09-08 14:41:33.914   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.914  4065  4075 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:41:33.915  1370  2107 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.915  1370  1393 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:41:33.916  1370  1387 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:41:33.917  4065  4077 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 14:41:33.917   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.918  4065  4075 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:41:33.919  1982  2259 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.919  1370  2107 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:41:33.920   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:41:33.920  4065  4077 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:41:33.921  4065  4077 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:41:33.922  4119  4327 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 14:41:33.922  4119  4327 D BluetoothAdapterProperties: Setting state to 16,
09-08 14:41:33.922  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 14:41:33.923  4119  4327 D BluetoothAdapterProperties: onBleDisable
09-08 14:41:33.923  4119  4327 I BluetoothAdapterState: Entering PendingCommandState
09-08 14:41:33.924  4119  4328 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 14:41:33.925  4119  4338 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 14:41:33.925  4119  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-08 14:41:33.926  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.927  4119  4331 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:41:33.928  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.929  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:41:33.930  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.932  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.934  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:33.936  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:33.937  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:33.947  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:34.130  4119  4331 I bt_hci  : shut_down
,09-08 14:41:34.149  4119  4335 D bt_hwcfg: hw_epilog_process
,09-08 14:41:34.150  4119  4335 I bt_vendor: low_power_mode_cb
,09-08 14:41:34.165  4119  4335 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 14:41:34.166  4119  4335 I bt_vendor: epilog_cb
,09-08 14:41:34.166  4119  4335 I bt_hci  : epilog_finished_callback
,09-08 14:41:34.174  4119  4331 I bt_hci_h4: hal_close
,09-08 14:41:34.175  4119  4331 I bt_userial_vendor: device fd = 51 close
,09-08 14:41:34.295  4119  4328 D bt_stack_manager: event_shut_down_stack finished.
,09-08 14:41:34.298  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 14:41:34.304  4119  4119 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:41:34.305  4119  4327 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 14:41:34.307  4119  4119 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:41:34.307  4119  4119 D BtGatt.GattService: stop()
,09-08 14:41:34.308  4119  4119 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 14:41:34.315  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:34.315  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:41:34.315  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:34.315  4119  4119 V BluetoothAdapterState: isBleTurningOff()=true
09-08 14:41:34.316  4119  4327 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 14:41:34.317  4119  4327 D BluetoothAdapterProperties: Setting state to 10,
09-08 14:41:34.317  4119  4327 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 14:41:34.320  4119  4327 I BluetoothAdapterState: Entering OffState,
09-08 14:41:34.321   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 14:41:34.345  4119  4119 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 14:41:34.345  4119  4119 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 14:41:34.346  4119  4328 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 14:41:34.351  4119  4328 D bt_stack_manager: event_clean_up_stack finished.
,09-08 14:41:34.352  4119  4119 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 14:41:34.356  4119  4119 I art     : System.exit called, status: 0
,09-08 14:41:34.357  4119  4119 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 14:41:34.413   874  1693 I ActivityManager: Process com.android.bluetooth (pid 4119) has died
,09-08 14:41:38.830  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:38.830  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:38.837  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:38.838  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc3b553 removed from the list
09-08 14:41:38.838  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:38.838  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:41:38.839  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:38.845  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:41:38.846  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6bb6389 added. We now have 4 listener(s)
,09-08 14:41:38.846  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:41:38.849  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:38.849  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6bb6389 removed from the list
09-08 14:41:38.850  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:38.850  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:38.850  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:38.852  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:41:38.853  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b134f8e added. We now have 4 listener(s)
09-08 14:41:38.853  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:43.864  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:43.914   874   891 I ActivityManager: Start proc 4374:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 14:41:44.059  4374  4374 D AdapterServiceConfig: Adding HeadsetService
,09-08 14:41:44.060  4374  4374 D AdapterServiceConfig: Adding A2dpService
09-08 14:41:44.060  4374  4374 D AdapterServiceConfig: Adding HidService
09-08 14:41:44.060  4374  4374 D AdapterServiceConfig: Adding HealthService
09-08 14:41:44.060  4374  4374 D AdapterServiceConfig: Adding PanService
,09-08 14:41:44.061  4374  4374 D AdapterServiceConfig: Adding GattService
09-08 14:41:44.062  4374  4374 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 14:41:44.077   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36ddd6d:true
,09-08 14:41:44.077  4374  4374 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 14:41:44.088  4374  4386 I BluetoothAdapterState: Entering OffState
,09-08 14:41:44.088  4374  4374 I bt_bluedroid: init
,09-08 14:41:44.095  4374  4387 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 14:41:44.096  4374  4387 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 14:41:44.096  4374  4387 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 14:41:44.096  4374  4387 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 14:41:44.099  4374  4374 I bt_bluedroid: get_profile_interface socket
,09-08 14:41:44.104  4374  4374 I bt_bluedroid: get_profile_interface sdp
09-08 14:41:44.104  4374  4390 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:41:44.109  4374  4390 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:41:44.112  4374  4385 I bt_bluedroid: config_hci_snoop_log
,09-08 14:41:44.115   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 14:41:44.127  4374  4386 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 14:41:44.127  4374  4386 D BluetoothAdapterProperties: Setting state to 14
,09-08 14:41:44.128  4374  4386 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 14:41:44.133  4374  4386 D BluetoothBondStateMachine: make
,09-08 14:41:44.139  4374  4391 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 14:41:44.148  4374  4386 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:44.151  4374  4374 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 14:41:44.158  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:44.161  4374  4374 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:41:44.163  4374  4374 D BtGatt.GattService: Received start request. Starting profile...
,09-08 14:41:44.163  4374  4374 D BtGatt.GattService: start()
09-08 14:41:44.163  4374  4374 I bt_bluedroid: get_profile_interface gatt
,09-08 14:41:44.167  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:44.168  4374  4374 D BtGatt.AdvertiseManager: advertise manager created
,09-08 14:41:44.183  4374  4374 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:44.184  4374  4374 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:41:44.184  4374  4374 V BluetoothAdapterState: isBleTurningOn()=true
09-08 14:41:44.184  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:44.185  4374  4386 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 14:41:44.186  4374  4386 I bt_bluedroid: enable
09-08 14:41:44.186  4374  4387 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 14:41:44.187  4374  4387 I bt_hci  : start_up
,09-08 14:41:44.207  4374  4387 I bt_vendor: alloc value 0xb39ff189
09-08 14:41:44.207  4374  4387 I bt_vendor: init
09-08 14:41:44.208  4374  4387 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 14:41:44.208  4374  4387 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 14:41:44.317  4374  4387 D bt_hci  : start_up starting async portion
,09-08 14:41:44.318  4374  4394 I bt_hci  : event_finish_startup
,09-08 14:41:44.319  4374  4394 I bt_hci_h4: hal_open
09-08 14:41:44.319  4374  4394 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 14:41:44.328  4374  4394 I bt_userial_vendor: device fd = 51 open
,09-08 14:41:44.359  4374  4394 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:41:44.390  4374  4394 D bt_hwcfg: Chipset BCM4354A2
,09-08 14:41:44.391  4374  4394 D bt_hwcfg: Target name = [BCM4354A2]
09-08 14:41:44.391  4374  4394 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 14:41:45.237  4374  4394 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 14:41:45.238  4374  4394 D bt_hwcfg: Settlement delay -- 100 ms
09-08 14:41:45.239  4374  4394 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 14:41:45.357  4374  4394 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:41:45.358  4374  4394 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 14:41:45.386  4374  4394 I bt_hwcfg: vendor lib fwcfg completed
09-08 14:41:45.387  4374  4394 I bt_vendor: firmware callback
,09-08 14:41:45.387  4374  4394 I bt_hci  : firmware_config_callback
,09-08 14:41:45.401  4374  4396 I bt_btu  : btu_task pending for preload complete event
,09-08 14:41:45.401  4374  4396 I bt_btu_task: Bluetooth chip preload is complete
09-08 14:41:45.401  4374  4396 I bt_btu  : btu_task received preload complete event
,09-08 14:41:45.411  4374  4396 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 14:41:45.412  4374  4396 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 14:41:45.412  4374  4396 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 14:41:45.412  4374  4396 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 14:41:45.413  4374  4396 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 14:41:45.413  4374  4396 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 14:41:45.413  4374  4396 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 14:41:45.413  4374  4396 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 14:41:45.414  4374  4396 I         : BTE_InitTraceLevels -- TRC_GAP
,09-08 14:41:45.414  4374  4396 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 14:41:45.414  4374  4396 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 14:41:45.414  4374  4396 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 14:41:45.415  4374  4396 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 14:41:45.415  4374  4396 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 14:41:45.415  4374  4396 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 14:41:45.570  4374  4396 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397cd9d
09-08 14:41:45.570  4374  4396 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397cd9d 
,09-08 14:41:45.578  4374  4390 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 14:41:45.581  4374  4390 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 14:41:45.582  4374  4390 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:41:45.586  4374  4390 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:41:45.589  4374  4390 D BluetoothAdapterProperties: Scan Mode:20
,09-08 14:41:45.590  4374  4390 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 14:41:45.590  4374  4390 D bt_hci  : do_postload posting postload work item
,09-08 14:41:45.591  4374  4394 I bt_hci  : event_postload
,09-08 14:41:45.591  4374  4394 I bt_vendor: sco_config_cb
09-08 14:41:45.591  4374  4394 I bt_hci  : sco_config_callback postload finished.
09-08 14:41:45.597  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:45.601  4374  4390 D bt_bte_conf: Device ID record 1 : primary
,09-08 14:41:45.601  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:45.602  4374  4390 D bt_bte_conf:   vendorId            = 000f
09-08 14:41:45.602  4374  4390 D bt_bte_conf:   vendorIdSource      = 0001
09-08 14:41:45.602  4374  4394 I bt_vendor: low_power_mode_cb
09-08 14:41:45.602  4374  4390 D bt_bte_conf:   product             = 1200
,09-08 14:41:45.602  4374  4390 D bt_bte_conf:   version             = 1436
09-08 14:41:45.602  4374  4390 D bt_bte_conf:   clientExecutableURL = 
09-08 14:41:45.602  4374  4390 D bt_bte_conf:   serviceDescription  = 
,09-08 14:41:45.603  4374  4390 D bt_bte_conf:   documentationURL    = 
09-08 14:41:45.603  4374  4390 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 14:41:45.603  4374  4387 D bt_stack_manager: event_start_up_stack finished
,09-08 14:41:45.605  4374  4386 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 14:41:45.606  4374  4386 D BluetoothAdapterProperties: Setting state to 15
09-08 14:41:45.607  4374  4386 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 14:41:45.608  4374  4386 I BluetoothAdapterState: Entering BleOnState
,09-08 14:41:45.614  4374  4386 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 14:41:45.614  4374  4386 D BluetoothAdapterProperties: Setting state to 11
09-08 14:41:45.614  4374  4386 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 14:41:45.620  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:45.621  4374  4374 D HeadsetService: Received start request. Starting profile...
,09-08 14:41:45.627  4374  4374 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:41:45.627  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:45.627  4374  4374 D HeadsetStateMachine: make
,09-08 14:41:45.632  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:45.637  4374  4374 D HeadsetStateMachine: max_hf_connections = 1
,09-08 14:41:45.638  4374  4374 I bt_bluedroid: get_profile_interface handsfree
,09-08 14:41:45.638  4374  4390 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 14:41:45.639  4374  4390 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-08 14:41:45.642  4374  4386 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:41:45.644  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:45.645  4374  4374 D A2dpService: Received start request. Starting profile...
09-08 14:41:45.646  4374  4374 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 14:41:45.646  4374  4374 I bt_bluedroid: get_profile_interface avrcp
,09-08 14:41:45.652  4374  4374 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 14:41:45.652  4374  4374 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:41:45.652  4374  4374 D A2dpStateMachine: make
09-08 14:41:45.653  4374  4374 I bt_bluedroid: get_profile_interface a2dp
09-08 14:41:45.654  4374  4390 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 14:41:45.658  4374  4406 D A2dpStateMachine: Enter Disconnected: -2
,09-08 14:41:45.658  4374  4374 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 14:41:45.659  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:45.660  4374  4374 D HidService: Received start request. Starting profile...
09-08 14:41:45.660  4374  4374 I bt_bluedroid: get_profile_interface hidhost
09-08 14:41:45.660  4374  4374 D HidService: setHidService(): set to: null
09-08 14:41:45.660  4374  4390 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395e3e5
,09-08 14:41:45.660  4374  4390 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 14:41:45.662  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 14:41:45.662  4374  4374 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 14:41:45.663  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:45.663  4374  4374 D HealthService: Received start request. Starting profile...
,09-08 14:41:45.665  4374  4374 I bt_bluedroid: get_profile_interface health
,09-08 14:41:45.665  4374  4374 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 14:41:45.666  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
09-08 14:41:45.666  4374  4374 D PanService: Received start request. Starting profile...
09-08 14:41:45.666  4374  4374 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 14:41:45.666  4374  4374 I bt_bluedroid: get_profile_interface pan
09-08 14:41:45.667  4374  4390 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 14:41:45.673  4374  4374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:41:45.673  4374  4374 D BluetoothMapService: Received start request. Starting profile...
09-08 14:41:45.673  4374  4374 D BluetoothMapService: start()
,09-08 14:41:45.676  4374  4374 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 14:41:45.676  4374  4374 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 14:41:45.676  4374  4374 D BluetoothMapAppObserver: createReceiver()
09-08 14:41:45.677  4374  4374 D BluetoothMapAppObserver: initObservers()
,09-08 14:41:45.677  4374  4374 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 14:41:45.682  4374  4374 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:45.682  4374  4374 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:45.683  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:45.683  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:45.684  4374  4374 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:45.684  4374  4374 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:45.684  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:45.684  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:41:45.685  4374  4403 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isTurningOn()=true
,09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:45.685  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isTurningOff()=false
09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isTurningOn()=true
09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:41:45.686  4374  4374 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:41:45.686  4374  4386 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 14:41:45.687  4374  4386 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:41:45.687  4374  4386 D BluetoothAdapterProperties: State =  11
,09-08 14:41:45.689  4374  4390 D BluetoothAdapterProperties: Scan Mode:21
09-08 14:41:45.689  4374  4386 D BluetoothAdapterProperties: Setting state to 12
09-08 14:41:45.689  4374  4386 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 14:41:45.689  4374  4390 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:41:45.690  1370  1387 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:41:45.691  4374  4386 I BluetoothAdapterState: Entering OnState
,09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:45.693  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:45.694  4065  4077 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:41:45.694  1370  1370 D BluetoothMap: Proxy object connected
09-08 14:41:45.695  1370  1370 D MapProfile: Bluetooth service connected
09-08 14:41:45.695  1370  1370 D BluetoothMap: getConnectedDevices()
,09-08 14:41:45.695  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:45.696   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:45.696  4065  4065 D BluetoothInputDevice: Proxy object connected
09-08 14:41:45.696  4065  4065 D HidProfile: Bluetooth service connected
,09-08 14:41:45.697  1370  1387 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:45.699  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:41:45.700   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:45.700  4065  4075 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:41:45.700  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:41:45.700  1370  1370 D PanProfile: Bluetooth service connected
09-08 14:41:45.701  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:41:45.702  4065  4065 D BluetoothMap: Proxy object connected
09-08 14:41:45.702  1370  2107 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:41:45.702  4065  4065 D MapProfile: Bluetooth service connected
09-08 14:41:45.702  4065  4065 D BluetoothMap: getConnectedDevices()
09-08 14:41:45.702  1370  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:41:45.703  4374  4374 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:41:45.703  4374  4374 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 14:41:45.703  1370  1387 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:41:45.703  1370  1370 D BluetoothInputDevice: Proxy object connected
09-08 14:41:45.703  1370  1370 D HidProfile: Bluetooth service connected
09-08 14:41:45.704  4374  4374 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:45.705  4065  4412 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:41:45.706   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:45.706  4065  4077 D BluetoothPan: onBluetoothStateChange on: true
,09-08 14:41:45.706  4374  4374 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:41:45.708  1982  2259 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:45.708  4374  4374 D ObexServerSockets: Succeed to create listening sockets 
09-08 14:41:45.708  4374  4374 D ObexServerSockets0: startAccept()
09-08 14:41:45.708  4374  4374 D ObexServerSockets0: prepareForNewConnect()
09-08 14:41:45.708  4065  4065 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:41:45.708  1370  2107 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:41:45.708  4065  4065 D PanProfile: Bluetooth service connected
09-08 14:41:45.709   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:41:45.710  4065  4412 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:41:45.710  4374  4374 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 14:41:45.710  4374  4374 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 14:41:45.710  4065  4075 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:41:45.711   874   874 D BluetoothA2dp: Proxy object connected
09-08 14:41:45.711  1370  1370 D BluetoothA2dp: Proxy object connected
09-08 14:41:45.713  4374  4414 D ObexServerSockets0: Accepting socket connection...
09-08 14:41:45.713  4374  4413 D ObexServerSockets0: Accepting socket connection...
09-08 14:41:45.714  4065  4065 D BluetoothA2dp: Proxy object connected
09-08 14:41:45.714   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 14:41:45.715  4374  4374 D BluetoothMapService: onReceive
09-08 14:41:45.715  4374  4374 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:41:45.715  4374  4374 D BluetoothMapService: STATE_ON
09-08 14:41:45.716  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:41:45.717  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:45.721  4065  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:41:45.726  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:41:45.728  4065  4065 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:41:45.734  4065  4065 D BluetoothPbap: Proxy object connected
,09-08 14:41:45.735  4065  4065 D PbapServerProfile: Bluetooth service connected
,09-08 14:41:45.738  1370  1370 D BluetoothPbap: Proxy object connected
,09-08 14:41:45.739  1370  1370 D PbapServerProfile: Bluetooth service connected
,09-08 14:41:45.740  4374  4374 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:41:45.741  4374  4374 D ObexServerSockets0: prepareForNewConnect()
09-08 14:41:45.742  4374  4418 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:41:45.760  4374  4422 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:41:45.761  4374  4422 I BtOppRfcommListener: Accept thread started.
,09-08 14:41:45.799  1370  1387 D BluetoothHeadset: Proxy object connected
,09-08 14:41:45.799  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:45.800  1982  1995 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.800   874   891 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.801   874   874 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.801   874   874 D BluetoothHeadset: Proxy object connected
,09-08 14:41:45.801   874   874 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.802  4065  4412 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.802  1370  2107 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.802  1370  1370 D HeadsetProfile: Bluetooth service connected
09-08 14:41:45.803  4065  4065 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:45.807   874   891 D BluetoothHeadset: Proxy object connected
,09-08 14:41:45.808  1982  1992 D BluetoothHeadset: Proxy object connected
,09-08 14:41:45.810  4065  4077 D BluetoothHeadset: Proxy object connected
09-08 14:41:45.811  4065  4065 D HeadsetProfile: Bluetooth service connected
,09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:48.884  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:48.892  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:48.893  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:41:48.893  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b134f8e removed from the list
,09-08 14:41:48.893  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:41:48.894  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:48.894  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:41:48.897  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:41:48.897  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4a53af added. We now have 4 listener(s)
,09-08 14:41:48.898  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:41:48.902   874  2014 D WifiService: setWifiEnabled: false pid=4005, uid=10000
09-08 14:41:48.903   874  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:41:53.918  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:41:53.919   874  2057 D WifiService: setWifiEnabled: true pid=4005, uid=10000
09-08 14:41:53.919   874  2057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:41:53.932   874  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:53.952  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:53.957  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:41:53.962  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:41:53.967  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:41:53.976   874  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 14:41:53.977   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 14:41:53.978   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 14:41:53.979   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:41:53.979   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 14:41:53.979   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 14:41:53.980   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 14:41:53.995   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 14:41:53.996   374   872 D CommandListener: Setting iface cfg
09-08 14:41:53.996   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 14:41:53.997   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 14:41:53.998   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 14:41:54.051   874  1311 E native  : do suspend true
,09-08 14:41:54.051   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 14:41:54.065   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 14:41:54.082   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:41:55.393   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:41:55.542   874  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.88 rxSuccessRate=12.81 delta 1000 -> 994
,09-08 14:41:55.543   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 14:41:55.543   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:55.560   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 14:41:55.601   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 14:41:55.606  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 14:41:56.049  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:41:56.093  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 14:41:56.094  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 14:41:56.098   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:41:56.114   874  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 14:41:56.115   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:56.115   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 14:41:56.134   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:41:56.153   374   872 D CommandListener: Setting iface cfg
,09-08 14:41:56.154   874  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 14:41:56.162   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 14:41:56.182   874  4432 D DhcpClient: Receive thread started
,09-08 14:41:56.279   874  1311 E native  : do suspend false
,09-08 14:41:56.307   874  1897 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 14:41:56.331   874  4432 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-08 14:41:56.332   874  1897 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-08 14:41:56.336   874  1897 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 14:41:56.351   874  4432 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 14:41:56.352   874  1897 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 14:41:56.358   374   872 D CommandListener: Setting iface cfg
,09-08 14:41:56.371   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 14:41:56.375   874  1897 D DhcpClient: Scheduling renewal in 86399s
,09-08 14:41:56.376   874  1311 E native  : do suspend true
,09-08 14:41:56.404   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 14:41:56.408   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 14:41:56.410   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 14:41:56.413   874  1313 D ConnectivityService: Adding iface wlan0 to network 102
09-08 14:41:56.421   874  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:41:56.470   874  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 14:41:56.471   874  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 14:41:56.473   874  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 14:41:56.475   874  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 14:41:56.477   874  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 14:41:56.490   874  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 14:41:56.496   874  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-08 14:41:56.496   874  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 14:41:56.496   874  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 14:41:56.497   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:41:56.497   874  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-08 14:41:56.497   874  1313 D ConnectivityService:    accepting network in place of null
09-08 14:41:56.498   874  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 14:41:56.511   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392564, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:41:56.532   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:56.585   874  4430 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-08 14:41:56.596   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:41:56.603   874  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 14:41:56.603   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:56.617   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:41:56.621   874  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:56.639  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:56.641  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:56.648  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:56.651  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:56.651  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:41:56.658  1717  1717 D SystemUpdateService: onCreate
,09-08 14:41:56.663  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:41:56.670   874  4430 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:41:56 GMT], X-Android-Received-Millis=[1473338516669], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473338516636]}
,09-08 14:41:56.673   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 14:41:56.673   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 14:41:56.673   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 14:41:56.675   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 14:41:56.684  1717  4441 I SystemUpdateService: active receiver: enabled
,09-08 14:41:56.689  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:41:56.692  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-08 14:41:56.692  1717  2410 I iu.UploadsManager: num updated entries: 0
09-08 14:41:56.693  1717  2410 I iu.SyncManager: NEXT; no task
,09-08 14:41:56.700  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:41:56.701  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:41:56.703  4134  4134 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:41:56.708  1717  4444 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 14:41:56.708  1717  4444 W BaseAppContext: Using Auth Proxy for data requests.
09-08 14:41:56.709  4134  4134 D SprintDMHelper: simOperator: 
,09-08 14:41:56.709  4134  4134 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:41:56.737  1717  4444 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:41:56.741  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:56.742  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:41:56.747  1717  4441 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:41:56.773  1717  4441 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 14:41:56.773  1717  4441 I SystemUpdateService: now status is 0 (complete)
09-08 14:41:56.773  1717  4441 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:41:56.773  1717  4441 I SystemUpdateService: file has been verified
,09-08 14:41:56.773  1717  4441 I SystemUpdateService: OTA package size = 12249756
,09-08 14:41:56.780  1717  4441 I SystemUpdateService: showing system update notification
,09-08 14:41:56.794  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 14:41:56.794  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 14:41:56.794  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:41:56.794  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:41:56.802  1717  1717 D SystemUpdateService: onDestroy
,09-08 14:41:56.829  1717  4444 E MDM     : [185] SitrepService.a: Error sending sitrep.
,09-08 14:41:56.860  4160  4447 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:41:57.604   874  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:41:58.946  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:41:58.954  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:41:58.955  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:41:58.955  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4a53af removed from the list
,09-08 14:41:58.956  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:41:58.956  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:41:58.956  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:41:58.971  4005  4454 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 14:41:58.972  4005  4454 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:42:01.983  4005  4454 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 14:42:01.985  4005  4457 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 14:42:01.986  4005  4454 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:42:01.986  4005  4457 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:42:01.987  4005  4454 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:42:01.987  4005  4457 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:01.988  4005  4454 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:01.989  4005  4457 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:42:01.992  4005  4459 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: OutgoingSocketThread/Sender)
09-08 14:42:01.993  4005  4454 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 14:42:01.997  4005  4460 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: IncomingSocketThread/Sender)
,09-08 14:42:01.998  4005  4457 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 14:42:02.000  4005  4461 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: OutgoingSocketThread/Receiver)
,09-08 14:42:02.001  4005  4461 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: OutgoingSocketThread/Receiver)
,09-08 14:42:02.001  4005  4462 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: IncomingSocketThread/Receiver)
,09-08 14:42:02.003  4005  4461 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:42:02.004  4005  4462 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: IncomingSocketThread/Receiver)
09-08 14:42:02.004  4005  4462 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:42:02.004  4005  4461 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 14:42:02.004  4005  4462 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 14:42:04.503   874  1313 D ConnectivityService: handlePromptUnvalidated 102
,09-08 14:42:04.980  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 14:42:04.982  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 14:42:04.990  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16f6431 Bundle[{}]
,09-08 14:42:04.990  4005  4051 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 14:42:04.991  4005  4051 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 14:42:04.991  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 14:42:04.992  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 14:42:04.992  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 14:42:04.993  4005  4051 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 14:42:04.997  4005  4051 I System.out: Running OutgoingSocketThread
09-08 14:42:05.001  4005  4463 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-08 14:42:05.002  4005  4463 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:42:08.011  4005  4464 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 14:42:08.011  4005  4464 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:42:08.012  4005  4464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:08.012  4005  4463 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 14:42:08.012  4005  4463 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:42:08.013  4005  4463 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:08.013  4005  4464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:08.014  4005  4463 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:42:08.019  4005  4466 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: IncomingSocketThread/Sender)
09-08 14:42:08.019  4005  4464 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 14:42:08.024  4005  4468 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: IncomingSocketThread/Receiver)
09-08 14:42:08.024  4005  4467 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: OutgoingSocketThread/Sender)
09-08 14:42:08.025  4005  4468 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 470, thread name: IncomingSocketThread/Receiver)
09-08 14:42:08.025  4005  4468 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:42:08.025  4005  4468 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 470, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 14:42:08.026  4005  4463 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 14:42:08.029  4005  4469 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 471, name: OutgoingSocketThread/Receiver)
,09-08 14:42:08.031  4005  4469 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 471, thread name: OutgoingSocketThread/Receiver)
,09-08 14:42:08.031  4005  4469 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:42:08.032  4005  4469 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 471, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 14:42:11.013  4005  4051 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 480)
,09-08 14:42:11.015  4005  4051 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 14:42:11.015  4005  4051 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 481)
,09-08 14:42:11.025  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:42:11.025  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f23bc added. We now have 3 listener(s)
,09-08 14:42:11.030  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 14:42:11.030  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:42:11.030  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:42:11.031  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:42:11.031  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26daf45 added. We now have 4 listener(s)
09-08 14:42:11.031  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:42:11.031  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:42:11.034  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:42:11.043  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:42:11.050  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:42:11.050  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:42:11.051  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:42:11.051  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:42:11.051  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:42:11.051  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:11.051  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:11.051  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:11.051  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 14:42:11.051  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f23bc removed from the list
09-08 14:42:11.051  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:11.051  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26daf45 removed from the list
,09-08 14:42:11.058  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:42:11.058  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:42:11.058  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:11.059  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:11.059  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:11.061  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:42:11.061  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:11.061  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:11.061  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26daf45 not in the list
09-08 14:42:11.061  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:11.061  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:11.064  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:42:11.064  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:42:11.065  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:11.065  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26daf45 not in the list
09-08 14:42:11.066  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:11.066  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:42:11.066  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:42:11.067  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:11.067  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f23bc not in the list
09-08 14:42:11.069  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:42:11.069  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f27bcb added. We now have 3 listener(s)
,09-08 14:42:11.075  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:42:11.076  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:42:11.076  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:42:11.076  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:42:11.077  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff8bfa8 added. We now have 4 listener(s)
09-08 14:42:11.077  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:42:11.078  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:42:11.081  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:42:11.089  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:42:11.094  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:42:11.094  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:42:11.094  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:42:11.094  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:42:11.094  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:42:11.094  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:42:11.094  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:42:11.099  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:42:11.099  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:42:11.101  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:42:11.108  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:42:11.109  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:42:11.110  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:42:11.111  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:42:11.121  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 14:42:11.121  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 14:42:11.122  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:42:11.124  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:42:11.131  4374  4385 D BtGatt.GattService: registerClient() - UUID=1576ab8a-41a7-4778-a81d-d9315ff3462c
,09-08 14:42:11.132  4374  4390 D BtGatt.GattService: onClientRegistered() - UUID=1576ab8a-41a7-4778-a81d-d9315ff3462c, clientIf=5
09-08 14:42:11.133  4005  4016 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:42:11.136  4374  4411 D BtGatt.GattService: start scan with filters
,09-08 14:42:11.145  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:42:11.146  4374  4393 D BtGatt.ScanManager: handling starting scan
09-08 14:42:11.146  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:42:11.146  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:42:11.146  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:42:11.148  4374  4393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f7d61b5
,09-08 14:42:11.155  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:42:11.156  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:42:11.156  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:42:11.159  4374  4390 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 14:42:11.159  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:42:11.159  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:11.161  4374  4393 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 14:42:11.162  4005  4051 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 14:42:11.162  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 14:42:11.162  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 14:42:11.162  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:42:11.163  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:42:11.163  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:42:11.163  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 14:42:11.163  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:42:11.163  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:42:11.163  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:42:11.163  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:42:11.164  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:42:11.165  4374  4411 D BtGatt.GattService: stopScan() - queue size =1
09-08 14:42:11.165  4374  4402 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 14:42:11.166  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:42:11.166  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 14:42:11.166  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 14:42:11.166  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:42:11.166  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:42:11.167  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:42:11.167  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:42:11.167  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:42:11.167  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:42:11.168  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:11.169  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:42:11.169  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:42:11.169  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:42:11.171  4374  4390 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:42:11.171  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:11.173  4374  4393 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:42:11.173  4374  4393 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 14:42:11.188  4374  4390 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 14:42:11.188  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:11.197  4374  4390 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 14:42:11.197  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:11.209  4374  4390 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 14:42:11.209  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:11.210  4374  4393 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:42:11.220  4374  4390 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:42:11.220  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:11.221  4374  4393 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:42:11.233  4374  4390 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:42:11.233  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:11.671  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 14:42:11.671  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:42:11.671  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:42:14.170  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:42:14.171  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:42:14.171  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:42:14.172  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:14.173  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:14.173  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:14.173  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:42:14.174  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f27bcb removed from the list
09-08 14:42:14.174  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:14.174  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff8bfa8 removed from the list
09-08 14:42:14.174  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:42:14.175  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:14.176  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:14.177  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:14.180  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:42:14.180  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:14.181  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:14.181  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff8bfa8 not in the list
,09-08 14:42:14.181  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:14.182  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:14.185  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:42:14.185  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:42:14.186  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:42:14.186  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff8bfa8 not in the list
09-08 14:42:14.186  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:42:14.187  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:14.187  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:14.188  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f27bcb not in the list
09-08 14:42:14.189  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:42:14.189  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f81fd added. We now have 3 listener(s)
09-08 14:42:14.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 14:42:14.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:42:14.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:42:14.191  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:42:14.191  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@939ef2 added. We now have 4 listener(s)
,09-08 14:42:14.191  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:42:14.192  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:42:14.196  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:42:14.201  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:42:14.203  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:14.203  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:42:14.204  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:42:14.206  4005  4051 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1,
,09-08 14:42:14.206  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 14:42:14.206  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:42:14.207  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:42:14.207  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 14:42:14.207  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:42:14.207  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:14.210  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:42:14.211  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:42:14.211  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 14:42:14.211  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:42:14.212  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:42:14.212  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 14:42:14.212  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:42:14.212  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:14.212  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:42:14.214  4005  4470 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:42:14.218  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:42:14.219  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:42:14.219  4005  4470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:42:14.228  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:42:14.229  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:42:14.229  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:42:14.231  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:42:14.231  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:42:14.232  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 14:42:14.233  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:42:14.233  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 14:42:14.233  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 14:42:14.234  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:42:14.238  4374  4385 D BtGatt.GattService: registerClient() - UUID=fc36c186-0d90-4564-9867-eaa695ce763e
,09-08 14:42:14.238  4374  4390 D BtGatt.GattService: onClientRegistered() - UUID=fc36c186-0d90-4564-9867-eaa695ce763e, clientIf=5
09-08 14:42:14.238  4005  4015 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 14:42:14.240  4374  4392 D BtGatt.AdvertiseManager: message : 0
,09-08 14:42:14.243  4374  4392 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:42:14.263  4374  4390 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 14:42:14.276  4374  4390 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 14:42:14.277  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:42:14.278  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:42:14.284  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:42:14.286  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:42:14.287  4005  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:42:14.287  4005  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 14:42:14.287  4005  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 14:42:14.287  4005  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 14:42:14.287  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:42:14.292  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 14:42:14.292  4005  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 14:42:14.293  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:42:14.794  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 14:42:14.794  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:42:14.795  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:42:17.294  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:42:17.294  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 14:42:17.295  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:42:17.295  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 14:42:17.295  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:42:17.296  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 14:42:17.300  4005  4470 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-08 14:42:17.301  4005  4470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:42:17.301  4005  4470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:42:17.302  4005  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 14:42:17.302  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:42:17.303  4005  4051 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:42:17.304  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:42:17.304  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:42:17.305  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 14:42:17.305  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:42:17.305  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:42:17.306  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:42:17.308  4005  4051 D BluetoothAdapter: STATE_ON
09-08 14:42:17.309  4005  4051 D BluetoothLeScanner: could not find callback wrapper
,09-08 14:42:17.309  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:42:17.309  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 14:42:17.311  4374  4392 D BtGatt.AdvertiseManager: message : 1
09-08 14:42:17.313  4374  4392 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 14:42:17.321  4374  4390 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 14:42:17.322  4374  4390 D BtGatt.GattService: Client app is not null!
,09-08 14:42:17.324  4374  4385 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:42:17.325  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:42:17.325  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 14:42:17.325  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 14:42:17.325  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 14:42:17.326  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:42:17.328  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:42:17.328  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:42:17.328  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:42:17.329  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:42:17.331  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:42:17.331  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:17.331  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:17.331  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:42:17.331  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:42:17.332  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f81fd removed from the list
09-08 14:42:17.332  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-08 14:42:17.332  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:17.332  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@939ef2 removed from the list
09-08 14:42:17.332  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:42:17.334  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:17.332  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:42:17.335  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:17.336  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:17.338  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:42:17.338  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:17.338  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:42:17.338  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@939ef2 not in the list
09-08 14:42:17.339  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:17.339  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:17.341  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:42:17.341  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:42:17.341  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:17.341  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@939ef2 not in the list
09-08 14:42:17.341  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:17.341  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:17.341  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:17.342  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f81fd not in the list
09-08 14:42:17.342  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:42:17.342  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd869f added. We now have 3 listener(s)
09-08 14:42:17.345  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 14:42:17.345  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:42:17.345  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:42:17.345  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:42:17.345  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab0f3ec added. We now have 4 listener(s)
09-08 14:42:17.345  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:42:17.346  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:42:17.348  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:42:17.353  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:42:17.354  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:42:17.355  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:42:17.355  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:42:17.355  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:42:17.355  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:42:17.355  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:42:17.355  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:42:17.357  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-08 14:42:17.358  4005  4051 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:42:17.359  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:42:17.359  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:42:17.362  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:42:17.363  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:42:17.363  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:42:17.366  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:42:17.366  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:42:17.366  4005  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:42:17.367  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:42:17.369  4374  4384 D BtGatt.GattService: registerClient() - UUID=3054a29e-c02c-402a-af1a-53df79e34412
,09-08 14:42:17.369  4374  4390 D BtGatt.GattService: onClientRegistered() - UUID=3054a29e-c02c-402a-af1a-53df79e34412, clientIf=5
09-08 14:42:17.369  4005  4015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 14:42:17.370  4374  4385 D BtGatt.GattService: start scan with filters
,09-08 14:42:17.372  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:42:17.372  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:42:17.372  4374  4393 D BtGatt.ScanManager: handling starting scan
09-08 14:42:17.372  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:42:17.372  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-08 14:42:17.377  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:42:17.378  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:42:17.378  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:42:17.380  4374  4390 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 14:42:17.380  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 14:42:17.380  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:17.380  4374  4393 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:42:17.386  4374  4390 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 14:42:17.386  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:17.386  4374  4393 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:42:17.386  4374  4393 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:42:17.397  4374  4390 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 14:42:17.397  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:17.403  4374  4390 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:42:17.403  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:17.836  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:42:17.878  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:42:17.878  4005  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
09-08 14:42:17.879  4005  4005 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:42:18.912  4374  4374 D BtGatt.ScanManager: awakened up at time 414964
,09-08 14:42:18.915  4374  4393 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:42:18.998  4374  4390 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-08 14:42:18.998  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:18.999  4374  4390 D BtGatt.GattService: current time is 415051420218
09-08 14:42:19.000  4374  4390 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -90, 4, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -97, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:42:19.004  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:42:19.006  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 14:42:19.007  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 14:42:19.007  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 14:42:19.008  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:42:19.009  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:42:19.010  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 14:42:19.010  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:42:20.390  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:42:20.390  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:42:20.391  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:42:20.391  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.391  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:42:20.392  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:42:20.392  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:42:20.392  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:42:20.392  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:42:20.393  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:42:20.394  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:42:20.396  4005  4051 D BluetoothAdapter: STATE_ON
,09-08 14:42:20.398  4374  4384 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:42:20.401  4374  4385 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:42:20.402  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:42:20.402  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:42:20.402  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 14:42:20.403  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:42:20.403  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 14:42:20.411  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:42:20.411  4374  4374 D BtGatt.ScanManager: awakened up at time 416463
09-08 14:42:20.411  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:42:20.413  4005  4051 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:42:20.413  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:42:20.415  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:42:20.417  4374  4390 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:42:20.418  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:42:20.418  4374  4393 D BtGatt.ScanManager: stopping BLe Batch
09-08 14:42:20.419  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:42:20.419  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:42:20.419  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:42:20.420  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:20.420  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:42:20.420  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:20.420  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:42:20.421  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd869f removed from the list
09-08 14:42:20.421  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:20.421  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab0f3ec removed from the list
,09-08 14:42:20.421  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:42:20.421  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:20.422  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.422  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:20.424  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:42:20.424  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:20.425  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:20.425  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab0f3ec not in the list
09-08 14:42:20.425  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.425  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:20.427  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:42:20.427  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:42:20.427  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:42:20.427  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab0f3ec not in the list
09-08 14:42:20.428  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:20.428  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.428  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:20.428  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd869f not in the list
09-08 14:42:20.430  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:42:20.430  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9db1631 added. We now have 3 listener(s)
09-08 14:42:20.430  4374  4390 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 14:42:20.430  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:20.431  4374  4393 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 14:42:20.432  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:42:20.432  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:42:20.432  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:42:20.432  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:42:20.432  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df19116 added. We now have 4 listener(s)
09-08 14:42:20.432  4005  4051 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:42:20.434  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:42:20.438  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:42:20.449  4005  4051 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:42:20.451  4374  4390 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 14:42:20.451  4374  4390 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:42:20.452  4005  4051 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:42:20.452  4005  4051 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:42:20.452  4374  4390 D BtGatt.GattService: current time is 416505287594
09-08 14:42:20.453  4374  4390 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -91, 1, 0, 21, 2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25, 0]
09-08 14:42:20.453  4005  4051 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:42:20.454  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:42:20.454  4005  4051 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:42:20.454  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:20.454  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.454  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:42:20.454  4005  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 14:42:20.454  4005  4051 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9db1631 removed from the list
09-08 14:42:20.454  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:20.454  4005  4051 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df19116 removed from the list
09-08 14:42:20.455  4374  4390 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 13, -1, 16, 1, 64, 12, 2, 65, 48, 117, 18, -41, 74, -25]
,09-08 14:42:20.457  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:42:20.457  4005  4051 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:42:20.457  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:42:20.458  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.459  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:20.461  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:42:20.462  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:20.462  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:20.462  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df19116 not in the list
09-08 14:42:20.462  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.462  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:42:20.462  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:20.465  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:42:20.465  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:42:20.465  4005  4051 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:42:20.465  4005  4051 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df19116 not in the list
09-08 14:42:20.466  4005  4051 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:42:20.466  4005  4051 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:42:20.466  4005  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:42:20.466  4005  4051 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9db1631 not in the list
,09-08 14:42:20.469  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-08 14:42:20.469  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:42:20.470  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 14:42:20.470  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:42:20.471  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:42:20.471  4005  4051 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:42:20.921  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:42:22.493  4005  4471 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 490, name: My test thread name)
,09-08 14:42:24.491  4005  4051 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 490
,09-08 14:42:24.491  4005  4051 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 490, name: My test thread name)
,09-08 14:42:24.497  4005  4472 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: My test thread name)
,09-08 14:42:24.498  4005  4472 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 491, thread name: My test thread name)
09-08 14:42:24.498  4005  4472 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 491, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 14:42:24.504  4005  4051 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:42:24.513  4005  4473 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: My test thread name)
,09-08 14:42:24.514  4005  4473 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 495, thread name: My test thread name): Test exception.
09-08 14:42:24.514  4005  4473 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 495, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 14:42:24.523  4005  4051 I jxcore-log: Total number of executed tests:  82
09-08 14:42:24.523  4005  4051 I jxcore-log: 
,09-08 14:42:24.524  4005  4051 I jxcore-log: Number of passed tests:  82
09-08 14:42:24.524  4005  4051 I jxcore-log: 
,09-08 14:42:24.525  4005  4051 I jxcore-log: Number of failed tests:  0
09-08 14:42:24.525  4005  4051 I jxcore-log: 
09-08 14:42:24.526  4005  4051 I jxcore-log: Number of ignored tests:  0
09-08 14:42:24.526  4005  4051 I jxcore-log: 
,09-08 14:42:24.526  4005  4051 I jxcore-log: Total duration:  101399
09-08 14:42:24.526  4005  4051 I jxcore-log: 
,09-08 14:42:24.536  4005  4051 I jxcore-log: Unit Test app is loaded
09-08 14:42:24.536  4005  4051 I jxcore-log: 
,09-08 14:42:24.558  4005  4005 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 14:42:24.560  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.560  4005  4051 I jxcore-log: 
,09-08 14:42:24.573  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.573  4005  4051 I jxcore-log: 
,09-08 14:42:24.574  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.574  4005  4051 I jxcore-log: 
,09-08 14:42:24.575  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.575  4005  4051 I jxcore-log: 
,09-08 14:42:24.577  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:42:24.577  4005  4051 I jxcore-log: 
,09-08 14:42:24.579  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.579  4005  4051 I jxcore-log: 
,09-08 14:42:24.582  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.582  4005  4051 I jxcore-log: 
,09-08 14:42:24.585  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.585  4005  4051 I jxcore-log: 
,09-08 14:42:24.586  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:42:24.586  4005  4051 I jxcore-log: 
,09-08 14:42:24.587  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.587  4005  4051 I jxcore-log: 
,09-08 14:42:24.588  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.588  4005  4051 I jxcore-log: 
,09-08 14:42:24.590  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.590  4005  4051 I jxcore-log: 
09-08 14:42:24.591  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.591  4005  4051 I jxcore-log: 
,09-08 14:42:24.594  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.594  4005  4051 I jxcore-log: 
,09-08 14:42:24.596  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.596  4005  4051 I jxcore-log: 
,09-08 14:42:24.599  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.599  4005  4051 I jxcore-log: 
,09-08 14:42:24.602  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.602  4005  4051 I jxcore-log: 
,09-08 14:42:24.604  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.604  4005  4051 I jxcore-log: 
,09-08 14:42:24.606  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.606  4005  4051 I jxcore-log: 
,09-08 14:42:24.609  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.609  4005  4051 I jxcore-log: 
,09-08 14:42:24.611  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.611  4005  4051 I jxcore-log: 
,09-08 14:42:24.612  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.612  4005  4051 I jxcore-log: 
09-08 14:42:24.613  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.613  4005  4051 I jxcore-log: 
,09-08 14:42:24.614  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.614  4005  4051 I jxcore-log: 
09-08 14:42:24.614  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.614  4005  4051 I jxcore-log: 
,09-08 14:42:24.615  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.615  4005  4051 I jxcore-log: 
09-08 14:42:24.616  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.616  4005  4051 I jxcore-log: 
,09-08 14:42:24.617  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.617  4005  4051 I jxcore-log: 
09-08 14:42:24.618  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.618  4005  4051 I jxcore-log: 
,09-08 14:42:24.619  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.619  4005  4051 I jxcore-log: 
09-08 14:42:24.619  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.619  4005  4051 I jxcore-log: 
,09-08 14:42:24.620  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.620  4005  4051 I jxcore-log: 
09-08 14:42:24.621  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.621  4005  4051 I jxcore-log: 
,09-08 14:42:24.622  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.622  4005  4051 I jxcore-log: 
09-08 14:42:24.622  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.622  4005  4051 I jxcore-log: 
,09-08 14:42:24.623  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.623  4005  4051 I jxcore-log: 
09-08 14:42:24.624  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.624  4005  4051 I jxcore-log: 
,09-08 14:42:24.625  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.625  4005  4051 I jxcore-log: 
09-08 14:42:24.625  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.625  4005  4051 I jxcore-log: 
,09-08 14:42:24.626  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.626  4005  4051 I jxcore-log: 
09-08 14:42:24.627  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:42:24.627  4005  4051 I jxcore-log: 
,09-08 14:42:24.628  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.628  4005  4051 I jxcore-log: 
09-08 14:42:24.628  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:42:24.628  4005  4051 I jxcore-log: 
09-08 14:42:24.629  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.629  4005  4051 I jxcore-log: 
,09-08 14:42:24.630  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.630  4005  4051 I jxcore-log: 
09-08 14:42:24.631  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.631  4005  4051 I jxcore-log: 
,09-08 14:42:24.632  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.632  4005  4051 I jxcore-log: 
09-08 14:42:24.632  4005  4471 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 490, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-08 14:42:24.633  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.633  4005  4051 I jxcore-log: 
09-08 14:42:24.634  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.634  4005  4051 I jxcore-log: 
,09-08 14:42:24.635  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.635  4005  4051 I jxcore-log: 
09-08 14:42:24.636  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:42:24.636  4005  4051 I jxcore-log: 
,09-08 14:42:24.637  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.637  4005  4051 I jxcore-log: 
09-08 14:42:24.638  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.638  4005  4051 I jxcore-log: 
,09-08 14:42:24.638  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:42:24.638  4005  4051 I jxcore-log: 
09-08 14:42:24.639  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:42:24.639  4005  4051 I jxcore-log: 
09-08 14:42:24.640  4005  4051 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:42:24.640  4005  4051 I jxcore-log: 
,09-08 14:42:24.644  4005  4051 I jxcore-log: My device name is: motorola-Nexus 6
09-08 14:42:24.644  4005  4051 I jxcore-log: 
,09-08 14:42:24.646  4005  4051 I jxcore-log: Running for WIFI network type
09-08 14:42:24.646  4005  4051 I jxcore-log: ,
,09-08 14:42:27.154  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 14:42:27.154  4005  4051 I jxcore-log: 
,09-08 14:42:27.611  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 14:42:27.611  4005  4051 I jxcore-log: 
,09-08 14:42:27.644  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 14:42:27.644  4005  4051 I jxcore-log: 
,09-08 14:42:29.031  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 14:42:29.031  4005  4051 I jxcore-log: 
,09-08 14:42:29.315  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 14:42:29.315  4005  4051 I jxcore-log: 
,09-08 14:42:29.321  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 14:42:29.321  4005  4051 I jxcore-log: 
,09-08 14:42:29.328  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 14:42:29.328  4005  4051 I jxcore-log: 
,09-08 14:42:29.599  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 14:42:29.599  4005  4051 I jxcore-log: 
,09-08 14:42:29.616  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 14:42:29.616  4005  4051 I jxcore-log: 
,09-08 14:42:29.620  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 14:42:29.620  4005  4051 I jxcore-log: 
,09-08 14:42:30.373  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 14:42:30.373  4005  4051 I jxcore-log: 
,09-08 14:42:30.542  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 14:42:30.542  4005  4051 I jxcore-log: 
,09-08 14:42:30.738   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=426790, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:42:30.877  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 14:42:30.877  4005  4051 I jxcore-log: 
,09-08 14:42:30.887  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 14:42:30.887  4005  4051 I jxcore-log: 
,09-08 14:42:30.895  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 14:42:30.895  4005  4051 I jxcore-log: 
,09-08 14:42:30.902  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 14:42:30.902  4005  4051 I jxcore-log: 
,09-08 14:42:30.943  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 14:42:30.943  4005  4051 I jxcore-log: 
,09-08 14:42:30.990  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 14:42:30.990  4005  4051 I jxcore-log: 
,09-08 14:42:30.998  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 14:42:30.998  4005  4051 I jxcore-log: 
,09-08 14:42:31.006  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 14:42:31.006  4005  4051 I jxcore-log: 
,09-08 14:42:31.026  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 14:42:31.026  4005  4051 I jxcore-log: 
,09-08 14:42:31.032  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 14:42:31.032  4005  4051 I jxcore-log: 
,09-08 14:42:31.038  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 14:42:31.038  4005  4051 I jxcore-log: 
,09-08 14:42:31.054  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 14:42:31.054  4005  4051 I jxcore-log: 
,09-08 14:42:31.081  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 14:42:31.081  4005  4051 I jxcore-log: 
,09-08 14:42:31.092  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 14:42:31.092  4005  4051 I jxcore-log: 
,09-08 14:42:31.106  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 14:42:31.106  4005  4051 I jxcore-log: 
,09-08 14:42:31.118  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 14:42:31.118  4005  4051 I jxcore-log: 
,09-08 14:42:31.133  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 14:42:31.133  4005  4051 I jxcore-log: 
,09-08 14:42:31.144  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 14:42:31.144  4005  4051 I jxcore-log: 
,09-08 14:42:31.150  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 14:42:31.150  4005  4051 I jxcore-log: 
,09-08 14:42:31.180  4005  4051 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 14:42:31.180  4005  4051 I jxcore-log: 
,09-08 14:42:31.192  4005  4051 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 14:42:31.194  4005  4051 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 14:42:31.194  4005  4051 I jxcore-log: 
,09-08 14:42:36.251   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=432303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:43:21.573  1510  2136 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 14:43:36.481  3333  4485 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:43:36.521  3333  4486 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:43:36.554  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:43:36.558  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:43:36.608  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:43:36.608  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:43:36.608  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:43:36.608  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:43:36.640  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:43:36.643  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:43:36.678  1510  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 14:43:36.678  1510  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:43:36.678  1510  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:43:36.678  1510  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:43:36.701  3333  4486 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:43:36.703  3333  4485 E BooksSync: Soft error
09-08 14:43:36.703  3333  4485 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:43:36.703  3333  4485 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:43:36.703  3333  4485 E BooksSync: Sync error
09-08 14:43:36.703  3333  4485 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:43:36.703  3333  4485 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:43:36.703  3333  4485 I BooksSync: Finished books sync
,09-08 14:43:36.716   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 492331, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:44:07.252  3333  4488 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:44:07.297  3333  4489 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:44:07.318  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:07.325  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:07.389  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:44:07.389  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 14:44:07.390  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:44:07.390  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:44:07.450  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:07.457  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:07.514  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:44:07.514  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:44:07.514  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:44:07.515  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:44:07.547  3333  4489 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:44:07.549  3333  4488 E BooksSync: Soft error
09-08 14:44:07.549  3333  4488 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:44:07.549  3333  4488 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:44:07.550  3333  4488 E BooksSync: Sync error
09-08 14:44:07.550  3333  4488 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:44:07.550  3333  4488 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:44:07.550  3333  4488 I BooksSync: Finished books sync
,09-08 14:44:07.563   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 523194, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:44:38.052  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:38.057  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:44:38.104  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:44:38.104  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:44:38.104  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:44:38.104  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:44:38.125  3737  4492 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:44:38.125  3737  4492 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:44:38.125  3737  4492 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	... 12 more
09-08 14:44:38.125  3737  4492 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at fal.a(PG:38)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:44:38.125  3737  4492 E HttpOperation: 	... 14 more
,09-08 14:44:38.210  1510  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:44:38.211  1510  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:44:38.211  1510  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:44:38.211  1510  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:44:38.245  3737  4492 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:44:38.245  3737  4492 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at hec.a(PG:42)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at hee.a(PG:102)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at czr.a(PG:65)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at kka.a(PG:108)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:44:38.245  3737  4492 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	... 15 more
09-08 14:44:38.245  3737  4492 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at fal.a(PG:38)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:44:38.245  3737  4492 E HttpOperation: 	... 17 more
,09-08 14:44:38.245  3737  4492 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:44:38.245  3737  4492 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	... 15 more
09-08 14:44:38.245  3737  4492 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:44:38.245  3737  4492 E ExperimentLoader: 	... 17 more
,09-08 14:44:38.364   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 532925, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:45:08.424   874   874 I ActivityManager: Start proc 4499:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-08 14:45:08.501  3333  4512 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:45:08.510  4499  4499 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-08 14:45:08.532  4499  4499 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-08 14:45:08.532  4499  4499 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:45:08.532  4499  4499 I GAv4    :   adb logcat -s GAv4
,09-08 14:45:08.545  4499  4499 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:45:08.551  4499  4499 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:45:08.566  3333  4517 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:45:08.573  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.575  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.575  4499  4516 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:45:08.618  1510  3170 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:45:08.618  1510  3170 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:45:08.618  1510  3170 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:45:08.618  1510  3170 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:08.644  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.647  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.653  3252  4511 V KeepSync: Connecting to GoogleApiClient
09-08 14:45:08.654   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:45:08.695  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 14:45:08.695  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 14:45:08.695  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:45:08.695  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:08.748  3333  4517 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:45:08.749  3333  4512 E BooksSync: Soft error
09-08 14:45:08.749  3333  4512 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:45:08.749  3333  4512 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:45:08.749  3333  4512 E BooksSync: Sync error
09-08 14:45:08.749  3333  4512 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:45:08.749  3333  4512 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:45:08.749  3333  4512 I BooksSync: Finished books sync
,09-08 14:45:08.769  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.771   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 584466, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:45:08.777  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:08.815  1510  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:45:08.815  1510  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 14:45:08.816  1510  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:45:08.816  1510  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:08.829  1717  4518 V BaseAuthAsyncOperation: access token request failed
,09-08 14:45:08.830  3252  4511 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:45:08.876  1510  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:45:08.876  1510  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 14:45:08.877  1510  2059 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-08 14:45:08.877  1510  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:08.891  3252  4511 E KeepSync: IOException
09-08 14:45:08.891  3252  4511 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:45:08.891  3252  4511 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:45:08.891  3252  4511 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:45:08.891  3252  4511 E KeepSync: 	... 10 more
09-08 14:45:08.891  3252  4511 W KeepSync: Sync result 2
,09-08 14:45:08.898   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 568994, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:45:39.360  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:39.365  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:45:39.408  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:45:39.409  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:45:39.409  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:45:39.409  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:39.438  3737  4521 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:45:39.438  3737  4521 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:45:39.438  3737  4521 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	... 12 more
09-08 14:45:39.438  3737  4521 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at fal.a(PG:38)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:45:39.438  3737  4521 E HttpOperation: 	... 14 more
,09-08 14:45:39.521  1510  3170 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:45:39.521  1510  3170 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:45:39.521  1510  3170 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:45:39.521  1510  3170 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:39.542  3737  4521 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:45:39.542  3737  4521 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at hec.a(PG:42)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at hee.a(PG:102)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at czr.a(PG:65)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at kka.a(PG:108)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:45:39.542  3737  4521 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	... 15 more
09-08 14:45:39.542  3737  4521 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at fal.a(PG:38)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:45:39.542  3737  4521 E HttpOperation: 	... 17 more
,09-08 14:45:39.543  3737  4521 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:45:39.543  3737  4521 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	,at czp.a(PG:9081)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	... 15 more
09-08 14:45:39.543  3737  4521 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:45:39.543  3737  4521 E ExperimentLoader: 	... 17 more
,09-08 14:45:39.665   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 585110, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:45:39.719  3252  4523 V KeepSync: Connecting to GoogleApiClient
,09-08 14:45:39.719   874  2176 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:45:39.794  1510  4495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:45:39.794  1510  4495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 14:45:39.794  1510  4495 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:45:39.794  1510  4495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:39.810  1717  4524 V BaseAuthAsyncOperation: access token request failed
,09-08 14:45:39.811  3252  4523 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:45:39.858  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:45:39.858  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 14:45:39.858  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:45:39.858  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:45:39.876  3252  4523 E KeepSync: IOException
09-08 14:45:39.876  3252  4523 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:45:39.876  3252  4523 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:45:39.876  3252  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:45:39.876  3252  4523 E KeepSync: 	... 10 more
09-08 14:45:39.876  3252  4523 W KeepSync: Sync result 2
,09-08 14:45:39.890   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 615162, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,09-08 14:46:38.124  1510  2136 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 14:47:00.509  3697  3697 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-08 14:47:00.539  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:00.550  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:00.554  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:00.619  1510  3170 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 14:47:00.620  1510  3170 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 14:47:00.620  1510  3170 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:47:00.621  1510  3170 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:00.673  3697  3697 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-08 14:47:00.692  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:00.774  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 14:47:00.774  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-08 14:47:00.775  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:47:00.775  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:00.820  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:00.906  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 14:47:00.907  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 14:47:00.907  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-08 14:47:00.907  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:00.960  3697  3697 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-08 14:47:01.132  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:01.158  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-08 14:47:01.158  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 14:47:01.158  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:47:01.158  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:01.193  3697  3697 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
09-08 14:47:01.193  3697  3697 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-08 14:47:01.195  3697  3697 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-08 14:47:01.200  3697  3697 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,09-08 14:47:01.203  3697  3769 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-08 14:47:16.191  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:16.200  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:16.205  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:16.245  1510  4495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 14:47:16.246  1510  4495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 14:47:16.246  1510  4495 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:47:16.246  1510  4495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:16.289  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:47:16.290  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:47:16.290  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-08 14:47:36.687  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:36.697  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:36.699  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:36.751  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 14:47:36.751  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 14:47:36.751  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:47:36.751  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:36.795  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:47:36.796  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:47:36.796  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-08 14:47:57.053  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:57.064  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:57.068  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:47:57.124  1510  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:47:57.125  1510  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 14:47:57.125  1510  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:47:57.126  1510  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:47:57.179  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:47:57.180  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 14:47:57.183  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-08 14:48:17.481  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:17.492  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:17.494  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:17.555  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:48:17.556  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 14:48:17.556  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:48:17.556  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:48:17.606  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:48:17.607  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:48:17.607  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 14:48:37.968  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:37.987  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:37.992  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:38.058  1510  4495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:48:38.058  1510  4495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 14:48:38.058  1510  4495 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:48:38.059  1510  4495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:48:38.111  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:48:38.113  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:48:38.115  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 14:48:58.533  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:58.546  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:58.550  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:48:58.593  1510  4495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 14:48:58.593  1510  4495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 14:48:58.594  1510  4495 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:48:58.594  1510  4495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:48:58.629  3697  3697 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:48:58.630  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:48:58.632  3697  3697 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 14:50:20.692   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=896744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:50:33.052   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:50:45.758   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=921810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:50:58.105   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=934157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:51:10.825   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:51:23.172   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:51:35.891   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:51:48.239   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=984291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:52:01.599   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:52:13.945   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:52:26.745   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:52:39.092   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1035143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:52:51.812   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1047864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:53:04.145   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1060197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:53:16.905   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:53:29.225   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:53:41.945   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:53:54.291   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:54:07.038   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1123090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:54:19.359   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:54:32.159   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1148211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:54:44.505   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:54:57.225   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1173277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:55:09.572   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:55:26.132   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1202184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:55:34.638   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:55:42.786   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 14:55:51.198   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1227250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:55:59.692   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:56:16.265   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:56:24.745   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:56:41.438   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1277490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:56:49.918   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:57:06.505   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1302557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:57:14.998   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1311050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:57:31.572   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1327624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:57:40.065   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1336117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:57:56.638   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1352690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:58:05.131   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1361183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:58:21.705   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1377756, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:58:30.185   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1386237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:58:46.771   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1402823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:58:55.238   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1411290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:59:11.892   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1427944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:59:20.345   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1436397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:59:36.958   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1453010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:59:45.438   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1461490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:00:02.025   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1478077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:00:10.505   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:00:15.932   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1491984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:00:35.919   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:00:40.985   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:01:00.985   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1537037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:01:06.065   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1542117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:01:26.065   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1562117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:01:31.145   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1567197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:01:51.132   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1587184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:01:56.211   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1592263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:02:16.212   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1612264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:02:21.291   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1617343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:02:41.278   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1637330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:02:46.371   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1642423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:03:06.358   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1662410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:03:11.545   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1667597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:03:31.518   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1687570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 15:03:36.598   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1692650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 15:03:56.585   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1712636, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
