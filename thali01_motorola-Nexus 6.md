#### Test 8506767965eb647_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 19:43:14.115  3010  3789 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
09-13 19:43:14.115   873  2274 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 19:43:14.151  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 19:43:14.153  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 19:43:14.175  1491  1502 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-13 19:43:14.176  1491  1502 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 19:43:14.176  1491  1502 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:43:14.176  1491  1502 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 19:43:14.190  1709  3790 V BaseAuthAsyncOperation: access token request failed
09-13 19:43:14.190  3010  3789 V KeepSync: GoogleApiClient failed to connect with error code: 4
09-13 19:43:14.231  1491  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 19:43:14.232  1491  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 19:43:14.232  1491  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:43:14.232  1491  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 19:43:14.246  3010  3789 E KeepSync: IOException
09-13 19:43:14.246  3010  3789 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 19:43:14.246  3010  3789 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:43:14.246  3010  3789 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 19:43:14.246  3010  3789 E KeepSync: 	... 10 more
09-13 19:43:14.246  3010  3789 W KeepSync: Sync result 2
09-13 19:43:14.256   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 254579, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
09-13 19:43:14.811  3791  3791 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 19:43:14.816  3791  3791 D AndroidRuntime: CheckJNI is OFF
09-13 19:43:14.851  3791  3791 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 19:43:14.894  3791  3791 I Radio-JNI: register_android_hardware_Radio DONE
09-13 19:43:14.914  3791  3791 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 19:43:14.919   873  1708 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 19:43:14.974   873  1708 I ActivityManager: Start proc 3800:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 19:43:14.982  3791  3791 D AndroidRuntime: Shutting down VM
09-13 19:43:15.106  3800  3800 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 19:43:15.130  3800  3800 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 19:43:15.136  3800  3800 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5835-5838)
09-13 19:43:15.137  3800  3800 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 19:43:15.153  3800  3800 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7b3611e}
09-13 19:43:15.153  3800  3800 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 19:43:15.153  3800  3800 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 19:43:15.159  3800  3800 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 19:43:15.160  3800  3800 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 19:43:15.180  3800  3800 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 19:43:15.190  3800  3800 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 19:43:15.190  3800  3800 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 19:43:15.190  3800  3800 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 19:43:15.190  3800  3800 I Adreno  : Build Date                       : 10/20/15
09-13 19:43:15.190  3800  3800 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 19:43:15.190  3800  3800 I Adreno  : Local Branch                     : M14
09-13 19:43:15.190  3800  3800 I Adreno  : Remote Branch                    : 
09-13 19:43:15.190  3800  3800 I Adreno  : Remote Branch                    : 
09-13 19:43:15.190  3800  3800 I Adreno  : Reconstruct Branch               : 
,09-13 19:43:15.249   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cd6744:true
,09-13 19:43:15.298  3800  3800 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 19:43:15.312  3800  3800 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 19:43:15.369  3800  3838 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 19:43:15.387  3800  3825 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 19:43:15.417  3800  3838 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 19:43:15.433  1893  1893 I Keyboard.Facilitator: onFinishInput()
,09-13 19:43:15.501   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +449ms (total +542ms)
,09-13 19:43:15.569  3800  3800 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3800
,09-13 19:43:15.766  3800  3800 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 19:43:15.951  3800  3840 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699022544
,09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 19:43:15.961  3800  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b1f88d added. We now have 1 listener(s)
,09-13 19:43:15.966  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 19:43:15.967  3800  3840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 19:43:15.967  3800  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 19:43:15.968  3800  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 19:43:15.972  3800  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8396f90 added. We now have 1 listener(s)
09-13 19:43:15.972  3800  3840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:15.979   873  1307 D WifiService: New client listening to asynchronous messages
,09-13 19:43:15.981  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 19:43:15.981  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 19:43:15.981  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 19:43:15.981  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-13 19:43:15.981  3800  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 19:43:15.985  3800  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:15.985  3800  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 19:43:15.994  3800  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:15.994  3800  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:15.994  3800  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 19:43:15.994  3800  3840 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 19:43:15.995  3800  3840 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 19:43:16.000  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:16.011  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:16.026  3800  3800 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 19:43:17.867  3800  3847 W jxcore-log: Initializing JXcore engine
,09-13 19:43:17.867  3800  3847 W jxcore-log: JXcore engine is ready
,09-13 19:43:17.908  3847  3847 W Thread-318: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8866 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 19:43:17.908  3847  3847 W Thread-318: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13221]" dev="sockfs" ino=13221 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 19:43:17.908  3847  3847 W Thread-318: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 19:43:17.908  3847  3847 W Thread-318: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[30167]" dev="sockfs" ino=30167 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 19:43:17.923  3800  3847 W jxcore-log: Starting JXcore engine
,09-13 19:43:18.014  3800  3847 W jxcore-log: Platform android
09-13 19:43:18.014  3800  3847 W jxcore-log: 
,09-13 19:43:18.014  3800  3847 W jxcore-log: Process ARCH arm
09-13 19:43:18.014  3800  3847 W jxcore-log: 
,09-13 19:43:18.274  3800  3847 I jxcore-log: JXcore Cordova bridge is ready!
09-13 19:43:18.274  3800  3847 I jxcore-log: 
,09-13 19:43:18.274  3800  3847 W jxcore-log: JXcore engine is started
,09-13 19:43:18.283  3800  3840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 19:43:18.288  3800  3800 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 19:43:27.989   873  2064 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 19:43:31.931  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 19:43:31.931  3800  3847 I jxcore-log: 
,09-13 19:43:31.934  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 19:43:31.934  3800  3847 I jxcore-log: 
,09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:31.945  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:31.950  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:31.952  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 19:43:31.952  3800  3847 I jxcore-log: 
,09-13 19:43:31.954  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 19:43:31.954  3800  3847 I jxcore-log: 
,09-13 19:43:32.305  3800  3847 D ExecuteNativeTests: Running unit tests
,09-13 19:43:32.386  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 19:43:32.386  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 added. We now have 2 listener(s)
,09-13 19:43:32.387  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 19:43:32.387  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:32.387  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:32.387  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 19:43:32.387  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 added. We now have 2 listener(s)
09-13 19:43:32.388  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:32.388  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 19:43:32.391  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.396  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:43:32.398  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.398  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 19:43:32.400  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 19:43:32.400  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 19:43:32.400  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 19:43:32.401  3800  3847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,09-13 19:43:32.401  3800  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 19:43:32.401  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 19:43:32.402  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 19:43:32.402  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 19:43:32.402  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:32.402  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.402  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.402  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:32.402  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.402  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.402  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:32.403  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 removed from the list,
09-13 19:43:32.403  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.403  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 removed from the list
09-13 19:43:32.404  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 19:43:32.409  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.409  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.409  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.410  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.410  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.410  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.410  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.410  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.410  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.411  3800  3847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 19:43:32.412  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.412  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.412  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.412  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.412  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.412  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.412  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.413  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.413  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.413  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 19:43:32.413  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.413  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.413  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.413  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.414  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.414  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.414  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.414  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.418  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 19:43:32.418  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 19:43:32.418  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 19:43:32.418  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 19:43:32.419  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnect,ions: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 19:43:32.420  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 19:43:32.420  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.420  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.420  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.420  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.421  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.421  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.421  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.421  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.421  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.421  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.421  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.421  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.421  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.421  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.422  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.422  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.422  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.422  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.423  3800  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 19:43:32.424  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.427  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:43:32.428  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.428  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:32.430  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.431  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.431  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:32.431  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:32.431  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 19:43:32.431  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.432  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.434  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.434  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:32.437  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:32.438  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:32.438  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:32.440  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 19:43:32.441  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 19:43:32.441  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 19:43:32.441  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 19:43:32.442  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 19:43:32.442  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.446  2671  2815 D BtGatt.GattService: registerClient() - UUID=3c321d94-63c1-4f5b-85ab-b3da533b7453
09-13 19:43:32.446  2671  2690 D BtGatt.GattService: onClientRegistered() - UUID=3c321d94-63c1-4f5b-85ab-b3da533b7453, clientIf=5
09-13 19:43:32.447  3800  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 19:43:32.447  2671  2683 D BtGatt.GattService: start scan with filters
09-13 19:43:32.450  2671  2696 D BtGatt.ScanManager: handling starting scan
09-13 19:43:32.451  2671  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:32.451  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 19:43:32.454  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 19:43:32.454  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 19:43:32.454  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 19:43:32.458  2671  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 19:43:32.458  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.459  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 19:43:32.462  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:32.464  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:32.465  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:32.465  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.465  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-13 19:43:32.465  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 19:43:32.467  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 19:43:32.468  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 19:43:32.471  3800  3847 I io.jxcore.node.ConnectionHelper: start: OK
09-13 19:43:32.473  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.473  3800  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 19:43:32.473  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.473  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 19:43:32.473  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.473  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 19:43:32.473  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 19:43:32.473  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 19:43:32.473  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 19:43:32.473  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 19:43:32.474  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 19:43:32.474  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 19:43:32.474  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.475  2671  2683 D BtGatt.GattService: stopScan() - queue size =1
09-13 19:43:32.479  2671  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 19:43:32.479  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.479  2671  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 19:43:32.479  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.479  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 19:43:32.479  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 19:43:32.479  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 19:43:32.479  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 19:43:32.480  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.480  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.480  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:32.480  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.481  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.481  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.481  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.482  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.482  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.482  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.482  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.482  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.482  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:32.482  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.482  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.483  3800  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 19:43:32.483  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 19:43:32.485  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.483  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.486  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.502  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.502  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.503  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:43:32.505  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.505  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 19:43:32.505  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.505  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:32.506  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:32.506  2671  2696 D BtGatt.ScanManager: stopping BLe Batch
09-13 19:43:32.506  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:32.512  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:32.512  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.512  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 19:43:32.513  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:32.513  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:32.513  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:32.513  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.514  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.517  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:32.517  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.517  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.517  2671  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 19:43:32.517  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.520  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.521  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.521  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.524  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.524  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 19:43:32.524  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.524  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.526  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.527  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.528  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.532  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 19:43:32.532  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 19:43:32.532  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 19:43:32.533  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:32.535  2671  2815 D BtGatt.GattService: registerClient() - UUID=4d3890cd-4d56-4d13-a04d-4f929d6df385
,09-13 19:43:32.535  2671  2690 D BtGatt.GattService: onClientRegistered() - UUID=4d3890cd-4d56-4d13-a04d-4f929d6df385, clientIf=5
,09-13 19:43:32.536  3800  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 19:43:32.536  2671  2807 D BtGatt.GattService: start scan with filters
,09-13 19:43:32.539  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 19:43:32.539  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 19:43:32.539  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 19:43:32.540  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 19:43:32.540  2671  2696 D BtGatt.ScanManager: handling starting scan
,09-13 19:43:32.541  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:32.542  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 19:43:32.542  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 19:43:32.543  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 19:43:32.544  3800  3847 I io.jxcore.node.ConnectionHelper: start: OK,
,09-13 19:43:32.546  2671  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 19:43:32.546  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.546  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-13 19:43:32.547  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 19:43:32.547  3800  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 19:43:32.547  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.547  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 19:43:32.547  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.547  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 19:43:32.548  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 19:43:32.548  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 19:43:32.548  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 19:43:32.548  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 19:43:32.548  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 19:43:32.548  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 19:43:32.548  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.549  2671  2815 D BtGatt.GattService: stopScan() - queue size =1
09-13 19:43:32.550  2671  2807 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 19:43:32.550  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.550  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 19:43:32.550  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 19:43:32.550  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 19:43:32.550  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 19:43:32.551  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.551  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 19:43:32.551  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:32.551  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.551  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:32.551  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.551  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 19:43:32.552  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 19:43:32.553  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:32.554  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 19:43:32.554  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.554  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.556  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:32.556  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:32.557  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:32.557  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.558  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:32.558  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 19:43:32.558  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.558  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.558  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.558  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.558  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.558  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:32.559  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:32.559  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.559  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.560  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:32.560  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.560  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:32.563  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.564  2671  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 19:43:32.564  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.564  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.564  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.567  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.567  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.567  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.568  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.568  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.568  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:32.568  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.569  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.569  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.569  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.569  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.569  3800  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 19:43:32.570  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.570  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 19:43:32.570  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.573  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:32.575  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:32.575  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 19:43:32.575  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 19:43:32.575  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:32.575  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 19:43:32.575  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.575  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:32.578  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 19:43:32.578  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-13 19:43:32.578  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.578  2671  2696 D BtGatt.ScanManager: stopping BLe Batch,
09-13 19:43:32.580  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:32.581  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.585  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:32.585  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.585  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 19:43:32.585  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 19:43:32.585  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 19:43:32.586  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 19:43:32.586  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:32.589  2671  2683 D BtGatt.GattService: registerClient() - UUID=b44b9e41-72c1-452f-bea4-d1d7ee6739df
09-13 19:43:32.589  2671  2690 D BtGatt.GattService: onClientRegistered() - UUID=b44b9e41-72c1-452f-bea4-d1d7ee6739df, clientIf=5
,09-13 19:43:32.590  2671  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 19:43:32.590  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.590  3800  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 19:43:32.591  2671  2815 D BtGatt.GattService: start scan with filters
,09-13 19:43:32.594  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 19:43:32.594  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 19:43:32.594  2671  2696 D BtGatt.ScanManager: handling starting scan
,09-13 19:43:32.594  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 19:43:32.594  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 19:43:32.597  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:32.597  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 19:43:32.597  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 19:43:32.599  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 19:43:32.602  2671  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 19:43:32.602  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.602  2671  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 19:43:32.602  3800  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 19:43:32.602  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:32.602  3800  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 19:43:32.602  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:32.602  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 19:43:32.602  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.603  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 19:43:32.603  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 19:43:32.603  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 19:43:32.603  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 19:43:32.603  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 19:43:32.603  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 19:43:32.603  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 19:43:32.604  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:32.604  2671  2683 D BtGatt.GattService: stopScan() - queue size =1
,09-13 19:43:32.605  2671  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 19:43:32.605  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.606  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 19:43:32.606  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 19:43:32.606  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 19:43:32.606  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 19:43:32.607  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.607  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.607  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-13 19:43:32.607  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 19:43:32.608  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:32.609  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:32.609  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:32.609  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.609  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.609  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.610  2671  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-13 19:43:32.610  2671  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
09-13 19:43:32.612  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:32.612  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 19:43:32.615  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.615  3800  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 19:43:32.615  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.615  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:32.615  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.615  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.615  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 19:43:32.616  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
,09-13 19:43:32.616  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.616  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.616  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.616  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:32.619  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:32.619  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 19:43:32.619  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:32.620  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 19:43:32.620  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.622  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 19:43:32.622  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:32.622  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.623  2671  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 19:43:32.623  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.624  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:32.624  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 19:43:32.624  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.626  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 19:43:32.627  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.627  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.628  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:32.628  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.629  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:32.629  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:32.629  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.629  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.629  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 19:43:32.629  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.629  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.629  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.630  3800  3847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 19:43:32.630  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.630  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:32.631  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.631  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:32.631  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.631  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.631  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
,09-13 19:43:32.631  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.631  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.631  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.631  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.631  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.631  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.631  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.632  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:32.632  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.632  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.633  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.633  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.633  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.633  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.633  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.634  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 19:43:32.634  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:32.634  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.634  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:32.634  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.634  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.635  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.635  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.635  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.635  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.635  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.635  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.635  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 19:43:32.635  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.635  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.636  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:32.636  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.636  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.636  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.637  3800  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 19:43:32.637  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.637  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.637  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.637  3800  3847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 19:43:32.637  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:32.638  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:32.638  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.638  2671  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 19:43:32.638  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.638  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:32.638  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.638  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.638  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.638  2671  2696 D BtGatt.ScanManager: stopping BLe Batch
,09-13 19:43:32.638  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.642  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.642  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 19:43:32.642  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.642  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.642  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.642  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.645  2671  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:32.645  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.645  2671  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 19:43:32.647  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.647  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.647  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:32.648  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.648  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.648  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.648  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.648  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.649  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.649  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 19:43:32.649  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.649  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.649  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:32.649  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.649  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 19:43:32.649  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.649  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.649  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.649  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 19:43:32.649  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.649  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.650  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.650  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.650  2671  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 19:43:32.650  2671  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:32.651  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.651  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.651  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.652  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:32.652  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.652  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.652  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.652  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.652  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 19:43:32.654  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 19:43:32.654  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-13 19:43:32.654  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 19:43:32.654  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 19:43:32.654  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 19:43:32.654  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.654  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:32.654  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:32.654  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.654  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.654  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.654  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
,09-13 19:43:32.654  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.654  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.654  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 19:43:32.654  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.654  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.654  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.655  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.655  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:32.655  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.655  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.656  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.656  3800  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 19:43:32.656  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.656  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.656  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.656  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 19:43:32.656  3800  3847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 19:43:32.657  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 19:43:32.659  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 19:43:32.659  3800  3847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 19:43:32.659  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 19:43:32.660  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 19:43:32.661  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 19:43:32.661  3800  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 19:43:32.661  3800  3847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 19:43:32.661  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 19:43:32.661  3800  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 19:43:32.661  3800  3847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 19:43:32.661  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 19:43:32.661  3800  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 19:43:32.661  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 19:43:32.663  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 19:43:32.664  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 19:43:32.664  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 19:43:32.664  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 19:43:32.664  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 19:43:32.664  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 19:43:32.665  3800  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 19:43:32.665  3800  3847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-13 19:43:32.665  3800  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
09-13 19:43:32.665  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.665  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.665  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.665  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.665  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.665  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.665  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 19:43:32.666  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.666  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.666  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.666  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.666  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.666  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.666  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.666  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.667  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.667  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.667  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:32.667  3800  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
09-13 19:43:32.667  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.667  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.667  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.668  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.668  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.668  3800  3847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 19:43:32.668  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.668  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.668  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:32.669  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.669  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.669  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.669  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.669  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.669  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.669  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.669  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.669  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.669  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.669  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.671  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:32.671  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.671  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.671  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.671  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.671  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.671  3800  3849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 19:43:32.671  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.671  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.672  3800  3847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 19:43:32.672  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.672  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.672  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.672  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.672  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.672  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.672  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.672  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.672  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.673  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.673  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.673  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.673  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.673  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.673  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.673  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.673  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:32.674  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.674  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.674  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.674  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.675  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 19:43:32.676  3800  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 19:43:32.676  3800  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 19:43:32.676  3800  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 19:43:32.676  3800  3847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 19:43:32.676  3800  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 19:43:32.676  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 19:43:32.676  3800  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 19:43:32.676  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.676  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.676  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.677  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.677  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.677  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.677  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.677  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.677  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.677  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.677  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.677  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.677  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.677  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.678  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.678  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.678  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.678  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.678  3800  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 19:43:32.678  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.678  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.678  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.679  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.679  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.679  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.679  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.679  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.679  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.679  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.679  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.679  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.679  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.679  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.679  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.679  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.679  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.679  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.680  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.680  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.680  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.680  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.680  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.680  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.680  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.680  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.680  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.680  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.680  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.680  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.680  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.680  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.681  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.681  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.681  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.681  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.681  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.681  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.681  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.681  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.682  3800  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 19:43:32.682  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.683  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 19:43:32.683  3800  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 19:43:32.683  3800  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 19:43:32.684  3800  3800 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 19:43:32.684  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 19:43:32.684  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.684  3800  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 19:43:32.684  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.684  3800  3800 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 19:43:32.684  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 19:43:32.684  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 19:43:32.684  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 19:43:32.685  3800  3851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 19:43:32.685  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.685  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.685  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.685  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.685  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:32.685  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.685  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.686  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.686  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.686  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 19:43:32.686  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.686  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.686  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.686  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.686  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.686  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:32.686  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.686  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.686  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.686  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.686  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
,09-13 19:43:32.686  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.687  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.687  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:32.688  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:32.688  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 19:43:32.689  3800  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 19:43:32.689  3800  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 19:43:32.689  3800  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 19:43:32.691  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:32.692  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:32.692  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:32.692  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.692  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.695  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.695  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.696  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.696  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.696  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.697  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.697  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.697  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.697  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.697  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.697  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:32.697  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.697  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:32.698  3800  3847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 19:43:32.698  3800  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 19:43:32.698  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 19:43:32.699  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:32.699  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:32.699  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 19:43:32.699  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.699  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.699  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.699  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.699  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.699  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.699  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.700  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
,09-13 19:43:32.700  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.700  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.700  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.700  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.700  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.701  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:32.701  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.701  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.701  3800  3800 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 19:43:32.701  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.701  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.701  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.702  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.702  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.702  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.702  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.702  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.704  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:32.704  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.704  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.704  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.705  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.705  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.705  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.705  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.705  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.705  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.705  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:32.705  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.705  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.705  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.706  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.706  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.706  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.706  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.706  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.706  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:32.706  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:32.706  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.707  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:32.707  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:32.707  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:32.707  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:32.707  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.707  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.707  3800  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e8781 not in the list
09-13 19:43:32.707  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.707  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.707  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:32.707  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.707  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:32.707  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:32.707  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:32.708  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:32.708  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:32.708  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:32.709  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:32.709  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:32.709  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:32.709  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:32.709  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3f3026 not in the list
09-13 19:43:32.709  3800  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 19:43:32.709  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 19:43:32.709  3800  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 19:43:32.709  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 19:43:32.709  3800  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 19:43:32.710  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 19:43:32.711  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 19:43:32.711  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 19:43:32.711  3800  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 19:43:32.711  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 19:43:32.711  3800  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 19:43:32.711  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 19:43:32.711  3800  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 19:43:32.711  3800  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 19:43:32.712  3800  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 19:43:32.713  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:32.713  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@905dbdc added. We now have 2 listener(s)
09-13 19:43:32.713  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:32.715  3800  3847 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 19:43:32.716   873  2001 D WifiService: setWifiEnabled: true pid=3800, uid=10000
09-13 19:43:32.716   873  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 19:43:32.717  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:32.717  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a3d4e5 added. We now have 3 listener(s)
,09-13 19:43:32.717  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:32.724  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:32.724  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6bd9bba added. We now have 4 listener(s)
09-13 19:43:32.724  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:32.725  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:32.725  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2a6b added. We now have 5 listener(s)
09-13 19:43:32.726  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:32.729   873  3132 D WifiService: setWifiEnabled: false pid=3800, uid=10000
09-13 19:43:32.729   873  3132 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 19:43:32.733  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:32.734  2671  2686 D BluetoothAdapterState: Current state: ON, message: 23
09-13 19:43:32.734  2671  2686 D BluetoothAdapterProperties: Setting state to 13
,09-13 19:43:32.734  2671  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 19:43:32.735  2671  2686 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 19:43:32.735  2671  2686 I BluetoothAdapterState: Entering PendingCommandState
09-13 19:43:32.736  2671  2671 D BluetoothMapService: onReceive
09-13 19:43:32.736  2671  2671 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 19:43:32.736  2671  2671 D BluetoothMapService: STATE_TURNING_OFF
09-13 19:43:32.736  2671  2671 D BluetoothMapService: MAP Service closeService in
,09-13 19:43:32.736  2671  2671 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 19:43:32.736  2671  2671 D ObexServerSockets0: shutdown(block = true)
09-13 19:43:32.736  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.736  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:32.737  2671  2671 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 19:43:32.737  2671  2671 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 19:43:32.737  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.737  2671  2817 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 19:43:32.737  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.738  2671  2804 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 19:43:32.738  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:32.738  2671  2816 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 19:43:32.738  2671  2671 I BtOppRfcommListener: stopping Accept Thread
,09-13 19:43:32.739  2671  3403 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 19:43:32.739  2671  3403 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 19:43:32.742  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.745  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.746  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 19:43:32.747   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 19:43:32.747   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 19:43:32.748   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 19:43:32.748   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:32.748  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:32.748  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:32.749  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.749  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:32.752  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.753   873   886 I ActivityManager: Start proc 3854:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 19:43:32.754  2671  2690 D BluetoothAdapterProperties: Scan Mode:20
,09-13 19:43:32.754  2671  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 19:43:32.756   873  1306 E native  : do suspend true
,09-13 19:43:32.757  2671  2671 D HeadsetService: Received stop request...Stopping profile...,
,09-13 19:43:32.759  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.759   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:32.759   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:32.759   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:32.759  1978  2009 D BluetoothHeadset: Proxy object disconnected
09-13 19:43:32.759  2671  2671 V BluetoothAdapterState: isTurningOff()=true
,09-13 19:43:32.759  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:32.759  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:32.759  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:32.760  1364  1375 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:32.760  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,09-13 19:43:32.761  2671  2671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 19:43:32.761  2671  2671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 19:43:32.761  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.761  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 19:43:32.761  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:32.761  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:32.761  2671  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 19:43:32.761  2671  2690 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
09-13 19:43:32.762  2671  2671 D A2dpService: Received stop request...Stopping profile...
09-13 19:43:32.762  2671  2810 D A2dpStateMachine: Exit Disconnected: -1
09-13 19:43:32.764   873   873 D BluetoothA2dp: Proxy object disconnected
,09-13 19:43:32.764  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-13 19:43:32.765  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:32.765  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:32.765  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:32.765  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:32.767  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:32.767  2671  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 19:43:32.767  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 19:43:32.767  2671  2787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 19:43:32.767  2671  2787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 19:43:32.767  2671  2787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 19:43:32.768  2671  2787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 19:43:32.768   873  2065 D DhcpClient: Clearing IP address
09-13 19:43:32.768  2671  2671 D HidService: Received stop request...Stopping profile...
09-13 19:43:32.768   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 19:43:32.769  2671  2671 D HidService: Stopping Bluetooth HidService
09-13 19:43:32.770  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-13 19:43:32.770  2671  2671 D HealthService: Received stop request...Stopping profile...
09-13 19:43:32.770  1364  1364 D HidProfile: Bluetooth service disconnected
09-13 19:43:32.772  2671  2671 D PanService: Received stop request...Stopping profile...
,09-13 19:43:32.772   371   872 D CommandListener: Setting iface cfg
09-13 19:43:32.773  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 19:43:32.773  1364  1364 D PanProfile: Bluetooth service disconnected
09-13 19:43:32.773  2671  2671 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 19:43:32.773  2671  2671 D BluetoothMapService: stop()
,09-13 19:43:32.774  2671  2671 D BluetoothMapAppObserver: deinitObservers()
,09-13 19:43:32.774  2671  2671 D BluetoothMapAppObserver: removeReceiver()
09-13 19:43:32.774   873  2070 D DhcpClient: Receive thread stopped
,09-13 19:43:32.775  1364  1364 D BluetoothMap: Proxy object disconnected
09-13 19:43:32.775  1364  1364 D MapProfile: Bluetooth service disconnected
,09-13 19:43:32.775  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:32.775  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 19:43:32.775  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:32.775  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:32.775  1491  2535 V NativeCrypto: Read error: ssl=0xab418600: I/O error during system call, Connection timed out
,09-13 19:43:32.776  2671  2671 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 19:43:32.776  2671  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 19:43:32.776  2671  2671 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 19:43:32.777  2671  2671 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:32.777  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 19:43:32.777  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:32.777  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:32.777  2671  2671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 19:43:32.777  2671  2690 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 19:43:32.777  2671  2671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 19:43:32.778  2671  2671 V BluetoothAdapterState: isTurningOff()=true
,09-13 19:43:32.778  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:32.778  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:32.778  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:32.779  2671  2671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 19:43:32.780  2671  2671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 19:43:32.780  2671  2671 D BluetoothMapService: MAP Service closeService in
09-13 19:43:32.780  2671  2671 V BluetoothAdapterState: isTurningOff()=true
,09-13 19:43:32.780  2671  2671 V BluetoothAdapterState: isTurningOn()=false
,09-13 19:43:32.780  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:32.780  2671  2671 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:32.781  2671  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 19:43:32.781  2671  2686 D BluetoothAdapterProperties: Setting state to 15
09-13 19:43:32.781  2671  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 19:43:32.781  2671  2671 D BluetoothMapService: cleanup()
09-13 19:43:32.781  2671  2686 I BluetoothAdapterState: Entering BleOnState
,09-13 19:43:32.781  2671  2671 D BluetoothMapService: MAP Service closeService in
09-13 19:43:32.782  1364  1375 D BluetoothPan: onBluetoothStateChange on: false
09-13 19:43:32.782  1491  2535 V NativeCrypto: SSL shutdown failed: ssl=0xab418600: I/O error during system call, Broken pipe
09-13 19:43:32.782  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 19:43:32.783  1364  2066 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 19:43:32.784   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 19:43:32.784   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 19:43:32.784  1978  1995 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:32.784  1364  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 19:43:32.785   873  2001 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-13 19:43:32.785   873  2062 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-13 19:43:32.786   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 19:43:32.786   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 19:43:32.786   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 19:43:32.787   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 19:43:32.787   873  1306 E native  : do suspend true
09-13 19:43:32.790   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 19:43:32.793  1364  1376 D BluetoothMap: onBluetoothStateChange: up=false
09-13 19:43:32.794   395   395 E Parcel  : Reading a NULL string not supported here.
09-13 19:43:32.795   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:32.795  1364  2066 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:32.795   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:32.796   873  2062 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-13 19:43:32.799  2671  2686 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 19:43:32.799  2671  2686 D BluetoothAdapterProperties: Setting state to 16
09-13 19:43:32.799  2671  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 19:43:32.800  2671  2686 D BluetoothAdapterProperties: onBleDisable
09-13 19:43:32.801  2671  2686 I BluetoothAdapterState: Entering PendingCommandState
09-13 19:43:32.801  2671  2687 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 19:43:32.802  2671  2787 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 19:43:32.802  2671  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:32.803  3800  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
09-13 19:43:32.803  2671  2690 D BluetoothAdapterProperties: Scan Mode:20
09-13 19:43:32.806  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:32.806  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:32.807  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.808  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:32.809  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:32.809  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:32.810  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.810  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:32.811  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:32.812  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.815   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 19:43:32.820  3854  3854 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-13 19:43:32.837  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 19:43:32.838   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 19:43:32.839   371   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 19:43:32.839   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 19:43:32.839   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 19:43:32.842   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 19:43:32.843   873   890 D Tethering: MasterInitialState.processMessage what=3
09-13 19:43:32.846  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.847  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:32.850  3394  3394 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@38ffa42 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-13 19:43:32.850  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 19:43:32.864   873  2001 I ActivityManager: Start proc 3873:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 19:43:32.865   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 19:43:32.869  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:32.869   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:32.870  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:32.871  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.871  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:32.872  1854  2257 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 19:43:32.872  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:32.872  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:32.873   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c2c9321:true
09-13 19:43:32.873  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:32.873  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:32.896   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 19:43:32.897   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 19:43:32.899  3854  3854 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 19:43:32.901  3854  3854 D BluetoothMap: Create BluetoothMap proxy object
,09-13 19:43:32.906  3873  3873 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 19:43:32.912  3854  3854 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 19:43:32.926  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-13 19:43:32.931   873   884 I ActivityManager: Killing 3196:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 19:43:33.002  2671  2690 I bt_hci  : shut_down
,09-13 19:43:33.003  2671  2697 D bt_hwcfg: hw_epilog_process
09-13 19:43:33.004  2671  2697 I bt_vendor: low_power_mode_cb
,09-13 19:43:33.029  2671  2697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 19:43:33.029  2671  2697 I bt_vendor: epilog_cb
09-13 19:43:33.029  2671  2697 I bt_hci  : epilog_finished_callback
,09-13 19:43:33.033  2671  2690 I bt_hci_h4: hal_close
,09-13 19:43:33.034  2671  2690 I bt_userial_vendor: device fd = 51 close
,09-13 19:43:33.058  3873  3873 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.058  3873  3873 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.058  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 19:43:33.066  387,3  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:4,3:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.066  3873  3873 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 19:43:33.066  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 19:43:33.084  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 19:43:33.109  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 19:43:33.110  3854  3854 D DockEventReceiver: finishStartingService: stopping service
09-13 19:43:33.123   873  3132 I ActivityManager: Killing 3394:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 19:43:33.179  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 19:43:33.190  2671  2687 D bt_stack_manager: event_shut_down_stack finished.
,09-13 19:43:33.190  2671  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-13 19:43:33.192  1709  1709 D SystemUpdateService: onCreate
09-13 19:43:33.198  2671  2671 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 19:43:33.199  2671  2686 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 19:43:33.201  3800  3800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 19:43:33.200  2671  2671 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 19:43:33.202  2671  2671 D BtGatt.GattService: stop()
09-13 19:43:33.202  2671  2671 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 19:43:33.203  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 19:43:33.204  2671  2671 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:33.204  2671  2671 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:33.205  2671  2671 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:33.205  2671  2671 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 19:43:33.205  2671  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 19:43:33.205  2671  2686 D BluetoothAdapterProperties: Setting state to 10
09-13 19:43:33.206  2671  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 19:43:33.206  2671  2686 I BluetoothAdapterState: Entering OffState
09-13 19:43:33.208   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 19:43:33.225  2671  2671 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 19:43:33.225  2671  2671 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 19:43:33.225  2671  2687 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 19:43:33.227  2671  2671 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 19:43:33.227  2671  2687 D bt_stack_manager: event_clean_up_stack finished.
,09-13 19:43:33.230  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 19:43:33.235  2671  2671 I art     : System.exit called, status: 0
,09-13 19:43:33.235  2671  2671 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 19:43:33.259  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 19:43:33.260  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 19:43:33.265  1709  2514 I iu.UploadsManager: num queued entries: 0
,09-13 19:43:33.265  1709  2514 I iu.UploadsManager: num updated entries: 0
09-13 19:43:33.265  1709  2514 I iu.SyncManager: NEXT; no task
,09-13 19:43:33.249  1709  3907 I SystemUpdateService: active receiver: enabled
,09-13 19:43:33.279  1709  3907 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 19:43:33.281  1709  3907 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 19:43:33.281  1709  3907 I SystemUpdateService: now status is 0 (complete)
09-13 19:43:33.281  1709  3907 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 19:43:33.281  1709  3907 I SystemUpdateService: file has been verified
,09-13 19:43:33.281  1709  3907 I SystemUpdateService: OTA package size = 12249756
,09-13 19:43:33.295  1709  3907 I SystemUpdateService: showing system update notification
,09-13 19:43:33.310   873  2146 I ActivityManager: Start proc 3911:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 19:43:33.312   873  1947 I ActivityManager: Process com.android.bluetooth (pid 2671) has died
,09-13 19:43:33.350  3911  3911 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 19:43:33.353  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 19:43:33.372  3911  3911 D SprintDMHelper: simOperator: 
,09-13 19:43:33.372  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 19:43:33.388   873  2001 I ActivityManager: Start proc 3925:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 19:43:33.395  1709  1709 D SystemUpdateService: onDestroy
09-13 19:43:33.398   873  1707 I ActivityManager: Killing 2775:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 19:43:33.457  3873  3901 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 19:43:33.524   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@adebd32:true
,09-13 19:43:33.560   873  1383 I ActivityManager: Start proc 3941:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 19:43:33.596  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 19:43:33.642  3941  3941 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 19:43:33.642  3941  3941 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 19:43:33.642  3941  3941 I GAv4    :   adb logcat -s GAv4
,09-13 19:43:33.656  3941  3941 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:43:33.660  3941  3941 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:43:33.688  3941  3958 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:43:33.772  3941  3941 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 19:43:33.809  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 19:43:33.819  3941  3941 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 4515-4520)
09-13 19:43:33.819  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 19:43:33.826  3941  3941 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d9f77f2}
09-13 19:43:33.827  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 19:43:33.827  3941  3941 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 19:43:33.833  3941  3941 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 19:43:33.834  3941  3941 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 19:43:33.847  3941  3941 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 19:43:33.861  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 19:43:33.861  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 19:43:33.861  3941  3941 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 19:43:33.861  3941  3941 I Adreno  : Build Date                       : 10/20/15
09-13 19:43:33.861  3941  3941 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 19:43:33.861  3941  3941 I Adreno  : Local Branch                     : M14
09-13 19:43:33.861  3941  3941 I Adreno  : Remote Branch                    : 
09-13 19:43:33.861  3941  3941 I Adreno  : Remote Branch                    : 
09-13 19:43:33.861  3941  3941 I Adreno  : Reconstruct Branch               : 
,09-13 19:43:33.917  3941  3941 I NSApplication: Starting up...
,09-13 19:43:33.926  3941  3987 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 19:43:33.943   873  2001 I ActivityManager: Start proc 3992:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 19:43:33.944   873  2001 I ActivityManager: Killing 1693:android.process.acore/u0a5 (adj 15): empty #17
,09-13 19:43:34.035  3992  3992 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 19:43:34.220   873  2001 I ActivityManager: Killing 3604:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 19:43:34.319   873  1383 I ActivityManager: Start proc 4006:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 19:43:34.388  4006  4006 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 19:43:34.448  4006  4006 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 19:43:34.513   873  1383 I ActivityManager: Killing 3570:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-13 19:43:35.741   873  2028 D WifiService: setWifiEnabled: true pid=3800, uid=10000
,09-13 19:43:35.741   873  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 19:43:35.756   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-13 19:43:35.763  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:35.764  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:35.764  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:35.764  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:35.767  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:35.767  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:35.768  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:35.768  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:35.800   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-13 19:43:35.801   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 19:43:35.802   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 19:43:35.803   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 19:43:35.804   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 19:43:35.804   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 19:43:35.804   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 19:43:35.820   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 19:43:35.820   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 19:43:35.823   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:35.831   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 19:43:35.831   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 19:43:35.832   873  1306 E native  : do suspend true
,09-13 19:43:35.842   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 19:43:35.846   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 19:43:35.847   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 19:43:37.135   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 19:43:37.227   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.31 rxSuccessRate=16.81 delta 1000 -> 994
,09-13 19:43:37.229   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 19:43:37.229   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:37.242   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 19:43:37.280   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 19:43:37.282  1450  1450 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 19:43:37.712  1450  1450 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 19:43:37.761  1450  1450 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 19:43:37.762  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 19:43:37.764   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 19:43:37.774   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 19:43:37.774   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 19:43:37.774   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 19:43:37.790   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:37.806   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:37.806   873  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 19:43:37.814   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 19:43:37.836   873  4040 D DhcpClient: Receive thread started
,09-13 19:43:37.926   873  1306 E native  : do suspend false
,09-13 19:43:37.942   873  2065 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 19:43:37.957   873  4040 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172544, domain null
,09-13 19:43:37.958   873  2065 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172544 seconds
09-13 19:43:37.959   873  2065 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 19:43:37.973   873  4040 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 19:43:37.974   873  2065 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 19:43:37.975   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:37.981   873  2065 D DhcpClient: Scheduling renewal in 86399s
,09-13 19:43:37.986   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 19:43:37.988   873  1306 E native  : do suspend true
,09-13 19:43:38.006   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 19:43:38.009   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 19:43:38.010   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 19:43:38.013   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 19:43:38.020   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 19:43:38.075   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 19:43:38.076   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 19:43:38.077   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 19:43:38.078   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 19:43:38.079   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 19:43:38.089   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 19:43:38.096   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 19:43:38.097   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 19:43:38.097   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 19:43:38.098   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 19:43:38.098   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-13 19:43:38.098   873  1308 D ConnectivityService:    accepting network in place of null
09-13 19:43:38.100   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 19:43:38.110   873  4039 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 19:43:38.136   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:38.172   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:38.182   873  4038 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 19:43:38.183   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 19:43:38.183   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 19:43:38.186   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 19:43:38.188   873   890 D Tethering: MasterInitialState.processMessage what=3
09-13 19:43:38.199  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:38.199  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:43:38.199  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.199  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:38.209  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:38.209  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:43:38.210  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.210  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:38.213  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 19:43:38.217  1709  1709 D SystemUpdateService: onCreate
,09-13 19:43:38.224  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 19:43:38.227  1709  4052 I SystemUpdateService: active receiver: enabled
,09-13 19:43:38.231  1709  4052 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 19:43:38.234  1709  4052 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 19:43:38.235  1709  4052 I SystemUpdateService: now status is 0 (complete)
,09-13 19:43:38.235  1709  4052 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 19:43:38.235  1709  4052 I SystemUpdateService: file has been verified
,09-13 19:43:38.237  1709  4052 I SystemUpdateService: OTA package size = 12249756
,09-13 19:43:38.241  1709  4052 I SystemUpdateService: showing system update notification
,09-13 19:43:38.251  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 19:43:38.258  1709  4055 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 19:43:38.258  1709  4055 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 19:43:38.259  1709  4055 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 19:43:38.262  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 19:43:38.263  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 19:43:38.267   873  4038 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 17:43:38 GMT], X-Android-Received-Millis=[1473788618266], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473788618243]}
,09-13 19:43:38.267  1709  1709 D SystemUpdateService: onDestroy
09-13 19:43:38.268   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-13 19:43:38.268   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 19:43:38.268   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 19:43:38.269  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 19:43:38.269   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 19:43:38.274  1709  2514 I iu.UploadsManager: num queued entries: 0
,09-13 19:43:38.276  1709  2514 I iu.UploadsManager: num updated entries: 0
,09-13 19:43:38.281  1709  2514 I iu.SyncManager: NEXT; no task
,09-13 19:43:38.281  3911  3911 D SprintDMHelper: simOperator: 
09-13 19:43:38.281  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-13 19:43:38.283  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 19:43:38.284  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:43:38.320  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 19:43:38.320  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 19:43:38.321  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:43:38.321  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:43:38.338  1709  4055 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-13 19:43:38.386  2140  4058 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 19:43:38.602   873  1947 I ActivityManager: Killing 3621:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 19:43:38.748   873  2028 D WifiService: setWifiEnabled: false pid=3800, uid=10000
,09-13 19:43:38.749   873  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 19:43:38.758  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 19:43:38.760   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 19:43:38.760   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 19:43:38.760   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 19:43:38.760   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:38.774   873  1306 E native  : do suspend true
,09-13 19:43:38.781   873  2065 D DhcpClient: Clearing IP address
,09-13 19:43:38.781   371   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 19:43:38.784   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:38.793  1491  4064 V NativeCrypto: Read error: ssl=0x9acc8000: I/O error during system call, Connection timed out
09-13 19:43:38.795  1491  4064 V NativeCrypto: SSL shutdown failed: ssl=0x9acc8000: I/O error during system call, Broken pipe
,09-13 19:43:38.799   873  1383 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-13 19:43:38.800   873  4038 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-13 19:43:38.801   873  4038 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-13 19:43:38.801   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 19:43:38.801   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 19:43:38.802   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-13 19:43:38.810   395   395 E Parcel  : Reading a NULL string not supported here.
,09-13 19:43:38.811   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 19:43:38.816   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 19:43:38.816   873  1306 E native  : do suspend true
09-13 19:43:38.816   873  4038 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-13 19:43:38.818   873  4040 D DhcpClient: Receive thread stopped
,09-13 19:43:38.850   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:38.882   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:38.883   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 19:43:38.883   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 19:43:38.885   873   890 D Tethering: MasterInitialState.processMessage what=3
09-13 19:43:38.889   371   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 19:43:38.890  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:38.891  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:38.892  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.892  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:38.897  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:38.897  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:38.897  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:38.897  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:38.898  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 19:43:38.904  1709  1709 D SystemUpdateService: onCreate
09-13 19:43:38.907  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 19:43:38.922  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-13 19:43:38.924  1709  2514 I iu.UploadsManager: num queued entries: 0
09-13 19:43:38.924  1709  2514 I iu.UploadsManager: num updated entries: 0
09-13 19:43:38.929  1709  4072 I SystemUpdateService: active receiver: enabled
09-13 19:43:38.931  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-13 19:43:38.932  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 19:43:38.935  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-13 19:43:38.942  1709  4072 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-13 19:43:38.943  3911  3911 D SprintDMHelper: simOperator: 
09-13 19:43:38.943  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-13 19:43:38.948  1709  4072 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 19:43:38.948  1709  4072 I SystemUpdateService: now status is 0 (complete)
09-13 19:43:38.948  1709  4072 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 19:43:38.948  1709  4072 I SystemUpdateService: file has been verified
,09-13 19:43:38.961  1709  2514 I iu.SyncManager: NEXT; no task
,09-13 19:43:38.948  1709  4072 I SystemUpdateService: OTA package size = 12249756
,09-13 19:43:38.980  2140  4076 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 19:43:38.983   371   872 E Netd    : netlink response contains error (No such file or directory),
,09-13 19:43:38.996   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 19:43:38.996   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 19:43:38.996   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 19:43:39.007  1709  4072 I SystemUpdateService: showing system update notification
,09-13 19:43:39.012   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 19:43:39.014  1854  2257 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 19:43:39.018  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:39.019  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:39.019  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:39.019  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:39.020  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:39.020  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:39.020  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:39.021  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:39.021   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 19:43:39.039  1709  1709 D SystemUpdateService: onDestroy
,09-13 19:43:39.179   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 19:43:41.801   873   890 I ActivityManager: Start proc 4083:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 19:43:41.946  4083  4083 D AdapterServiceConfig: Adding HeadsetService
,09-13 19:43:41.947  4083  4083 D AdapterServiceConfig: Adding A2dpService
09-13 19:43:41.948  4083  4083 D AdapterServiceConfig: Adding HidService
,09-13 19:43:41.950  4083  4083 D AdapterServiceConfig: Adding HealthService
,09-13 19:43:41.951  4083  4083 D AdapterServiceConfig: Adding PanService
,09-13 19:43:41.953  4083  4083 D AdapterServiceConfig: Adding GattService
,09-13 19:43:41.954  4083  4083 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 19:43:41.975   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43da708:true
,09-13 19:43:41.975  4083  4083 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 19:43:41.979  4083  4083 I bt_bluedroid: init
,09-13 19:43:41.979  4083  4095 I BluetoothAdapterState: Entering OffState
,09-13 19:43:41.985  4083  4096 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 19:43:41.985  4083  4096 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 19:43:41.985  4083  4096 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 19:43:41.986  4083  4096 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 19:43:41.987  4083  4083 I bt_bluedroid: get_profile_interface socket
,09-13 19:43:41.990  4083  4099 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 19:43:41.991  4083  4083 I bt_bluedroid: get_profile_interface sdp
09-13 19:43:41.992  4083  4099 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 19:43:41.996  4083  4094 I bt_bluedroid: config_hci_snoop_log
,09-13 19:43:41.998   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 19:43:42.004  4083  4095 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 19:43:42.005  4083  4095 D BluetoothAdapterProperties: Setting state to 14
09-13 19:43:42.005  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 19:43:42.007  4083  4095 D BluetoothBondStateMachine: make
,09-13 19:43:42.012  4083  4100 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 19:43:42.018  4083  4095 I BluetoothAdapterState: Entering PendingCommandState
,09-13 19:43:42.019  4083  4083 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 19:43:42.025  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:42.026  4083  4083 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 19:43:42.027  4083  4083 D BtGatt.GattService: Received start request. Starting profile...
,09-13 19:43:42.028  4083  4083 D BtGatt.GattService: start()
,09-13 19:43:42.028  4083  4083 I bt_bluedroid: get_profile_interface gatt
09-13 19:43:42.030  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:42.031  4083  4083 D BtGatt.AdvertiseManager: advertise manager created
,09-13 19:43:42.042  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:42.042  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:42.042  4083  4083 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 19:43:42.043  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:42.043  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 19:43:42.044  4083  4095 I bt_bluedroid: enable
09-13 19:43:42.044  4083  4096 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 19:43:42.045  4083  4096 I bt_hci  : start_up
,09-13 19:43:42.066  4083  4096 I bt_vendor: alloc value 0xb39e5189
,09-13 19:43:42.066  4083  4096 I bt_vendor: init
09-13 19:43:42.067  4083  4096 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 19:43:42.067  4083  4096 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 19:43:42.175  4083  4096 D bt_hci  : start_up starting async portion
,09-13 19:43:42.175  4083  4103 I bt_hci  : event_finish_startup
09-13 19:43:42.176  4083  4103 I bt_hci_h4: hal_open
09-13 19:43:42.176  4083  4103 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 19:43:42.187  4083  4103 I bt_userial_vendor: device fd = 51 open
,09-13 19:43:42.216  4083  4103 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 19:43:42.247  4083  4103 D bt_hwcfg: Chipset BCM4354A2
,09-13 19:43:42.248  4083  4103 D bt_hwcfg: Target name = [BCM4354A2]
09-13 19:43:42.249  4083  4103 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 19:43:42.469  1491  2175 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,09-13 19:43:42.912  4083  4103 I bt_hwcfg: bt vendor lib: set UART baud 115200,
09-13 19:43:42.913  4083  4103 D bt_hwcfg: Settlement delay -- 100 ms
09-13 19:43:42.913  4083  4103 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 19:43:43.030  4083  4103 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 19:43:43.032  4083  4103 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 19:43:43.060  4083  4103 I bt_hwcfg: vendor lib fwcfg completed
,09-13 19:43:43.060  4083  4103 I bt_vendor: firmware callback
09-13 19:43:43.060  4083  4103 I bt_hci  : firmware_config_callback
,09-13 19:43:43.073  4083  4105 I bt_btu  : btu_task pending for preload complete event
,09-13 19:43:43.073  4083  4105 I bt_btu_task: Bluetooth chip preload is complete
09-13 19:43:43.074  4083  4105 I bt_btu  : btu_task received preload complete event
,09-13 19:43:43.084  4083  4105 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 19:43:43.084  4083  4105 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 19:43:43.084  4083  4105 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 19:43:43.085  4083  4105 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 19:43:43.085  4083  4105 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 19:43:43.085  4083  4105 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 19:43:43.086  4083  4105 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 19:43:43.086  4083  4105 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 19:43:43.086  4083  4105 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 19:43:43.086  4083  4105 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 19:43:43.087  4083  4105 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 19:43:43.087  4083  4105 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 19:43:43.087  4083  4105 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 19:43:43.087  4083  4105 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 19:43:43.088  4083  4105 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 19:43:43.221  4083  4105 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,09-13 19:43:43.222  4083  4105 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,09-13 19:43:43.246  4083  4099 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 19:43:43.248  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 19:43:43.248  4083  4099 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 19:43:43.250  4083  4099 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 19:43:43.252  4083  4099 D BluetoothAdapterProperties: Scan Mode:20
09-13 19:43:43.252  4083  4099 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 19:43:43.252  4083  4099 D bt_hci  : do_postload posting postload work item
09-13 19:43:43.252  4083  4103 I bt_hci  : event_postload
09-13 19:43:43.253  4083  4103 I bt_vendor: sco_config_cb
09-13 19:43:43.253  4083  4103 I bt_hci  : sco_config_callback postload finished.
09-13 19:43:43.253  4083  4099 D bt_bte_conf: Device ID record 1 : primary
09-13 19:43:43.253  4083  4099 D bt_bte_conf:   vendorId            = 000f
09-13 19:43:43.253  4083  4099 D bt_bte_conf:   vendorIdSource      = 0001
09-13 19:43:43.254  4083  4099 D bt_bte_conf:   product             = 1200
09-13 19:43:43.254  4083  4099 D bt_bte_conf:   version             = 1436
09-13 19:43:43.254  4083  4099 D bt_bte_conf:   clientExecutableURL = 
09-13 19:43:43.254  4083  4099 D bt_bte_conf:   serviceDescription  = 
09-13 19:43:43.254  4083  4099 D bt_bte_conf:   documentationURL    = 
09-13 19:43:43.254  4083  4099 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 19:43:43.254  4083  4096 D bt_stack_manager: event_start_up_stack finished
,09-13 19:43:43.255  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 19:43:43.256  4083  4095 D BluetoothAdapterProperties: Setting state to 15
09-13 19:43:43.256  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 19:43:43.257  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:43.257  4083  4095 I BluetoothAdapterState: Entering BleOnState
09-13 19:43:43.260  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:43.262  4083  4095 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 19:43:43.262  4083  4095 D BluetoothAdapterProperties: Setting state to 11
,09-13 19:43:43.262  4083  4103 I bt_vendor: low_power_mode_cb
09-13 19:43:43.263  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 19:43:43.270  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:43.271  4083  4083 D HeadsetService: Received start request. Starting profile...
09-13 19:43:43.275  4083  4083 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 19:43:43.275  4083  4083 D HeadsetStateMachine: make
09-13 19:43:43.279  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:43.283  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:43.288  4083  4083 D HeadsetStateMachine: max_hf_connections = 1
09-13 19:43:43.288  4083  4083 I bt_bluedroid: get_profile_interface handsfree
09-13 19:43:43.289  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 19:43:43.289  4083  4099 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 19:43:43.292  4083  4095 I BluetoothAdapterState: Entering PendingCommandState
09-13 19:43:43.294  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:43.295  4083  4083 D A2dpService: Received start request. Starting profile...
,09-13 19:43:43.296  4083  4083 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 19:43:43.296  4083  4083 I bt_bluedroid: get_profile_interface avrcp
,09-13 19:43:43.302  4083  4083 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 19:43:43.302  4083  4083 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 19:43:43.302  4083  4083 D A2dpStateMachine: make
09-13 19:43:43.303  4083  4083 I bt_bluedroid: get_profile_interface a2dp
,09-13 19:43:43.303  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 19:43:43.306  4083  4115 D A2dpStateMachine: Enter Disconnected: -2
,09-13 19:43:43.309  4083  4083 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 19:43:43.309  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 19:43:43.310  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:43.311  4083  4083 D HidService: Received start request. Starting profile...
09-13 19:43:43.311  3854  3854 D BluetoothInputDevice: Proxy object connected
09-13 19:43:43.311  4083  4083 I bt_bluedroid: get_profile_interface hidhost
,09-13 19:43:43.311  4083  4099 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
09-13 19:43:43.311  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 19:43:43.311  4083  4083 D HidService: setHidService(): set to: null
,09-13 19:43:43.312  3854  3854 D HidProfile: Bluetooth service connected
09-13 19:43:43.312  4083  4083 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 19:43:43.313  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:43.313  4083  4083 D HealthService: Received start request. Starting profile...
,09-13 19:43:43.315  4083  4083 I bt_bluedroid: get_profile_interface health
,09-13 19:43:43.315  4083  4083 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 19:43:43.316  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:43.317  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 19:43:43.317  4083  4083 D PanService: Received start request. Starting profile...
09-13 19:43:43.317  4083  4083 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 19:43:43.317  4083  4083 I bt_bluedroid: get_profile_interface pan
09-13 19:43:43.318  4083  4099 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 19:43:43.318  3854  3854 D PanProfile: Bluetooth service connected
,09-13 19:43:43.320  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:43.321  4083  4083 D BluetoothMapService: Received start request. Starting profile...
09-13 19:43:43.321  4083  4083 D BluetoothMapService: start()
09-13 19:43:43.321  3854  3854 D BluetoothMap: Proxy object connected
09-13 19:43:43.321  3854  3854 D MapProfile: Bluetooth service connected
09-13 19:43:43.321  3854  3854 D BluetoothMap: getConnectedDevices()
09-13 19:43:43.322  3854  3854 D BluetoothMap: Bluetooth is Not enabled
09-13 19:43:43.323  4083  4083 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 19:43:43.323  4083  4083 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 19:43:43.324  4083  4083 D BluetoothMapAppObserver: createReceiver()
,09-13 19:43:43.324  4083  4083 D BluetoothMapAppObserver: initObservers()
09-13 19:43:43.324  4083  4083 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 19:43:43.330  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:43.330  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.330  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.330  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:43.332  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:43.332  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.332  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.332  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:43.332  4083  4112 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.333  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:43.334  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:43.334  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:43.334  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:43.334  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:43.334  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 19:43:43.334  4083  4095 D BluetoothAdapterProperties: ScanMode =  20
,09-13 19:43:43.334  4083  4095 D BluetoothAdapterProperties: State =  11
09-13 19:43:43.335  4083  4095 D BluetoothAdapterProperties: Setting state to 12
09-13 19:43:43.335  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 19:43:43.336  1364  2066 D BluetoothPan: onBluetoothStateChange on: true
09-13 19:43:43.337  4083  4099 D BluetoothAdapterProperties: Scan Mode:21
09-13 19:43:43.337  4083  4095 I BluetoothAdapterState: Entering OnState
,09-13 19:43:43.337  4083  4099 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 19:43:43.340  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 19:43:43.340  1364  1364 D PanProfile: Bluetooth service connected
09-13 19:43:43.340  3854  3864 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:43.340  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:43.341  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 19:43:43.344  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:43.344  3854  3865 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 19:43:43.346  3854  3864 D BluetoothPan: onBluetoothStateChange on: true
,09-13 19:43:43.346  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:43.346  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:43.348  1364  1364 D BluetoothInputDevice: Proxy object connected
09-13 19:43:43.348   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 19:43:43.348  1364  1364 D HidProfile: Bluetooth service connected
,09-13 19:43:43.348  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:43.349   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 19:43:43.349  1978  1995 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:43.350  1364  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 19:43:43.350   873   873 D BluetoothA2dp: Proxy object connected
,09-13 19:43:43.350  4083  4083 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 19:43:43.351  4083  4083 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 19:43:43.352  1364  1364 D BluetoothA2dp: Proxy object connected
09-13 19:43:43.352  1364  1376 D BluetoothMap: onBluetoothStateChange: up=true
09-13 19:43:43.352  4083  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 19:43:43.354   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 19:43:43.354  1364  2066 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:43.354  1364  1364 D BluetoothMap: Proxy object connected
,09-13 19:43:43.354  1364  1364 D MapProfile: Bluetooth service connected
09-13 19:43:43.354  1364  1364 D BluetoothMap: getConnectedDevices()
09-13 19:43:43.355   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:43.355  4083  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 19:43:43.355  3854  3865 D BluetoothMap: onBluetoothStateChange: up=true
09-13 19:43:43.357   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 19:43:43.359  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:43.359  4083  4083 D ObexServerSockets: Succeed to create listening sockets 
09-13 19:43:43.359  4083  4083 D ObexServerSockets0: startAccept()
,09-13 19:43:43.360  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:43.360  4083  4083 D ObexServerSockets0: prepareForNewConnect()
,09-13 19:43:43.361  3854  3854 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 19:43:43.363  4083  4083 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 19:43:43.363  4083  4083 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 19:43:43.364  4083  4083 D BluetoothMapService: onReceive
09-13 19:43:43.364  4083  4083 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 19:43:43.364  4083  4083 D BluetoothMapService: STATE_ON
09-13 19:43:43.364  4083  4120 D ObexServerSockets0: Accepting socket connection...
09-13 19:43:43.364  4083  4121 D ObexServerSockets0: Accepting socket connection...
,09-13 19:43:43.367  3854  3854 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 19:43:43.373  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 19:43:43.376  3854  3854 D BluetoothA2dp: Proxy object connected
,09-13 19:43:43.380  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 19:43:43.386  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-13 19:43:43.390  3854  3854 D BluetoothPbap: Proxy object connected
,09-13 19:43:43.390  1364  1364 D BluetoothPbap: Proxy object connected
09-13 19:43:43.390  1364  1364 D PbapServerProfile: Bluetooth service connected
09-13 19:43:43.390  3854  3854 D PbapServerProfile: Bluetooth service connected
09-13 19:43:43.390  4083  4083 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 19:43:43.390  4083  4083 D ObexServerSockets0: prepareForNewConnect()
,09-13 19:43:43.399  4083  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 19:43:43.412  4083  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 19:43:43.414  4083  4129 I BtOppRfcommListener: Accept thread started.
,09-13 19:43:43.450   873   873 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.450   873   873 D BluetoothHeadset: Proxy object connected
09-13 19:43:43.451   873   873 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.451  1978  2055 D BluetoothHeadset: Proxy object connected
09-13 19:43:43.452  1364  1376 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.452  1364  1364 D HeadsetProfile: Bluetooth service connected
09-13 19:43:43.454   873   890 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.456  1364  2066 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.456   873   890 D BluetoothHeadset: Proxy object connected
09-13 19:43:43.457  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-13 19:43:43.471  3854  3864 D BluetoothHeadset: Proxy object connected
,09-13 19:43:43.471  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-13 19:43:44.764  4083  4095 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 19:43:44.765  4083  4095 D BluetoothAdapterProperties: Setting state to 13
09-13 19:43:44.765  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 19:43:44.767  4083  4095 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 19:43:44.776  4083  4083 D BluetoothMapService: onReceive
,09-13 19:43:44.776  4083  4083 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 19:43:44.777  4083  4083 D BluetoothMapService: STATE_TURNING_OFF
09-13 19:43:44.777  4083  4083 D BluetoothMapService: MAP Service closeService in
,09-13 19:43:44.777  4083  4083 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 19:43:44.778  4083  4083 D ObexServerSockets0: shutdown(block = true)
09-13 19:43:44.779  4083  4120 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 19:43:44.781  4083  4083 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 19:43:44.781  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:44.781  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:44.782  4083  4095 I BluetoothAdapterState: Entering PendingCommandState
09-13 19:43:44.782  4083  4121 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 19:43:44.783  4083  4107 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 19:43:44.783  4083  4083 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 19:43:44.784  4083  4083 I BtOppRfcommListener: stopping Accept Thread
09-13 19:43:44.785  4083  4129 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 19:43:44.787  4083  4099 D BluetoothAdapterProperties: Scan Mode:20
09-13 19:43:44.787  4083  4129 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 19:43:44.786  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:44.788  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:44.788  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 19:43:44.793  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:44.793  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:44.794  3800  3800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 19:43:44.794  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:44.794  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 19:43:44.795  4083  4083 D HeadsetService: Received stop request...Stopping profile...
09-13 19:43:44.796  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:44.797  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:44.803   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:44.803   873   873 D BluetoothHeadset: Proxy object disconnected
09-13 19:43:44.803   873   873 D BluetoothHeadset: Proxy object disconnected
09-13 19:43:44.804  3854  3864 D BluetoothHeadset: Proxy object disconnected
09-13 19:43:44.805  1978  2009 D BluetoothHeadset: Proxy object disconnected
,09-13 19:43:44.805  1364  1375 D BluetoothHeadset: Proxy object disconnected
09-13 19:43:44.806  4083  4083 D A2dpService: Received stop request...Stopping profile...
,09-13 19:43:44.806  4083  4115 D A2dpStateMachine: Exit Disconnected: -1
,09-13 19:43:44.806  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-13 19:43:44.807  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-13 19:43:44.807   873   873 D BluetoothA2dp: Proxy object disconnected
09-13 19:43:44.808  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:44.808  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:44.808  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:44.808  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:44.812  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 19:43:44.813  4083  4083 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 19:43:44.813  4083  4083 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 19:43:44.813  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 19:43:44.813  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:44.813  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:44.814  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:44.814  4083  4099 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 19:43:44.814  3854  3854 D DockEventReceiver: finishStartingService: stopping service
09-13 19:43:44.815  4083  4083 D HidService: Received stop request...Stopping profile...
09-13 19:43:44.815  4083  4083 D HidService: Stopping Bluetooth HidService
09-13 19:43:44.815  3854  3854 D HeadsetProfile: Bluetooth service disconnected
09-13 19:43:44.815  3854  3854 D BluetoothA2dp: Proxy object disconnected
09-13 19:43:44.816  1364  1364 D BluetoothInputDevice: Proxy object disconnected
,09-13 19:43:44.816  1364  1364 D HidProfile: Bluetooth service disconnected
09-13 19:43:44.816  3854  3854 D BluetoothInputDevice: Proxy object disconnected
09-13 19:43:44.816  3854  3854 D HidProfile: Bluetooth service disconnected
09-13 19:43:44.817  4083  4083 D HealthService: Received stop request...Stopping profile...
09-13 19:43:44.818  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:44.818  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:44.818  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:44.818  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:44.819  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 19:43:44.819  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:44.819  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 19:43:44.820  4083  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 19:43:44.820  4083  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 19:43:44.820  4083  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 19:43:44.820  4083  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 19:43:44.822  4083  4083 D PanService: Received stop request...Stopping profile...
,09-13 19:43:44.824  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 19:43:44.824  1364  1364 D PanProfile: Bluetooth service disconnected
09-13 19:43:44.824  3854  3854 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 19:43:44.825  3854  3854 D PanProfile: Bluetooth service disconnected
09-13 19:43:44.824  4083  4083 D BluetoothMapService: Received stop request...Stopping profile...
09-13 19:43:44.825  4083  4083 D BluetoothMapService: stop()
09-13 19:43:44.825  4083  4083 D BluetoothMapAppObserver: deinitObservers()
09-13 19:43:44.825  4083  4083 D BluetoothMapAppObserver: removeReceiver()
,09-13 19:43:44.827  1364  1364 D BluetoothMap: Proxy object disconnected
,09-13 19:43:44.827  1364  1364 D MapProfile: Bluetooth service disconnected
09-13 19:43:44.827  3854  3854 D BluetoothMap: Proxy object disconnected
09-13 19:43:44.827  3854  3854 D MapProfile: Bluetooth service disconnected
09-13 19:43:44.828  1364  1364 D BluetoothPbap: Proxy object disconnected
09-13 19:43:44.829  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,09-13 19:43:44.829  3854  3854 D BluetoothPbap: Proxy object disconnected
,09-13 19:43:44.829  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:44.829  3854  3854 D PbapServerProfile: Bluetooth service disconnected
,09-13 19:43:44.829  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:44.829  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:44.829  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:44.829  4083  4083 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 19:43:44.830  4083  4083 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 19:43:44.830  4083  4099 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 19:43:44.830  4083  4083 V BluetoothAdapterState: isTurningOff()=true
,09-13 19:43:44.830  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:44.830  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:44.830  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:44.830  4083  4083 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 19:43:44.831  4083  4083 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 19:43:44.831  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:44.831  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:44.831  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:44.831  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:44.831  4083  4099 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 19:43:44.832  4083  4083 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 19:43:44.832  4083  4083 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 19:43:44.833  4083  4083 D BluetoothMapService: MAP Service closeService in
09-13 19:43:44.833  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-13 19:43:44.833  4083  4083 V BluetoothAdapterState: isTurningOn()=false
,09-13 19:43:44.833  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:44.833  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:44.833  4083  4083 D BluetoothMapService: cleanup()
09-13 19:43:44.833  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 19:43:44.833  4083  4095 D BluetoothAdapterProperties: Setting state to 15
09-13 19:43:44.833  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 19:43:44.834  4083  4095 I BluetoothAdapterState: Entering BleOnState
09-13 19:43:44.833  4083  4083 D BluetoothMapService: MAP Service closeService in
09-13 19:43:44.836  1364  2066 D BluetoothPan: onBluetoothStateChange on: false
,09-13 19:43:44.837  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 19:43:44.838  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 19:43:44.838  3854  3864 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 19:43:44.839  3854  3865 D BluetoothPan: onBluetoothStateChange on: false
09-13 19:43:44.840  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 19:43:44.840   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 19:43:44.841   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:44.841  3854  3864 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 19:43:44.842  1978  1995 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:44.842  1364  2066 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 19:43:44.842  1364  1375 D BluetoothMap: onBluetoothStateChange: up=false
09-13 19:43:44.843   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 19:43:44.843  1364  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:44.844  3854  3865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 19:43:44.844   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 19:43:44.844  3854  3864 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 19:43:44.845  4083  4095 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 19:43:44.845  4083  4095 D BluetoothAdapterProperties: Setting state to 16
,09-13 19:43:44.845  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 19:43:44.846  4083  4095 D BluetoothAdapterProperties: onBleDisable
,09-13 19:43:44.848  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:44.849  4083  4096 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 19:43:44.849  4083  4099 D BluetoothAdapterProperties: Scan Mode:20
09-13 19:43:44.850  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:44.850  4083  4105 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 19:43:44.850  4083  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 19:43:44.851  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 19:43:44.851  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:44.850  4083  4095 I BluetoothAdapterState: Entering PendingCommandState
,09-13 19:43:44.852  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:44.856  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 19:43:44.865  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-13 19:43:45.051  4083  4099 I bt_hci  : shut_down
,09-13 19:43:45.052  4083  4103 D bt_hwcfg: hw_epilog_process
09-13 19:43:45.053  4083  4103 I bt_vendor: low_power_mode_cb
,09-13 19:43:45.078  4083  4103 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 19:43:45.078  4083  4103 I bt_vendor: epilog_cb
09-13 19:43:45.079  4083  4103 I bt_hci  : epilog_finished_callback
,09-13 19:43:45.089  4083  4099 I bt_hci_h4: hal_close
,09-13 19:43:45.091  4083  4099 I bt_userial_vendor: device fd = 51 close
,09-13 19:43:45.215  4083  4096 D bt_stack_manager: event_shut_down_stack finished.
,09-13 19:43:45.216  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 19:43:45.222  4083  4095 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 19:43:45.223  4083  4083 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 19:43:45.224  4083  4083 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 19:43:45.225  4083  4083 D BtGatt.GattService: stop()
,09-13 19:43:45.225  4083  4083 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 19:43:45.230  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:45.230  4083  4083 V BluetoothAdapterState: isTurningOn()=false
,09-13 19:43:45.230  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:45.231  4083  4083 V BluetoothAdapterState: isBleTurningOff()=true
09-13 19:43:45.232  4083  4095 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 19:43:45.232  4083  4095 D BluetoothAdapterProperties: Setting state to 10
09-13 19:43:45.233  4083  4095 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 19:43:45.234  4083  4095 I BluetoothAdapterState: Entering OffState
09-13 19:43:45.236   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 19:43:45.266  4083  4083 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 19:43:45.266  4083  4083 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 19:43:45.267  4083  4096 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 19:43:45.277  4083  4096 D bt_stack_manager: event_clean_up_stack finished.
,09-13 19:43:45.277  4083  4083 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 19:43:45.282  4083  4083 I art     : System.exit called, status: 0
,09-13 19:43:45.282  4083  4083 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 19:43:45.344   873  2001 I ActivityManager: Process com.android.bluetooth (pid 4083) has died
,09-13 19:43:46.103   873  1308 D ConnectivityService: handlePromptUnvalidated 101
,09-13 19:43:47.761  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 19:43:47.762  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:50.769  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 19:43:50.770  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@341da61 added. We now have 6 listener(s)
09-13 19:43:50.770  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:50.774  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:50.775  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b99b986 added. We now have 7 listener(s)
,09-13 19:43:50.775  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:50.777  3800  3847 I System.out: IsBluetoothEnabled
,09-13 19:43:50.789  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:50.819   873   890 I ActivityManager: Start proc 4144:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 19:43:50.975  4144  4144 D AdapterServiceConfig: Adding HeadsetService
,09-13 19:43:50.975  4144  4144 D AdapterServiceConfig: Adding A2dpService
,09-13 19:43:50.976  4144  4144 D AdapterServiceConfig: Adding HidService
,09-13 19:43:50.976  4144  4144 D AdapterServiceConfig: Adding HealthService,
,09-13 19:43:50.976  4144  4144 D AdapterServiceConfig: Adding PanService
,09-13 19:43:50.976  4144  4144 D AdapterServiceConfig: Adding GattService
09-13 19:43:50.977  4144  4144 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 19:43:50.992   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@be6cee5:true
,09-13 19:43:50.993  4144  4144 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 19:43:51.001  4144  4144 I bt_bluedroid: init
,09-13 19:43:51.002  4144  4156 I BluetoothAdapterState: Entering OffState
,09-13 19:43:51.008  4144  4157 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 19:43:51.009  4144  4157 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 19:43:51.009  4144  4157 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 19:43:51.010  4144  4157 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 19:43:51.013  4144  4144 I bt_bluedroid: get_profile_interface socket
,09-13 19:43:51.017  4144  4144 I bt_bluedroid: get_profile_interface sdp
,09-13 19:43:51.018  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 19:43:51.023  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 19:43:51.025  4144  4155 I bt_bluedroid: config_hci_snoop_log
,09-13 19:43:51.028   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 19:43:51.042  4144  4156 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 19:43:51.042  4144  4156 D BluetoothAdapterProperties: Setting state to 14
,09-13 19:43:51.043  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 19:43:51.048  4144  4156 D BluetoothBondStateMachine: make
,09-13 19:43:51.054  4144  4161 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 19:43:51.064  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 19:43:51.066  4144  4144 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 19:43:51.076  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:51.077  4144  4144 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 19:43:51.079  4144  4144 D BtGatt.GattService: Received start request. Starting profile...
09-13 19:43:51.080  4144  4144 D BtGatt.GattService: start()
,09-13 19:43:51.080  4144  4144 I bt_bluedroid: get_profile_interface gatt
09-13 19:43:51.083  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:51.083  4144  4144 D BtGatt.AdvertiseManager: advertise manager created
,09-13 19:43:51.102  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:51.102  4144  4144 V BluetoothAdapterState: isTurningOn()=false
09-13 19:43:51.102  4144  4144 V BluetoothAdapterState: isBleTurningOn()=true
09-13 19:43:51.103  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:51.104  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 19:43:51.105  4144  4156 I bt_bluedroid: enable
09-13 19:43:51.106  4144  4157 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 19:43:51.107  4144  4157 I bt_hci  : start_up
,09-13 19:43:51.129  4144  4157 I bt_vendor: alloc value 0xb39e5189
,09-13 19:43:51.129  4144  4157 I bt_vendor: init
09-13 19:43:51.129  4144  4157 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 19:43:51.129  4144  4157 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 19:43:51.237  4144  4157 D bt_hci  : start_up starting async portion
,09-13 19:43:51.237  4144  4164 I bt_hci  : event_finish_startup
,09-13 19:43:51.238  4144  4164 I bt_hci_h4: hal_open
09-13 19:43:51.238  4144  4164 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 19:43:51.250  4144  4164 I bt_userial_vendor: device fd = 51 open
,09-13 19:43:51.281  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 19:43:51.312  4144  4164 D bt_hwcfg: Chipset BCM4354A2
,09-13 19:43:51.312  4144  4164 D bt_hwcfg: Target name = [BCM4354A2]
09-13 19:43:51.313  4144  4164 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 19:43:52.143  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 19:43:52.144  4144  4164 D bt_hwcfg: Settlement delay -- 100 ms
09-13 19:43:52.145  4144  4164 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 19:43:52.263  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 19:43:52.264  4144  4164 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 19:43:52.292  4144  4164 I bt_hwcfg: vendor lib fwcfg completed
,09-13 19:43:52.292  4144  4164 I bt_vendor: firmware callback
09-13 19:43:52.293  4144  4164 I bt_hci  : firmware_config_callback
,09-13 19:43:52.306  4144  4166 I bt_btu  : btu_task pending for preload complete event
,09-13 19:43:52.306  4144  4166 I bt_btu_task: Bluetooth chip preload is complete
09-13 19:43:52.306  4144  4166 I bt_btu  : btu_task received preload complete event
,09-13 19:43:52.318  4144  4166 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 19:43:52.318  4144  4166 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 19:43:52.319  4144  4166 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 19:43:52.319  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 19:43:52.319  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 19:43:52.320  4144  4166 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 19:43:52.320  4144  4166 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 19:43:52.320  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 19:43:52.320  4144  4166 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 19:43:52.320  4144  4166 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 19:43:52.321  4144  4166 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 19:43:52.321  4144  4166 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 19:43:52.321  4144  4166 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 19:43:52.322  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 19:43:52.322  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 19:43:52.475  4144  4166 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
09-13 19:43:52.475  4144  4166 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,09-13 19:43:52.484  4144  4160 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 19:43:52.487  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 19:43:52.488  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 19:43:52.491  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 19:43:52.494  4144  4160 D BluetoothAdapterProperties: Scan Mode:20
09-13 19:43:52.495  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 19:43:52.496  4144  4160 D bt_hci  : do_postload posting postload work item
09-13 19:43:52.496  4144  4164 I bt_hci  : event_postload
09-13 19:43:52.497  4144  4164 I bt_vendor: sco_config_cb
09-13 19:43:52.497  4144  4164 I bt_hci  : sco_config_callback postload finished.
09-13 19:43:52.500  4144  4160 D bt_bte_conf: Device ID record 1 : primary
,09-13 19:43:52.500  4144  4160 D bt_bte_conf:   vendorId            = 000f
09-13 19:43:52.500  4144  4160 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 19:43:52.501  4144  4160 D bt_bte_conf:   product             = 1200
09-13 19:43:52.501  4144  4160 D bt_bte_conf:   version             = 1436
09-13 19:43:52.501  4144  4160 D bt_bte_conf:   clientExecutableURL = 
09-13 19:43:52.501  4144  4160 D bt_bte_conf:   serviceDescription  = 
09-13 19:43:52.502  4144  4160 D bt_bte_conf:   documentationURL    = 
09-13 19:43:52.502  4144  4160 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 19:43:52.503  4144  4157 D bt_stack_manager: event_start_up_stack finished
09-13 19:43:52.504  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:52.504  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 19:43:52.505  4144  4156 D BluetoothAdapterProperties: Setting state to 15
,09-13 19:43:52.505  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 19:43:52.506  4144  4156 I BluetoothAdapterState: Entering BleOnState
09-13 19:43:52.507  4144  4164 I bt_vendor: low_power_mode_cb
,09-13 19:43:52.511  4144  4156 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 19:43:52.511  4144  4156 D BluetoothAdapterProperties: Setting state to 11
09-13 19:43:52.511  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 19:43:52.519  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:52.526  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:52.527  4144  4144 D HeadsetService: Received start request. Starting profile...
,09-13 19:43:52.530  4144  4144 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 19:43:52.531  4144  4144 D HeadsetStateMachine: make
,09-13 19:43:52.536  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 19:43:52.543  4144  4144 D HeadsetStateMachine: max_hf_connections = 1
,09-13 19:43:52.543  4144  4144 I bt_bluedroid: get_profile_interface handsfree
09-13 19:43:52.544  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 19:43:52.544  4144  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 19:43:52.549  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:52.550  4144  4144 D A2dpService: Received start request. Starting profile...
09-13 19:43:52.551  4144  4144 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 19:43:52.551  4144  4144 I bt_bluedroid: get_profile_interface avrcp
,09-13 19:43:52.559  4144  4144 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 19:43:52.559  4144  4144 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-13 19:43:52.560  4144  4144 D A2dpStateMachine: make
09-13 19:43:52.561  4144  4144 I bt_bluedroid: get_profile_interface a2dp
,09-13 19:43:52.562  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 19:43:52.564  4144  4175 D A2dpStateMachine: Enter Disconnected: -2
,09-13 19:43:52.567  4144  4144 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 19:43:52.568  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:52.569  4144  4144 D HidService: Received start request. Starting profile...
09-13 19:43:52.569  4144  4144 I bt_bluedroid: get_profile_interface hidhost
09-13 19:43:52.569  4144  4160 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
,09-13 19:43:52.570  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 19:43:52.570  4144  4144 D HidService: setHidService(): set to: null
,09-13 19:43:52.570  4144  4144 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 19:43:52.571  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:52.572  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 19:43:52.572  4144  4144 D HealthService: Received start request. Starting profile...
,09-13 19:43:52.573  4144  4144 I bt_bluedroid: get_profile_interface health
09-13 19:43:52.574  4144  4144 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 19:43:52.575  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
09-13 19:43:52.576  4144  4144 D PanService: Received start request. Starting profile...
,09-13 19:43:52.576  4144  4144 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 19:43:52.576  4144  4144 I bt_bluedroid: get_profile_interface pan
,09-13 19:43:52.577  4144  4160 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 19:43:52.580  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:52.581  4144  4144 D BluetoothMapService: Received start request. Starting profile...
09-13 19:43:52.581  4144  4144 D BluetoothMapService: start()
09-13 19:43:52.584  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 19:43:52.585  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 19:43:52.585  4144  4144 D BluetoothMapAppObserver: createReceiver()
,09-13 19:43:52.586  4144  4144 D BluetoothMapAppObserver: initObservers()
09-13 19:43:52.586  4144  4144 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 19:43:52.593  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:52.594  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:52.594  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:52.594  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 19:43:52.596  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-13 19:43:52.596  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:52.596  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:52.596  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:52.596  4144  4173 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 19:43:52.596  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isTurningOn()=true
,09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:52.597  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-13 19:43:52.598  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-13 19:43:52.599  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 19:43:52.599  4144  4156 D BluetoothAdapterProperties: ScanMode =  20
,09-13 19:43:52.599  4144  4156 D BluetoothAdapterProperties: State =  11
09-13 19:43:52.599  4144  4156 D BluetoothAdapterProperties: Setting state to 12
09-13 19:43:52.599  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 19:43:52.600  1364  1375 D BluetoothPan: onBluetoothStateChange on: true
09-13 19:43:52.601  4144  4160 D BluetoothAdapterProperties: Scan Mode:21
09-13 19:43:52.602  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 19:43:52.602  4144  4156 I BluetoothAdapterState: Entering OnState
,09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:52.604  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:52.607  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:52.607  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 19:43:52.607  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 19:43:52.608  1364  1364 D PanProfile: Bluetooth service connected
09-13 19:43:52.610  1364  2066 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 19:43:52.611  3854  3854 D BluetoothInputDevice: Proxy object connected
09-13 19:43:52.611  3854  3854 D HidProfile: Bluetooth service connected
09-13 19:43:52.612  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 19:43:52.612  3854  4133 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 19:43:52.613  4144  4144 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 19:43:52.614  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 19:43:52.615  3854  3865 D BluetoothPan: onBluetoothStateChange on: true
,09-13 19:43:52.618  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 19:43:52.619  1364  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 19:43:52.619  4144  4144 D ObexServerSockets: Succeed to create listening sockets 
,09-13 19:43:52.619  4144  4144 D ObexServerSockets0: startAccept()
09-13 19:43:52.619  4144  4144 D ObexServerSockets0: prepareForNewConnect()
,09-13 19:43:52.622  1364  1364 D BluetoothInputDevice: Proxy object connected
,09-13 19:43:52.622  1364  1364 D HidProfile: Bluetooth service connected
09-13 19:43:52.622   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 19:43:52.622  4144  4144 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 19:43:52.623  4144  4144 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 19:43:52.623   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:52.623  3854  4133 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 19:43:52.625  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 19:43:52.625  3854  3854 D PanProfile: Bluetooth service connected
09-13 19:43:52.625  4144  4180 D ObexServerSockets0: Accepting socket connection...
09-13 19:43:52.625  1978  2009 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:52.625   873   873 D BluetoothA2dp: Proxy object connected
09-13 19:43:52.626  4144  4181 D ObexServerSockets0: Accepting socket connection...
09-13 19:43:52.626  1364  2066 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 19:43:52.629  3854  3854 D BluetoothA2dp: Proxy object connected
09-13 19:43:52.629  1364  1364 D BluetoothA2dp: Proxy object connected
09-13 19:43:52.629  1364  1376 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 19:43:52.631   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 19:43:52.631  1364  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 19:43:52.632  3854  3865 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 19:43:52.633   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 19:43:52.633  3854  4133 D BluetoothMap: onBluetoothStateChange: up=true
09-13 19:43:52.633  1364  1364 D BluetoothMap: Proxy object connected
09-13 19:43:52.633  1364  1364 D MapProfile: Bluetooth service connected
09-13 19:43:52.633  1364  1364 D BluetoothMap: getConnectedDevices()
09-13 19:43:52.636  3854  3854 D BluetoothMap: Proxy object connected
,09-13 19:43:52.636  3854  3854 D MapProfile: Bluetooth service connected
09-13 19:43:52.636  3854  3854 D BluetoothMap: getConnectedDevices()
09-13 19:43:52.637  4144  4144 D BluetoothMapService: onReceive
09-13 19:43:52.637  4144  4144 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 19:43:52.637  4144  4144 D BluetoothMapService: STATE_ON
,09-13 19:43:52.638   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 19:43:52.640  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:52.644  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 19:43:52.653  1491  1491 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 19:43:52.654  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-13 19:43:52.664  1364  1364 D BluetoothPbap: Proxy object connected
,09-13 19:43:52.665  3854  3854 D BluetoothPbap: Proxy object connected
09-13 19:43:52.665  1364  1364 D PbapServerProfile: Bluetooth service connected
09-13 19:43:52.665  3854  3854 D PbapServerProfile: Bluetooth service connected
09-13 19:43:52.665  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 19:43:52.665  4144  4144 D ObexServerSockets0: prepareForNewConnect()
,09-13 19:43:52.675  4144  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 19:43:52.706  4144  4191 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 19:43:52.708  4144  4191 I BtOppRfcommListener: Accept thread started.
,09-13 19:43:52.726   873   873 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.726   873   873 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.726   873   873 D BluetoothHeadset: Proxy object connected
09-13 19:43:52.727  3854  3864 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.728  1978  2009 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.728  1978  1995 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.728  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-13 19:43:52.731  1364  1376 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.731   873   890 D BluetoothHeadset: Proxy object connected
09-13 19:43:52.731  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-13 19:43:52.732  1364  1375 D BluetoothHeadset: Proxy object connected
09-13 19:43:52.733  3854  4133 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.734   873   890 D BluetoothHeadset: Proxy object connected
,09-13 19:43:52.738  3854  3854 D HeadsetProfile: Bluetooth service connected
09-13 19:43:52.739  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:52.812  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:52.818  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:52.821  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 19:43:52.821  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9f0247 added. We now have 8 listener(s)
,09-13 19:43:52.822  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:52.829   873  1947 D WifiService: setWifiEnabled: false pid=3800, uid=10000
09-13 19:43:52.830   873  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 19:43:52.844  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:52.846   873  2146 D WifiService: setWifiEnabled: true pid=3800, uid=10000
09-13 19:43:52.846   873  2146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 19:43:52.859   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:52.879  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:52.886  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:52.896   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-13 19:43:52.897   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 19:43:52.898   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 19:43:52.899   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 19:43:52.900   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 19:43:52.900   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 19:43:52.900   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 19:43:52.915   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 19:43:52.915   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 19:43:52.916   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:52.968   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-13 19:43:52.969   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 19:43:52.973   873  1306 E native  : do suspend true
,09-13 19:43:52.994   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 19:43:53.007   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 19:43:53.013   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:53.870  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:53.877  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:53.890  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 19:43:53.892  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 19:43:53.897  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eca7464 Bundle[{}]
,09-13 19:43:53.898  3800  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 19:43:53.898  3800  3847 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 19:43:53.898  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 19:43:53.899  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 19:43:53.899  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 19:43:53.900  3800  3847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 19:43:53.904  3800  3847 I System.out: Running OutgoingSocketThread
,09-13 19:43:53.907  3800  4197 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 412)
,09-13 19:43:53.909  3800  4197 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44361
,09-13 19:43:53.909  3800  4197 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 19:43:54.333   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 19:43:54.470   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=18.25 delta 1000 -> 994
,09-13 19:43:54.471   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 19:43:54.471   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:54.492   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 19:43:54.552   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 19:43:54.556  1450  1450 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 19:43:54.907  3800  3847 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 413)
,09-13 19:43:54.908  3800  3847 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 413)
,09-13 19:43:54.917  3800  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,09-13 19:43:54.919  3800  3847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 19:43:54.919  3800  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 419)
,09-13 19:43:54.926  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 19:43:54.926  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fca74 added. We now have 2 listener(s)
,09-13 19:43:54.928  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:54.928  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 19:43:54.929  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:54.929  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:54.929  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@560bb9d added. We now have 9 listener(s)
09-13 19:43:54.929  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:54.929  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 19:43:54.932  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:54.938  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:54.940  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:54.940  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:54.941  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:54.941  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbf7be3 added. We now have 3 listener(s)
,09-13 19:43:54.942  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:54.943  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 19:43:54.943  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:54.943  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 19:43:54.944  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:54.944  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d919e0 added. We now have 10 listener(s)
09-13 19:43:54.944  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:54.944  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:54.946  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:54.946  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:54.946  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:54.946  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:54.946  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:54.946  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:54.946  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:54.947  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fca74 removed from the list
09-13 19:43:54.947  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:54.947  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@560bb9d removed from the list
09-13 19:43:54.947  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:54.947  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:54.947  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:54.947  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:54.949  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:54.949  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:54.949  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:54.949  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@560bb9d not in the list
09-13 19:43:54.949  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:54.949  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:54.950  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:54.950  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:54.950  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:54.950  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d919e0 removed from the list
09-13 19:43:54.950  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:54.950  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:54.951  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:54.951  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:54.951  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbf7be3 removed from the list
09-13 19:43:54.951  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:54.952  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a927499 added. We now have 2 listener(s)
09-13 19:43:54.953  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 19:43:54.953  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:54.953  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 19:43:54.954  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:54.954  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@738735e added. We now have 9 listener(s)
,09-13 19:43:54.954  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:54.954  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 19:43:54.957  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:54.967  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:54.969  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:54.969  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:54.970  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 19:43:54.970  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce5f40c added. We now have 3 listener(s)
,09-13 19:43:54.972  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:54.972  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 19:43:54.972  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:54.972  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:54.972  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8cc155 added. We now have 10 listener(s)
09-13 19:43:54.972  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:54.972  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:54.973  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:54.973  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 19:43:54.973  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:54.973  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:54.973  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:54.976  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:54.976  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:54.977  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:54.981  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 19:43:54.982  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:54.982  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 19:43:54.986  1450  1450 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 19:43:54.988  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 19:43:54.988  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 19:43:54.988  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 19:43:54.989  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:54.994  4144  4155 D BtGatt.GattService: registerClient() - UUID=a6c9ebbe-280c-438f-b892-9c8ea9fbec2a
09-13 19:43:54.995  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=a6c9ebbe-280c-438f-b892-9c8ea9fbec2a, clientIf=5
,09-13 19:43:54.996  3800  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 19:43:54.997  4144  4172 D BtGatt.GattService: start scan with filters
,09-13 19:43:55.002  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 19:43:55.002  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-13 19:43:55.002  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 19:43:55.002  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 19:43:55.002  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 19:43:55.004  4144  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@561c4b8
,09-13 19:43:55.007  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:55.007  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 19:43:55.007  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 19:43:55.009  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 19:43:55.010  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 19:43:55.010  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.011  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 19:43:55.013  3800  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 19:43:55.013  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:55.013  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 19:43:55.013  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.013  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 19:43:55.013  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 19:43:55.013  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 19:43:55.013  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 19:43:55.014  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 19:43:55.014  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 19:43:55.014  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 19:43:55.017  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:55.017  1450  1450 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 19:43:55.018  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 19:43:55.018  4144  4172 D BtGatt.GattService: stopScan() - queue size =1
09-13 19:43:55.020   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 19:43:55.022  4144  4154 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 19:43:55.024  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:55.024  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 19:43:55.024  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 19:43:55.025  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-13 19:43:55.025  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 19:43:55.027  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 19:43:55.027  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 19:43:55.027  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:55.027  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 19:43:55.027  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:55.028  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.028  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 19:43:55.028   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 19:43:55.028  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 19:43:55.029   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 19:43:55.029   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 19:43:55.029  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.031  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 19:43:55.031  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.031  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:55.039  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:55.039  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:55.039  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:55.039  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:55.039  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:55.039  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:55.039  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.039  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 19:43:55.039  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.040  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a927499 removed from the list
09-13 19:43:55.040  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.040  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@738735e removed from the list
,09-13 19:43:55.040  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:55.040  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.040  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.041  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 19:43:55.041  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.041  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.042  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.042  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.042  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-13 19:43:55.042  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@738735e not in the list
,09-13 19:43:55.043  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:55.044  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:55.044  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:55.044  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.045  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.047  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.047  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.048   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 19:43:55.049  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.050  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:55.050  3800  3847 D BluetoothLeScanner: could not find callback wrapper
09-13 19:43:55.050  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:55.050  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:55.050  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:55.050  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:55.050  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 19:43:55.050  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8cc155 removed from the list
,09-13 19:43:55.052  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:55.052  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:55.052  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:55.052  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.052  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.052  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.053  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce5f40c removed from the list,
09-13 19:43:55.053  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:55.053  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80cc60d added. We now have 2 listener(s)
,09-13 19:43:55.054  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 19:43:55.054  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.055  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.055  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:55.055  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:55.056  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:55.056  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.056  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:55.056  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd679c2 added. We now have 9 listener(s)
,09-13 19:43:55.056  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:55.056  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 19:43:55.058  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:55.058  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 19:43:55.060  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 19:43:55.061  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.062   371   872 D CommandListener: Setting iface cfg,
09-13 19:43:55.062   873  1306 D WifiStateMachine: Start Dhcp Watchdog 3
09-13 19:43:55.064  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:55.069  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 19:43:55.069  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.069  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
09-13 19:43:55.070   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:55.073  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:55.074  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:55.074  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.075  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:55.075  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 19:43:55.075  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:55.076  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:55.077  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:55.078  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:55.078  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd6bb10 added. We now have 3 listener(s)
09-13 19:43:55.079  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.079  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:55.079  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:55.080  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:55.080  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fccb609 added. We now have 10 listener(s)
09-13 19:43:55.080  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:55.080  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:55.080  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 19:43:55.080  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.081  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:55.081  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:55.081  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 19:43:55.081  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.081  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:55.084  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:55.084  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:55.087  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 19:43:55.087  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:55.087  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:55.090   873  4200 D DhcpClient: Receive thread started
,09-13 19:43:55.091  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 19:43:55.091  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 19:43:55.091  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 19:43:55.091  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:55.094  4144  4172 D BtGatt.GattService: registerClient() - UUID=3de25a25-aa0b-46ed-b83c-ca0ed8f52b0b
09-13 19:43:55.094  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=3de25a25-aa0b-46ed-b83c-ca0ed8f52b0b, clientIf=5
09-13 19:43:55.095  3800  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 19:43:55.095  4144  4183 D BtGatt.GattService: start scan with filters
,09-13 19:43:55.097  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-13 19:43:55.098  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 19:43:55.098  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 19:43:55.098  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 19:43:55.098  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 19:43:55.102  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 19:43:55.102  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:55.102  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 19:43:55.103  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 19:43:55.103  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.103  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 19:43:55.104  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 19:43:55.106  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:55.106  3800  3847 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 19:43:55.107  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:55.107  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:55.107  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 19:43:55.107  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:55.107  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.107  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
09-13 19:43:55.107  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 19:43:55.107  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:55.107  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.107  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-13 19:43:55.108  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.108  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80cc60d removed from the list
09-13 19:43:55.108  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:55.108  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd679c2 removed from the list
09-13 19:43:55.108  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:55.108  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.109  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.109  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
09-13 19:43:55.109  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.109  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.110  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd679c2 not in the list
09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 19:43:55.110  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 19:43:55.110  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 19:43:55.110  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 19:43:55.111  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:55.111  4144  4154 D BtGatt.GattService: stopScan() - queue size =1
09-13 19:43:55.112  4144  4155 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 19:43:55.112  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:55.112  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 19:43:55.112  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 19:43:55.112  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 19:43:55.112  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 19:43:55.113  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:55.113  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:55.113  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:55.113  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.114  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 19:43:55.114  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.114  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.114  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.115  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:55.115  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.115  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:55.117  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:55.117  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 19:43:55.118  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 19:43:55.118  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.120  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 19:43:55.122  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 19:43:55.122  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 19:43:55.122  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.122  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.122  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 19:43:55.122  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.123  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
09-13 19:43:55.124  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:55.124  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.124  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:55.126  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:55.126  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.126  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.127  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:55.127  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.127  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 19:43:55.128  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 19:43:55.128  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.128  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 19:43:55.128  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.128  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fccb609 removed from the list
09-13 19:43:55.128  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:55.128  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.129  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.129  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.129  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd6bb10 removed from the list
09-13 19:43:55.129  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 19:43:55.129  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8edc28 added. We now have 2 listener(s)
09-13 19:43:55.131  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 19:43:55.131  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.132  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.132  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 19:43:55.132  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 19:43:55.132  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:55.132  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d81d41 added. We now have 9 listener(s)
09-13 19:43:55.132  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:55.133  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 19:43:55.134  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:55.136  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 19:43:55.138  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 19:43:55.138  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:43:55.138  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:55.138  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3027 added. We now have 3 listener(s)
,09-13 19:43:55.139  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:55.139  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.140  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 19:43:55.140  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:55.140  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:55.140  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70992d4 added. We now have 10 listener(s)
09-13 19:43:55.140  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:55.140  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:55.140  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 19:43:55.140  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 19:43:55.140  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.140  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:55.141  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:55.142  3800  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 19:43:55.142  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 19:43:55.144  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 19:43:55.145  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:55.145  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 19:43:55.147  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 19:43:55.147  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 19:43:55.147  3800  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 19:43:55.147  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:55.149  4144  4172 D BtGatt.GattService: registerClient() - UUID=8fdd5ed1-7102-4477-b89d-74037c0e8756
,09-13 19:43:55.149  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=8fdd5ed1-7102-4477-b89d-74037c0e8756, clientIf=5
09-13 19:43:55.149  3800  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 19:43:55.150  4144  4154 D BtGatt.GattService: start scan with filters
,09-13 19:43:55.151  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 19:43:55.151  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 19:43:55.151  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 19:43:55.151  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 19:43:55.151  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-13 19:43:55.153  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 19:43:55.154  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 19:43:55.154  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 19:43:55.155  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 19:43:55.157  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 19:43:55.157  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.157  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 19:43:55.159  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 19:43:55.159  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:55.159  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:55.159  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:55.159  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.159  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 19:43:55.159  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.159  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8edc28 removed from the list
,09-13 19:43:55.159  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.159  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d81d41 removed from the list
09-13 19:43:55.159  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:43:55.159  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 19:43:55.160  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.160  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 19:43:55.160  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.160  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.161  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d81d41 not in the list
,09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 19:43:55.161  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 19:43:55.161  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 19:43:55.161  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 19:43:55.161  3800  3847 D BluetoothAdapter: STATE_ON
09-13 19:43:55.162  4144  4182 D BtGatt.GattService: stopScan() - queue size =1
,09-13 19:43:55.162  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 19:43:55.162  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.162  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
09-13 19:43:55.162  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 19:43:55.162  4144  4154 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 19:43:55.163  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 19:43:55.163  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 19:43:55.163  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 19:43:55.163  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 19:43:55.163  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 19:43:55.164  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 19:43:55.164  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 19:43:55.164  3800  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 19:43:55.164  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.164  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.165  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:55.165  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.165  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 19:43:55.166  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:55.166  3800  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 19:43:55.170  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 19:43:55.170  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 19:43:55.170  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 19:43:55.171  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 19:43:55.171  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.172  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 19:43:55.172  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.172  3800  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 19:43:55.172  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 19:43:55.172  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 19:43:55.174   873  1306 E native  : do suspend false
,09-13 19:43:55.175  3800  3800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 19:43:55.175  3800  3800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 19:43:55.175  3800  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.177  3800  3800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 19:43:55.177  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 19:43:55.177  3800  3847 D BluetoothAdapter: STATE_ON
,09-13 19:43:55.177  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 19:43:55.177  3800  3847 D BluetoothLeScanner: could not find callback wrapper
,09-13 19:43:55.177  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.177  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 19:43:55.177  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 19:43:55.177  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 19:43:55.178  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:55.178  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70992d4 removed from the list
09-13 19:43:55.178  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 19:43:55.178  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.178  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.178  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 19:43:55.178  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3027 removed from the list
09-13 19:43:55.179  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 19:43:55.179  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944686c added. We now have 2 listener(s)
,09-13 19:43:55.181  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.181  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:43:55.181  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 19:43:55.181  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 19:43:55.181  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9798e35 added. We now have 9 listener(s)
09-13 19:43:55.181  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 19:43:55.182  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 19:43:55.183  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 19:43:55.184  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:43:55.183  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 19:43:55.184  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
09-13 19:43:55.186   873  2065 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 19:43:55.186  3800  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 19:43:55.188  3800  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 19:43:55.188  3800  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 19:43:55.189  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 19:43:55.189  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4c3b added. We now have 3 listener(s)
09-13 19:43:55.189  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 19:43:55.190  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:43:55.191  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 19:43:55.191  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 19:43:55.191  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-13 19:43:55.191  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:43:55.191  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 19:43:55.191  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.191  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e459f58 added. We now have 10 listener(s)
09-13 19:43:55.191  3800  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:43:55.191  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 19:43:55.192  3800  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 19:43:55.192  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:55.192  3800  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 19:43:55.192  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:55.192  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.192  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 19:43:55.192  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.192  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944686c removed from the list
09-13 19:43:55.192  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:55.192  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9798e35 removed from the list
09-13 19:43:55.192  3800  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 19:43:55.192  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.193  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.193  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.194  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.194  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 19:43:55.194  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 19:43:55.194  3800  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9798e35 not in the list
09-13 19:43:55.194  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:43:55.194  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:43:55.195  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 19:43:55.195  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 19:43:55.195  3800  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:43:55.195  3800  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e459f58 removed from the list
09-13 19:43:55.195  3800  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:43:55.196  3800  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 19:43:55.196  3800  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 19:43:55.196  3800  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:43:55.196  3800  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4c3b removed from the list
,09-13 19:43:55.196  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 19:43:55.196  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything,
09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 19:43:55.197  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 19:43:55.203  3800  4201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: My test thread name)
,09-13 19:43:55.203  3800  4201 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: My test thread name)
09-13 19:43:55.203  3800  4201 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 19:43:55.204   873  4200 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
09-13 19:43:55.204   873  2065 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
09-13 19:43:55.205  3800  4202 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: My test thread name)
,09-13 19:43:55.205  3800  4202 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: My test thread name)
,09-13 19:43:55.205  3800  4202 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 19:43:55.205   873  2065 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 19:43:55.207  3800  3847 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 19:43:55.207  3800  3847 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 19:43:55.207  3800  3847 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-13 19:43:55.207  3800  3847 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 19:43:55.207  3800  3847 D com.test.thalitest.ThaliTestRunner: Total duration: 22833 ms
,09-13 19:43:55.209  3800  3847 I jxcore-log: Total number of executed tests:  80
09-13 19:43:55.209  3800  3847 I jxcore-log: 
09-13 19:43:55.209  3800  3847 I jxcore-log: Number of passed tests:  80
09-13 19:43:55.209  3800  3847 I jxcore-log: 
09-13 19:43:55.209  3800  3847 I jxcore-log: Number of failed tests:  0
09-13 19:43:55.209  3800  3847 I jxcore-log: 
09-13 19:43:55.209  3800  3847 I jxcore-log: Number of ignored tests:  0
09-13 19:43:55.209  3800  3847 I jxcore-log: 
09-13 19:43:55.209  3800  3847 I jxcore-log: Total duration:  22833
09-13 19:43:55.209  3800  3847 I jxcore-log: 
,09-13 19:43:55.211  3800  3847 I jxcore-log: Unit Test app is loaded
09-13 19:43:55.211  3800  3847 I jxcore-log: 
,09-13 19:43:55.219  3800  3800 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,09-13 19:43:55.220   873  4200 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 19:43:55.220   873  2065 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-13 19:43:55.221   371   872 D CommandListener: Setting iface cfg
,09-13 19:43:55.222  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.222  3800  3847 I jxcore-log: 
09-13 19:43:55.224   873  2065 D DhcpClient: Scheduling renewal in 86399s
09-13 19:43:55.225  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.225  3800  3847 I jxcore-log: 
,09-13 19:43:55.225   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 19:43:55.226  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.226  3800  3847 I jxcore-log: 
09-13 19:43:55.226   873  1306 E native  : do suspend true
09-13 19:43:55.226  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.226  3800  3847 I jxcore-log: 
09-13 19:43:55.227  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.227  3800  3847 I jxcore-log: 
,09-13 19:43:55.228  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.228  3800  3847 I jxcore-log: 
,09-13 19:43:55.229  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.229  3800  3847 I jxcore-log: 
,09-13 19:43:55.231  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.231  3800  3847 I jxcore-log: 
,09-13 19:43:55.231  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.231  3800  3847 I jxcore-log: 
,09-13 19:43:55.232  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.232  3800  3847 I jxcore-log: 
,09-13 19:43:55.232  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.232  3800  3847 I jxcore-log: 
,09-13 19:43:55.233  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 19:43:55.233  3800  3847 I jxcore-log: 
09-13 19:43:55.234  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.234  3800  3847 I jxcore-log: 
,09-13 19:43:55.234  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.234  3800  3847 I jxcore-log: 
09-13 19:43:55.235  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.235  3800  3847 I jxcore-log: 
,09-13 19:43:55.235  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.235  3800  3847 I jxcore-log: 
09-13 19:43:55.236  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.236  3800  3847 I jxcore-log: 
,09-13 19:43:55.236  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.236  3800  3847 I jxcore-log: 
,09-13 19:43:55.237  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.237  3800  3847 I jxcore-log: 
09-13 19:43:55.237  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.237  3800  3847 I jxcore-log: 
,09-13 19:43:55.237  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.237  3800  3847 I jxcore-log: 
,09-13 19:43:55.238  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.238  3800  3847 I jxcore-log: 
09-13 19:43:55.238   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-13 19:43:55.239  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.239  3800  3847 I jxcore-log: 
,09-13 19:43:55.239   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-13 19:43:55.239  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.239  3800  3847 I jxcore-log: 
09-13 19:43:55.239   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 19:43:55.240   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 19:43:55.242   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 19:43:55.244  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.244  3800  3847 I jxcore-log: 
,09-13 19:43:55.245  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 19:43:55.245  3800  3847 I jxcore-log: 
09-13 19:43:55.246  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.246  3800  3847 I jxcore-log: 
09-13 19:43:55.246  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.246  3800  3847 I jxcore-log: 
09-13 19:43:55.247  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.247  3800  3847 I jxcore-log: 
,09-13 19:43:55.247  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.247  3800  3847 I jxcore-log: 
,09-13 19:43:55.248  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.248  3800  3847 I jxcore-log: 
09-13 19:43:55.248  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.248  3800  3847 I jxcore-log: 
09-13 19:43:55.249  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 19:43:55.249  3800  3847 I jxcore-log: 
09-13 19:43:55.251  3800  3847 I jxcore-log: My device name is: motorola-Nexus 6
09-13 19:43:55.251  3800  3847 I jxcore-log: 
,09-13 19:43:55.281   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 19:43:55.281   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 19:43:55.283   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 19:43:55.285   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 19:43:55.290   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 19:43:55.310   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 19:43:55.315   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-13 19:43:55.315   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-13 19:43:55.315   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 19:43:55.315   873  1308 D ConnectivityService:    accepting network in place of null
09-13 19:43:55.315   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 19:43:55.316   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 19:43:55.317   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 19:43:55.325   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=296026, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 19:43:55.361   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:55.398   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 19:43:55.399   873  4198 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 19:43:55.402   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 19:43:55.402   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 19:43:55.404   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 19:43:55.405   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:43:55.435  3800  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 19:43:55.436  3800  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 19:43:55.451  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 19:43:55.454  1709  1709 D SystemUpdateService: onCreate
,09-13 19:43:55.457  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 19:43:55.460  3702  4210 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 19:43:55.470   873  4198 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 17:43:55 GMT], X-Android-Received-Millis=[1473788635470], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473788635447]}
,09-13 19:43:55.472   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 19:43:55.473   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 19:43:55.473   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 19:43:55.473   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
,09-13 19:43:55.483  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 19:43:55.486  1709  2514 I iu.UploadsManager: num queued entries: 0
,09-13 19:43:55.486  1709  2514 I iu.UploadsManager: num updated entries: 0
,09-13 19:43:55.489  1709  4212 I SystemUpdateService: active receiver: enabled
,09-13 19:43:55.497  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 19:43:55.499  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 19:43:55.500  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 19:43:55.504  3911  3911 D SprintDMHelper: simOperator: 
,09-13 19:43:55.504  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 19:43:55.505  1709  4215 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 19:43:55.505  1709  4215 W BaseAppContext: Using Auth Proxy for data requests.
09-13 19:43:55.507  1709  4215 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 19:43:55.535  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:43:55.543  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:43:55.553  1709  4212 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 19:43:55.558  3800  3800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 19:43:55.559  1709  2514 I iu.SyncManager: NEXT; no task
,09-13 19:43:55.567  1709  4212 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 19:43:55.567  1709  4212 I SystemUpdateService: now status is 0 (complete)
,09-13 19:43:55.567  1709  4212 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 19:43:55.568  1709  4212 I SystemUpdateService: file has been verified
,09-13 19:43:55.568  1709  4212 I SystemUpdateService: OTA package size = 12249756
,09-13 19:43:55.589  1709  4212 I SystemUpdateService: showing system update notification
,09-13 19:43:55.602  3702  4222 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 19:43:55.629  3800  3800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 19:43:55.646  1491  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:43:55.646  1491  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 19:43:55.647  1491  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:43:55.647  1491  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:43:55.647  1491  1502 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 19:43:55.647  1491  1502 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 19:43:55.647  1491  1502 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:43:55.647  1491  1502 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 19:43:55.655  2140  4218 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 19:43:55.677  3800  3800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 19:43:55.688  1709  1709 D SystemUpdateService: onDestroy
,09-13 19:43:55.690  1491  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:43:55.690  1491  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 19:43:55.690  1491  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:43:55.690  1491  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:43:55.704  3702  4222 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 19:43:55.705  3702  4210 E BooksSync: Soft error
09-13 19:43:55.705  3702  4210 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:43:55.705  3702  4210 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 19:43:55.705  3702  4210 E BooksSync: Sync error
09-13 19:43:55.705  3702  4210 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:43:55.705  3702  4210 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 19:43:55.707  3702  4210 I BooksSync: Finished books sync
,09-13 19:43:55.712   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288205, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:43:55.712  1709  4215 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-13 19:43:55.785  3800  3847 E jxcore  : Error!: Cannot find module './CoordinatedClient'
09-13 19:43:55.785  3800  3847 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js","_functionName":"","_lineNumber":"12","_columnNumber":"25","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js:12:25"}]
,09-13 19:43:55.789  3800  3847 E jxcore-log: Error: 
,09-13 19:43:55.789  3800  3847 E jxcore-log: Cannot find module './CoordinatedClient'
09-13 19:43:55.789  3800  3847 E jxcore-log:  (module.js 802:9)
09-13 19:43:55.789  3800  3847 E jxcore-log: 
09-13 19:43:55.790  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 19:43:55.790  3800  3847 I jxcore-log: 
09-13 19:43:55.791  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 19:43:55.791  3800  3847 I jxcore-log: 
09-13 19:43:55.791  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 19:43:55.791  3800  3847 I jxcore-log: 
09-13 19:43:55.792  3800  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 19:43:55.792  3800  3847 I jxcore-log: 
,09-13 19:43:58.031  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 19:43:58.031  3800  3847 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-13 19:43:58.157  3800  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 19:43:58.158  3800  3847 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-13 19:44:03.323   873  1308 D ConnectivityService: handlePromptUnvalidated 102
,09-13 19:44:15.472  1893  1948 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-13 19:44:15.473  1893  1948 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-13 19:44:15.527  1491  1491 I ConfigService: onCreate
,09-13 19:44:20.602  1491  1491 I ConfigService: onDestroy
,09-13 19:44:26.040  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:26.043  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:26.081  1491  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 19:44:26.082  1491  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:44:26.082  1491  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:26.082  1491  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:26.106  2986  4229 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 19:44:26.106  2986  4229 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at blb.a(PG:3937)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at czp.a(PG:18188)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:26.106  2986  4229 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	... 12 more
09-13 19:44:26.106  2986  4229 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at fal.a(PG:38)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:44:26.106  2986  4229 E HttpOperation: 	... 14 more
,09-13 19:44:26.153  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:44:26.153  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:44:26.153  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:26.153  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:26.187  2986  4229 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 19:44:26.187  2986  4229 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at hec.a(PG:42)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at hee.a(PG:102)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at czr.a(PG:65)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at kka.a(PG:108)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at czp.a(PG:19176)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:26.187  2986  4229 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	... 15 more
09-13 19:44:26.187  2986  4229 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at fal.a(PG:38)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:44:26.187  2986  4229 E HttpOperation: 	... 17 more
09-13 19:44:26.187  2986  4229 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 19:44:26.187  2986  4229 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at hec.a(PG:42)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at hee.a(PG:102)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at czr.a(PG:65)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at kka.a(PG:108)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	... 15 more
09-13 19:44:26.187  2986  4229 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at fal.a(PG:38)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 19:44:26.187  2986  4229 E ExperimentLoader: 	... 17 more
,09-13 19:44:26.402   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 321311, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:44:39.369   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340070, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:44:41.427  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:41.441  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:41.446  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:41.503  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 19:44:41.504  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 19:44:41.504  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:41.504  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:41.543  1491  3733 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 19:44:41.543  1491  3733 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 19:44:41.556  3496  3533 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 19:44:41.556  3496  3533 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 19:44:41.556  3496  3533 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 19:44:41.556  3496  3533 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 19:44:41.556  3496  3533 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 19:44:41.556  3496  3533 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 19:44:41.556  3496  3533 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 19:44:46.616   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 19:44:56.545  3702  4235 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 19:44:56.586  3702  4236 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 19:44:56.598  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.601  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.632  1491  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:44:56.632  1491  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 19:44:56.632  1491  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:56.632  1491  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:56.668  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.671  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.703  1491  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:44:56.703  1491  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 19:44:56.703  1491  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:56.704  1491  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:56.725  3702  4236 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 19:44:56.727  3702  4235 E BooksSync: Soft error
09-13 19:44:56.727  3702  4235 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:44:56.727  3702  4235 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 19:44:56.727  3702  4235 E BooksSync: Sync error
09-13 19:44:56.727  3702  4235 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:44:56.727  3702  4235 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 19:44:56.727  3702  4235 I BooksSync: Finished books sync
,09-13 19:44:56.738   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 328318, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:44:56.914  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.920  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:44:56.994  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:44:56.994  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:44:56.994  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:44:56.994  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:57.029  2986  4238 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 19:44:57.029  2986  4238 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at blb.a(PG:3937)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at czp.a(PG:18188)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:57.029  2986  4238 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	... 12 more
09-13 19:44:57.029  2986  4238 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at fal.a(PG:38)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:44:57.029  2986  4238 E HttpOperation: 	... 14 more
,09-13 19:44:57.118  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:44:57.118  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:44:57.118  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:44:57.119  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:44:57.131  2986  4238 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 19:44:57.131  2986  4238 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at hec.a(PG:42)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at hee.a(PG:102)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at czr.a(PG:65)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at kka.a(PG:108)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at czp.a(PG:19176)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:57.131  2986  4238 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	... 15 more
09-13 19:44:57.131  2986  4238 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at fal.a(PG:38)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:44:57.131  2986  4238 E HttpOperation: 	... 17 more
,09-13 19:44:57.131  2986  4238 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 19:44:57.131  2986  4238 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at hec.a(PG:42)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at hee.a(PG:102)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at czr.a(PG:65)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at kka.a(PG:108)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	... 15 more
09-13 19:44:57.131  2986  4238 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at fal.a(PG:38)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 19:44:57.131  2986  4238 E ExperimentLoader: 	... 17 more
,09-13 19:44:57.297   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 357172, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:45:25.483   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:45:48.336   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 19:45:57.734  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:45:57.737  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:45:57.771  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:45:57.771  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:45:57.771  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:45:57.771  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:45:57.787  2986  4243 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 19:45:57.787  2986  4243 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at blb.a(PG:3937)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at czp.a(PG:18188)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:45:57.787  2986  4243 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	... 12 more
09-13 19:45:57.787  2986  4243 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at fal.a(PG:38)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:45:57.787  2986  4243 E HttpOperation: 	... 14 more
,09-13 19:45:57.891  1491  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:45:57.892  1491  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:45:57.892  1491  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:45:57.892  1491  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:45:57.908  2986  4243 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 19:45:57.908  2986  4243 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at hec.a(PG:42)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at hee.a(PG:102)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at czr.a(PG:65)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at kka.a(PG:108)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at czp.a(PG:19176)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:45:57.908  2986  4243 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	... 15 more
09-13 19:45:57.908  2986  4243 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at fal.a(PG:38)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:45:57.908  2986  4243 E HttpOperation: 	... 17 more
09-13 19:45:57.909  2986  4243 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 19:45:57.909  2986  4243 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at hec.a(PG:42)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at hee.a(PG:102)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at czr.a(PG:65)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at kka.a(PG:108)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	... 15 more
09-13 19:45:57.909  2986  4243 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at fal.a(PG:38)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 19:45:57.909  2986  4243 E ExperimentLoader: 	... 17 more
,09-13 19:45:58.060   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 418136, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:46:28.191  3702  4246 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 19:46:28.230  3702  4247 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 19:46:28.245  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:46:28.250  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:46:28.291  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:46:28.292  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 19:46:28.292  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:46:28.292  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:46:28.334  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:46:28.337  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:46:28.371  1491  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:46:28.371  1491  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 19:46:28.372  1491  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:46:28.372  1491  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:46:28.397  3702  4247 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 19:46:28.398  3702  4246 E BooksSync: Soft error
09-13 19:46:28.398  3702  4246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:46:28.398  3702  4246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 19:46:28.399  3702  4246 E BooksSync: Sync error
09-13 19:46:28.399  3702  4246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:46:28.399  3702  4246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 19:46:28.399  3702  4246 I BooksSync: Finished books sync
,09-13 19:46:28.407   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 421250, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:46:31.829   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:47:26.285  3010  4250 V KeepSync: Connecting to GoogleApiClient
09-13 19:47:26.286   873  2274 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 19:47:26.348  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:47:26.350  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:47:26.387  1491  2965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-13 19:47:26.387  1491  2965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 19:47:26.388  1491  2965 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:47:26.388  1491  2965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:47:26.416  1709  4251 V BaseAuthAsyncOperation: access token request failed
,09-13 19:47:26.418  3010  4250 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 19:47:26.481  1491  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 19:47:26.481  1491  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 19:47:26.481  1491  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:47:26.481  1491  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:47:26.505  3010  4250 E KeepSync: IOException
09-13 19:47:26.505  3010  4250 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 19:47:26.505  3010  4250 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:47:26.505  3010  4250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 19:47:26.505  3010  4250 E KeepSync: 	... 10 more
,09-13 19:47:26.505  3010  4250 W KeepSync: Sync result 2
,09-13 19:47:26.517   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 506822, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:47:43.416   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=524117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 19:47:57.826  1491  2175 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 19:47:58.646  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:47:58.650  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:47:58.706  1491  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:47:58.706  1491  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 19:47:58.706  1491  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:47:58.707  1491  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:47:58.746  2986  4254 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 19:47:58.746  2986  4254 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at blb.a(PG:3937)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at czp.a(PG:18188)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:47:58.746  2986  4254 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	... 12 more
09-13 19:47:58.746  2986  4254 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at fal.a(PG:38)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:47:58.746  2986  4254 E HttpOperation: 	... 14 more
,09-13 19:47:58.842  1491  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 19:47:58.843  1491  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 19:47:58.843  1491  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:47:58.843  1491  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:47:58.866  2986  4254 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 19:47:58.866  2986  4254 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jdm.a(PG:82)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jcs.o(PG:406)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jcn.a(PG:1379)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jcs.i(PG:143)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at hec.a(PG:42)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at hee.a(PG:102)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at czr.a(PG:65)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at kka.a(PG:108)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at czp.a(PG:19176)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at czp.a(PG:9081)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at czq.run(PG:1686)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:47:58.866  2986  4254 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jdj.a(PG:4091)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jdj.a(PG:1125)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jdm.a(PG:77)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	... 15 more
09-13 19:47:58.866  2986  4254 E HttpOperation: Caused by: faj: BadAuthentication
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at fal.a(PG:38)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	at jdj.a(PG:4089)
09-13 19:47:58.866  2986  4254 E HttpOperation: 	... 17 more
09-13 19:47:58.866  2986  4254 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 19:47:58.866  2986  4254 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at hec.a(PG:42)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at hee.a(PG:102)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at czr.a(PG:65)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at kka.a(PG:108)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	... 15 more
09-13 19:47:58.866  2986  4254 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at fal.a(PG:38)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 19:47:58.866  2986  4254 E ExperimentLoader: 	... 17 more
,09-13 19:47:58.993   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 539038, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:48:27.029   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=567730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:48:29.162  3010  4257 V KeepSync: Connecting to GoogleApiClient
,09-13 19:48:29.163   873  1383 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 19:48:29.233  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:29.237  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:29.296  1491  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 19:48:29.296  1491  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 19:48:29.297  1491  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:48:29.297  1491  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:48:29.347  1709  4258 V BaseAuthAsyncOperation: access token request failed
,09-13 19:48:29.350  3010  4257 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 19:48:29.441  1491  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 19:48:29.441  1491  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 19:48:29.441  1491  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:48:29.441  1491  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:48:29.469  3010  4257 E KeepSync: IOException
09-13 19:48:29.469  3010  4257 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 19:48:29.469  3010  4257 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 19:48:29.469  3010  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 19:48:29.469  3010  4257 E KeepSync: 	... 10 more
,09-13 19:48:29.469  3010  4257 W KeepSync: Sync result 2
,09-13 19:48:29.480   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 539796, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:48:47.163   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 19:48:59.690  3702  4261 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 19:48:59.712  3702  4262 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 19:48:59.720  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:59.726  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:59.786  1491  3733 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:48:59.787  1491  3733 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 19:48:59.787  1491  3733 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 19:48:59.787  1491  3733 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:48:59.828  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:59.830  1491  1491 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 19:48:59.849  1491  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 19:48:59.849  1491  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 19:48:59.849  1491  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 19:48:59.849  1491  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 19:48:59.865  3702  4262 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 19:48:59.866  3702  4261 E BooksSync: Soft error
09-13 19:48:59.866  3702  4261 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:48:59.866  3702  4261 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 19:48:59.866  3702  4261 E BooksSync: Sync error
09-13 19:48:59.866  3702  4261 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 19:48:59.866  3702  4261 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 19:48:59.866  3702  4261 I BooksSync: Finished books sync
,09-13 19:48:59.877   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 576729, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 19:49:30.816   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=631517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:49:46.976   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 19:50:30.549   873  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=691250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 19:59:17.977   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-13 20:06:45.876  4316  4316 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 20:06:45.881  4316  4316 D AndroidRuntime: CheckJNI is OFF
09-13 20:06:45.917  4316  4316 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 20:06:45.962  4316  4316 I Radio-JNI: register_android_hardware_Radio DONE
09-13 20:06:45.983  4316  4316 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 20:06:45.995   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-13 20:06:45.996   873   886 I ActivityManager: Killing 3800:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-13 20:06:46.108   873   896 W PackageSettings: Skipping PackageSetting{7cc6c25 com.example.hello/10273} due to missing metadata
09-13 20:06:46.126   873   883 I WindowState: WIN DEATH: Window{7b2974 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 20:06:46.127   873  1307 D WifiService: Client connection lost with reason: 4
09-13 20:06:46.128   873  1947 D GraphicsStats: Buffer count: 2
09-13 20:06:46.143   873   896 I art     : Starting a blocking GC Explicit
09-13 20:06:46.174   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 20:06:46.174   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 20:06:46.175   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-13 20:06:46.175   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 20:06:46.175   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.175   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.175   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.175   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 20:06:46.175   873   886 I ActivityManager:   Force finishing activity ActivityRecord{6a3c8b9 u0 com.test.thalitest/.MainActivity t4}
09-13 20:06:46.183   873  1383 W ActivityManager: Spurious death for ProcessRecord{28f163a 0:com.test.thalitest/u0a0}, curProc for 3800: null
09-13 20:06:46.197   873   896 I art     : Explicit concurrent mark sweep GC freed 34706(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/43MB, paused 776us total 53.439ms
09-13 20:06:46.217   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 20:06:46.219  4316  4316 I art     : System.exit called, status: 0
09-13 20:06:46.219  4316  4316 I AndroidRuntime: VM exiting with result code 0.
09-13 20:06:46.271   873   896 I ActivityManager: Start proc 4329:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-13 20:06:46.271   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-13 20:06:46.285   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-13 20:06:46.290  1893  1893 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 20:06:46.294   873  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 20:06:46.299  4144  4144 D BluetoothMapAppObserver: onReceive
09-13 20:06:46.299  4144  4144 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 20:06:46.303  1854  2167 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 20:06:46.309  1893  4342 I Keyboard.Facilitator.DecoderInitializer: run()
09-13 20:06:46.311  3590  3590 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-13 20:06:46.335  1893  4342 I Decoder : createOrResetDecoder
09-13 20:06:46.357  1978  1978 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 20:06:46.364   873  3132 I ActivityManager: Start proc 4344:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-13 20:06:46.374   873  1304 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-13 20:06:46.377   873  1708 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3800 uid 10000
09-13 20:06:46.379   873  1707 I ActivityManager: Killing 3427:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
09-13 20:06:46.385  1893  1893 I Keyboard.Facilitator: onFinishInput()
09-13 20:06:46.391   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 20:06:46.454  1491  1491 I ConfigService: onCreate
09-13 20:06:46.464  4344  4344 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 20:06:46.471  1491  4357 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 20:06:46.472  1491  4357 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-13 20:06:46.473  1491  4357 W SQLiteOpenHelper: Opened config.db in read-only mode
09-13 20:06:46.493  1893  4342 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-13 20:06:46.518  1997  2072 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 20:06:46.522   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 20:06:46.526   873   885 E PackageManager: Failed to write settings, restoring backup
09-13 20:06:46.526   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 20:06:46.526   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 20:06:46.526   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 20:06:46.526   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 20:06:46.526   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 20:06:46.526   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.526   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.526   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.532   873  1707 I ActivityManager: Start proc 4362:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-13 20:06:46.532  1997  2072 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 20:06:46.532  1997  2072 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1997
09-13 20:06:46.532  1997  2072 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.532  1997  2072 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.532   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-13 20:06:46.532   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 20:06:46.532   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 20:06:46.532   873   886 E DropBoxManagerService: 	... 13 more
09-13 20:06:46.535   873  2146 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 20:06:46.538   873  4368 E DropBoxManagerService: Can't write: system_app_crash
09-13 20:06:46.538   873  4368 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 20:06:46.538   873  4368 E DropBoxManagerService: 	... 5 more
09-13 20:06:46.539  1997  2072 I Process : Sending signal. PID: 1997 SIG: 9
09-13 20:06:46.545  1893  4342 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-13 20:06:46.547  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 20:06:46.547  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-13 20:06:46.550  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-13 20:06:46.550  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 20:06:46.551  1893  4342 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 20:06:46.552  1893  4342 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 20:06:46.552  1893  4342 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-13 20:06:46.589  4344  4344 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.597  4344  4359 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.600  4344  4376 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.604  4344  4359 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 20:06:46.607   873  2028 I ActivityManager: Start proc 4377:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-13 20:06:46.610   873  1947 D GraphicsStats: Buffer count: 1
09-13 20:06:46.610   873  1708 I WindowState: WIN DEATH: Window{466ff8e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 20:06:46.621   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1997) has died
09-13 20:06:46.621   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 20:06:46.623   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-13 20:06:46.640   873   886 I ActivityManager: Start proc 4390:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 20:06:46.657  4377  4377 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 20:06:46.688  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 20:06:46.688  4390  4390 D AndroidRuntime: Shutting down VM
09-13 20:06:46.694  1491  1491 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-13 20:06:46.695  1491  1491 D AndroidRuntime: Shutting down VM
09-13 20:06:46.695  4390  4390 E AndroidRuntime: FATAL EXCEPTION: main
09-13 20:06:46.695  4390  4390 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4390
09-13 20:06:46.695  4390  4390 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 20:06:46.695  4390  4390 E AndroidRuntime: 	... 10 more
09-13 20:06:46.695  1491  1491 E AndroidRuntime: FATAL EXCEPTION: main
09-13 20:06:46.695  1491  1491 E AndroidRuntime: Process: com.google.process.gapps, PID: 1491
09-13 20:06:46.695  1491  1491 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 20:06:46.695  1491  1491 E AndroidRuntime: 	... 8 more

```
