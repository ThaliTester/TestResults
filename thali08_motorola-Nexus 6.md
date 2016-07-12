#### Test 757892685a40176_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-12 17:45:08.454  2910  3645 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
07-12 17:45:08.455   875  1707 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:45:08.554  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 17:45:08.555  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:45:08.555  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:08.555  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:08.571  1804  3646 V BaseAuthAsyncOperation: access token request failed
07-12 17:45:08.573  2910  3645 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-12 17:45:08.607  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 17:45:08.607  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:45:08.607  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:08.607  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:08.620  2910  3645 E KeepSync: IOException
07-12 17:45:08.620  2910  3645 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:45:08.620  2910  3645 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:45:08.620  2910  3645 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:45:08.620  2910  3645 E KeepSync: 	... 10 more
07-12 17:45:08.620  2910  3645 W KeepSync: Sync result 2
07-12 17:45:08.628   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 160314, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
07-12 17:45:09.041  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:45:09.089  3647  3647 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 17:45:09.093  3647  3647 D AndroidRuntime: CheckJNI is OFF
07-12 17:45:09.130  3647  3647 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 17:45:09.169  3647  3647 I Radio-JNI: register_android_hardware_Radio DONE
07-12 17:45:09.188  3647  3647 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 17:45:09.192   875  1379 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 17:45:09.237   875  1379 I ActivityManager: Start proc 3660:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 17:45:09.240  3647  3647 D AndroidRuntime: Shutting down VM
07-12 17:45:09.262  1488  3671 I VacuumService: Vacuum at: now=1468338309262 tag=VacuumService
07-12 17:45:09.308  3660  3660 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-12 17:45:09.335  3660  3660 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-12 17:45:09.342  3660  3660 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1340-1342)
07-12 17:45:09.342  3660  3660 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:09.358  3660  3660 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d61bae8}
07-12 17:45:09.358  3660  3660 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:09.359  3660  3660 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:45:09.365  3660  3660 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 17:45:09.367  3660  3660 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 17:45:09.384  3660  3660 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 17:45:09.394  3660  3660 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:09.395  3660  3660 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:09.395  3660  3660 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 17:45:09.395  3660  3660 I Adreno  : Build Date                       : 10/20/15
07-12 17:45:09.395  3660  3660 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 17:45:09.395  3660  3660 I Adreno  : Local Branch                     : M14
07-12 17:45:09.395  3660  3660 I Adreno  : Remote Branch                    : 
07-12 17:45:09.395  3660  3660 I Adreno  : Remote Branch                    : 
07-12 17:45:09.395  3660  3660 I Adreno  : Reconstruct Branch               : 
07-12 17:45:09.420  1488  3673 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
07-12 17:45:09.422  1488  3673 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-12 17:45:09.444   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f4ee33:true
07-12 17:45:09.453  1488  3673 W Uploader:  no longer exists, so no auth token.
,07-12 17:45:09.491  3660  3660 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:45:09.505  3660  3660 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-12 17:45:09.573  3660  3703 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 17:45:09.591  3660  3689 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-12 17:45:09.624  3660  3703 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 17:45:09.652  1650  1650 I Keyboard.Facilitator: onFinishInput()
07-12 17:45:09.688  3660  3660 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3660
07-12 17:45:09.688   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +421ms (total +472ms)
07-12 17:45:09.738  3660  3660 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 17:45:09.873  3660  3704 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1656751824
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 17:45:09.878  3660  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f5969f added. We now have 1 listener(s)
07-12 17:45:09.881  3660  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-12 17:45:09.882  3660  3704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:09.882  3660  3704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:09.882  3660  3704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:45:09.885  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:45:09.886  3660  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e76a4a added. We now have 1 listener(s)
07-12 17:45:09.886  3660  3704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:09.888   875  1305 D WifiService: New client listening to asynchronous messages
07-12 17:45:09.891  3660  3704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-12 17:45:09.892  3660  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:09.892  3660  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:45:09.892  3660  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:45:09.892  3660  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 17:45:09.894  3660  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:09.895  3660  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:09.898  3660  3704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:09.898  3660  3704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:45:09.899  3660  3704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:09.900  3660  3704 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:09.900  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:09.903  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:09.921  1488  3673 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-12 17:45:09.921  1488  3673 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 17:45:09.921  1488  3673 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:09.921  1488  3673 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:09.925  3660  3660 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-12 17:45:09.933  1488  3673 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 17:45:09.933  1488  3673 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 17:45:09.933  1488  3673 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-12 17:45:10.247  1488  3673 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-12 17:45:10.247  1488  3673 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 17:45:10.247  1488  3673 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:10.247  1488  3673 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:10.268  1488  3673 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 17:45:10.268  1488  3673 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 17:45:10.268  1488  3673 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-12 17:45:10.745  3660  3714 W jxcore-log: Initializing JXcore engine
07-12 17:45:10.745  3660  3714 W jxcore-log: JXcore engine is ready
07-12 17:45:10.783  3714  3714 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8989 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
07-12 17:45:10.783  3714  3714 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9592]" dev="sockfs" ino=9592 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 17:45:10.783  3714  3714 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 17:45:10.783  3714  3714 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25829]" dev="sockfs" ino=25829 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-12 17:45:10.796  3660  3714 W jxcore-log: Starting JXcore engine
07-12 17:45:10.888   875  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
07-12 17:45:10.915  1488  3673 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-12 17:45:10.916  1488  3673 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 17:45:10.916  1488  3673 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:10.916  1488  3673 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:10.917  3660  3714 W jxcore-log: Platform android
07-12 17:45:10.917  3660  3714 W jxcore-log: 
07-12 17:45:10.917  3660  3714 W jxcore-log: Process ARCH arm
07-12 17:45:10.917  3660  3714 W jxcore-log: 
07-12 17:45:10.938  1488  3673 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 17:45:10.938  1488  3673 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 17:45:10.938  1488  3673 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 17:45:11.117  3660  3714 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:45:11.117  3660  3714 I jxcore-log: 
,07-12 17:45:11.118  3660  3714 W jxcore-log: JXcore engine is started,
,07-12 17:45:11.126  3660  3704 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:45:11.130  3660  3660 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:45:14.477   875  2087 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:21.287  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 17:45:21.287  3660  3714 I jxcore-log: 
,07-12 17:45:21.289  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 17:45:21.289  3660  3714 I jxcore-log: 
,07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:21.302  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:21.309  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:21.311  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 17:45:21.311  3660  3714 I jxcore-log: 
,07-12 17:45:21.313  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 17:45:21.313  3660  3714 I jxcore-log: 
,07-12 17:45:21.648  3660  3714 I jxcore-log: Unit Test app is loadeded
07-12 17:45:21.648  3660  3714 I jxcore-log: 
,07-12 17:45:21.653  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:21.653  3660  3714 I jxcore-log: 
,07-12 17:45:21.656  3660  3714 I jxcore-log: runUTtestsBefore
07-12 17:45:21.656  3660  3714 I jxcore-log: 
,07-12 17:45:21.657  3660  3714 D JXMOBILE: Running tests
,07-12 17:45:21.676  3660  3660 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 17:45:21.719  3660  3714 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-12 17:45:21.719  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-12 17:45:21.719  3660  3714 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-12 17:45:21.719  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-12 17:45:21.719  3660  3714 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-12 17:45:21.719  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-12 17:45:21.721  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:21.721  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-12 17:45:21.721  3660  3714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-12 17:45:21.721  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:21.721  3660  3714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-12 17:45:21.721  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:21.721  3660  3714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-12 17:45:21.721  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-12 17:45:21.722  3660  3714 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-12 17:45:21.723  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:21.723  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b86ae0 added. We now have 2 listener(s)
07-12 17:45:21.723  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:21.728  3660  3714 D BluetoothAdapter: enable(): BT is already enabled..!
07-12 17:45:21.728   875   885 D WifiService: setWifiEnabled: true pid=3660, uid=10000
07-12 17:45:21.728   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:21.730  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:21.730  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@855f199 added. We now have 3 listener(s)
07-12 17:45:21.730  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:21.746  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:21.746  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18aac5e added. We now have 4 listener(s)
07-12 17:45:21.746  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:21.748  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:21.748  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@744383f added. We now have 5 listener(s)
07-12 17:45:21.749  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:21.752   875  1743 D WifiService: setWifiEnabled: false pid=3660, uid=10000
07-12 17:45:21.752   875  1743 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:21.764  2555  2602 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:21.765  2555  2602 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:21.765  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-12 17:45:21.767  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:21.767  2555  2602 D BluetoothAdapterProperties: onBluetoothDisable()
,07-12 17:45:21.783  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:21.784  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:21.784  2555  2602 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:21.793  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:21.793  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:21.786  2555  2607 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:21.794  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:21.792   875  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-12 17:45:21.803   875  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-12 17:45:21.803   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:21.803   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:21.805  2555  2555 D HeadsetService: Received stop request...Stopping profile...
,07-12 17:45:21.811   875   875 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:21.811   875   875 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:21.811  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:21.812  1349  1360 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:21.812   875   875 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:21.813  1349  1349 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:21.813  2555  2555 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:21.814  1740  1970 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:21.814  2555  2768 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:21.816  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:21.820  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:21.821  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:21.824  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:21.831   875  1304 E native  : do suspend true
,07-12 17:45:21.834   875   888 I ActivityManager: Start proc 3719:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-12 17:45:21.835   875   875 D BluetoothA2dp: Proxy object disconnected
,07-12 17:45:21.836  2555  2555 D HidService: Received stop request...Stopping profile...
07-12 17:45:21.836  2555  2555 D HidService: Stopping Bluetooth HidService
07-12 17:45:21.838  2555  2555 D HealthService: Received stop request...Stopping profile...
07-12 17:45:21.838  2555  2555 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:21.839  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.839  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.839  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:21.839  2555  2555 D PanService: Received stop request...Stopping profile...
,07-12 17:45:21.842  2555  2555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:21.842  2555  2555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-12 17:45:21.842  2555  2607 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-12 17:45:21.842  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.842  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:21.843  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.843  2555  2607 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-12 17:45:21.844   875  2088 D DhcpClient: Clearing IP address
07-12 17:45:21.844   373   873 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:21.845  1349  1349 D BluetoothA2dp: Proxy object disconnected
,07-12 17:45:21.845  1349  1349 D BluetoothInputDevice: Proxy object disconnected
,07-12 17:45:21.845  1349  1349 D HidProfile: Bluetooth service disconnected
,07-12 17:45:21.845  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-12 17:45:21.845  1349  1349 D PanProfile: Bluetooth service disconnected
07-12 17:45:21.846  2555  2555 D BluetoothMapService: Received stop request...Stopping profile...
07-12 17:45:21.846  2555  2555 D BluetoothMapService: stop()
07-12 17:45:21.847  2555  2555 D BluetoothMapAppObserver: deinitObservers()
07-12 17:45:21.847  2555  2555 D BluetoothMapAppObserver: removeReceiver()
,07-12 17:45:21.848  1349  1349 D BluetoothMap: Proxy object disconnected
,07-12 17:45:21.848  1349  1349 D MapProfile: Bluetooth service disconnected
,07-12 17:45:21.849  2555  2555 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:21.849  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.849  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.849  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.850  2555  2555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.850  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.850  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.850  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.850  2555  2555 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:21.850  2555  2555 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:21.850  2555  2607 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:21.851  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.851  2555  2607 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:21.851  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.851  2555  2555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.851  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.851  2555  2748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:21.851  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:21.851  2555  2748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:21.851  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.851  2555  2748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:21.851  2555  2748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:21.851  2555  2555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:21.851  2555  2607 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:21.851  2555  2555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:21.852  2555  2555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.852  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.852  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.852  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.853  2555  2555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-12 17:45:21.853  2555  2555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:21.853   373   873 D CommandListener: Setting iface cfg
07-12 17:45:21.853  2555  2555 D BluetoothMapService: MAP Service closeService in
,07-12 17:45:21.854  2555  2555 D BluetoothMapMasInstance0: MAP Service shutdown
07-12 17:45:21.854  2555  2555 D ObexServerSockets0: shutdown(block = true)
07-12 17:45:21.854  2555  2774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-12 17:45:21.854  2555  2555 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:21.854  2555  2775 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:21.855  2555  2555 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:21.855  2555  2762 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-12 17:45:21.855  2555  2555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.855  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.855  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.855  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.855  1488  2293 V NativeCrypto: Read error: ssl=0x9afede00: I/O error during system call, Connection timed out
07-12 17:45:21.855  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:21.855  2555  2602 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:21.855  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:21.856  1349  1857 D BluetoothMap: onBluetoothStateChange: up=false
,07-12 17:45:21.856  2555  2602 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:21.856   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.857  1740  1755 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.857  1349  1360 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:21.858  1488  2293 V NativeCrypto: SSL shutdown failed: ssl=0x9afede00: I/O error during system call, Broken pipe
07-12 17:45:21.858   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.858  1349  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:21.859  1349  1857 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.859  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:21.859  2555  2555 D BluetoothMapService: cleanup()
07-12 17:45:21.859  2555  2555 D BluetoothMapService: MAP Service closeService in
07-12 17:45:21.859  2555  2555 I BtOppRfcommListener: stopping Accept Thread
,07-12 17:45:21.859  2555  3294 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:21.860  2555  3294 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:21.862  1349  1366 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:21.863   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-12 17:45:21.863   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-12 17:45:21.864   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.864   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:21.865  2555  2602 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:21.865  2555  2602 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:21.865  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:21.865   396   396 E Parcel  : Reading a NULL string not supported here.
,07-12 17:45:21.867  2555  2602 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:21.867  2555  2602 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:21.868  2555  2604 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:21.869  2555  2748 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-12 17:45:21.869  2555  2748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.871  2555  2607 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.874  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:21.874   875  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
07-12 17:45:21.874  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.875   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:21.875   875  1304 E native  : do suspend true
,07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.876  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:21.877  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.877   875  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:21.881   875  2089 D DhcpClient: Receive thread stopped
,07-12 17:45:21.899  3719  3719 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-12 17:45:21.904   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:21.910  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:21.916  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:21.918   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d6ca0a:true
,07-12 17:45:21.923   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:21.923   373   873 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:21.925   875  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 17:45:21.925   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:21.931   875  1743 I ActivityManager: Start proc 3735:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 17:45:21.933   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-12 17:45:21.936   875   892 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.938  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:21.940  3243  3243 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a1ceef2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.941  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:21.950   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:21.954  1835  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.954  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:21.955  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.955   875  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.958  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:21.958  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:21.967  3719  3719 D LocalBluetoothProfileManager: Adding local MAP profile
,07-12 17:45:21.969  3719  3719 D BluetoothMap: Create BluetoothMap proxy object
,07-12 17:45:21.973  3719  3719 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 17:45:21.986  3719  3719 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:21.992  3735  3735 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-12 17:45:21.994   875  1707 I ActivityManager: Killing 2849:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-12 17:45:22.000   373   873 E Netd    : netlink response contains error (No such file or directory)
,07-12 17:45:22.001   875  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-12 17:45:22.069  2555  2607 I bt_hci  : shut_down
,07-12 17:45:22.070  2555  2625 D bt_hwcfg: hw_epilog_process
,07-12 17:45:22.071  2555  2625 I bt_vendor: low_power_mode_cb
,07-12 17:45:22.090  2555  2625 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-12 17:45:22.091  2555  2625 I bt_vendor: epilog_cb
07-12 17:45:22.091  2555  2625 I bt_hci  : epilog_finished_callback
,07-12 17:45:22.096  2555  2607 I bt_hci_h4: hal_close
,07-12 17:45:22.096  2555  2607 I bt_userial_vendor: device fd = 51 close
,07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.183  3735  3735 D StrictMode: 	,at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instr,umentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.183  3735  3735 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.183  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.184  3735  3735 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.184  3735  3735 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.184  3735  3735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.188  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:22.200  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:22.200  3719  3719 D DockEventReceiver: finishStartingService: stopping service
07-12 17:45:22.202   875  1389 I ActivityManager: Killing 3243:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-12 17:45:22.355  3735  3762 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 17:45:22.387  2555  2604 D bt_stack_manager: event_shut_down_stack finished.
,07-12 17:45:22.387  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-12 17:45:22.389   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@587a93f:true
,07-12 17:45:22.392  2555  2602 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17:45:22.392  2555  2555 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:22.392  2555  2555 D BtGatt.GattService: Received stop request...Stopping profile...
07-12 17:45:22.392  2555  2555 D BtGatt.GattService: stop()
07-12 17:45:22.393  2555  2555 D BtGatt.AdvertiseManager: advertise clients cleared
,07-12 17:45:22.400  2555  2555 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:22.400  2555  2555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:22.400  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.400  2555  2555 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:22.400  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-12 17:45:22.400  2555  2602 D BluetoothAdapterProperties: Setting state to 10
,07-12 17:45:22.400  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-12 17:45:22.401  2555  2602 I BluetoothAdapterState: Entering OffState
07-12 17:45:22.401   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-12 17:45:22.414  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-12 17:45:22.415  2555  2555 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-12 17:45:22.418  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:22.419  2555  2555 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-12 17:45:22.419  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-12 17:45:22.420  2555  2604 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-12 17:45:22.421  2555  2604 D bt_stack_manager: event_clean_up_stack finished.
07-12 17:45:22.419  2555  2555 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:22.420  1804  2358 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:22.423  1804  2358 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:22.425  1804  2358 I iu.SyncManager: NEXT; no task
07-12 17:45:22.427  2555  2555 I art     : System.exit called, status: 0
,07-12 17:45:22.427  2555  2555 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:22.434   875   886 I ActivityManager: Start proc 3774:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-12 17:45:22.461   875  1707 I ActivityManager: Process com.android.bluetooth (pid 2555) has died
,07-12 17:45:22.481  3774  3774 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-12 17:45:22.484  3774  3774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:22.493  3774  3774 D SprintDMHelper: simOperator: 
07-12 17:45:22.493  3774  3774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-12 17:45:22.521   875  1694 I ActivityManager: Start proc 3786:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-12 17:45:22.612  2382  3800 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-12 17:45:22.623   875   886 I ActivityManager: Start proc 3801:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 17:45:22.627   875  1389 I ActivityManager: Killing 3307:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-12 17:45:22.707  3801  3801 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-12 17:45:22.755  3801  3801 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 17:45:22.755  3801  3801 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:22.755  3801  3801 I GAv4    :   adb logcat -s GAv4
,07-12 17:45:22.767  3801  3801 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:22.772  3801  3801 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:22.800  3801  3818 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:22.901  3801  3801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-12 17:45:22.931  3801  3801 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 17:45:22.948  3801  3801 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 4937-4949)
,07-12 17:45:22.949  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:45:22.958  3801  3801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e2001c}
,07-12 17:45:22.958  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:22.959  3801  3801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 17:45:22.965  3801  3801 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:45:22.967  3801  3801 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:45:22.989  3801  3801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 17:45:23.002  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:45:23.002  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:23.002  3801  3801 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 17:45:23.002  3801  3801 I Adreno  : Build Date                       : 10/20/15
07-12 17:45:23.002  3801  3801 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 17:45:23.002  3801  3801 I Adreno  : Local Branch                     : M14
07-12 17:45:23.002  3801  3801 I Adreno  : Remote Branch                    : 
07-12 17:45:23.002  3801  3801 I Adreno  : Remote Branch                    : 
07-12 17:45:23.002  3801  3801 I Adreno  : Reconstruct Branch               : 
,07-12 17:45:23.059  3801  3847 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 17:45:23.059  3801  3801 I NSApplication: Starting up...
,07-12 17:45:23.112   875  1379 I ActivityManager: Start proc 3852:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 17:45:23.116   875  1379 I ActivityManager: Killing 3447:com.google.android.apps.books/u0a34 (adj 15): empty #17
,07-12 17:45:23.204  3852  3852 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 17:45:23.424   875   886 I ActivityManager: Killing 1695:android.process.acore/u0a5 (adj 15): empty #17
,07-12 17:45:23.477   875  1694 I ActivityManager: Start proc 3866:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-12 17:45:23.573  3866  3866 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-12 17:45:23.625  3866  3866 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 17:45:23.636   875   885 I ActivityManager: Killing 3520:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-12 17:45:26.796   875  1690 D WifiService: setWifiEnabled: true pid=3660, uid=10000
,07-12 17:45:26.797   875  1690 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:26.808   875  1304 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:26.815  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:26.815  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:26.818  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:26.818  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:26.829   875  1304 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:26.829   875  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:26.830   875  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-12 17:45:26.831   875  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:26.832   875  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:26.832   875  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 17:45:26.832   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 17:45:26.832   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:26.851   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:45:26.852   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-12 17:45:26.853   373   873 D CommandListener: Setting iface cfg
,07-12 17:45:26.865   875  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-12 17:45:26.865   875  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 17:45:26.865   875  1304 E native  : do suspend true
,07-12 17:45:26.877   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:26.877   875  1303 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:26.878   875  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-12 17:45:27.513   875  1743 I ActivityManager: Killing 3537:com.android.musicfx/u0a18 (adj 15): empty #17
,07-12 17:45:28.246   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:45:28.306   875  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=67.19 delta 1000 -> 994
,07-12 17:45:28.308   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-12 17:45:28.308   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:28.318   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-12 17:45:28.364   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 17:45:28.365  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 17:45:28.791  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 17:45:28.836  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 17:45:28.837  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-12 17:45:28.839   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:28.851   875  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:28.851   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:28.851   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 17:45:28.866   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:28.877   373   873 D CommandListener: Setting iface cfg
,07-12 17:45:28.878   875  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,07-12 17:45:28.893   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-12 17:45:28.906   875  3903 D DhcpClient: Receive thread started
,07-12 17:45:28.995   875  1304 E native  : do suspend false
,07-12 17:45:29.017   875  2088 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 17:45:29.031   875  3903 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,07-12 17:45:29.034   875  2088 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,07-12 17:45:29.040   875  2088 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-12 17:45:29.054   875  3903 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 17:45:29.056   875  2088 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-12 17:45:29.061   373   873 D CommandListener: Setting iface cfg
,07-12 17:45:29.071   875  2088 D DhcpClient: Scheduling renewal in 86399s
,07-12 17:45:29.079   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-12 17:45:29.080   875  1304 E native  : do suspend true
,07-12 17:45:29.101   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 17:45:29.102   875  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 17:45:29.102   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 17:45:29.104   875  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 17:45:29.106   875  1306 D ConnectivityService: Adding iface wlan0 to network 101
,07-12 17:45:29.143   875  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 17:45:29.143   875  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-12 17:45:29.145   875  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-12 17:45:29.146   875  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-12 17:45:29.147   875  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-12 17:45:29.154   875  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-12 17:45:29.160   875  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-12 17:45:29.160   875  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-12 17:45:29.161   875  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 17:45:29.161   875  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-12 17:45:29.161   875  1306 D ConnectivityService:    accepting network in place of null
,07-12 17:45:29.162   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 17:45:29.162   875  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:29.179   875  3902 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181179, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:29.204   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:29.240   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:29.244   875  3901 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:809::200e
,07-12 17:45:29.247   875  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-12 17:45:29.247   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:29.249   875  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-12 17:45:29.254   875   892 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:29.264  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:29.264  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:29.266  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:29.267  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:29.327   875   887 I ActivityManager: Start proc 3913:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-12 17:45:29.333   875  3901 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 15:45:29 GMT], X-Android-Received-Millis=[1468338329331], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468338329302]}
,07-12 17:45:29.339   875  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:29.339   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-12 17:45:29.339   875  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-12 17:45:29.340   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 17:45:29.360  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-12 17:45:29.365  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-12 17:45:29.367  1804  2358 I iu.UploadsManager: num queued entries: 0
07-12 17:45:29.368  1804  2358 I iu.UploadsManager: num updated entries: 0
07-12 17:45:29.368  1804  2358 I iu.SyncManager: NEXT; no task
07-12 17:45:29.376  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:29.384  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-12 17:45:29.387  3774  3774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-12 17:45:29.398  3774  3774 D SprintDMHelper: simOperator: 
07-12 17:45:29.398  3774  3774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-12 17:45:29.404  1804  3929 I MDM     : [205] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-12 17:45:29.405  1804  3929 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:45:29.412  1804  3929 V GoogleAuthProtoRequest: [205] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:45:29.438  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:29.439  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:29.457  3913  3913 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 17:45:29.466  3913  3913 I BooksApp: Created application version: 3.6.9 (30609)
,07-12 17:45:29.488  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-12 17:45:29.488  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-12 17:45:29.488  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:29.488  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:29.524  1804  3929 E MDM     : [205] SitrepService.a: Error sending sitrep.
,07-12 17:45:29.530  3913  3941 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:45:29.703  3913  3948 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:45:29.750  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 17:45:29.750  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:45:29.750  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:29.751  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:29.814  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 17:45:29.814  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:45:29.814  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:29.814  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:29.836  3913  3948 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:45:29.838  3913  3941 E BooksSync: Soft error
07-12 17:45:29.838  3913  3941 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:45:29.838  3913  3941 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:45:29.838  3913  3941 E BooksSync: Sync error
07-12 17:45:29.838  3913  3941 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:45:29.838  3913  3941 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:45:29.839  3913  3941 I BooksSync: Finished books sync
07-12 17:45:29.848   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160958, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:45:29.936  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:29.963  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 17:45:29.963  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 17:45:29.963  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:29.963  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:29.999  3378  3378 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 17:45:29.999  3378  3378 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 17:45:30.000  3378  3378 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-12 17:45:30.248   875  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-12 17:45:31.050  2382  3934 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-12 17:45:31.059   875   886 I ActivityManager: Killing 3328:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-12 17:45:31.802   875  1707 D WifiService: setWifiEnabled: false pid=3660, uid=10000
,07-12 17:45:31.803   875  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:31.836  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-12 17:45:31.840   875  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-12 17:45:31.841   875  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-12 17:45:31.841   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 17:45:31.841   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:31.858   875  1304 E native  : do suspend true
,07-12 17:45:31.869   875  2088 D DhcpClient: Clearing IP address
,07-12 17:45:31.869   373   873 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:31.872   373   873 D CommandListener: Setting iface cfg
,07-12 17:45:31.874   875  3903 D DhcpClient: Receive thread stopped
,07-12 17:45:31.878  1488  3942 V NativeCrypto: Read error: ssl=0x9afede00: I/O error during system call, Connection timed out
,07-12 17:45:31.881  1488  3942 V NativeCrypto: SSL shutdown failed: ssl=0x9afede00: I/O error during system call, Broken pipe
,07-12 17:45:31.885   875   886 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
07-12 17:45:31.885   875  3901 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,07-12 17:45:31.887   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-12 17:45:31.888   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,07-12 17:45:31.890   875  3901 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,07-12 17:45:31.892   396   396 E Parcel  : Reading a NULL string not supported here.
,07-12 17:45:31.892   875  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
07-12 17:45:31.897   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:31.897   875  1304 E native  : do suspend true
07-12 17:45:31.905   875  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-12 17:45:31.955   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:31.987   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:31.987   373   873 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:31.988   875  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-12 17:45:31.988   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:31.993   875   892 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:32.012  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:32.012  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:32.013  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:32.014  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:32.034  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-12 17:45:32.041  1804  2358 I iu.UploadsManager: num queued entries: 0
07-12 17:45:32.041  1804  2358 I iu.UploadsManager: num updated entries: 0
07-12 17:45:32.044  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-12 17:45:32.045  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-12 17:45:32.049  3774  3774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:32.054  3774  3774 D SprintDMHelper: simOperator: 
,07-12 17:45:32.055  3774  3774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-12 17:45:32.067   373   873 E Netd    : netlink response contains error (No such file or directory)
,07-12 17:45:32.068   875  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-12 17:45:32.068   875  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:32.069   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:45:32.083   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:32.085  1835  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:32.086  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:32.086  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:32.087  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:32.087  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:32.088   875  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-12 17:45:32.094  1804  2358 I iu.SyncManager: NEXT; no task
,07-12 17:45:32.096  2382  3961 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-12 17:45:34.478  3913  3939 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 17:45:36.858   875   892 I ActivityManager: Start proc 3969:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:37.000  3969  3969 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:37.001  3969  3969 D AdapterServiceConfig: Adding A2dpService
07-12 17:45:37.001  3969  3969 D AdapterServiceConfig: Adding HidService
07-12 17:45:37.001  3969  3969 D AdapterServiceConfig: Adding HealthService
07-12 17:45:37.001  3969  3969 D AdapterServiceConfig: Adding PanService
07-12 17:45:37.001  3969  3969 D AdapterServiceConfig: Adding GattService
07-12 17:45:37.002  3969  3969 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 17:45:37.015  3969  3969 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:37.015   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@be283b6:true
,07-12 17:45:37.019  3969  3969 I bt_bluedroid: init
,07-12 17:45:37.019  3969  3983 I BluetoothAdapterState: Entering OffState
,07-12 17:45:37.021  3969  3984 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 17:45:37.021  3969  3984 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:37.021  3969  3984 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:37.021  3969  3984 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:37.022  3969  3969 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:37.023  3969  3969 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:37.025  3969  3980 I bt_bluedroid: config_hci_snoop_log
,07-12 17:45:37.026   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-12 17:45:37.026  3969  3987 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-12 17:45:37.029  3969  3987 D BluetoothAdapterProperties: Name is: Nexus 6
,07-12 17:45:37.030  3969  3983 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 17:45:37.031  3969  3983 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:37.031  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 17:45:37.035  3969  3983 D BluetoothBondStateMachine: make
,07-12 17:45:37.038  3969  3988 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:37.045  3969  3983 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:37.045  3969  3969 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 17:45:37.049  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:37.050  3969  3969 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:37.050  3969  3969 D BtGatt.GattService: Received start request. Starting profile...
,07-12 17:45:37.050  3969  3969 D BtGatt.GattService: start()
07-12 17:45:37.051  3969  3969 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:37.051  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
07-12 17:45:37.052  3969  3969 D BtGatt.AdvertiseManager: advertise manager created
,07-12 17:45:37.060  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:37.061  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.061  3969  3969 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:37.061  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.061  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:37.062  3969  3983 I bt_bluedroid: enable
07-12 17:45:37.062  3969  3984 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 17:45:37.062  3969  3984 I bt_hci  : start_up
,07-12 17:45:37.068  3969  3984 I bt_vendor: alloc value 0xb3a02189
07-12 17:45:37.068  3969  3984 I bt_vendor: init
07-12 17:45:37.068  3969  3984 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:37.068  3969  3984 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:37.167   875  1306 D ConnectivityService: handlePromptUnvalidated 101
,07-12 17:45:37.175  3969  3984 D bt_hci  : start_up starting async portion
,07-12 17:45:37.175  3969  3991 I bt_hci  : event_finish_startup
07-12 17:45:37.176  3969  3991 I bt_hci_h4: hal_open
07-12 17:45:37.176  3969  3991 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-12 17:45:37.187  3969  3991 I bt_userial_vendor: device fd = 51 open
,07-12 17:45:37.217  3969  3991 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:37.249  3969  3991 D bt_hwcfg: Chipset BCM4354A2
,07-12 17:45:37.249  3969  3991 D bt_hwcfg: Target name = [BCM4354A2]
,07-12 17:45:37.250  3969  3991 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-12 17:45:37.912  3969  3991 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 17:45:37.913  3969  3991 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:37.913  3969  3991 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:38.030  3969  3991 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:38.031  3969  3991 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-12 17:45:38.061  3969  3991 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:38.061  3969  3991 I bt_vendor: firmware callback
,07-12 17:45:38.061  3969  3991 I bt_hci  : firmware_config_callback
,07-12 17:45:38.074  3969  3993 I bt_btu  : btu_task pending for preload complete event
07-12 17:45:38.074  3969  3993 I bt_btu_task: Bluetooth chip preload is complete
07-12 17:45:38.074  3969  3993 I bt_btu  : btu_task received preload complete event
,07-12 17:45:38.085  3969  3993 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 17:45:38.086  3969  3993 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 17:45:38.086  3969  3993 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 17:45:38.086  3969  3993 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:38.087  3969  3993 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-12 17:45:38.087  3969  3993 I         : BTE_InitTraceLevels -- TRC_A2D,
07-12 17:45:38.087  3969  3993 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 17:45:38.087  3969  3993 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 17:45:38.088  3969  3993 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:38.088  3969  3993 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 17:45:38.088  3969  3993 I         : BTE_InitTraceLevels -- TRC_SDP
,07-12 17:45:38.088  3969  3993 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 17:45:38.089  3969  3993 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:38.090  3969  3993 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:38.090  3969  3993 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:38.224  3969  3993 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397fd9d,
07-12 17:45:38.225  3969  3993 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397fd9d 
,07-12 17:45:38.237  3969  3987 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,07-12 17:45:38.239  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:38.240  3969  3987 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-12 17:45:38.245  3969  3987 D BluetoothAdapterProperties: Name is: Nexus 6
07-12 17:45:38.249  3969  3987 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:38.249  3969  3987 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:38.249  3969  3987 D bt_hci  : do_postload posting postload work item
,07-12 17:45:38.250  3969  3991 I bt_hci  : event_postload
,07-12 17:45:38.250  3969  3991 I bt_vendor: sco_config_cb
,07-12 17:45:38.250  3969  3991 I bt_hci  : sco_config_callback postload finished.
,07-12 17:45:38.252  3969  3987 D bt_bte_conf: Device ID record 1 : primary
,07-12 17:45:38.252  3969  3987 D bt_bte_conf:   vendorId            = 000f
,07-12 17:45:38.253  3969  3987 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 17:45:38.253  3969  3987 D bt_bte_conf:   product             = 1200
,07-12 17:45:38.253  3969  3987 D bt_bte_conf:   version             = 1436
,07-12 17:45:38.254  3969  3987 D bt_bte_conf:   clientExecutableURL = 
07-12 17:45:38.254  3969  3987 D bt_bte_conf:   serviceDescription  = 
07-12 17:45:38.254  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:38.254  3969  3987 D bt_bte_conf:   documentationURL    = 
07-12 17:45:38.255  3969  3987 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-12 17:45:38.255  3969  3984 D bt_stack_manager: event_start_up_stack finished
,07-12 17:45:38.257  3969  3991 I bt_vendor: low_power_mode_cb
07-12 17:45:38.257  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:38.257  3969  3983 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:38.258  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:38.258  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:38.259  3969  3983 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:38.264  3969  3983 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:38.265  3969  3983 D BluetoothAdapterProperties: Setting state to 11
07-12 17:45:38.265  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-12 17:45:38.276  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:38.278  3969  3969 D HeadsetService: Received start request. Starting profile...
,07-12 17:45:38.281  3969  3969 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 17:45:38.281  3969  3969 D HeadsetStateMachine: make
,07-12 17:45:38.286  3969  3983 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:38.292  3969  3969 D HeadsetStateMachine: max_hf_connections = 1
,07-12 17:45:38.292  3969  3969 I bt_bluedroid: get_profile_interface handsfree
07-12 17:45:38.293  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 17:45:38.293  3969  3987 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-12 17:45:38.296  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:38.296  3969  3969 D A2dpService: Received start request. Starting profile...
07-12 17:45:38.297  3969  3969 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-12 17:45:38.297  3969  3969 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:38.306  3969  3969 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:38.306  3969  3969 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:38.306  3969  3969 D A2dpStateMachine: make
,07-12 17:45:38.307  3969  3969 I bt_bluedroid: get_profile_interface a2dp
,07-12 17:45:38.308  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-12 17:45:38.310  3969  4002 D A2dpStateMachine: Enter Disconnected: -2
,07-12 17:45:38.311  3969  3969 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 17:45:38.312  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:38.313  3969  3969 D HidService: Received start request. Starting profile...
,07-12 17:45:38.313  3719  3719 D BluetoothInputDevice: Proxy object connected
07-12 17:45:38.313  3969  3969 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:38.313  3969  3987 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39613e5
07-12 17:45:38.313  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 17:45:38.314  3969  3969 D HidService: setHidService(): set to: null
,07-12 17:45:38.314  3719  3719 D HidProfile: Bluetooth service connected
07-12 17:45:38.314  3969  3969 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 17:45:38.315  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
07-12 17:45:38.316  3969  3969 D HealthService: Received start request. Starting profile...
,07-12 17:45:38.317  3969  3969 I bt_bluedroid: get_profile_interface health
,07-12 17:45:38.318  3969  3969 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 17:45:38.318  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:38.320  3719  3719 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 17:45:38.320  3719  3719 D PanProfile: Bluetooth service connected
,07-12 17:45:38.322  3969  3969 D PanService: Received start request. Starting profile...
,07-12 17:45:38.322  3969  3969 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:38.322  3969  3969 I bt_bluedroid: get_profile_interface pan
07-12 17:45:38.323  3969  3987 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 17:45:38.325  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:38.326  3969  3969 D BluetoothMapService: Received start request. Starting profile...
,07-12 17:45:38.326  3719  3719 D BluetoothMap: Proxy object connected
07-12 17:45:38.326  3969  3969 D BluetoothMapService: start()
07-12 17:45:38.327  3719  3719 D MapProfile: Bluetooth service connected
,07-12 17:45:38.327  3719  3719 D BluetoothMap: getConnectedDevices()
07-12 17:45:38.328  3719  3719 D BluetoothMap: Bluetooth is Not enabled
07-12 17:45:38.329  3969  3969 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-12 17:45:38.329  3969  3969 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-12 17:45:38.330  3969  3969 D BluetoothMapAppObserver: createReceiver()
,07-12 17:45:38.331  3969  3969 D BluetoothMapAppObserver: initObservers()
07-12 17:45:38.331  3969  3969 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 17:45:38.340  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:38.341  3969  3969 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:38.341  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.341  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:38.341  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:38.343  3969  3969 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.343  3969  4000 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:38.344  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:38.345  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:38.345  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 17:45:38.345  3969  3983 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:38.345  3969  3983 D BluetoothAdapterProperties: State =  11
,07-12 17:45:38.349  3969  3987 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:38.349  3969  3987 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:38.350  3969  3983 D BluetoothAdapterProperties: Setting state to 12
,07-12 17:45:38.350  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 17:45:38.358  3719  3729 D BluetoothPan: onBluetoothStateChange on: true
,07-12 17:45:38.358  3969  3983 I BluetoothAdapterState: Entering OnState
,07-12 17:45:38.358  3969  3969 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:38.358  1349  1857 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:38.359  3969  3969 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 17:45:38.360   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:38.360  1349  1349 D BluetoothMap: Proxy object connected
,07-12 17:45:38.360  3719  3730 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:38.360  1349  1349 D MapProfile: Bluetooth service connected
07-12 17:45:38.360  1349  1349 D BluetoothMap: getConnectedDevices(),
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:38.361  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:38.362  3719  3729 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:38.362  1740  1752 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:38.363  1349  1366 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:38.363  3969  3969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:38.364   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:38.365  3719  3730 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:38.365  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:38.365  1349  1857 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 17:45:38.366  3969  3969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:38.367  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:38.369  1349  1366 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-12 17:45:38.370  3969  3969 D ObexServerSockets: Succeed to create listening sockets 
,07-12 17:45:38.370  3969  3969 D ObexServerSockets0: startAccept()
,07-12 17:45:38.370  3969  3969 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:38.371  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:38.372  3969  3969 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 17:45:38.372  3969  3969 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-12 17:45:38.373  1349  1349 D BluetoothInputDevice: Proxy object connected
,07-12 17:45:38.373  1349  1349 D HidProfile: Bluetooth service connected
07-12 17:45:38.373  1349  1360 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:38.373  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:38.374  3969  4009 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:38.375  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:38.375  1349  1349 D PanProfile: Bluetooth service connected
07-12 17:45:38.375  3969  4008 D ObexServerSockets0: Accepting socket connection...
,07-12 17:45:38.375   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:38.375  1349  1349 D BluetoothA2dp: Proxy object connected
07-12 17:45:38.375   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:38.376   875   875 D BluetoothA2dp: Proxy object connected
07-12 17:45:38.378  3969  3969 D BluetoothMapService: onReceive
07-12 17:45:38.378  3969  3969 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:38.378  3969  3969 D BluetoothMapService: STATE_ON
07-12 17:45:38.380  3719  3719 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 17:45:38.380   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 17:45:38.385  3719  3719 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 17:45:38.390  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:38.392  3719  3719 D BluetoothA2dp: Proxy object connected
,07-12 17:45:38.396  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:38.399  3719  3719 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:38.404  1349  1349 D BluetoothPbap: Proxy object connected
,07-12 17:45:38.404  1349  1349 D PbapServerProfile: Bluetooth service connected
07-12 17:45:38.404  3719  3719 D BluetoothPbap: Proxy object connected
,07-12 17:45:38.404  3719  3719 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:38.408  3969  3969 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:38.409  3969  3969 D ObexServerSockets0: prepareForNewConnect()
,07-12 17:45:38.413  3969  4014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:38.427  3969  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:38.428  3969  4018 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:38.462   875   875 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.462   875   875 D BluetoothHeadset: Proxy object connected
07-12 17:45:38.462  1349  1366 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.462   875   875 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.462  1349  1349 D HeadsetProfile: Bluetooth service connected
07-12 17:45:38.463  1740  1970 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.464  1740  1755 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.465   875   892 D BluetoothHeadset: Proxy object connected
07-12 17:45:38.470  1349  1360 D BluetoothHeadset: Proxy object connected
07-12 17:45:38.470  1349  1349 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:38.475   875   892 D BluetoothHeadset: Proxy object connected
,07-12 17:45:38.488  3719  3730 D BluetoothHeadset: Proxy object connected
07-12 17:45:38.488  3719  3719 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:39.549  3378  3391 D Finsky  : [273] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-12 17:45:39.571  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:39.581  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:39.583  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:39.612  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 17:45:39.612  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-12 17:45:39.613  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:39.613  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:39.636  3378  3391 D Finsky  : [273] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-12 17:45:41.820  3969  3983 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:41.821  3969  3983 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:41.821  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-12 17:45:41.823  3969  3983 D BluetoothAdapterProperties: onBluetoothDisable()
,07-12 17:45:41.831  3969  3983 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:41.832  3969  3969 D BluetoothMapService: onReceive
,07-12 17:45:41.833  3969  3969 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-12 17:45:41.834  3969  3969 D BluetoothMapService: STATE_TURNING_OFF
07-12 17:45:41.834  3969  3969 D BluetoothMapService: MAP Service closeService in
,07-12 17:45:41.834  3969  3969 D BluetoothMapMasInstance0: MAP Service shutdown
07-12 17:45:41.834  3969  3969 D ObexServerSockets0: shutdown(block = true)
,07-12 17:45:41.835  3969  3969 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:41.835  3969  3969 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-12 17:45:41.835  3969  3996 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,07-12 17:45:41.836  3969  4009 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:41.836  3969  4008 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,07-12 17:45:41.843  3969  3987 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:41.843  3969  3969 I BtOppRfcommListener: stopping Accept Thread
,07-12 17:45:41.843  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:41.844  3969  4018 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-12 17:45:41.846  3969  4018 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:41.850  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:41.852  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:41.853  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:41.855  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:41.856  3969  3969 D HeadsetService: Received stop request...Stopping profile...
07-12 17:45:41.857  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:41.859   875   875 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:41.859   875   875 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:41.860  1349  1857 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:41.860  3969  3969 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:41.860   875   875 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:41.860  3719  3729 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:41.860  3969  4002 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:41.861  1740  1882 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:41.861   875   875 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:41.863  3969  3969 D HidService: Received stop request...Stopping profile...
,07-12 17:45:41.863  3969  3969 D HidService: Stopping Bluetooth HidService
07-12 17:45:41.864  3719  3719 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:41.865  3969  3969 D HealthService: Received stop request...Stopping profile...
07-12 17:45:41.865  3719  3719 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:41.865  3719  3719 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:41.868  3719  3719 D BluetoothInputDevice: Proxy object disconnected
,07-12 17:45:41.868  3719  3719 D HidProfile: Bluetooth service disconnected
07-12 17:45:41.868  3969  3969 D PanService: Received stop request...Stopping profile...
,07-12 17:45:41.869  3719  3719 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:41.869  3719  3719 D PanProfile: Bluetooth service disconnected
07-12 17:45:41.870  3969  3969 D BluetoothMapService: Received stop request...Stopping profile...
07-12 17:45:41.870  3969  3969 D BluetoothMapService: stop()
07-12 17:45:41.870  3969  3969 D BluetoothMapAppObserver: deinitObservers()
,07-12 17:45:41.870  3969  3969 D BluetoothMapAppObserver: removeReceiver()
,07-12 17:45:41.871  3719  3719 D BluetoothMap: Proxy object disconnected
07-12 17:45:41.871  3719  3719 D MapProfile: Bluetooth service disconnected
07-12 17:45:41.872  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.872  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:41.872  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:41.872  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:41.875  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:41.876  3969  3969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:41.876  3969  3969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:41.876  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.876  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:41.876  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:41.876  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:41.876  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:41.877  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-12 17:45:41.877  3969  3987 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-12 17:45:41.876  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:41.878  1349  1349 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:41.878  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:41.878  1349  1349 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:41.878  1349  1349 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:41.878  1349  1349 D HidProfile: Bluetooth service disconnected
07-12 17:45:41.879  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:41.879  1349  1349 D PanProfile: Bluetooth service disconnected
07-12 17:45:41.879  1349  1349 D BluetoothMap: Proxy object disconnected
07-12 17:45:41.879  1349  1349 D MapProfile: Bluetooth service disconnected
07-12 17:45:41.880  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:41.880  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.880  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:41.880  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:41.880  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:41.880  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:41.880  3969  3993 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:41.880  3969  3993 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:41.880  3969  3993 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-12 17:45:41.880  3969  3993 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:41.880  3969  3969 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:41.880  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-12 17:45:41.880  3969  3969 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:41.881  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.881  3969  3987 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:41.881  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:41.881  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:41.881  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:41.881  3969  3969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-12 17:45:41.881  3969  3987 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:41.882  3969  3969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
07-12 17:45:41.882  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.882  3969  3969 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:41.882  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:41.882  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:41.883  3969  3969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-12 17:45:41.883  3969  3969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:41.884  3969  3969 D BluetoothMapService: MAP Service closeService in
07-12 17:45:41.884  3969  3969 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:41.884  3969  3969 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:41.884  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:41.884  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:41.884  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:41.885  3969  3969 D BluetoothMapService: cleanup()
,07-12 17:45:41.885  3969  3983 D BluetoothAdapterProperties: Setting state to 15
,07-12 17:45:41.885  3969  3969 D BluetoothMapService: MAP Service closeService in
07-12 17:45:41.885  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:41.885  3969  3983 I BluetoothAdapterState: Entering BleOnState
,07-12 17:45:41.886  3719  3730 D BluetoothPan: onBluetoothStateChange on: false
,07-12 17:45:41.887  1349  1349 D BluetoothPbap: Proxy object disconnected
07-12 17:45:41.887  3719  3719 D BluetoothPbap: Proxy object disconnected
07-12 17:45:41.887  1349  1349 D PbapServerProfile: Bluetooth service disconnected
,07-12 17:45:41.887  3719  3719 D PbapServerProfile: Bluetooth service disconnected
,07-12 17:45:41.888  1349  1360 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:41.891   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:41.891  3719  3729 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:41.891  3719  3730 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:41.892  3719  4025 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:41.893  1740  1752 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:41.893  1349  1857 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:41.894   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:41.894  3719  3729 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-12 17:45:41.895  1349  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-12 17:45:41.895  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:41.896  3719  3730 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:41.898  1349  1857 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:41.899  1349  1366 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:41.899   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:41.899   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-12 17:45:41.900  3969  3983 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:41.900  3969  3983 D BluetoothAdapterProperties: Setting state to 16
,07-12 17:45:41.900  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:41.901  3969  3983 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:41.901  3969  3983 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:41.902  3969  3984 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:41.903  3969  3987 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:41.904  3969  3993 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-12 17:45:41.904  3969  3993 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:41.905  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:41.905  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:41.906  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:41.910  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:41.924  3719  3719 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:42.105  3969  3987 I bt_hci  : shut_down
,07-12 17:45:42.106  3969  3991 D bt_hwcfg: hw_epilog_process
,07-12 17:45:42.118  3969  3991 I bt_vendor: low_power_mode_cb
,07-12 17:45:42.142  3969  3991 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-12 17:45:42.142  3969  3991 I bt_vendor: epilog_cb
07-12 17:45:42.142  3969  3991 I bt_hci  : epilog_finished_callback
,07-12 17:45:42.150  3969  3987 I bt_hci_h4: hal_close
,07-12 17:45:42.152  3969  3987 I bt_userial_vendor: device fd = 51 close
,07-12 17:45:42.285  3969  3984 D bt_stack_manager: event_shut_down_stack finished.
,07-12 17:45:42.286  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-12 17:45:42.292  3969  3983 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-12 17:45:42.292  3969  3969 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:42.294  3969  3969 D BtGatt.GattService: Received stop request...Stopping profile...
,07-12 17:45:42.295  3969  3969 D BtGatt.GattService: stop()
,07-12 17:45:42.295  3969  3969 D BtGatt.AdvertiseManager: advertise clients cleared
,07-12 17:45:42.301  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:42.301  3969  3969 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:42.301  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:42.301  3969  3969 V BluetoothAdapterState: isBleTurningOff()=true
,07-12 17:45:42.302  3969  3983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-12 17:45:42.303  3969  3983 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:42.303  3969  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-12 17:45:42.305  3969  3983 I BluetoothAdapterState: Entering OffState
,07-12 17:45:42.307   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.,
,07-12 17:45:42.330  3969  3969 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-12 17:45:42.330  3969  3969 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:42.330  3969  3969 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:42.332  3969  3984 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:42.341  3969  3984 D bt_stack_manager: event_clean_up_stack finished.
,07-12 17:45:42.349  3969  3969 I art     : System.exit called, status: 0
,07-12 17:45:42.349  3969  3969 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:42.417   875  1389 I ActivityManager: Process com.android.bluetooth (pid 3969) has died
,07-12 17:45:46.818  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:46.818  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.825  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:46.826  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8b0e55 added. We now have 6 listener(s)
,07-12 17:45:46.826  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.830  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:46.830  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a51306a added. We now have 7 listener(s)
07-12 17:45:46.831  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.832  3660  3714 I System.out: IsBluetoothEnabled
,07-12 17:45:46.841  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:46.886   875   892 I ActivityManager: Start proc 4030:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:46.991  4030  4030 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:46.992  4030  4030 D AdapterServiceConfig: Adding A2dpService,
,07-12 17:45:46.992  4030  4030 D AdapterServiceConfig: Adding HidService
,07-12 17:45:46.992  4030  4030 D AdapterServiceConfig: Adding HealthService
,07-12 17:45:46.992  4030  4030 D AdapterServiceConfig: Adding PanService
,07-12 17:45:46.993  4030  4030 D AdapterServiceConfig: Adding GattService
,07-12 17:45:46.993  4030  4030 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 17:45:47.008  4030  4030 D BluetoothAdapterState: make() - Creating AdapterState
07-12 17:45:47.008   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c06c926:true
,07-12 17:45:47.014  4030  4030 I bt_bluedroid: init
,07-12 17:45:47.014  4030  4042 I BluetoothAdapterState: Entering OffState
,07-12 17:45:47.021  4030  4043 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 17:45:47.021  4030  4043 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:47.021  4030  4043 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:47.022  4030  4043 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:47.023  4030  4030 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:47.026  4030  4030 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:47.031  4030  4041 I bt_bluedroid: config_hci_snoop_log
,07-12 17:45:47.031  4030  4046 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-12 17:45:47.034  4030  4046 D BluetoothAdapterProperties: Name is: Nexus 6
,07-12 17:45:47.037   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-12 17:45:47.044  4030  4042 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 17:45:47.045  4030  4042 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:47.045  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 17:45:47.050  4030  4042 D BluetoothBondStateMachine: make
,07-12 17:45:47.054  4030  4047 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:47.061  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:47.062  4030  4030 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 17:45:47.067  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:47.068  4030  4030 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:47.069  4030  4030 D BtGatt.GattService: Received start request. Starting profile...
07-12 17:45:47.069  4030  4030 D BtGatt.GattService: start()
,07-12 17:45:47.069  4030  4030 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:47.071  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
07-12 17:45:47.071  4030  4030 D BtGatt.AdvertiseManager: advertise manager created
,07-12 17:45:47.081  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:47.081  4030  4030 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:47.081  4030  4030 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:47.081  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:47.082  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:47.082  4030  4042 I bt_bluedroid: enable
07-12 17:45:47.082  4030  4043 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-12 17:45:47.083  4030  4043 I bt_hci  : start_up
,07-12 17:45:47.102  4030  4043 I bt_vendor: alloc value 0xb3a02189
,07-12 17:45:47.103  4030  4043 I bt_vendor: init
07-12 17:45:47.103  4030  4043 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:47.103  4030  4043 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:47.211  4030  4043 D bt_hci  : start_up starting async portion
,07-12 17:45:47.212  4030  4050 I bt_hci  : event_finish_startup
07-12 17:45:47.212  4030  4050 I bt_hci_h4: hal_open
,07-12 17:45:47.212  4030  4050 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-12 17:45:47.224  4030  4050 I bt_userial_vendor: device fd = 51 open
,07-12 17:45:47.254  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:47.285  4030  4050 D bt_hwcfg: Chipset BCM4354A2
,07-12 17:45:47.286  4030  4050 D bt_hwcfg: Target name = [BCM4354A2]
07-12 17:45:47.286  4030  4050 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-12 17:45:47.946  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 17:45:47.947  4030  4050 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:47.948  4030  4050 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:48.064  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:48.066  4030  4050 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-12 17:45:48.095  4030  4050 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:48.095  4030  4050 I bt_vendor: firmware callback
07-12 17:45:48.095  4030  4050 I bt_hci  : firmware_config_callback
,07-12 17:45:48.107  4030  4052 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:48.107  4030  4052 I bt_btu_task: Bluetooth chip preload is complete
07-12 17:45:48.108  4030  4052 I bt_btu  : btu_task received preload complete event
,07-12 17:45:48.120  4030  4052 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:48.120  4030  4052 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 17:45:48.121  4030  4052 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 17:45:48.121  4030  4052 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:48.121  4030  4052 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 17:45:48.121  4030  4052 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 17:45:48.122  4030  4052 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 17:45:48.122  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 17:45:48.124  4030  4052 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:48.124  4030  4052 I         : BTE_InitTraceLevels -- TRC_PAN
,07-12 17:45:48.125  4030  4052 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 17:45:48.126  4030  4052 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 17:45:48.126  4030  4052 I         : BTE_InitTraceLevels -- TRC_SMP
,07-12 17:45:48.127  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:48.127  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:48.261  4030  4052 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397fd9d
,07-12 17:45:48.261  4030  4052 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397fd9d 
,07-12 17:45:48.273  4030  4046 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
07-12 17:45:48.274  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:48.275  4030  4046 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-12 17:45:48.278  4030  4046 D BluetoothAdapterProperties: Name is: Nexus 6
,07-12 17:45:48.282  4030  4046 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:48.282  4030  4046 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:48.285  4030  4046 D bt_hci  : do_postload posting postload work item
07-12 17:45:48.286  4030  4050 I bt_hci  : event_postload
07-12 17:45:48.286  4030  4050 I bt_vendor: sco_config_cb
,07-12 17:45:48.286  4030  4050 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:48.287  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:48.290  4030  4046 D bt_bte_conf: Device ID record 1 : primary
,07-12 17:45:48.290  4030  4046 D bt_bte_conf:   vendorId            = 000f
,07-12 17:45:48.290  4030  4046 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 17:45:48.290  4030  4046 D bt_bte_conf:   product             = 1200
,07-12 17:45:48.291  4030  4046 D bt_bte_conf:   version             = 1436
,07-12 17:45:48.291  4030  4046 D bt_bte_conf:   clientExecutableURL = 
,07-12 17:45:48.291  4030  4046 D bt_bte_conf:   serviceDescription  = 
,07-12 17:45:48.291  4030  4046 D bt_bte_conf:   documentationURL    = 
,07-12 17:45:48.292  4030  4046 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-12 17:45:48.292  4030  4043 D bt_stack_manager: event_start_up_stack finished
,07-12 17:45:48.294  4030  4050 I bt_vendor: low_power_mode_cb
,07-12 17:45:48.297  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-12 17:45:48.298  4030  4042 D BluetoothAdapterProperties: Setting state to 15
,07-12 17:45:48.299  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:48.300  4030  4042 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:48.303  4030  4042 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:48.304  4030  4042 D BluetoothAdapterProperties: Setting state to 11
07-12 17:45:48.304  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:48.309  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
07-12 17:45:48.310  4030  4030 D HeadsetService: Received start request. Starting profile...
07-12 17:45:48.316  4030  4030 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 17:45:48.316  4030  4030 D HeadsetStateMachine: make
,07-12 17:45:48.330  4030  4030 D HeadsetStateMachine: max_hf_connections = 1
,07-12 17:45:48.330  4030  4030 I bt_bluedroid: get_profile_interface handsfree
07-12 17:45:48.331  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 17:45:48.331  4030  4046 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-12 17:45:48.337  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:48.337  4030  4030 D A2dpService: Received start request. Starting profile...
,07-12 17:45:48.338  4030  4030 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:48.339  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:48.339  4030  4030 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:48.346  4030  4030 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:48.346  4030  4030 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:48.346  4030  4030 D A2dpStateMachine: make
,07-12 17:45:48.347  4030  4030 I bt_bluedroid: get_profile_interface a2dp
07-12 17:45:48.348  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-12 17:45:48.350  4030  4060 D A2dpStateMachine: Enter Disconnected: -2
,07-12 17:45:48.351  4030  4030 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 17:45:48.352  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:48.353  4030  4030 D HidService: Received start request. Starting profile...
,07-12 17:45:48.353  4030  4030 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:48.354  4030  4046 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39613e5
07-12 17:45:48.354  4030  4030 D HidService: setHidService(): set to: null
07-12 17:45:48.354  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-12 17:45:48.356  4030  4030 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 17:45:48.357  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:48.358  4030  4030 D HealthService: Received start request. Starting profile...
,07-12 17:45:48.359  4030  4030 I bt_bluedroid: get_profile_interface health
,07-12 17:45:48.361  4030  4030 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 17:45:48.362  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:48.362  4030  4030 D PanService: Received start request. Starting profile...
,07-12 17:45:48.363  4030  4030 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:48.363  4030  4030 I bt_bluedroid: get_profile_interface pan
07-12 17:45:48.364  4030  4046 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 17:45:48.368  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:48.369  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:48.369  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.369  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:48.369  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:48.373  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:48.374  4030  4030 D BluetoothMapService: Received start request. Starting profile...
,07-12 17:45:48.374  4030  4030 D BluetoothMapService: start()
,07-12 17:45:48.378  4030  4030 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-12 17:45:48.379  4030  4030 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-12 17:45:48.380  4030  4030 D BluetoothMapAppObserver: createReceiver()
,07-12 17:45:48.381  4030  4030 D BluetoothMapAppObserver: initObservers()
,07-12 17:45:48.381  4030  4030 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 17:45:48.389  4030  4030 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:48.389  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.389  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:48.389  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:48.390  4030  4058 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.390  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:48.391  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:48.391  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:48.391  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.391  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:48.391  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:48.394  4030  4030 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:48.394  4030  4030 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:48.394  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:48.394  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:48.394  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-12 17:45:48.395  4030  4042 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:48.395  4030  4042 D BluetoothAdapterProperties: State =  11
,07-12 17:45:48.396  4030  4042 D BluetoothAdapterProperties: Setting state to 12
,07-12 17:45:48.396  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 17:45:48.398  3719  3730 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:48.399  4030  4046 D BluetoothAdapterProperties: Scan Mode:21
,07-12 17:45:48.398  4030  4042 I BluetoothAdapterState: Entering OnState
,07-12 17:45:48.400  4030  4046 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:48.403  1349  1366 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:48.405  3719  3719 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 17:45:48.405  3719  3719 D PanProfile: Bluetooth service connected
07-12 17:45:48.406   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:48.406  3719  3729 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:48.407  3719  4025 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:48.407  1349  1349 D BluetoothMap: Proxy object connected
07-12 17:45:48.407  1349  1349 D MapProfile: Bluetooth service connected
07-12 17:45:48.407  1349  1349 D BluetoothMap: getConnectedDevices()
07-12 17:45:48.409  3719  3730 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:48.410  4030  4030 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:48.410  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:48.411  4030  4030 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 17:45:48.411  1740  1970 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:48.412  1349  1857 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:48.413  4030  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:48.413   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:48.413  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:48.413  3719  4025 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-12 17:45:48.415  1349  1366 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:48.416  4030  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:48.418  4030  4030 D ObexServerSockets: Succeed to create listening sockets 
,07-12 17:45:48.419  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:48.419  4030  4030 D ObexServerSockets0: startAccept(),
07-12 17:45:48.419  4030  4030 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:48.419  3719  3729 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 17:45:48.420  3719  3719 D BluetoothMap: Proxy object connected
07-12 17:45:48.420  3719  3719 D MapProfile: Bluetooth service connected
07-12 17:45:48.420  3719  3719 D BluetoothMap: getConnectedDevices()
07-12 17:45:48.422  4030  4030 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-12 17:45:48.422  4030  4030 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-12 17:45:48.425  3719  3719 D BluetoothInputDevice: Proxy object connected
07-12 17:45:48.425  3719  3719 D HidProfile: Bluetooth service connected
07-12 17:45:48.425  1349  1857 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:48.425  1349  1349 D BluetoothA2dp: Proxy object connected
07-12 17:45:48.427  3719  3719 D BluetoothA2dp: Proxy object connected
07-12 17:45:48.427  4030  4068 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:48.428  4030  4067 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:48.428  1349  1366 D BluetoothPan: onBluetoothStateChange on: true
,07-12 17:45:48.434  1349  1349 D BluetoothInputDevice: Proxy object connected
07-12 17:45:48.430   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:48.436   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 17:45:48.436  1349  1349 D HidProfile: Bluetooth service connected
07-12 17:45:48.437   875   875 D BluetoothA2dp: Proxy object connected
,07-12 17:45:48.438  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 17:45:48.438  1349  1349 D PanProfile: Bluetooth service connected
07-12 17:45:48.439  4030  4030 D BluetoothMapService: onReceive
07-12 17:45:48.439  4030  4030 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:48.439  4030  4030 D BluetoothMapService: STATE_ON
,07-12 17:45:48.442   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 17:45:48.445  3719  3719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:48.450  1488  1488 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:48.454  3719  3719 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:48.462  3719  3719 D BluetoothPbap: Proxy object connected
,07-12 17:45:48.462  3719  3719 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:48.467  1349  1349 D BluetoothPbap: Proxy object connected
,07-12 17:45:48.467  1349  1349 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:48.470  4030  4030 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:48.470  4030  4030 D ObexServerSockets0: prepareForNewConnect()
,07-12 17:45:48.473  4030  4073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:48.488  4030  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:48.491  4030  4077 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:48.510   875   875 D BluetoothHeadset: Proxy object connected
,07-12 17:45:48.510   875   875 D BluetoothHeadset: Proxy object connected
07-12 17:45:48.511  1349  1360 D BluetoothHeadset: Proxy object connected,
,07-12 17:45:48.511  1349  1349 D HeadsetProfile: Bluetooth service connected
07-12 17:45:48.511   875   875 D BluetoothHeadset: Proxy object connected
07-12 17:45:48.511  3719  3730 D BluetoothHeadset: Proxy object connected
07-12 17:45:48.511  3719  3719 D HeadsetProfile: Bluetooth service connected
07-12 17:45:48.512  1740  1755 D BluetoothHeadset: Proxy object connected
,07-12 17:45:48.512  1740  1882 D BluetoothHeadset: Proxy object connected
07-12 17:45:48.514   875   892 D BluetoothHeadset: Proxy object connected
,07-12 17:45:48.519  1349  1366 D BluetoothHeadset: Proxy object connected
07-12 17:45:48.519  1349  1349 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:48.536   875   892 D BluetoothHeadset: Proxy object connected
,07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:48.859  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:48.865  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:48.868  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:48.869  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4e195b added. We now have 8 listener(s)
07-12 17:45:48.869  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:48.875   875   886 D WifiService: setWifiEnabled: false pid=3660, uid=10000
,07-12 17:45:48.875   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:48.885  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:48.886   875  1694 D WifiService: setWifiEnabled: true pid=3660, uid=10000
,07-12 17:45:48.887   875  1694 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:48.899   875  1304 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:48.914  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:48.922  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:48.935   875  1304 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:48.935   875  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:48.936   875  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-12 17:45:48.936   875  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:48.937   875  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:48.937   875  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-12 17:45:48.938   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 17:45:48.938   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:48.955   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-12 17:45:48.957   373   873 D CommandListener: Setting iface cfg
,07-12 17:45:48.957   875  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
07-12 17:45:48.957   875  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:48.957   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:45:49.014   875  1303 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:49.015   875  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-12 17:45:49.022   875  1304 E native  : do suspend true
,07-12 17:45:49.079   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:50.450   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:45:50.563   875  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=68.75 delta 1000 -> 994
07-12 17:45:50.565   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-12 17:45:50.565   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:50.585   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-12 17:45:50.629   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 17:45:50.632  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.908  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.914  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:50.922  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-12 17:45:50.926  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-12 17:45:50.940  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@628ad7e Bundle[{}]
,07-12 17:45:50.941  3660  3714 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:50.941  3660  3714 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:45:50.942  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-12 17:45:50.943  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-12 17:45:50.944  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:45:50.945  3660  3714 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:45:50.952  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-12 17:45:50.952  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:50.953  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:50.953  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-12 17:45:50.953  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-12 17:45:50.953  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.961  3660  3714 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 352)
,07-12 17:45:50.961  3660  3714 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 352)
07-12 17:45:50.961  3660  3714 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 352)
,07-12 17:45:50.961  3660  3714 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 352)
,07-12 17:45:50.965  3660  3714 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
,07-12 17:45:50.965  3660  3714 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 358)
07-12 17:45:50.965  3660  3714 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 358)
07-12 17:45:50.966  3660  3714 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 359)
,07-12 17:45:50.968  3660  3714 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
,07-12 17:45:50.970  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-12 17:45:50.971  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5cb5f8 added. We now have 2 listener(s)
,07-12 17:45:50.973  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:50.973  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:50.973  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:50.974  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.974  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bb3ad1 added. We now have 9 listener(s)
07-12 17:45:50.974  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.979  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:50.982  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.988  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.990  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.991  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.991  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.991  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94af037 added. We now have 3 listener(s)
,07-12 17:45:50.993  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:50.993  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.993  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.993  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.993  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba339a4 added. We now have 10 listener(s)
07-12 17:45:50.993  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.994  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.994  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.994  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.994  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.995  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.995  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.995  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.995  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.995  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5cb5f8 removed from the list
,07-12 17:45:50.995  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.995  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bb3ad1 removed from the list
07-12 17:45:50.997  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.997  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.997  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.998  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.998  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.999  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.999  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bb3ad1 not in the list
07-12 17:45:50.999  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.000  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:51.000  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.000  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba339a4 removed from the list
07-12 17:45:51.000  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.000  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.001  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:51.001  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.001  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94af037 removed from the list
07-12 17:45:51.003  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.004  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e7b30d added. We now have 2 listener(s)
07-12 17:45:51.009  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.009  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.010  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.010  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.010  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4362c2 added. We now have 9 listener(s)
07-12 17:45:51.011  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.015  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:51.021  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.027  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:51.031  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:51.032  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.032  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.032  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac4c10 added. We now have 3 listener(s)
07-12 17:45:51.034  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.037  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.038  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.038  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.038  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.039  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.039  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e97309 added. We now have 10 listener(s)
07-12 17:45:51.039  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.040  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.040  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:51.041  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.041  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.055  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.056  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.064  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 17:45:51.077  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:51.081  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:51.082  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.082  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.083  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-12 17:45:51.083  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:51.085  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.091  4030  4041 D BtGatt.GattService: registerClient() - UUID=d78b2483-9e00-4ab2-8cab-6ebce8401f44
,07-12 17:45:51.091  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=d78b2483-9e00-4ab2-8cab-6ebce8401f44, clientIf=5
07-12 17:45:51.092  3660  3670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.094  4030  4040 D BtGatt.GattService: start scan with filters
,07-12 17:45:51.098  4030  4049 D BtGatt.ScanManager: handling starting scan
07-12 17:45:51.098  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:51.098  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-12 17:45:51.098  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-12 17:45:51.099  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-12 17:45:51.099  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:51.099  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:51.099  4030  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@412c032
,07-12 17:45:51.100  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-12 17:45:51.101  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 17:45:51.101  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-12 17:45:51.103  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-12 17:45:51.103  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.104  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:51.106  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.106  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-12 17:45:51.106  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.107  3660  3714 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-12 17:45:51.107  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.107  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.107  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.107  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:51.108   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:51.107  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.108  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-12 17:45:51.108  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.108  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:51.109  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.110  4030  4066 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:51.110  4030  4041 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:51.111  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:51.111  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.111  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.111  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.111  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:51.111  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:51.111  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:51.111  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.112  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:51.112  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:51.112  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.112  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:51.112  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:51.112  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:51.113  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.113  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.113  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.113  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.114   875  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 17:45:51.114   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:51.114   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-12 17:45:51.116  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.116  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.117  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.117  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.117  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.117  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.117  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:51.117  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e7b30d removed from the list
07-12 17:45:51.118  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.118  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4362c2 removed from the list
07-12 17:45:51.118  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:51.119  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:51.119  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.119  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.119  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.119  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:51.119  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-12 17:45:51.119  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:51.119  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.119  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4362c2 not in the list
07-12 17:45:51.124  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.124  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.124  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.125  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.125  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.125  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.128  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.128  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.128  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.129  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-12 17:45:51.130  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:51.131  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:51.132  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.132  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.132  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.132  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.132  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.132  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.132  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e97309 removed from the list
,07-12 17:45:51.132  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.130   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:51.132  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.133  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:51.133  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.133  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac4c10 removed from the list
07-12 17:45:51.133  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.134  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a658d28 added. We now have 2 listener(s)
,07-12 17:45:51.136  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.136  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.136  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.136  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.136  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f7a41 added. We now have 9 listener(s)
,07-12 17:45:51.136  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:51.139  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:51.141  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-12 17:45:51.141  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.141  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.141   373   873 D CommandListener: Setting iface cfg
07-12 17:45:51.142  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.142   875  1304 D WifiStateMachine: Start Dhcp Watchdog 3
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.145  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:51.146  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-12 17:45:51.147  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.147  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:51.147  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:51.148  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.149  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.149  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.149  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1025527 added. We now have 3 listener(s)
07-12 17:45:51.150   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-12 17:45:51.150  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.150  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.150  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.151  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.151  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a53d4 added. We now have 10 listener(s)
07-12 17:45:51.151  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.151  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.151  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.151  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.152  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:51.152  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:51.152  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.152  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.154  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.155  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.155  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:51.158  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:51.158  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.159  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.159  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.159  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:51.159  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-12 17:45:51.159  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.161  4030  4065 D BtGatt.GattService: registerClient() - UUID=550b7c5f-8aac-4c40-b1f9-6c670690127f
07-12 17:45:51.161  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=550b7c5f-8aac-4c40-b1f9-6c670690127f, clientIf=5
07-12 17:45:51.161  3660  3672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.161  4030  4040 D BtGatt.GattService: start scan with filters
,07-12 17:45:51.163  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:51.163  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-12 17:45:51.163  4030  4049 D BtGatt.ScanManager: handling starting scan
07-12 17:45:51.163  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:51.163  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:51.163  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:51.164  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:51.164  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.165  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.165  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-12 17:45:51.165  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.165  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.165  3660  3714 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-12 17:45:51.165  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.165  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.165  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.165  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.165  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-12 17:45:51.166  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.166  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.166  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a658d28 removed from the list
07-12 17:45:51.166  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.166  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f7a41 removed from the list
07-12 17:45:51.166  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.166  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:51.166  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.166  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:51.166  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.167  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:51.167  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.167  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f7a41 not in the list
,07-12 17:45:51.167  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:51.167  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.167  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:51.167  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-12 17:45:51.167  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-12 17:45:51.167  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.168  4030  4041 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:51.168  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:51.168  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.168  4030  4065 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:51.168  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
07-12 17:45:51.168  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.169  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:51.169  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-12 17:45:51.169  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:51.169  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.170  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.170  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-12 17:45:51.170  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71a53d4 removed from the list
07-12 17:45:51.170  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.170  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.170  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:51.170  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.170  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:51.170  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:51.170  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1025527 removed from the list
,07-12 17:45:51.171  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.171  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad83079 added. We now have 2 listener(s)
,07-12 17:45:51.172  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.172  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:51.172  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.172  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.172  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367b1be added. We now have 9 listener(s)
07-12 17:45:51.173  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:51.173  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:51.173  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.173  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:51.173  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:51.175  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.175  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.175  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:51.178  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:51.179  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.180  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:51.180  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.180  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-12 17:45:51.181   875  4085 D DhcpClient: Receive thread started
07-12 17:45:51.182  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.182  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.183  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.183  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.183  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.184  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:51.185  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:51.185  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:51.186  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.186  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c496c added. We now have 3 listener(s)
07-12 17:45:51.187  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.187  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:51.187  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.187  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-12 17:45:51.188  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.187  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.188  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.188  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:51.188  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa25b35 added. We now have 10 listener(s)
07-12 17:45:51.188  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.188  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:51.188  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:51.188  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.188  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.190  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.190  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.192  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:51.192  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.192  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.193  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:51.193  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:51.194  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.194  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.194  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
07-12 17:45:51.194  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:51.194  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.196  4030  4066 D BtGatt.GattService: registerClient() - UUID=f1b35e04-2bc0-40ce-8c8c-3e0153afa798
07-12 17:45:51.196  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=f1b35e04-2bc0-40ce-8c8c-3e0153afa798, clientIf=5
07-12 17:45:51.196  3660  3672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.196  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:51.196  4030  4040 D BtGatt.GattService: start scan with filters
07-12 17:45:51.197  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:51.197  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:51.198  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:51.198  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:51.198  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-12 17:45:51.198  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:51.199  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.199  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:51.199  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:51.200  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.200  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:51.200  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.201  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.201  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:51.203  4030  4049 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:51.203  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.203  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.203  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.203  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.203  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.203  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-12 17:45:51.203  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.204  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad83079 removed from the list
07-12 17:45:51.204  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.205  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367b1be removed from the list
07-12 17:45:51.205  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.205  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.205  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.205  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.205  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.205  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.205  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.205  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367b1be not in the list
07-12 17:45:51.205  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:51.205  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-12 17:45:51.205  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:51.206  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.206  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:51.206  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.207  4030  4069 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:51.207  4030  4041 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:51.207  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:51.208  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.208  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.208  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.208  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:51.208  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:51.208  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-12 17:45:51.208  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-12 17:45:51.209  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.209  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.210  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.210  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:51.210  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:51.210  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.210  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.210  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.210  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:51.212  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-12 17:45:51.212  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.212  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:51.212  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-12 17:45:51.212  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.213  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:51.216  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:51.216  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.216  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-12 17:45:51.217  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.217  3660  3714 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:51.217  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.217  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.217  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.217  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa25b35 removed from the list
07-12 17:45:51.217  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.217  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.217  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.217  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.217  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c496c removed from the list
07-12 17:45:51.218  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.218  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4563a96 added. We now have 2 listener(s)
07-12 17:45:51.219  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.220  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.220  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.221  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:51.221  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.221  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.221  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.221  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.221  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.221  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.221  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494d617 added. We now have 9 listener(s)
07-12 17:45:51.221  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.223  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:51.224  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:51.225  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.225  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.227  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:51.229  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:51.229  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.229  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.229  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fbbed added. We now have 3 listener(s)
,07-12 17:45:51.230  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.230  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:51.231  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.231  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.231  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.231  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.231  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.231  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:51.231  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:51.231  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab36a22 added. We now have 10 listener(s)
07-12 17:45:51.231  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:51.232  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.232  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.232  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.232  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:51.232  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.232  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.232  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.232  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4563a96 removed from the list
07-12 17:45:51.232  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.232  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494d617 removed from the list
,07-12 17:45:51.232  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.232  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.233  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.233  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.233  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.233  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
07-12 17:45:51.233  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.233  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494d617 not in the list
07-12 17:45:51.233  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.234  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.234  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.234  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.234  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.234  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab36a22 removed from the list
07-12 17:45:51.234  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.234  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.234  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.234  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.234  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fbbed removed from the list
07-12 17:45:51.234  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:51.234  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 added. We now have 2 listener(s)
07-12 17:45:51.235  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:51.235  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.235  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-12 17:45:51.236  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 17:45:51.236  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:51.236  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:51.236  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:51.236  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 added. We now have 9 listener(s)
,07-12 17:45:51.236  3660  3714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:51.238  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:51.240  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.240  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.240  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.242  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:51.243  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:51.244  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:51.244  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.245  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-12 17:45:51.245  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-12 17:45:51.245  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:51.246  3660  3714 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-12 17:45:51.246  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.246  3660  3714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:51.246  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:51.246  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-12 17:45:51.246  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-12 17:45:51.246  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.247  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.247  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.247  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.247  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.247  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-12 17:45:51.247  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:51.247  3660  3714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 removed from the list
07-12 17:45:51.247  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.247  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 removed from the list
07-12 17:45:51.248  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.248  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.249  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.249  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.249  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.249  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.249  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.249  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.250  3660  3714 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-12 17:45:51.250  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.250  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.250  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.250  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.250  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.250  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.250  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.251  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.251  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.251  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.251  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.251  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.251  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.251  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.251  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.251  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.251  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.251  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.253  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:51.253  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:51.254  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:51.255  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-12 17:45:51.255  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.255  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.255  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.255  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.255  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.255  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.256  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.256  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.256  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.256  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.256  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.256  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.256  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:51.256  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.256  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.256  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.256  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.257  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.257  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.257  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.257  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.257  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.257  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.257  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.257  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.257  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.257  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.257  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.257  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.257  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.257  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.257  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.257  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.257  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.257  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
,07-12 17:45:51.258  3660  3714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:51.259  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.261  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:51.262  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:51.262  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.263  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.263  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:51.263  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.263  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:51.264  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:51.264  3660  3714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.265  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.266   875  1304 E native  : do suspend false
07-12 17:45:51.266  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.267  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:51.268  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.268  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.268  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.268  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:51.268  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-12 17:45:51.269  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.270  4030  4041 D BtGatt.GattService: registerClient() - UUID=a6faaeb2-ab85-4314-9eb1-34d7932975f3
,07-12 17:45:51.270  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=a6faaeb2-ab85-4314-9eb1-34d7932975f3, clientIf=5
07-12 17:45:51.271  3660  3672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.271  4030  4065 D BtGatt.GattService: start scan with filters
,07-12 17:45:51.273  4030  4049 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:51.273  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:51.273  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:51.273  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:51.273  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:51.274  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.274  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-12 17:45:51.274  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.275  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.275  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:51.275  3660  3714 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:51.275  3660  3660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.275  3660  3660 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:51.275  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.276   875  2088 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 17:45:51.277  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.278  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.278  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.278  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:51.278  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-12 17:45:51.278  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.278  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:51.278  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.278  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:51.279  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.279  4030  4040 D BtGatt.GattService: stopScan() - queue size =1
,07-12 17:45:51.279  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:51.279  4030  4069 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:51.279  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.280  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-12 17:45:51.280  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:51.280  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.280  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.280  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.280  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.280  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.281  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.281  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.281  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:51.281  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.281  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.281  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.281  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.281  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.282  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.282  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:51.282  3660  3714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-12 17:45:51.285  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.285  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.286  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.286  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-12 17:45:51.286  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:51.286  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.286  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.286  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:51.286  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-12 17:45:51.287   875  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172778, domain null
,07-12 17:45:51.288   875  2088 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172778 seconds
07-12 17:45:51.288   875  2088 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.288  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:51.289  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.289  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.289  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.290  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:51.290  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.290  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.290  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-12 17:45:51.292  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.292  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.292  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.292  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:51.292  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:51.293  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.293  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.295  4030  4041 D BtGatt.GattService: registerClient() - UUID=e7237c43-36b8-4aa1-8f54-cd7c399128da
,07-12 17:45:51.295  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=e7237c43-36b8-4aa1-8f54-cd7c399128da, clientIf=5
07-12 17:45:51.296  3660  3670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.296  4030  4069 D BtGatt.GattService: start scan with filters
,07-12 17:45:51.296  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.296  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:51.298  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:51.298  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:51.298  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:51.298  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:51.298  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.298  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:51.298  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:51.299  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.299  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:51.300  3660  3714 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:51.300  3660  3660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.300  3660  3660 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:51.300  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:51.301   875  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 17:45:51.301  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.301  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.301  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.301  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-12 17:45:51.301  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-12 17:45:51.301  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:51.301  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-12 17:45:51.301   875  2088 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-12 17:45:51.301  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.302  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-12 17:45:51.302  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.302  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:51.302  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.303  4030  4069 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:51.303  4030  4065 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:51.303   373   873 D CommandListener: Setting iface cfg
07-12 17:45:51.303  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.303  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.303  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:51.303  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:51.303  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-12 17:45:51.303  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.303  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.304  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.304  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.304  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.304  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:51.304  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.304  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:51.304  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.304  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
,07-12 17:45:51.304  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.304  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.305   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
07-12 17:45:51.306  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.306  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.307   875  2088 D DhcpClient: Scheduling renewal in 86399s
07-12 17:45:51.308   875  1304 E native  : do suspend true
07-12 17:45:51.309  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:51.309  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.310  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.311  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.311  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.311  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.311  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.311  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.311  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.312  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.312  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.312  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:51.312  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.312  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.312  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.312  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.312  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.312  3660  3714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:51.313  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.317  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:51.317  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.317  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:51.318  3660  3714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:51.318  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:51.318  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.318  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-12 17:45:51.320   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-12 17:45:51.321  3660  3714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:51.321  3660  3714 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:51.321  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.321  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:51.322   875  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 17:45:51.322   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-12 17:45:51.323  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.323   875  1306 D ConnectivityService: Adding iface wlan0 to network 102
07-12 17:45:51.323  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:51.323  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:51.325   875  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 17:45:51.327  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:51.327  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.327  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:51.327  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:51.327  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:51.328  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.328  4030  4049 D BtGatt.ScanManager: handling starting scan
07-12 17:45:51.330  4030  4040 D BtGatt.GattService: registerClient() - UUID=1a188e30-63dd-4078-b8d0-c5f954cf564d
07-12 17:45:51.331  4030  4046 D BtGatt.GattService: onClientRegistered() - UUID=1a188e30-63dd-4078-b8d0-c5f954cf564d, clientIf=5
07-12 17:45:51.331  3660  3670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:51.331  4030  4065 D BtGatt.GattService: start scan with filters
07-12 17:45:51.333  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:51.333  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-12 17:45:51.333  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:51.333  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:51.333  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.333  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:51.334  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:51.333  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:51.334  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.334  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:51.335  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.335  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-12 17:45:51.335  3660  3660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:51.335  3660  3660 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:51.335  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:51.335  3660  3714 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:51.335  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.335  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.335  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.335  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:51.335  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:51.336  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.336  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-12 17:45:51.336  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.336  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:51.336  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.337  4030  4069 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:51.337  4030  4040 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:51.337  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.337  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:51.337  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:51.337  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-12 17:45:51.338  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-12 17:45:51.338  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.338  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.338  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.338  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.338  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:51.338  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.338  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:51.339  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-12 17:45:51.340  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.340  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.340  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.340  3660  3714 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-12 17:45:51.340  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:51.340  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.340  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.340  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.340  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:51.340  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.340  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.340  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.340  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.341  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.342  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.343  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.343  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.343  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.345  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:51.345  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:51.345  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.346  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.346  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.346  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.346  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.346  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.346  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.346  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.346  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.347  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.347  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.347  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.347  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.347  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.347  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.347  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.347  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.347  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.347  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.347  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.348  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.348  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.348  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.348  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.348  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.348  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:51.348  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.348  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.348  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.349  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.349  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.349  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.349  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
,07-12 17:45:51.350  3660  3714 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-12 17:45:51.350  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.350  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.350  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.350  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.351  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.351  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.351  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.351  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.351  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.351  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.351  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.351  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.351  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.351  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.351  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.351  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.352  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.352  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:51.352  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.352  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.352  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.353  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.353  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.353  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.354  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-12 17:45:51.354  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.354  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.354  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.354  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.354  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.354  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.354  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.354  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.354  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.355  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:51.355  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.355  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.355  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.355  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.355  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.355  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.355  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.355  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.356  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.356  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.356  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.356  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
,07-12 17:45:51.357  3660  3714 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-12 17:45:51.357  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.357  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-12 17:45:51.357  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.357  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.357  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.357  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.357  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:51.358  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.358  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.358  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.358  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.358  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.358  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:51.358  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.358  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.358  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.358  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:51.358  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.358  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.358  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.359  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.359  3660  3714 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:51.359  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.359  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.359  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.360  3660  3714 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.360  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:51.360  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.360  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:51.360  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:51.360  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.360  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.360  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.361  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.361  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.361  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.361  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.361  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.361  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.361  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.361  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.361  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.361  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.361  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:51.362  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.362  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:51.362  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.362  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.362  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.362  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.363  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.363  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:51.365  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:51.365  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:51.366  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.366  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.366  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:51.366  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:51.366  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-12 17:45:51.366  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.366  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.366  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.368  4030  4049 D BtGatt.ScanManager: handling starting scan
07-12 17:45:51.368  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.368  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.368  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.368  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.368  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.368  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.368  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.368  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.368  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.368  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.368  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.368  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.368  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.369  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.369  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.369  3660  3714 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:51.369  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.369  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.369  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.370  3660  3714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:51.370  3660  3714 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:51.370  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:51.371  3660  3714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:51.371  3660  3714 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:51.371   875  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-12 17:45:51.371   875  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:51.371  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:51.372  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:51.372  3660  3714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-12 17:45:51.373  3660  3714 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-12 17:45:51.373   875  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-12 17:45:51.373  3660  3714 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-12 17:45:51.373  3660  3714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:51.373  3660  3714 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-12 17:45:51.373  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.373  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.373  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.374   875  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-12 17:45:51.374  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.374  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.374  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.374  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.374  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.374  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.374  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.374  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.374  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.374  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.374  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.374  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.374  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.374   875  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-12 17:45:51.375  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:51.375  4030  4046 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:51.375  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.375  4030  4049 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:51.375  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.375  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.375  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:51.375  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.375  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.376  3660  3714 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-12 17:45:51.376  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.376  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.376  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.376  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.376  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.376  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.376  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.377  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.377  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.377  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.377  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.377  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.377  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.377  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.377  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.377  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.377  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.378  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.378  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.378  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.378  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.378  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.378  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.378  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.378  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.379  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:51.379  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.379  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.379  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.379  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.379  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.379  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.379  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.379  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.379  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.379  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.379  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.379  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.379  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.380  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.380  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.380  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.380  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.380  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.381  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.381  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.381  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.381  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.381  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.381  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.381  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.381  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:51.381  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.381  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.381  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.381  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.381  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.381  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.381  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.381  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.382  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.383  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.383  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.383  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.383  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.383  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.383  3660  3714 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-12 17:45:51.383  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.383  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.384  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.384  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.384  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.384  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.384  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.384  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.384  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.384  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.384  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.384  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.384  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.384  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:51.384  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.384  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.384  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.385  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:51.385  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.385  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.385  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.385  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.385  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.385  4030  4049 D BtGatt.ScanManager: Starting BLE batch scan
,07-12 17:45:51.385  4030  4049 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:51.385  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.385  3660  3714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-12 17:45:51.385  3660  3714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-12 17:45:51.385  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:51.386  3660  3714 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-12 17:45:51.386  3660  3714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:51.386  3660  3714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-12 17:45:51.386  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-12 17:45:51.386  3660  3714 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-12 17:45:51.386  3660  3714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:51.386  3660  3714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:51.386  3660  3714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:51.386  3660  3714 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-12 17:45:51.386  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.386  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.386  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.386  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.386  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.387  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.387  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.387  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.387  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.387  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.387  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.387  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.387  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.387  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.387  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.387  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.387  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.387  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.388  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.388  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.388  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.388  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.388  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.388  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.388  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.388  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.388  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.388  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.388  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.388  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.388  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.389  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.389  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.389  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:51.389  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.389  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.389  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.389  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.389   875  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-12 17:45:51.389  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.389  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.389  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.389  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.389  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.389  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.389  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.390  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.390  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.390  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.390  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.390  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.390  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.390  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.390  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.390  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.390  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.390  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.390  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.390  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.390  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
,07-12 17:45:51.391  3660  3714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-12 17:45:51.391  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.392  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-12 17:45:51.392  4030  4046 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:51.392  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.393  3660  3714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-12 17:45:51.393  3660  3714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-12 17:45:51.393  3660  3660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-12 17:45:51.393  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-12 17:45:51.393  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.393  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:51.393  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-12 17:45:51.393  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-12 17:45:51.393  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-12 17:45:51.393  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.394  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.394  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.394  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:51.394  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:51.394  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:51.394  3660  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:51.395  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.395  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:51.395  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.395  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.395  3660  3714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.395  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.395  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:51.395  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.396  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.396  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.396  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.396  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:51.396  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:51.396  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.396  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.396  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.397   875  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
07-12 17:45:51.397   875  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-12 17:45:51.397   875  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-12 17:45:51.398   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:51.398   875  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-12 17:45:51.398   875  1306 D ConnectivityService:    accepting network in place of null
07-12 17:45:51.398  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.398  3660  3660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:51.399  3660  4088 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-12 17:45:51.400  3660  4088 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-12 17:45:51.399   875  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:51.401  4030  4046 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-12 17:45:51.401  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:51.401  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.401  4030  4049 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:51.402  3660  3660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:51.402  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:51.402  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.402  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.402  3660  3660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:51.402  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.402  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:51.402  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:51.402  3660  3660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:51.402  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.402  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.403  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.403  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.403  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.403  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.403  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.403  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:51.404  3660  3660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:51.404  3660  3660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:51.405  3660  3660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-12 17:45:51.405  3660  3660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-12 17:45:51.405  3660  3660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-12 17:45:51.405  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.405  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.405  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.405  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.406  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.406  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:51.406  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.406  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.406  4030  4046 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:51.406  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.407  4030  4049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:51.407  3660  3714 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-12 17:45:51.408  3660  3714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:51.408  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:51.409  3660  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:51.409  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.409  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:51.409  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.409  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.409  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.409  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.410  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.410  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.410  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.410  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.410  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.410  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.410  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.410  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.410  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.410  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.410  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.410  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.410  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.411  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.411  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.411  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.411  4030  4046 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:51.411  4030  4046 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:51.414  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.414  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:51.414  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.414  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.414  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.414  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.414  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.415  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.415  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.415  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.415  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.415  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.415  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.415  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.415  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.415  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.415  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.415  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.415  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.415  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.415  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.416  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.416  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.416  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.416  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.416  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.416  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.416  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:51.416  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.416  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.416  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.416  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.416  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.416  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.417  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.417  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.417  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.417  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.417  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:51.417  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.417  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.417  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.417  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.417  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.418  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.418  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.418  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.418  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.418  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.418  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.418  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
,07-12 17:45:51.418  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.418  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.418  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.418  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.418  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.418  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.418  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.418  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.418  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.419  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.419  3660  3714 D BluetoothAdapter: STATE_ON
,07-12 17:45:51.419  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.419  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.419  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.419  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.420  3660  3714 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:51.420  3660  3714 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-12 17:45:51.420  3660  3660 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-12 17:45:51.420  3660  3714 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-12 17:45:51.420  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.420  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:51.421  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:51.421  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.421  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.421  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.421  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.421  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.421  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.421  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.421  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.421  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.421  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.421  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:51.421  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.421  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.421  3660  3714 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-12 17:45:51.421  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.422  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.422  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.422  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.422  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.422  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.422  3660  3714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:51.422  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:51.422  3660  3714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:51.422  3660  3714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:51.422  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.422  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.422  3660  3714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106bcb3 not in the list
07-12 17:45:51.422  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.422  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.422  3660  3714 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:51.422  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.422  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.422  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:51.423  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:51.423  3660  3714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:51.423  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:51.423  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:51.423  3660  3714 D BluetoothAdapter: STATE_ON
07-12 17:45:51.423  3660  3714 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:51.423  3660  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:51.423  3660  3714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:51.423  3660  3714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf1270 not in the list
07-12 17:45:51.424  3660  3714 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-12 17:45:51.424  3660  3714 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-12 17:45:51.424  3660  3714 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-12 17:45:51.424  3660  3714 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-12 17:45:51.424  3660  3714 E com.test.thalitest.ThaliTestRunner: Total duration: 29708 ms
,07-12 17:45:51.425  3660  3714 I jxcore-log: PromiseSuccess
07-12 17:45:51.425  3660  3714 I jxcore-log: 
07-12 17:45:51.427  3660  3714 I jxcore-log: My device name is: motorola-Nexus 6
07-12 17:45:51.427  3660  3714 I jxcore-log: 
07-12 17:45:51.428  3660  3714 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 17:45:51.428  3660  3714 I jxcore-log: 
07-12 17:45:51.430   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-12 17:45:51.432   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=203432, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:51.460   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,07-12 17:45:51.462   875  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-12 17:45:51.462   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:51.465   875   892 D Tethering: MasterInitialState.processMessage what=3
,07-12 17:45:51.468   875  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:51.470  3660  3660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:51.471  3660  3660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:51.500  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 17:45:51.503  1804  2358 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:51.504  1804  2358 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:51.509  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:51.510  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-12 17:45:51.512  3774  3774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:51.514   875  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:815::200e
,07-12 17:45:51.517  3774  3774 D SprintDMHelper: simOperator: 
,07-12 17:45:51.517  3774  3774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-12 17:45:51.524  1804  4096 I MDM     : [208] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-12 17:45:51.524  1804  4096 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:45:51.531  1804  4096 V GoogleAuthProtoRequest: [208] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:45:51.545  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:51.555  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:51.544  1804  2358 I iu.SyncManager: NEXT; no task
,07-12 17:45:51.581  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-12 17:45:51.582  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-12 17:45:51.582  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:51.582  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:51.590   875  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 15:45:51 GMT], X-Android-Received-Millis=[1468338351589], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468338351558]}
,07-12 17:45:51.596   875  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 17:45:51.596   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-12 17:45:51.596   875  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-12 17:45:51.597   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 17:45:51.601  1804  4096 E MDM     : [208] SitrepService.a: Error sending sitrep.
,07-12 17:45:51.644  2382  4099 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-12 17:45:52.463   875  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,07-12 17:45:55.443  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 17:45:55.443  3660  3714 I jxcore-log: 
,07-12 17:45:55.841  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 17:45:55.841  3660  3714 I jxcore-log: 
,07-12 17:45:55.866  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 17:45:55.866  3660  3714 I jxcore-log: 
,07-12 17:45:55.871  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 17:45:55.871  3660  3714 I jxcore-log: 
,07-12 17:45:55.887  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 17:45:55.887  3660  3714 I jxcore-log: 
,07-12 17:45:55.892  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 17:45:55.892  3660  3714 I jxcore-log: 
,07-12 17:45:57.895  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 17:45:57.895  3660  3714 I jxcore-log: 
,07-12 17:45:57.907  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 17:45:57.907  3660  3714 I jxcore-log: 
,07-12 17:45:57.917  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 17:45:57.917  3660  3714 I jxcore-log: 
,07-12 17:45:58.075  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 17:45:58.075  3660  3714 I jxcore-log: 
,07-12 17:45:58.786  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 17:45:58.786  3660  3714 I jxcore-log: 
,07-12 17:45:58.843  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 17:45:58.843  3660  3714 I jxcore-log: 
,07-12 17:45:58.850  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 17:45:58.850  3660  3714 I jxcore-log: 
,07-12 17:45:59.056  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 17:45:59.056  3660  3714 I jxcore-log: 
,07-12 17:45:59.078  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 17:45:59.078  3660  3714 I jxcore-log: 
,07-12 17:45:59.083  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 17:45:59.083  3660  3714 I jxcore-log: 
,07-12 17:45:59.089  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 17:45:59.089  3660  3714 I jxcore-log: 
,07-12 17:45:59.106  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 17:45:59.106  3660  3714 I jxcore-log: 
,07-12 17:45:59.126  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 17:45:59.126  3660  3714 I jxcore-log: 
,07-12 17:45:59.214  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 17:45:59.214  3660  3714 I jxcore-log: 
,07-12 17:45:59.219  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 17:45:59.219  3660  3714 I jxcore-log: 
,07-12 17:45:59.247  3660  3714 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 17:45:59.247  3660  3714 I jxcore-log: 
,07-12 17:45:59.261  3660  3714 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 17:45:59.262  3660  3714 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 17:45:59.262  3660  3714 I jxcore-log: 
,07-12 17:45:59.312  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:59.312  3660  3714 I jxcore-log: 
,07-12 17:45:59.314  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:59.314  3660  3714 I jxcore-log: 
,07-12 17:45:59.314  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.314  3660  3714 I jxcore-log: 
,07-12 17:45:59.316  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.316  3660  3714 I jxcore-log: 
,07-12 17:45:59.318  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.318  3660  3714 I jxcore-log: 
,07-12 17:45:59.318  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.318  3660  3714 I jxcore-log: 
,07-12 17:45:59.319  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.319  3660  3714 I jxcore-log: 
07-12 17:45:59.320  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.320  3660  3714 I jxcore-log: 
,07-12 17:45:59.320  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:59.320  3660  3714 I jxcore-log: 
,07-12 17:45:59.321  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:59.321  3660  3714 I jxcore-log: 
,07-12 17:45:59.322  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.322  3660  3714 I jxcore-log: 
,07-12 17:45:59.323  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.323  3660  3714 I jxcore-log: 
,07-12 17:45:59.323  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.323  3660  3714 I jxcore-log: 
07-12 17:45:59.324  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.324  3660  3714 I jxcore-log: 
07-12 17:45:59.324  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.324  3660  3714 I jxcore-log: 
07-12 17:45:59.325  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.325  3660  3714 I jxcore-log: 
,07-12 17:45:59.325  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.325  3660  3714 I jxcore-log: 
07-12 17:45:59.326  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.326  3660  3714 I jxcore-log: 
07-12 17:45:59.326  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.326  3660  3714 I jxcore-log: 
,07-12 17:45:59.327  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:59.327  3660  3714 I jxcore-log: 
07-12 17:45:59.327  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.327  3660  3714 I jxcore-log: 
07-12 17:45:59.327  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.327  3660  3714 I jxcore-log: 
07-12 17:45:59.328  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.328  3660  3714 I jxcore-log: 
,07-12 17:45:59.328  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.328  3660  3714 I jxcore-log: 
07-12 17:45:59.329  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.329  3660  3714 I jxcore-log: 
07-12 17:45:59.330  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.330  3660  3714 I jxcore-log: 
07-12 17:45:59.330  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:59.330  3660  3714 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
07-12 17:45:59.331  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.331  3660  3714 I jxcore-log: 
07-12 17:45:59.331  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.331  3660  3714 I jxcore-log: 
07-12 17:45:59.332  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.332  3660  3714 I jxcore-log: 
07-12 17:45:59.332  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.332  3660  3714 I jxcore-log: 
07-12 17:45:59.333  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.333  3660  3714 I jxcore-log: 
07-12 17:45:59.333  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.333  3660  3714 I jxcore-log: 
07-12 17:45:59.334  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.334  3660  3714 I jxcore-log: 
07-12 17:45:59.334  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.334  3660  3714 I jxcore-log: 
07-12 17:45:59.334  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.334  3660  3714 I jxcore-log: 
07-12 17:45:59.335  3660  3714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:59.335  3660  3714 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
07-12 17:45:59.335  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.335  3660  3714 I jxcore-log: 
07-12 17:45:59.336  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.336  3660  3714 I jxcore-log: 
07-12 17:45:59.337  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.337  3660  3714 I jxcore-log: 
,07-12 17:45:59.337  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.337  3660  3714 I jxcore-log: 
07-12 17:45:59.338  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.338  3660  3714 I jxcore-log: 
,07-12 17:45:59.338  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.338  3660  3714 I jxcore-log: 
,07-12 17:45:59.339  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.339  3660  3714 I jxcore-log: 
,07-12 17:45:59.340  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.340  3660  3714 I jxcore-log: 
07-12 17:45:59.340  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.340  3660  3714 I jxcore-log: 
,07-12 17:45:59.341  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.341  3660  3714 I jxcore-log: 
,07-12 17:45:59.341  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.341  3660  3714 I jxcore-log: 
,07-12 17:45:59.342  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.342  3660  3714 I jxcore-log: 
,07-12 17:45:59.343  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.343  3660  3714 I jxcore-log: 
,07-12 17:45:59.343  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.343  3660  3714 I jxcore-log: 
,07-12 17:45:59.344  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.344  3660  3714 I jxcore-log: 
07-12 17:45:59.344  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:59.344  3660  3714 I jxcore-log: 
,07-12 17:45:59.345  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.345  3660  3714 I jxcore-log: 
,07-12 17:45:59.345  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:45:59.345  3660  3714 I jxcore-log: 
,07-12 17:45:59.346  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.346  3660  3714 I jxcore-log: 
,07-12 17:45:59.346  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.346  3660  3714 I jxcore-log: 
,07-12 17:45:59.347  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-12 17:45:59.347  3660  3714 I jxcore-log: 
07-12 17:45:59.347  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:59.347  3660  3714 I jxcore-log: 
07-12 17:45:59.348  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-12 17:45:59.348  3660  3714 I jxcore-log: 
07-12 17:45:59.349  3660  3714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:59.349  3660  3714 I jxcore-log: 
,07-12 17:45:59.398   875  1306 D ConnectivityService: handlePromptUnvalidated 102
,07-12 17:46:07.377   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219377, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:46:09.692  1650  1774 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-12 17:46:09.693  1650  1774 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 17:46:09.744  1488  1488 I ConfigService: onCreate
,07-12 17:46:14.833  1488  1488 I ConfigService: onDestroy
,07-12 17:46:20.424   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:46:21.626  3913  4109 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:46:21.658  3913  4110 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:46:21.674  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:21.677  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:21.715  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 17:46:21.715  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:46:21.715  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:46:21.715  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:21.749  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:21.752  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:21.789  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:46:21.789  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:46:21.789  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:46:21.789  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:21.811  3913  4110 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:46:21.813  3913  4109 E BooksSync: Soft error
07-12 17:46:21.813  3913  4109 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:46:21.813  3913  4109 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:46:21.813  3913  4109 E BooksSync: Sync error
07-12 17:46:21.813  3913  4109 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:46:21.813  3913  4109 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:46:21.816  3913  4109 I BooksSync: Finished books sync
,07-12 17:46:21.829   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212122, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:46:35.891   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=247890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:46:52.181  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:52.182  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:52.214  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:46:52.214  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:46:52.214  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:46:52.214  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:52.227  2864  4113 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 17:46:52.227  2864  4113 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at blb.a(PG:3937)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at czp.a(PG:18188)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:46:52.227  2864  4113 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	... 12 more
07-12 17:46:52.227  2864  4113 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at fal.a(PG:38)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:46:52.227  2864  4113 E HttpOperation: 	... 14 more
,07-12 17:46:52.260  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:46:52.260  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:46:52.260  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:46:52.260  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:52.309  2864  4113 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 17:46:52.309  2864  4113 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at hec.a(PG:42)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at hee.a(PG:102)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at czr.a(PG:65)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at kka.a(PG:108)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at czp.a(PG:19176)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:46:52.309  2864  4113 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	... 15 more
07-12 17:46:52.309  2864  4113 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at fal.a(PG:38)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:46:52.309  2864  4113 E HttpOperation: 	... 17 more
,07-12 17:46:52.309  2864  4113 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 17:46:52.309  2864  4113 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at hec.a(PG:42)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at hee.a(PG:102)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at czr.a(PG:65)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at kka.a(PG:108)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	... 15 more
07-12 17:46:52.309  2864  4113 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at fal.a(PG:38)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 17:46:52.309  2864  4113 E ExperimentLoader: 	... 17 more
,07-12 17:46:52.445   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 248519, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:46:56.264   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:47:11.730   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:47:22.591  3913  4120 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:47:22.624  3913  4122 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:47:22.643  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:22.647  2910  4121 V KeepSync: Connecting to GoogleApiClient
,07-12 17:47:22.653  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:47:22.654   875  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:47:22.708  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:47:22.708  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:47:22.709  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:22.709  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:22.801  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:47:22.801  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:47:22.801  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:47:22.801  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:22.866  1804  4123 V BaseAuthAsyncOperation: access token request failed
,07-12 17:47:22.867  2910  4121 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:47:22.868  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:47:22.868  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:47:22.868  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:47:22.869  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:22.893  3913  4122 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:47:22.893  3913  4120 E BooksSync: Soft error
07-12 17:47:22.893  3913  4120 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:47:22.893  3913  4120 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:47:22.894  3913  4120 E BooksSync: Sync error
07-12 17:47:22.894  3913  4120 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:47:22.894  3913  4120 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:47:22.894  3913  4120 I BooksSync: Finished books sync
,07-12 17:47:22.903   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 266276, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:47:22.943  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:47:22.943  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:47:22.944  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:47:22.944  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:22.960  2910  4121 E KeepSync: IOException
07-12 17:47:22.960  2910  4121 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:47:22.960  2910  4121 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:47:22.960  2910  4121 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:47:22.960  2910  4121 E KeepSync: 	... 10 more
,07-12 17:47:22.960  2910  4121 W KeepSync: Sync result 2
,07-12 17:47:23.001   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 290788, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:47:53.308  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:53.309  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:53.353  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:47:53.354  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:47:53.354  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:53.354  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:53.375  2864  4126 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 17:47:53.375  2864  4126 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at blb.a(PG:3937)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at czp.a(PG:18188)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:47:53.375  2864  4126 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	... 12 more
07-12 17:47:53.375  2864  4126 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at fal.a(PG:38)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:47:53.375  2864  4126 E HttpOperation: 	... 14 more
,07-12 17:47:53.464  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:47:53.464  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:47:53.464  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:53.464  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:53.492  2864  4126 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 17:47:53.492  2864  4126 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at hec.a(PG:42)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at hee.a(PG:102)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at czr.a(PG:65)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at kka.a(PG:108)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at czp.a(PG:19176)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:47:53.492  2864  4126 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	... 15 more
07-12 17:47:53.492  2864  4126 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at fal.a(PG:38)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:47:53.492  2864  4126 E HttpOperation: 	... 17 more
,07-12 17:47:53.493  2864  4126 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 17:47:53.493  2864  4126 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at hec.a(PG:42)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at hee.a(PG:102)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at czr.a(PG:65)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at kka.a(PG:108)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	... 15 more
07-12 17:47:53.493  2864  4126 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at fal.a(PG:38)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 17:47:53.493  2864  4126 E ExperimentLoader: 	... 17 more
,07-12 17:47:53.659   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 295854, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:48:09.698  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:09.721  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:09.726  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:09.769  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 17:48:09.769  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 17:48:09.769  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:09.769  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:09.800  1488  2040 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-12 17:48:09.800  1488  2040 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:48:09.810  3378  3411 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 17:48:09.810  3378  3411 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-12 17:48:09.810  3378  3411 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-12 17:48:09.810  3378  3411 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-12 17:48:09.810  3378  3411 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-12 17:48:09.810  3378  3411 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-12 17:48:09.810  3378  3411 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:48:14.851   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=346850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:48:23.823  2910  4132 V KeepSync: Connecting to GoogleApiClient
,07-12 17:48:23.824   875  1786 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:48:23.872  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:23.875  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:23.902  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:48:23.902  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:48:23.902  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:23.902  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:23.927  1804  4133 V BaseAuthAsyncOperation: access token request failed
,07-12 17:48:23.928  2910  4132 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:48:23.973  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:48:23.973  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:48:23.974  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:23.974  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:23.988  2910  4132 E KeepSync: IOException
07-12 17:48:23.988  2910  4132 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:48:23.988  2910  4132 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:48:23.988  2910  4132 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:48:23.988  2910  4132 E KeepSync: 	... 10 more
,07-12 17:48:23.988  2910  4132 W KeepSync: Sync result 2
,07-12 17:48:24.005   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 326176, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:48:25.624   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=357624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:48:54.211  3913  4135 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:48:54.238  3913  4136 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:48:54.263  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:54.266  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:54.299  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:48:54.300  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:48:54.300  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:54.300  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:54.327  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:48:54.329  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:54.358  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 17:48:54.358  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:48:54.358  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:54.358  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:54.375  3913  4136 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:48:54.377  3913  4135 E BooksSync: Soft error
07-12 17:48:54.377  3913  4135 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:48:54.377  3913  4135 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:48:54.377  3913  4135 E BooksSync: Sync error
07-12 17:48:54.377  3913  4135 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:48:54.377  3913  4135 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:48:54.379  3913  4135 I BooksSync: Finished books sync
,07-12 17:48:54.384   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 359795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:49:16.238   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:49:24.733  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:24.737  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:24.768  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:49:24.768  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:49:24.769  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:49:24.769  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:24.793  2864  4141 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 17:49:24.793  2864  4141 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at blb.a(PG:3937)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at czp.a(PG:18188)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:49:24.793  2864  4141 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	... 12 more
07-12 17:49:24.793  2864  4141 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at fal.a(PG:38)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:49:24.793  2864  4141 E HttpOperation: 	... 14 more
,07-12 17:49:24.853  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:49:24.853  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:49:24.853  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:49:24.853  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:24.869  2864  4141 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 17:49:24.869  2864  4141 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at hec.a(PG:42)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at hee.a(PG:102)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at czr.a(PG:65)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at kka.a(PG:108)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at czp.a(PG:19176)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:49:24.869  2864  4141 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	... 15 more
07-12 17:49:24.869  2864  4141 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at fal.a(PG:38)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:49:24.869  2864  4141 E HttpOperation: 	,... 17 more
07-12 17:49:24.869  2864  4141 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 17:49:24.869  2864  4141 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at hec.a(PG:42)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at hee.a(PG:102)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at czr.a(PG:65)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at kka.a(PG:108)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jdj.a(PG:4091),
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	... 15 more
07-12 17:49:24.869  2864  4141 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at fal.a(PG:38)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 17:49:24.869  2864  4141 E ExperimentLoader: 	... 17 more
,07-12 17:49:24.996   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 388478, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:49:31.731   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:49:55.127  2910  4145 V KeepSync: Connecting to GoogleApiClient
07-12 17:49:55.127   875  1786 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:49:55.185  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:55.188  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:55.229  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:49:55.229  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 17:49:55.230  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:49:55.230  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:55.258  1804  4146 V BaseAuthAsyncOperation: access token request failed
,07-12 17:49:55.259  2910  4145 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:49:55.322  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:49:55.322  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-12 17:49:55.322  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:49:55.322  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:55.346  2910  4145 E KeepSync: IOException
07-12 17:49:55.346  2910  4145 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:49:55.346  2910  4145 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:49:55.346  2910  4145 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:49:55.346  2910  4145 E KeepSync: 	... 10 more
,07-12 17:49:55.347  2910  4145 W KeepSync: Sync result 2
,07-12 17:49:55.357   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 418353, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:49:56.824   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=448823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:50:12.264   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=464264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:50:56.598   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=508597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:51:04.210  3913  4150 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:51:04.233  3913  4151 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:51:04.248  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:04.251  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:04.277  1488  4138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:51:04.278  1488  4138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:51:04.278  1488  4138 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:04.278  1488  4138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:04.309  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:04.312  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:04.340  1488  2350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:51:04.340  1488  2350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:51:04.340  1488  2350 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:51:04.340  1488  2350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:04.359  3913  4151 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:51:04.360  3913  4150 E BooksSync: Soft error
07-12 17:51:04.360  3913  4150 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:51:04.360  3913  4150 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:51:04.360  3913  4150 E BooksSync: Sync error
07-12 17:51:04.360  3913  4150 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:51:04.360  3913  4150 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:51:04.360  3913  4150 I BooksSync: Finished books sync
,07-12 17:51:04.371   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 516168, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:51:12.051   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=524051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:51:24.832  1488  1987 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:51:26.237   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=538237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:51:34.796  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:34.797  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:34.835  1488  2842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 17:51:34.835  1488  2842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:51:34.835  1488  2842 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:34.835  1488  2842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:34.853  2864  4154 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 17:51:34.853  2864  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at blb.a(PG:3937)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at czp.a(PG:18188)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:51:34.853  2864  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	... 12 more
07-12 17:51:34.853  2864  4154 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at fal.a(PG:38)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:51:34.853  2864  4154 E HttpOperation: 	... 14 more
,07-12 17:51:34.904  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 17:51:34.904  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:51:34.904  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:34.904  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:34.949  2864  4154 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 17:51:34.949  2864  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at hec.a(PG:42)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at hee.a(PG:102)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at czr.a(PG:65)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at kka.a(PG:108)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at czp.a(PG:19176)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:51:34.949  2864  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	... 15 more
07-12 17:51:34.949  2864  4154 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at fal.a(PG:38)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:51:34.949  2864  4154 E HttpOperation: 	... 17 more
07-12 17:51:34.949  2864  4154 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 17:51:34.949  2864  4154 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at hec.a(PG:42)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at hee.a(PG:102)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at czr.a(PG:65)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at kka.a(PG:108)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	... 15 more
07-12 17:51:34.949  2864  4154 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at fal.a(PG:38)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 17:51:34.949  2864  4154 E ExperimentLoader: 	... 17 more
,07-12 17:51:35.122   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 542633, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:51:41.704   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=553704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:51:55.731   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=567730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:52:05.394  2910  4158 V KeepSync: Connecting to GoogleApiClient
07-12 17:52:05.395   875  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:52:05.444  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:52:05.447  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:52:05.482  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 17:52:05.482  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 17:52:05.482  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:52:05.482  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:52:05.505  1804  4159 V BaseAuthAsyncOperation: access token request failed
,07-12 17:52:05.507  2910  4158 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:52:05.575  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:52:05.575  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:52:05.575  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:52:05.575  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:52:05.601  2910  4158 E KeepSync: IOException
07-12 17:52:05.601  2910  4158 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:52:05.601  2910  4158 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:52:05.601  2910  4158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:52:05.601  2910  4158 E KeepSync: 	... 10 more
,07-12 17:52:05.601  2910  4158 W KeepSync: Sync result 2
,07-12 17:52:05.615   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 572053, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:52:11.197   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=583197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:53:15.184   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:53:30.717   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=662717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:55:24.033  3913  4170 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:55:24.068  3913  4171 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 17:55:24.085  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:24.087  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:24.152  1488  4138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:55:24.152  1488  4138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:55:24.152  1488  4138 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:55:24.153  1488  4138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:24.196  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:24.199  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:24.229  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:55:24.229  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:55:24.229  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:55:24.229  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:24.244  3913  4171 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:55:24.245  3913  4170 E BooksSync: Soft error
07-12 17:55:24.245  3913  4170 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:55:24.245  3913  4170 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:55:24.245  3913  4170 E BooksSync: Sync error
07-12 17:55:24.245  3913  4170 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:55:24.245  3913  4170 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:55:24.245  3913  4170 I BooksSync: Finished books sync
,07-12 17:55:24.252   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 775940, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:55:54.600  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:54.602  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:54.632  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:55:54.633  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:55:54.633  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-12 17:55:54.633  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:54.654  2864  4175 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 17:55:54.654  2864  4175 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at blb.a(PG:3937)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at czp.a(PG:18188)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:55:54.654  2864  4175 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	... 12 more
07-12 17:55:54.654  2864  4175 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at fal.a(PG:38)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:55:54.654  2864  4175 E HttpOperation: 	... 14 more
,07-12 17:55:54.746  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 17:55:54.746  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 17:55:54.746  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:55:54.746  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:54.785  2864  4175 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 17:55:54.785  2864  4175 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jdm.a(PG:82)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jcs.o(PG:406)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jcn.a(PG:1379)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jcs.i(PG:143)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at hec.a(PG:42)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at hee.a(PG:102)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at czr.a(PG:65)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at kka.a(PG:108)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at czp.a(PG:19176)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at czp.a(PG:9081)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at czq.run(PG:1686)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:55:54.785  2864  4175 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jdj.a(PG:4091)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jdj.a(PG:1125)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jdm.a(PG:77)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	... 15 more
07-12 17:55:54.785  2864  4175 E HttpOperation: Caused by: faj: BadAuthentication
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at fal.a(PG:38)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	at jdj.a(PG:4089)
07-12 17:55:54.785  2864  4175 E HttpOperation: 	... 17 more
,07-12 17:55:54.785  2864  4175 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 17:55:54.785  2864  4175 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at hec.a(PG:42)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at hee.a(PG:102)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at czr.a(PG:65)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at kka.a(PG:108)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	... 15 more
07-12 17:55:54.785  2864  4175 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at fal.a(PG:38)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 17:55:54.785  2864  4175 E ExperimentLoader: 	... 17 more
,07-12 17:55:54.911   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 798395, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:56:25.083  2910  4179 V KeepSync: Connecting to GoogleApiClient
,07-12 17:56:25.084   875  1743 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 17:56:25.141  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:56:25.142  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:56:25.163  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:56:25.163  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 17:56:25.163  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:56:25.163  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:56:25.193  1804  4180 V BaseAuthAsyncOperation: access token request failed
,07-12 17:56:25.194  2910  4179 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:56:25.233  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:56:25.233  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:56:25.233  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:56:25.233  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:56:25.245  2910  4179 E KeepSync: IOException
07-12 17:56:25.245  2910  4179 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:56:25.245  2910  4179 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:56:25.245  2910  4179 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:56:25.245  2910  4179 E KeepSync: 	... 10 more
,07-12 17:56:25.245  2910  4179 W KeepSync: Sync result 2
,07-12 17:56:25.255   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 827007, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:57:54.693  1488  1987 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 18:02:07.063  1804  1804 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,07-12 18:02:07.096  1804  4195 I EventLogService: Opted in for usage reporting
,07-12 18:02:07.097  1804  4195 I EventLogService: Aggregate from 1468336698166 (log), 1468336698166 (data)
,07-12 18:02:07.142  1804  4196 I CheckinService: Checking schedule, now: 1468339327142 next: 1468339326995
,07-12 18:02:07.142  1804  4196 I CheckinService: active receiver: enabled
,07-12 18:02:07.146  1804  4196 I CheckinService: Preparing to send checkin request
,07-12 18:02:07.169  1804  4195 W EventLogAggregator: Unknown tag: snet_gcore
,07-12 18:02:07.169  1804  4195 W EventLogAggregator: Unknown tag: snet_launch_service
,07-12 18:02:07.299  1804  4196 I EventLogService: Accumulating logs since 1468339327169
,07-12 18:02:07.310  1804  4196 I EventLogService: Opted in for usage reporting
,07-12 18:02:07.329  1804  4195 I ServiceDumpSys: dumping service [account]
,07-12 18:02:07.363  1804  4196 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1
,07-12 18:02:07.367   875  1305 D WifiService: New client listening to asynchronous messages
,07-12 18:02:07.368  1804  4196 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-12 18:02:07.492  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:07.497  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:07.544  1488  1921 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-12 18:02:07.545  1488  1921 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-12 18:02:07.545  1488  1921 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 18:02:07.545  1488  1921 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:02:07.565  1804  4196 W CheckinRequestBuilder: awaiting user notification for token
,07-12 18:02:07.619   875  1743 I ActivityManager: Start proc 4203:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 18:02:07.743  4203  4203 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-12 18:02:07.759  4203  4203 I MultiDex: VM with version 2.1.0 has multidex support
07-12 18:02:07.759  4203  4203 I MultiDex: install
07-12 18:02:07.759  4203  4203 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 18:02:07.813  4203  4203 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 18:02:07.838  4203  4203 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 18:02:07.844  1488  2316 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 18:02:07.851  1488  1488 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 18:02:07.869  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:07.872  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-12 18:02:07.934   875  1690 I ActivityManager: Start proc 4219:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,07-12 18:02:07.980  4219  4219 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-12 18:02:07.990  4219  4219 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 18:02:07.990  4219  4219 I MultiDex: install
07-12 18:02:07.990  4219  4219 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 18:02:08.008  4203  4214 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 18:02:08.009   377  1313 D WVCdm   : Instantiating CDM.
,07-12 18:02:08.009   377  1276 I WVCdm   : CdmEngine::OpenSession
07-12 18:02:08.009   377  1276 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 18:02:08.013   377  1276 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 18:02:08.018   377  1276 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,07-12 18:02:08.018   377  1276 D DrmWidevineDash: Service_Initialize: starts!
07-12 18:02:08.018   377  1276 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-12 18:02:08.018   377  1276 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 18:02:08.032  1804  4233 D LocationInitializer: Restart initialization of location
,07-12 18:02:08.052  4203  4218 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-12 18:02:08.054  1835  1958 W GCoreFlp: No location to return for getLastLocation()
,07-12 18:02:08.055  1488  4238 W FusedLocationProvider: location=null
,07-12 18:02:08.060  4219  4219 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 18:02:08.083  4219  4219 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 18:02:08.089  1488  2322 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 18:02:08.093  1488  1488 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 18:02:08.099  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:08.101  4219  4219 D WearableService: callingUid 10011, callindPid: 4219
,07-12 18:02:08.102  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-12 18:02:08.130  1835  2258 E MDM     : [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-12 18:02:08.131  1804  4242 D LocationInitializer: Restart initialization of location
,07-12 18:02:08.133  1835  2258 E MDM     : [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-12 18:02:08.137  4219  4241 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-12 18:02:08.154  1835  1958 W GCoreFlp: No location to return for getLastLocation()
07-12 18:02:08.155  1488  4244 W FusedLocationProvider: location=null
,07-12 18:02:08.229   377  1276 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 18:02:08.231   377  1276 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-12 18:02:08.232   377  1276 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2ad7000
07-12 18:02:08.232   377  1276 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2ad7000
,07-12 18:02:08.239   333   340 D DrmLibTime: got the req here! ret=0
,07-12 18:02:08.239   333   340 D DrmLibTime: command id, time_cmd_id = 770
07-12 18:02:08.239   333   340 D DrmLibTime: time_getutcsec starts!
07-12 18:02:08.239   333   340 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-12 18:02:08.239   333   340 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-12 18:02:08.239   333   340 D DrmLibTime: QSEE Time Listener: seconds: 1468339328
07-12 18:02:08.239   333   340 D DrmLibTime: QSEE Time Listener: nano seconds: 239814351
,07-12 18:02:08.239   333   340 D DrmLibTime: time_getutcsec returns 0, sec = 1468339328; nsec = 239814351
07-12 18:02:08.239   333   340 D DrmLibTime: time_getutcsec finished! 
07-12 18:02:08.239   333   340 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-12 18:02:08.240   333   340 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-12 18:02:08.248   377  1276 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-12 18:02:08.249   377  1276 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-12 18:02:08.250   377  1276 D DrmWidevineDash: hlos api version =  10
07-12 18:02:08.250   377  1276 D DrmWidevineDash: tz api version =  10
07-12 18:02:08.250   377  1276 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 18:02:08.250   377  1276 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-12 18:02:08.278   377  1276 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-12 18:02:08.279   377  1276 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 18:02:08.279   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2fc0134
,07-12 18:02:08.279   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-12 18:02:08.279   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-12 18:02:08.279   377  1276 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3ac21d8, dataLength=8
,07-12 18:02:08.280   377  1276 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-12 18:02:08.291   377  1276 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2a92c00, wrapped_rsa_key_length=1280
,07-12 18:02:08.295   377  1276 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-12 18:02:08.295   377  1276 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 18:02:08.296   377   377 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-12 18:02:08.296   377   377 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 18:02:08.296   377   377 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-12 18:02:08.296   377   377 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2b2fdc0, idLength=0xbecd800c
,07-12 18:02:08.316   377   377 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-12 18:02:08.316   377   377 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-12 18:02:08.317   377   377 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-12 18:02:08.317   377   377 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,07-12 18:02:08.317   377   377 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-12 18:02:08.317   377   377 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
07-12 18:02:08.318   377   377 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-12 18:02:08.318   377   377 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-12 18:02:08.320   377   377 D DrmWidevineDash: hlos api version =  10
,07-12 18:02:08.320   377   377 D DrmWidevineDash: tz api version =  10
07-12 18:02:08.320   377   377 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-12 18:02:08.320   377   377 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-12 18:02:08.321   377   377 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-12 18:02:08.321   377   377 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,07-12 18:02:08.321   377   377 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
07-12 18:02:08.322   377   377 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-12 18:02:08.322   377   377 D WVCdm   : PrepareKeyRequest: nonce=2538584617
07-12 18:02:08.323   377   377 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4887000
07-12 18:02:08.323   377   377 D DrmWidevineDash: message_length=1624, signature=0xb60b6d40, signature_length=3201138916
,07-12 18:02:08.443   377   377 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-12 18:02:08.444   377  1313 I WVCdm   : CdmEngine::CloseSession
,07-12 18:02:08.444   377  1313 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-12 18:02:08.445   377  1313 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-12 18:02:08.445   377  1313 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-12 18:02:08.446   377  1313 D DrmWidevineDash: Service_Uninitialize: starts!
07-12 18:02:08.446   377  1313 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-12 18:02:08.446   377  1313 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-12 18:02:08.446   377  1313 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-12 18:02:08.447   377  1313 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-12 18:02:08.672   377  1276 I WVCdm   : CdmEngine::OpenSession
07-12 18:02:08.672   377  1276 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 18:02:08.673   377  1276 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 18:02:08.674   377  1276 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
07-12 18:02:08.674   377  1276 D DrmWidevineDash: Service_Initialize: starts!
,07-12 18:02:08.674   377  1276 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-12 18:02:08.674   377  1276 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 18:02:09.106   377  1276 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 18:02:09.111   377  1276 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-12 18:02:09.112   377  1276 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2ad7000
07-12 18:02:09.112   377  1276 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2ad7000
,07-12 18:02:09.118   333   340 D DrmLibTime: got the req here! ret=0
,07-12 18:02:09.119   333   340 D DrmLibTime: command id, time_cmd_id = 770
07-12 18:02:09.119   333   340 D DrmLibTime: time_getutcsec starts!
,07-12 18:02:09.119   333   340 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-12 18:02:09.119   333   340 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-12 18:02:09.119   333   340 D DrmLibTime: QSEE Time Listener: seconds: 1468339329
07-12 18:02:09.119   333   340 D DrmLibTime: QSEE Time Listener: nano seconds: 119184595
,07-12 18:02:09.119   333   340 D DrmLibTime: time_getutcsec returns 0, sec = 1468339329; nsec = 119184595
07-12 18:02:09.119   333   340 D DrmLibTime: time_getutcsec finished! 
07-12 18:02:09.119   333   340 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-12 18:02:09.119   333   340 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-12 18:02:09.125   377  1276 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-12 18:02:09.127   377  1276 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-12 18:02:09.127   377  1276 D DrmWidevineDash: hlos api version =  10
07-12 18:02:09.127   377  1276 D DrmWidevineDash: tz api version =  10
,07-12 18:02:09.127   377  1276 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 18:02:09.128   377  1276 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-12 18:02:09.147   377  1276 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-12 18:02:09.147   377  1276 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 18:02:09.147   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2fc0134
07-12 18:02:09.147   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-12 18:02:09.147   377  1276 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-12 18:02:09.147   377  1276 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3ac2478, dataLength=8
,07-12 18:02:09.148   377  1276 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-12 18:02:09.148   377  1276 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2a92600, wrapped_rsa_key_length=1280
07-12 18:02:09.152   377  1276 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-12 18:02:09.152   377  1276 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 18:02:09.157   377  1312 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-12 18:02:09.157   377  1312 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 18:02:09.157   377  1312 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 18:02:09.157   377  1312 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2b2fdc0, idLength=0xb2ec0f2c
,07-12 18:02:09.169   377  1312 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-12 18:02:09.169   377  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-12 18:02:09.170   377  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-12 18:02:09.170   377  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-12 18:02:09.170   377  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-12 18:02:09.170   377  1312 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-12 18:02:09.171   377  1312 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-12 18:02:09.171   377  1312 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-12 18:02:09.171   377  1312 D DrmWidevineDash: hlos api version =  10
07-12 18:02:09.171   377  1312 D DrmWidevineDash: tz api version =  10
07-12 18:02:09.172   377  1312 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-12 18:02:09.172   377  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
07-12 18:02:09.172   377  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-12 18:02:09.173   377  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-12 18:02:09.173   377  1312 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
07-12 18:02:09.174   377  1312 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-12 18:02:09.174   377  1312 D WVCdm   : PrepareKeyRequest: nonce=681284512
,07-12 18:02:09.174   377  1312 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4888c00
07-12 18:02:09.174   377  1312 D DrmWidevineDash: message_length=1655, signature=0xb60b7240, signature_length=3001815044
,07-12 18:02:09.236   377  1312 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-12 18:02:09.237   377  1276 I WVCdm   : CdmEngine::CloseSession
07-12 18:02:09.237   377  1276 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-12 18:02:09.237   377  1276 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-12 18:02:09.237   377  1276 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-12 18:02:09.238   377  1276 D DrmWidevineDash: Service_Uninitialize: starts!
07-12 18:02:09.238   377  1276 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-12 18:02:09.238   377  1276 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-12 18:02:09.239   377  1276 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-12 18:02:09.246   377  1276 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-12 18:02:09.408  4251  4251 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 18:02:09.484  4251  4251 I dex2oat : dex2oat took 76.737ms (threads: 4) arena alloc=326KB java alloc=47KB native alloc=1661KB free=1666KB
,07-12 18:02:09.489  4203  4214 W System  : ClassLoader referenced unknown path: 
,07-12 18:02:09.509  4203  4214 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 18:02:09.509  4203  4214 I Adreno  : Build Date                       : 10/20/15
07-12 18:02:09.509  4203  4214 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 18:02:09.509  4203  4214 I Adreno  : Local Branch                     : M14
07-12 18:02:09.509  4203  4214 I Adreno  : Remote Branch                    : 
07-12 18:02:09.509  4203  4214 I Adreno  : Remote Branch                    : 
07-12 18:02:09.509  4203  4214 I Adreno  : Reconstruct Branch               : 
,07-12 18:02:09.593  4203  4214 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 18:02:09.593  4203  4214 I Adreno  : Build Date                       : 10/20/15
07-12 18:02:09.593  4203  4214 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 18:02:09.593  4203  4214 I Adreno  : Local Branch                     : M14
07-12 18:02:09.593  4203  4214 I Adreno  : Remote Branch                    : 
07-12 18:02:09.593  4203  4214 I Adreno  : Remote Branch                    : 
07-12 18:02:09.593  4203  4214 I Adreno  : Reconstruct Branch               : 
,07-12 18:02:09.717  1804  4196 I CheckinRequestBuilder: Classify the device as Phone.
,07-12 18:02:09.730  1804  4196 I EventLogService: Opted in for usage reporting
,07-12 18:02:10.006  1804  4196 W System.err: java.lang.Exception: Error converting session
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
,07-12 18:02:10.007  1804  4196 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-12 18:02:10.007  1804  4196 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
,07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
,07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
,07-12 18:02:10.008  1804  4196 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
07-12 18:02:10.008  1804  4196 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
07-12 18:02:10.008  1804  4196 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
,07-12 18:02:10.008  1804  4196 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 18:02:10.009  1804  4196 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:02:10.009  1804  4196 W System.err: Caused by: java.io.IOException: Invalid session data
07-12 18:02:10.009  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
,07-12 18:02:10.009  1804  4196 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
07-12 18:02:10.009  1804  4196 W System.err: 	... 25 more
,07-12 18:02:10.152  1804  4196 I CheckinTask: Sending checkin request (8832 bytes)
,07-12 18:02:10.807  1804  4196 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1
,07-12 18:02:10.811  1804  4196 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-12 18:02:10.904  1804  1810 E System  : Uncaught exception thrown by finalizer
,07-12 18:02:10.905  1804  1810 E System  : java.lang.NullPointerException: ssl_session == null
07-12 18:02:10.905  1804  1810 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-12 18:02:10.905  1804  1810 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-12 18:02:10.905  1804  1810 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-12 18:02:10.905  1804  1810 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-12 18:02:10.905  1804  1810 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-12 18:02:11.095  1488  4138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
07-12 18:02:11.096  1488  4138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
,07-12 18:02:11.096  1488  4138 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:02:11.097  1488  4138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:02:11.150  1804  4196 W CheckinRequestBuilder: awaiting user notification for token
,07-12 18:02:11.199  1804  4196 I CheckinRequestBuilder: Classify the device as Phone.
,07-12 18:02:11.216  1804  4196 I EventLogService: Opted in for usage reporting
,07-12 18:02:11.233  1804  4196 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-12 18:02:11.251  1804  4196 I CheckinService: Checking schedule, now: 1468339331251 next: 1468380474234
,07-12 18:02:11.252  1804  4196 I CheckinService: active receiver: disabled
,07-12 18:02:11.294  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 18:02:11.296  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-12 18:02:11.310  1488  2817 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-12 18:02:12.064   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1184063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE},
,07-12 18:02:13.161   875   885 I ActivityManager: Killing 3559:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-12 18:02:13.246   875  1786 I ActivityManager: Killing 3483:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-12 18:02:17.261   875  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 18:02:17.295   875  1690 I ActivityManager: Start proc 4265:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-12 18:02:17.341  4265  4265 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-12 18:02:17.381  1835  1835 V GmsNetworkLocationProvi: DISABLE
,07-12 18:02:17.385  4265  4265 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-12 18:02:17.389  1835  1835 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-12 18:02:17.420  1804  4284 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 18:02:17.426  1804  4284 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-12 18:02:17.434  1821  4286 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 18:02:17.460  1804  2147 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-12 18:02:17.478  4265  4281 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-12 18:02:17.481  1821  4286 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 47 ms] updated apps [took 47 ms] 
,07-12 18:02:17.773  4265  4281 D ContactDirectoryManager: Found com.google.contacts.gal.provider
07-12 18:02:17.773  4265  4281 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-12 18:02:17.807   875  1786 I ActivityManager: Start proc 4289:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,07-12 18:02:17.873  4289  4289 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-12 18:02:17.930   875  1707 I ActivityManager: Start proc 4301:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,07-12 18:02:17.961   875  1694 I ActivityManager: Start proc 4312:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,07-12 18:02:17.978   875  1743 I ActivityManager: Killing 3719:com.android.settings/1000 (adj 15): empty #17
,07-12 18:02:18.028   875  1379 I ActivityManager: Killing 3735:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,07-12 18:02:18.056  4301  4301 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-12 18:02:18.137  4301  4327 I Gmail   : getAccountsCursor
,07-12 18:02:18.183  4301  4328 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-12 18:02:18.195  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:18.239  4312  4312 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-12 18:02:18.314  4312  4312 I GoogleHttpClient: GMS http client unavailable, use old client
,07-12 18:02:18.335  4301  4301 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 18:02:18.350  4265  4281 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-12 18:02:18.383  4265  4281 I ContactDirectoryManager: Discovered 0 contact directories in 770ms
,07-12 18:02:18.467  4301  4342 E Gmail   : Error finding the version of the Email provider.....
07-12 18:02:18.467  4301  4342 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-12 18:02:18.467  4301  4342 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-12 18:02:18.467  4301  4342 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:02:18.468  4301  4342 W EmailMigration: We do not support migrating this version of the Email provider.
,07-12 18:02:18.492  4301  4344 I Gmail   : getAccountsCursor
,07-12 18:02:18.507  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:18.557  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:18.592   875  1389 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-12 18:02:18.617  4289  4289 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 18:02:18.636  4301  4350 I Gmail   : Observing account changes for notifications
,07-12 18:02:18.646  4289  4289 I Exchange: EasService.onCreate
,07-12 18:02:18.663  4289  4353 I Exchange: RestartPingTask
,07-12 18:02:18.681  4301  4349 I Gmail   : notifyAccountChanged
,07-12 18:02:18.684  4301  4340 I Gmail   : getAccountsCursor
,07-12 18:02:18.696  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:18.699  4301  4349 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 18:02:18.713  4301  4349 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 18:02:18.722  4289  4289 I Exchange: RestartPingsTask did not start any pings.
07-12 18:02:18.722  4289  4289 I Exchange: PSS stopIfIdle
,07-12 18:02:18.722  4289  4289 I Exchange: PSS has no active accounts; stopping service.
,07-12 18:02:18.724  4289  4289 I Exchange: onDestroy
,07-12 18:02:18.733  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 18:02:18.734  4301  4349 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
07-12 18:02:18.734  4301  4349 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-12 18:02:18.738  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:18.852  4301  4344 I Gmail   : getAccountsCursor
,07-12 18:02:18.863  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:02:22.372   875   885 I ActivityManager: Killing 3866:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,07-12 18:02:22.509   875  1707 I ActivityManager: Killing 3774:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,07-12 18:02:23.368  4301  4333 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 18:02:23.691  4289  4352 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 18:02:32.317   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1204317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 18:02:45.965   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 18:04:03.732  3913  4364 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 18:04:03.754  3913  4365 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 18:04:03.765  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:03.770  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:03.805  1488  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 18:04:03.805  1488  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 18:04:03.805  1488  1498 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-12 18:04:03.805  1488  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:03.831  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:03.833  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:03.854  1488  4138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 18:04:03.854  1488  4138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 18:04:03.854  1488  4138 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:04:03.854  1488  4138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:03.873  3913  4365 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 18:04:03.874  3913  4364 E BooksSync: Soft error
07-12 18:04:03.874  3913  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 18:04:03.874  3913  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 18:04:03.874  3913  4364 E BooksSync: Sync error
07-12 18:04:03.874  3913  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 18:04:03.874  3913  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 18:04:03.874  3913  4364 I BooksSync: Finished books sync
,07-12 18:04:03.888   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1295389, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 18:04:34.321  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:34.323  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:34.361  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 18:04:34.361  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 18:04:34.361  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:04:34.361  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:34.379  2864  4369 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 18:04:34.379  2864  4369 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jdm.a(PG:82)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jcs.o(PG:406)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jcn.a(PG:1379)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jcs.i(PG:143)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at blb.a(PG:3937)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at czp.a(PG:18188)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at czp.a(PG:9081)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at czq.run(PG:1686)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:04:34.379  2864  4369 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jdj.a(PG:4091)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jdj.a(PG:1125)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jdm.a(PG:77)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	... 12 more
07-12 18:04:34.379  2864  4369 E HttpOperation: Caused by: faj: BadAuthentication
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at fal.a(PG:38)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	at jdj.a(PG:4089)
07-12 18:04:34.379  2864  4369 E HttpOperation: 	... 14 more
,07-12 18:04:34.430  1488  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 18:04:34.430  1488  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 18:04:34.430  1488  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 18:04:34.430  1488  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:34.455  2864  4369 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 18:04:34.455  2864  4369 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jdm.a(PG:82)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jcs.o(PG:406)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jcn.a(PG:1379)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jcs.i(PG:143)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at hec.a(PG:42)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at hee.a(PG:102)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at czr.a(PG:65)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at kka.a(PG:108)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at czp.a(PG:19176)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at czp.a(PG:9081)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at czq.run(PG:1686)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:04:34.455  2864  4369 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jdj.a(PG:4091)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jdj.a(PG:1125)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jdm.a(PG:77)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	... 15 more
07-12 18:04:34.455  2864  4369 E HttpOperation: Caused by: faj: BadAuthentication
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at fal.a(PG:38)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	at jdj.a(PG:4089)
07-12 18:04:34.455  2864  4369 E HttpOperation: 	... 17 more
,07-12 18:04:34.455  2864  4369 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 18:04:34.455  2864  4369 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at hec.a(PG:42)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at hee.a(PG:102)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at czr.a(PG:65)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at kka.a(PG:108)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	... 15 more
07-12 18:04:34.455  2864  4369 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at fal.a(PG:38)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 18:04:34.455  2864  4369 E ExperimentLoader: 	... 17 more
,07-12 18:04:34.577   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1309456, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-12 18:05:04.756  2910  4373 V KeepSync: Connecting to GoogleApiClient
07-12 18:05:04.757   875  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 18:05:04.826  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:05:04.831  1488  1488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:05:04.893  1488  1500 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 18:05:04.893  1488  1500 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 18:05:04.893  1488  1500 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 18:05:04.894  1488  1500 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:05:04.928  1804  4374 V BaseAuthAsyncOperation: access token request failed
,07-12 18:05:04.930  2910  4373 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 18:05:04.992  1488  4138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 18:05:04.992  1488  4138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 18:05:04.992  1488  4138 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:05:04.992  1488  4138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:05:05.010  2910  4373 E KeepSync: IOException
07-12 18:05:05.010  2910  4373 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 18:05:05.010  2910  4373 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 18:05:05.010  2910  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 18:05:05.010  2910  4373 E KeepSync: 	... 10 more
,07-12 18:05:05.011  2910  4373 W KeepSync: Sync result 2
,07-12 18:05:05.028   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 1336040, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 18:06:13.531   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1425530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 18:06:35.090   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 18:07:13.371   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1485370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 18:07:27.304   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1499304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-12 18:08:45.341  4383  4383 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 18:08:45.345  4383  4383 D AndroidRuntime: CheckJNI is OFF
07-12 18:08:45.381  4383  4383 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 18:08:45.422  4383  4383 I Radio-JNI: register_android_hardware_Radio DONE
07-12 18:08:45.443  4383  4383 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 18:08:45.456   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 18:08:45.457   875   888 I ActivityManager: Killing 3660:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-12 18:08:45.528   875  1707 D GraphicsStats: Buffer count: 2
07-12 18:08:45.528   875  1305 D WifiService: Client connection lost with reason: 4
07-12 18:08:45.528   875  1694 I WindowState: WIN DEATH: Window{4cb0cd9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 18:08:45.588   875   898 W PackageSettings: Skipping PackageSetting{39df377 com.example.hello/10273} due to missing metadata
07-12 18:08:45.612   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 18:08:45.612   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 18:08:45.613   875   888 E ActivityManager: Failure starting process com.test.thalitest
07-12 18:08:45.613   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 18:08:45.613   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:45.613   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:45.613   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:45.613   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 18:08:45.613   875   888 I ActivityManager:   Force finishing activity ActivityRecord{ff0cc0 u0 com.test.thalitest/.MainActivity t10}
07-12 18:08:45.619   875   898 I art     : Starting a blocking GC Explicit
07-12 18:08:45.625   875  1389 W ActivityManager: Spurious death for ProcessRecord{71c0eb0 0:com.test.thalitest/u0a0}, curProc for 3660: null
07-12 18:08:45.679   875   898 I art     : Explicit concurrent mark sweep GC freed 41446(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 760us total 59.832ms
07-12 18:08:45.701   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 18:08:45.704  4383  4383 I art     : System.exit called, status: 0
07-12 18:08:45.704  4383  4383 I AndroidRuntime: VM exiting with result code 0.
07-12 18:08:45.762   875   898 I ActivityManager: Start proc 4394:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
07-12 18:08:45.763   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-12 18:08:45.786   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 18:08:45.790  4030  4030 D BluetoothMapAppObserver: onReceive
07-12 18:08:45.790  4030  4030 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-12 18:08:45.794  1650  1650 I Keyboard.Facilitator: resetDictionaries() : en_US
07-12 18:08:45.797   875  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 18:08:45.799  1835  2014 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 18:08:45.808  3506  3506 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-12 18:08:45.821  1650  4407 I Keyboard.Facilitator.DecoderInitializer: run()
07-12 18:08:45.822  1650  4407 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-12 18:08:45.822  1650  4407 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-12 18:08:45.823  1650  4407 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-12 18:08:45.823  1650  4407 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-12 18:08:45.823  1650  4407 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-12 18:08:45.823  1650  4407 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-12 18:08:45.826  1650  4407 I Decoder : createOrResetDecoder
07-12 18:08:45.831  1740  1740 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 18:08:45.842   875  1302 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-12 18:08:45.852  1488  1488 I ConfigService: onCreate
07-12 18:08:45.867   875   886 I ActivityManager: Start proc 4411:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-12 18:08:45.871  4265  4281 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
07-12 18:08:45.872  4265  4281 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-12 18:08:45.872  4265  4281 E AndroidRuntime: Process: android.process.acore, PID: 4265
07-12 18:08:45.872  4265  4281 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:45.872  4265  4281 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:45.871  4265  4412 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-12 18:08:45.880   875  4422 E DropBoxManagerService: Can't write: system_app_crash
07-12 18:08:45.880   875  4422 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:45.880   875  4422 E DropBoxManagerService: 	... 5 more
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-12 18:08:45.883  1488  4410 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:08:45.899   875  1694 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3660 uid 10000
07-12 18:08:45.899  1650  1650 I Keyboard.Facilitator: onFinishInput()
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-12 18:08:45.884  1488  4410 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-12 18:08:45.906  1488  4410 W SQLiteOpenHelper: Opened config.db in read-only mode
07-12 18:08:45.906   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 18:08:45.910  4265  4412 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
07-12 18:08:45.910  4265  4412 I Process : Sending signal. PID: 4265 SIG: 9
07-12 18:08:45.925  1650  4407 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-12 18:08:45.932  4411  4411 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-12 18:08:45.945  1756  1851 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-12 18:08:45.946   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-12 18:08:45.947   875   887 E PackageManager: Failed to write settings, restoring backup
07-12 18:08:45.947   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-12 18:08:45.947   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-12 18:08:45.947   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-12 18:08:45.947   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-12 18:08:45.947   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-12 18:08:45.947   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:45.947   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:45.947   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:45.954   875   888 E DropBoxManagerService: Can't write: system_server_wtf
07-12 18:08:45.954   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 18:08:45.954   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:45.954   875   888 E DropBoxManagerService: 	... 13 more
07-12 18:08:45.958  1650  4407 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-12 18:08:45.958   875  1743 I ActivityManager: Start proc 4428:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
07-12 18:08:45.959  1756  1851 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-12 18:08:45.959  1756  1851 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1756
07-12 18:08:45.959  1756  1851 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:45.959  1756  1851 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: Can't write: system_app_crash
07-12 18:08:45.961   875  4434 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:45.961   875  4434 E DropBoxManagerService: 	... 5 more
07-12 18:08:45.962   875   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-12 18:08:45.964   279   279 E lowmemorykiller: Error writing /proc/4265/oom_score_adj; errno=22
07-12 18:08:45.974  1756  1851 I Process : Sending signal. PID: 1756 SIG: 9
07-12 18:08:45.974   279   279 E lowmemorykiller: Error writing /proc/4265/oom_score_adj; errno=22
07-12 18:08:45.980  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-12 18:08:45.980  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-12 18:08:45.981  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-12 18:08:45.981  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-12 18:08:45.982  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-12 18:08:45.982  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-12 18:08:45.983  1650  4407 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-12 18:08:45.983  1650  4407 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-12 18:08:45.983  1650  4407 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-12 18:08:45.983  1650  4407 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-12 18:08:45.983  1650  4407 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-12 18:08:45.983  1650  4407 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-12 18:08:45.995   875  1379 I ActivityManager: Killing 3786:com.android.chrome/u0a40 (adj 15): empty #17
07-12 18:08:46.001  1488  1488 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-12 18:08:46.001  1488  1488 D AndroidRuntime: Shutting down VM
07-12 18:08:46.002  1488  1488 E AndroidRuntime: FATAL EXCEPTION: main
07-12 18:08:46.002  1488  1488 E AndroidRuntime: Process: com.google.process.gapps, PID: 1488
07-12 18:08:46.002  1488  1488 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-12 18:08:46.002  1488  1488 E AndroidRuntime: 	... 8 more
07-12 18:08:46.034   875  1707 D GraphicsStats: Buffer count: 1
07-12 18:08:46.034   875  1389 I WindowState: WIN DEATH: Window{e56425d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-12 18:08:46.050   875  1694 I ActivityManager: Process android.process.acore (pid 4265) has died
07-12 18:08:46.050   875  1694 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
07-12 18:08:46.050   875  4443 E DropBoxManagerService: Can't write: system_app_crash
07-12 18:08:46.050   875  4443 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:46.050   875  4443 E DropBoxManagerService: 	... 5 more
07-12 18:08:46.052   875  1707 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1756) has died
07-12 18:08:46.053   875  1707 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
07-12 18:08:46.054   875  1707 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-12 18:08:46.069   875   888 I ActivityManager: Start proc 4444:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-12 18:08:46.071  1488  1488 I Process : Sending signal. PID: 1488 SIG: 9
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 18:08:46.109  4444  4444 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 18:08:46.109  4444  4444 D AndroidRuntime: Shutting down VM
07-12 18:08:46.114  4444  4444 E AndroidRuntime: FATAL EXCEPTION: main
07-12 18:08:46.114  4444  4444 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4444
07-12 18:08:46.114  4444  4444 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-12 18:08:46.114  4444  4444 E AndroidRuntime: 	... 10 more
07-12 18:08:46.116   875  1379 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-12 18:08:46.116  4444  4444 I Process : Sending signal. PID: 4444 SIG: 9
07-12 18:08:46.117   875  4459 E DropBoxManagerService: Can't write: system_app_crash
07-12 18:08:46.117   875  4459 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:46.117   875  4459 E DropBoxManagerService: 	... 5 more
07-12 18:08:46.120   875  1305 D WifiService: Client connection lost with reason: 4
07-12 18:08:46.126   875   885 I ActivityManager: Process com.google.process.gapps (pid 1488) has died
07-12 18:08:46.126   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
07-12 18:08:46.126   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
07-12 18:08:46.126   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
07-12 18:08:46.139   875   888 I ActivityManager: Start proc 4460:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
07-12 18:08:46.143  1804  1804 W RocketImpressions: ClearcutLogger connection suspended: 1
07-12 18:08:46.144   875  1690 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4444) has died
07-12 18:08:46.146   875  1690 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-12 18:08:46.162   875   888 I ActivityManager: Start proc 4472:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
