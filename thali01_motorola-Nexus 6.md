#### Test 8484329600bfcdc_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 17:22:21.798   873  1866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 17:22:22.983  3844  3844 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 17:22:22.988  3844  3844 D AndroidRuntime: CheckJNI is OFF
09-12 17:22:23.031  3844  3844 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 17:22:23.081  3844  3844 I Radio-JNI: register_android_hardware_Radio DONE
09-12 17:22:23.103  3844  3844 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 17:22:23.107   873  2016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 17:22:23.164   873  2016 I ActivityManager: Start proc 3853:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 17:22:23.171  3844  3844 D AndroidRuntime: Shutting down VM
09-12 17:22:23.261  3853  3853 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 17:22:23.287  3853  3853 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 17:22:23.294  3853  3853 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7037-7040)
09-12 17:22:23.294  3853  3853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 17:22:23.310  3853  3853 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fa96e20}
09-12 17:22:23.311  3853  3853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 17:22:23.311  3853  3853 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 17:22:23.318  3853  3853 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 17:22:23.319  3853  3853 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 17:22:23.338  3853  3853 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 17:22:23.349  3853  3853 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 17:22:23.349  3853  3853 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 17:22:23.349  3853  3853 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 17:22:23.349  3853  3853 I Adreno  : Build Date                       : 10/20/15
09-12 17:22:23.349  3853  3853 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 17:22:23.349  3853  3853 I Adreno  : Local Branch                     : M14
09-12 17:22:23.349  3853  3853 I Adreno  : Remote Branch                    : 
09-12 17:22:23.349  3853  3853 I Adreno  : Remote Branch                    : 
09-12 17:22:23.349  3853  3853 I Adreno  : Reconstruct Branch               : 
,09-12 17:22:23.399   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12005e7:true
,09-12 17:22:23.491  3853  3853 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 17:22:23.506  3853  3853 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 17:22:23.584  3853  3891 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 17:22:23.603  3853  3877 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 17:22:23.633  3853  3891 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 17:22:23.653  1903  1903 I Keyboard.Facilitator: onFinishInput()
,09-12 17:22:23.688   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +476ms (total +563ms)
,09-12 17:22:23.728  3853  3853 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3853
,09-12 17:22:23.811  3853  3853 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 17:22:23.977  3853  3893 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1678313168
,09-12 17:22:23.988  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 17:22:23.988  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 17:22:23.988  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 17:22:23.988  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 17:22:23.988  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 17:22:23.989  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed50037 added. We now have 1 listener(s)
,09-12 17:22:23.993  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 17:22:23.995  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 17:22:23.996  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 17:22:23.996  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 17:22:24.002  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa0b2c2 added. We now have 1 listener(s)
09-12 17:22:24.002  3853  3893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:22:24.007   873  1314 D WifiService: New client listening to asynchronous messages
,09-12 17:22:24.009  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:22:24.009  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 17:22:24.009  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 17:22:24.009  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 17:22:24.009  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 17:22:24.011  3853  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:24.011  3853  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 17:22:24.019  3853  3893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:24.019  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:22:24.019  3853  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 17:22:24.019  3853  3893 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 17:22:24.020  3853  3893 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 17:22:24.025  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:24.033  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:24.044  3853  3853 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 17:22:24.918  3853  3899 W jxcore-log: Initializing JXcore engine
,09-12 17:22:24.918  3853  3899 W jxcore-log: JXcore engine is ready
,09-12 17:22:24.970  3899  3899 W Thread-328: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 17:22:24.970  3899  3899 W Thread-328: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11927]" dev="sockfs" ino=11927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 17:22:24.970  3899  3899 W Thread-328: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 17:22:24.970  3899  3899 W Thread-328: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23467]" dev="sockfs" ino=23467 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 17:22:24.984  3853  3899 W jxcore-log: Starting JXcore engine
,09-12 17:22:25.064  3853  3899 W jxcore-log: Platform android
09-12 17:22:25.064  3853  3899 W jxcore-log: 
,09-12 17:22:25.064  3853  3899 W jxcore-log: Process ARCH arm
09-12 17:22:25.064  3853  3899 W jxcore-log: 
,09-12 17:22:25.266  3853  3899 I jxcore-log: JXcore Cordova bridge is ready!
09-12 17:22:25.266  3853  3899 I jxcore-log: 
,09-12 17:22:25.266  3853  3899 W jxcore-log: JXcore engine is started
,09-12 17:22:25.280  3853  3893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 17:22:25.284  3853  3853 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 17:22:26.847  3042  3901 V KeepSync: Connecting to GoogleApiClient
09-12 17:22:26.847   873  2030 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 17:22:26.888  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:22:26.893  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:22:26.927  1508  2286 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 17:22:26.927  1508  2286 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 17:22:26.927  1508  2286 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 17:22:26.927  1508  2286 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:22:26.950  1715  3902 V BaseAuthAsyncOperation: access token request failed
,09-12 17:22:26.951  3042  3901 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 17:22:27.020  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 17:22:27.020  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 17:22:27.020  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 17:22:27.021  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:22:27.041  3042  3901 E KeepSync: IOException
09-12 17:22:27.041  3042  3901 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 17:22:27.041  3042  3901 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 17:22:27.041  3042  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 17:22:27.041  3042  3901 E KeepSync: 	... 10 more
,09-12 17:22:27.041  3042  3901 W KeepSync: Sync result 2
,09-12 17:22:27.054   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 285609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 17:22:39.745  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 17:22:39.745  3853  3899 I jxcore-log: 
,09-12 17:22:39.748  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 17:22:39.748  3853  3899 I jxcore-log: 
,09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:39.760  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:22:39.767  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:22:39.769  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 17:22:39.769  3853  3899 I jxcore-log: 
,09-12 17:22:39.771  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 17:22:39.771  3853  3899 I jxcore-log: 
,09-12 17:22:40.145  3853  3899 I jxcore-log: Running unit tests
09-12 17:22:40.145  3853  3899 I jxcore-log: 
,09-12 17:22:40.146  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:22:40.146  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1c91c4 added. We now have 2 listener(s)
,09-12 17:22:40.147  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 17:22:40.147  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 17:22:40.147  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 17:22:40.147  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:22:40.147  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82bf8ad added. We now have 2 listener(s)
,09-12 17:22:40.147  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:22:40.148  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 17:22:40.156  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:40.173  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:22:40.176  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:22:40.177  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:22:40.177  3853  3899 D executeNativeTests: Running unit tests
,09-12 17:22:40.179  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:40.181  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:40.249  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:22:40.249  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 added. We now have 3 listener(s)
,09-12 17:22:40.251  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 17:22:40.251  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 17:22:40.251  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 17:22:40.251  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:22:40.251  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 added. We now have 3 listener(s)
,09-12 17:22:40.251  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 17:22:40.251  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:22:40.255  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:40.260  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:22:40.264  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:22:40.264  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:22:40.266  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:22:40.266  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 17:22:40.268  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:40.268  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 17:22:40.268  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 17:22:40.268  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 17:22:40.270  3853  3899 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 17:22:40.270  3853  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 17:22:40.270  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 17:22:40.270  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:22:40.270  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:22:40.270  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:22:40.270  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:22:40.271  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:22:40.271  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:22:40.271  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:22:40.271  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.271  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:22:40.271  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 17:22:40.271  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 removed from the list
09-12 17:22:40.272  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.272  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 removed from the list
09-12 17:22:40.272  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:22:40.272  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.272  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.272  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.275  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:22:40.276  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:22:40.276  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.276  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:22:40.277  3853  3899 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 17:22:40.280  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:22:40.280  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:22:40.280  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:22:40.280  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:22:40.280  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.280  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.281  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:22:40.281  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.281  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:40.281  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:22:40.281  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.281  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.281  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.281  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.282  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:22:40.282  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:22:40.282  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.282  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:40.290  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 17:22:40.290  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 17:22:40.290  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 17:22:40.290  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 17:22:40.290  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 17:22:40.291  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 17:22:40.292  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 17:22:40.293  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 17:22:40.293  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:22:40.293  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:22:40.293  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:22:40.294  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:22:40.294  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.294  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.294  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:22:40.294  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.294  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:40.294  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:22:40.294  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.294  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.294  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:40.295  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:22:40.296  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:22:40.296  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:22:40.296  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:40.296  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:40.297  3853  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 17:22:40.299  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:40.305  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:22:40.309  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:40.309  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 17:22:40.310  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 17:22:40.310  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 17:22:40.310  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 17:22:40.310  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:40.310  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 17:22:40.312  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:22:40.314  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 17:22:40.314  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 17:22:40.314  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:22:40.320  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 17:22:40.322  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 17:22:40.323  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 17:22:40.325  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 17:22:40.329  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 17:22:40.329  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 17:22:40.329  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 17:22:40.330  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 17:22:40.331  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:22:40.336  2702  2712 D BtGatt.GattService: registerClient() - UUID=a8ebec88-11f1-4af5-a6bf-698547141d74
09-12 17:22:40.336  2702  2739 D BtGatt.GattService: onClientRegistered() - UUID=a8ebec88-11f1-4af5-a6bf-698547141d74, clientIf=5
09-12 17:22:40.337  3853  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 17:22:40.338  2702  2892 D BtGatt.GattService: start scan with filters
09-12 17:22:40.341  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 17:22:40.342  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 17:22:40.342  2702  2764 D BtGatt.ScanManager: handling starting scan
09-12 17:22:40.342  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 17:22:40.342  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 17:22:40.344  2702  2764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:22:40.345  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 17:22:40.345  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 17:22:40.346  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 17:22:40.347  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 17:22:40.350  3853  3899 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 17:22:40.355  2702  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 17:22:40.355  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:40.356  2702  2764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 17:22:40.370  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 17:22:40.370  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:40.371  2702  2764 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 17:22:40.371  2702  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 17:22:40.393  2702  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 17:22:40.393  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:40.407  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 17:22:40.407  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:40.839   873  1866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 17:22:40.847  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 17:22:40.848  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 17:22:40.848  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:22:41.913  2702  2702 D BtGatt.ScanManager: awakened up at time 325658
,09-12 17:22:41.916  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:41.965  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-12 17:22:41.966  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:41.966  2702  2739 D BtGatt.GattService: current time is 325712438076
,09-12 17:22:41.969  2702  2739 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -106, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 17:22:41.973  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 17:22:41.976  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 17:22:41.977  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 17:22:41.978  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 17:22:41.979  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-12 17:22:41.980  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 17:22:43.469  2702  2702 D BtGatt.ScanManager: awakened up at time 327214
,09-12 17:22:43.471  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:43.500  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-12 17:22:43.501  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:43.501  2702  2739 D BtGatt.GattService: current time is 327247375160
09-12 17:22:43.502  2702  2739 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 17:22:43.503  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 17:22:43.503  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 17:22:43.504  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 17:22:45.003  2702  2702 D BtGatt.ScanManager: awakened up at time 328749
,09-12 17:22:45.008  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:45.017  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 17:22:45.018  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:45.359  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:22:45.360  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:22:45.360  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 17:22:45.361  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:45.361  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 17:22:45.362  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:22:45.363  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 17:22:45.364  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 17:22:45.364  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 17:22:45.366  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 17:22:45.366  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 17:22:45.369  3853  3899 D BluetoothAdapter: STATE_ON
,09-12 17:22:45.371  2702  2893 D BtGatt.GattService: stopScan() - queue size =1
,09-12 17:22:45.374  2702  2714 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 17:22:45.375  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 17:22:45.375  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 17:22:45.376  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 17:22:45.376  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 17:22:45.377  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 17:22:45.380  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 17:22:45.382  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 17:22:45.382  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 17:22:45.383  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 17:22:45.384  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:22:45.389  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:22:45.389  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 17:22:45.390  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:22:45.391  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:22:45.391  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:45.391  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:22:45.392  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:22:45.392  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:45.392  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:45.393  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:22:45.393  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:22:45.395  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 17:22:45.396  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:45.396  2702  2764 D BtGatt.ScanManager: stopping BLe Batch
,09-12 17:22:45.404  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 17:22:45.405  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:45.405  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:45.419  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 17:22:45.420  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:45.891  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:22:50.396  3853  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 17:22:50.401  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:50.415  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:22:50.422  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:22:50.423  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:22:50.423  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 17:22:50.423  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 17:22:50.424  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 17:22:50.424  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:50.424  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 17:22:50.431  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:22:50.435  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 17:22:50.435  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 17:22:50.439  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:50.448  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 17:22:50.450  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 17:22:50.451  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 17:22:50.460  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 17:22:50.461  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 17:22:50.461  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 17:22:50.463  3853  3899 D BluetoothAdapter: STATE_ON
,09-12 17:22:50.469  2702  2893 D BtGatt.GattService: registerClient() - UUID=ca093710-824b-4f04-9cd7-ec5f26043d70
,09-12 17:22:50.470  2702  2739 D BtGatt.GattService: onClientRegistered() - UUID=ca093710-824b-4f04-9cd7-ec5f26043d70, clientIf=5
,09-12 17:22:50.471  3853  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 17:22:50.472  2702  2712 D BtGatt.GattService: start scan with filters
,09-12 17:22:50.480  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 17:22:50.480  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 17:22:50.480  2702  2764 D BtGatt.ScanManager: handling starting scan
,09-12 17:22:50.480  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,09-12 17:22:50.481  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 17:22:50.489  2702  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 17:22:50.490  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:50.490  2702  2764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 17:22:50.491  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:22:50.491  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:22:50.492  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 17:22:50.499  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 17:22:50.509  3853  3899 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 17:22:50.510  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 17:22:50.510  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:50.512  2702  2764 D BtGatt.ScanManager: Starting BLE batch scan
09-12 17:22:50.512  2702  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 17:22:50.517  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:22:50.517  3853  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 17:22:50.517  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 17:22:50.517  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 17:22:50.517  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:50.518  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 17:22:50.518  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:22:50.518  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 17:22:50.518  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 17:22:50.518  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 17:22:50.518  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 17:22:50.518  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 17:22:50.520  3853  3899 D BluetoothAdapter: STATE_ON
,09-12 17:22:50.522  2702  2712 D BtGatt.GattService: stopScan() - queue size =1
,09-12 17:22:50.523  2702  2714 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 17:22:50.524  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 17:22:50.524  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 17:22:50.525  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 17:22:50.525  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 17:22:50.525  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 17:22:50.528  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:22:50.529  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 17:22:50.529  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 17:22:50.529  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 17:22:50.531  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:22:50.534  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 17:22:50.534  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:22:50.535  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:22:50.535  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:22:50.535  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:50.536  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:22:50.536  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:22:50.536  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:22:50.536  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:22:50.537  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:22:50.537  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:22:50.538  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:22:50.538  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:22:50.541  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:22:50.541  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:22:50.542  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:22:50.542  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:22:50.545  3853  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 17:22:50.546  2702  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 17:22:50.546  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:50.550  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:50.557  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:22:50.557  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:22:50.558  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:50.561  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:22:50.562  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 17:22:50.562  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 17:22:50.562  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 17:22:50.563  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 17:22:50.563  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:22:50.563  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 17:22:50.568  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:22:50.568  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 17:22:50.569  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:50.569  2702  2764 D BtGatt.ScanManager: stopping BLe Batch
09-12 17:22:50.569  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 17:22:50.569  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 17:22:50.574  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 17:22:50.575  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:22:50.576  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 17:22:50.576  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 17:22:50.579  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 17:22:50.579  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:50.580  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:50.582  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 17:22:50.582  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 17:22:50.582  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 17:22:50.584  3853  3899 D BluetoothAdapter: STATE_ON
,09-12 17:22:50.587  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 17:22:50.588  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:50.588  2702  2712 D BtGatt.GattService: registerClient() - UUID=af772c3a-6287-4f69-bcbd-13c04db60408
,09-12 17:22:50.590  2702  2739 D BtGatt.GattService: onClientRegistered() - UUID=af772c3a-6287-4f69-bcbd-13c04db60408, clientIf=5
,09-12 17:22:50.591  3853  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 17:22:50.591  2702  2714 D BtGatt.GattService: start scan with filters
,09-12 17:22:50.595  2702  2764 D BtGatt.ScanManager: handling starting scan
,09-12 17:22:50.595  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 17:22:50.596  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 17:22:50.596  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 17:22:50.596  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 17:22:50.602  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:22:50.603  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 17:22:50.603  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 17:22:50.604  2702  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 17:22:50.604  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:50.605  2702  2764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 17:22:50.609  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 17:22:50.613  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 17:22:50.613  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:50.614  2702  2764 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 17:22:50.614  2702  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 17:22:50.616  3853  3899 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 17:22:50.627  2702  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 17:22:50.627  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:50.635  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 17:22:50.635  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:51.104  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 17:22:51.105  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 17:22:51.105  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:22:52.142  2702  2702 D BtGatt.ScanManager: awakened up at time 335888
,09-12 17:22:52.146  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:52.195  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-12 17:22:52.195  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:52.196  2702  2739 D BtGatt.GattService: current time is 335942045351
,09-12 17:22:52.197  2702  2739 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -92, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 17:22:52.198  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 17:22:52.199  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 17:22:52.200  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 17:22:52.201  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 17:22:52.202  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 17:22:53.698  2702  2702 D BtGatt.ScanManager: awakened up at time 337444
,09-12 17:22:53.701  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:53.752  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 17:22:53.752  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:53.752  2702  2739 D BtGatt.GattService: current time is 337498578573
,09-12 17:22:53.754  2702  2739 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -103, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -92, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 17:22:53.755  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 17:22:53.756  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 17:22:53.757  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 17:22:53.758  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 17:22:53.759  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 17:22:53.760  2702  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 17:22:55.253  2702  2702 D BtGatt.ScanManager: awakened up at time 338999
,09-12 17:22:55.257  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:55.266  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 17:22:55.266  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:55.616  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:22:55.617  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:22:55.617  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 17:22:55.618  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:22:55.618  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 17:22:55.618  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 17:22:55.618  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 17:22:55.619  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 17:22:55.619  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 17:22:55.619  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 17:22:55.620  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 17:22:55.623  3853  3899 D BluetoothAdapter: STATE_ON,
09-12 17:22:55.625  2702  2892 D BtGatt.GattService: stopScan() - queue size =1
,09-12 17:22:55.627  2702  2714 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 17:22:55.628  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 17:22:55.628  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 17:22:55.629  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 17:22:55.629  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 17:22:55.629  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-12 17:22:55.633  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:22:55.633  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 17:22:55.634  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 17:22:55.634  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 17:22:55.637  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:22:55.639  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:22:55.640  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:22:55.640  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:22:55.641  2702  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 17:22:55.641  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:55.643  2702  2764 D BtGatt.ScanManager: stopping BLe Batch
,09-12 17:22:55.653  2702  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 17:22:55.653  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:22:55.653  2702  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:22:55.662  2702  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 17:22:55.662  2702  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:22:56.142  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:22:56.142  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:22:56.142  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:22:58.225  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:22:58.246  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:22:58.252  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:22:58.285  1508  2412 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 17:22:58.285  1508  2412 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 17:22:58.285  1508  2412 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 17:22:58.285  1508  2412 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:22:58.301  1508  2412 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 17:22:58.301  1508  2412 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 17:22:58.307  3513  3542 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 17:22:58.307  3513  3542 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 17:22:58.307  3513  3542 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 17:22:58.307  3513  3542 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 17:22:58.307  3513  3542 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 17:22:58.307  3513  3542 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 17:22:58.307  3513  3542 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 17:23:00.641  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:00.641  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.642  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 17:23:00.642  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.642  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.643  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:23:00.643  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:00.643  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.644  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.644  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:00.644  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.646  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.647  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:00.651  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:23:00.652  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:23:00.652  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.653  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.656  3853  3899 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 17:23:00.658  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:00.659  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.660  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.660  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.662  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.662  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.662  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.662  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.662  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.662  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.662  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.662  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.662  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.663  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.665  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:23:00.665  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.665  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.666  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.668  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 17:23:00.669  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:00.669  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.669  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 17:23:00.670  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:23:00.670  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.670  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.671  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:00.671  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:00.671  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.671  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:00.672  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.672  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 17:23:00.672  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.672  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.675  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.675  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.675  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.676  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.677  3853  3899 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 17:23:00.678  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:00.678  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.678  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.679  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.679  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.679  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.680  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.680  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.680  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.680  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:00.681  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.681  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.681  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.682  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:00.684  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.684  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.684  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.684  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.686  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 17:23:00.686  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:00.686  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.686  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.687  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:23:00.687  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.687  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.687  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.688  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:00.688  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.688  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.688  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.688  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.688  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.689  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.691  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.691  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:23:00.691  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:00.691  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.693  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 17:23:00.693  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 17:23:00.693  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 17:23:00.693  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 17:23:00.694  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:23:00.694  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:23:00.694  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 17:23:00.695  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 17:23:00.695  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 17:23:00.695  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:00.695  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:23:00.695  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.696  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.696  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.697  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:00.697  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.697  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.697  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.697  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.698  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.698  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.698  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.698  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.700  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:23:00.700  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.701  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.701  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.705  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 17:23:00.706  3853  3899 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 17:23:00.706  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 17:23:00.712  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 17:23:00.713  3853  3899 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 17:23:00.713  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 17:23:00.713  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 17:23:00.713  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 17:23:00.713  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-12 17:23:00.713  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 17:23:00.714  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 17:23:00.715  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 17:23:00.716  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 17:23:00.716  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 17:23:00.716  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 17:23:00.716  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 17:23:00.716  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 17:23:00.716  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to ,peer with ID abcd
09-12 17:23:00.716  3853  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 17:23:00.717  3853  3899 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 17:23:00.717  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 17:23:00.717  3853  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 17:23:00.717  3853  3899 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 17:23:00.717  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 17:23:00.717  3853  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 17:23:00.717  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-12 17:23:00.722  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-12 17:23:00.723  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 17:23:00.723  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 17:23:00.724  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 17:23:00.724  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-12 17:23:00.724  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 17:23:00.725  3853  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 17:23:00.725  3853  3899 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 17:23:00.726  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:00.726  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:23:00.726  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.726  3853  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 392)
09-12 17:23:00.726  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.726  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.726  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.726  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 17:23:00.727  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.728  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.728  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.728  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.728  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.728  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.728  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.728  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.729  3853  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 392
09-12 17:23:00.729  3853  3908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:00.729  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.729  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.730  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.730  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.731  3853  3899 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 17:23:00.731  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:00.731  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.731  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.731  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:23:00.732  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.732  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.732  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.732  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.732  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:00.732  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:00.732  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.732  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.732  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.732  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:00.733  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:23:00.734  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:23:00.734  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.734  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.734  3853  3899 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 17:23:00.735  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:00.735  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.735  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 17:23:00.735  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.736  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.736  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.736  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.736  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.736  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.736  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.737  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:00.737  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.737  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.737  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.738  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.738  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:00.738  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.739  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.739  3853  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 17:23:00.739  3853  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-12 17:23:00.740  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 17:23:00.740  3853  3899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 17:23:00.740  3853  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 17:23:00.740  3853  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 17:23:00.740  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 17:23:00.740  3853  3899 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 17:23:00.740  3853  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 17:23:00.740  3853  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-12 17:23:00.740  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 17:23:00.741  3853  3899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 17:23:00.741  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:00.741  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:00.741  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:00.741  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.741  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.742  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.742  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:00.742  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.742  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.742  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:00.742  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.742  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.742  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.742  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.744  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:00.744  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:23:00.744  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.744  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.744  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:00.744  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.744  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:00.745  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:00.745  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:00.745  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:00.745  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:00.745  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:00.745  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:05.746  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.746  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.747  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:05.747  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.747  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.748  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:05.748  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:05.749  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:05.749  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:05.749  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:05.750  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:05.750  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.750  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:05.751  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.751  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.751  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:05.751  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.752  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:05.752  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.752  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:05.757  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:05.757  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:05.758  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:05.758  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.763  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 17:23:05.764  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:23:05.768  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 17:23:05.770  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 17:23:05.771  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 17:23:05.772  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 17:23:05.773  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 17:23:05.773  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:23:05.775  3853  3910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:05.775  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:23:05.776  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 17:23:05.776  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 17:23:05.776  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 17:23:05.776  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:05.777  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 17:23:05.778  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 17:23:05.778  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:05.779  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.779  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 17:23:05.779  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 17:23:05.779  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 17:23:05.781  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:05.781  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.782  3853  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 17:23:05.783  3853  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 17:23:05.783  3853  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 17:23:05.785  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:23:05.785  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:23:05.786  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:23:05.786  3853  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 17:23:05.786  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:23:05.788  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.788  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:05.788  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:23:05.788  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:05.789  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:05.789  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:05.789  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.789  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:05.789  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 17:23:05.789  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:05.789  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:05.789  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.789  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.789  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.789  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.791  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:05.791  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:05.791  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.792  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:05.793  3853  3899 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 17:23:05.794  3853  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 17:23:05.794  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-12 17:23:05.795  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:23:05.795  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 17:23:05.795  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:05.795  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:05.795  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:05.796  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:05.796  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.796  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.796  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:05.796  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.796  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:05.796  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:05.796  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.796  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.796  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.796  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.799  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:05.799  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:05.799  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.799  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.806  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:23:05.806  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:05.806  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:05.807  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:23:05.807  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.807  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.807  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
,09-12 17:23:05.807  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.807  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:05.807  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:05.807  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.807  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.808  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.808  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:05.809  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:23:05.809  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:23:05.810  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.810  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.811  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:23:05.811  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:23:05.812  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:23:05.812  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:23:05.812  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.812  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.812  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8d363 not in the list
09-12 17:23:05.812  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.812  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
09-12 17:23:05.813  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:05.813  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.813  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.813  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:05.813  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:05.814  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:23:05.814  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:23:05.814  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:05.815  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec5b60 not in the list
,09-12 17:23:05.816  3853  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 17:23:05.816  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 17:23:05.816  3853  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 17:23:05.816  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 17:23:05.816  3853  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 17:23:05.816  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 17:23:05.819  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 17:23:05.819  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 17:23:05.820  3853  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 17:23:05.821  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 17:23:05.821  3853  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 17:23:05.821  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-12 17:23:05.821  3853  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 17:23:05.821  3853  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 17:23:05.822  3853  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 17:23:05.822  3853  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 17:23:05.822  3853  3899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 17:23:05.823  3853  3899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 17:23:05.823  3853  3899 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 17:23:05.823  3853  3899 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 17:23:05.824  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:23:05.824  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@994df42 added. We now have 3 listener(s)
,09-12 17:23:05.824  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:05.826  3853  3899 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 17:23:05.827   873  1395 D WifiService: setWifiEnabled: true pid=3853, uid=10000
09-12 17:23:05.827   873  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:05.862  2702  2868 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-12 17:23:05.862  2702  2889 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-12 17:23:05.863  3853  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 392)
,09-12 17:23:06.287  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:23:10.835  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:23:10.835  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f755b53 added. We now have 4 listener(s)
09-12 17:23:10.836  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:10.852  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:10.853  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f755b53 removed from the list
09-12 17:23:10.853  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:10.853  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:10.854  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:10.856  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:23:10.856  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfd5c90 added. We now have 4 listener(s)
09-12 17:23:10.857  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:10.860  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:10.861  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfd5c90 removed from the list
09-12 17:23:10.861  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:10.861  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:10.862  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:10.864  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:23:10.864  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4747989 added. We now have 4 listener(s)
,09-12 17:23:10.865  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:10.872   873  1936 D WifiService: setWifiEnabled: false pid=3853, uid=10000
,09-12 17:23:10.872   873  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:10.883  2702  2728 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 17:23:10.884  2702  2728 D BluetoothAdapterProperties: Setting state to 13
09-12 17:23:10.884  2702  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 17:23:10.884  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:23:10.886  2702  2728 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 17:23:10.894  2702  2728 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:10.898  2702  2702 D BluetoothMapService: onReceive
,09-12 17:23:10.898  2702  2702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 17:23:10.898  2702  2702 D BluetoothMapService: STATE_TURNING_OFF
,09-12 17:23:10.898  2702  2702 D BluetoothMapService: MAP Service closeService in
,09-12 17:23:10.898  2702  2702 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 17:23:10.899  2702  2702 D ObexServerSockets0: shutdown(block = true)
,09-12 17:23:10.899  2702  2739 D BluetoothAdapterProperties: Scan Mode:20
,09-12 17:23:10.900  2702  2905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 17:23:10.900  2702  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 17:23:10.902  2702  2702 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 17:23:10.902  2702  2702 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 17:23:10.903  2702  2906 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 17:23:10.903  2702  2702 I BtOppRfcommListener: stopping Accept Thread
09-12 17:23:10.904  2702  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 17:23:10.904  2702  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 17:23:10.905  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.905  2702  2889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:10.905  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:23:10.908  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.908  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:10.908  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:23:10.912  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:10.915  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:10.919  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:10.919  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:23:10.919   873   886 I ActivityManager: Start proc 3914:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 17:23:10.920  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:10.920  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:23:10.922  2702  2702 D HeadsetService: Received stop request...Stopping profile...
09-12 17:23:10.924   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:10.924  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 17:23:10.924  1984  2375 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:10.925  1352  1377 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:10.925   873  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 17:23:10.925   873  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 17:23:10.925   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 17:23:10.925  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:10.926  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:23:10.926   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:10.927  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:10.927   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:10.927  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:10.927   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:10.928  1352  1352 D HeadsetProfile: Bluetooth service disconnected
,09-12 17:23:10.930  2702  2702 D A2dpService: Received stop request...Stopping profile...
09-12 17:23:10.931  2702  2897 D A2dpStateMachine: Exit Disconnected: -1
09-12 17:23:10.931  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:10.933   873  1313 E native  : do suspend true
09-12 17:23:10.933   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 17:23:10.933  1352  1352 D BluetoothA2dp: Proxy object disconnected
09-12 17:23:10.933  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:10.934  2702  2702 D HidService: Received stop request...Stopping profile...
,09-12 17:23:10.934  2702  2702 D HidService: Stopping Bluetooth HidService
,09-12 17:23:10.935  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-12 17:23:10.935  1352  1352 D HidProfile: Bluetooth service disconnected
,09-12 17:23:10.936  2702  2702 V BluetoothAdapterState: isTurningOff()=true
,09-12 17:23:10.936  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:10.936  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.936  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.936  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:10.936  2702  2702 D HealthService: Received stop request...Stopping profile...
09-12 17:23:10.938  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:10.938  2702  2702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 17:23:10.939  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.940  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.940  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.940  2702  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 17:23:10.940  2702  2739 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 17:23:10.940  2702  2702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 17:23:10.941  2702  2702 D PanService: Received stop request...Stopping profile...
09-12 17:23:10.942  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 17:23:10.942  1352  1352 D PanProfile: Bluetooth service disconnected
09-12 17:23:10.943  2702  2702 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:10.943  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.943  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.943  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:10.943  2702  2702 D BluetoothMapService: Received stop request...Stopping profile...
09-12 17:23:10.943  2702  2702 D BluetoothMapService: stop()
09-12 17:23:10.944  2702  2702 D BluetoothMapAppObserver: deinitObservers()
09-12 17:23:10.944  2702  2702 D BluetoothMapAppObserver: removeReceiver()
,09-12 17:23:10.945  1352  1352 D BluetoothMap: Proxy object disconnected
09-12 17:23:10.945  1352  1352 D MapProfile: Bluetooth service disconnected
09-12 17:23:10.946   873  1880 D DhcpClient: Clearing IP address
09-12 17:23:10.946   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 17:23:10.949   372   872 D CommandListener: Setting iface cfg
09-12 17:23:10.949  2702  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 17:23:10.949  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.949  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.949  2702  2868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 17:23:10.949  2702  2868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 17:23:10.950  2702  2868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 17:23:10.950  2702  2868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 17:23:10.950  2702  2702 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:10.950  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.950  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.950  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:10.950  2702  2702 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 17:23:10.950  2702  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 17:23:10.951  2702  2702 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 17:23:10.951  2702  2702 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:10.951  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.951  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.951  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:10.951  2702  2702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 17:23:10.951  2702  2739 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 17:23:10.952  2702  2702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 17:23:10.953   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 17:23:10.954   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 17:23:10.956   873  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-12 17:23:10.956   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 17:23:10.956   873  1313 E native  : do suspend true
09-12 17:23:10.952  2702  2702 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:10.959  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.959  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.959  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:10.959  2702  2702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 17:23:10.959  2702  2702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 17:23:10.960   443   443 E Parcel  : Reading a NULL string not supported here.
09-12 17:23:10.961  2702  2702 D BluetoothMapService: MAP Service closeService in
09-12 17:23:10.961  2702  2702 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:10.961  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:10.962  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:10.962  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:10.962  2702  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 17:23:10.962  2702  2702 D BluetoothMapService: cleanup()
09-12 17:23:10.962  2702  2728 D BluetoothAdapterProperties: Setting state to 15
09-12 17:23:10.962  2702  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 17:23:10.962  2702  2702 D BluetoothMapService: MAP Service closeService in
09-12 17:23:10.962   873  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-12 17:23:10.962  2702  2728 I BluetoothAdapterState: Entering BleOnState
09-12 17:23:10.963  1352  1372 D BluetoothPan: onBluetoothStateChange on: false
09-12 17:23:10.965  1352  2140 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 17:23:10.965  1508  2433 V NativeCrypto: Read error: ssl=0x9b538000: I/O error during system call, Connection timed out
,09-12 17:23:10.966  1352  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 17:23:10.966  1984  2375 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:10.966   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:10.967  1352  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-12 17:23:10.967   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:10.967   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 17:23:10.967  1352  2140 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 17:23:10.968   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 17:23:10.969  1352  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:10.969  2702  2728 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-12 17:23:10.969  2702  2728 D BluetoothAdapterProperties: Setting state to 16
09-12 17:23:10.969  2702  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 17:23:10.969  2702  2728 D BluetoothAdapterProperties: onBleDisable
,09-12 17:23:10.970  2702  2728 I BluetoothAdapterState: Entering PendingCommandState
09-12 17:23:10.970  2702  2731 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 17:23:10.971  2702  2868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 17:23:10.971  2702  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:10.971   873  1883 D DhcpClient: Receive thread stopped
09-12 17:23:10.973  2702  2739 D BluetoothAdapterProperties: Scan Mode:20
09-12 17:23:10.974  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:10.974  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:10.975  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.975  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:10.977  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:10.977  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:10.977  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.977  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:10.979  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:10.979  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:10.980  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
09-12 17:23:10.980  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:10.981  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:10.982  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:10.983  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:10.990   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 17:23:10.990  1508  2433 V NativeCrypto: SSL shutdown failed: ssl=0x9b538000: I/O error during system call, Broken pipe
,09-12 17:23:11.008   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 17:23:11.008   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 17:23:11.009   873  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 17:23:11.009   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:11.011   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 17:23:11.013   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 17:23:11.015  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:11.017  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:11.018  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:11.020  3376  3376 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@84c09a4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 17:23:11.026  3914  3914 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 17:23:11.031   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:11.033   873  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 17:23:11.034  1867  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 17:23:11.034  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:11.034  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:11.034  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:11.034  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:11.036  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:11.036  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:11.036  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:11.036  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:11.038  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:11.038  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:11.038  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:11.038  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:11.043  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 17:23:11.048  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:11.050   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@595359e:true
,09-12 17:23:11.060   873  2016 I ActivityManager: Start proc 3934:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 17:23:11.068   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 17:23:11.069   873  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 17:23:11.087  3934  3934 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 17:23:11.090  3914  3914 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 17:23:11.092  3914  3914 D BluetoothMap: Create BluetoothMap proxy object
,09-12 17:23:11.099  3914  3914 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 17:23:11.113  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:11.120   873  2016 I ActivityManager: Killing 3376:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 17:23:11.172  2702  2739 I bt_hci  : shut_down
,09-12 17:23:11.180  2702  2766 D bt_hwcfg: hw_epilog_process
,09-12 17:23:11.181  2702  2766 I bt_vendor: low_power_mode_cb
,09-12 17:23:11.204  2702  2766 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 17:23:11.204  2702  2766 I bt_vendor: epilog_cb
,09-12 17:23:11.205  2702  2766 I bt_hci  : epilog_finished_callback
,09-12 17:23:11.211  2702  2739 I bt_hci_h4: hal_close
,09-12 17:23:11.212  2702  2739 I bt_userial_vendor: device fd = 51 close
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.274  3934  3934 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.274  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.275  3934  3934 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:23:11.275  3934  3934 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:23:11.278  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 17:23:11.288  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:11.299  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:11.307   873  1395 I ActivityManager: Killing 3564:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 17:23:11.371  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 17:23:11.377  1715  1715 D SystemUpdateService: onCreate
,09-12 17:23:11.380  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 17:23:11.382  2702  2731 D bt_stack_manager: event_shut_down_stack finished.
09-12 17:23:11.383  2702  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 17:23:11.388  2702  2728 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 17:23:11.389  2702  2702 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 17:23:11.409  2702  2702 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 17:23:11.409  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-12 17:23:11.409  2702  2702 D BtGatt.GattService: stop()
09-12 17:23:11.410  2702  2702 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 17:23:11.413  2702  2702 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:11.413  2702  2702 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:11.413  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 17:23:11.413  2702  2702 V BluetoothAdapterState: isBleTurningOff()=true
09-12 17:23:11.414  2702  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 17:23:11.414  2702  2728 D BluetoothAdapterProperties: Setting state to 10
09-12 17:23:11.414  2702  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 17:23:11.415   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 17:23:11.417  2702  2728 I BluetoothAdapterState: Entering OffState
,09-12 17:23:11.419  1715  2407 I iu.UploadsManager: num queued entries: 0
,09-12 17:23:11.425  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 17:23:11.426  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 17:23:11.429  1715  2407 I iu.UploadsManager: num updated entries: 0
,09-12 17:23:11.430  1715  2407 I iu.SyncManager: NEXT; no task
,09-12 17:23:11.406  1715  3965 I SystemUpdateService: active receiver: enabled
,09-12 17:23:11.440  1715  3965 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 17:23:11.442  1715  3965 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 17:23:11.442  1715  3965 I SystemUpdateService: now status is 0 (complete)
,09-12 17:23:11.442  1715  3965 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 17:23:11.442  1715  3965 I SystemUpdateService: file has been verified
09-12 17:23:11.443  1715  3965 I SystemUpdateService: OTA package size = 12249756
09-12 17:23:11.446   873  2104 I ActivityManager: Start proc 3967:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 17:23:11.459  2702  2702 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 17:23:11.459  2702  2702 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 17:23:11.459  2702  2702 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 17:23:11.460  2702  2731 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 17:23:11.464  2702  2731 D bt_stack_manager: event_clean_up_stack finished.
,09-12 17:23:11.469  2702  2702 I art     : System.exit called, status: 0
,09-12 17:23:11.469  2702  2702 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 17:23:11.474  1715  3965 I SystemUpdateService: showing system update notification
,09-12 17:23:11.498  3967  3967 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 17:23:11.501  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:11.512  3967  3967 D SprintDMHelper: simOperator: 
,09-12 17:23:11.512  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 17:23:11.537   873  1395 I ActivityManager: Start proc 3980:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 17:23:11.542   873  1937 I ActivityManager: Process com.android.bluetooth (pid 2702) has died
,09-12 17:23:11.569  1715  1715 D SystemUpdateService: onDestroy
,09-12 17:23:11.703  3934  3957 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 17:23:11.719   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b728575:true
,09-12 17:23:11.720   873  1395 I ActivityManager: Start proc 3997:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 17:23:11.725   873  1395 I ActivityManager: Killing 3441:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 17:23:11.794  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 17:23:11.858  3997  3997 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 17:23:11.858  3997  3997 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 17:23:11.858  3997  3997 I GAv4    :   adb logcat -s GAv4
,09-12 17:23:11.870  3997  3997 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 17:23:11.876  3997  3997 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 17:23:11.900  3997  4014 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 17:23:12.024  3997  3997 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 17:23:12.058  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 17:23:12.067  3997  3997 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5810-5812)
,09-12 17:23:12.069  3997  3997 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 17:23:12.082  3997  3997 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79723d4}
,09-12 17:23:12.083  3997  3997 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 17:23:12.083  3997  3997 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 17:23:12.093  3997  3997 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 17:23:12.094  3997  3997 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 17:23:12.110  3997  3997 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 17:23:12.123  3997  3997 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 17:23:12.124  3997  3997 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 17:23:12.124  3997  3997 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 17:23:12.124  3997  3997 I Adreno  : Build Date                       : 10/20/15
09-12 17:23:12.124  3997  3997 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 17:23:12.124  3997  3997 I Adreno  : Local Branch                     : M14
09-12 17:23:12.124  3997  3997 I Adreno  : Remote Branch                    : 
09-12 17:23:12.124  3997  3997 I Adreno  : Remote Branch                    : 
09-12 17:23:12.124  3997  3997 I Adreno  : Reconstruct Branch               : 
,09-12 17:23:12.189  3997  3997 I NSApplication: Starting up...
,09-12 17:23:12.199  3997  4043 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 17:23:12.216   873  2103 I ActivityManager: Start proc 4048:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 17:23:12.220   873  2103 I ActivityManager: Killing 3496:android.process.acore/u0a5 (adj 15): empty #17
,09-12 17:23:12.290  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 17:23:12.489   873  1936 I ActivityManager: Killing 3678:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 17:23:12.504  3550  3559 W art     : Suspending all threads took: 5.366ms
,09-12 17:23:12.549   873  2019 I ActivityManager: Start proc 4062:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 17:23:12.596  4062  4062 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 17:23:12.657  4062  4062 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 17:23:12.717   873  1721 I ActivityManager: Killing 3695:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 17:23:15.911   873  2016 D WifiService: setWifiEnabled: true pid=3853, uid=10000
,09-12 17:23:15.911   873  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:15.931  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:15.931  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:15.931  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:15.931  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:15.932  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:15.932  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:15.932  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:15.932  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:15.934   873  1313 D WifiConfigStore: Loading config and enabling all networks 
09-12 17:23:15.934  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:15.934  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:15.934  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:15.934  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:15.954   873  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-12 17:23:15.957   873  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 17:23:15.961   873  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 17:23:15.964   873  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 17:23:15.964   873  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 17:23:15.965   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 17:23:15.965   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 17:23:15.987   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 17:23:15.988   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 17:23:15.988   372   872 D CommandListener: Setting iface cfg
09-12 17:23:15.988   873  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 17:23:15.989   873  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 17:23:15.997   873  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 17:23:15.997   873  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-12 17:23:15.997   873  1313 E native  : do suspend true
,09-12 17:23:16.030   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:16.840   873  1937 I ActivityManager: Killing 2061:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 17:23:17.217   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 17:23:17.252   873  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.38 rxSuccessRate=12.06 delta 1000 -> 994
,09-12 17:23:17.254   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 17:23:17.254   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:17.271   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 17:23:17.323   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 17:23:17.325  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 17:23:17.746  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 17:23:17.791  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 17:23:17.792  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 17:23:17.800   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:17.808   873  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 17:23:17.808   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 17:23:17.808   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 17:23:17.827   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:17.837   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:17.841   873  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 17:23:17.853   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 17:23:17.896   873  4098 D DhcpClient: Receive thread started
,09-12 17:23:17.978   873  1313 E native  : do suspend false
,09-12 17:23:18.002   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 17:23:18.020   873  4098 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172460, domain null
,09-12 17:23:18.021   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172460 seconds
,09-12 17:23:18.026   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 17:23:18.040   873  4098 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 17:23:18.041   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 17:23:18.047   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:18.059   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 17:23:18.059   873  1880 D DhcpClient: Scheduling renewal in 86399s
,09-12 17:23:18.061   873  1313 E native  : do suspend true
,09-12 17:23:18.082   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 17:23:18.083   873  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 17:23:18.084   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 17:23:18.086   873  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 17:23:18.086   873  1315 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 17:23:18.128   873  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 17:23:18.128   873  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-12 17:23:18.130   873  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 17:23:18.131   873  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 17:23:18.133   873  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 17:23:18.142   873  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 17:23:18.149   873  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 17:23:18.150   873  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 17:23:18.150   873  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 17:23:18.150   873  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 17:23:18.150   873  1315 D ConnectivityService:    accepting network in place of null
09-12 17:23:18.151   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 17:23:18.152   873  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 17:23:18.167   873  4097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=361913, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 17:23:18.203   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:18.238   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:18.245   873  4096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 17:23:18.251   873  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 17:23:18.251   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:18.259   873  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 17:23:18.262   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 17:23:18.277  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:18.277  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:23:18.277  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.277  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:23:18.281  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:18.281  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:23:18.281  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.281  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:23:18.283  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:18.283  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:23:18.283  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:18.283  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:23:18.295  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 17:23:18.299  1715  1715 D SystemUpdateService: onCreate
,09-12 17:23:18.303  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 17:23:18.309   873  4096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 15:23:18 GMT], X-Android-Received-Millis=[1473693798308], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473693798283]}
,09-12 17:23:18.309   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 17:23:18.310   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 17:23:18.310   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 17:23:18.311   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 17:23:18.320  1715  4110 I SystemUpdateService: active receiver: enabled
,09-12 17:23:18.327  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 17:23:18.334  1715  2407 I iu.UploadsManager: num queued entries: 0
,09-12 17:23:18.335  1715  2407 I iu.UploadsManager: num updated entries: 0
09-12 17:23:18.335  1715  2407 I iu.SyncManager: NEXT; no task
,09-12 17:23:18.336  1715  4110 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 17:23:18.339  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 17:23:18.340  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 17:23:18.342  1715  4110 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 17:23:18.342  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-12 17:23:18.342  1715  4110 I SystemUpdateService: now status is 0 (complete)
09-12 17:23:18.343  1715  4110 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 17:23:18.343  1715  4110 I SystemUpdateService: file has been verified
,09-12 17:23:18.349  1715  4114 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 17:23:18.349  1715  4114 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 17:23:18.350  3967  3967 D SprintDMHelper: simOperator: 
,09-12 17:23:18.350  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 17:23:18.359  1715  4114 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 17:23:18.365  1715  4110 I SystemUpdateService: OTA package size = 12249756
,09-12 17:23:18.381  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:23:18.385  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:23:18.407  1715  4110 I SystemUpdateService: showing system update notification
,09-12 17:23:18.439  1715  1715 D SystemUpdateService: onDestroy
,09-12 17:23:18.462  1508  2412 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-12 17:23:18.462  1508  2412 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 17:23:18.463  1508  2412 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 17:23:18.468  1508  2412 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:23:18.490  2213  4118 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 17:23:18.495  1715  4114 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-12 17:23:19.248   873  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 17:23:20.923   873  2047 D WifiService: setWifiEnabled: false pid=3853, uid=10000
,09-12 17:23:20.923   873  2047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:20.961  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 17:23:20.964   873  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 17:23:20.964   873  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 17:23:20.965   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 17:23:20.965   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:20.990   873  1313 E native  : do suspend true
,09-12 17:23:21.005   873  1880 D DhcpClient: Clearing IP address
,09-12 17:23:21.006   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 17:23:21.011   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:21.014  1508  4123 V NativeCrypto: Read error: ssl=0x99b7e400: I/O error during system call, Connection timed out
09-12 17:23:21.019  1508  4123 V NativeCrypto: SSL shutdown failed: ssl=0x99b7e400: I/O error during system call, Broken pipe
,09-12 17:23:21.025   873  4098 D DhcpClient: Receive thread stopped
,09-12 17:23:21.027   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 17:23:21.027   873  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 17:23:21.028   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-12 17:23:21.028   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 17:23:21.029   873  1313 E native  : do suspend true
09-12 17:23:21.033   443   443 E Parcel  : Reading a NULL string not supported here.
,09-12 17:23:21.045   873  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 17:23:21.076   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:21.106   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:21.106   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 17:23:21.108   873  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 17:23:21.108   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:21.113   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 17:23:21.125  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.125  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:21.125  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.125  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:21.127  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.127  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:21.127  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.128  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:21.129  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.129  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:21.129  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.129  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:21.134   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 17:23:21.144  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 17:23:21.155   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:21.157  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.158  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:21.158  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.158  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:21.158  1715  1715 D SystemUpdateService: onCreate
,09-12 17:23:21.159  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.159  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:21.159  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.159  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:21.160   873  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 17:23:21.160  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:21.161  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:21.161  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:21.161  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:21.163  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 17:23:21.166  1867  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 17:23:21.181  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 17:23:21.192  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 17:23:21.194  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 17:23:21.196  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:21.200  3967  3967 D SprintDMHelper: simOperator: 
,09-12 17:23:21.200  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 17:23:21.205  1715  2407 I iu.UploadsManager: num queued entries: 0
,09-12 17:23:21.208   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 17:23:21.210  1715  2407 I iu.UploadsManager: num updated entries: 0
,09-12 17:23:21.205  1715  4134 I SystemUpdateService: active receiver: enabled
,09-12 17:23:21.227  2213  4138 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 17:23:21.235  1715  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 17:23:21.238  1715  2407 I iu.SyncManager: NEXT; no task
,09-12 17:23:21.243  1715  4134 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 17:23:21.243  1715  4134 I SystemUpdateService: now status is 0 (complete)
09-12 17:23:21.244  1715  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 17:23:21.244  1715  4134 I SystemUpdateService: file has been verified
09-12 17:23:21.244  1715  4134 I SystemUpdateService: OTA package size = 12249756
,09-12 17:23:21.248  1715  4134 I SystemUpdateService: showing system update notification
,09-12 17:23:21.258  1715  1715 D SystemUpdateService: onDestroy
,09-12 17:23:23.318  1508  2239 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 17:23:23.694  1903  1957 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 17:23:23.694  1903  1957 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 17:23:23.725  1508  1508 I ConfigService: onCreate
,09-12 17:23:25.980   873   890 I ActivityManager: Start proc 4145:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 17:23:26.106  4145  4145 D AdapterServiceConfig: Adding HeadsetService
,09-12 17:23:26.107  4145  4145 D AdapterServiceConfig: Adding A2dpService
09-12 17:23:26.107  4145  4145 D AdapterServiceConfig: Adding HidService
09-12 17:23:26.107  4145  4145 D AdapterServiceConfig: Adding HealthService
09-12 17:23:26.107  4145  4145 D AdapterServiceConfig: Adding PanService
09-12 17:23:26.108  4145  4145 D AdapterServiceConfig: Adding GattService
,09-12 17:23:26.109  4145  4145 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 17:23:26.123  4145  4145 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 17:23:26.123   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1c91cc:true
,09-12 17:23:26.128  4145  4145 I bt_bluedroid: init
,09-12 17:23:26.129  4145  4157 I BluetoothAdapterState: Entering OffState
,09-12 17:23:26.134  4145  4158 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 17:23:26.134  4145  4158 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 17:23:26.135  4145  4158 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 17:23:26.135  4145  4158 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 17:23:26.137  4145  4145 I bt_bluedroid: get_profile_interface socket
,09-12 17:23:26.139  4145  4145 I bt_bluedroid: get_profile_interface sdp
,09-12 17:23:26.142  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 17:23:26.144  4145  4156 I bt_bluedroid: config_hci_snoop_log
,09-12 17:23:26.145  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 17:23:26.147   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 17:23:26.154   873  1315 D ConnectivityService: handlePromptUnvalidated 101
,09-12 17:23:26.156  4145  4157 D BluetoothAdapterState: Current state: OFF, message: 0
09-12 17:23:26.156  4145  4157 D BluetoothAdapterProperties: Setting state to 14
09-12 17:23:26.157  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 17:23:26.159  4145  4157 D BluetoothBondStateMachine: make
,09-12 17:23:26.163  4145  4162 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 17:23:26.166  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:26.167  4145  4145 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 17:23:26.170  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:26.171  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 17:23:26.172  4145  4145 D BtGatt.GattService: Received start request. Starting profile...
,09-12 17:23:26.172  4145  4145 D BtGatt.GattService: start()
09-12 17:23:26.172  4145  4145 I bt_bluedroid: get_profile_interface gatt
,09-12 17:23:26.174  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:23:26.174  4145  4145 D BtGatt.AdvertiseManager: advertise manager created
,09-12 17:23:26.182  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:26.183  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 17:23:26.183  4145  4145 V BluetoothAdapterState: isBleTurningOn()=true
09-12 17:23:26.183  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:26.183  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 17:23:26.184  4145  4157 I bt_bluedroid: enable
09-12 17:23:26.184  4145  4158 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 17:23:26.185  4145  4158 I bt_hci  : start_up
,09-12 17:23:26.204  4145  4158 I bt_vendor: alloc value 0xb3a84189
09-12 17:23:26.204  4145  4158 I bt_vendor: init
,09-12 17:23:26.205  4145  4158 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 17:23:26.206  4145  4158 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 17:23:26.312  4145  4158 D bt_hci  : start_up starting async portion
,09-12 17:23:26.313  4145  4165 I bt_hci  : event_finish_startup
09-12 17:23:26.313  4145  4165 I bt_hci_h4: hal_open
09-12 17:23:26.313  4145  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 17:23:26.323  4145  4165 I bt_userial_vendor: device fd = 51 open
,09-12 17:23:26.355  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 17:23:26.387  4145  4165 D bt_hwcfg: Chipset BCM4354A2
,09-12 17:23:26.387  4145  4165 D bt_hwcfg: Target name = [BCM4354A2]
09-12 17:23:26.388  4145  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 17:23:27.047  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 17:23:27.049  4145  4165 D bt_hwcfg: Settlement delay -- 100 ms
09-12 17:23:27.049  4145  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 17:23:27.166  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 17:23:27.167  4145  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 17:23:27.196  4145  4165 I bt_hwcfg: vendor lib fwcfg completed
,09-12 17:23:27.196  4145  4165 I bt_vendor: firmware callback
,09-12 17:23:27.196  4145  4165 I bt_hci  : firmware_config_callback
,09-12 17:23:27.207  4145  4167 I bt_btu  : btu_task pending for preload complete event
,09-12 17:23:27.208  4145  4167 I bt_btu_task: Bluetooth chip preload is complete
09-12 17:23:27.208  4145  4167 I bt_btu  : btu_task received preload complete event
,09-12 17:23:27.220  4145  4167 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 17:23:27.221  4145  4167 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 17:23:27.221  4145  4167 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 17:23:27.221  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 17:23:27.221  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 17:23:27.222  4145  4167 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 17:23:27.222  4145  4167 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 17:23:27.222  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 17:23:27.222  4145  4167 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 17:23:27.223  4145  4167 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 17:23:27.223  4145  4167 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 17:23:27.223  4145  4167 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 17:23:27.223  4145  4167 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 17:23:27.224  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 17:23:27.224  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 17:23:27.356  4145  4167 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a01d9d
,09-12 17:23:27.356  4145  4167 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a01d9d 
,09-12 17:23:27.368  4145  4161 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 17:23:27.370  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 17:23:27.371  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 17:23:27.374  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 17:23:27.380  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,09-12 17:23:27.380  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 17:23:27.381  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:27.381  4145  4161 D bt_hci  : do_postload posting postload work item
,09-12 17:23:27.381  4145  4165 I bt_hci  : event_postload
,09-12 17:23:27.382  4145  4165 I bt_vendor: sco_config_cb
,09-12 17:23:27.382  4145  4165 I bt_hci  : sco_config_callback postload finished.
,09-12 17:23:27.383  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:27.384  4145  4161 D bt_bte_conf: Device ID record 1 : primary,
09-12 17:23:27.384  4145  4161 D bt_bte_conf:   vendorId            = 000f
,09-12 17:23:27.384  4145  4161 D bt_bte_conf:   vendorIdSource      = 0001
09-12 17:23:27.385  4145  4161 D bt_bte_conf:   product             = 1200
09-12 17:23:27.385  4145  4161 D bt_bte_conf:   version             = 1436
,09-12 17:23:27.385  4145  4161 D bt_bte_conf:   clientExecutableURL = 
,09-12 17:23:27.385  4145  4161 D bt_bte_conf:   serviceDescription  = 
09-12 17:23:27.385  4145  4161 D bt_bte_conf:   documentationURL    = 
09-12 17:23:27.386  4145  4161 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 17:23:27.386  4145  4158 D bt_stack_manager: event_start_up_stack finished
,09-12 17:23:27.386  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:27.388  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 17:23:27.389  4145  4157 D BluetoothAdapterProperties: Setting state to 15
09-12 17:23:27.389  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 17:23:27.390  4145  4157 I BluetoothAdapterState: Entering BleOnState
,09-12 17:23:27.391  4145  4165 I bt_vendor: low_power_mode_cb
09-12 17:23:27.394  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 17:23:27.395  4145  4157 D BluetoothAdapterProperties: Setting state to 11
09-12 17:23:27.395  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 17:23:27.402  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:27.405  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:27.407  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:23:27.407  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:27.408  4145  4145 D HeadsetService: Received start request. Starting profile...
,09-12 17:23:27.412  4145  4145 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 17:23:27.412  4145  4145 D HeadsetStateMachine: make
09-12 17:23:27.414  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:27.421  4145  4145 D HeadsetStateMachine: max_hf_connections = 1
,09-12 17:23:27.421  4145  4145 I bt_bluedroid: get_profile_interface handsfree
,09-12 17:23:27.422  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 17:23:27.422  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 17:23:27.427  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:27.428  4145  4145 D A2dpService: Received start request. Starting profile...
09-12 17:23:27.428  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:27.429  4145  4145 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 17:23:27.429  4145  4145 I bt_bluedroid: get_profile_interface avrcp
,09-12 17:23:27.435  4145  4145 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 17:23:27.435  4145  4145 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 17:23:27.435  4145  4145 D A2dpStateMachine: make
09-12 17:23:27.436  4145  4145 I bt_bluedroid: get_profile_interface a2dp
,09-12 17:23:27.437  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 17:23:27.441  4145  4176 D A2dpStateMachine: Enter Disconnected: -2
,09-12 17:23:27.442  4145  4145 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 17:23:27.443  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:27.444  3914  3914 D BluetoothInputDevice: Proxy object connected
,09-12 17:23:27.444  4145  4145 D HidService: Received start request. Starting profile...
09-12 17:23:27.444  4145  4145 I bt_bluedroid: get_profile_interface hidhost
09-12 17:23:27.444  4145  4145 D HidService: setHidService(): set to: null
,09-12 17:23:27.444  4145  4161 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e33e5
09-12 17:23:27.444  3914  3914 D HidProfile: Bluetooth service connected
09-12 17:23:27.444  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 17:23:27.445  4145  4145 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 17:23:27.446  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:27.446  4145  4145 D HealthService: Received start request. Starting profile...
,09-12 17:23:27.448  4145  4145 I bt_bluedroid: get_profile_interface health
,09-12 17:23:27.448  4145  4145 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 17:23:27.449  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:27.450  4145  4145 D PanService: Received start request. Starting profile...
,09-12 17:23:27.450  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 17:23:27.450  4145  4145 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 17:23:27.451  4145  4145 I bt_bluedroid: get_profile_interface pan
09-12 17:23:27.451  3914  3914 D PanProfile: Bluetooth service connected
09-12 17:23:27.451  4145  4161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 17:23:27.457  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:27.458  4145  4145 D BluetoothMapService: Received start request. Starting profile...
,09-12 17:23:27.459  4145  4145 D BluetoothMapService: start()
09-12 17:23:27.459  3914  3914 D BluetoothMap: Proxy object connected
09-12 17:23:27.459  3914  3914 D MapProfile: Bluetooth service connected
09-12 17:23:27.459  3914  3914 D BluetoothMap: getConnectedDevices()
,09-12 17:23:27.460  3914  3914 D BluetoothMap: Bluetooth is Not enabled
09-12 17:23:27.461  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 17:23:27.462  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 17:23:27.462  4145  4145 D BluetoothMapAppObserver: createReceiver()
,09-12 17:23:27.463  4145  4145 D BluetoothMapAppObserver: initObservers()
09-12 17:23:27.463  4145  4145 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 17:23:27.472  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:27.472  4145  4145 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:27.472  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:27.472  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:27.474  4145  4174 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 17:23:27.474  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:27.474  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isTurningOff()=false,
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:27.475  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false,
09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false,
,09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 17:23:27.476  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:27.477  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 17:23:27.477  4145  4157 D BluetoothAdapterProperties: ScanMode =  20
09-12 17:23:27.477  4145  4157 D BluetoothAdapterProperties: State =  11
,09-12 17:23:27.478  4145  4157 D BluetoothAdapterProperties: Setting state to 12
,09-12 17:23:27.478  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 17:23:27.478  4145  4157 I BluetoothAdapterState: Entering OnState
,09-12 17:23:27.479  3914  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 17:23:27.480  1352  2140 D BluetoothPan: onBluetoothStateChange on: true
,09-12 17:23:27.481  4145  4161 D BluetoothAdapterProperties: Scan Mode:21
09-12 17:23:27.481  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 17:23:27.482  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 17:23:27.483  1352  1352 D PanProfile: Bluetooth service connected
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:27.483  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:27.483  1352  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 17:23:27.485  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-12 17:23:27.486  1352  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 17:23:27.488  1352  1352 D BluetoothInputDevice: Proxy object connected
09-12 17:23:27.488  1352  1352 D HidProfile: Bluetooth service connected
,09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:27.489  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:27.491  1984  2000 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 17:23:27.491  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 17:23:27.491  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:27.492  3914  3925 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 17:23:27.492  4145  4145 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 17:23:27.492  1352  1352 D BluetoothA2dp: Proxy object connected
09-12 17:23:27.494  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:27.496  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:27.496   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:27.497  1352  2140 D BluetoothMap: onBluetoothStateChange: up=true
09-12 17:23:27.497  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:27.498  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:27.499  4145  4145 D ObexServerSockets: Succeed to create listening sockets 
09-12 17:23:27.499  1352  1352 D BluetoothMap: Proxy object connected
,09-12 17:23:27.499  1352  1352 D MapProfile: Bluetooth service connected
09-12 17:23:27.499  4145  4145 D ObexServerSockets0: startAccept()
,09-12 17:23:27.499  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 17:23:27.499  4145  4145 D ObexServerSockets0: prepareForNewConnect()
09-12 17:23:27.501  3914  3924 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 17:23:27.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 17:23:27.501  3914  3925 D BluetoothPan: onBluetoothStateChange on: true
09-12 17:23:27.501   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 17:23:27.502   873   873 D BluetoothA2dp: Proxy object connected
,09-12 17:23:27.502  1352  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 17:23:27.502  4145  4145 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 17:23:27.503  4145  4145 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 17:23:27.504   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 17:23:27.505  1352  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:27.506  4145  4184 D ObexServerSockets0: Accepting socket connection...
,09-12 17:23:27.506   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 17:23:27.507  4145  4183 D ObexServerSockets0: Accepting socket connection...
,09-12 17:23:27.509  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:27.510  4145  4145 D BluetoothMapService: onReceive
09-12 17:23:27.510  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
09-12 17:23:27.510  4145  4145 D BluetoothMapService: STATE_ON
09-12 17:23:27.511  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:27.512  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:27.513  3914  3914 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 17:23:27.519  3914  3914 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 17:23:27.526  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 17:23:27.529  3914  3914 D BluetoothA2dp: Proxy object connected
09-12 17:23:27.531  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 17:23:27.531  4145  4145 D ObexServerSockets0: prepareForNewConnect(),
,09-12 17:23:27.535  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:27.540  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:27.551  1352  1352 D BluetoothPbap: Proxy object connected
,09-12 17:23:27.551  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-12 17:23:27.551  3914  3914 D BluetoothPbap: Proxy object connected
09-12 17:23:27.552  3914  3914 D PbapServerProfile: Bluetooth service connected
,09-12 17:23:27.561  4145  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:27.574  4145  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:27.575  4145  4192 I BtOppRfcommListener: Accept thread started.
,09-12 17:23:27.592   873   873 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.593  1984  1998 D BluetoothHeadset: Proxy object connected
09-12 17:23:27.593  1352  2140 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.593  1352  1352 D HeadsetProfile: Bluetooth service connected
09-12 17:23:27.594   873   873 D BluetoothHeadset: Proxy object connected
09-12 17:23:27.594   873   873 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.597   873   890 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.602   873   890 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.604   873   890 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.605  1352  1372 D BluetoothHeadset: Proxy object connected
,09-12 17:23:27.605  1352  1352 D HeadsetProfile: Bluetooth service connected
,09-12 17:23:27.622  3914  3925 D BluetoothHeadset: Proxy object connected
09-12 17:23:27.623  3914  3914 D HeadsetProfile: Bluetooth service connected
,09-12 17:23:28.806  1508  1508 I ConfigService: onDestroy
,09-12 17:23:30.941  4145  4157 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 17:23:30.942  4145  4157 D BluetoothAdapterProperties: Setting state to 13
,09-12 17:23:30.942  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 17:23:30.944  4145  4157 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 17:23:30.953  4145  4145 D BluetoothMapService: onReceive
09-12 17:23:30.953  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 17:23:30.954  4145  4145 D BluetoothMapService: STATE_TURNING_OFF
,09-12 17:23:30.956  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:30.958  4145  4145 D BluetoothMapService: MAP Service closeService in
09-12 17:23:30.958  4145  4145 D BluetoothMapMasInstance0: MAP Service shutdown,
09-12 17:23:30.958  4145  4145 D ObexServerSockets0: shutdown(block = true)
09-12 17:23:30.958  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:30.958  4145  4183 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:30.958  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:30.959  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 17:23:30.960  4145  4184 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 17:23:30.961  4145  4169 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 17:23:30.961  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:30.961  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:30.962  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 17:23:30.964  4145  4145 I BtOppRfcommListener: stopping Accept Thread
,09-12 17:23:30.965  4145  4192 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 17:23:30.965  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:30.965  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:30.965  4145  4192 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 17:23:30.966  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 17:23:30.966  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:30.969  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:30.970  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:30.971  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 17:23:30.971  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:30.972  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
09-12 17:23:30.972  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 17:23:30.978  4145  4145 D HeadsetService: Received stop request...Stopping profile...
,09-12 17:23:30.980  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 17:23:30.980   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:30.980  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:30.981  1984  2000 D BluetoothHeadset: Proxy object disconnected
,09-12 17:23:30.981  1352  1377 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:30.981  1352  1352 D HeadsetProfile: Bluetooth service disconnected
09-12 17:23:30.981   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:30.982  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:30.982  3914  3924 D BluetoothHeadset: Proxy object disconnected
09-12 17:23:30.982   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 17:23:30.983  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:30.984  4145  4145 D A2dpService: Received stop request...Stopping profile...
,09-12 17:23:30.985  4145  4176 D A2dpStateMachine: Exit Disconnected: -1
09-12 17:23:30.986  3914  3914 D HeadsetProfile: Bluetooth service disconnected
09-12 17:23:30.987   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 17:23:30.987  1352  1352 D BluetoothA2dp: Proxy object disconnected,
09-12 17:23:30.988  4145  4145 D HidService: Received stop request...Stopping profile...
09-12 17:23:30.988  4145  4145 D HidService: Stopping Bluetooth HidService
09-12 17:23:30.989  1352  1352 D BluetoothInputDevice: Proxy object disconnected,
09-12 17:23:30.989  1352  1352 D HidProfile: Bluetooth service disconnected
09-12 17:23:30.990  4145  4145 D HealthService: Received stop request...Stopping profile...
,09-12 17:23:30.992  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:30.992  4145  4145 D PanService: Received stop request...Stopping profile...
09-12 17:23:30.993  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 17:23:30.993  1352  1352 D PanProfile: Bluetooth service disconnected
09-12 17:23:30.993  4145  4145 V BluetoothAdapterState: isTurningOff()=true,
09-12 17:23:30.993  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:30.993  3914  3914 D BluetoothA2dp: Proxy object disconnected
09-12 17:23:30.993  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false,
09-12 17:23:30.993  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:30.993  3914  3914 D BluetoothInputDevice: Proxy object disconnected
09-12 17:23:30.993  3914  3914 D HidProfile: Bluetooth service disconnected
09-12 17:23:30.994  4145  4145 D BluetoothMapService: Received stop request...Stopping profile...
09-12 17:23:30.994  4145  4145 D BluetoothMapService: stop()
,09-12 17:23:30.995  3914  3914 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 17:23:30.995  3914  3914 D PanProfile: Bluetooth service disconnected
09-12 17:23:30.996  4145  4145 D BluetoothMapAppObserver: deinitObservers()
09-12 17:23:30.996  4145  4145 D BluetoothMapAppObserver: removeReceiver()
,09-12 17:23:30.997  1352  1352 D BluetoothMap: Proxy object disconnected,
09-12 17:23:30.998  1352  1352 D MapProfile: Bluetooth service disconnected
,09-12 17:23:30.998  3914  3914 D BluetoothMap: Proxy object disconnected
09-12 17:23:30.998  3914  3914 D MapProfile: Bluetooth service disconnected
09-12 17:23:30.998  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 17:23:30.999  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008,
09-12 17:23:30.999  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 17:23:30.999  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 17:23:30.999  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:30.999  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:30.999  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 17:23:30.999  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:30.999  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:30.999  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:30.999  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:31.001  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 17:23:31.001  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 17:23:31.001  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:31.001  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 17:23:31.001  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 17:23:31.001  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 17:23:31.001  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 17:23:31.003  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:31.003  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 17:23:31.003  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:31.003  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:31.003  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 17:23:31.004  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 17:23:31.004  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 17:23:31.004  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:31.004  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:31.004  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 17:23:31.004  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:31.005  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 17:23:31.005  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 17:23:31.005  4145  4161 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 17:23:31.007  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 17:23:31.007  4145  4145 V BluetoothAdapterState: isTurningOff()=true
,09-12 17:23:31.007  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 17:23:31.007  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:31.008  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:31.008  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 17:23:31.008  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 17:23:31.009  4145  4145 D BluetoothMapService: MAP Service closeService in
,09-12 17:23:31.009  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 17:23:31.009  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:31.009  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:31.009  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:31.010  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-12 17:23:31.010  4145  4157 D BluetoothAdapterProperties: Setting state to 15
09-12 17:23:31.010  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 17:23:31.010  4145  4157 I BluetoothAdapterState: Entering BleOnState
09-12 17:23:31.011  3914  3924 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 17:23:31.011  4145  4145 D BluetoothMapService: cleanup()
09-12 17:23:31.011  4145  4145 D BluetoothMapService: MAP Service closeService in
09-12 17:23:31.011  3914  3925 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 17:23:31.012  1352  1377 D BluetoothPan: onBluetoothStateChange on: false
09-12 17:23:31.013  1352  1352 D BluetoothPbap: Proxy object disconnected
,09-12 17:23:31.013  1352  2140 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 17:23:31.014  3914  3914 D BluetoothPbap: Proxy object disconnected
09-12 17:23:31.014  3914  3914 D PbapServerProfile: Bluetooth service disconnected
,09-12 17:23:31.013  1352  1352 D PbapServerProfile: Bluetooth service disconnected
09-12 17:23:31.016  1352  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 17:23:31.019  1984  1998 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:31.019  3914  3924 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 17:23:31.020   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:31.020  3914  3925 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 17:23:31.020  1352  1377 D BluetoothMap: onBluetoothStateChange: up=false
09-12 17:23:31.021  3914  3924 D BluetoothMap: onBluetoothStateChange: up=false
09-12 17:23:31.022   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 17:23:31.022  3914  3925 D BluetoothPan: onBluetoothStateChange on: false
09-12 17:23:31.023   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 17:23:31.023  1352  2140 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 17:23:31.023   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 17:23:31.024  1352  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 17:23:31.024  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 17:23:31.024  4145  4157 D BluetoothAdapterProperties: Setting state to 16
,09-12 17:23:31.024  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 17:23:31.025  4145  4157 D BluetoothAdapterProperties: onBleDisable
,09-12 17:23:31.025  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
09-12 17:23:31.025  4145  4158 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 17:23:31.027  4145  4167 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 17:23:31.027  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 17:23:31.028  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:31.029  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,09-12 17:23:31.030  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:31.031  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 17:23:31.031  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:31.035  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:31.036  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 17:23:31.036  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:31.037  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:31.044  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:31.234  4145  4161 I bt_hci  : shut_down
,09-12 17:23:31.243  4145  4165 I bt_vendor: low_power_mode_cb
,09-12 17:23:31.245  4145  4165 D bt_hwcfg: hw_epilog_process
,09-12 17:23:31.264  4145  4165 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-12 17:23:31.264  4145  4165 I bt_vendor: epilog_cb
09-12 17:23:31.264  4145  4165 I bt_hci  : epilog_finished_callback
,09-12 17:23:31.267  4145  4161 I bt_hci_h4: hal_close
,09-12 17:23:31.267  4145  4161 I bt_userial_vendor: device fd = 51 close
,09-12 17:23:31.397  4145  4158 D bt_stack_manager: event_shut_down_stack finished.
,09-12 17:23:31.398  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 17:23:31.407  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 17:23:31.408  4145  4157 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 17:23:31.409  4145  4145 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 17:23:31.409  4145  4145 D BtGatt.GattService: stop()
,09-12 17:23:31.409  4145  4145 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 17:23:31.418  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:31.419  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 17:23:31.419  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:31.420  4145  4145 V BluetoothAdapterState: isBleTurningOff()=true
09-12 17:23:31.421  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 17:23:31.421  4145  4157 D BluetoothAdapterProperties: Setting state to 10
,09-12 17:23:31.421  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 17:23:31.422  4145  4157 I BluetoothAdapterState: Entering OffState
,09-12 17:23:31.423   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 17:23:31.438  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 17:23:31.438  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 17:23:31.438  4145  4145 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 17:23:31.440  4145  4158 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 17:23:31.443  4145  4158 D bt_stack_manager: event_clean_up_stack finished.
,09-12 17:23:31.446  4145  4145 I art     : System.exit called, status: 0
,09-12 17:23:31.446  4145  4145 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 17:23:31.501   873  2016 I ActivityManager: Process com.android.bluetooth (pid 4145) has died
,09-12 17:23:35.941  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:35.941  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:35.946  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:35.946  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4747989 removed from the list
09-12 17:23:35.947  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:23:35.947  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:35.947  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:35.950  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:23:35.951  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37059af added. We now have 4 listener(s)
09-12 17:23:35.951  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:35.953  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:35.953  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37059af removed from the list
,09-12 17:23:35.954  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:35.954  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:23:35.954  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:23:35.956  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:23:35.957  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e83b1bc added. We now have 4 listener(s)
,09-12 17:23:35.958  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:40.969  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:41.017   873   890 I ActivityManager: Start proc 4202:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 17:23:41.150  4202  4202 D AdapterServiceConfig: Adding HeadsetService
,09-12 17:23:41.150  4202  4202 D AdapterServiceConfig: Adding A2dpService
09-12 17:23:41.150  4202  4202 D AdapterServiceConfig: Adding HidService
09-12 17:23:41.150  4202  4202 D AdapterServiceConfig: Adding HealthService
09-12 17:23:41.151  4202  4202 D AdapterServiceConfig: Adding PanService
,09-12 17:23:41.151  4202  4202 D AdapterServiceConfig: Adding GattService
09-12 17:23:41.152  4202  4202 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 17:23:41.168   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a802119:true
,09-12 17:23:41.168  4202  4202 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 17:23:41.173  4202  4202 I bt_bluedroid: init
,09-12 17:23:41.174  4202  4214 I BluetoothAdapterState: Entering OffState
,09-12 17:23:41.177  4202  4215 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 17:23:41.177  4202  4215 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 17:23:41.177  4202  4215 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 17:23:41.177  4202  4215 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 17:23:41.178  4202  4202 I bt_bluedroid: get_profile_interface socket
09-12 17:23:41.181  4202  4202 I bt_bluedroid: get_profile_interface sdp
,09-12 17:23:41.184  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 17:23:41.187  4202  4213 I bt_bluedroid: config_hci_snoop_log
,09-12 17:23:41.188  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 17:23:41.190   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 17:23:41.202  4202  4214 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 17:23:41.202  4202  4214 D BluetoothAdapterProperties: Setting state to 14
,09-12 17:23:41.203  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 17:23:41.207  4202  4214 D BluetoothBondStateMachine: make
,09-12 17:23:41.213  4202  4219 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 17:23:41.219  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:41.220  4202  4202 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 17:23:41.223  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:41.224  4202  4202 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 17:23:41.226  4202  4202 D BtGatt.GattService: Received start request. Starting profile...
09-12 17:23:41.226  4202  4202 D BtGatt.GattService: start()
,09-12 17:23:41.226  4202  4202 I bt_bluedroid: get_profile_interface gatt
09-12 17:23:41.227  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:23:41.227  4202  4202 D BtGatt.AdvertiseManager: advertise manager created
,09-12 17:23:41.241  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:41.242  4202  4202 V BluetoothAdapterState: isTurningOn()=false
,09-12 17:23:41.242  4202  4202 V BluetoothAdapterState: isBleTurningOn()=true
09-12 17:23:41.242  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:41.243  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 17:23:41.244  4202  4214 I bt_bluedroid: enable
09-12 17:23:41.244  4202  4215 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 17:23:41.245  4202  4215 I bt_hci  : start_up
,09-12 17:23:41.266  4202  4215 I bt_vendor: alloc value 0xb3a84189
09-12 17:23:41.267  4202  4215 I bt_vendor: init
,09-12 17:23:41.267  4202  4215 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 17:23:41.268  4202  4215 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 17:23:41.377  4202  4215 D bt_hci  : start_up starting async portion
,09-12 17:23:41.378  4202  4222 I bt_hci  : event_finish_startup
09-12 17:23:41.378  4202  4222 I bt_hci_h4: hal_open
,09-12 17:23:41.378  4202  4222 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 17:23:41.390  4202  4222 I bt_userial_vendor: device fd = 51 open
,09-12 17:23:41.420  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 17:23:41.451  4202  4222 D bt_hwcfg: Chipset BCM4354A2
,09-12 17:23:41.451  4202  4222 D bt_hwcfg: Target name = [BCM4354A2]
09-12 17:23:41.452  4202  4222 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 17:23:42.333  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 17:23:42.335  4202  4222 D bt_hwcfg: Settlement delay -- 100 ms
09-12 17:23:42.335  4202  4222 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 17:23:42.452  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 17:23:42.453  4202  4222 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 17:23:42.483  4202  4222 I bt_hwcfg: vendor lib fwcfg completed
,09-12 17:23:42.483  4202  4222 I bt_vendor: firmware callback
09-12 17:23:42.484  4202  4222 I bt_hci  : firmware_config_callback
,09-12 17:23:42.495  4202  4224 I bt_btu  : btu_task pending for preload complete event
,09-12 17:23:42.495  4202  4224 I bt_btu_task: Bluetooth chip preload is complete
09-12 17:23:42.495  4202  4224 I bt_btu  : btu_task received preload complete event
,09-12 17:23:42.507  4202  4224 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 17:23:42.508  4202  4224 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 17:23:42.508  4202  4224 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 17:23:42.508  4202  4224 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 17:23:42.509  4202  4224 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 17:23:42.509  4202  4224 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 17:23:42.510  4202  4224 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 17:23:42.511  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 17:23:42.512  4202  4224 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 17:23:42.512  4202  4224 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 17:23:42.513  4202  4224 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 17:23:42.516  4202  4224 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 17:23:42.517  4202  4224 I         : BTE_InitTraceLevels -- TRC_SMP
,09-12 17:23:42.517  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 17:23:42.517  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 17:23:42.651  4202  4224 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a01d9d
,09-12 17:23:42.651  4202  4224 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a01d9d 
,09-12 17:23:42.660  4202  4218 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 17:23:42.661  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 17:23:42.662  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 17:23:42.666  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 17:23:42.670  4202  4218 D BluetoothAdapterProperties: Scan Mode:20
,09-12 17:23:42.671  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 17:23:42.671  4202  4218 D bt_hci  : do_postload posting postload work item
,09-12 17:23:42.671  4202  4222 I bt_hci  : event_postload
,09-12 17:23:42.672  4202  4222 I bt_vendor: sco_config_cb
09-12 17:23:42.672  4202  4222 I bt_hci  : sco_config_callback postload finished.
,09-12 17:23:42.677  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:42.678  4202  4218 D bt_bte_conf: Device ID record 1 : primary
,09-12 17:23:42.678  4202  4218 D bt_bte_conf:   vendorId            = 000f
09-12 17:23:42.679  4202  4218 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 17:23:42.679  4202  4218 D bt_bte_conf:   product             = 1200
,09-12 17:23:42.679  4202  4218 D bt_bte_conf:   version             = 1436
,09-12 17:23:42.679  4202  4218 D bt_bte_conf:   clientExecutableURL = 
,09-12 17:23:42.679  4202  4218 D bt_bte_conf:   serviceDescription  = 
09-12 17:23:42.680  4202  4218 D bt_bte_conf:   documentationURL    = 
09-12 17:23:42.680  4202  4218 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 17:23:42.681  4202  4215 D bt_stack_manager: event_start_up_stack finished
,09-12 17:23:42.683  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:42.683  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 17:23:42.684  4202  4214 D BluetoothAdapterProperties: Setting state to 15
,09-12 17:23:42.684  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 17:23:42.685  4202  4214 I BluetoothAdapterState: Entering BleOnState
,09-12 17:23:42.690  4202  4222 I bt_vendor: low_power_mode_cb
,09-12 17:23:42.692  4202  4214 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 17:23:42.693  4202  4214 D BluetoothAdapterProperties: Setting state to 11
,09-12 17:23:42.693  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11,
,09-12 17:23:42.699  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:42.701  4202  4202 D HeadsetService: Received start request. Starting profile...
09-12 17:23:42.707  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:42.708  4202  4202 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 17:23:42.709  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:42.710  4202  4202 D HeadsetStateMachine: make
,09-12 17:23:42.712  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,09-12 17:23:42.722  4202  4202 D HeadsetStateMachine: max_hf_connections = 1
09-12 17:23:42.722  4202  4202 I bt_bluedroid: get_profile_interface handsfree
09-12 17:23:42.722  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 17:23:42.722  4202  4218 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-12 17:23:42.725  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:23:42.726  4202  4202 D A2dpService: Received start request. Starting profile...
09-12 17:23:42.727  4202  4202 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 17:23:42.727  4202  4202 I bt_bluedroid: get_profile_interface avrcp
,09-12 17:23:42.735  4202  4202 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 17:23:42.735  4202  4202 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 17:23:42.735  4202  4202 D A2dpStateMachine: make
,09-12 17:23:42.737  4202  4202 I bt_bluedroid: get_profile_interface a2dp
,09-12 17:23:42.737  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-12 17:23:42.739  4202  4202 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 17:23:42.739  4202  4234 D A2dpStateMachine: Enter Disconnected: -2
09-12 17:23:42.740  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
09-12 17:23:42.740  4202  4202 D HidService: Received start request. Starting profile...
,09-12 17:23:42.740  4202  4202 I bt_bluedroid: get_profile_interface hidhost
09-12 17:23:42.740  4202  4202 D HidService: setHidService(): set to: null
09-12 17:23:42.740  4202  4218 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e33e5
09-12 17:23:42.741  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 17:23:42.741  4202  4202 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 17:23:42.741  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:42.742  4202  4202 D HealthService: Received start request. Starting profile...
,09-12 17:23:42.744  4202  4202 I bt_bluedroid: get_profile_interface health
,09-12 17:23:42.744  4202  4202 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 17:23:42.745  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:42.746  4202  4202 D PanService: Received start request. Starting profile...
,09-12 17:23:42.746  4202  4202 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 17:23:42.746  4202  4202 I bt_bluedroid: get_profile_interface pan
,09-12 17:23:42.746  4202  4218 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 17:23:42.749  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:23:42.749  4202  4202 D BluetoothMapService: Received start request. Starting profile...
,09-12 17:23:42.749  4202  4202 D BluetoothMapService: start()
,09-12 17:23:42.752  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 17:23:42.753  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 17:23:42.753  4202  4202 D BluetoothMapAppObserver: createReceiver()
09-12 17:23:42.754  4202  4202 D BluetoothMapAppObserver: initObservers()
09-12 17:23:42.754  4202  4202 D BluetoothMapAppObserver: getEnabledAccountItems(),
,09-12 17:23:42.762  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:42.762  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:42.762  4202  4202 V BluetoothAdapterState: isTurningOn()=true
,09-12 17:23:42.762  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:42.762  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:42.765  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:42.765  4202  4231 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 17:23:42.765  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:42.765  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:42.766  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isTurningOff()=false
09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:42.767  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
09-12 17:23:42.768  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,09-12 17:23:42.768  4202  4202 V BluetoothAdapterState: isTurningOn()=true
09-12 17:23:42.768  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
09-12 17:23:42.768  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 17:23:42.768  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 17:23:42.768  4202  4214 D BluetoothAdapterProperties: ScanMode =  20
09-12 17:23:42.768  4202  4214 D BluetoothAdapterProperties: State =  11
09-12 17:23:42.769  4202  4214 D BluetoothAdapterProperties: Setting state to 12
09-12 17:23:42.769  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 17:23:42.770  4202  4214 I BluetoothAdapterState: Entering OnState
,09-12 17:23:42.770  3914  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 17:23:42.770  4202  4218 D BluetoothAdapterProperties: Scan Mode:21
,09-12 17:23:42.770  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 17:23:42.773  3914  3925 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 17:23:42.775  1352  1377 D BluetoothPan: onBluetoothStateChange on: true
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:42.775  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 17:23:42.776  1352  2140 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 17:23:42.777  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 17:23:42.777  1352  1352 D PanProfile: Bluetooth service connected
,09-12 17:23:42.778  1352  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 17:23:42.778  1352  1352 D BluetoothA2dp: Proxy object connected
,09-12 17:23:42.778  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:42.779  1984  2375 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 17:23:42.779  3914  3925 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 17:23:42.780  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 17:23:42.780   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:42.780  3914  3924 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:42.781  4202  4202 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 17:23:42.781  1352  2140 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 17:23:42.782  1352  1352 D BluetoothInputDevice: Proxy object connected
09-12 17:23:42.782  1352  1352 D HidProfile: Bluetooth service connected
,09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:42.782  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:42.782  3914  3925 D BluetoothMap: onBluetoothStateChange: up=true
09-12 17:23:42.783  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 17:23:42.783   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:42.784  3914  3924 D BluetoothPan: onBluetoothStateChange on: true
09-12 17:23:42.785  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 17:23:42.785  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 17:23:42.786   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 17:23:42.786   873   873 D BluetoothA2dp: Proxy object connected
09-12 17:23:42.786  4202  4202 D ObexServerSockets: Succeed to create listening sockets 
09-12 17:23:42.786  4202  4202 D ObexServerSockets0: startAccept()
,09-12 17:23:42.787  1352  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 17:23:42.787  4202  4202 D ObexServerSockets0: prepareForNewConnect()
09-12 17:23:42.788   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:42.788  3914  3914 D BluetoothInputDevice: Proxy object connected
09-12 17:23:42.788  1352  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 17:23:42.788  3914  3914 D HidProfile: Bluetooth service connected
09-12 17:23:42.790  4202  4202 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 17:23:42.790  4202  4202 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 17:23:42.791  4202  4242 D ObexServerSockets0: Accepting socket connection...
09-12 17:23:42.791  4202  4241 D ObexServerSockets0: Accepting socket connection...
09-12 17:23:42.793  1352  1352 D BluetoothMap: Proxy object connected
09-12 17:23:42.793  1352  1352 D MapProfile: Bluetooth service connected
,09-12 17:23:42.793  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 17:23:42.793   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 17:23:42.795  4202  4202 D BluetoothMapService: onReceive
09-12 17:23:42.795  4202  4202 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 17:23:42.795  4202  4202 D BluetoothMapService: STATE_ON
,09-12 17:23:42.795  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:42.796  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:23:42.797  3914  3914 D BluetoothA2dp: Proxy object connected
,09-12 17:23:42.800  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 17:23:42.800  3914  3914 D PanProfile: Bluetooth service connected
,09-12 17:23:42.800  3914  3914 D BluetoothMap: Proxy object connected
,09-12 17:23:42.800  3914  3914 D MapProfile: Bluetooth service connected
09-12 17:23:42.800  3914  3914 D BluetoothMap: getConnectedDevices()
,09-12 17:23:42.805  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 17:23:42.810  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 17:23:42.811  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 17:23:42.818  3914  3914 D BluetoothPbap: Proxy object connected
,09-12 17:23:42.818  3914  3914 D PbapServerProfile: Bluetooth service connected
,09-12 17:23:42.820  1352  1352 D BluetoothPbap: Proxy object connected
09-12 17:23:42.820  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-12 17:23:42.822  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 17:23:42.822  4202  4202 D ObexServerSockets0: prepareForNewConnect()
,09-12 17:23:42.826  4202  4246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:42.841  4202  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:23:42.844  4202  4250 I BtOppRfcommListener: Accept thread started.
,09-12 17:23:42.881   873   873 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.881   873   890 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.885  3914  3924 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.885  1984  2136 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.885   873   890 D BluetoothHeadset: Proxy object connected
09-12 17:23:42.885  3914  3914 D HeadsetProfile: Bluetooth service connected
09-12 17:23:42.886  1352  2140 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.886  1352  1352 D HeadsetProfile: Bluetooth service connected
09-12 17:23:42.886   873   873 D BluetoothHeadset: Proxy object connected
09-12 17:23:42.886  3914  4239 D BluetoothHeadset: Proxy object connected
,09-12 17:23:42.886   873   873 D BluetoothHeadset: Proxy object connected
09-12 17:23:42.887   873   890 D BluetoothHeadset: Proxy object connected
09-12 17:23:42.887  3914  3914 D HeadsetProfile: Bluetooth service connected
,09-12 17:23:42.890  1352  1377 D BluetoothHeadset: Proxy object connected
09-12 17:23:42.890  1352  1352 D HeadsetProfile: Bluetooth service connected
,09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:45.988  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:45.995  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:45.997  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:23:45.998  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e83b1bc removed from the list
,09-12 17:23:45.998  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:45.998  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:45.999  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:46.001  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:23:46.001  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a22545 added. We now have 4 listener(s)
09-12 17:23:46.002  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:23:46.006   873  1721 D WifiService: setWifiEnabled: false pid=3853, uid=10000
,09-12 17:23:46.006   873  1721 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:51.019  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:23:51.021   873  2103 D WifiService: setWifiEnabled: true pid=3853, uid=10000
,09-12 17:23:51.021   873  2103 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 17:23:51.035   873  1313 D WifiConfigStore: Loading config and enabling all networks 
,09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:51.053  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:51.059  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 17:23:51.072  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 17:23:51.076  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 17:23:51.078   873  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-12 17:23:51.079   873  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 17:23:51.080   873  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 17:23:51.080   873  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 17:23:51.081   873  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 17:23:51.081   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 17:23:51.081   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 17:23:51.094   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 17:23:51.095   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 17:23:51.095   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:51.147   873  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 17:23:51.147   873  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 17:23:51.149   873  1313 E native  : do suspend true
,09-12 17:23:51.170   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:51.186   873  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 17:23:51.198   873  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 17:23:52.358   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 17:23:52.493   873  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.06 rxSuccessRate=13.56 delta 1000 -> 994
09-12 17:23:52.494   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 17:23:52.494   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:52.512   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 17:23:52.552   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 17:23:52.553  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 17:23:52.977  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 17:23:53.023  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 17:23:53.025  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 17:23:53.032   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 17:23:53.049   873  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 17:23:53.050   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 17:23:53.051   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 17:23:53.073   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 17:23:53.095   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:53.096   873  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 17:23:53.112   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 17:23:53.136   873  4261 D DhcpClient: Receive thread started
,09-12 17:23:53.238   873  1313 E native  : do suspend false
,09-12 17:23:53.267   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 17:23:53.282   873  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-12 17:23:53.283   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-12 17:23:53.288   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 17:23:53.302   873  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 17:23:53.303   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 17:23:53.310   372   872 D CommandListener: Setting iface cfg
,09-12 17:23:53.320   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 17:23:53.323   873  1880 D DhcpClient: Scheduling renewal in 86399s
,09-12 17:23:53.324   873  1313 E native  : do suspend true
,09-12 17:23:53.343   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 17:23:53.346   873  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 17:23:53.348   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 17:23:53.349   873  1315 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 17:23:53.364   873  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 17:23:53.401   873  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 17:23:53.401   873  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 17:23:53.403   873  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 17:23:53.404   873  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 17:23:53.406   873  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 17:23:53.415   873  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 17:23:53.421   873  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 17:23:53.421   873  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-12 17:23:53.421   873  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-12 17:23:53.421   873  1315 D ConnectivityService:    accepting network in place of null
,09-12 17:23:53.423   873  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 17:23:53.423   873  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 17:23:53.425   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 17:23:53.436   873  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=397182, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 17:23:53.471   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:53.505   873  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 17:23:53.513   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 17:23:53.521   873  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 17:23:53.521   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:53.524   873  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 17:23:53.528   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:53.547  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:23:53.549  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:53.556  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 17:23:53.559  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:53.563  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 17:23:53.568  1715  1715 D SystemUpdateService: onCreate
,09-12 17:23:53.571   873  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 15:23:53 GMT], X-Android-Received-Millis=[1473693833570], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473693833547]}
,09-12 17:23:53.572   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 17:23:53.572   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 17:23:53.572   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 17:23:53.572  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 17:23:53.573   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 17:23:53.596  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 17:23:53.599  1715  2407 I iu.UploadsManager: num queued entries: 0
,09-12 17:23:53.599  1715  2407 I iu.UploadsManager: num updated entries: 0
,09-12 17:23:53.605  1715  4271 I SystemUpdateService: active receiver: enabled
,09-12 17:23:53.606  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 17:23:53.607  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 17:23:53.610  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 17:23:53.620  3967  3967 D SprintDMHelper: simOperator: 
,09-12 17:23:53.620  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 17:23:53.625  1715  4273 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 17:23:53.628  1715  4273 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 17:23:53.645  1715  4273 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 17:23:53.650  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:23:53.652  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:23:53.659  1715  2407 I iu.SyncManager: NEXT; no task
,09-12 17:23:53.665  1715  4271 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 17:23:53.675  1715  4271 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 17:23:53.675  1715  4271 I SystemUpdateService: now status is 0 (complete)
09-12 17:23:53.675  1715  4271 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 17:23:53.675  1715  4271 I SystemUpdateService: file has been verified
09-12 17:23:53.676  1715  4271 I SystemUpdateService: OTA package size = 12249756
,09-12 17:23:53.684  1715  4271 I SystemUpdateService: showing system update notification
,09-12 17:23:53.693  1508  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-12 17:23:53.693  1508  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 17:23:53.693  1508  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 17:23:53.693  1508  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:23:53.712  1715  4273 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 17:23:53.722  1715  1715 D SystemUpdateService: onDestroy
,09-12 17:23:53.754  2213  4276 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 17:23:53.841  1508  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 17:23:53.842  1508  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 17:23:53.842  1508  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 17:23:53.842  1508  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:23:53.858  3550  4282 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 17:23:53.858  3550  4282 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jdm.a(PG:82)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jcs.o(PG:406)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jcn.a(PG:1379)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jcs.i(PG:143)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at blb.a(PG:3937)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at czp.a(PG:18188)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at czp.a(PG:9087)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at czq.run(PG:1686)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:23:53.858  3550  4282 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jdj.a(PG:4091)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jdj.a(PG:1125)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jdm.a(PG:77)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	... 12 more
09-12 17:23:53.858  3550  4282 E HttpOperation: Caused by: faj: BadAuthentication
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at fal.a(PG:38)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	at jdj.a(PG:4089)
09-12 17:23:53.858  3550  4282 E HttpOperation: 	... 14 more
,09-12 17:23:54.077  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 17:23:54.077  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 17:23:54.077  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 17:23:54.077  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:23:54.098  3550  4289 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 17:23:54.098  3550  4289 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jdm.a(PG:82)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jcs.o(PG:406)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jcn.a(PG:1379)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jcs.i(PG:143)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at blb.a(PG:3937)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at czp.a(PG:18188)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at czp.a(PG:9081)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at czq.run(PG:1686)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:23:54.098  3550  4289 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jdj.a(PG:4091)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jdj.a(PG:1125)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jdm.a(PG:77)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	... 12 more
09-12 17:23:54.098  3550  4289 E HttpOperation: Caused by: faj: BadAuthentication
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at fal.a(PG:38)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	at jdj.a(PG:4089)
09-12 17:23:54.098  3550  4289 E HttpOperation: 	... 14 more
,09-12 17:23:54.155  1508  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 17:23:54.155  1508  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 17:23:54.155  1508  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 17:23:54.155  1508  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:23:54.172  3550  4289 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 17:23:54.172  3550  4289 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jdm.a(PG:82)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jcs.o(PG:406)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jcn.a(PG:1379)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jcs.i(PG:143)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at hec.a(PG:42)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at hee.a(PG:102)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at czr.a(PG:65)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at kka.a(PG:108)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at czp.a(PG:19176)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at czp.a(PG:9081)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at czq.run(PG:1686)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:23:54.172  3550  4289 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jdj.a(PG:4091)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jdj.a(PG:1125)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jdm.a(PG:77)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	... 15 more
09-12 17:23:54.172  3550  4289 E HttpOperation: Caused by: faj: BadAuthentication
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at fal.a(PG:38)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	at jdj.a(PG:4089)
09-12 17:23:54.172  3550  4289 E HttpOperation: 	... 17 more
,09-12 17:23:54.172  3550  4289 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 17:23:54.172  3550  4289 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jcs.i(PG:143)
,09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at hec.a(PG:42)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at hee.a(PG:102)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at czr.a(PG:65)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at kka.a(PG:108)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	... 15 more
09-12 17:23:54.172  3550  4289 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at fal.a(PG:38)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 17:23:54.172  3550  4289 E ExperimentLoader: 	... 17 more
,09-12 17:23:54.363   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 247348, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 17:23:54.521   873  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:23:56.048  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:23:56.056  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:23:56.058  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:23:56.059  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a22545 removed from the list
09-12 17:23:56.059  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:23:56.059  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:23:56.059  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:23:56.072  3853  4290 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-12 17:23:56.072  3853  4290 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 17:23:59.079  3853  4291 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 17:23:59.080  3853  4290 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 17:23:59.081  3853  4291 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 17:23:59.081  3853  4290 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 17:23:59.083  3853  4290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 17:23:59.083  3853  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 17:23:59.085  3853  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 17:23:59.085  3853  4290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 17:23:59.087  3853  4291 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 17:23:59.087  3853  4290 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 17:23:59.095  3853  4293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
,09-12 17:23:59.098  3853  4296 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
,09-12 17:23:59.100  3853  4296 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
,09-12 17:23:59.101  3853  4294 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: OutgoingSocketThread/Sender)
,09-12 17:23:59.101  3853  4295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Receiver)
,09-12 17:23:59.101  3853  4296 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-12 17:23:59.102  3853  4296 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 17:23:59.102  3853  4295 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: IncomingSocketThread/Receiver)
09-12 17:23:59.103  3853  4295 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 17:23:59.103  3853  4295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 17:24:01.429   873  1315 D ConnectivityService: handlePromptUnvalidated 102
,09-12 17:24:02.079  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 17:24:02.081  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 17:24:02.090  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4762676 Bundle[{}]
,09-12 17:24:02.090  3853  3899 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 17:24:02.090  3853  3899 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 17:24:02.091  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 17:24:02.091  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 17:24:02.092  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 17:24:02.093  3853  3899 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 17:24:02.097  3853  3899 I System.out: Running OutgoingSocketThread
,09-12 17:24:02.100  3853  4297 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-12 17:24:02.100  3853  4297 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 17:24:05.109  3853  4298 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-12 17:24:05.110  3853  4298 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 17:24:05.110  3853  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 17:24:05.110  3853  4297 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 17:24:05.111  3853  4297 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 17:24:05.111  3853  4297 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 17:24:05.111  3853  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 17:24:05.112  3853  4297 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 17:24:05.113  3853  4298 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 17:24:05.119  3853  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: OutgoingSocketThread/Sender)
,09-12 17:24:05.121  3853  4297 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 17:24:05.126  3853  4300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Sender)
,09-12 17:24:05.129  3853  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Receiver)
,09-12 17:24:05.129  3853  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Receiver)
09-12 17:24:05.130  3853  4302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: IncomingSocketThread/Receiver)
09-12 17:24:05.130  3853  4302 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 17:24:05.131  3853  4302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 17:24:05.131  3853  4303 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: OutgoingSocketThread/Receiver)
,09-12 17:24:05.131  3853  4303 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 17:24:05.132  3853  4303 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 17:24:08.112  3853  3899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,09-12 17:24:08.114  3853  3899 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 17:24:08.115  3853  3899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,09-12 17:24:08.120  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 17:24:08.120  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3149a added. We now have 3 listener(s)
09-12 17:24:08.122  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 17:24:08.122  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 17:24:08.122  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 17:24:08.123  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:24:08.123  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972e1cb added. We now have 4 listener(s)
09-12 17:24:08.123  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 17:24:08.124  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:24:08.129  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:24:08.138  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:24:08.142  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:24:08.142  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:24:08.143  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 17:24:08.143  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:24:08.143  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:24:08.143  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:08.143  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:24:08.143  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:24:08.144  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 17:24:08.144  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3149a removed from the list
09-12 17:24:08.144  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:24:08.145  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972e1cb removed from the list
09-12 17:24:08.147  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:24:08.150  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:24:08.151  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 17:24:08.151  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:08.152  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:08.152  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:08.153  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:08.153  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:24:08.153  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:08.153  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972e1cb not in the list
09-12 17:24:08.153  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:08.153  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:08.154  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:24:08.154  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:08.154  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:08.155  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972e1cb not in the list
,09-12 17:24:08.155  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:24:08.155  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:08.155  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:08.155  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3149a not in the list
09-12 17:24:08.156  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:24:08.156  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d0c1 added. We now have 3 listener(s)
09-12 17:24:08.157  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 17:24:08.158  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 17:24:08.158  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 17:24:08.158  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:24:08.158  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32de066 added. We now have 4 listener(s)
09-12 17:24:08.158  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 17:24:08.159  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 17:24:08.161  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:24:08.165  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:24:08.167  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:08.168  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:24:08.169  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 17:24:08.169  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 17:24:08.169  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 17:24:08.169  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 17:24:08.170  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 17:24:08.170  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 17:24:08.177  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:24:08.179  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 17:24:08.179  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 17:24:08.184  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 17:24:08.184  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 17:24:08.184  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 17:24:08.187  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 17:24:08.187  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 17:24:08.188  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 17:24:08.189  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:24:08.193  4202  4240 D BtGatt.GattService: registerClient() - UUID=d6ed9e31-2498-4433-b023-2ea3f43f0bcd
,09-12 17:24:08.194  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=d6ed9e31-2498-4433-b023-2ea3f43f0bcd, clientIf=5
,09-12 17:24:08.197  3853  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 17:24:08.200  4202  4232 D BtGatt.GattService: start scan with filters
,09-12 17:24:08.209  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 17:24:08.209  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 17:24:08.209  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 17:24:08.210  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 17:24:08.210  4202  4221 D BtGatt.ScanManager: handling starting scan
,09-12 17:24:08.212  4202  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d819aa
,09-12 17:24:08.219  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:24:08.219  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 17:24:08.219  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:24:08.223  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 17:24:08.226  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 17:24:08.226  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.227  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 17:24:08.228  3853  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 17:24:08.228  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 17:24:08.229  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 17:24:08.229  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:24:08.229  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 17:24:08.229  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:24:08.229  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 17:24:08.229  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 17:24:08.229  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 17:24:08.229  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 17:24:08.230  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 17:24:08.230  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:24:08.231  4202  4232 D BtGatt.GattService: stopScan() - queue size =1
,09-12 17:24:08.232  4202  4213 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 17:24:08.232  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 17:24:08.232  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 17:24:08.233  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 17:24:08.233  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 17:24:08.233  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 17:24:08.234  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:24:08.234  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 17:24:08.234  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 17:24:08.234  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 17:24:08.235  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:24:08.236  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:24:08.236  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 17:24:08.236  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 17:24:08.244  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 17:24:08.244  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.244  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
09-12 17:24:08.244  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 17:24:08.268  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 17:24:08.268  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.281  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 17:24:08.281  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.294  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 17:24:08.295  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.295  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
,09-12 17:24:08.312  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 17:24:08.312  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:24:08.313  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:24:08.331  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 17:24:08.331  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:08.737  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:24:08.738  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:24:08.738  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:24:11.237  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:24:11.238  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:24:11.238  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 17:24:11.239  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:24:11.240  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:11.240  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:24:11.240  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 17:24:11.241  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d0c1 removed from the list
09-12 17:24:11.241  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:11.241  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32de066 removed from the list
09-12 17:24:11.241  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:24:11.242  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:11.243  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:11.244  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:11.247  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:11.247  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:24:11.248  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:11.248  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32de066 not in the list
09-12 17:24:11.248  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:11.249  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:11.252  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:24:11.252  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:11.252  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:24:11.252  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32de066 not in the list
09-12 17:24:11.253  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:11.253  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:24:11.253  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:11.254  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@844d0c1 not in the list
09-12 17:24:11.255  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:24:11.255  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbbf43 added. We now have 3 listener(s)
,09-12 17:24:11.258  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 17:24:11.258  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 17:24:11.258  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 17:24:11.258  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 17:24:11.258  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa909c0 added. We now have 4 listener(s)
09-12 17:24:11.258  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 17:24:11.259  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:24:11.261  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:24:11.268  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:24:11.270  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:24:11.271  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:24:11.273  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 17:24:11.273  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:24:11.274  3853  3899 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 17:24:11.274  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-12 17:24:11.276  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:24:11.277  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 17:24:11.277  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-12 17:24:11.277  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 17:24:11.278  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 17:24:11.278  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 17:24:11.279  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 17:24:11.279  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 17:24:11.279  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 17:24:11.281  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 17:24:11.281  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 17:24:11.281  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:11.281  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 17:24:11.284  3853  4304 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 17:24:11.288  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 17:24:11.288  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 17:24:11.289  3853  4304 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 17:24:11.292  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 17:24:11.293  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 17:24:11.293  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 17:24:11.296  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 17:24:11.296  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 17:24:11.297  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-12 17:24:11.298  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 17:24:11.298  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 17:24:11.298  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-12 17:24:11.299  3853  3899 D BluetoothAdapter: STATE_ON
,09-12 17:24:11.302  4202  4240 D BtGatt.GattService: registerClient() - UUID=0ed9c0a0-c15b-472a-9e24-1d57e23cca8a
,09-12 17:24:11.302  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=0ed9c0a0-c15b-472a-9e24-1d57e23cca8a, clientIf=5
09-12 17:24:11.302  3853  3863 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
,09-12 17:24:11.305  4202  4220 D BtGatt.AdvertiseManager: message : 0
,09-12 17:24:11.309  4202  4220 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 17:24:11.329  4202  4218 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 17:24:11.343  4202  4218 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 17:24:11.346  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 17:24:11.347  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 17:24:11.352  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 17:24:11.355  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 17:24:11.355  3853  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 17:24:11.356  3853  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-12 17:24:11.356  3853  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 17:24:11.356  3853  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 17:24:11.356  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-12 17:24:11.361  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 17:24:11.366  3853  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 17:24:11.366  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 17:24:11.868  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 17:24:11.868  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 17:24:11.868  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:24:14.362  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:24:14.363  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-12 17:24:14.363  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 17:24:14.364  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 17:24:14.364  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 17:24:14.365  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 17:24:14.367  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 17:24:14.367  3853  4304 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-12 17:24:14.367  3853  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 17:24:14.368  3853  4304 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 17:24:14.368  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:24:14.368  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 17:24:14.368  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 17:24:14.368  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 17:24:14.368  3853  4304 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 17:24:14.369  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 17:24:14.369  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 17:24:14.372  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:24:14.372  3853  3899 D BluetoothLeScanner: could not find callback wrapper
,09-12 17:24:14.373  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 17:24:14.373  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 17:24:14.376  4202  4220 D BtGatt.AdvertiseManager: message : 1
,09-12 17:24:14.378  4202  4220 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 17:24:14.386  4202  4218 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 17:24:14.387  4202  4218 D BtGatt.GattService: Client app is not null!
,09-12 17:24:14.389  4202  4213 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 17:24:14.390  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 17:24:14.390  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 17:24:14.390  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 17:24:14.390  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 17:24:14.391  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 17:24:14.393  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 17:24:14.393  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 17:24:14.393  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 17:24:14.394  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:24:14.398  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:24:14.398  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 17:24:14.398  3853  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 17:24:14.399  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:24:14.399  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 17:24:14.399  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:14.399  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:14.399  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 17:24:14.399  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:24:14.400  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 17:24:14.400  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbbf43 removed from the list
09-12 17:24:14.400  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:14.400  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa909c0 removed from the list
09-12 17:24:14.400  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:24:14.400  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:14.401  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:14.401  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:14.403  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:14.403  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:24:14.403  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:14.403  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa909c0 not in the list
09-12 17:24:14.403  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:14.403  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:14.405  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:24:14.405  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:14.405  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:14.405  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa909c0 not in the list
09-12 17:24:14.406  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:24:14.406  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:14.406  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:14.406  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbbf43 not in the list
,09-12 17:24:14.408  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:24:14.408  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fe9b5 added. We now have 3 listener(s)
,09-12 17:24:14.413  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 17:24:14.413  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 17:24:14.413  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 17:24:14.414  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:24:14.414  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9d84a added. We now have 4 listener(s)
09-12 17:24:14.414  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 17:24:14.415  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:24:14.419  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:24:14.425  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:24:14.427  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 17:24:14.427  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:24:14.427  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 17:24:14.427  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 17:24:14.427  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 17:24:14.427  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 17:24:14.427  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 17:24:14.430  3853  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 17:24:14.430  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 17:24:14.431  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:24:14.434  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:24:14.435  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 17:24:14.435  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 17:24:14.436  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 17:24:14.438  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 17:24:14.439  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 17:24:14.439  3853  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 17:24:14.439  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:24:14.442  4202  4213 D BtGatt.GattService: registerClient() - UUID=9373cfd6-aaf0-4cb3-96d8-f73347c13041
,09-12 17:24:14.443  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=9373cfd6-aaf0-4cb3-96d8-f73347c13041, clientIf=5
09-12 17:24:14.443  3853  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 17:24:14.444  4202  4232 D BtGatt.GattService: start scan with filters
,09-12 17:24:14.447  4202  4221 D BtGatt.ScanManager: handling starting scan
09-12 17:24:14.448  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 17:24:14.448  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 17:24:14.448  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 17:24:14.448  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 17:24:14.451  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 17:24:14.451  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 17:24:14.451  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 17:24:14.453  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 17:24:14.462  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 17:24:14.462  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:14.462  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 17:24:14.474  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 17:24:14.474  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:24:14.474  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
09-12 17:24:14.475  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 17:24:14.503  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 17:24:14.504  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:14.524  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 17:24:14.525  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:14.900  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:24:14.951  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 17:24:14.952  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 17:24:14.952  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 17:24:16.030  4202  4202 D BtGatt.ScanManager: awakened up at time 419775
,09-12 17:24:16.033  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 17:24:16.086  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-12 17:24:16.086  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:16.087  4202  4218 D BtGatt.GattService: current time is 419832780788
09-12 17:24:16.088  4202  4218 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -99, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -92, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -99, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 17:24:16.092  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 17:24:16.094  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 17:24:16.095  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 17:24:16.096  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 17:24:16.096  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 17:24:16.097  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 17:24:17.465  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:24:17.465  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:24:17.466  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 17:24:17.466  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.467  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 17:24:17.467  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 17:24:17.467  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 17:24:17.467  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 17:24:17.468  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 17:24:17.468  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 17:24:17.468  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 17:24:17.471  3853  3899 D BluetoothAdapter: STATE_ON
09-12 17:24:17.473  4202  4230 D BtGatt.GattService: stopScan() - queue size =1
09-12 17:24:17.476  4202  4213 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 17:24:17.477  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 17:24:17.478  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 17:24:17.478  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 17:24:17.479  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 17:24:17.479  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 17:24:17.483  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 17:24:17.487  4202  4202 D BtGatt.ScanManager: awakened up at time 421232
,09-12 17:24:17.484  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 17:24:17.489  3853  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 17:24:17.490  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 17:24:17.494  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 17:24:17.498  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 17:24:17.498  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 17:24:17.498  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 17:24:17.499  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 17:24:17.499  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.500  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:24:17.500  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 17:24:17.501  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 17:24:17.501  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fe9b5 removed from the list
09-12 17:24:17.501  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:24:17.501  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
,09-12 17:24:17.501  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:24:17.502  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9d84a removed from the list
09-12 17:24:17.502  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:24:17.502  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:17.504  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.504  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:17.507  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 17:24:17.507  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:24:17.507  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:17.507  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9d84a not in the list
,09-12 17:24:17.508  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.508  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:17.510  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 17:24:17.511  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 17:24:17.511  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 17:24:17.511  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 17:24:17.511  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:17.511  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:17.512  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9d84a not in the list
09-12 17:24:17.512  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:17.512  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.512  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:17.513  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fe9b5 not in the list
,09-12 17:24:17.514  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 17:24:17.515  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f1f097 added. We now have 3 listener(s)
,09-12 17:24:17.521  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 17:24:17.521  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 17:24:17.521  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 17:24:17.521  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 17:24:17.521  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ba284 added. We now have 4 listener(s)
,09-12 17:24:17.522  3853  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 17:24:17.522  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 17:24:17.526  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 17:24:17.532  3853  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 17:24:17.535  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-12 17:24:17.535  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 17:24:17.535  4202  4218 D BtGatt.GattService: current time is 421281076248
,09-12 17:24:17.535  4202  4218 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -98, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 17:24:17.536  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 17:24:17.536  4202  4218 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 17:24:17.536  3853  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 17:24:17.537  3853  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 17:24:17.538  3853  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 17:24:17.538  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 17:24:17.538  3853  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 17:24:17.538  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:17.538  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.539  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 17:24:17.539  3853  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 17:24:17.539  3853  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f1f097 removed from the list
,09-12 17:24:17.539  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:17.539  3853  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ba284 removed from the list
,09-12 17:24:17.541  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 17:24:17.546  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 17:24:17.546  3853  3899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 17:24:17.546  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:17.547  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.547  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:17.548  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:17.549  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:24:17.549  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 17:24:17.549  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ba284 not in the list
09-12 17:24:17.549  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 17:24:17.550  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 17:24:17.552  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 17:24:17.552  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 17:24:17.552  3853  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 17:24:17.552  3853  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ba284 not in the list
09-12 17:24:17.552  3853  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 17:24:17.552  3853  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 17:24:17.552  3853  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 17:24:17.552  3853  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f1f097 not in the list
09-12 17:24:17.553  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 17:24:17.554  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 17:24:17.554  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 17:24:17.554  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 17:24:17.554  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 17:24:17.554  3853  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 17:24:17.999  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 17:24:19.572  3853  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,09-12 17:24:21.570  3853  3899 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 457
,09-12 17:24:21.571  3853  3899 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 457, name: My test thread name)
,09-12 17:24:21.579  3853  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,09-12 17:24:21.580  3853  4307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: My test thread name)
09-12 17:24:21.580  3853  4307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 17:24:21.585  3853  3899 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 17:24:21.596  3853  4306 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-12 17:24:21.596  3853  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
09-12 17:24:21.598  3853  4308 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 462, thread name: My test thread name): Test exception.
,09-12 17:24:21.598  3853  4308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 17:24:21.609  3853  3899 I jxcore-log: Total number of executed tests:  82
09-12 17:24:21.609  3853  3899 I jxcore-log: 
,09-12 17:24:21.610  3853  3899 I jxcore-log: Number of passed tests:  82
09-12 17:24:21.610  3853  3899 I jxcore-log: 
,09-12 17:24:21.612  3853  3899 I jxcore-log: Number of failed tests:  0
09-12 17:24:21.612  3853  3899 I jxcore-log: 
,09-12 17:24:21.613  3853  3899 I jxcore-log: Number of ignored tests:  0
09-12 17:24:21.613  3853  3899 I jxcore-log: 
,09-12 17:24:21.615  3853  3899 I jxcore-log: Total duration:  101353
09-12 17:24:21.615  3853  3899 I jxcore-log: 
,09-12 17:24:21.628  3853  3899 I jxcore-log: Unit Test app is loaded
09-12 17:24:21.628  3853  3899 I jxcore-log: 
,09-12 17:24:21.639  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.639  3853  3899 I jxcore-log: 
,09-12 17:24:21.645  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.645  3853  3899 I jxcore-log: 
,09-12 17:24:21.646  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.646  3853  3899 I jxcore-log: 
,09-12 17:24:21.648  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.648  3853  3899 I jxcore-log: 
,09-12 17:24:21.651  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 17:24:21.651  3853  3899 I jxcore-log: 
,09-12 17:24:21.654  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.654  3853  3899 I jxcore-log: 
,09-12 17:24:21.657  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.657  3853  3899 I jxcore-log: 
,09-12 17:24:21.658  3853  3853 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 17:24:21.661  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.661  3853  3899 I jxcore-log: 
,09-12 17:24:21.662  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 17:24:21.662  3853  3899 I jxcore-log: 
,09-12 17:24:21.663  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.663  3853  3899 I jxcore-log: 
,09-12 17:24:21.665  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.665  3853  3899 I jxcore-log: 
,09-12 17:24:21.666  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.666  3853  3899 I jxcore-log: 
09-12 17:24:21.667  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.667  3853  3899 I jxcore-log: 
,09-12 17:24:21.668  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.668  3853  3899 I jxcore-log: 
,09-12 17:24:21.669  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.669  3853  3899 I jxcore-log: 
,09-12 17:24:21.672  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.672  3853  3899 I jxcore-log: 
,09-12 17:24:21.673  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.673  3853  3899 I jxcore-log: 
,09-12 17:24:21.673  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.673  3853  3899 I jxcore-log: 
09-12 17:24:21.674  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.674  3853  3899 I jxcore-log: 
,09-12 17:24:21.675  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.675  3853  3899 I jxcore-log: 
,09-12 17:24:21.675  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.675  3853  3899 I jxcore-log: 
09-12 17:24:21.676  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.676  3853  3899 I jxcore-log: 
,09-12 17:24:21.677  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.677  3853  3899 I jxcore-log: 
09-12 17:24:21.677  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.677  3853  3899 I jxcore-log: 
,09-12 17:24:21.678  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.678  3853  3899 I jxcore-log: 
09-12 17:24:21.678  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.678  3853  3899 I jxcore-log: 
,09-12 17:24:21.679  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.679  3853  3899 I jxcore-log: 
09-12 17:24:21.680  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.680  3853  3899 I jxcore-log: 
09-12 17:24:21.680  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.680  3853  3899 I jxcore-log: 
,09-12 17:24:21.681  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.681  3853  3899 I jxcore-log: 
09-12 17:24:21.681  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-12 17:24:21.681  3853  3899 I jxcore-log: 
09-12 17:24:21.682  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.682  3853  3899 I jxcore-log: 
09-12 17:24:21.682  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.682  3853  3899 I jxcore-log: 
09-12 17:24:21.683  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.683  3853  3899 I jxcore-log: 
09-12 17:24:21.684  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.684  3853  3899 I jxcore-log: 
09-12 17:24:21.685  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.685  3853  3899 I jxcore-log: 
09-12 17:24:21.688  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.688  3853  3899 I jxcore-log: 
,09-12 17:24:21.690  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.690  3853  3899 I jxcore-log: 
,09-12 17:24:21.692  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.692  3853  3899 I jxcore-log: 
,09-12 17:24:21.694  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.694  3853  3899 I jxcore-log: 
,09-12 17:24:21.696  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 17:24:21.696  3853  3899 I jxcore-log: 
,09-12 17:24:21.698  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.698  3853  3899 I jxcore-log: 
,09-12 17:24:21.700  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 17:24:21.700  3853  3899 I jxcore-log: 
,09-12 17:24:21.702  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.702  3853  3899 I jxcore-log: 
,09-12 17:24:21.705  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.705  3853  3899 I jxcore-log: 
,09-12 17:24:21.707  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.707  3853  3899 I jxcore-log: 
,09-12 17:24:21.710  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.710  3853  3899 I jxcore-log: 
,09-12 17:24:21.711  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.711  3853  3899 I jxcore-log: 
,09-12 17:24:21.712  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.712  3853  3899 I jxcore-log: 
09-12 17:24:21.713  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.713  3853  3899 I jxcore-log: 
,09-12 17:24:21.713  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 17:24:21.713  3853  3899 I jxcore-log: 
09-12 17:24:21.714  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.714  3853  3899 I jxcore-log: 
,09-12 17:24:21.715  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.715  3853  3899 I jxcore-log: 
09-12 17:24:21.715  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 17:24:21.715  3853  3899 I jxcore-log: 
,09-12 17:24:21.716  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 17:24:21.716  3853  3899 I jxcore-log: 
09-12 17:24:21.717  3853  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 17:24:21.717  3853  3899 I jxcore-log: 
,09-12 17:24:21.722  3853  3899 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-12 17:24:21.722  3853  3899 I jxcore-log:   bluetooth: 'on',
09-12 17:24:21.722  3853  3899 I jxcore-log:   wifi: 'on',
09-12 17:24:21.722  3853  3899 I jxcore-log:   cellular: 'doNotCare',
09-12 17:24:21.722  3853  3899 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 17:24:21.722  3853  3899 I jxcore-log: 
,09-12 17:24:21.728  3853  3899 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-12 17:24:21.728  3853  3899 I jxcore-log:   bluetooth: 'on',
09-12 17:24:21.728  3853  3899 I jxcore-log:   wifi: 'on',
09-12 17:24:21.728  3853  3899 I jxcore-log:   cellular: 'doNotCare',
09-12 17:24:21.728  3853  3899 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 17:24:21.728  3853  3899 I jxcore-log: 
,09-12 17:24:21.729  3853  3899 I jxcore-log: My device name is: motorola-Nexus 6
09-12 17:24:21.729  3853  3899 I jxcore-log: 
09-12 17:24:21.730  3853  3899 I jxcore-log: WARN testUtils: myNameCallback not set!
09-12 17:24:21.730  3853  3899 I jxcore-log: 
09-12 17:24:21.730  3853  3899 I jxcore-log: Running for WIFI network type
09-12 17:24:21.730  3853  3899 I jxcore-log: 
,09-12 17:24:24.277  3853  3899 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThatAlwaysPass.js
09-12 17:24:24.277  3853  3899 I jxcore-log: 
,09-12 17:24:24.288  3853  3899 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 17:24:24.289  3853  3899 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 17:24:24.289  3853  3899 I jxcore-log: 
,09-12 17:24:24.292  3853  3899 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-12 17:24:24.292  3853  3899 I jxcore-log: 
,09-12 17:24:24.292  3853  3899 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 17:24:24.292  3853  3899 I jxcore-log: 
,09-12 17:24:24.297  3853  3899 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 17:24:24.297  3853  3899 I jxcore-log: 
,09-12 17:24:24.414  3853  3899 I jxcore-log: ThaliTape :: Connected to the test server
09-12 17:24:24.414  3853  3899 I jxcore-log: 
,09-12 17:24:25.087  3853  3899 I jxcore-log: TAP version 13
09-12 17:24:25.087  3853  3899 I jxcore-log: 
,09-12 17:24:25.092  3853  3899 I jxcore-log: # setup
09-12 17:24:25.092  3853  3899 I jxcore-log: 
,09-12 17:24:25.797  3853  3899 I jxcore-log: ok 1 (unnamed assert)
09-12 17:24:25.797  3853  3899 I jxcore-log: 
,09-12 17:24:25.806  3853  3899 I jxcore-log: # 1. The test that always pass
09-12 17:24:25.806  3853  3899 I jxcore-log: 
,09-12 17:24:26.117  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:24:26.121  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 17:24:26.154  1508  3803 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 17:24:26.155  1508  3803 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 17:24:26.155  1508  3803 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 17:24:26.155  1508  3803 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:24:26.177  3550  4319 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 17:24:26.177  3550  4319 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jdm.a(PG:82)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jcs.o(PG:406)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jcn.a(PG:1379)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jcs.i(PG:143)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at blb.a(PG:3937)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at czp.a(PG:18188)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at czp.a(PG:9081)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at czq.run(PG:1686)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:24:26.177  3550  4319 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jdj.a(PG:4091)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jdj.a(PG:1125)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jdm.a(PG:77)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	... 12 more
09-12 17:24:26.177  3550  4319 E HttpOperation: Caused by: faj: BadAuthentication
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at fal.a(PG:38)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	at jdj.a(PG:4089)
09-12 17:24:26.177  3550  4319 E HttpOperation: 	... 14 more
,09-12 17:24:26.228  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 17:24:26.228  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 17:24:26.228  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 17:24:26.228  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 17:24:26.250  3550  4319 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 17:24:26.250  3550  4319 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jdm.a(PG:82)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jcs.o(PG:406)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jcn.a(PG:1379)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jcs.i(PG:143)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at hec.a(PG:42)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at hee.a(PG:102)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at czr.a(PG:65)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at kka.a(PG:108)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at czp.a(PG:19176)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at czp.a(PG:9081)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at czq.run(PG:1686)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:24:26.250  3550  4319 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jdj.a(PG:4091)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jdj.a(PG:1125)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jdm.a(PG:77)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	... 15 more
09-12 17:24:26.250  3550  4319 E HttpOperation: Caused by: faj: BadAuthentication
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at fal.a(PG:38)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	at jdj.a(PG:4089)
09-12 17:24:26.250  3550  4319 E HttpOperation: 	... 17 more
,09-12 17:24:26.250  3550  4319 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 17:24:26.250  3550  4319 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at hec.a(PG:42)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at hee.a(PG:102)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at czr.a(PG:65)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at kka.a(PG:108)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	... 15 more
09-12 17:24:26.250  3550  4319 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at fal.a(PG:38)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 17:24:26.250  3550  4319 E ExperimentLoader: 	... 17 more
,09-12 17:24:26.293  3853  3899 I jxcore-log: ok 2 (unnamed assert)
09-12 17:24:26.293  3853  3899 I jxcore-log: 
,09-12 17:24:26.296  3853  3899 I jxcore-log: # teardown
09-12 17:24:26.296  3853  3899 I jxcore-log: 
,09-12 17:24:26.394   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 429691, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 17:24:27.113  3853  3899 I jxcore-log: ok 3 (unnamed assert)
09-12 17:24:27.113  3853  3899 I jxcore-log: 
,09-12 17:24:27.734  3853  3899 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 17:24:27.734  3853  3899 I jxcore-log: 
,09-12 17:24:28.411  4321  4321 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 17:24:28.416  4321  4321 D AndroidRuntime: CheckJNI is OFF
,09-12 17:24:28.459  4321  4321 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 17:24:28.509  4321  4321 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 17:24:28.536  4321  4321 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 17:24:28.549   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 17:24:28.549   873   886 I ActivityManager: Killing 3853:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 17:24:28.650   873   896 W PackageSettings: Skipping PackageSetting{e06040f com.example.hello/10273} due to missing metadata
,09-12 17:24:28.667   873  1395 D GraphicsStats: Buffer count: 2
,09-12 17:24:28.671   873  1314 D WifiService: Client connection lost with reason: 4
,09-12 17:24:28.667   873  1936 I WindowState: WIN DEATH: Window{2cbd1e2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 17:24:28.706   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 17:24:28.706   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 17:24:28.707   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 17:24:28.707   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 17:24:28.707   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:28.707   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:28.707   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 17:24:28.707   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 17:24:28.707   873   886 I ActivityManager:   Force finishing activity ActivityRecord{32507ef u0 com.test.thalitest/.MainActivity t4}
,09-12 17:24:28.710   873   896 I art     : Starting a blocking GC Explicit
,09-12 17:24:28.715   873  2016 W ActivityManager: Spurious death for ProcessRecord{e510fb3 0:com.test.thalitest/u0a0}, curProc for 3853: null
,09-12 17:24:28.760   873   896 I art     : Explicit concurrent mark sweep GC freed 71310(4MB) AllocSpace objects, 14(328KB) LOS objects, 33% free, 29MB/43MB, paused 715us total 48.475ms
,09-12 17:24:28.786   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 17:24:28.791  4321  4321 I art     : System.exit called, status: 0
,09-12 17:24:28.791  4321  4321 I AndroidRuntime: VM exiting with result code 0.
,09-12 17:24:28.793   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 17:24:28.811   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 17:24:28.822  4202  4202 D BluetoothMapAppObserver: onReceive
,09-12 17:24:28.822  4202  4202 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 17:24:28.824   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 17:24:28.826  1867  2231 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 17:24:28.832  3663  3663 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 17:24:28.833  1903  1903 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-12 17:24:28.836  1903  4332 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 17:24:28.840  1903  4332 I Decoder : createOrResetDecoder
,09-12 17:24:28.865   873  1936 I ActivityManager: Start proc 4335:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 17:24:28.877  1984  1984 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 17:24:28.886  1508  1508 I ConfigService: onCreate
,09-12 17:24:28.898  4335  4335 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 17:24:28.899  1508  4347 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-12 17:24:28.916   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 17:24:28.916  1903  4332 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 17:24:28.926   873  1395 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3853 uid 10000
,09-12 17:24:28.927  1903  1903 I Keyboard.Facilitator: onFinishInput()
,09-12 17:24:28.931  2001  2135 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 17:24:28.932   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 17:24:28.932   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 17:24:28.932   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 17:24:28.932   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 17:24:28.932   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 17:24:28.932   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 17:24:28.932   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 17:24:28.932   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:28.932   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:28.932   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:28.939   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 17:24:28.939   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 17:24:28.939   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:28.939   873   886 E DropBoxManagerService: 	... 13 more
,09-12 17:24:28.943   873  2103 I ActivityManager: Start proc 4348:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 17:24:28.944  2001  2135 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 17:24:28.944  2001  2135 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2001
09-12 17:24:28.944  2001  2135 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:28.944  2001  2135 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:28.946   873  1939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 17:24:28.946   873  4355 E DropBoxManagerService: Can't write: system_app_crash
09-12 17:24:28.946   873  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:28.946   873  4355 E DropBoxManagerService: 	... 5 more
,09-12 17:24:28.952  2001  2135 I Process : Sending signal. PID: 2001 SIG: 9
,09-12 17:24:28.958  1903  4332 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 17:24:28.960  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-12 17:24:28.960  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 17:24:28.962  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 17:24:28.962  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 17:24:28.963  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-12 17:24:28.963  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-12 17:24:28.964  1903  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 17:24:28.964  1903  4332 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 17:24:28.964  1903  4332 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 17:24:28.964  1903  4332 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 17:24:28.964  1903  4332 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-12 17:24:28.964  1903  4332 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 17:24:28.982  4335  4335 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 17:24:28.995  4335  4365 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 17:24:29.006   873   883 I ActivityManager: Start proc 4366:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 17:24:29.008   873   883 D GraphicsStats: Buffer count: 1
09-12 17:24:29.008   873  2014 I WindowState: WIN DEATH: Window{64aac28 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 17:24:29.018  4335  4356 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.018  4335  4356 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:29.018   873  1937 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2001) has died
,09-12 17:24:29.019   873  1937 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 17:24:29.020   873  1937 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.032  4335  4356 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:29.040   873  2016 I ActivityManager: Start proc 4379:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 17:24:29.060  4366  4366 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 17:24:29.082  4379  4379 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:24:29.082  4379  4379 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:24:29.082  4379  4379 D AndroidRuntime: Shutting down VM
,09-12 17:24:29.090  4379  4379 E AndroidRuntime: FATAL EXCEPTION: main
09-12 17:24:29.090  4379  4379 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4379
09-12 17:24:29.090  4379  4379 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 17:24:29.090  4379  4379 E AndroidRuntime: 	... 10 more
,09-12 17:24:29.091  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 17:24:29.091  1508  1508 D AndroidRuntime: Shutting down VM
09-12 17:24:29.092   873  4396 E DropBoxManagerService: Can't write: system_app_crash
09-12 17:24:29.092   873  4396 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:29.092   873  4396 E DropBoxManagerService: 	... 5 more
,09-12 17:24:29.095   873  2030 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 17:24:29.096  4379  4379 I Process : Sending signal. PID: 4379 SIG: 9
,09-12 17:24:29.099  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
09-12 17:24:29.099  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
09-12 17:24:29.099  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 17:24:29.099  1508  1508 E AndroidRuntime: 	... 8 more
,09-12 17:24:29.102   873  4397 E DropBoxManagerService: Can't write: system_app_crash
09-12 17:24:29.102   873  4397 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:29.102   873  4397 E DropBoxManagerService: 	... 5 more
,09-12 17:24:29.105  1508  1508 I Process : Sending signal. PID: 1508 SIG: 9
,09-12 17:24:29.122   873  2016 I ActivityManager: Killing 3725:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 17:24:29.155  4335  4356 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-12 17:24:29.159  4335  4365 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.159  4335  4365 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:29.160  4335  4365 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 17:24:29.160  4335  4365 E AndroidRuntime: Process: android.process.acore, PID: 4335
09-12 17:24:29.160  4335  4365 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.160  4335  4365 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 17:24:29.160  4335  4356 I Process : Sending signal. PID: 4335 SIG: 9
,09-12 17:24:29.170  1715  4393 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@1c0c417
09-12 17:24:29.170   873  1314 D WifiService: Client connection lost with reason: 4
,09-12 17:24:29.185   873  2103 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4379) has died
,09-12 17:24:29.186   873  2103 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 17:24:29.193   873  2019 I ActivityManager: Process com.google.process.gapps (pid 1508) has died
,09-12 17:24:29.193   873  2019 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,09-12 17:24:29.193   873  2019 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,09-12 17:24:29.193   873  2019 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,09-12 17:24:29.193   873  2019 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,09-12 17:24:29.206  3550  3550 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,09-12 17:24:29.208   873   886 I ActivityManager: Start proc 4398:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 17:24:29.226   873  1939 I ActivityManager: Start proc 4410:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-12 17:24:29.227  1715  1715 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-12 17:24:29.233   873  4416 E DropBoxManagerService: Can't write: system_app_crash
09-12 17:24:29.233   873  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:29.233   873  4416 E DropBoxManagerService: 	... 5 more
,09-12 17:24:29.236   873  1390 I ActivityManager: Process android.process.acore (pid 4335) has died
09-12 17:24:29.236   873  1390 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40957ms
,09-12 17:24:29.267  4398  4398 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:24:29.267  4398  4398 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 17:24:29.267  4398  4398 D AndroidRuntime: Shutting down VM
,09-12 17:24:29.272  4410  4410 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-12 17:24:29.276  4398  4398 E AndroidRuntime: FATAL EXCEPTION: main
09-12 17:24:29.276  4398  4398 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4398
09-12 17:24:29.276  4398  4398 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 17:24:29.276  4398  4398 E AndroidRuntime: 	... 10 more
,09-12 17:24:29.277   873   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 17:24:29.279  4398  4398 I Process : Sending signal. PID: 4398 SIG: 9
,09-12 17:24:29.284  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-12 17:24:29.285  1715  1715 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-12 17:24:29.285   873  4425 E DropBoxManagerService: Can't write: system_app_crash
09-12 17:24:29.285   873  4425 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 17:24:29.285   873  4425 E DropBoxManagerService: 	... 5 more
,09-12 17:24:29.292   281   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
