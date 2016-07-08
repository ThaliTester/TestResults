#### Test 75789268d2ecd3a_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,07-08 14:05:09.552  3034  3836 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
07-08 14:05:09.554   872  1744 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
07-08 14:05:09.623  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-08 14:05:09.625  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-08 14:05:09.642  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-08 14:05:09.642  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:05:09.643  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:09.643  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-08 14:05:09.656  1863  3839 V BaseAuthAsyncOperation: access token request failed
07-08 14:05:09.658  3034  3836 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-08 14:05:09.698  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:05:09.698  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:05:09.698  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:09.699  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-08 14:05:09.712  3034  3836 E KeepSync: IOException
07-08 14:05:09.712  3034  3836 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:05:09.712  3034  3836 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:05:09.712  3034  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:05:09.712  3034  3836 E KeepSync: 	... 10 more
07-08 14:05:09.712  3034  3836 W KeepSync: Sync result 2
07-08 14:05:09.717   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 292026, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
07-08 14:05:10.148  3840  3840 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:05:10.153  3840  3840 D AndroidRuntime: CheckJNI is OFF
07-08 14:05:10.195  3840  3840 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:05:10.246  3840  3840 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:05:10.268  3840  3840 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-08 14:05:10.272   872  1739 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-08 14:05:10.303   872  1739 I ActivityManager: Start proc 3849:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-08 14:05:10.312  3840  3840 D AndroidRuntime: Shutting down VM
07-08 14:05:10.431  3849  3849 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-08 14:05:10.455  3849  3849 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-08 14:05:10.462  3849  3849 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3594-3597)
07-08 14:05:10.462  3849  3849 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:05:10.477  3849  3849 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aa0bb8d}
07-08 14:05:10.477  3849  3849 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:05:10.478  3849  3849 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-08 14:05:10.484  3849  3849 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-08 14:05:10.485  3849  3849 E SysUtils: ApplicationContext is null in ApplicationStatus
07-08 14:05:10.505  3849  3849 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-08 14:05:10.515  3849  3849 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:05:10.515  3849  3849 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:05:10.515  3849  3849 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-08 14:05:10.515  3849  3849 I Adreno  : Build Date                       : 10/20/15
07-08 14:05:10.515  3849  3849 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-08 14:05:10.515  3849  3849 I Adreno  : Local Branch                     : M14
07-08 14:05:10.515  3849  3849 I Adreno  : Remote Branch                    : 
07-08 14:05:10.515  3849  3849 I Adreno  : Remote Branch                    : 
07-08 14:05:10.515  3849  3849 I Adreno  : Reconstruct Branch               : 
,07-08 14:05:10.579   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23a85cf:true
,07-08 14:05:10.627  3849  3849 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-08 14:05:10.640  3849  3849 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-08 14:05:10.736  3849  3886 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-08 14:05:10.749  3849  3873 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-08 14:05:10.786  3849  3886 I OpenGLRenderer: Initialized EGL, version 1.4
,07-08 14:05:10.806  1656  1656 I Keyboard.Facilitator: onFinishInput()
,07-08 14:05:10.840   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +449ms (total +552ms)
,07-08 14:05:10.878  3849  3849 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3849
,07-08 14:05:11.048  3849  3849 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-08 14:05:11.165  3849  3887 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1677723344
,07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-08 14:05:11.174  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b35f468 added. We now have 1 listener(s)
,07-08 14:05:11.179  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-08 14:05:11.184  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-08 14:05:11.190  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:05:11.191  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-08 14:05:11.203  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e5567 added. We now have 1 listener(s)
07-08 14:05:11.204  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:11.211   872  1312 D WifiService: New client listening to asynchronous messages
,07-08 14:05:11.215  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-08 14:05:11.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:05:11.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-08 14:05:11.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-08 14:05:11.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-08 14:05:11.221  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:11.222  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:11.230  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:05:11.230  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-08 14:05:11.230  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:11.231  3849  3887 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:05:11.238  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:11.241  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:11.282  3849  3849 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-08 14:05:12.135  3849  3895 W jxcore-log: Initializing JXcore engine
,07-08 14:05:12.135  3849  3895 W jxcore-log: JXcore engine is ready
,07-08 14:05:12.227  3895  3895 W Thread-357: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-08 14:05:12.227  3895  3895 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10706]" dev="sockfs" ino=10706 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-08 14:05:12.227  3895  3895 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-08 14:05:12.227  3895  3895 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27703]" dev="sockfs" ino=27703 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-08 14:05:12.245  3849  3895 W jxcore-log: Starting JXcore engine
,07-08 14:05:12.329  3849  3895 W jxcore-log: Platform android
07-08 14:05:12.329  3849  3895 W jxcore-log: 
,07-08 14:05:12.329  3849  3895 W jxcore-log: Process ARCH arm
07-08 14:05:12.329  3849  3895 W jxcore-log: 
,07-08 14:05:12.518  3849  3895 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:05:12.518  3849  3895 I jxcore-log: 
,07-08 14:05:12.518  3849  3895 W jxcore-log: JXcore engine is started
,07-08 14:05:12.527  3849  3887 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-08 14:05:12.533  3849  3849 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-08 14:05:22.373  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-08 14:05:22.373  3849  3895 I jxcore-log: 
,07-08 14:05:22.375  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-08 14:05:22.375  3849  3895 I jxcore-log: 
,07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:22.388  3849  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:05:22.395  3849  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:05:22.397  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-08 14:05:22.397  3849  3895 I jxcore-log: 
,07-08 14:05:22.399  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-08 14:05:22.399  3849  3895 I jxcore-log: 
,07-08 14:05:22.718  3849  3895 I jxcore-log: Unit Test app is loaded
07-08 14:05:22.718  3849  3895 I jxcore-log: 
,07-08 14:05:22.723  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:22.723  3849  3895 I jxcore-log: 
,07-08 14:05:22.727  3849  3895 I jxcore-log: My device name is: motorola-Nexus 6
07-08 14:05:22.727  3849  3895 I jxcore-log: 
,07-08 14:05:22.729  3849  3895 I jxcore-log: WARN testUtils: myNameCallback not set!
07-08 14:05:22.729  3849  3895 I jxcore-log: 
,07-08 14:05:22.750  3849  3849 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-08 14:05:22.751  3849  3887 D JX-Cordova: Running tests
,07-08 14:05:22.848  3849  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-08 14:05:22.848  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-08 14:05:22.848  3849  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-08 14:05:22.849  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:05:22.849  3849  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-08 14:05:22.849  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-08 14:05:22.850  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-08 14:05:22.850  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-08 14:05:22.851  3849  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-08 14:05:22.851  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-08 14:05:22.851  3849  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,07-08 14:05:22.851  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-08 14:05:22.851  3849  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-08 14:05:22.851  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-08 14:05:22.852  3849  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-08 14:05:22.853  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:22.853  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28c4bed added. We now have 2 listener(s)
07-08 14:05:22.853  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:22.855  3849  3887 D BluetoothAdapter: enable(): BT is already enabled..!
07-08 14:05:22.855   872  1801 D WifiService: setWifiEnabled: true pid=3849, uid=10000
07-08 14:05:22.855   872  1801 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:05:22.856  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:22.856  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b2cba22 added. We now have 3 listener(s)
07-08 14:05:22.856  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:22.860  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:22.860  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0dccb3 added. We now have 4 listener(s)
07-08 14:05:22.860  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:22.862  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:22.862  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb0e270 added. We now have 5 listener(s)
07-08 14:05:22.862  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:22.864   872  1744 D WifiService: setWifiEnabled: false pid=3849, uid=10000
07-08 14:05:22.864   872  1744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:05:22.867  2542  2570 D BluetoothAdapterState: Current state: ON, message: 23,
07-08 14:05:22.867  2542  2570 D BluetoothAdapterProperties: Setting state to 13
07-08 14:05:22.867  2542  2570 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-08 14:05:22.868  2542  2570 D BluetoothAdapterProperties: onBluetoothDisable()
07-08 14:05:22.869  2542  2570 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:05:22.873  2542  2542 D BluetoothMapService: onReceive
,07-08 14:05:22.873  2542  2542 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:05:22.873  2542  2542 D BluetoothMapService: STATE_TURNING_OFF
07-08 14:05:22.874  2542  2542 D BluetoothMapService: MAP Service closeService in
07-08 14:05:22.874  2542  2542 D BluetoothMapMasInstance0: MAP Service shutdown
07-08 14:05:22.874  2542  2542 D ObexServerSockets0: shutdown(block = true)
07-08 14:05:22.876  2542  2705 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-08 14:05:22.880  2542  2542 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-08 14:05:22.881  2542  2706 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-08 14:05:22.881  2542  2691 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-08 14:05:22.881  2542  2542 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:05:22.881  2542  2542 I BtOppRfcommListener: stopping Accept Thread
07-08 14:05:22.882  2542  3376 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-08 14:05:22.882  2542  3376 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-08 14:05:22.883  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:05:22.884   872  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-08 14:05:22.884   872  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-08 14:05:22.884   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:05:22.884   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:22.894   872   885 I ActivityManager: Start proc 3898:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-08 14:05:22.895  2542  2574 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:05:22.895  2542  2570 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:05:22.897  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:22.898  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:05:22.899  2542  2542 D HeadsetService: Received stop request...Stopping profile...
,07-08 14:05:22.899  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:05:22.900   872  1311 E native  : do suspend true
,07-08 14:05:22.901   872   872 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:22.901  1723  1734 D BluetoothHeadset: Proxy object disconnected
07-08 14:05:22.902  1362  1802 D BluetoothHeadset: Proxy object disconnected
07-08 14:05:22.902  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,07-08 14:05:22.902   872   872 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:22.902   872   872 D BluetoothHeadset: Proxy object disconnected
07-08 14:05:22.902  2542  2542 D A2dpService: Received stop request...Stopping profile...
,07-08 14:05:22.902  2542  2697 D A2dpStateMachine: Exit Disconnected: -1
07-08 14:05:22.904  1362  1362 D BluetoothA2dp: Proxy object disconnected
07-08 14:05:22.904   872   872 D BluetoothA2dp: Proxy object disconnected
07-08 14:05:22.905  2542  2542 D HidService: Received stop request...Stopping profile...
,07-08 14:05:22.905  2542  2542 D HidService: Stopping Bluetooth HidService
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:22.905  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:05:22.906  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:05:22.906  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:05:22.906  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,07-08 14:05:22.906  1362  1362 D HidProfile: Bluetooth service disconnected
,07-08 14:05:22.907  2542  2542 D HealthService: Received stop request...Stopping profile...
,07-08 14:05:22.907  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:22.908  2542  2542 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:05:22.908  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.908  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:22.908  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:22.909  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:22.910   872  2118 D DhcpClient: Clearing IP address
07-08 14:05:22.910   372   871 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:05:22.910  2542  2542 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:05:22.911  2542  2542 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-08 14:05:22.911  2542  2574 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-08 14:05:22.911  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.911  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.911  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.911  2542  2574 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-08 14:05:22.912  2542  2542 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:22.912  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.912  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:22.912  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:22.913  2542  2542 D PanService: Received stop request...Stopping profile...
07-08 14:05:22.914  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:05:22.914  1362  1362 D PanProfile: Bluetooth service disconnected
07-08 14:05:22.914   372   871 D CommandListener: Setting iface cfg
07-08 14:05:22.915  2542  2574 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-08 14:05:22.915  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.915  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.915  2542  2682 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:05:22.915  2542  2682 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:05:22.915  2542  2682 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:05:22.916  2542  2682 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:05:22.916  2542  2542 D BluetoothMapService: Received stop request...Stopping profile...
07-08 14:05:22.916  2542  2542 D BluetoothMapService: stop()
07-08 14:05:22.917  2542  2542 D BluetoothMapAppObserver: deinitObservers()
07-08 14:05:22.917  2542  2542 D BluetoothMapAppObserver: removeReceiver()
07-08 14:05:22.918  1362  1362 D BluetoothMap: Proxy object disconnected
07-08 14:05:22.918  1362  1362 D MapProfile: Bluetooth service disconnected
07-08 14:05:22.918  2542  2542 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:22.918  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.918  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:22.918  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:22.919  2542  2542 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:05:22.919  2542  2574 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:05:22.919  2542  2542 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-08 14:05:22.919   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-08 14:05:22.919   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-08 14:05:22.921   398   398 E Parcel  : Reading a NULL string not supported here.
07-08 14:05:22.922   872  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
07-08 14:05:22.923   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:05:22.923   872  1311 E native  : do suspend true
07-08 14:05:22.924  2542  2542 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:22.924  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.924  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:22.924  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:22.925  2542  2542 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:05:22.925  2542  2574 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:0,5:22.925  2542  2542 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-08 14:05:22.925  2542  2542 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:22.925  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.925  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:22.925  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:22.925  2542  2542 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:05:22.926  2542  2542 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:05:22.927  2542  2542 D BluetoothMapService: MAP Service closeService in
07-08 14:05:22.927  2542  2542 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:22.927  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:22.927  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:22.927  2542  2542 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:22.927  2542  2570 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:05:22.927  2542  2570 D BluetoothAdapterProperties: Setting state to 15
07-08 14:05:22.927  2542  2542 D BluetoothMapService: cleanup()
07-08 14:05:22.927  2542  2542 D BluetoothMapService: MAP Service closeService in
07-08 14:05:22.927  2542  2570 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:05:22.927  2542  2570 I BluetoothAdapterState: Entering BleOnState
07-08 14:05:22.927  1723  1734 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:22.928   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-08 14:05:22.928  1362  1379 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:05:22.932   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:22.932  1362  1834 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:05:22.932  1362  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:22.932   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:22.932   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:22.933  1506  2353 V NativeCrypto: Read error: ssl=0xaebeac00: I/O error during system call, Connection timed out
07-08 14:05:22.933  1362  1802 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:05:22.933   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:05:22.933  1362  1379 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:05:22.934  1362  1834 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:05:22.934  2542  2570 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:05:22.934  2542  2570 D BluetoothAdapterProperties: Setting state to 16
07-08 14:05:22.934  2542  2570 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-08 14:05:22.935  2542  2570 D BluetoothAdapterProperties: onBleDisable
07-08 14:05:22.935  2542  2570 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:05:22.935  2542  2571 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:05:22.936  2542  2574 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:05:22.936  2542  2682 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-08 14:05:22.936  2542  2682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:22.938   872  2119 D DhcpClient: Receive thread stopped
07-08 14:05:22.939  1506  2353 V NativeCrypto: SSL shutdown failed: ssl=0xaebeac00: I/O error during system call, Broken pipe
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:22.940  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:22.940  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:22.942  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:22.942  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:22.959   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:05:22.968  3898  3898 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-08 14:05:22.979  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:05:22.982   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:05:22.983   372   871 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:05:22.983   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-08 14:05:22.983   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:05:22.986   872   889 D Tethering: MasterInitialState.processMessage what=3
07-08 14:05:22.987   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-08 14:05:22.987  3381  3381 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6e0f081 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-08 14:05:22.989  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:22.989  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-08 14:05:22.992  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:22.997   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@64f17af:true
07-08 14:05:23.003   872  1744 I ActivityManager: Start proc 3915:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-08 14:05:23.005   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:05:23.007   872  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:23.008  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:23.009  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:23.010  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:23.010  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:23.017  1827  2063 W Settings: Setting airplane_mode_on has mov,ed from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:05:23.034  3898  3898 D LocalBluetoothProfileManager: Adding local MAP profile
07-08 14:05:23.039  3898  3898 D BluetoothMap: Create BluetoothMap proxy object
07-08 14:05:23.042   372   871 E Netd    : netlink response contains error (No such file or directory)
,07-08 14:05:23.044  3898  3898 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-08 14:05:23.049  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-08 14:05:23.057  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:23.066   872  1387 I ActivityManager: Killing 3381:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-08 14:05:23.141  2542  2574 I bt_hci  : shut_down
,07-08 14:05:23.142  2542  2580 D bt_hwcfg: hw_epilog_process
,07-08 14:05:23.143  2542  2580 I bt_vendor: low_power_mode_cb
,07-08 14:05:23.172  2542  2580 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-08 14:05:23.172  2542  2580 I bt_vendor: epilog_cb
07-08 14:05:23.172  2542  2580 I bt_hci  : epilog_finished_callback
,07-08 14:05:23.182  2542  2574 I bt_hci_h4: hal_close
,07-08 14:05:23.182  2542  2574 I bt_userial_vendor: device fd = 51 close
,07-08 14:05:23.239  3915  3915 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:05:23.239  3915  3915 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:05:23.239  3915  3915 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:05:23.239  3915  3915 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:05:23.239  3,915  3915 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:05:23.239  3915  3915 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:583)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.239  3915  3915 D StrictMode: 	,at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.239  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:05:23.240  3915  3915 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.240  3915  3915 D Stric,tMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:05:23.240  3915  3915 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:05:23.240  3915  3915 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:05:23.240  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:05:23.245  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:05:23.252  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-08 14:05:23.252  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:23.259   872  1387 I ActivityManager: Killing 2389:com.google.android.talk/u0a61 (adj 15): empty #17
,07-08 14:05:23.300   872  1387 W libprocessgroup: failed to kill pid 2389: No such process
,07-08 14:05:23.330   872  1387 I ActivityManager: Start proc 3949:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,07-08 14:05:23.339  2542  2571 D bt_stack_manager: event_shut_down_stack finished.
07-08 14:05:23.339  2542  2570 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-08 14:05:23.341  2542  2570 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-08 14:05:23.341  2542  2542 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:05:23.342  2542  2542 D BtGatt.GattService: Received stop request...Stopping profile...,
07-08 14:05:23.342  2542  2542 D BtGatt.GattService: stop()
07-08 14:05:23.342  2542  2542 D BtGatt.AdvertiseManager: advertise clients cleared
07-08 14:05:23.345  2542  2542 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:23.345  2542  2542 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:23.345  2542  2542 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:23.345  2542  2542 V BluetoothAdapterState: isBleTurningOff()=true
,07-08 14:05:23.346  2542  2570 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:05:23.346  2542  2570 D BluetoothAdapterProperties: Setting state to 10
07-08 14:05:23.346  2542  2570 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-08 14:05:23.356  2542  2570 I BluetoothAdapterState: Entering OffState
07-08 14:05:23.357   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-08 14:05:23.366  2542  2542 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-08 14:05:23.366  2542  2542 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:05:23.366  2542  2542 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-08 14:05:23.367  2542  2571 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-08 14:05:23.371  2542  2571 D bt_stack_manager: event_clean_up_stack finished.
,07-08 14:05:23.372  2542  2542 I art     : System.exit called, status: 0
,07-08 14:05:23.372  2542  2542 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:05:23.394  3949  3949 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-08 14:05:23.415   872   882 I ActivityManager: Process com.android.bluetooth (pid 2542) has died
,07-08 14:05:23.665  3949  3969 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-08 14:05:23.666  3949  3969 I Babel_SMS: MmsConfig.loadMmsSettings
,07-08 14:05:23.666  3949  3969 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-08 14:05:23.666  3949  3969 I Babel_SMS: MmsConfig.loadFromDatabase
,07-08 14:05:23.731  3949  3969 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-08 14:05:23.731  3949  3969 I Babel_SMS: MmsConfig.loadFromResources
,07-08 14:05:23.735  3949  3969 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-08 14:05:23.744  3949  3969 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-08 14:05:23.779  3949  3949 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:05:23.781  3949  3949 I Babel_Crash: startup - clean
,07-08 14:05:23.802  3949  3949 I Babel_telephony: TeleModule.launchCompleted
,07-08 14:05:23.814   872  1389 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-08 14:05:23.775  3915  3940 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-08 14:05:23.824  3949  3949 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-08 14:05:23.831  3949  3949 W Babel   : BAM#gBA: invalid account id: -1
07-08 14:05:23.831  3949  3949 W Babel   : BAM#gBA: invalid account id: -1
07-08 14:05:23.831  3949  3949 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-08 14:05:23.840   872  1693 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-08 14:05:23.843  3949  3974 I Babel   : deleted: false for 0
,07-08 14:05:23.889  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-08 14:05:23.908  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:05:23.915  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-08 14:05:23.916  1863  2360 I iu.UploadsManager: num queued entries: 0
07-08 14:05:23.916  1863  2360 I iu.UploadsManager: num updated entries: 0
,07-08 14:05:23.926  1863  2360 I iu.SyncManager: NEXT; no task
,07-08 14:05:23.937   872  1690 I ActivityManager: Start proc 3977:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-08 14:05:23.940  3949  3949 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-08 14:05:23.976  3977  3977 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-08 14:05:23.988  3977  3977 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:24.010  3977  3977 D SprintDMHelper: simOperator: 
07-08 14:05:24.010  3977  3977 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-08 14:05:24.015  3949  3949 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-08 14:05:24.026  3949  3949 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-08 14:05:24.029  3949  3949 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-08 14:05:24.032   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d0a6dd:true
,07-08 14:05:24.031  3949  3949 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-08 14:05:24.043   872  1693 I ActivityManager: Start proc 3989:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-08 14:05:24.047  3949  3949 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-08 14:05:24.053   872   882 I ActivityManager: Killing 3554:com.google.process.gapps/u0a99 (adj 15): empty #17
,07-08 14:05:24.086  3949  3949 I vclib   : onServiceConnected
,07-08 14:05:24.168   872  1389 I ActivityManager: Start proc 4004:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-08 14:05:24.172  3949  4003 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-08 14:05:24.174   872  1737 I ActivityManager: Killing 2525:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-08 14:05:24.229  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-08 14:05:24.278  4004  4004 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-08 14:05:24.278  4004  4004 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:05:24.278  4004  4004 I GAv4    :   adb logcat -s GAv4
,07-08 14:05:24.291  4004  4004 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:05:24.296  4004  4004 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:05:24.332  4004  4021 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:05:24.430  4004  4004 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-08 14:05:24.468  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-08 14:05:24.475  4004  4004 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7607-7610)
,07-08 14:05:24.475  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:05:24.484  4004  4004 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c5fbf1}
,07-08 14:05:24.484  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:05:24.484  4004  4004 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-08 14:05:24.492  4004  4004 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-08 14:05:24.494  4004  4004 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-08 14:05:24.509  4004  4004 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-08 14:05:24.521  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:05:24.521  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:05:24.521  4004  4004 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-08 14:05:24.521  4004  4004 I Adreno  : Build Date                       : 10/20/15
07-08 14:05:24.521  4004  4004 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-08 14:05:24.521  4004  4004 I Adreno  : Local Branch                     : M14
07-08 14:05:24.521  4004  4004 I Adreno  : Remote Branch                    : 
07-08 14:05:24.521  4004  4004 I Adreno  : Remote Branch                    : 
07-08 14:05:24.521  4004  4004 I Adreno  : Reconstruct Branch               : 
,07-08 14:05:24.580  4004  4004 I NSApplication: Starting up...
,07-08 14:05:24.590  4004  4051 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-08 14:05:24.622   872  1693 I ActivityManager: Start proc 4056:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-08 14:05:24.624   872  1693 I ActivityManager: Killing 3483:android.process.acore/u0a5 (adj 15): empty #17
,07-08 14:05:24.689  4056  4056 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-08 14:05:24.858   872  1722 I ActivityManager: Killing 3675:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-08 14:05:24.932   872  1722 I ActivityManager: Start proc 4070:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-08 14:05:24.978  4070  4070 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-08 14:05:25.026  4070  4070 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-08 14:05:25.044   872  1801 I ActivityManager: Killing 3691:com.android.musicfx/u0a18 (adj 15): empty #17
,07-08 14:05:26.889  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-08 14:05:26.889  3849  3895 I jxcore-log: 
,07-08 14:05:27.278  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-08 14:05:27.278  3849  3895 I jxcore-log: 
,07-08 14:05:27.303  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-08 14:05:27.303  3849  3895 I jxcore-log: 
,07-08 14:05:27.308  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-08 14:05:27.308  3849  3895 I jxcore-log: 
,07-08 14:05:27.324  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-08 14:05:27.324  3849  3895 I jxcore-log: 
,07-08 14:05:27.328  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-08 14:05:27.328  3849  3895 I jxcore-log: 
,07-08 14:05:27.908   872  1801 D WifiService: setWifiEnabled: true pid=3849, uid=10000
,07-08 14:05:27.909   872  1801 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:05:27.925   872  1311 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:27.932  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:27.933  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:27.935  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:27.935  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:27.942   872  1311 D WifiConfigStore: loaded 0 passpoint configs
07-08 14:05:27.942   872  1311 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:05:27.943   872  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-08 14:05:27.943   872  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-08 14:05:27.944   872  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:05:27.944   872  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-08 14:05:27.944   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-08 14:05:27.944   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-08 14:05:27.959   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-08 14:05:27.959   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-08 14:05:27.960   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:27.967   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-08 14:05:27.967   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-08 14:05:27.967   872  1311 E native  : do suspend true
,07-08 14:05:27.979   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:05:27.979   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-08 14:05:27.980   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:05:28.804   872  1744 I ActivityManager: Killing 3407:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-08 14:05:29.337   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:05:29.359   872  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.56 rxSuccessRate=15.69 delta 1000 -> 994
,07-08 14:05:29.361   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-08 14:05:29.361   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:29.376   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-08 14:05:29.407  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-08 14:05:29.407  3849  3895 I jxcore-log: 
,07-08 14:05:29.420  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-08 14:05:29.420  3849  3895 I jxcore-log: 
,07-08 14:05:29.429  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-08 14:05:29.429  3849  3895 I jxcore-log: 
,07-08 14:05:29.450   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-08 14:05:29.453  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-08 14:05:29.595  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-08 14:05:29.595  3849  3895 I jxcore-log: 
,07-08 14:05:29.679  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-08 14:05:29.679  3849  3895 I jxcore-log: 
,07-08 14:05:29.740  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-08 14:05:29.740  3849  3895 I jxcore-log: 
,07-08 14:05:29.749  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-08 14:05:29.749  3849  3895 I jxcore-log: 
,07-08 14:05:29.879  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:05:29.916  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:05:29.917  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-08 14:05:29.923   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:05:29.928   872  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:05:29.928   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:05:29.929   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:05:29.944   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:29.953   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:29.953   872  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,07-08 14:05:29.959   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-08 14:05:29.964  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-08 14:05:29.964  3849  3895 I jxcore-log: 
,07-08 14:05:29.984  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-08 14:05:29.984  3849  3895 I jxcore-log: 
,07-08 14:05:29.989  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-08 14:05:29.989  3849  3895 I jxcore-log: 
,07-08 14:05:29.994  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-08 14:05:29.994  3849  3895 I jxcore-log: 
,07-08 14:05:30.009   872  4105 D DhcpClient: Receive thread started
,07-08 14:05:30.009  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-08 14:05:30.009  3849  3895 I jxcore-log: 
,07-08 14:05:30.031  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-08 14:05:30.031  3849  3895 I jxcore-log: 
,07-08 14:05:30.091   872  1311 E native  : do suspend false
,07-08 14:05:30.106   872  2118 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:05:30.120  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-08 14:05:30.120  3849  3895 I jxcore-log: 
,07-08 14:05:30.126  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-08 14:05:30.126  3849  3895 I jxcore-log: 
,07-08 14:05:30.127   872  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172491, domain null
,07-08 14:05:30.128   872  2118 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172491 seconds
,07-08 14:05:30.131   872  2118 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-08 14:05:30.143   872  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:05:30.144   872  2118 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:05:30.149   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:30.158  3849  3895 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-08 14:05:30.158  3849  3895 I jxcore-log: 
,07-08 14:05:30.158   872  2118 D DhcpClient: Scheduling renewal in 86399s
07-08 14:05:30.161   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-08 14:05:30.167   872  1311 E native  : do suspend true
,07-08 14:05:30.175  3849  3895 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-08 14:05:30.179  3849  3895 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-08 14:05:30.179  3849  3895 I jxcore-log: 
,07-08 14:05:30.181   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-08 14:05:30.181   872  1311 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:05:30.182   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-08 14:05:30.183   872  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-08 14:05:30.185   872  1313 D ConnectivityService: Adding iface wlan0 to network 101
,07-08 14:05:30.217   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-08 14:05:30.217   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-08 14:05:30.218   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-08 14:05:30.219   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-08 14:05:30.220   872  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-08 14:05:30.226   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:05:30.230   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-08 14:05:30.230   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-08 14:05:30.230   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-08 14:05:30.230   872  1313 D ConnectivityService:    accepting network in place of null
07-08 14:05:30.230   872  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:05:30.231   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:05:30.232   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:05:30.242   872  4104 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333377, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:05:30.253   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:05:30.260  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:30.260  3849  3895 I jxcore-log: 
,07-08 14:05:30.260  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:30.260  3849  3895 I jxcore-log: 
,07-08 14:05:30.262  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:05:30.262  3849  3895 I jxcore-log: 
,07-08 14:05:30.263  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:05:30.263  3849  3895 I jxcore-log: 
,07-08 14:05:30.265  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:30.265  3849  3895 I jxcore-log: 
,07-08 14:05:30.265  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:30.265  3849  3895 I jxcore-log: 
,07-08 14:05:30.266  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
07-08 14:05:30.266  3849  3895 I jxcore-log: 
07-08 14:05:30.267  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:05:30.267  3849  3895 I jxcore-log: 
,07-08 14:05:30.272   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:05:30.276   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-08 14:05:30.276   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:05:30.278   872   889 D Tethering: MasterInitialState.processMessage what=3
07-08 14:05:30.280   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:30.287  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:05:30.287  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:30.288  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:05:30.288  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:30.289  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:30.289  3849  3895 I jxcore-log: 
,07-08 14:05:30.292  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:30.292  3849  3895 I jxcore-log: 
,07-08 14:05:30.308   872  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:807::200e
,07-08 14:05:30.321  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:05:30.324  1863  2360 I iu.UploadsManager: num queued entries: 0
,07-08 14:05:30.332  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:05:30.334  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-08 14:05:30.335  3977  3977 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:30.339  1863  4116 I MDM     : [218] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-08 14:05:30.339  1863  4116 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:05:30.341  1863  4116 V GoogleAuthProtoRequest: [218] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:05:30.342  3977  3977 D SprintDMHelper: simOperator: 
,07-08 14:05:30.342  3977  3977 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-08 14:05:30.351  1863  2360 I iu.UploadsManager: num updated entries: 0
,07-08 14:05:30.359  1863  2360 I iu.SyncManager: NEXT; no task
,07-08 14:05:30.372  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:30.373  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:30.377   872  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:05:30 GMT], X-Android-Received-Millis=[1467979530376], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467979530349]}
,07-08 14:05:30.378   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:05:30.378   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,07-08 14:05:30.378   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-08 14:05:30.379   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:05:30.423  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-08 14:05:30.423  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-08 14:05:30.423  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth,
,07-08 14:05:30.423  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:30.441  1863  4116 E MDM     : [218] SitrepService.a: Error sending sitrep.
,07-08 14:05:30.478  3949  4121 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-08 14:05:31.278   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-08 14:05:32.917   872  1387 D WifiService: setWifiEnabled: false pid=3849, uid=10000
,07-08 14:05:32.918   872  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:05:32.956  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:05:32.966   872  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-08 14:05:32.967   872  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-08 14:05:32.967   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:05:32.967   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:32.981   872  1311 E native  : do suspend true
,07-08 14:05:32.998   872  2118 D DhcpClient: Clearing IP address
,07-08 14:05:32.999   372   871 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:05:33.004   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:33.011  1506  4126 V NativeCrypto: Read error: ssl=0x9a4da400: I/O error during system call, Connection timed out
,07-08 14:05:33.016   872  4105 D DhcpClient: Receive thread stopped
,07-08 14:05:33.023   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-08 14:05:33.023   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-08 14:05:33.024   872  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-08 14:05:33.024  1506  4126 V NativeCrypto: SSL shutdown failed: ssl=0x9a4da400: I/O error during system call, Broken pipe
,07-08 14:05:33.032   398   398 E Parcel  : Reading a NULL string not supported here.
,07-08 14:05:33.038   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
07-08 14:05:33.038   872  1311 E native  : do suspend true
07-08 14:05:33.038   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-08 14:05:33.072   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:05:33.098   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:05:33.099   372   871 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:05:33.100   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-08 14:05:33.100   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:33.102   872   889 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:33.109  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:33.109  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:33.110  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:33.110  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:33.111  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:05:33.111  3849  3895 I jxcore-log: 
07-08 14:05:33.114   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:05:33.115  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:05:33.115  3849  3895 I jxcore-log: 
,07-08 14:05:33.132  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-08 14:05:33.134   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:33.137  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:33.137  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:33.138  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:33.138  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:33.138   872  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:05:33.138  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:33.138  3849  3895 I jxcore-log: 
07-08 14:05:33.140  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:33.140  3849  3895 I jxcore-log: 
07-08 14:05:33.141  1827  2063 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:05:33.147  1863  2360 I iu.UploadsManager: num queued entries: 0
,07-08 14:05:33.147  1863  2360 I iu.UploadsManager: num updated entries: 0
,07-08 14:05:33.149  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:05:33.150  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-08 14:05:33.152  3977  3977 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:33.156  3977  3977 D SprintDMHelper: simOperator: 
07-08 14:05:33.156  3977  3977 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-08 14:05:33.167  1863  2360 I iu.SyncManager: NEXT; no task
,07-08 14:05:33.170  3949  4141 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-08 14:05:33.185   372   871 E Netd    : netlink response contains error (No such file or directory)
07-08 14:05:33.186   872  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-08 14:05:37.964   872   889 I ActivityManager: Start proc 4145:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-08 14:05:38.093  4145  4145 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:05:38.093  4145  4145 D AdapterServiceConfig: Adding A2dpService
,07-08 14:05:38.094  4145  4145 D AdapterServiceConfig: Adding HidService
,07-08 14:05:38.094  4145  4145 D AdapterServiceConfig: Adding HealthService
,07-08 14:05:38.094  4145  4145 D AdapterServiceConfig: Adding PanService
,07-08 14:05:38.094  4145  4145 D AdapterServiceConfig: Adding GattService
,07-08 14:05:38.094  4145  4145 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:05:38.110   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2661c10:true
,07-08 14:05:38.110  4145  4145 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:05:38.115  4145  4145 I bt_bluedroid: init
,07-08 14:05:38.116  4145  4157 I BluetoothAdapterState: Entering OffState
,07-08 14:05:38.119  4145  4158 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-08 14:05:38.120  4145  4158 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:05:38.120  4145  4158 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:05:38.120  4145  4158 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-08 14:05:38.121  4145  4145 I bt_bluedroid: get_profile_interface socket
,07-08 14:05:38.123  4145  4145 I bt_bluedroid: get_profile_interface sdp,
07-08 14:05:38.125  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,07-08 14:05:38.127  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
07-08 14:05:38.128  4145  4156 I bt_bluedroid: config_hci_snoop_log
,07-08 14:05:38.131   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-08 14:05:38.139  4145  4157 D BluetoothAdapterState: Current state: OFF, message: 0
,07-08 14:05:38.139  4145  4157 D BluetoothAdapterProperties: Setting state to 14
07-08 14:05:38.140  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-08 14:05:38.144  4145  4157 D BluetoothBondStateMachine: make
,07-08 14:05:38.147  4145  4162 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-08 14:05:38.153  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:05:38.155  4145  4145 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-08 14:05:38.159  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:38.160  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:05:38.161  4145  4145 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:05:38.161  4145  4145 D BtGatt.GattService: start()
,07-08 14:05:38.161  4145  4145 I bt_bluedroid: get_profile_interface gatt
,07-08 14:05:38.162  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
07-08 14:05:38.163  4145  4145 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:05:38.172  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:38.173  4145  4145 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:38.173  4145  4145 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:05:38.173  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:38.174  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:05:38.175  4145  4157 I bt_bluedroid: enable
,07-08 14:05:38.176  4145  4158 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:05:38.177  4145  4158 I bt_hci  : start_up
,07-08 14:05:38.188  4145  4158 I bt_vendor: alloc value 0xb3a82189
,07-08 14:05:38.189  4145  4158 I bt_vendor: init
07-08 14:05:38.189  4145  4158 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:05:38.189  4145  4158 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:05:38.234   872  1313 D ConnectivityService: handlePromptUnvalidated 101
,07-08 14:05:38.296  4145  4158 D bt_hci  : start_up starting async portion
,07-08 14:05:38.297  4145  4165 I bt_hci  : event_finish_startup
,07-08 14:05:38.298  4145  4165 I bt_hci_h4: hal_open
,07-08 14:05:38.298  4145  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-08 14:05:38.308  4145  4165 I bt_userial_vendor: device fd = 51 open
,07-08 14:05:38.339  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:05:38.371  4145  4165 D bt_hwcfg: Chipset BCM4354A2
,07-08 14:05:38.371  4145  4165 D bt_hwcfg: Target name = [BCM4354A2]
,07-08 14:05:38.372  4145  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-08 14:05:39.007  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:05:39.008  4145  4165 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:05:39.008  4145  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:05:39.125  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
07-08 14:05:39.126  4145  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-08 14:05:39.156  4145  4165 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:05:39.156  4145  4165 I bt_vendor: firmware callback
07-08 14:05:39.157  4145  4165 I bt_hci  : firmware_config_callback
,07-08 14:05:39.167  4145  4167 I bt_btu  : btu_task pending for preload complete event
,07-08 14:05:39.168  4145  4167 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:05:39.168  4145  4167 I bt_btu  : btu_task received preload complete event
,07-08 14:05:39.179  4145  4167 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:05:39.180  4145  4167 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:05:39.180  4145  4167 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:05:39.180  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVDT
07-08 14:05:39.180  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:05:39.181  4145  4167 I         : BTE_InitTraceLevels -- TRC_A2D
07-08 14:05:39.181  4145  4167 I         : BTE_InitTraceLevels -- TRC_BNEP
07-08 14:05:39.181  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTM
07-08 14:05:39.181  4145  4167 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:05:39.182  4145  4167 I         : BTE_InitTraceLevels -- TRC_PAN
07-08 14:05:39.182  4145  4167 I         : BTE_InitTraceLevels -- TRC_SDP
07-08 14:05:39.182  4145  4167 I         : BTE_InitTraceLevels -- TRC_GATT
07-08 14:05:39.183  4145  4167 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:05:39.183  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-08 14:05:39.183  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:05:39.317  4145  4167 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ffd9d
,07-08 14:05:39.317  4145  4167 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ffd9d 
,07-08 14:05:39.328  4145  4161 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-08 14:05:39.331  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:05:39.332  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-08 14:05:39.336  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,07-08 14:05:39.342  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:05:39.343  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:05:39.343  4145  4161 D bt_hci  : do_postload posting postload work item
,07-08 14:05:39.343  4145  4165 I bt_hci  : event_postload
,07-08 14:05:39.343  4145  4165 I bt_vendor: sco_config_cb
07-08 14:05:39.343  4145  4165 I bt_hci  : sco_config_callback postload finished.
07-08 14:05:39.346  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:39.348  4145  4161 D bt_bte_conf: Device ID record 1 : primary
,07-08 14:05:39.349  4145  4161 D bt_bte_conf:   vendorId            = 000f
07-08 14:05:39.349  4145  4161 D bt_bte_conf:   vendorIdSource      = 0001
07-08 14:05:39.349  4145  4161 D bt_bte_conf:   product             = 1200
07-08 14:05:39.349  4145  4161 D bt_bte_conf:   version             = 1436
07-08 14:05:39.350  4145  4161 D bt_bte_conf:   clientExecutableURL = 
07-08 14:05:39.350  4145  4161 D bt_bte_conf:   serviceDescription  = 
07-08 14:05:39.350  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:39.350  4145  4165 I bt_vendor: low_power_mode_cb
07-08 14:05:39.350  4145  4161 D bt_bte_conf:   documentationURL    = 
07-08 14:05:39.350  4145  4161 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-08 14:05:39.351  4145  4158 D bt_stack_manager: event_start_up_stack finished
07-08 14:05:39.352  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:05:39.352  4145  4157 D BluetoothAdapterProperties: Setting state to 15
07-08 14:05:39.352  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:05:39.352  4145  4157 I BluetoothAdapterState: Entering BleOnState
,07-08 14:05:39.358  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:05:39.359  4145  4157 D BluetoothAdapterProperties: Setting state to 11
,07-08 14:05:39.359  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-08 14:05:39.364  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:39.366  4145  4145 D HeadsetService: Received start request. Starting profile...
07-08 14:05:39.370  4145  4145 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-08 14:05:39.370  4145  4145 D HeadsetStateMachine: make
,07-08 14:05:39.378  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:05:39.384  4145  4145 D HeadsetStateMachine: max_hf_connections = 1
,07-08 14:05:39.384  4145  4145 I bt_bluedroid: get_profile_interface handsfree
,07-08 14:05:39.385  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:05:39.385  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-08 14:05:39.391  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:39.392  4145  4145 D A2dpService: Received start request. Starting profile...
,07-08 14:05:39.393  4145  4145 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-08 14:05:39.394  4145  4145 I bt_bluedroid: get_profile_interface avrcp
,07-08 14:05:39.402  4145  4145 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-08 14:05:39.402  4145  4145 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:05:39.402  4145  4145 D A2dpStateMachine: make
,07-08 14:05:39.404  4145  4145 I bt_bluedroid: get_profile_interface a2dp
,07-08 14:05:39.405  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-08 14:05:39.407  4145  4176 D A2dpStateMachine: Enter Disconnected: -2
,07-08 14:05:39.408  4145  4145 I BluetoothHidServiceJni: classInitNative: succeeds
07-08 14:05:39.409  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:39.411  4145  4145 D HidService: Received start request. Starting profile...
07-08 14:05:39.411  3898  3898 D BluetoothInputDevice: Proxy object connected
07-08 14:05:39.411  4145  4145 I bt_bluedroid: get_profile_interface hidhost
07-08 14:05:39.411  4145  4161 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e13e5
,07-08 14:05:39.411  4145  4145 D HidService: setHidService(): set to: null
07-08 14:05:39.412  3898  3898 D HidProfile: Bluetooth service connected
07-08 14:05:39.412  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-08 14:05:39.413  4145  4145 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-08 14:05:39.414  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
07-08 14:05:39.415  4145  4145 D HealthService: Received start request. Starting profile...
,07-08 14:05:39.418  4145  4145 I bt_bluedroid: get_profile_interface health
,07-08 14:05:39.419  4145  4145 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-08 14:05:39.420  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:39.422  3898  3898 D BluetoothPan: BluetoothPAN Proxy object connected
,07-08 14:05:39.422  4145  4145 D PanService: Received start request. Starting profile...
07-08 14:05:39.422  4145  4145 D BluetoothPanServiceJni: initializeNative(L110): pan
07-08 14:05:39.422  3898  3898 D PanProfile: Bluetooth service connected
,07-08 14:05:39.422  4145  4145 I bt_bluedroid: get_profile_interface pan
07-08 14:05:39.423  4145  4161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-08 14:05:39.429  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:39.431  4145  4145 D BluetoothMapService: Received start request. Starting profile...
,07-08 14:05:39.431  4145  4145 D BluetoothMapService: start(),
,07-08 14:05:39.432  3898  3898 D BluetoothMap: Proxy object connected
,07-08 14:05:39.434  3898  3898 D MapProfile: Bluetooth service connected
07-08 14:05:39.434  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-08 14:05:39.434  3898  3898 D BluetoothMap: getConnectedDevices()
,07-08 14:05:39.435  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-08 14:05:39.435  4145  4145 D BluetoothMapAppObserver: createReceiver()
07-08 14:05:39.435  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-08 14:05:39.440  4145  4145 D BluetoothMapAppObserver: initObservers()
07-08 14:05:39.440  4145  4145 D BluetoothMapAppObserver: getEnabledAccountItems()
07-08 14:05:39.440  3898  3898 D BluetoothMap: Bluetooth is Not enabled
,07-08 14:05:39.450  4145  4173 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-08 14:05:39.450  4145  4145 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:39.451  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:05:39.451  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:39.451  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:39.452  4145  4145 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isTurningOn()=true,
,07-08 14:05:39.453  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:39.454  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:39.454  4145  4145 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:39.454  4145  4145 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:39.454  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:39.454  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:39.455  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:39.455  4145  4145 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:39.455  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:39.455  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:39.455  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-08 14:05:39.455  4145  4157 D BluetoothAdapterProperties: ScanMode =  20
,07-08 14:05:39.455  4145  4157 D BluetoothAdapterProperties: State =  11
,07-08 14:05:39.461  4145  4161 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:05:39.461  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:05:39.461  4145  4157 D BluetoothAdapterProperties: Setting state to 12
,07-08 14:05:39.462  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:05:39.463  1723  1883 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:39.463  4145  4157 I BluetoothAdapterState: Entering OnState
,07-08 14:05:39.464  1362  4037 D BluetoothPbap: onBluetoothStateChange: up=true
,07-08 14:05:39.466   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:39.466  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:39.466  3898  3909 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:05:39.468  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:39.468  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:05:39.469  4145  4145 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-08 14:05:39.471  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:05:39.471  3849  3895 I jxcore-log: 
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:39.472  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:39.474  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:39.475  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:05:39.475  1362  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:05:39.476  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:05:39.476  3849  3895 I jxcore-log: 
07-08 14:05:39.478  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:05:39.478  3898  3908 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:05:39.479  1362  1834 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:39.479  4145  4145 D ObexServerSockets: Succeed to create listening sockets 
07-08 14:05:39.479  4145  4145 D ObexServerSockets0: startAccept()
07-08 14:05:39.479  4145  4145 D ObexServerSockets0: prepareForNewConnect()
07-08 14:05:39.479   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:39.480   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:39.480  3898  3909 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:05:39.481  1362  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:05:39.482  4145  4145 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-08 14:05:39.482  4145  4145 D BluetoothSdpJni: SDP Create record success -, handle: 0
07-08 14:05:39.483  1362  1362 D BluetoothInputDevice: Proxy object connected
07-08 14:05:39.483  1362  1362 D HidProfile: Bluetooth service connected
,07-08 14:05:39.484  4145  4181 D ObexServerSockets0: Accepting socket connection...
07-08 14:05:39.485  4145  4182 D ObexServerSockets0: Accepting socket connection...
07-08 14:05:39.485  1362  1362 D BluetoothA2dp: Proxy object connected
07-08 14:05:39.486  3898  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:05:39.486   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:05:39.487   872   872 D BluetoothA2dp: Proxy object connected
07-08 14:05:39.487  1362  1834 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:05:39.489  1362  1379 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:05:39.490  1362  1362 D BluetoothMap: Proxy object connected
07-08 14:05:39.490  1362  1362 D MapProfile: Bluetooth service connected
07-08 14:05:39.490  1362  1362 D BluetoothMap: getConnectedDevices()
07-08 14:05:39.491  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:05:39.492  1362  1362 D PanProfile: Bluetooth service connected
07-08 14:05:39.494   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
07-08 14:05:39.494  4145  4145 D BluetoothMapService: onReceive
07-08 14:05:39.494  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:05:39.494  4145  4145 D BluetoothMapService: STATE_ON
07-08 14:05:39.497  3898  3898 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-08 14:05:39.506  3898  3898 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-08 14:05:39.513  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:05:39.515  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:05:39.515  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:05:39.516  3898  3898 D BluetoothA2dp: Proxy object connected
,07-08 14:05:39.525  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:05:39.530  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:39.533  1362  1362 D BluetoothPbap: Proxy object connected
07-08 14:05:39.533  1362  1362 D PbapServerProfile: Bluetooth service connected
,07-08 14:05:39.534  3898  3898 D BluetoothPbap: Proxy object connected
07-08 14:05:39.534  3898  3898 D PbapServerProfile: Bluetooth service connected
,07-08 14:05:39.547  4145  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:39.565  4145  4191 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:39.565   872   872 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.566  1723  2069 D BluetoothHeadset: Proxy object connected
07-08 14:05:39.566   872   889 D BluetoothHeadset: Proxy object connected
07-08 14:05:39.566  1362  1386 D BluetoothHeadset: Proxy object connected
07-08 14:05:39.566  4145  4191 I BtOppRfcommListener: Accept thread started.
07-08 14:05:39.567  1362  1362 D HeadsetProfile: Bluetooth service connected
,07-08 14:05:39.567   872   872 D BluetoothHeadset: Proxy object connected
07-08 14:05:39.567   872   872 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.580  1362  4037 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.580  1362  1362 D HeadsetProfile: Bluetooth service connected
07-08 14:05:39.580   872   889 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.580   872   889 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.609  3898  3909 D BluetoothHeadset: Proxy object connected
,07-08 14:05:39.611  3898  3898 D HeadsetProfile: Bluetooth service connected
,07-08 14:05:40.268  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:40.280  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:40.282  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:40.345  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-08 14:05:40.345  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-08 14:05:40.346  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:05:40.346  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:40.390  1506  2953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:05:40.390  1506  2953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:05:40.403  3502  3531 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-08 14:05:40.403  3502  3531 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-08 14:05:40.403  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-08 14:05:40.403  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-08 14:05:40.403  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-08 14:05:40.403  3502  3531 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-08 14:05:40.403  3502  3531 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:05:42.937  4145  4157 D BluetoothAdapterState: Current state: ON, message: 23
,07-08 14:05:42.938  4145  4157 D BluetoothAdapterProperties: Setting state to 13
07-08 14:05:42.938  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-08 14:05:42.940  4145  4157 D BluetoothAdapterProperties: onBluetoothDisable()
,07-08 14:05:42.943  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:05:42.946  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:05:42.947  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:05:42.958  4145  4145 D BluetoothMapService: onReceive
,07-08 14:05:42.959  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:05:42.959  4145  4145 D BluetoothMapService: STATE_TURNING_OFF
,07-08 14:05:42.959  4145  4145 D BluetoothMapService: MAP Service closeService in
,07-08 14:05:42.959  4145  4145 D BluetoothMapMasInstance0: MAP Service shutdown
,07-08 14:05:42.959  4145  4145 D ObexServerSockets0: shutdown(block = true)
,07-08 14:05:42.960  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:05:42.960  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-08 14:05:42.961  4145  4182 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,07-08 14:05:42.962  4145  4181 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,07-08 14:05:42.963  4145  4170 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-08 14:05:42.965  4145  4145 I BtOppRfcommListener: stopping Accept Thread
,07-08 14:05:42.966  4145  4191 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-08 14:05:42.966  4145  4191 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:42.970  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:42.971  4145  4145 D HeadsetService: Received stop request...Stopping profile...
,07-08 14:05:42.975  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:42.977  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:05:42.978  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:42.978  3849  3895 I jxcore-log: 
,07-08 14:05:42.978   872   872 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:42.979  1723  1733 D BluetoothHeadset: Proxy object disconnected
07-08 14:05:42.980  1362  1802 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:42.980   872   872 D BluetoothHeadset: Proxy object disconnected,
07-08 14:05:42.980   872   872 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:42.981  3898  3908 D BluetoothHeadset: Proxy object disconnected
,07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:42.981  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:42.982  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:42.983  4145  4145 D A2dpService: Received stop request...Stopping profile...
,07-08 14:05:42.984  4145  4176 D A2dpStateMachine: Exit Disconnected: -1
07-08 14:05:42.986   872   872 D BluetoothA2dp: Proxy object disconnected,
,07-08 14:05:42.986  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:05:42.986  3849  3895 I jxcore-log: 
,07-08 14:05:42.986  4145  4145 V BluetoothAdapterState: isTurningOff()=true,
07-08 14:05:42.986  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:05:42.986  3898  3898 D HeadsetProfile: Bluetooth service disconnected
,07-08 14:05:42.986  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:42.987  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:42.987  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,07-08 14:05:42.987  1362  1362 D BluetoothA2dp: Proxy object disconnected
07-08 14:05:42.988  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:05:42.989  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-08 14:05:42.989  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:05:42.989  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:05:42.989  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:42.989  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-08 14:05:42.990  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:05:42.990  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:42.991  3898  3898 D BluetoothA2dp: Proxy object disconnected
07-08 14:05:42.992  4145  4145 D HidService: Received stop request...Stopping profile...
07-08 14:05:42.992  4145  4145 D HidService: Stopping Bluetooth HidService
07-08 14:05:42.995  1362  1362 D BluetoothInputDevice: Proxy object disconnected
07-08 14:05:42.995  1362  1362 D HidProfile: Bluetooth service disconnected
07-08 14:05:42.995  3898  3898 D BluetoothInputDevice: Proxy object disconnected
,07-08 14:05:42.996  3898  3898 D HidProfile: Bluetooth service disconnected
07-08 14:05:42.996  4145  4145 D HealthService: Received stop request...Stopping profile...
07-08 14:05:42.998  4145  4145 D PanService: Received stop request...Stopping profile...
07-08 14:05:43.000  4145  4145 D BluetoothMapService: Received stop request...Stopping profile...
07-08 14:05:43.000  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-08 14:05:43.000  4145  4145 D BluetoothMapService: stop()
07-08 14:05:43.000  1362  1362 D PanProfile: Bluetooth service disconnected
07-08 14:05:43.001  3898  3898 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:05:43.001  3898  3898 D PanProfile: Bluetooth service disconnected
,07-08 14:05:43.001  4145  4145 D BluetoothMapAppObserver: deinitObservers()
07-08 14:05:43.001  4145  4145 D BluetoothMapAppObserver: removeReceiver()
07-08 14:05:43.002  3898  3898 D BluetoothMap: Proxy object disconnected
07-08 14:05:43.002  4145  4145 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:43.002  1362  1362 D BluetoothMap: Proxy object disconnected
07-08 14:05:43.003  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:05:43.003  3898  3898 D MapProfile: Bluetooth service disconnected
07-08 14:05:43.003  1362  1362 D MapProfile: Bluetooth service disconnected
07-08 14:05:43.003  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.003  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:43.004  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-08 14:05:43.004  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:43.004  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:43.004  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:05:43.004  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:05:43.004  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-08 14:05:43.004  4145  4167 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-08 14:05:43.012  4145  4145 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:05:43.012  4145  4145 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:43.012  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.012  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:43.013  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:05:43.013  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:05:43.013  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-08 14:05:43.013  4145  4145 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:43.013  4145  4145 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:43.013  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.013  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:43.013  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:05:43.013  4145  4161 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-08 14:05:43.014  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:05:43.018  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-08 14:05:43.019  4145  4145 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:43.019  4145  4145 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:43.019  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.019  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:43.019  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:05:43.019  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:05:43.020  4145  4145 D BluetoothMapService: MAP Service closeService in
,07-08 14:05:43.020  4145  4145 V BluetoothAdapterState: isTurningOff()=true
07-08 14:05:43.020  4145  4145 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:43.020  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.020  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:43.021  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26,
,07-08 14:05:43.021  4145  4157 D BluetoothAdapterProperties: Setting state to 15
,07-08 14:05:43.021  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:05:43.021  4145  4157 I BluetoothAdapterState: Entering BleOnState
07-08 14:05:43.021  1723  1734 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:43.021  4145  4145 D BluetoothMapService: cleanup()
07-08 14:05:43.022  4145  4145 D BluetoothMapService: MAP Service closeService in
07-08 14:05:43.022  1362  1386 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:05:43.022   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:43.022  3898  3909 D BluetoothPbap: onBluetoothStateChange: up=false
,07-08 14:05:43.025  3898  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-08 14:05:43.026  1362  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:05:43.026  3898  3909 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-08 14:05:43.027  3898  3908 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:05:43.027  1362  1802 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:43.028   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:43.028   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:05:43.028  3898  3909 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:05:43.029  1362  1834 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:05:43.029  3898  3908 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-08 14:05:43.029   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:05:43.030  1362  4037 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:05:43.030  1362  1386 D BluetoothPan: onBluetoothStateChange on: false
,07-08 14:05:43.032  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:05:43.032  4145  4157 D BluetoothAdapterProperties: Setting state to 16
,07-08 14:05:43.032  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-08 14:05:43.032  4145  4157 D BluetoothAdapterProperties: onBleDisable
07-08 14:05:43.033  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:05:43.033  4145  4158 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:05:43.033  4145  4167 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-08 14:05:43.033  4145  4167 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:05:43.035  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:05:43.036  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:43.037  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:05:43.037  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:43.043  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:05:43.046  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:43.235  4145  4161 I bt_hci  : shut_down
,07-08 14:05:43.236  4145  4165 D bt_hwcfg: hw_epilog_process
,07-08 14:05:43.238  4145  4165 I bt_vendor: low_power_mode_cb
,07-08 14:05:43.262  4145  4165 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-08 14:05:43.262  4145  4165 I bt_vendor: epilog_cb
07-08 14:05:43.263  4145  4165 I bt_hci  : epilog_finished_callback
,07-08 14:05:43.271  4145  4161 I bt_hci_h4: hal_close
,07-08 14:05:43.273  4145  4161 I bt_userial_vendor: device fd = 51 close
,07-08 14:05:43.408  4145  4158 D bt_stack_manager: event_shut_down_stack finished.
07-08 14:05:43.409  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-08 14:05:43.415  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:05:43.415  4145  4157 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-08 14:05:43.417  4145  4145 D BtGatt.GattService: Received stop request...Stopping profile...
07-08 14:05:43.417  4145  4145 D BtGatt.GattService: stop()
07-08 14:05:43.417  4145  4145 D BtGatt.AdvertiseManager: advertise clients cleared
,07-08 14:05:43.422  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:43.422  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:05:43.423  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:43.423  4145  4145 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:05:43.424  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:05:43.426  4145  4157 D BluetoothAdapterProperties: Setting state to 10
,07-08 14:05:43.426  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-08 14:05:43.428  4145  4157 I BluetoothAdapterState: Entering OffState
,07-08 14:05:43.431   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-08 14:05:43.460  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:05:43.460  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:05:43.461  4145  4158 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-08 14:05:43.470  4145  4158 D bt_stack_manager: event_clean_up_stack finished.
,07-08 14:05:43.470  4145  4145 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-08 14:05:43.477  4145  4145 I art     : System.exit called, status: 0
,07-08 14:05:43.478  4145  4145 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:05:43.546   872  1690 I ActivityManager: Process com.android.bluetooth (pid 4145) has died
,07-08 14:05:47.934  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:47.934  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:05:47.941  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:47.942  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d80566e added. We now have 6 listener(s)
,07-08 14:05:47.942  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:47.946  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:47.946  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10e810f added. We now have 7 listener(s)
07-08 14:05:47.946  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:47.948  3849  3887 I System.out: IsBluetoothEnabled
,07-08 14:05:47.958  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:48.011   872   889 I ActivityManager: Start proc 4202:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-08 14:05:48.135  4202  4202 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:05:48.135  4202  4202 D AdapterServiceConfig: Adding A2dpService
07-08 14:05:48.136  4202  4202 D AdapterServiceConfig: Adding HidService
07-08 14:05:48.136  4202  4202 D AdapterServiceConfig: Adding HealthService
,07-08 14:05:48.136  4202  4202 D AdapterServiceConfig: Adding PanService
07-08 14:05:48.136  4202  4202 D AdapterServiceConfig: Adding GattService
07-08 14:05:48.137  4202  4202 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:05:48.153   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1745ea6:true
,07-08 14:05:48.154  4202  4202 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:05:48.159  4202  4202 I bt_bluedroid: init
,07-08 14:05:48.160  4202  4214 I BluetoothAdapterState: Entering OffState
,07-08 14:05:48.164  4202  4215 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-08 14:05:48.165  4202  4215 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:05:48.165  4202  4215 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:05:48.165  4202  4215 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-08 14:05:48.166  4202  4202 I bt_bluedroid: get_profile_interface socket
,07-08 14:05:48.168  4202  4202 I bt_bluedroid: get_profile_interface sdp
,07-08 14:05:48.173  4202  4213 I bt_bluedroid: config_hci_snoop_log
,07-08 14:05:48.173  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-08 14:05:48.176  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,07-08 14:05:48.176   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-08 14:05:48.189  4202  4214 D BluetoothAdapterState: Current state: OFF, message: 0
,07-08 14:05:48.189  4202  4214 D BluetoothAdapterProperties: Setting state to 14
07-08 14:05:48.189  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-08 14:05:48.194  4202  4214 D BluetoothBondStateMachine: make
,07-08 14:05:48.199  4202  4219 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-08 14:05:48.208  4202  4202 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-08 14:05:48.208  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:05:48.212  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:48.213  4202  4202 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:05:48.214  4202  4202 D BtGatt.GattService: Received start request. Starting profile...
,07-08 14:05:48.214  4202  4202 D BtGatt.GattService: start()
07-08 14:05:48.214  4202  4202 I bt_bluedroid: get_profile_interface gatt
,07-08 14:05:48.216  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
07-08 14:05:48.216  4202  4202 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:05:48.228  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:48.229  4202  4202 V BluetoothAdapterState: isTurningOn()=false
07-08 14:05:48.229  4202  4202 V BluetoothAdapterState: isBleTurningOn()=true
,07-08 14:05:48.229  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:48.230  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:05:48.231  4202  4214 I bt_bluedroid: enable
07-08 14:05:48.231  4202  4215 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:05:48.232  4202  4215 I bt_hci  : start_up
,07-08 14:05:48.243  4202  4215 I bt_vendor: alloc value 0xb3a82189
,07-08 14:05:48.243  4202  4215 I bt_vendor: init
07-08 14:05:48.243  4202  4215 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:05:48.244  4202  4215 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:05:48.351  4202  4215 D bt_hci  : start_up starting async portion
07-08 14:05:48.352  4202  4222 I bt_hci  : event_finish_startup
,07-08 14:05:48.352  4202  4222 I bt_hci_h4: hal_open
,07-08 14:05:48.352  4202  4222 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-08 14:05:48.360  4202  4222 I bt_userial_vendor: device fd = 51 open
,07-08 14:05:48.392  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:05:48.424  4202  4222 D bt_hwcfg: Chipset BCM4354A2
,07-08 14:05:48.425  4202  4222 D bt_hwcfg: Target name = [BCM4354A2]
07-08 14:05:48.425  4202  4222 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-08 14:05:49.082  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-08 14:05:49.084  4202  4222 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:05:49.084  4202  4222 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:05:49.201  4202  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
07-08 14:05:49.202  4202  4222 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-08 14:05:49.231  4202  4222 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:05:49.231  4202  4222 I bt_vendor: firmware callback
,07-08 14:05:49.231  4202  4222 I bt_hci  : firmware_config_callback
,07-08 14:05:49.244  4202  4224 I bt_btu  : btu_task pending for preload complete event
,07-08 14:05:49.245  4202  4224 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:05:49.245  4202  4224 I bt_btu  : btu_task received preload complete event
,07-08 14:05:49.258  4202  4224 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:05:49.258  4202  4224 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-08 14:05:49.259  4202  4224 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:05:49.259  4202  4224 I         : BTE_InitTraceLevels -- TRC_AVDT
07-08 14:05:49.259  4202  4224 I         : BTE_InitTraceLevels -- TRC_AVRC
07-08 14:05:49.260  4202  4224 I         : BTE_InitTraceLevels -- TRC_A2D
07-08 14:05:49.260  4202  4224 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-08 14:05:49.260  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTM
,07-08 14:05:49.260  4202  4224 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:05:49.261  4202  4224 I         : BTE_InitTraceLevels -- TRC_PAN
07-08 14:05:49.261  4202  4224 I         : BTE_InitTraceLevels -- TRC_SDP
,07-08 14:05:49.261  4202  4224 I         : BTE_InitTraceLevels -- TRC_GATT
07-08 14:05:49.261  4202  4224 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:05:49.262  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-08 14:05:49.262  4202  4224 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:05:49.396  4202  4224 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ffd9d
,07-08 14:05:49.396  4202  4224 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ffd9d 
,07-08 14:05:49.407  4202  4218 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-08 14:05:49.409  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:05:49.410  4202  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-08 14:05:49.414  4202  4218 D BluetoothAdapterProperties: Name is: Nexus 6
07-08 14:05:49.417  4202  4218 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:05:49.418  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:05:49.418  4202  4218 D bt_hci  : do_postload posting postload work item
,07-08 14:05:49.419  4202  4222 I bt_hci  : event_postload
,07-08 14:05:49.419  4202  4222 I bt_vendor: sco_config_cb
,07-08 14:05:49.419  4202  4222 I bt_hci  : sco_config_callback postload finished.
,07-08 14:05:49.422  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:49.426  4202  4218 D bt_bte_conf: Device ID record 1 : primary
07-08 14:05:49.426  4202  4218 D bt_bte_conf:   vendorId            = 000f
07-08 14:05:49.426  4202  4218 D bt_bte_conf:   vendorIdSource      = 0001
,07-08 14:05:49.427  4202  4222 I bt_vendor: low_power_mode_cb
07-08 14:05:49.427  4202  4218 D bt_bte_conf:   product             = 1200
07-08 14:05:49.427  4202  4218 D bt_bte_conf:   version             = 1436
07-08 14:05:49.427  4202  4218 D bt_bte_conf:   clientExecutableURL = 
,07-08 14:05:49.427  4202  4218 D bt_bte_conf:   serviceDescription  = 
07-08 14:05:49.428  4202  4218 D bt_bte_conf:   documentationURL    = 
07-08 14:05:49.428  4202  4218 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-08 14:05:49.429  4202  4215 D bt_stack_manager: event_start_up_stack finished
07-08 14:05:49.429  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-08 14:05:49.430  4202  4214 D BluetoothAdapterProperties: Setting state to 15
07-08 14:05:49.430  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:05:49.432  4202  4214 I BluetoothAdapterState: Entering BleOnState
,07-08 14:05:49.436  4202  4214 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-08 14:05:49.437  4202  4214 D BluetoothAdapterProperties: Setting state to 11
,07-08 14:05:49.437  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-08 14:05:49.449  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.450  4202  4202 D HeadsetService: Received start request. Starting profile...
,07-08 14:05:49.456  4202  4202 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-08 14:05:49.462  4202  4202 D HeadsetStateMachine: make
,07-08 14:05:49.468  4202  4214 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:05:49.472  4202  4202 D HeadsetStateMachine: max_hf_connections = 1
,07-08 14:05:49.472  4202  4202 I bt_bluedroid: get_profile_interface handsfree
07-08 14:05:49.472  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:05:49.473  4202  4218 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-08 14:05:49.480  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.481  4202  4202 D A2dpService: Received start request. Starting profile...
07-08 14:05:49.482  4202  4202 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:05:49.482  4202  4202 I bt_bluedroid: get_profile_interface avrcp
,07-08 14:05:49.490  4202  4202 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-08 14:05:49.490  4202  4202 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:05:49.490  4202  4202 D A2dpStateMachine: make
,07-08 14:05:49.492  4202  4202 I bt_bluedroid: get_profile_interface a2dp
,07-08 14:05:49.493  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-08 14:05:49.495  4202  4232 D A2dpStateMachine: Enter Disconnected: -2
07-08 14:05:49.498  4202  4202 I BluetoothHidServiceJni: classInitNative: succeeds
07-08 14:05:49.500  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.500  4202  4202 D HidService: Received start request. Starting profile...
07-08 14:05:49.501  4202  4202 I bt_bluedroid: get_profile_interface hidhost
07-08 14:05:49.501  4202  4218 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e13e5
07-08 14:05:49.501  4202  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-08 14:05:49.501  4202  4202 D HidService: setHidService(): set to: null
07-08 14:05:49.502  4202  4202 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-08 14:05:49.503  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.504  4202  4202 D HealthService: Received start request. Starting profile...
07-08 14:05:49.504  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:05:49.505  4202  4202 I bt_bluedroid: get_profile_interface health
07-08 14:05:49.506  4202  4202 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:05:49.507  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.508  4202  4202 D PanService: Received start request. Starting profile...
07-08 14:05:49.508  4202  4202 D BluetoothPanServiceJni: initializeNative(L110): pan
07-08 14:05:49.508  4202  4202 I bt_bluedroid: get_profile_interface pan
07-08 14:05:49.509  4202  4218 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-08 14:05:49.513  4202  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
,07-08 14:05:49.514  4202  4202 D BluetoothMapService: Received start request. Starting profile...
,07-08 14:05:49.514  4202  4202 D BluetoothMapService: start()
,07-08 14:05:49.517  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-08 14:05:49.519  4202  4202 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-08 14:05:49.519  4202  4202 D BluetoothMapAppObserver: createReceiver()
,07-08 14:05:49.520  4202  4202 D BluetoothMapAppObserver: initObservers()
07-08 14:05:49.520  4202  4202 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-08 14:05:49.532  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:49.532  4202  4202 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:49.532  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:49.532  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:05:49.534  4202  4230 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:49.534  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:49.535  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:49.535  4202  4202 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:05:49.535  4202  4202 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:05:49.535  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:05:49.535  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isTurningOff()=false
07-08 14:05:49.538  4202  4202 V BluetoothAdapterState: isTurningOn()=true
07-08 14:05:49.539  4202  4202 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:05:49.539  4202  4202 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:05:49.539  4202  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:05:49.539  4202  4214 D BluetoothAdapterProperties: ScanMode =  20
,07-08 14:05:49.539  4202  4214 D BluetoothAdapterProperties: State =  11
07-08 14:05:49.540  4202  4214 D BluetoothAdapterProperties: Setting state to 12
07-08 14:05:49.540  4202  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:05:49.541  1723  1734 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:05:49.542  4202  4218 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:05:49.542  4202  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:05:49.543  4202  4214 I BluetoothAdapterState: Entering OnState
,07-08 14:05:49.544  1362  4037 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:49.546  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:49.549   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:49.549  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:49.549  3898  3908 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:05:49.551  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:05:49.551  3849  3895 I jxcore-log: 
07-08 14:05:49.552  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:05:49.553  4202  4202 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-08 14:05:49.553  3898  3909 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:05:49.555  1362  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:05:49.555  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:49.558  4202  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:49.560  3898  3908 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:05:49.560  4202  4202 D ObexServerSockets: Succeed to create listening sockets 
07-08 14:05:49.560  4202  4202 D ObexServerSockets0: startAccept()
07-08 14:05:49.560  4202  4202 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:05:49.563  4202  4202 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-08 14:05:49.563  4202  4202 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-08 14:05:49.565  1362  1362 D BluetoothA2dp: Proxy object connected
,07-08 14:05:49.565  4202  4240 D ObexServerSockets0: Accepting socket connection...
07-08 14:05:49.566  4202  4239 D ObexServerSockets0: Accepting socket connection...
,07-08 14:05:49.565  3898  3909 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:05:49.567  3898  3898 D BluetoothA2dp: Proxy object connected
,07-08 14:05:49.571  3898  3898 D BluetoothPan: BluetoothPAN Proxy object connected
,07-08 14:05:49.571  3898  3898 D PanProfile: Bluetooth service connected
,07-08 14:05:49.571  1362  1802 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:05:49.591   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:05:49.591   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:05:49.593  3898  3909 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:05:49.597  3898  3898 D BluetoothMap: Proxy object connected
,07-08 14:05:49.598  3898  3898 D MapProfile: Bluetooth service connected
07-08 14:05:49.598  3898  3898 D BluetoothMap: getConnectedDevices()
,07-08 14:05:49.599  1362  1834 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-08 14:05:49.604  3898  4241 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-08 14:05:49.606  1362  1362 D BluetoothInputDevice: Proxy object connected
07-08 14:05:49.606  1362  1362 D HidProfile: Bluetooth service connected
,07-08 14:05:49.610  3898  3898 D BluetoothInputDevice: Proxy object connected
07-08 14:05:49.610   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:05:49.610  3898  3898 D HidProfile: Bluetooth service connected
,07-08 14:05:49.611   872   872 D BluetoothA2dp: Proxy object connected
,07-08 14:05:49.611  1362  1386 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:05:49.614  1362  1362 D BluetoothMap: Proxy object connected
,07-08 14:05:49.615  1362  1802 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:05:49.615  1362  1362 D MapProfile: Bluetooth service connected
07-08 14:05:49.615  1362  1362 D BluetoothMap: getConnectedDevices()
,07-08 14:05:49.619  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,07-08 14:05:49.619  1362  1362 D PanProfile: Bluetooth service connected
,07-08 14:05:49.620   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,07-08 14:05:49.623  4202  4202 D BluetoothMapService: onReceive
,07-08 14:05:49.623  4202  4202 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:05:49.623  4202  4202 D BluetoothMapService: STATE_ON
,07-08 14:05:49.631  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:05:49.641  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:05:49.643  3898  3898 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:05:49.658  3898  3898 D BluetoothPbap: Proxy object connected
,07-08 14:05:49.658  3898  3898 D PbapServerProfile: Bluetooth service connected
07-08 14:05:49.659  1362  1362 D BluetoothPbap: Proxy object connected
07-08 14:05:49.659  1362  1362 D PbapServerProfile: Bluetooth service connected
07-08 14:05:49.659  4202  4202 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:05:49.659  4202  4202 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:05:49.660   872   872 D BluetoothHeadset: Proxy object connected
07-08 14:05:49.661  1723  1883 D BluetoothHeadset: Proxy object connected
,07-08 14:05:49.662  1362  1834 D BluetoothHeadset: Proxy object connected
,07-08 14:05:49.662   872   872 D BluetoothHeadset: Proxy object connected
07-08 14:05:49.662  1362  1362 D HeadsetProfile: Bluetooth service connected
,07-08 14:05:49.663   872   872 D BluetoothHeadset: Proxy object connected
,07-08 14:05:49.663  3898  3908 D BluetoothHeadset: Proxy object connected
07-08 14:05:49.664  3898  3898 D HeadsetProfile: Bluetooth service connected
,07-08 14:05:49.679  4202  4246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:49.693  1362  1802 D BluetoothHeadset: Proxy object connected
07-08 14:05:49.693  1362  1362 D HeadsetProfile: Bluetooth service connected
07-08 14:05:49.694   872   889 D BluetoothHeadset: Proxy object connected
07-08 14:05:49.694   872   889 D BluetoothHeadset: Proxy object connected
,07-08 14:05:49.714  4202  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:05:49.717  4202  4250 I BtOppRfcommListener: Accept thread started.
,07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:49.976  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:49.984  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:49.988  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:49.988  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f19b59c added. We now have 8 listener(s)
07-08 14:05:49.989  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:49.990  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:05:49.990  3849  3895 I jxcore-log: 
,07-08 14:05:49.995   872  1387 D WifiService: setWifiEnabled: false pid=3849, uid=10000
,07-08 14:05:49.995   872  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:05:50.006  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:50.007   872  1693 D WifiService: setWifiEnabled: true pid=3849, uid=10000
,07-08 14:05:50.007   872  1693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:05:50.022   872  1311 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:50.039  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:50.042  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:50.046  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:50.046  3849  3895 I jxcore-log: 
,07-08 14:05:50.052   872  1311 D WifiConfigStore: loaded 0 passpoint configs
,07-08 14:05:50.053   872  1311 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-08 14:05:50.054   872  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-08 14:05:50.056   872  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-08 14:05:50.056   872  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-08 14:05:50.057   872  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-08 14:05:50.057   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-08 14:05:50.057   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-08 14:05:50.070   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:05:50.070   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-08 14:05:50.072   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:50.122   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-08 14:05:50.122   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:05:50.130   872  1311 E native  : do suspend true
,07-08 14:05:50.145   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:05:50.146   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-08 14:05:50.160   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:05:51.563   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:05:51.685   872  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.31 rxSuccessRate=17.12 delta 1000 -> 994
,07-08 14:05:51.687   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-08 14:05:51.687   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:51.705   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-08 14:05:51.790   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-08 14:05:51.793  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.029  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:52.036  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.040  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.040  3849  3895 I jxcore-log: 
,07-08 14:05:52.045  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-08 14:05:52.047  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-08 14:05:52.060  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c289bcb Bundle[{}]
,07-08 14:05:52.061  3849  3887 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:05:52.061  3849  3887 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-08 14:05:52.062  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-08 14:05:52.063  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-08 14:05:52.063  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-08 14:05:52.064  3849  3887 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-08 14:05:52.072  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-08 14:05:52.072  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-08 14:05:52.072  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-08 14:05:52.072  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-08 14:05:52.073  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-08 14:05:52.073  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.080  3849  3887 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 384)
,07-08 14:05:52.080  3849  3887 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 384)
07-08 14:05:52.080  3849  3887 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 384)
,07-08 14:05:52.081  3849  3887 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 384)
,07-08 14:05:52.084  3849  3887 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 390)
,07-08 14:05:52.084  3849  3887 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 390)
07-08 14:05:52.085  3849  3887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 390)
,07-08 14:05:52.085  3849  3887 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 391)
07-08 14:05:52.087  3849  3887 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 393)
,07-08 14:05:52.090  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.090  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f00ba5 added. We now have 2 listener(s)
07-08 14:05:52.091  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.092  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.092  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.092  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.092  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f6b7a added. We now have 9 listener(s)
,07-08 14:05:52.092  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:52.097  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:05:52.101  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.107  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:52.111  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.111  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:52.111  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.111  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1da8f88 added. We now have 3 listener(s)
,07-08 14:05:52.114  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-08 14:05:52.114  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:05:52.114  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.114  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.114  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.114  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfabd21 added. We now have 10 listener(s)
07-08 14:05:52.114  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.115  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.115  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.115  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.116  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.116  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.117  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-08 14:05:52.117  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:05:52.117  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f00ba5 removed from the list
07-08 14:05:52.117  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.117  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f6b7a removed from the list
07-08 14:05:52.117  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.118  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.118  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:05:52.119  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.119  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:05:52.119  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.119  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f6b7a not in the list
07-08 14:05:52.119  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.119  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:05:52.119  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.119  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfabd21 removed from the list
07-08 14:05:52.119  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.119  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.119  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:05:52.120  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.120  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1da8f88 removed from the list
07-08 14:05:52.120  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:05:52.120  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.120  3849  3895 I jxcore-log: 
,07-08 14:05:52.121  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8c546 added. We now have 2 listener(s)
07-08 14:05:52.123  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.123  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:05:52.123  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.124  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.125  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5b8307 added. We now have 9 listener(s)
,07-08 14:05:52.125  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:52.129  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:05:52.133  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.140  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:52.143  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.143  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:52.143  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.144  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a50a5d added. We now have 3 listener(s)
,07-08 14:05:52.145  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-08 14:05:52.145  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.146  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,07-08 14:05:52.146  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:52.146  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75befd2 added. We now have 10 listener(s)
07-08 14:05:52.146  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.146  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.146  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
07-08 14:05:52.146  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.147  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.147  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.151  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-08 14:05:52.154  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
07-08 14:05:52.154  3849  3895 I jxcore-log: 
07-08 14:05:52.155  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.155  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.162  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.165  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:05:52.165  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:05:52.165  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-08 14:05:52.166  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:05:52.166  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-08 14:05:52.167  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.174  4202  4213 D BtGatt.GattService: registerClient() - UUID=735ab067-b215-472f-839b-919556d688f8
,07-08 14:05:52.176  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=735ab067-b215-472f-839b-919556d688f8, clientIf=5
,07-08 14:05:52.178  3849  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-08 14:05:52.180  4202  4243 D BtGatt.GattService: start scan with filters
,07-08 14:05:52.189  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-08 14:05:52.189  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-08 14:05:52.189  4202  4221 D BtGatt.ScanManager: handling starting scan
,07-08 14:05:52.190  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-08 14:05:52.190  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-08 14:05:52.190  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
07-08 14:05:52.190  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-08 14:05:52.191  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:05:52.192  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.192  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:05:52.193  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.193  3849  3887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-08 14:05:52.193  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.193  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.193  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.194  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:05:52.194  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:05:52.194  4202  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c5e73af
07-08 14:05:52.194  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.194  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.194  3849  3895 I jxcore-log: 
07-08 14:05:52.194  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:05:52.194  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.196  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.197  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.197  3849  3895 I jxcore-log: 
07-08 14:05:52.198  4202  4212 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:05:52.200  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:05:52.200  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.200  4202  4213 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.201  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.202  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:05:52.202  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:05:52.202  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:05:52.202  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.203  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-08 14:05:52.203  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-08 14:05:52.204  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.204  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-08 14:05:52.205  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-08 14:05:52.208  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-08 14:05:52.208  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:05:52.209  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.209  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,07-08 14:05:52.209  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-08 14:05:52.214  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.215  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.216  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.216  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.216  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.216  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:05:52.217  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8c546 removed from the list
,07-08 14:05:52.217  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.217  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.217  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.218  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5b8307 removed from the list
07-08 14:05:52.218  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.218  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:05:52.219  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:05:52.219  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.219  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-08 14:05:52.220  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.221  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:05:52.221  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,07-08 14:05:52.222  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5b8307 not in the list
,07-08 14:05:52.222  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:05:52.222  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.223  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
,07-08 14:05:52.223  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-08 14:05:52.225  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:05:52.226  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:05:52.226  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.226  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.231  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.232  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.232  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-08 14:05:52.232  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.233  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-08 14:05:52.234  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.234  3849  3887 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:05:52.234  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.234  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.234  3849  3895 I jxcore-log: 
,07-08 14:05:52.234  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.234  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.234  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75befd2 removed from the list
07-08 14:05:52.235  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.235  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.235  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:05:52.235  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:05:52.235  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a50a5d removed from the list
,07-08 14:05:52.236  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:05:52.236  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb42815 added. We now have 2 listener(s)
07-08 14:05:52.236  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.236  3849  3895 I jxcore-log: 
07-08 14:05:52.238  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.238  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:05:52.238  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.238  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.238  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.238  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:52.238  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c29a72a added. We now have 9 listener(s)
07-08 14:05:52.238  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.240  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:05:52.243  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.244  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:05:52.244  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.247  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:52.249  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.249  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:52.250  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.250  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14eab8 added. We now have 3 listener(s)
07-08 14:05:52.251  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.252  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:05:52.252  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.252  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.252  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:05:52.253  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.253  3849  3895 I jxcore-log: 
07-08 14:05:52.254  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-08 14:05:52.254  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.254  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.254  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:52.254  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bc3091 added. We now have 10 listener(s)
07-08 14:05:52.254  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.254  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.255  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.255  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:05:52.255  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.255  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.258  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:05:52.258  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.258  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.260  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.260  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:05:52.263  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-08 14:05:52.263  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.264  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:05:52.265  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:05:52.265  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.265  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:05:52.265  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:05:52.266  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-08 14:05:52.266  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.268  4202  4213 D BtGatt.GattService: registerClient() - UUID=04d90112-c078-42dd-9cd9-62dbc761c1f2
,07-08 14:05:52.268  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=04d90112-c078-42dd-9cd9-62dbc761c1f2, clientIf=5
07-08 14:05:52.269  3849  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:05:52.269  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-08 14:05:52.269  4202  4243 D BtGatt.GattService: start scan with filters
07-08 14:05:52.269  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-08 14:05:52.272   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:05:52.272  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-08 14:05:52.272  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:05:52.273  4202  4221 D BtGatt.ScanManager: handling starting scan
07-08 14:05:52.273  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:05:52.273  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:05:52.273  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.273  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:05:52.274  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:05:52.274  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.275  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:05:52.275  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.276  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.276  3849  3895 I jxcore-log: 
,07-08 14:05:52.276  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.276  3849  3887 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:05:52.276  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.276  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.276  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.276  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.276  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.277  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.277  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.277  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb42815 removed from the list
07-08 14:05:52.277  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.277  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c29a72a removed from the list
07-08 14:05:52.277  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.277  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:05:52.277  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.277  3849  3895 I jxcore-log: 
07-08 14:05:52.277   872  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-08 14:05:52.277   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:05:52.277   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:05:52.278  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.278  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:05:52.278  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.278  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:05:52.278  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.279  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c29a72a not in the list
,07-08 14:05:52.279  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:05:52.279  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:05:52.279  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.279  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:05:52.279  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.280  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.280  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:05:52.280  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.280  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:05:52.280  4202  4237 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:05:52.281  4202  4212 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.281  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.282  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-08 14:05:52.282  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:05:52.282  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.282  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:05:52.282  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.282  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.282  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:05:52.282  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:05:52.283  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:05:52.283  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.283  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.283  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.284  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.285  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:05:52.286  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.286  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
,07-08 14:05:52.286  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-08 14:05:52.288  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.288  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.292   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:05:52.294  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.297  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:05:52.297  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.297  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.300   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:52.300  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.300  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.301  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.301   872  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,07-08 14:05:52.301  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:05:52.301  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.301  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.301  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.302  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.302  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.302  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.302  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bc3091 removed from the list
07-08 14:05:52.302  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.302  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.302  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-08 14:05:52.302  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.302  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14eab8 removed from the list
07-08 14:05:52.302  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.302  3849  3895 I jxcore-log: 
07-08 14:05:52.303  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:05:52.303  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1e58d0 added. We now have 2 listener(s)
07-08 14:05:52.303  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.303  3849  3895 I jxcore-log: 
07-08 14:05:52.304  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.304  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.304  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.304  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:52.304  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db60c9 added. We now have 9 listener(s)
07-08 14:05:52.304  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:52.306  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:05:52.306  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:05:52.307  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.307   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
07-08 14:05:52.308  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.311  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:52.312  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:05:52.312  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.312  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:05:52.313  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:52.313  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:05:52.313  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.313  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@441b2ef added. We now have 3 listener(s)
,07-08 14:05:52.315  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.315  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.315  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:05:52.315  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.316  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85831fc added. We now have 10 listener(s)
07-08 14:05:52.316  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:52.316  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.316  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-08 14:05:52.316  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.316  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.316  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:52.318   872  4258 D DhcpClient: Receive thread started
07-08 14:05:52.318  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:05:52.318  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.318  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.318  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.319  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.319  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:05:52.320  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.320  3849  3895 I jxcore-log: 
,07-08 14:05:52.322  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.323  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.323  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.323  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:05:52.323  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-08 14:05:52.323  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:05:52.323  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-08 14:05:52.323  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.323  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.325  4202  4238 D BtGatt.GattService: registerClient() - UUID=7ce9b8bb-b778-4ce8-b520-8630cb89f5f8
,07-08 14:05:52.325  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=7ce9b8bb-b778-4ce8-b520-8630cb89f5f8, clientIf=5
07-08 14:05:52.326  3849  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-08 14:05:52.326  4202  4237 D BtGatt.GattService: start scan with filters
,07-08 14:05:52.328  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-08 14:05:52.328  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-08 14:05:52.328  4202  4221 D BtGatt.ScanManager: handling starting scan
,07-08 14:05:52.328  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:05:52.328  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:05:52.328  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.328  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:05:52.328  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.330  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.330  3849  3895 I jxcore-log: 
07-08 14:05:52.330  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-08 14:05:52.330  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:05:52.330  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.330  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.330  3849  3895 I jxcore-log: 
,07-08 14:05:52.332  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.332  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.332  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.332  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.332  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.332  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.332  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.332  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1e58d0 removed from the list
07-08 14:05:52.332  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.332  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db60c9 removed from the list
07-08 14:05:52.332  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.333  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.333  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:05:52.333  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.333  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.333  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:05:52.333  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:05:52.333  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.334  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.334  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.334  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db60c9 not in the list
07-08 14:05:52.334  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:05:52.334  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-08 14:05:52.334  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.334  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:05:52.334  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.335  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.335  4202  4243 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:05:52.336  4202  4212 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:05:52.336  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.336  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:05:52.336  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:05:52.337  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:05:52.337  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.337  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.337  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.337  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.338  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:05:52.338  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.338  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:05:52.339  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-08 14:05:52.340  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.340  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.343  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.344  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.344  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:05:52.344  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.346  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.347  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.347  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:05:52.347  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.347  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.347  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85831fc removed from the list
,07-08 14:05:52.347  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.347  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.347  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.347  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-08 14:05:52.347  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.347  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.347  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@441b2ef removed from the list
07-08 14:05:52.348  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.348  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f471e8 added. We now have 2 listener(s)
07-08 14:05:52.349  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.349  3849  3895 I jxcore-log: 
,07-08 14:05:52.350  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.350  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.350  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.350  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.350  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.350  3849  3895 I jxcore-log: 
07-08 14:05:52.350  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c396001 added. We now have 9 listener(s)
07-08 14:05:52.350  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:05:52.352  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:05:52.352  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:05:52.352  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.354  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.357  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:52.358  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-08 14:05:52.358  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.358  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:05:52.359  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.359  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:05:52.359  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:05:52.359  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc710e7 added. We now have 3 listener(s)
,07-08 14:05:52.360  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.361  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.361  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-08 14:05:52.362  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.362  3849  3895 I jxcore-log: 
07-08 14:05:52.362  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.362  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:05:52.362  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:05:52.362  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e92c494 added. We now have 10 listener(s)
07-08 14:05:52.363  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.363  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.363  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.363  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.363  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.363  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.363  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:05:52.363  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:05:52.363  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f471e8 removed from the list
07-08 14:05:52.363  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.363  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c396001 removed from the list
07-08 14:05:52.363  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.364  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.364  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:05:52.364  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.364  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.364  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.364  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.364  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.364  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.364  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.365  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c396001 not in the list
,07-08 14:05:52.365  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.365  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.365  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.365  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.365  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.365  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e92c494 removed from the list
07-08 14:05:52.365  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.365  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.365  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.365  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.365  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc710e7 removed from the list
,07-08 14:05:52.366  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:05:52.366  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d added. We now have 2 listener(s)
07-08 14:05:52.367  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-08 14:05:52.367  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:05:52.367  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:05:52.368  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:05:52.368  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 added. We now have 9 listener(s)
07-08 14:05:52.368  3849  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:05:52.369  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:05:52.369  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.370  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:05:52.372  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.374  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:52.376  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.376  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:05:52.376  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:05:52.377  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.378  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:05:52.378  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.378  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-08 14:05:52.378  3849  3887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-08 14:05:52.379  3849  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-08 14:05:52.380  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-08 14:05:52.380  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-08 14:05:52.380  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:05:52.380  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.380  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.380  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.380  3849  3895 I jxcore-log: 
07-08 14:05:52.380  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.380  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.380  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.380  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.380  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:05:52.381  3849  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d removed from the list
07-08 14:05:52.381  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.381  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 removed from the list
,07-08 14:05:52.381  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.381  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.381  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.381  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.381  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.382  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.382  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.382  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.382  3849  3887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-08 14:05:52.383  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.383  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.383  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.383  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.383  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.384  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.384  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.384  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.384  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.384  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.384  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.384  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.384  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.384  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.384  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.384  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.384  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.384  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.386  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-08 14:05:52.386  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:05:52.387  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-08 14:05:52.388  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:05:52.388  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,07-08 14:05:52.388  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:05:52.388  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:05:52.388  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:05:52.388  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.388  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.388  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.388  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.388  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.388  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.388  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.389  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.389  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.389  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.389  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.389  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.389  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.389  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.389  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.389  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.389  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.390  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.390  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.390  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.390  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.390  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.390  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.390  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.390  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.390  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.390  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.390  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.390  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.390  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.391  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.391  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.391  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.391  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.391  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.391  3849  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-08 14:05:52.392  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.395  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:52.397  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:52.397  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:52.397  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.397  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:05:52.397  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.397  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.398   872  1311 E native  : do suspend false
07-08 14:05:52.400  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:52.401  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.401  3849  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:05:52.401  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.402  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.402  3849  3895 I jxcore-log: 
,07-08 14:05:52.404  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.404  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.404  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:05:52.405  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:05:52.405  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:05:52.405  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-08 14:05:52.405  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.407  4202  4238 D BtGatt.GattService: registerClient() - UUID=26e5bd8b-34bb-402c-b863-8c4f193c50be
,07-08 14:05:52.407  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=26e5bd8b-34bb-402c-b863-8c4f193c50be, clientIf=5
07-08 14:05:52.408  3849  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:05:52.408  4202  4213 D BtGatt.GattService: start scan with filters
,07-08 14:05:52.409   872  2118 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:05:52.411  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-08 14:05:52.411  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:05:52.411  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:05:52.411  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:05:52.411  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.411  4202  4221 D BtGatt.ScanManager: handling starting scan
07-08 14:05:52.411  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.414  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-08 14:05:52.417  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-08 14:05:52.417  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:05:52.417  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:05:52.417  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.417  3849  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.417  3849  3849 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:05:52.417  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-08 14:05:52.417  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.417  3849  3887 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:05:52.418  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.418  3849  3895 I jxcore-log: 
07-08 14:05:52.419  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.419  3849  3895 I jxcore-log: 
,07-08 14:05:52.420  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.420  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.421  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.421  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-08 14:05:52.421  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-08 14:05:52.421  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:05:52.421  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.421  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-08 14:05:52.421  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.422  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.422  4202  4213 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:05:52.423  4202  4212 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.423  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.423  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-08 14:05:52.424  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:05:52.424  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.424  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:05:52.424  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
07-08 14:05:52.424  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.424  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.424  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.424  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:05:52.424  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
07-08 14:05:52.424  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-08 14:05:52.424  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:05:52.425  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.425  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.425  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.425  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.425  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.425  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.425  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.425  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-08 14:05:52.425  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
,07-08 14:05:52.425  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.426  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.426  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.426  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:05:52.427  3849  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:05:52.427  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.428  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.430  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.431  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.432  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.432  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.432  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.434  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:05:52.435  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.435  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.435  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.436  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:05:52.436  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.436  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:05:52.436  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:05:52.436  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.436  3849  3895 I jxcore-log: 
07-08 14:05:52.436  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-08 14:05:52.436  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-08 14:05:52.437  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.437  3849  3895 I jxcore-log: 
,07-08 14:05:52.439  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:52.439  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.439  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:05:52.439  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:05:52.439  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-08 14:05:52.440  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.440  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:05:52.441   872  4258 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172777, domain null
07-08 14:05:52.441   872  2118 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172777 seconds
07-08 14:05:52.442  4202  4237 D BtGatt.GattService: registerClient() - UUID=3b8de9e8-0fa3-4b3e-a6cf-5527853762df
07-08 14:05:52.442   872  2118 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
07-08 14:05:52.442  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.442  3849  3895 I jxcore-log: 
,07-08 14:05:52.442  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=3b8de9e8-0fa3-4b3e-a6cf-5527853762df, clientIf=5
07-08 14:05:52.442  3849  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:05:52.443  4202  4238 D BtGatt.GattService: start scan with filters
07-08 14:05:52.443  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:05:52.443  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.445  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-08 14:05:52.445  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:05:52.445  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-08 14:05:52.445  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:05:52.445  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:05:52.445  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:05:52.445  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:05:52.447  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.447  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:05:52.447  3849  3887 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:05:52.447  3849  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.447  3849  3849 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-08 14:05:52.447  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.448  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.448  3849  3895 I jxcore-log: 
,07-08 14:05:52.449  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.449  3849  3895 I jxcore-log: 
,07-08 14:05:52.450  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.450  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.450  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.451  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-08 14:05:52.451  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-08 14:05:52.451  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:05:52.451  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.451  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:05:52.451  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.452  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.452  4202  4212 D BtGatt.GattService: stopScan() - queue size =0
07-08 14:05:52.452  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:05:52.452  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.452  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
,07-08 14:05:52.452  4202  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:05:52.453  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.453  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.453  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.454   872  4258 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
07-08 14:05:52.454  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:05:52.454  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.454  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.454   872  2118 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:05:52.454  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.454  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.454  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.454  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.454  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.454  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.454  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.454  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.455  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.455  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.455  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.455  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.455   372   871 D CommandListener: Setting iface cfg
,07-08 14:05:52.455  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.455  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.455  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.456  3849  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:05:52.457   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
07-08 14:05:52.458  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.458  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:05:52.459  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.459  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.460  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.460  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:05:52.460   872  1311 E native  : do suspend true
07-08 14:05:52.460   872  2118 D DhcpClient: Scheduling renewal in 86399s
,07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:05:52.462  3849  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:05:52.463  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:05:52.464  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-08 14:05:52.464  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.465  3849  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:05:52.465  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.465  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.465  4202  4221 D BtGatt.ScanManager: handling starting scan
07-08 14:05:52.465  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.466  3849  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:05:52.466  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:52.468  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.468  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.468  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:05:52.470  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.470  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:05:52.471  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:05:52.471  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-08 14:05:52.471  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.471  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-08 14:05:52.471  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-08 14:05:52.471  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.473   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-08 14:05:52.474  4202  4238 D BtGatt.GattService: registerClient() - UUID=d4392d52-b240-403d-bdc6-fcafbf85675f
,07-08 14:05:52.474  4202  4218 D BtGatt.GattService: onClientRegistered() - UUID=d4392d52-b240-403d-bdc6-fcafbf85675f, clientIf=5
07-08 14:05:52.474   872  1311 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:05:52.474  3849  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:05:52.474  4202  4212 D BtGatt.GattService: start scan with filters
,07-08 14:05:52.476   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-08 14:05:52.476  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:05:52.476  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.476   872  1313 D ConnectivityService: Adding iface wlan0 to network 102
07-08 14:05:52.477  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-08 14:05:52.477  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:05:52.477  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:05:52.477  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-08 14:05:52.477  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-08 14:05:52.477  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:05:52.478  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:05:52.478  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:05:52.481  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.481  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
07-08 14:05:52.481  3849  3887 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:05:52.481  3849  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-08 14:05:52.481  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.481  3849  3849 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-08 14:05:52.481  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.481  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.481  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.481  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-08 14:05:52.481   872  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-08 14:05:52.481  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:05:52.481  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:05:52.481  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.481  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-08 14:05:52.482  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.482  3849  3895 I jxcore-log: 
,07-08 14:05:52.481  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:05:52.484  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.485  4202  4213 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:05:52.485  4202  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:05:52.486  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:05:52.486  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.486  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.487  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.487  3849  3849 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.487  3849  3849 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:05:52.487  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.487  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.487  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.487  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.487  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.487  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:05:52.487  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
,07-08 14:05:52.487  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.487  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.488  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.488  3849  3895 I jxcore-log: 
07-08 14:05:52.489  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:52.489  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.489  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
07-08 14:05:52.490  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:05:52.490  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.490  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.490  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.490  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.490  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.490  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.490  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.491  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:05:52.491  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:05:52.491  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:05:52.491  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.491  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.491  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.491  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.491  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:05:52.491  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.491  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.491  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.492  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.492  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
,07-08 14:05:52.492  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.492  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.492  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.492  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.492  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.493  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:05:52.493  3849  3895 I jxcore-log: 
07-08 14:05:52.494  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.494  3849  3895 I jxcore-log: 
,07-08 14:05:52.494  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:05:52.494  3849  3895 I jxcore-log: 
07-08 14:05:52.494  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.494  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:05:52.498  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:05:52.498  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-08 14:05:52.498  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.499  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.499  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.499  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.502  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.502  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:05:52.502  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.502  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:05:52.502  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.502  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.503  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.503  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.503  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.503  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-08 14:05:52.503  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.504  3849  3887 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-08 14:05:52.504  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.504  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-08 14:05:52.504  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.504  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:05:52.505  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.505  3849  3895 I jxcore-log: 
07-08 14:05:52.506  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.506  3849  3895 I jxcore-log: 
07-08 14:05:52.504  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.506  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.507  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.507  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.507  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.507  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.507  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.507  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.507  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.507  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.507  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.507  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.507  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.507  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.507  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.507  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.508  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.508  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.508  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.508  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.508  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.509  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-08 14:05:52.509  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.509  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.509  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.510  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.510  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.510  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.510  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
,07-08 14:05:52.510  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.510  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.510  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.510  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.510  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.510  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.510  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.510  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-08 14:05:52.510  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.510  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.510  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.510  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.510  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.511  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.511  3849  3887 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:05:52.511  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.511  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.511  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.512  3849  3887 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-08 14:05:52.512  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.512  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.512  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.513  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.513  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.513  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.513  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.513  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.513  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.513  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.513  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.513  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.513  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.513  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.513  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.513  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.513  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.514  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.514  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.514  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.514  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.514  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.515  3849  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-08 14:05:52.515  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.515  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:05:52.515  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.515  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.515  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.516  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.516  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.516  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.516  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.516  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.516  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.516  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.516  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.516  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.516  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.516  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.516  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.516  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.517  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.517  4202  4221 D BtGatt.ScanManager: handling starting scan
07-08 14:05:52.517  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.517  3849  3887 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:05:52.517  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.517  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.517  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.518  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-08 14:05:52.519  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:05:52.519  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:05:52.519  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:05:52.520  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-08 14:05:52.520   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-08 14:05:52.520   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-08 14:05:52.520  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:05:52.521  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.521  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.521  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.521  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.521  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.522  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.522  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.522   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-08 14:05:52.522  4202  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-08 14:05:52.523  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.523  4202  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:05:52.524   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-08 14:05:52.522  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.524  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.524  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.524  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.524  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.524  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.524  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.525  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.525  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.525  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.525   872  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-08 14:05:52.526  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.526  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.526  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.526  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.526  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.528  3849  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:05:52.529  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:05:52.529  3849  3887 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:05:52.529  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.529  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:05:52.529  4202  4221 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:05:52.529  4202  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-08 14:05:52.530  3849  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:05:52.530  3849  3887 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-08 14:05:52.530  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:05:52.530  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:05:52.531  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:05:52.532  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:05:52.533   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:05:52.533  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:05:52.533  3849  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-08 14:05:52.534  3849  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-08 14:05:52.534  3849  3887 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-08 14:05:52.534  3849  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:05:52.534  3849  3887 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-08 14:05:52.535  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.535  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.535  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.535  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.536  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.536  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.536  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
,07-08 14:05:52.536  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.536  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.536  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.536  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.536  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.536  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.536  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.536  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.536  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.536  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.537  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.537  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.537  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.537  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.537  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.537   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
07-08 14:05:52.537   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-08 14:05:52.538   872  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:05:52.538  3849  3887 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-08 14:05:52.538   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:05:52.538  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.538  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.538  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.538   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-08 14:05:52.539   872  1313 D ConnectivityService:    accepting network in place of null
07-08 14:05:52.539  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.539  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.539  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.539  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.539  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.539  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.539  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.539  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.539  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.539  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.539  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.539   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:05:52.539  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.540  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.540  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.540  4202  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:05:52.540  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.540  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.540  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.540  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.540  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.540  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.541  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.541  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.541  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.541  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.542  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.542  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.542  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.542  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.542  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.542  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.542  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.542  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.542  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.542  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.542  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.542  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.542  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.543  3849  3887 D BluetoothAdapter: STATE_ON
,07-08 14:05:52.543  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.543  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.543  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.543  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.544  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.544  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:05:52.544  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.544  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.544  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.544  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.544  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.545  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.545  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
,07-08 14:05:52.545  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.545  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.545  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.545  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.545  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.545  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:05:52.545  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.545  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.545  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.545  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.546  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.546  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.546  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.546  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.546  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.547  3849  3887 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-08 14:05:52.548  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-08 14:05:52.548  3849  3895 I jxcore-log: 
07-08 14:05:52.548  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.548  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.548  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.548  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.549  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.549  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.549   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=355683, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:05:52.549  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.549  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.549  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.549  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.549  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.549  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.549  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.549  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.549  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.549  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.549  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.550  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.550  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.550  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.550  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.550  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.550  3849  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,07-08 14:05:52.550  3849  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-08 14:05:52.550  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:05:52.550  3849  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-08 14:05:52.550  3849  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-08 14:05:52.551  3849  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-08 14:05:52.551  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:05:52.551  3849  3887 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,07-08 14:05:52.551  3849  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-08 14:05:52.551  3849  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:05:52.551  4202  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:05:52.551  3849  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:05:52.551  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.551  3849  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-08 14:05:52.551  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.551  4202  4221 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:05:52.551  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.551  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.551  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.551  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.552  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.552  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.552  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.552  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.552  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.552  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.552  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.552  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.552  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.552  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.552  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.552  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.553  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.553  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.553  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.553  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.553  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.553  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.553  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.553  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.553  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.553  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.554  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.554  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.554  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.554  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.554  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.554  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.554  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:05:52.554  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.554  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.555  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.555  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.555  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.555  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.555  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.556  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.556  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.556  3849  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-08 14:05:52.557  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.557  4202  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:05:52.557  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:05:52.557  4202  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:05:52.557  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-08 14:05:52.558  3849  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-08 14:05:52.558  3849  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-08 14:05:52.559  3849  3849 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-08 14:05:52.559  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-08 14:05:52.559  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-08 14:05:52.559  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.559  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.559  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:05:52.559  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-08 14:05:52.559  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:05:52.560  3849  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:05:52.560  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.560  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:05:52.560  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:05:52.560  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.560  3849  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.561  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:05:52.561  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.561  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.562  4202  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:05:52.562  4202  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:05:52.562  3849  4264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-08 14:05:52.563  3849  4264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,07-08 14:05:52.562  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.564  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.565  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.565  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:05:52.565  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.565  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.566  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.566  3849  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:05:52.566   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:05:52.568  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:05:52.569  3849  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:05:52.569  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:05:52.569  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.569  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.569  3849  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:05:52.569  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.569  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:05:52.569  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:05:52.569  3849  3849 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:05:52.569  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.569  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.569  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.569  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.569  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.569  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.570  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.570  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:05:52.571  3849  3849 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:05:52.571  3849  3849 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:05:52.571  3849  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-08 14:05:52.571  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:05:52.571  3849  3849 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-08 14:05:52.571  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.571  3849  3849 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-08 14:05:52.571  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.572  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.572  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.572  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.572  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.572  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.573  3849  3887 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,07-08 14:05:52.573  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:05:52.573  3849  3895 I jxcore-log: 
07-08 14:05:52.573  3849  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:05:52.573  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:05:52.573  3849  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:05:52.573  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.573  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.573  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.574  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.574  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.575  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:05:52.575  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.575  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.575  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.575  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.575  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.575  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.575  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.575  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.575  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.575  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.575  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.576  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.576  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.576  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.576  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.576  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.578  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.578  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.579  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.579  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.579  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.579  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.579  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.579  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.579  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.579  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.579  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.579  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.579  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.579  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.579  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.579  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.579  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.580  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.580  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.580  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.580  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.580  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.580  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.580  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.580  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.581  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.581  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.581  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.581  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.581  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.581  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.581  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.581  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.581  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.581  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.581  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.581  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.581  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.581  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.582  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.582  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.582  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:05:52.582  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.582  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.582  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.582  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.583  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.583  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.583  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.583  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.583  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.583  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.583  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.583  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.583  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.583  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.583  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.583  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.583  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.583  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.583  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.584  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.584  3849  3887 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:05:52.584  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.584  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.584  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.584  3849  3887 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-08 14:05:52.584  3849  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-08 14:05:52.585  3849  3849 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-08 14:05:52.585  3849  3887 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-08 14:05:52.586  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:05:52.586  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.586  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:05:52.586  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.586  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.586  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.586  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.586  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.586  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.586  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:05:52.586  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.586  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.586  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.586  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.586  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.586  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.586  3849  3887 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-08 14:05:52.586  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:05:52.587  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.587  3849  3887 D BluetoothLeScanner: could not find callback wrapper
07-08 14:05:52.587  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.587  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.587  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.587  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-08 14:05:52.587  3849  3895 I jxcore-log: 
07-08 14:05:52.587  3849  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:05:52.587  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:52.587  3849  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:05:52.587  3849  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:05:52.588  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.588  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.588  3849  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adafb3d not in the list
07-08 14:05:52.588  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:05:52.588  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.588  3849  3887 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:05:52.588  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.588  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.588  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:05:52.588  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:05:52.588  3849  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:05:52.588  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:05:52.588  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:05:52.589  3849  3887 D BluetoothAdapter: STATE_ON
07-08 14:05:52.589  3849  3887 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:05:52.589  3849  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:05:52.589  3849  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:05:52.589  3849  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f7bf32 not in the list
07-08 14:05:52.589  3849  3887 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
,07-08 14:05:52.589  3849  3887 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-08 14:05:52.589  3849  3887 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-08 14:05:52.589  3849  3887 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-08 14:05:52.589  3849  3887 E com.test.thalitest.ThaliTestRunner: Total duration: 29746 ms
07-08 14:05:52.590  3849  3887 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 29839ms. Plugin should use CordovaInterface.getThreadPool().
07-08 14:05:52.595   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:05:52.598   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-08 14:05:52.598   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:52.600   872   889 D Tethering: MasterInitialState.processMessage what=3
07-08 14:05:52.602   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:05:52.605  3849  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:05:52.606  3849  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:05:52.608  3849  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:05:52.608  3849  3895 I jxcore-log: 
,07-08 14:05:52.647   872  4256 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:80c::200e
,07-08 14:05:52.652  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:05:52.656  1863  2360 I iu.UploadsManager: num queued entries: 0
,07-08 14:05:52.660  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:05:52.661  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-08 14:05:52.663  3977  3977 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:05:52.673  1863  4269 I MDM     : [221] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-08 14:05:52.673  1863  4269 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:05:52.676  1863  4269 V GoogleAuthProtoRequest: [221] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:05:52.668  1863  2360 I iu.UploadsManager: num updated entries: 0
,07-08 14:05:52.678  3977  3977 D SprintDMHelper: simOperator: 
,07-08 14:05:52.679  3977  3977 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-08 14:05:52.688  1863  2360 I iu.SyncManager: NEXT; no task
,07-08 14:05:52.702  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:52.708  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:52.717   872  4256 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:05:52 GMT], X-Android-Received-Millis=[1467979552716], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467979552688]}
,07-08 14:05:52.718   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:05:52.718   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-08 14:05:52.718   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-08 14:05:52.719   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:05:52.764  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-08 14:05:52.764  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-08 14:05:52.764  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:52.765  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:52.796  1863  4269 E MDM     : [221] SitrepService.a: Error sending sitrep.
,07-08 14:05:52.802  3949  4272 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-08 14:05:53.600   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,07-08 14:05:55.212  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:05:55.212  3849  3887 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-08 14:05:55.330  3849  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:05:55.330  3849  3887 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-08 14:06:00.545   872  1313 D ConnectivityService: handlePromptUnvalidated 102
,07-08 14:06:10.807  1656  1758 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-08 14:06:10.807  1656  1758 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-08 14:06:10.856  1506  1506 I ConfigService: onCreate
,07-08 14:06:15.900  1506  1506 I ConfigService: onDestroy
,07-08 14:06:18.749   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381883, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:06:46.156   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:07:11.903   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=435037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:08:13.568  3595  4288 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:08:13.619  3595  4289 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:08:13.633  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:13.637  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:13.672  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-08 14:08:13.672  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-08 14:08:13.672  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:08:13.672  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:13.708  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:13.711  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:13.741  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:08:13.741  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:08:13.742  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:08:13.742  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:13.766  3595  4289 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:08:13.767  3595  4288 E BooksSync: Soft error
07-08 14:08:13.767  3595  4288 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:08:13.767  3595  4288 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:08:13.769  3595  4288 E BooksSync: Sync error
07-08 14:08:13.769  3595  4288 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:08:13.769  3595  4288 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:08:13.769  3595  4288 I BooksSync: Finished books sync
,07-08 14:08:13.779   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 496640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:08:46.345  3595  4291 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:08:46.367  3595  4292 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:08:46.385  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:46.388  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:46.417  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:08:46.418  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:08:46.418  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:08:46.418  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:46.460  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:46.463  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:46.505  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:08:46.505  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:08:46.505  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:08:46.505  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:46.530  3595  4292 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:08:46.532  3595  4291 E BooksSync: Soft error
07-08 14:08:46.532  3595  4291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:08:46.532  3595  4291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:08:46.532  3595  4291 E BooksSync: Sync error
07-08 14:08:46.532  3595  4291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:08:46.532  3595  4291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:08:46.532  3595  4291 I BooksSync: Finished books sync
,07-08 14:08:46.542   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 529430, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:09:17.038  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:17.040  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:17.087  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:09:17.087  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:09:17.087  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:17.087  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:17.113  3540  4296 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:09:17.113  3540  4296 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at czp.a(PG:9087)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:09:17.113  3540  4296 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	... 12 more
07-08 14:09:17.113  3540  4296 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at fal.a(PG:38)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:09:17.113  3540  4296 E HttpOperation: 	... 14 more
,07-08 14:09:17.344  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:09:17.344  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-08 14:09:17.344  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:17.345  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:17.378  3540  4300 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:09:17.378  3540  4300 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:09:17.378  3540  4300 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	... 12 more
07-08 14:09:17.378  3540  4300 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at fal.a(PG:38)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:09:17.378  3540  4300 E HttpOperation: 	... 14 more
,07-08 14:09:17.428  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
07-08 14:09:17.428  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-08 14:09:17.428  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:17.428  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:17.442  3540  4300 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:09:17.442  3540  4300 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at hec.a(PG:42)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at hee.a(PG:102)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at czr.a(PG:65)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at kka.a(PG:108)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:09:17.442  3540  4300 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	... 15 more
07-08 14:09:17.442  3540  4300 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at fal.a(PG:38)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:09:17.442  3540  4300 E HttpOperation: 	... 17 more
,07-08 14:09:17.443  3540  4300 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:09:17.443  3540  4300 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	... 15 more
07-08 14:09:17.443  3540  4300 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	at jdj.a(PG:4089)
07-08 14:09:17.443  3540  4300 E ExperimentLoader: 	... 17 more
,07-08 14:09:17.595   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 282473, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:09:35.423   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=578557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:09:47.732  3034  4302 V KeepSync: Connecting to GoogleApiClient
,07-08 14:09:47.733   872  1387 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:09:47.779  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:47.781  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:47.814  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-08 14:09:47.814  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-08 14:09:47.814  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:47.814  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:47.835  1863  4303 V BaseAuthAsyncOperation: access token request failed
,07-08 14:09:47.836  3034  4302 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:09:47.890  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:09:47.890  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:09:47.890  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:47.890  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:47.912  3034  4302 E KeepSync: IOException
07-08 14:09:47.912  3034  4302 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:09:47.912  3034  4302 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:09:47.912  3034  4302 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:09:47.912  3034  4302 E KeepSync: 	... 10 more
07-08 14:09:47.913  3034  4302 W KeepSync: Sync result 2
,07-08 14:09:47.926   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 571771, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:10:01.182   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=604317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:10:18.175  3595  4307 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:10:18.288  3595  4308 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:10:18.299  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:18.301  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:18.338  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:10:18.338  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:10:18.338  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:10:18.338  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:18.377  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:18.381  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:18.435  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:10:18.435  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:10:18.435  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:10:18.435  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:18.485  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-08 14:10:18.485  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-08 14:10:18.485  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:10:18.485  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:18.497  3595  4308 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:10:18.497  3595  4307 E BooksSync: Soft error
07-08 14:10:18.497  3595  4307 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:10:18.497  3595  4307 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:10:18.498  3595  4307 E BooksSync: Sync error
07-08 14:10:18.498  3595  4307 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:10:18.498  3595  4307 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:10:18.498  3595  4307 I BooksSync: Finished books sync
,07-08 14:10:18.513   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 594708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:10:18.514  3540  4306 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:10:18.514  3540  4306 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at czp.a(PG:9081)
,07-08 14:10:18.514  3540  4306 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:10:18.514  3540  4306 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	... 12 more
07-08 14:10:18.514  3540  4306 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at fal.a(PG:38)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:10:18.514  3540  4306 E HttpOperation: 	... 14 more
,07-08 14:10:18.556  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:10:18.556  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:10:18.556  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:10:18.557  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:18.576  3540  4306 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:10:18.576  3540  4306 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at hec.a(PG:42)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at hee.a(PG:102)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at czr.a(PG:65)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at kka.a(PG:108)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:10:18.576  3540  4306 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	... 15 more
07-08 14:10:18.576  3540  4306 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at fal.a(PG:38)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:10:18.576  3540  4306 E HttpOperation: 	... 17 more
,07-08 14:10:18.577  3540  4306 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:10:18.577  3540  4306 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	... 15 more
07-08 14:10:18.577  3540  4306 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	at jdj.a(PG:4089)
07-08 14:10:18.577  3540  4306 E ExperimentLoader: 	... 17 more
,07-08 14:10:18.690   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 591966, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:10:40.584  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:40.594  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:40.600  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:40.651  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-08 14:10:40.651  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-08 14:10:40.651  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:10:40.651  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:40.685  1506  1516 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:10:40.685  1506  1516 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:10:40.693  3502  3531 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-08 14:10:40.693  3502  3531 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-08 14:10:40.693  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-08 14:10:40.693  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-08 14:10:40.693  3502  3531 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-08 14:10:40.693  3502  3531 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-08 14:10:40.693  3502  3531 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:10:45.716   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:10:48.939  3034  4318 V KeepSync: Connecting to GoogleApiClient
,07-08 14:10:48.939   872  1801 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:10:49.002  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:49.007  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:10:49.044  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:10:49.045  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:10:49.045  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:10:49.045  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:49.065  1863  4319 V BaseAuthAsyncOperation: access token request failed
,07-08 14:10:49.066  3034  4318 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:10:49.129  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:10:49.129  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:10:49.130  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:10:49.130  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:10:49.152  3034  4318 E KeepSync: IOException
07-08 14:10:49.152  3034  4318 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:10:49.152  3034  4318 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:10:49.152  3034  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:10:49.152  3034  4318 E KeepSync: 	... 10 more
,07-08 14:10:49.152  3034  4318 W KeepSync: Sync result 2
,07-08 14:10:49.167   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 623926, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:10:59.900  1863  1863 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-08 14:10:59.906  1863  4320 I ConfigFetchService: running network task: configservice_periodic
,07-08 14:10:59.911  1863  4320 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
07-08 14:10:59.911  1863  4320 E WakeLock: java.lang.IllegalArgumentException
07-08 14:10:59.911  1863  4320 E WakeLock: 	at com.google.android.gms.stats.d.<init>(SourceFile:135)
07-08 14:10:59.911  1863  4320 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:341)
07-08 14:10:59.911  1863  4320 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:159)
07-08 14:10:59.911  1863  4320 E WakeLock: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-08 14:10:59.917  1863  4320 I ConfigFetchService: launchTask
,07-08 14:10:59.936  1506  1506 I ConfigService: onCreate
,07-08 14:10:59.950  1863  1863 I ConfigFetchService: service connected
,07-08 14:10:59.958  1863  1863 D ConfigFetchService: ConfigApi connection successful.
,07-08 14:11:06.783   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:11:09.976  1863  4321 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VDDdTSaQaB3d09ZhA3wP59HSAbO3qBZTXcbH1Xv2Q40mvC6XFZeyAKk0Yr4XjC_MS8UaguWniqPnWsLM6LUC8Xj80U6mjA8ySjf3hKlyrw4xQCWiEzKnWcYn6GCieH80sdfxWhzsiV63zBUYdLy4zPhoYG18umc1cyYxF9rTyxH8V8Di3gaAJupPljKhXP-wFyU6v08HRcY4uCnrP26dzF7Jv4vzSyz_GV9LBQIQNDjYXy2hk
,07-08 14:11:10.040  1863  4321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:11:10.530  1863  4321 I ConfigFetchTask: updating config table for com.google.android.gms
,07-08 14:11:10.576  1863  1863 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,07-08 14:11:10.579  1863  1863 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-08 14:11:10.579  1863  1863 I ConfigFetchService: GmsCore config value changed; rescheduling
,07-08 14:11:10.581  1863  1863 I ConfigFetchService: fetch service done; releasing wakelock
,07-08 14:11:10.598  1863  4326 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,07-08 14:11:10.645  1863  4326 I ConfigFetchService: stopping self
,07-08 14:11:10.740   872   882 I ActivityManager: Start proc 4328:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-08 14:11:10.756  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:10.765  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:10.767  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:10.792  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
07-08 14:11:10.794  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
07-08 14:11:10.794  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:11:10.794  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:11:10.810  1863  4327 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
,07-08 14:11:10.816  4328  4328 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-08 14:11:10.908  4328  4340 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-08 14:11:10.959  4328  4340 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:11:10.983  4328  4340 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:11:11.066  4352  4352 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1583620731.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1583620731.dex
,07-08 14:11:11.099  4328  4328 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-08 14:11:11.117  4352  4352 I dex2oat : dex2oat took 51.612ms (threads: 4) arena alloc=199KB java alloc=41KB native alloc=1642KB free=1685KB
,07-08 14:11:11.291  4328  4328 W InstanceID/Rpc: Found 10011
,07-08 14:11:12.570   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=675704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:11:15.671   872  1739 I ActivityManager: Killing 3713:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-08 14:11:15.899  1506  1506 I art     : Waiting for a blocking GC DisableMovingGc
,07-08 14:11:15.907  1506  1506 I art     : WaitForGcToComplete blocked for 8.545ms for cause DisableMovingGc
07-08 14:11:15.907  1506  1506 I art     : Starting a blocking GC DisableMovingGc
,07-08 14:11:15.911  1506  1506 I ConfigService: onDestroy
,07-08 14:11:17.481  1506  2020 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:11:21.397  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:21.400  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:21.432  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-08 14:11:21.432  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-08 14:11:21.432  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:11:21.432  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:11:21.466  3540  4416 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:11:21.466  3540  4416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:11:21.466  3540  4416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	... 12 more
07-08 14:11:21.466  3540  4416 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at fal.a(PG:38)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:11:21.466  3540  4416 E HttpOperation: 	... 14 more
,07-08 14:11:21.520  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:11:21.520  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:11:21.520  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:11:21.520  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:11:21.540  3540  4416 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:11:21.540  3540  4416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at hec.a(PG:42)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at hee.a(PG:102)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at czr.a(PG:65)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at kka.a(PG:108)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:11:21.540  3540  4416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	... 15 more
07-08 14:11:21.540  3540  4416 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at fal.a(PG:38)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:11:21.540  3540  4416 E HttpOperation: 	... 17 more
,07-08 14:11:21.541  3540  4416 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:11:21.541  3540  4416 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	... 15 more
07-08 14:11:21.541  3540  4416 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	at jdj.a(PG:4089)
07-08 14:11:21.541  3540  4416 E ExperimentLoader: 	... 17 more
,07-08 14:11:21.664   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 684297, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:11:47.050   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:11:55.007  3034  4419 V KeepSync: Connecting to GoogleApiClient
,07-08 14:11:55.008   872  1737 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:11:55.063  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:55.066  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:11:55.099  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:11:55.099  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:11:55.099  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:11:55.100  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:11:55.117  1863  4420 V BaseAuthAsyncOperation: access token request failed
,07-08 14:11:55.119  3034  4419 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:11:55.171  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:11:55.171  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:11:55.172  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:11:55.172  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:11:55.188  3034  4419 E KeepSync: IOException
07-08 14:11:55.188  3034  4419 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:11:55.188  3034  4419 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:11:55.188  3034  4419 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:11:55.188  3034  4419 E KeepSync: 	... 10 more
07-08 14:11:55.188  3034  4419 W KeepSync: Sync result 2
,07-08 14:11:55.203   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 718032, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:11:56.809   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=719944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:12:22.516   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=745650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:12:28.695  3595  4422 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:12:28.751  3595  4423 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:12:28.780  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:28.787  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:28.846  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:12:28.847  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:12:28.847  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:12:28.847  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:12:28.882  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:28.885  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:28.915  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:12:28.916  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:12:28.916  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:12:28.916  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:12:28.938  3595  4423 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:12:28.939  3595  4422 E BooksSync: Soft error
07-08 14:12:28.939  3595  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:12:28.939  3595  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:12:28.939  3595  4422 E BooksSync: Sync error
07-08 14:12:28.939  3595  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:12:28.939  3595  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:12:28.939  3595  4422 I BooksSync: Finished books sync
,07-08 14:12:28.950   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 751711, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:13:21.539  1506  2020 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:13:26.972  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:26.978  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:27.021  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:13:27.021  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:13:27.021  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:13:27.021  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:13:27.040  3540  4429 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:13:27.040  3540  4429 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:13:27.040  3540  4429 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	... 12 more
07-08 14:13:27.040  3540  4429 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at fal.a(PG:38)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:13:27.040  3540  4429 E HttpOperation: 	... 14 more
,07-08 14:13:27.093  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:13:27.093  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:13:27.093  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:13:27.094  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:13:27.111  3540  4429 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:13:27.111  3540  4429 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at hec.a(PG:42)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at hee.a(PG:102)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at czr.a(PG:65)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at kka.a(PG:108)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:13:27.111  3540  4429 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	... 15 more
07-08 14:13:27.111  3540  4429 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at fal.a(PG:38)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:13:27.111  3540  4429 E HttpOperation: 	... 17 more
,07-08 14:13:27.111  3540  4429 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:13:27.111  3540  4429 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	... 15 more
07-08 14:13:27.111  3540  4429 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	at jdj.a(PG:4089)
07-08 14:13:27.111  3540  4429 E ExperimentLoader: 	... 17 more
,07-08 14:13:27.251   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 809743, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:14:06.962  3034  4434 V KeepSync: Connecting to GoogleApiClient
,07-08 14:14:06.962   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:14:07.049  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:14:07.050  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:14:07.075  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:14:07.076  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:14:07.076  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:14:07.076  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:14:07.111  1863  4435 V BaseAuthAsyncOperation: access token request failed
,07-08 14:14:07.112  3034  4434 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:14:07.167  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:14:07.167  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:14:07.167  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:14:07.167  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:14:07.207  3034  4434 E KeepSync: IOException
07-08 14:14:07.207  3034  4434 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:14:07.207  3034  4434 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:14:07.207  3034  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:14:07.207  3034  4434 E KeepSync: 	... 10 more
07-08 14:14:07.207  3034  4434 W KeepSync: Sync result 2
,07-08 14:14:07.225   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 849798, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:14:46.290   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=889424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:14:58.916   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=902050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:15:15.583   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=918717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:15:28.223   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=931357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:15:46.063   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=949197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:15:58.969   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=962103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:16:15.543   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=978677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:16:28.169   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:16:49.125   872   872 I ActivityManager: Start proc 4443:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-08 14:16:49.170  3595  4455 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:16:49.201  4443  4443 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-08 14:16:49.231  4443  4443 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-08 14:16:49.231  4443  4443 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:16:49.231  4443  4443 I GAv4    :   adb logcat -s GAv4
,07-08 14:16:49.237  3595  4457 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:16:49.256  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:49.259  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:49.262  4443  4443 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:16:49.269  4443  4443 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:16:49.301  4443  4460 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:16:49.314  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:16:49.314  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:16:49.314  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:16:49.314  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:16:49.344  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:49.346  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:49.364  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:16:49.364  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:16:49.364  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:16:49.365  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:16:49.389  3595  4457 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:16:49.389  3595  4455 E BooksSync: Soft error
07-08 14:16:49.389  3595  4455 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:16:49.389  3595  4455 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:16:49.389  3595  4455 E BooksSync: Sync error
07-08 14:16:49.389  3595  4455 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:16:49.389  3595  4455 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:16:49.390  3595  4455 I BooksSync: Finished books sync
,07-08 14:16:49.405   872  1387 I ActivityManager: Killing 3639:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-08 14:16:49.407   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1012213, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:17:37.662  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:17:37.666  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:17:37.706  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:17:37.706  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:17:37.706  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:17:37.706  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:17:37.720  3540  4464 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:17:37.720  3540  4464 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:17:37.720  3540  4464 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	... 12 more
07-08 14:17:37.720  3540  4464 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at fal.a(PG:38)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:17:37.720  3540  4464 E HttpOperation: 	... 14 more
,07-08 14:17:37.793  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:17:37.793  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:17:37.793  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:17:37.793  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:17:37.817  3540  4464 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:17:37.817  3540  4464 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at hec.a(PG:42)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at hee.a(PG:102)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at czr.a(PG:65)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at kka.a(PG:108)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:17:37.817  3540  4464 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	... 15 more
07-08 14:17:37.817  3540  4464 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at fal.a(PG:38)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:17:37.817  3540  4464 E HttpOperation: 	... 17 more
,07-08 14:17:37.817  3540  4464 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:17:37.817  3540  4464 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	... 15 more
07-08 14:17:37.817  3540  4464 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	at jdj.a(PG:4089)
07-08 14:17:37.817  3540  4464 E ExperimentLoader: 	... 17 more
,07-08 14:17:37.995   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1060274, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:18:30.298  3034  4468 V KeepSync: Connecting to GoogleApiClient
,07-08 14:18:30.298   872  1387 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:18:30.375  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:18:30.381  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:18:30.436  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-08 14:18:30.436  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:18:30.436  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:18:30.436  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:18:30.469  1863  4469 V BaseAuthAsyncOperation: access token request failed
,07-08 14:18:30.470  3034  4468 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:18:30.546  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:18:30.546  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:18:30.546  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:18:30.547  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:18:30.575  3034  4468 E KeepSync: IOException
07-08 14:18:30.575  3034  4468 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:18:30.575  3034  4468 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:18:30.575  3034  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:18:30.575  3034  4468 E KeepSync: 	... 10 more
07-08 14:18:30.575  3034  4468 W KeepSync: Sync result 2
,07-08 14:18:30.584   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1113279, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:20:16.196   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,07-08 14:23:56.038   872  1301 I PowerManagerService: Waking up from dozing (uid 1000)...
,07-08 14:23:56.039   872   872 V KeyguardServiceDelegate: onStartedWakingUp()
,07-08 14:23:56.042   872   892 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-08 14:23:56.054   872   892 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@3d1ccb5)
,07-08 14:23:56.062   282   282 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
,07-08 14:23:56.063   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
07-08 14:23:56.063   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-08 14:23:56.073  1827  1827 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
07-08 14:23:56.074  3849  3849 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-08 14:23:56.074  3849  3849 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-08 14:23:56.075  1705  1862 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
07-08 14:23:56.075  1705  1862 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-08 14:23:56.076  1705  1862 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-08 14:23:56.076   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:23:56.076  1705  1851 D BrcmNfcJni: RoutingManager::commitRouting
07-08 14:23:56.076  1705  1862 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-08 14:23:56.081   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:23:56.096  3849  3849 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-08 14:23:56.096  3849  3849 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-08 14:23:56.096   872   882 I ActivityManager: Start proc 4485:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-08 14:23:56.101   872  1739 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-08 14:23:56.102   872  1311 E native  : do suspend false
,07-08 14:23:56.113   872  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:23:56.169  4485  4485 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-08 14:23:56.171   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-08 14:23:56.171   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-08 14:23:56.186   872  1693 I ActivityManager: Killing 1807:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,07-08 14:23:56.219   872  1312 D WifiService: Client connection lost with reason: 4
,07-08 14:23:56.280   872   892 I DisplayPowerController: Unblocked screen on after 238 ms
07-08 14:23:56.281   872   892 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-08 14:23:56.281   872   892 I DreamManagerService: Gently waking up from dream.
07-08 14:23:56.282   872   883 I DreamManagerService: Leaving dreamland.
07-08 14:23:56.282   872   887 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-08 14:23:56.314   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,07-08 14:23:56.315   872  1336 D SurfaceControl: Excessive delay in setPowerMode(): 252ms
07-08 14:23:56.315   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-08 14:23:56.857  1705  2105 D NfcService: Discovery configuration equal, not updating.
,07-08 14:23:59.136   872  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-08 14:24:01.063   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1444197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:24:13.183   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:25:29.964  3595  4520 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:25:29.987  1863  4521 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:25:30.021  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.042  3595  4522 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-08 14:25:30.052  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.053  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.089  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: mail
,07-08 14:25:30.090  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-08 14:25:30.090  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:30.090  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:30.097  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:25:30.097  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:25:30.097  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:30.097  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:30.114  1506  1518 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:25:30.114  1506  1518 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:30.116  1863  4521 W SubscribedFeeds: Hard error
,07-08 14:25:30.127   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1532806, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:30.131   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1565235, reason: Periodic
,07-08 14:25:30.146  1506  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:25:30.147  1506  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:25:30.147  1506  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:30.147  1506  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:30.162   872   884 I ActivityManager: Start proc 4523:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,07-08 14:25:30.183  3595  4522 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:25:30.185  3595  4520 E BooksSync: Soft error
07-08 14:25:30.185  3595  4520 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:25:30.185  3595  4520 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:25:30.185  3595  4520 E BooksSync: Sync error
07-08 14:25:30.185  3595  4520 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:25:30.185  3595  4520 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:25:30.185  3595  4520 I BooksSync: Finished books sync
,07-08 14:25:30.190   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1532798, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:25:30.228  4523  4523 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-08 14:25:30.280   872  1744 I ActivityManager: Start proc 4540:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,07-08 14:25:30.311  1827  4536 I GCoreUlr: Uploading GCM registration ID for account#2#
,07-08 14:25:30.311  4540  4540 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-08 14:25:30.327  1827  4536 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:30.327  4540  4540 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@aa0bb8d(com.android.providers.calendar.CalendarProvider2@ba30142)
,07-08 14:25:30.339  1827  4536 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,07-08 14:25:30.346  1827  4536 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-08 14:25:30.369  4523  4523 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-08 14:25:30.371  4523  4523 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-08 14:25:30.377  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,07-08 14:25:30.378  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud.
07-08 14:25:30.378  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:30.378  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:30.404  1827  4536 E GCoreUlr: 
07-08 14:25:30.404  1827  4536 E GCoreUlr: com.google.android.gms.auth.ae: BadAuthentication
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.location.reporting.service.u.b(SourceFile:220)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
07-08 14:25:30.404  1827  4536 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-08 14:25:30.421   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1532917, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:30.422   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1566343, reason: Periodic
,07-08 14:25:30.467   872   884 I ActivityManager: Start proc 4566:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,07-08 14:25:30.474  4523  4565 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-08 14:25:30.516  4566  4566 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-08 14:25:30.519  4523  4565 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:25:30.545  4523  4565 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:25:30.548  4523  4565 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,07-08 14:25:30.570  4566  4581 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-08 14:25:30.603  4566  4580 I Gmail   : getAccountsCursor
,07-08 14:25:30.618  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.635  4566  4566 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-08 14:25:30.687  4566  4591 E Gmail   : Error finding the version of the Email provider.....
07-08 14:25:30.687  4566  4591 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-08 14:25:30.687  4566  4591 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-08 14:25:30.687  4566  4591 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:25:30.687  4566  4591 W EmailMigration: We do not support migrating this version of the Email provider.
,07-08 14:25:30.695  4566  4589 W Gmail   : Sync started for account: account:61035162
,07-08 14:25:30.701  4566  4593 I Gmail   : getAccountsCursor
,07-08 14:25:30.712  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.789   872  1744 I ActivityManager: Start proc 4598:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,07-08 14:25:30.790   872  1690 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-08 14:25:30.826  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:30.827  4566  4609 I Gmail   : Observing account changes for notifications
,07-08 14:25:30.864  4598  4598 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-08 14:25:30.902  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,07-08 14:25:30.902  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud.
07-08 14:25:30.902  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:25:30.903  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:30.935  4598  4598 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-08 14:25:30.968  4598  4598 I Exchange: EasService.onCreate
,07-08 14:25:30.979  4598  4615 I Exchange: RestartPingTask
,07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:153)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:90)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:859)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:419)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:352)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:469)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.Utils.executeAndLog(Utils.java:555)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2853)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:2301)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffsForAccount(CalendarSyncAdapterApiary.java:2182)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:623)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:473)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.android.emailcommon.syncadapter.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:49)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.zzb(Unknown Source)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:141)
07-08 14:25:30.986  4523  4565 E CalendarSyncAdapter: 	... 13 more
,07-08 14:25:31.014  4598  4598 I Exchange: RestartPingsTask did not start any pings.
07-08 14:25:31.014  4598  4598 I Exchange: PSS stopIfIdle
07-08 14:25:31.015  4598  4598 I Exchange: PSS has no active accounts; stopping service.
,07-08 14:25:31.015  4598  4598 I Exchange: onDestroy
,07-08 14:25:31.030   872  1690 I ActivityManager: Killing 3502:com.android.vending/u0a19 (adj 15): empty #17
,07-08 14:25:31.031   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1532911, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:31.033   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1566771, reason: Periodic
,07-08 14:25:31.093  4566  4611 I Gmail   : notifyAccountChanged
,07-08 14:25:31.096  4566  4581 I Gmail   : getAccountsCursor
,07-08 14:25:31.104  4566  4611 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
07-08 14:25:31.107  4566  4611 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-08 14:25:31.111  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:31.132  4566  4611 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
07-08 14:25:31.133  4566  4611 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-08 14:25:31.160   872   884 I ActivityManager: Start proc 4621:com.google.process.gapps/u0a99 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,07-08 14:25:31.177  4566  4589 I Gmail   : notifyAccountChanged
,07-08 14:25:31.190  4621  4621 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-08 14:25:31.212  4621  4621 I GoogleHttpClient: GMS http client unavailable, use old client
,07-08 14:25:31.244   872  1691 I ActivityManager: Start proc 4636:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,07-08 14:25:31.290  4636  4636 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-08 14:25:31.322  4566  4589 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,07-08 14:25:31.342  4540  4540 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
07-08 14:25:31.342  4540  4540 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-08 14:25:31.346   872   882 I ActivityManager: Killing 3898:com.android.settings/1000 (adj 15): empty #17
,07-08 14:25:31.387  4636  4636 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-08 14:25:31.396  4636  4651 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-08 14:25:31.469  4621  4635 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,07-08 14:25:31.476  4566  4588 I Gmail   : getAccountsCursor
,07-08 14:25:31.488  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:31.529  4621  4635 I GoogleHttpClient: GMS http client unavailable, use old client
,07-08 14:25:31.605  4566  4589 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-08 14:25:31.707  4566  4589 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:25:31.758  4636  4651 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-08 14:25:31.758  4636  4651 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-08 14:25:31.802  4636  4651 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-08 14:25:31.843  4566  4589 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:25:31.857  4636  4651 I ContactDirectoryManager: Discovered 0 contact directories in 236ms
,07-08 14:25:31.872  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:31.901  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
07-08 14:25:31.901  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-08 14:25:31.901  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:31.901  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:31.915  1506  2953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:25:31.915  1506  2953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:31.942  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,07-08 14:25:31.942  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> cp without consulting the cloud.
07-08 14:25:31.942  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:31.942  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:31.965  1506  2953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:25:31.965  1506  2953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: innerSync failed
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:269)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:169)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:128)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-08 14:25:31.968  4621  4635 D ContactsSyncAdapter: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:31.996   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1532930, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:31.997   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1566392, reason: Periodic
,07-08 14:25:31.997   872  1739 I ActivityManager: Killing 3915:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,07-08 14:25:32.018  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
07-08 14:25:32.018  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-08 14:25:32.018  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:32.018  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:32.064  1506  2953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:25:32.064  1506  2953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:32.095  4566  4589 I Gmail   : notifyAccountChanged
,07-08 14:25:32.100  4566  4593 I Gmail   : getAccountsCursor
,07-08 14:25:32.111  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:32.144  1863  1863 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-08 14:25:32.150  4566  4589 I Gmail   : notifyAccountChanged
,07-08 14:25:32.152  4566  4580 I Gmail   : getAccountsCursor
,07-08 14:25:32.157  4566  4589 W Gmail   : Sync complete for account: account:61035162
,07-08 14:25:32.162  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:32.180   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1532923, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:32.182   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1566536, reason: Periodic
,07-08 14:25:32.184   872   883 I ActivityManager: Killing 4070:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,07-08 14:25:32.356  4004  4663 I SyncAdapterService: Ignoring sync request for non-current account
,07-08 14:25:32.429  3989  4669 D DelayedSyncController: Delaying sync.
,07-08 14:25:32.489  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
07-08 14:25:32.490  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.511  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.563  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.591  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.627  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.692  1863  1863 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:25:32.785  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,07-08 14:25:32.785  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud.
,07-08 14:25:32.785  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:32.785  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:32.816  1863  4662 E RemindersSync: AuthError [T SyncAdapterThread-1:id=238:priority=5:group=main]
,07-08 14:25:32.882   872   884 I ActivityManager: Start proc 4674:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,07-08 14:25:32.889   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1532935, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:32.891   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1568292, reason: Periodic
,07-08 14:25:32.953  4674  4674 W System  : ClassLoader referenced unknown path: /system/app/Music2/lib/arm
,07-08 14:25:32.961  4674  4674 I MultiDex: VM with version 2.1.0 has multidex support
,07-08 14:25:32.961  4674  4674 I MultiDex: install
,07-08 14:25:32.961  4674  4674 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-08 14:25:32.965   872   884 I ActivityManager: Start proc 4686:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,07-08 14:25:33.000  4674  4674 I MusicStore: Database version: 121
,07-08 14:25:33.036  4686  4686 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-08 14:25:33.082  4674  4674 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,07-08 14:25:33.126  4674  4674 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-08 14:25:33.186  4674  4674 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:25:33.193   872  1389 I ActivityManager: Start proc 4704:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,07-08 14:25:33.235  4674  4674 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-08 14:25:33.236  4674  4674 D AndroidMusic: GMSCore installation verified
07-08 14:25:33.236  4704  4704 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-08 14:25:33.241  4686  4709 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,07-08 14:25:33.253  4674  4674 I ConfigStore: Config Database version: 1
,07-08 14:25:33.294   872   883 I ActivityManager: Killing 3977:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,07-08 14:25:33.353   872  1389 I ActivityManager: Killing 4056:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,07-08 14:25:33.466  4674  4674 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-08 14:25:33.482  1863  4720 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-08 14:25:33.503  4674  4674 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-08 14:25:33.507  4674  4674 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:25:33.513  4674  4674 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
,07-08 14:25:33.514  4674  4674 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-08 14:25:33.517  4674  4723 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,07-08 14:25:33.543  4674  4674 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,07-08 14:25:33.548  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,07-08 14:25:33.556  4674  4674 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,07-08 14:25:33.581  4674  4674 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e4b87ed and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-08 14:25:33.583  4674  4674 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-08 14:25:33.588  4674  4674 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
07-08 14:25:33.590  4674  4674 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-08 14:25:33.592  4674  4674 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:25:33.600  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,07-08 14:25:33.613  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,07-08 14:25:33.627  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:33.646  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.music, service: sj
,07-08 14:25:33.646  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> sj without consulting the cloud.
07-08 14:25:33.646  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:25:33.646  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:25:33.655  1506  2953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:25:33.655  1506  2953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:25:33.660  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-08 14:25:33.667  4674  4723 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,07-08 14:25:33.667  4674  4723 W MusicSyncAdapter: Sync failed due to an authentication issue.
,07-08 14:25:33.668  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-08 14:25:33.673  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-08 14:25:33.674  4674  4674 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-08 14:25:33.677  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-08 14:25:33.684   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1532958, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-08 14:25:33.685  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-08 14:25:33.685   872   884 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1569615, reason: Periodic
,07-08 14:25:33.692  4674  4674 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,07-08 14:25:33.693  4674  4674 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
07-08 14:25:33.694  4674  4674 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,07-08 14:25:33.696  4674  4730 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-08 14:25:33.697  4674  4730 I MusicLeanback: Stop autocaching.
,07-08 14:25:33.701  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-08 14:25:33.703  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-08 14:25:33.779  4674  4674 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-08 14:25:33.789  4674  4674 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,07-08 14:25:33.794  4674  4674 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,07-08 14:25:33.804  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-08 14:25:33.812  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-08 14:25:33.883   872  1691 I ActivityManager: Start proc 4737:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,07-08 14:25:33.885  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-08 14:25:33.893  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-08 14:25:33.895  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-08 14:25:33.898  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-08 14:25:33.899  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-08 14:25:33.962  4737  4737 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-08 14:25:33.975  4737  4737 I MultiDex: VM with version 2.1.0 has multidex support
,07-08 14:25:33.975  4737  4737 I MultiDex: install
07-08 14:25:33.975  4737  4737 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-08 14:25:34.034  4737  4737 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:25:34.064  4737  4737 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:25:34.077  1506  2324 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-08 14:25:34.080  1506  1506 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-08 14:25:34.085  4737  4737 D WearableService: callingUid 10011, callindPid: 4737
,07-08 14:25:34.097  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:25:34.105  1863  1863 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-08 14:25:34.123  4674  4674 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-08 14:25:34.124  4674  4744 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-08 14:25:34.128  1827  2271 E MDM     : [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-08 14:25:34.138  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-08 14:25:34.152   872  1691 I ActivityManager: Killing 3949:com.google.android.talk/u0a61 (adj 15): empty #17
,07-08 14:25:34.167  4737  4753 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-08 14:25:34.188  1863  4757 D LocationInitializer: Restart initialization of location
,07-08 14:25:34.210  1827  1957 W GCoreFlp: No location to return for getLastLocation()
,07-08 14:25:34.210  1506  4759 W FusedLocationProvider: location=null
,07-08 14:25:35.314  4523  4551 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-08 14:25:35.703  4566  4585 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-08 14:25:35.995  4598  4614 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-08 14:25:36.647   872  1744 I ActivityManager: Killing 4328:com.google.android.youtube/u0a86 (adj 15): empty #17
,07-08 14:25:37.422   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1540557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:25:38.449  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-08 14:25:38.471  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-08 14:25:38.485  4674  4674 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-08 14:25:38.486  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@e89c4d0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-08 14:25:38.497  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-08 14:25:38.503  4674  4766 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-08 14:25:38.503  4674  4766 I MusicLeanback: Stop autocaching.
,07-08 14:25:38.507  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-08 14:25:38.517  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-08 14:25:38.518  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-08 14:25:38.527  4674  4674 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-08 14:25:38.527  4674  4674 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-08 14:25:38.530  4674  4674 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-08 14:25:38.539  4674  4769 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-08 14:25:38.540  4674  4674 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-08 14:25:39.136   872  1722 I ActivityManager: Killing 4443:com.google.android.deskclock/u0a44 (adj 15): empty #17
,07-08 14:25:39.226   872  1801 I ActivityManager: Killing 3540:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,07-08 14:25:56.116  1827  2338 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:25:57.035   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-08 14:25:57.045  1656  1656 I Keyboard.Facilitator: onFinishInput()
,07-08 14:25:57.686  3849  3849 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-08 14:25:57.686  3849  3849 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-08 14:25:57.722  3849  3849 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c289bcb Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f38e473, 16908290=android.view.AbsSavedState$1@f38e473}, android:focusedViewId=100}]}],
07-08 14:25:57.722  3849  3849 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-08 14:25:57.722  3849  3849 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-08 14:25:57.722  3849  3849 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-08 14:25:57.725   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-08 14:25:57.761   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,07-08 14:25:57.761   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
07-08 14:25:57.761   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-08 14:25:57.988   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-08 14:25:57.992   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-08 14:25:57.997   872  1336 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
07-08 14:25:57.999   872   892 I DreamManagerService: Entering dreamland.
07-08 14:25:58.000   872   892 I PowerManagerService: Dozing...
07-08 14:25:58.002   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-08 14:25:58.066   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:58.076   872  1311 E native  : do suspend true
,07-08 14:25:58.196   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1561330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:25:58.212   376  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-08 14:25:58.212   376  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,07-08 14:26:03.767   872   884 I ActivityManager: Start proc 4778:com.google.android.apps.plus/u0a74 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,07-08 14:26:04.264  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:26:04.266  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:26:04.329  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:26:04.329  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:26:04.329  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:26:04.329  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:26:04.349  4778  4797 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-08 14:26:04.349  4778  4797 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at blb.a(PG:3937)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at czp.a(PG:18188)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:26:04.349  4778  4797 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	... 12 more
07-08 14:26:04.349  4778  4797 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at fal.a(PG:38)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:26:04.349  4778  4797 E HttpOperation: 	... 14 more
,07-08 14:26:04.387  1506  1939 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-08 14:26:04.387  1506  1939 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-08 14:26:04.387  1506  1939 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:26:04.387  1506  1939 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:26:04.401  4778  4797 E HttpOperation: [getmobileexperiments] Unexpected exception
07-08 14:26:04.401  4778  4797 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jdm.a(PG:82)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jcs.o(PG:406)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jcn.a(PG:1379)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jcs.i(PG:143)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at hec.a(PG:42)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at hee.a(PG:102)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at czr.a(PG:65)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at kka.a(PG:108)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at czp.a(PG:19176)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at czp.a(PG:9081)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at czq.run(PG:1686)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:26:04.401  4778  4797 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jdj.a(PG:4091)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jdj.a(PG:1125)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jdm.a(PG:77)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	... 15 more
,07-08 14:26:04.401  4778  4797 E HttpOperation: Caused by: faj: BadAuthentication
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at fal.a(PG:38)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	at jdj.a(PG:4089)
07-08 14:26:04.401  4778  4797 E HttpOperation: 	... 17 more
,07-08 14:26:04.401  4778  4797 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-08 14:26:04.401  4778  4797 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jdm.a(PG:82)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jcs.o(PG:406)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jcn.a(PG:1379)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jcs.i(PG:143)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at hec.a(PG:42)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at hee.a(PG:102)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at czr.a(PG:65)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at kka.a(PG:108)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at czp.a(PG:19176)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at czp.a(PG:9081)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at czq.run(PG:1686)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jdj.a(PG:4091)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jdj.a(PG:1125)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jdm.a(PG:77)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	... 15 more
,07-08 14:26:04.401  4778  4797 E ExperimentLoader: Caused by: faj: BadAuthentication
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at fal.a(PG:38)
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	at jdj.a(PG:4089),
07-08 14:26:04.401  4778  4797 E ExperimentLoader: 	... 17 more
,07-08 14:26:04.566   872  1693 I ActivityManager: Killing 3034:com.google.android.keep/u0a79 (adj 15): empty #17
07-08 14:26:04.566   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1560906, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:26:07.076   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1570210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:26:23.636   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1586770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:26:33.063   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1596197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:26:55.509   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1618643, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:26:57.047  1656  1758 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-08 14:26:57.048  1656  1758 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-08 14:26:57.103  1506  1506 I ConfigService: onCreate
,07-08 14:27:02.188  1506  1506 I ConfigService: onDestroy
,07-08 14:27:15.743   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1638877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:27:16.507   872   884 I ActivityManager: Start proc 4805:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,07-08 14:27:16.622  4805  4805 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,07-08 14:27:16.915  4805  4821 V KeepSync: Connecting to GoogleApiClient
07-08 14:27:16.916   872  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-08 14:27:16.956  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:27:16.957  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:27:16.988  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:27:16.988  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:27:16.988  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:27:16.988  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:27:17.005  1863  4826 V BaseAuthAsyncOperation: access token request failed
,07-08 14:27:17.007  4805  4821 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:27:17.092  1506  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:27:17.092  1506  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:27:17.092  1506  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:27:17.092  1506  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:27:17.109  4805  4821 E KeepSync: IOException
07-08 14:27:17.109  4805  4821 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:27:17.109  4805  4821 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
,07-08 14:27:17.109  4805  4821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:27:17.109  4805  4821 E KeepSync: 	... 10 more
07-08 14:27:17.110  4805  4821 W KeepSync: Sync result 2
,07-08 14:27:17.116   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1639559, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:27:17.519   872  1739 I ActivityManager: Killing 4485:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,07-08 14:27:21.644  4805  4812 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@daeb59)
,07-08 14:27:31.010  1506  2020 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:27:37.289   872  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1660423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-08 14:28:41.245  4832  4832 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:28:41.250  4832  4832 D AndroidRuntime: CheckJNI is OFF
07-08 14:28:41.286  4832  4832 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:28:41.328  4832  4832 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:28:41.348  4832  4832 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-08 14:28:41.358   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-08 14:28:41.359   872   885 I ActivityManager: Killing 3849:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-08 14:28:41.453   872   883 D GraphicsStats: Buffer count: 2
07-08 14:28:41.453   872  1691 I WindowState: WIN DEATH: Window{ae80bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-08 14:28:41.454   872  1312 D WifiService: Client connection lost with reason: 4
07-08 14:28:41.495   872   897 W PackageSettings: Skipping PackageSetting{6e1bde0 com.example.hello/10273} due to missing metadata
07-08 14:28:41.524   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-08 14:28:41.525   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-08 14:28:41.526   872   885 E ActivityManager: Failure starting process com.test.thalitest
07-08 14:28:41.526   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-08 14:28:41.526   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:28:41.526   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:41.526   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:28:41.526   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-08 14:28:41.527   872   885 I ActivityManager:   Force finishing activity ActivityRecord{9e59218 u0 com.test.thalitest/.MainActivity t2}
07-08 14:28:41.533   872   897 I art     : Starting a blocking GC Explicit
07-08 14:28:41.560   872   883 W ActivityManager: Spurious death for ProcessRecord{df5251b 0:com.test.thalitest/u0a0}, curProc for 3849: null
07-08 14:28:41.613   872   897 I art     : Explicit concurrent mark sweep GC freed 36926(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 28MB/43MB, paused 834us total 77.784ms
07-08 14:28:41.633   872   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-08 14:28:41.638  4832  4832 I art     : System.exit called, status: 0
07-08 14:28:41.639  4832  4832 I AndroidRuntime: VM exiting with result code 0.
07-08 14:28:41.695   872   897 I ActivityManager: Start proc 4842:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
07-08 14:28:41.695   872   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-08 14:28:41.725   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-08 14:28:41.732  1827  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-08 14:28:41.733  4202  4202 D BluetoothMapAppObserver: onReceive
07-08 14:28:41.733  4202  4202 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-08 14:28:41.742   872  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-08 14:28:41.746  3661  3661 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-08 14:28:41.748  1656  1656 I Keyboard.Facilitator: resetDictionaries() : en_US
07-08 14:28:41.753  1656  4855 I Keyboard.Facilitator.DecoderInitializer: run()
07-08 14:28:41.756  1656  4855 I Decoder : createOrResetDecoder
07-08 14:28:41.775   872  1737 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3849 uid 10000
07-08 14:28:41.776  1656  1656 I Keyboard.Facilitator: onFinishInput()
07-08 14:28:41.786  4636  4651 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
07-08 14:28:41.788  4636  4651 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-08 14:28:41.788  4636  4651 E AndroidRuntime: Process: android.process.acore, PID: 4636
07-08 14:28:41.788  4636  4651 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:41.788  4636  4651 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:28:41.791   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-08 14:28:41.792   872   884 E PackageManager: Failed to write settings, restoring backup
07-08 14:28:41.792   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-08 14:28:41.792   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-08 14:28:41.792   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-08 14:28:41.792   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-08 14:28:41.792   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-08 14:28:41.792   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:28:41.792   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:41.792   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:28:41.794  1723  1723 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-08 14:28:41.797   872   885 E DropBoxManagerService: Can't write: system_server_wtf
07-08 14:28:41.797   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-08 14:28:41.797   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:28:41.797   872   885 E DropBoxManagerService: 	... 13 more
07-08 14:28:41.798   872  1309 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-08 14:28:41.809   872  1722 I ActivityManager: Start proc 4859:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-08 14:28:41.822  1506  1506 I ConfigService: onCreate
07-08 14:28:41.829  4636  4651 I Process : Sending signal. PID: 4636 SIG: 9
07-08 14:28:41.831   872  4872 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:28:41.831   872  4872 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:28:41.831   872  4872 E DropBoxManagerService: 	... 5 more
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-08 14:28:41.835  1506  4870 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-08 14:28:41.838  1506  4870 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:28:41.842  1506  4870 W SQLiteOpenHelper: Opened config.db in read-only mode
07-08 14:28:41.845   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-08 14:28:41.859  4859  4859 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-08 14:28:41.865  1656  4855 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-08 14:28:41.878  1740  1841 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-08 14:28:41.886  1656  4855 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-08 14:28:41.889  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-08 14:28:41.889  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-08 14:28:41.891   872  1722 I ActivityManager: Start proc 4874:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
07-08 14:28:41.892  1740  1841 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-08 14:28:41.892  1740  1841 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1740
07-08 14:28:41.892  1740  1841 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:41.892  1740  1841 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:28:41.893   872  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-08 14:28:41.894   872  4880 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:28:41.894   872  4880 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:28:41.894   872  4880 E DropBoxManagerService: 	... 5 more
07-08 14:28:41.907   872  1801 I ActivityManager: Start proc 4887:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
07-08 14:28:41.918  1740  1841 I Process : Sending signal. PID: 1740 SIG: 9
07-08 14:28:41.925   872  1801 I ActivityManager: Process android.process.acore (pid 4636) has died
07-08 14:28:41.925   872  1801 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
07-08 14:28:41.927  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-08 14:28:41.927  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-08 14:28:41.927  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-08 14:28:41.927  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-08 14:28:41.929  1656  4855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-08 14:28:41.929  1656  4855 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-08 14:28:41.929  1656  4855 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-08 14:28:41.930  1656  4855 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-08 14:28:41.930  1656  4855 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-08 14:28:41.930  1656  4855 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-08 14:28:41.947  4887  4887 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
07-08 14:28:41.956   872  1691 I ActivityManager: Killing 3595:com.google.android.apps.books/u0a34 (adj 15): empty #17
07-08 14:28:41.981   872  1300 W InputDispatcher: channel '8273aef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
07-08 14:28:41.981   872  1300 E InputDispatcher: channel '8273aef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
07-08 14:28:41.983   872   883 D GraphicsStats: Buffer count: 1
07-08 14:28:41.983   872  1739 I WindowState: WIN DEATH: Window{8273aef u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-08 14:28:41.983   872  1739 W InputDispatcher: Attempted to unregister already unregistered input channel '8273aef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
07-08 14:28:42.001   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1740) has died
07-08 14:28:42.001   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 10925ms
07-08 14:28:42.002   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-08 14:28:42.018   872   885 I ActivityManager: Start proc 4902:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:28:42.063  4902  4902 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:28:42.063  4902  4902 D AndroidRuntime: Shutting down VM
07-08 14:28:42.071  4902  4902 E AndroidRuntime: FATAL EXCEPTION: main
07-08 14:28:42.071  4902  4902 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4902
07-08 14:28:42.071  4902  4902 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-08 14:28:42.071  4902  4902 E AndroidRuntime: 	... 10 more
07-08 14:28:42.073   872  1387 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-08 14:28:42.073  4902  4902 I Process : Sending signal. PID: 4902 SIG: 9
07-08 14:28:42.076   872  4919 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:28:42.076   872  4919 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:28:42.076   872  4919 E DropBoxManagerService: 	... 5 more
07-08 14:28:42.083  1863  4917 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-08 14:28:42.083  1863  4917 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-08 14:28:42.087  1863  4917 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-08 14:28:42.088  1863  4917 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-08 14:28:42.099   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4902) has died
07-08 14:28:42.100   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-08 14:28:42.110  4887  4887 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-08 14:28:42.113   872   885 I ActivityManager: Start proc 4921:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-08 14:28:42.150  4887  4887 E RollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/user/0/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".

```
