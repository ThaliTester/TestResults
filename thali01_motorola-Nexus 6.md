#### Test 83268893a5a5a53_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 15:45:50.901  3766  3857 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
08-30 15:45:50.901   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 15:45:50.948  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 15:45:50.951  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 15:45:50.981  1519  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 15:45:50.981  1519  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 15:45:50.981  1519  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:45:50.981  1519  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 15:45:51.001  1720  3858 V BaseAuthAsyncOperation: access token request failed
08-30 15:45:51.002  3766  3857 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-30 15:45:51.058  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 15:45:51.058  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 15:45:51.059  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:45:51.059  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 15:45:51.076  3766  3857 E KeepSync: IOException
08-30 15:45:51.076  3766  3857 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 15:45:51.076  3766  3857 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 15:45:51.076  3766  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 15:45:51.076  3766  3857 E KeepSync: 	... 10 more
08-30 15:45:51.076  3766  3857 W KeepSync: Sync result 2
08-30 15:45:51.088   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 162455, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-30 15:45:51.611  3859  3859 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 15:45:51.615  3859  3859 D AndroidRuntime: CheckJNI is OFF
08-30 15:45:51.651  3859  3859 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 15:45:51.693  3859  3859 I Radio-JNI: register_android_hardware_Radio DONE
08-30 15:45:51.712  3859  3859 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 15:45:51.721   874  1942 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 15:45:51.790   874  1942 I ActivityManager: Start proc 3868:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 15:45:51.806  3859  3859 D AndroidRuntime: Shutting down VM
08-30 15:45:51.884  3868  3868 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 15:45:51.935  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 15:45:51.943  3868  3868 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 881-884)
08-30 15:45:51.943  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:45:51.958  3868  3868 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e8d58e4}
08-30 15:45:51.958  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:45:51.958  3868  3868 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:45:51.965  3868  3868 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 15:45:51.967  3868  3868 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 15:45:51.983  3868  3868 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 15:45:51.995  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 15:45:51.995  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 15:45:51.995  3868  3868 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 15:45:51.995  3868  3868 I Adreno  : Build Date                       : 10/20/15
08-30 15:45:51.995  3868  3868 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 15:45:51.995  3868  3868 I Adreno  : Local Branch                     : M14
08-30 15:45:51.995  3868  3868 I Adreno  : Remote Branch                    : 
08-30 15:45:51.995  3868  3868 I Adreno  : Remote Branch                    : 
08-30 15:45:51.995  3868  3868 I Adreno  : Reconstruct Branch               : 
,08-30 15:45:52.082   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9463c59:true
,08-30 15:45:52.123  3868  3868 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 15:45:52.137  3868  3868 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 15:45:52.219  3868  3907 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 15:45:52.237  3868  3893 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 15:45:52.271  3868  3907 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 15:45:52.286  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-30 15:45:52.342   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms (total +570ms)
,08-30 15:45:52.394  3868  3868 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3868
,08-30 15:45:52.459  3868  3868 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 15:45:52.630  3868  3908 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1677723344
,08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 15:45:52.640  3868  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f79f4b added. We now have 1 listener(s)
08-30 15:45:52.644  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 15:45:52.649  3868  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:45:52.652  3868  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:52.655  3868  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 15:45:52.659  3868  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb1dbe6 added. We now have 1 listener(s)
08-30 15:45:52.660  3868  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:52.666  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:45:52.666  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 15:45:52.666   874  1309 D WifiService: New client listening to asynchronous messages
,08-30 15:45:52.668  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 15:45:52.668  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 15:45:52.668  3868  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 15:45:52.673  3868  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:52.673  3868  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 15:45:52.692  3868  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:52.693  3868  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:45:52.693  3868  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 15:45:52.695  3868  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:45:52.698  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:52.699  3868  3908 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:45:52.707  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:52.754  3868  3868 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 15:45:53.429   874  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 15:45:53.913  3868  3915 W jxcore-log: Initializing JXcore engine
,08-30 15:45:53.913  3868  3915 W jxcore-log: JXcore engine is ready
,08-30 15:45:53.951  3915  3915 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 15:45:53.951  3915  3915 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10661]" dev="sockfs" ino=10661 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 15:45:53.951  3915  3915 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 15:45:53.951  3915  3915 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29866]" dev="sockfs" ino=29866 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 15:45:53.965  3868  3915 W jxcore-log: Starting JXcore engine
,08-30 15:45:54.046  3868  3915 W jxcore-log: Platform android
08-30 15:45:54.046  3868  3915 W jxcore-log: 
,08-30 15:45:54.047  3868  3915 W jxcore-log: Process ARCH arm
08-30 15:45:54.047  3868  3915 W jxcore-log: 
,08-30 15:45:54.241  3868  3915 I jxcore-log: JXcore Cordova bridge is ready!
08-30 15:45:54.241  3868  3915 I jxcore-log: 
,08-30 15:45:54.241  3868  3915 W jxcore-log: JXcore engine is started
,08-30 15:45:54.252  3868  3908 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 15:45:54.257  3868  3868 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 15:45:54.860   874   884 I ActivityManager: Start proc 3916:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-30 15:45:54.903  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 15:45:54.942  3916  3916 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 15:45:54.980  3916  3939 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:45:55.015  1519  2400 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 15:45:55.015  1519  2400 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 15:45:55.015  1519  2400 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 15:45:55.015  1519  2400 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 15:45:55.042  3916  3939 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 15:45:55.081  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:45:55.113  1519  2400 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 15:45:55.114  1519  2400 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 15:45:55.117  1519  2400 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 15:45:55.117  1519  2400 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:45:55.145  3522  3522 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 15:45:55.145  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 15:45:55.145  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 15:45:55.154   874  1385 I ActivityManager: Killing 2271:com.google.android.talk/u0a61 (adj 15): empty #17
,08-30 15:45:59.776   874  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=198717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 15:46:03.652  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 15:46:03.652  3868  3915 I jxcore-log: 
,08-30 15:46:03.655  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 15:46:03.655  3868  3915 I jxcore-log: 
,08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:03.667  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:46:03.674  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:46:03.681  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 15:46:03.681  3868  3915 I jxcore-log: 
,08-30 15:46:03.688  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 15:46:03.688  3868  3915 I jxcore-log: 
,08-30 15:46:04.231  3868  3915 D executeNativeTests: Running unit tests
,08-30 15:46:04.289  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:04.289  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b added. We now have 2 listener(s)
,08-30 15:46:04.290  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:04.291  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:04.291  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:04.291  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:04.291  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 added. We now have 2 listener(s)
08-30 15:46:04.291  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:04.292  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:46:04.298  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.307  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:46:04.325  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:46:04.326  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:46:04.332  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.334  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 15:46:04.337  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.339  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 15:46:04.339  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:46:04.340  3868  3915 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 15:46:04.341  3868  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:46:04.341  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:46:04.341  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:46:04.341  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 15:46:04.342  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.342  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.342  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:46:04.343  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.343  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.343  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:04.343  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 15:46:04.343  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b removed from the list
08-30 15:46:04.344  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.344  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 removed from the list
08-30 15:46:04.344  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.344  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.345  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.345  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.346  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.346  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.346  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.346  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.348  3868  3915 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 15:46:04.349  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.349  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.349  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.350  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.350  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.350  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.350  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.350  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.350  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.350  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.350  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.350  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.350  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.350  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.352  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.352  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.352  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.352  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:46:04.358  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:46:04.359  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:46:04.360  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.360  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.360  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.360  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.360  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.360  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.360  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.361  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.361  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.361  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.361  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.361  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.361  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.361  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.363  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.363  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.363  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.363  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.364  3868  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:46:04.367  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.375  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:04.378  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.379  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:04.379  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:46:04.379  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:46:04.379  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:46:04.379  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.379  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:46:04.382  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.383  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:46:04.383  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:46:04.388  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.388  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:46:04.390  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:46:04.391  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:46:04.393  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 15:46:04.399  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 15:46:04.399  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:46:04.399  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:46:04.400  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:46:04.400  3868  3915 D BluetoothAdapter: STATE_ON
08-30 15:46:04.405  2633  2645 D BtGatt.GattService: registerClient() - UUID=aae40931-dbe3-45f1-9d33-6dcd400ebe83
08-30 15:46:04.406  2633  2666 D BtGatt.GattService: onClientRegistered() - UUID=aae40931-dbe3-45f1-9d33-6dcd400ebe83, clientIf=5
08-30 15:46:04.407  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 15:46:04.408  2633  2735 D BtGatt.GattService: start scan with filters
08-30 15:46:04.413  2633  2671 D BtGatt.ScanManager: handling starting scan
08-30 15:46:04.413  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 15:46:04.414  2633  2671 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
08-30 15:46:04.414  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:46:04.418  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:46:04.418  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 15:46:04.423  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:04.424  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:04.424  2633  2666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:46:04.424  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.424  2633  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 15:46:04.425  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:46:04.427  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:46:04.439  3868  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:46:04.442  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.445  3868  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:46:04.445  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.445  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:46:04.445  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.445  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:46:04.445  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:46:04.446  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:46:04.446  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 15:46:04.446  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:46:04.447  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:04.447  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:46:04.449  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:46:04.449  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.449  2633  2671 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:46:04.450  2633  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:46:04.451  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:04.455  2633  2644 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:46:04.457  2633  2645 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 15:46:04.462  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:46:04.462  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:46:04.463  2633  2666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 15:46:04.464  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:04.462  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:46:04.465  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:04.465  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:46:04.469  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:04.469  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 15:46:04.469  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 15:46:04.469  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:46:04.470  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:04.470  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:46:04.471  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:46:04.471  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:04.471  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.471  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.471  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:04.471  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
,08-30 15:46:04.471  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.471  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.471  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:46:04.472  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.472  3868  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 15:46:04.474  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 15:46:04.474  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-30 15:46:04.474  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.479  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:46:04.480  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 15:46:04.480  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.480  2633  2671 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:46:04.481  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.481  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:04.482  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:46:04.482  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 15:46:04.482  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:46:04.482  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-30 15:46:04.482  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:46:04.484  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.485  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:46:04.485  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:46:04.486  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 15:46:04.486  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.486  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.486  2633  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:04.491  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:46:04.492  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:46:04.492  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:46:04.492  2633  2666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:04.492  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.497  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:46:04.497  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:46:04.497  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:46:04.498  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:04.500  2633  2644 D BtGatt.GattService: registerClient() - UUID=7e8c917d-9a6b-473c-b631-28c429f135d9
,08-30 15:46:04.500  2633  2666 D BtGatt.GattService: onClientRegistered() - UUID=7e8c917d-9a6b-473c-b631-28c429f135d9, clientIf=5
,08-30 15:46:04.501  3868  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:46:04.501  2633  2735 D BtGatt.GattService: start scan with filters
,08-30 15:46:04.503  2633  2671 D BtGatt.ScanManager: handling starting scan
08-30 15:46:04.503  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:46:04.504  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 15:46:04.504  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:46:04.504  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:46:04.506  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:04.506  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:46:04.506  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:04.508  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 15:46:04.509  2633  2666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:46:04.509  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.509  2633  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 15:46:04.510  3868  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:46:04.512  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.512  3868  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:46:04.512  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.512  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:46:04.512  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.512  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 15:46:04.512  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:46:04.513  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 15:46:04.513  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 15:46:04.513  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 15:46:04.513  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:04.513  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:46:04.514  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 15:46:04.514  3868  3915 D BluetoothAdapter: STATE_ON
08-30 15:46:04.514  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:04.514  2633  2671 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:46:04.514  2633  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-30 15:46:04.514  2633  2644 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:46:04.514  2633  2645 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:46:04.515  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 15:46:04.515  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:46:04.515  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 15:46:04.515  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:04.515  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-30 15:46:04.516  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 15:46:04.516  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:46:04.516  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 15:46:04.516  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:46:04.517  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:04.517  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.517  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.517  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:04.517  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:04.517  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.517  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:04.518  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.518  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:04.518  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.518  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:46:04.518  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.518  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.518  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.519  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.519  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.519  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.519  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.520  3868  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 15:46:04.521  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.522  2633  2666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:46:04.522  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.526  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:04.527  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 15:46:04.527  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:04.528  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:46:04.528  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:04.528  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:46:04.528  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:46:04.528  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:46:04.528  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.528  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:46:04.530  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.532  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:46:04.532  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:46:04.532  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.533  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:46:04.533  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.534  2633  2671 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:46:04.536  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:46:04.536  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:46:04.536  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:46:04.540  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 15:46:04.540  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.540  2633  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:04.541  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:46:04.541  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 15:46:04.541  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:46:04.542  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:04.544  2633  2644 D BtGatt.GattService: registerClient() - UUID=5d5bc6ff-5a17-45c9-b80f-cacd8ff78033
,08-30 15:46:04.545  2633  2666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:04.545  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.545  2633  2666 D BtGatt.GattService: onClientRegistered() - UUID=5d5bc6ff-5a17-45c9-b80f-cacd8ff78033, clientIf=5
08-30 15:46:04.545  3868  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 15:46:04.545  2633  2645 D BtGatt.GattService: start scan with filters
,08-30 15:46:04.548  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:46:04.548  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:46:04.548  2633  2671 D BtGatt.ScanManager: handling starting scan
08-30 15:46:04.548  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:46:04.548  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:46:04.550  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:04.550  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:46:04.551  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:46:04.552  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:46:04.554  2633  2666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:46:04.554  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.554  2633  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:46:04.554  3868  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:46:04.554  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.555  3868  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:46:04.555  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.555  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:46:04.555  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.555  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:46:04.555  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:46:04.555  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 15:46:04.555  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:46:04.555  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:46:04.555  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:04.555  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:46:04.556  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:04.557  2633  2644 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:46:04.557  2633  2735 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:46:04.558  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:46:04.558  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:46:04.558  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:46:04.558  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:04.558  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:46:04.559  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:46:04.559  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.559  2633  2671 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:46:04.559  2633  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 15:46:04.559  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:04.559  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:46:04.559  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:46:04.559  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:46:04.560  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:04.561  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:46:04.561  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:04.561  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:04.562  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.562  3868  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:46:04.562  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.562  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:46:04.562  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.562  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.562  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:04.563  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.563  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.563  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.563  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.563  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.563  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.563  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.564  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.564  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:04.564  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.564  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.565  3868  3915 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 15:46:04.565  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:04.566  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.566  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.566  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.566  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.566  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.566  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.566  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.566  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.566  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.566  2633  2666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:46:04.566  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.566  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.566  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.567  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.567  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.567  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.567  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.567  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.567  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.568  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:46:04.568  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.569  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.569  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.569  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.569  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.569  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.569  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.569  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.569  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.569  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.569  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.569  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.569  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.569  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.570  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.570  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.570  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.570  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.571  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:46:04.571  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.571  3868  3915 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 15:46:04.571  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.571  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.571  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.571  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.572  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.572  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.572  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.572  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.572  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.572  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.572  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.572  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.572  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.572  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.573  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.573  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:04.573  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.573  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.573  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 15:46:04.574  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.574  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.574  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.574  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.574  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 15:46:04.574  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.574  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.574  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.574  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.574  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.574  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.575  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.575  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.575  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.576  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.576  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.576  2633  2666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:46:04.576  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.576  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.576  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.576  2633  2671 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:46:04.576  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:46:04.576  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:46:04.577  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:46:04.577  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:46:04.577  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:46:04.577  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:46:04.577  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.577  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.577  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.577  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.578  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.578  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.578  3868  391,5 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.578  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.578  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.578  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.578  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.578  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.578  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.578  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.579  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.579  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.579  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.579  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.580  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:46:04.581  3868  3915 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:46:04.581  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:46:04.582  2633  2666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:46:04.582  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.582  2633  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:04.584  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:46:04.584  3868  3915 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 15:46:04.584  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:46:04.584  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:46:04.584  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:46:04.585  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:46:04.586  2633  2666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:46:04.586  2633  2666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:46:04.586  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:46:04.587  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:46:04.587  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:46:04.587  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 15:46:04.587  3868  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:46:04.587  3868  3915 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 15:46:04.587  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:46:04.587  3868  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:46:04.587  3868  3915 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 15:46:04.587  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:46:04.587  3868  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 15:46:04.588  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 15:46:04.591  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 15:46:04.591  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 15:46:04.591  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 15:46:04.592  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 15:46:04.592  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 15:46:04.592  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 15:46:04.592  3868  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:46:04.592  3868  3915 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 15:46:04.592  3868  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
,08-30 15:46:04.593  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:04.593  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.593  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:46:04.593  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.593  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.593  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.593  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 15:46:04.594  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list,
08-30 15:46:04.594  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.594  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.594  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.594  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.594  3868  3940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:04.594  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.594  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.594  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.594  3868  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-30 15:46:04.594  3868  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-30 15:46:04.594  3868  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
08-30 15:46:04.595  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.595  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:04.595  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.595  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.596  3868  3915 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-30 15:46:04.596  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.596  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.596  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.596  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.596  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.596  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.596  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.597  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.597  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.597  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:46:04.597  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.597  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.597  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.597  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.597  3868  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-30 15:46:04.597  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.598  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.598  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.598  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.598  3868  3915 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 15:46:04.598  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.598  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 15:46:04.598  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.599  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.599  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.599  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.599  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
,08-30 15:46:04.599  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.599  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.599  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.599  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.599  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.599  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.599  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.600  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.600  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.600  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.600  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.600  3868  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 15:46:04.600  3868  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 15:46:04.601  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:46:04.601  3868  3915 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-30 15:46:04.601  3868  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:46:04.601  3868  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 15:46:04.601  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 15:46:04.601  3868  3915 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 15:46:04.601  3868  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:46:04.601  3868  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:46:04.601  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 15:46:04.601  3868  3915 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 15:46:04.601  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.601  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 15:46:04.601  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.601  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.601  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.601  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.602  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
,08-30 15:46:04.602  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.602  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.602  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:46:04.602  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.602  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.602  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.602  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.602  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:04.603  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.603  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.603  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.603  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.603  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.603  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.603  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.603  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.603  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.603  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.603  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.603  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.603  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.604  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.604  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.604  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.604  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.604  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.604  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:04.604  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.604  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.604  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.604  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.604  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.604  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.604  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.604  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.604  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.604  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.604  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.604  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.604  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.606  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.606  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.606  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.606  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.607  3868  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 15:46:04.607  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.608  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 15:46:04.608  3868  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 15:46:04.608  3868  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:46:04.609  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 15:46:04.609  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
,08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.609  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 15:46:04.609  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:46:04.609  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.609  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.610  3868  3942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:04.610  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:04.610  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.611  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.611  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.611  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:46:04.611  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.611  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:04.611  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.611  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.611  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:04.611  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.611  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.611  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.611  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.611  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.611  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.611  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.611  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.611  3868  3942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 15:46:04.611  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.611  3868  3942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 15:46:04.611  3868  3942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 15:46:04.612  3868  3868 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 15:46:04.612  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.612  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.612  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.612  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.613  3868  3915 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 15:46:04.613  3868  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:46:04.613  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:46:04.615  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:46:04.615  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:04.615  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.615  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.615  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.615  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.615  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.615  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.615  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.615  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.615  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.615  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.615  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.615  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.616  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:04.616  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.616  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:04.616  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.617  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.619  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:04.619  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.619  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.619  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:04.619  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.619  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.619  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.619  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.619  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.619  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.619  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.619  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.619  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.619  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.620  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.620  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:04.620  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.620  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
,08-30 15:46:04.621  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:04.621  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:04.621  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:04.621  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:04.621  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:04.621  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.621  3868  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b8d5b not in the list
08-30 15:46:04.621  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:04.621  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.621  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:04.621  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.621  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.621  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:04.621  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:04.622  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:04.622  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 15:46:04.622  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:04.622  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f19f8 not in the list
08-30 15:46:04.623  3868  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-30 15:46:04.623  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
08-30 15:46:04.623  3868  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 15:46:04.623  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:46:04.623  3868  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 15:46:04.623  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:46:04.624  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 15:46:04.624  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 15:46:04.625  3868  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 15:46:04.625  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 15:46:04.625  3868  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-30 15:46:04.625  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 15:46:04.625  3868  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 15:46:04.625  3868  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 15:46:04.625  3868  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 15:46:04.625  3868  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 15:46:04.626  3868  3915 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-30 15:46:04.626  3868  3915 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 15:46:04.626  3868  3915 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 15:46:04.626  3868  3915 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 15:46:04.627  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:04.627  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3124c1a added. We now have 2 listener(s)
,08-30 15:46:04.627  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:04.628  3868  3915 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 15:46:04.628   874  1996 D WifiService: setWifiEnabled: true pid=3868, uid=10000
08-30 15:46:04.628   874  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:46:04.629  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:04.629  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@816834b added. We now have 3 listener(s)
,08-30 15:46:04.629  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:04.632  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:04.632  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@498f128 added. We now have 4 listener(s)
08-30 15:46:04.632  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:04.633  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:04.633  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b890e41 added. We now have 5 listener(s)
08-30 15:46:04.633  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:04.634   874  1994 D WifiService: setWifiEnabled: false pid=3868, uid=10000
08-30 15:46:04.634   874  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:46:04.637  2633  2661 D BluetoothAdapterState: Current state: ON, message: 23
08-30 15:46:04.637  2633  2661 D BluetoothAdapterProperties: Setting state to 13
08-30 15:46:04.637  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:04.637  2633  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 15:46:04.637  2633  2661 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:46:04.638  2633  2661 I BluetoothAdapterState: Entering PendingCommandState
08-30 15:46:04.638  2633  2666 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:46:04.639  2633  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 15:46:04.641  2633  2633 D BluetoothMapService: onReceive
,08-30 15:46:04.641  2633  2633 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:46:04.641  2633  2633 D BluetoothMapService: STATE_TURNING_OFF
,08-30 15:46:04.641  2633  2633 D BluetoothMapService: MAP Service closeService in
,08-30 15:46:04.641  2633  2633 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 15:46:04.641  2633  2633 D ObexServerSockets0: shutdown(block = true)
08-30 15:46:04.642  2633  2633 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:46:04.642  2633  2777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 15:46:04.642  2633  2633 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 15:46:04.642  2633  2778 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 15:46:04.642  2633  2732 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 15:46:04.642  2633  2633 I BtOppRfcommListener: stopping Accept Thread
08-30 15:46:04.642  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.642  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:04.642  2633  3426 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 15:46:04.643  2633  3426 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:46:04.643  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.643  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.643  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:04.646  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.649  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.650  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:46:04.652   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 15:46:04.652   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 15:46:04.652   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 15:46:04.652   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:04.653  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:04.653  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:04.654  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.654  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:04.656   874   887 I ActivityManager: Start proc 3946:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 15:46:04.658  2633  2633 D HeadsetService: Received stop request...Stopping profile...
08-30 15:46:04.660  1945  2374 D BluetoothHeadset: Proxy object disconnected
,08-30 15:46:04.660   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:04.660   874  1308 E native  : do suspend true
08-30 15:46:04.662   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:04.660  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.663  1366  1379 D BluetoothHeadset: Proxy object disconnected
,08-30 15:46:04.663   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:04.665  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.665  2633  2633 D A2dpService: Received stop request...Stopping profile...
08-30 15:46:04.665  2633  2758 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:46:04.666   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 15:46:04.667  2633  2633 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:04.667  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.667  2633  2633 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:46:04.667  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.668  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:04.668  2633  2633 D HidService: Received stop request...Stopping profile...
08-30 15:46:04.668  2633  2633 D HidService: Stopping Bluetooth HidService
08-30 15:46:04.670  2633  2633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:46:04.670  2633  2633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:46:04.671  2633  2666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 15:46:04.671  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:46:04.671  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:04.671  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:46:04.671  2633  2666 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 15:46:04.672   874  1871 D DhcpClient: Clearing IP address
08-30 15:46:04.673   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:46:04.674  2633  2633 D HealthService: Received stop request...Stopping profile...
,08-30 15:46:04.675  2633  2633 D PanService: Received stop request...Stopping profile...
,08-30 15:46:04.676   372   872 D CommandListener: Setting iface cfg
,08-30 15:46:04.677  2633  2633 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:46:04.677  2633  2633 D BluetoothMapService: stop()
08-30 15:46:04.677  2633  2633 D BluetoothMapAppObserver: deinitObservers()
08-30 15:46:04.677  2633  2633 D BluetoothMapAppObserver: removeReceiver()
08-30 15:46:04.678  2633  2633 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:04.678  2633  2633 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:04.678  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.678  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:04.679  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:46:04.679  2633  2666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 15:46:04.679  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:04.680  2633  2722 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:46:04.680  2633  2722 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:46:04.680  2633  2722 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:46:04.680  2633  2722 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:46:04.680  2633  2633 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:04.680  2633  2633 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:04.680  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.680  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:04.680  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-30 15:46:04.680  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-30 15:46:04.680  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-30 15:46:04.681  1366  1366 D HidProfile: Bluetooth service disconnected
08-30 15:46:04.681  2633  2633 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:46:04.681  2633  2666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:46:04.681  2633  2633 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 15:46:04.681  2633  2633 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:04.681  2633  2633 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:04.681  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.682  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:04.682  2633  2633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:46:04.682  2633  2666 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 15:46:04.682  2633  2633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:46:04.683   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 15:46:04.683  2633  2633 V BluetoothAdapterState: isTurningOff()=true
,08-30 15:46:04.683   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:46:04.683   874  1308 E native  : do suspend true
08-30 15:46:04.683  2633  2633 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:04.683  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.683  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:04.685   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:46:04.686   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 15:46:04.686  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:46:04.686  1366  1366 D PanProfile: Bluetooth service disconnected
08-30 15:46:04.686   395   395 E Parcel  : Reading a NULL string not supported here.
08-30 15:46:04.686  1366  1366 D BluetoothMap: Proxy object disconnected
,08-30 15:46:04.686  1366  1366 D MapProfile: Bluetooth service disconnected
08-30 15:46:04.688  2633  2633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:46:04.688  2633  2633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:46:04.689  2633  2633 D BluetoothMapService: MAP Service closeService in
08-30 15:46:04.690  2633  2633 V BluetoothAdapterState: isTurningOff()=true
,08-30 15:46:04.690  2633  2633 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:46:04.690  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:04.690  2633  2633 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:04.690   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 15:46:04.695  2633  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 15:46:04.695  2633  2661 D BluetoothAdapterProperties: Setting state to 15
08-30 15:46:04.695  2633  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 15:46:04.696  2633  2661 I BluetoothAdapterState: Entering BleOnState
,08-30 15:46:04.696   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:04.696  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:04.696  1945  1959 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:04.696  2633  2633 D BluetoothMapService: cleanup()
08-30 15:46:04.697  2633  2633 D BluetoothMapService: MAP Service closeService in
08-30 15:46:04.697  1366  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:46:04.698   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:04.698  1366  2232 D BluetoothPan: onBluetoothStateChange on: false
,08-30 15:46:04.699   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:04.699   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:46:04.699  1366  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:46:04.699  1366  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:46:04.700  1366  2232 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:46:04.701  2633  2661 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 15:46:04.701  2633  2661 D BluetoothAdapterProperties: Setting state to 16
08-30 15:46:04.701  2633  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 15:46:04.701  2633  2661 D BluetoothAdapterProperties: onBleDisable
08-30 15:46:04.701  2633  2661 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:04.701  2633  2662 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 15:46:04.702  1519  2559 V NativeCrypto: Read error: ssl=0x9a63e800: I/O error during system call, Connection timed out
08-30 15:46:04.702  2633  2722 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 15:46:04.703  2633  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:04.704  2633  2666 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:46:04.705   874  1887 D DhcpClient: Receive thread stopped
08-30 15:46:04.711  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:04.711  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:04.711  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:04.712  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:04.713  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:04.713  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:04.714  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.714  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:04.715  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.716  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.720  1519  2559 V NativeCrypto: SSL shutdown failed: ssl=0x9a63e800: I/O error during system call, Broken pipe
,08-30 15:46:04.725   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:04.734  3946  3946 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 15:46:04.742  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:46:04.745   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:04.746   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:46:04.746   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 15:46:04.746   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:04.749   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:46:04.749  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:46:04.750   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:46:04.754  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:04.757  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:04.758   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1cc38d:true
,08-30 15:46:04.767   874  1956 I ActivityManager: Start proc 3963:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 15:46:04.769   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 15:46:04.771  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.771   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:04.771  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:04.772  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.772  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:04.774  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.775  2028  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:04.775  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:04.775  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:04.776  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:04.783  3946  3946 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 15:46:04.784  3946  3946 D BluetoothMap: Create BluetoothMap proxy object
,08-30 15:46:04.790  3946  3946 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 15:46:04.802  3963  3963 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 15:46:04.805  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:46:04.809   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-30 15:46:04.810   874  2259 I ActivityManager: Killing 3231:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-30 15:46:04.903  2633  2666 I bt_hci  : shut_down
,08-30 15:46:04.904  2633  2673 D bt_hwcfg: hw_epilog_process
,08-30 15:46:04.915  2633  2673 I bt_vendor: low_power_mode_cb
,08-30 15:46:04.946  2633  2673 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 15:46:04.946  2633  2673 I bt_vendor: epilog_cb
08-30 15:46:04.946  2633  2673 I bt_hci  : epilog_finished_callback
,08-30 15:46:04.952  2633  2666 I bt_hci_h4: hal_close
,08-30 15:46:04.953  2633  2666 I bt_userial_vendor: device fd = 51 close
,08-30 15:46:04.995  3963  3963 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48),
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.995  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:04.996  3963  3963 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:04.996  3963  3963 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:05.001  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 15:46:05.009  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:05.009  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:46:05.015   874  1951 I ActivityManager: Killing 3582:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 15:46:05.074  2633  2662 D bt_stack_manager: event_shut_down_stack finished.
,08-30 15:46:05.076  2633  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 15:46:05.100   874  1996 I ActivityManager: Start proc 3997:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-30 15:46:05.103  2633  2633 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:46:05.104  2633  2661 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 15:46:05.105  2633  2633 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:46:05.105  2633  2633 D BtGatt.GattService: stop()
,08-30 15:46:05.105  2633  2633 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 15:46:05.107  2633  2633 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:05.107  2633  2633 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:05.107  2633  2633 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:05.108  2633  2633 V BluetoothAdapterState: isBleTurningOff()=true
08-30 15:46:05.108  2633  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 15:46:05.108  2633  2661 D BluetoothAdapterProperties: Setting state to 10
08-30 15:46:05.109  2633  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 15:46:05.109  2633  2661 I BluetoothAdapterState: Entering OffState
,08-30 15:46:05.111   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 15:46:05.111  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:46:05.121  2633  2633 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 15:46:05.121  2633  2633 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 15:46:05.121  2633  2662 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 15:46:05.121  2633  2633 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 15:46:05.124  2633  2662 D bt_stack_manager: event_clean_up_stack finished.
,08-30 15:46:05.129  2633  2633 I art     : System.exit called, status: 0
,08-30 15:46:05.130  2633  2633 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:46:05.163  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-30 15:46:05.194   874  1942 I ActivityManager: Process com.android.bluetooth (pid 2633) has died
,08-30 15:46:05.426  3997  4017 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 15:46:05.426  3997  4017 I Babel_SMS: MmsConfig.loadMmsSettings
08-30 15:46:05.427  3997  4017 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-30 15:46:05.427  3997  4017 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 15:46:05.470  3997  4017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-30 15:46:05.470  3997  4017 I Babel_SMS: MmsConfig.loadFromResources
,08-30 15:46:05.471  3997  4017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 15:46:05.472  3997  4017 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-30 15:46:05.515  3997  3997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:46:05.518  3997  3997 I Babel_Crash: startup - clean
,08-30 15:46:05.557  3997  3997 I Babel_telephony: TeleModule.launchCompleted
,08-30 15:46:05.573   874   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 15:46:05.583  3997  3997 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-30 15:46:05.591  3997  3997 W Babel   : BAM#gBA: invalid account id: -1
,08-30 15:46:05.592  3997  3997 W Babel   : BAM#gBA: invalid account id: -1
,08-30 15:46:05.598  3997  3997 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-30 15:46:05.601  3997  4023 I Babel   : deleted: false for 0
,08-30 15:46:05.609   874  1427 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 15:46:05.643  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 15:46:05.649  1720  1720 D SystemUpdateService: onCreate
,08-30 15:46:05.665  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:46:05.680  1720  4025 I SystemUpdateService: active receiver: enabled
,08-30 15:46:05.692  1720  4025 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:46:05.693  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 15:46:05.695  1720  2450 I iu.UploadsManager: num queued entries: 0
,08-30 15:46:05.695  1720  2450 I iu.UploadsManager: num updated entries: 0
,08-30 15:46:05.698  1720  2450 I iu.SyncManager: NEXT; no task
,08-30 15:46:05.699  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:46:05.702  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:46:05.716  1720  4025 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 15:46:05.716  1720  4025 I SystemUpdateService: now status is 0 (complete)
08-30 15:46:05.717  1720  4025 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 15:46:05.718  1720  4025 I SystemUpdateService: file has been verified
08-30 15:46:05.719   874  1942 I ActivityManager: Start proc 4027:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 15:46:05.721  3997  3997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:46:05.723  1720  4025 I SystemUpdateService: OTA package size = 12249756
,08-30 15:46:05.728  1720  4025 I SystemUpdateService: showing system update notification
,08-30 15:46:05.739  1720  1720 D SystemUpdateService: onDestroy
,08-30 15:46:05.773  4027  4027 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 15:46:05.782  4027  4027 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:05.790  3997  3997 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 15:46:05.795  4027  4027 D SprintDMHelper: simOperator: 
,08-30 15:46:05.795  4027  4027 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:46:05.802  3997  3997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:46:05.804  3997  3997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:46:05.817  3997  3997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:46:05.820  3963  3988 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 15:46:05.824  3997  3997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:46:05.833   874  1427 I ActivityManager: Start proc 4039:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 15:46:05.838   874  1427 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 15:46:05.882   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5195a1:true
,08-30 15:46:05.888  3997  3997 I vclib   : onServiceConnected
,08-30 15:46:05.997   874  1996 I ActivityManager: Start proc 4054:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 15:46:06.000  3997  4053 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 15:46:06.019   874   884 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-30 15:46:06.039  4054  4054 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 15:46:06.143  4054  4054 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 15:46:06.143  4054  4054 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 15:46:06.143  4054  4054 I GAv4    :   adb logcat -s GAv4
,08-30 15:46:06.159  4054  4054 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:46:06.167  4054  4054 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:46:06.200  4054  4071 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:46:06.302  4054  4054 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 15:46:06.338  4054  4054 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 15:46:06.352  4054  4054 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5289-5293)
,08-30 15:46:06.354  4054  4054 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 15:46:06.367  4054  4054 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6f2e058}
,08-30 15:46:06.369  4054  4054 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:46:06.369  4054  4054 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 15:46:06.377  4054  4054 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 15:46:06.379  4054  4054 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 15:46:06.395  4054  4054 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 15:46:06.407  4054  4054 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 15:46:06.407  4054  4054 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 15:46:06.407  4054  4054 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 15:46:06.407  4054  4054 I Adreno  : Build Date                       : 10/20/15
08-30 15:46:06.407  4054  4054 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 15:46:06.407  4054  4054 I Adreno  : Local Branch                     : M14
08-30 15:46:06.407  4054  4054 I Adreno  : Remote Branch                    : 
08-30 15:46:06.407  4054  4054 I Adreno  : Remote Branch                    : 
08-30 15:46:06.407  4054  4054 I Adreno  : Reconstruct Branch               : 
,08-30 15:46:06.471  4054  4054 I NSApplication: Starting up...
,08-30 15:46:06.486  4054  4100 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 15:46:06.520   874  1713 I ActivityManager: Start proc 4105:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-30 15:46:06.521   874  1713 I ActivityManager: Killing 3657:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 15:46:06.634  4105  4105 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 15:46:06.826   874  2259 I ActivityManager: Killing 3672:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 15:46:07.646   874  2259 D WifiService: setWifiEnabled: true pid=3868, uid=10000
,08-30 15:46:07.647   874  2259 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:46:07.669   874  1308 D WifiConfigStore: Loading config and enabling all networks 
08-30 15:46:07.670  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:07.671  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:07.671  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:07.671  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:07.675  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:07.675  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:07.676  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:07.676  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:07.700   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-30 15:46:07.701   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 15:46:07.702   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 15:46:07.703   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:46:07.703   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 15:46:07.703   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 15:46:07.703   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 15:46:07.722   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 15:46:07.723   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:46:07.725   372   872 D CommandListener: Setting iface cfg
,08-30 15:46:07.726   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 15:46:07.726   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 15:46:07.739   874  1308 E native  : do suspend true
,08-30 15:46:07.739   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 15:46:07.746   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 15:46:07.770   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:46:09.133   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:46:09.205   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.06 rxSuccessRate=9.50 delta 1000 -> 994
,08-30 15:46:09.207   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 15:46:09.207   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:09.227   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 15:46:09.281   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 15:46:09.284  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 15:46:09.741  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:46:09.791  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 15:46:09.793  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 15:46:09.797   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:46:09.805   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:46:09.805   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:09.805   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 15:46:09.821   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:09.831   372   872 D CommandListener: Setting iface cfg
08-30 15:46:09.832   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 15:46:09.839   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 15:46:09.864   874  4132 D DhcpClient: Receive thread started
,08-30 15:46:09.948   874  1308 E native  : do suspend false
,08-30 15:46:09.965   874  1871 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 15:46:09.986   874  4132 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172614, domain null
,08-30 15:46:09.987   874  1871 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172614 seconds
,08-30 15:46:09.990   874  1871 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 15:46:10.004   874  4132 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 15:46:10.005   874  1871 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 15:46:10.010   372   872 D CommandListener: Setting iface cfg
,08-30 15:46:10.020   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 15:46:10.021   874  1871 D DhcpClient: Scheduling renewal in 86399s
08-30 15:46:10.024   874  1308 E native  : do suspend true
,08-30 15:46:10.049   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 15:46:10.052   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 15:46:10.053   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 15:46:10.056   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 15:46:10.064   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:46:10.118   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 15:46:10.118   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 15:46:10.119   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
,08-30 15:46:10.120   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 15:46:10.121   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 15:46:10.129   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 15:46:10.137   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 15:46:10.137   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 15:46:10.138   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 15:46:10.139   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:46:10.139   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 15:46:10.139   874  1310 D ConnectivityService:    accepting network in place of null
,08-30 15:46:10.142   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:46:10.178   874  4130 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209119, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 15:46:10.183   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:10.231   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:10.239   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 15:46:10.239   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:10.243   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 15:46:10.248   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 15:46:10.250   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:46:10.255  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:10.255  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:10.255  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:10.255  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:10.258  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:10.258  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:46:10.258  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:10.258  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:10.263  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 15:46:10.265  1720  1720 D SystemUpdateService: onCreate
,08-30 15:46:10.269  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:46:10.278  1720  4142 I SystemUpdateService: active receiver: enabled
,08-30 15:46:10.285  1720  4142 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:46:10.287  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 15:46:10.288  1720  4142 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 15:46:10.289  1720  4142 I SystemUpdateService: now status is 0 (complete)
,08-30 15:46:10.289  1720  4142 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 15:46:10.289  1720  4142 I SystemUpdateService: file has been verified
08-30 15:46:10.289  1720  4142 I SystemUpdateService: OTA package size = 12249756
,08-30 15:46:10.295  1720  4142 I SystemUpdateService: showing system update notification
08-30 15:46:10.297  1720  4145 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 15:46:10.297  1720  4145 W BaseAppContext: Using Auth Proxy for data requests.
08-30 15:46:10.298  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 15:46:10.299  1720  4145 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:46:10.299  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 15:46:10.300  1720  2450 I iu.UploadsManager: num queued entries: 0
08-30 15:46:10.300  1720  2450 I iu.UploadsManager: num updated entries: 0
,08-30 15:46:10.301  4027  4027 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:46:10.302  1720  2450 I iu.SyncManager: NEXT; no task
,08-30 15:46:10.305  4027  4027 D SprintDMHelper: simOperator: 
08-30 15:46:10.306  4027  4027 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:46:10.307  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:46:10.309  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:46:10.314   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:46:10 GMT], X-Android-Received-Millis=[1472564770313], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472564770284]}
,08-30 15:46:10.316   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 15:46:10.316   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 15:46:10.316   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 15:46:10.317   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 15:46:10.321  1720  1720 D SystemUpdateService: onDestroy
,08-30 15:46:10.340  1519  2047 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 15:46:10.340  1519  2047 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 15:46:10.340  1519  2047 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:46:10.340  1519  2047 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:46:10.359  1720  4145 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-30 15:46:10.429  3997  4150 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 15:46:10.656   874   884 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-30 15:46:10.657   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:46:10.667   874  1994 I ActivityManager: Killing 2209:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 15:46:10.682  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 15:46:10.688   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:46:10.689   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 15:46:10.690   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:46:10.691   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:10.706   874  1308 E native  : do suspend true
,08-30 15:46:10.714   874  1871 D DhcpClient: Clearing IP address
,08-30 15:46:10.714   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:46:10.717   372   872 D CommandListener: Setting iface cfg
08-30 15:46:10.719  1519  4156 V NativeCrypto: Read error: ssl=0xaebf2600: I/O error during system call, Connection timed out
,08-30 15:46:10.722  1519  4156 V NativeCrypto: SSL shutdown failed: ssl=0xaebf2600: I/O error during system call, Broken pipe
,08-30 15:46:10.726   874  1427 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-30 15:46:10.726   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-30 15:46:10.727   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 15:46:10.731   874  4132 D DhcpClient: Receive thread stopped
,08-30 15:46:10.733   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:46:10.733   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 15:46:10.737   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-30 15:46:10.740   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 15:46:10.740   395   395 E Parcel  : Reading a NULL string not supported here.
08-30 15:46:10.743   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:46:10.744   874  1308 E native  : do suspend true
08-30 15:46:10.747   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 15:46:10.777   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:10.827   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:10.827   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:46:10.828   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 15:46:10.828   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:10.832   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:46:10.837  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:10.838  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:10.838  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.838  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:10.839  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:10.839  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:10.839  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.839  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:10.842   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 15:46:10.849  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 15:46:10.856  1720  1720 D SystemUpdateService: onCreate
08-30 15:46:10.861  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 15:46:10.861   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 15:46:10.864  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.864  2028  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:10.864  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:10.864  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.864  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:10.865  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:10.865  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:10.865  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:10.865  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:10.872   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:46:10.880  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 15:46:10.883  1720  4166 I SystemUpdateService: active receiver: enabled
,08-30 15:46:10.882  1720  2450 I iu.UploadsManager: num queued entries: 0
08-30 15:46:10.886  1720  2450 I iu.UploadsManager: num updated entries: 0
08-30 15:46:10.889  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 15:46:10.890  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 15:46:10.892  4027  4027 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:46:10.896  1720  4166 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-30 15:46:10.898  4027  4027 D SprintDMHelper: simOperator: 
08-30 15:46:10.899  4027  4027 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 15:46:10.909   372   872 E Netd    : netlink response contains error (No such file or directory)
08-30 15:46:10.911   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:46:10.911   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 15:46:10.912  1720  4166 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 15:46:10.912  1720  4166 I SystemUpdateService: now status is 0 (complete)
08-30 15:46:10.913  1720  4166 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 15:46:10.913  1720  4166 I SystemUpdateService: file has been verified
08-30 15:46:10.919  1720  4166 I SystemUpdateService: OTA package size = 12249756
,08-30 15:46:10.916  1720  2450 I iu.SyncManager: NEXT; no task
,08-30 15:46:10.930  3997  4170 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 15:46:10.959  1720  4166 I SystemUpdateService: showing system update notification
,08-30 15:46:10.977  1720  1720 D SystemUpdateService: onDestroy
,08-30 15:46:11.238   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 15:46:13.713   874   891 I ActivityManager: Start proc 4173:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 15:46:13.840  4173  4173 D AdapterServiceConfig: Adding HeadsetService
08-30 15:46:13.840  4173  4173 D AdapterServiceConfig: Adding A2dpService
,08-30 15:46:13.840  4173  4173 D AdapterServiceConfig: Adding HidService
08-30 15:46:13.840  4173  4173 D AdapterServiceConfig: Adding HealthService
08-30 15:46:13.840  4173  4173 D AdapterServiceConfig: Adding PanService
08-30 15:46:13.841  4173  4173 D AdapterServiceConfig: Adding GattService
08-30 15:46:13.841  4173  4173 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 15:46:13.856   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3124c1a:true
08-30 15:46:13.857  4173  4173 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 15:46:13.861  4173  4173 I bt_bluedroid: init
,08-30 15:46:13.862  4173  4185 I BluetoothAdapterState: Entering OffState
,08-30 15:46:13.866  4173  4186 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 15:46:13.867  4173  4186 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:46:13.867  4173  4186 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:46:13.867  4173  4186 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 15:46:13.869  4173  4173 I bt_bluedroid: get_profile_interface socket
,08-30 15:46:13.871  4173  4173 I bt_bluedroid: get_profile_interface sdp
,08-30 15:46:13.874  4173  4184 I bt_bluedroid: config_hci_snoop_log
,08-30 15:46:13.875   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 15:46:13.882  4173  4189 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:46:13.884  4173  4189 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:46:13.886  4173  4185 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 15:46:13.886  4173  4185 D BluetoothAdapterProperties: Setting state to 14
,08-30 15:46:13.886  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 15:46:13.891  4173  4185 D BluetoothBondStateMachine: make
,08-30 15:46:13.895  4173  4190 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 15:46:13.902  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:13.903  4173  4173 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 15:46:13.906  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:13.907  4173  4173 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:46:13.907  4173  4173 D BtGatt.GattService: Received start request. Starting profile...
,08-30 15:46:13.907  4173  4173 D BtGatt.GattService: start()
08-30 15:46:13.907  4173  4173 I bt_bluedroid: get_profile_interface gatt
08-30 15:46:13.908  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
08-30 15:46:13.908  4173  4173 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:46:13.915  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:13.915  4173  4173 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:46:13.915  4173  4173 V BluetoothAdapterState: isBleTurningOn()=true
08-30 15:46:13.915  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:13.916  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 15:46:13.916  4173  4185 I bt_bluedroid: enable
,08-30 15:46:13.917  4173  4186 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 15:46:13.918  4173  4186 I bt_hci  : start_up
,08-30 15:46:13.936  4173  4186 I bt_vendor: alloc value 0xb399c189
08-30 15:46:13.936  4173  4186 I bt_vendor: init
08-30 15:46:13.936  4173  4186 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 15:46:13.936  4173  4186 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 15:46:14.042  4173  4186 D bt_hci  : start_up starting async portion
,08-30 15:46:14.043  4173  4193 I bt_hci  : event_finish_startup
,08-30 15:46:14.043  4173  4193 I bt_hci_h4: hal_open
08-30 15:46:14.044  4173  4193 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 15:46:14.052  4173  4193 I bt_userial_vendor: device fd = 51 open
,08-30 15:46:14.086  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:46:14.118  4173  4193 D bt_hwcfg: Chipset BCM4354A2
,08-30 15:46:14.118  4173  4193 D bt_hwcfg: Target name = [BCM4354A2]
08-30 15:46:14.119  4173  4193 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 15:46:14.774  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 15:46:14.776  4173  4193 D bt_hwcfg: Settlement delay -- 100 ms
08-30 15:46:14.776  4173  4193 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 15:46:14.892  4173  4193 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:46:14.894  4173  4193 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 15:46:14.924  4173  4193 I bt_hwcfg: vendor lib fwcfg completed
,08-30 15:46:14.924  4173  4193 I bt_vendor: firmware callback
,08-30 15:46:14.924  4173  4193 I bt_hci  : firmware_config_callback
,08-30 15:46:14.935  4173  4197 I bt_btu  : btu_task pending for preload complete event
08-30 15:46:14.935  4173  4197 I bt_btu_task: Bluetooth chip preload is complete
08-30 15:46:14.936  4173  4197 I bt_btu  : btu_task received preload complete event
,08-30 15:46:14.945  4173  4197 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:46:14.946  4173  4197 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:46:14.946  4173  4197 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 15:46:14.946  4173  4197 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 15:46:14.947  4173  4197 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:46:14.947  4173  4197 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:46:14.947  4173  4197 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 15:46:14.947  4173  4197 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:46:14.948  4173  4197 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:46:14.948  4173  4197 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 15:46:14.948  4173  4197 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:46:14.948  4173  4197 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:46:14.949  4173  4197 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 15:46:14.949  4173  4197 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:46:14.949  4173  4197 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:46:15.082  4173  4197 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-30 15:46:15.082  4173  4197 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-30 15:46:15.094  4173  4189 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 15:46:15.095  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:46:15.096  4173  4189 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:46:15.104  4173  4189 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:46:15.107  4173  4189 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:46:15.108  4173  4189 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:46:15.111  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:15.112  4173  4189 D bt_hci  : do_postload posting postload work item
08-30 15:46:15.112  4173  4193 I bt_hci  : event_postload
08-30 15:46:15.112  4173  4193 I bt_vendor: sco_config_cb
08-30 15:46:15.112  4173  4193 I bt_hci  : sco_config_callback postload finished.
,08-30 15:46:15.115  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:15.119  4173  4189 D bt_bte_conf: Device ID record 1 : primary
,08-30 15:46:15.119  4173  4193 I bt_vendor: low_power_mode_cb
,08-30 15:46:15.119  4173  4189 D bt_bte_conf:   vendorId            = 000f
08-30 15:46:15.119  4173  4189 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 15:46:15.119  4173  4189 D bt_bte_conf:   product             = 1200
08-30 15:46:15.119  4173  4189 D bt_bte_conf:   version             = 1436
,08-30 15:46:15.120  4173  4189 D bt_bte_conf:   clientExecutableURL = 
08-30 15:46:15.120  4173  4189 D bt_bte_conf:   serviceDescription  = 
,08-30 15:46:15.120  4173  4189 D bt_bte_conf:   documentationURL    = 
08-30 15:46:15.120  4173  4189 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 15:46:15.120  4173  4186 D bt_stack_manager: event_start_up_stack finished
,08-30 15:46:15.121  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 15:46:15.121  4173  4185 D BluetoothAdapterProperties: Setting state to 15
,08-30 15:46:15.122  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 15:46:15.125  4173  4185 I BluetoothAdapterState: Entering BleOnState
,08-30 15:46:15.129  4173  4185 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 15:46:15.129  4173  4185 D BluetoothAdapterProperties: Setting state to 11,
08-30 15:46:15.129  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 15:46:15.143  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:15.144  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
08-30 15:46:15.144  4173  4173 D HeadsetService: Received start request. Starting profile...
08-30 15:46:15.144  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:15.147  4173  4173 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 15:46:15.147  4173  4173 D HeadsetStateMachine: make
,08-30 15:46:15.152  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:15.154  4173  4173 D HeadsetStateMachine: max_hf_connections = 1
08-30 15:46:15.154  4173  4173 I bt_bluedroid: get_profile_interface handsfree
,08-30 15:46:15.154  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 15:46:15.155  4173  4189 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 15:46:15.159  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:15.159  4173  4173 D A2dpService: Received start request. Starting profile...
08-30 15:46:15.160  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:15.160  4173  4173 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:46:15.160  4173  4173 I bt_bluedroid: get_profile_interface avrcp
,08-30 15:46:15.165  4173  4173 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 15:46:15.165  4173  4173 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:46:15.165  4173  4173 D A2dpStateMachine: make
,08-30 15:46:15.167  4173  4173 I bt_bluedroid: get_profile_interface a2dp
,08-30 15:46:15.167  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 15:46:15.169  4173  4173 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:46:15.169  4173  4206 D A2dpStateMachine: Enter Disconnected: -2
08-30 15:46:15.169  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:15.170  4173  4173 D HidService: Received start request. Starting profile...
08-30 15:46:15.170  4173  4173 I bt_bluedroid: get_profile_interface hidhost
,08-30 15:46:15.171  4173  4173 D HidService: setHidService(): set to: null
08-30 15:46:15.171  4173  4189 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-30 15:46:15.171  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 15:46:15.171  4173  4173 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:46:15.172  3946  3946 D BluetoothInputDevice: Proxy object connected
,08-30 15:46:15.172  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
08-30 15:46:15.173  4173  4173 D HealthService: Received start request. Starting profile...
,08-30 15:46:15.173  3946  3946 D HidProfile: Bluetooth service connected
,08-30 15:46:15.174  4173  4173 I bt_bluedroid: get_profile_interface health
,08-30 15:46:15.174  4173  4173 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 15:46:15.175  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:15.176  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:46:15.176  4173  4173 D PanService: Received start request. Starting profile...
08-30 15:46:15.177  4173  4173 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:46:15.177  4173  4173 I bt_bluedroid: get_profile_interface pan
08-30 15:46:15.177  4173  4189 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 15:46:15.180  4173  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:15.181  4173  4173 D BluetoothMapService: Received start request. Starting profile...
,08-30 15:46:15.181  4173  4173 D BluetoothMapService: start()
,08-30 15:46:15.183  4173  4173 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 15:46:15.184  4173  4173 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 15:46:15.184  4173  4173 D BluetoothMapAppObserver: createReceiver()
,08-30 15:46:15.185  4173  4173 D BluetoothMapAppObserver: initObservers()
08-30 15:46:15.185  4173  4173 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 15:46:15.191  4173  4173 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:15.191  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:15.191  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:15.191  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:15.192  3946  3946 D PanProfile: Bluetooth service connected
,08-30 15:46:15.193  3946  3946 D BluetoothMap: Proxy object connected
08-30 15:46:15.193  4173  4204 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 15:46:15.193  3946  3946 D MapProfile: Bluetooth service connected
08-30 15:46:15.193  3946  3946 D BluetoothMap: getConnectedDevices(),
,08-30 15:46:15.194  3946  3946 D BluetoothMap: Bluetooth is Not enabled
,08-30 15:46:15.194  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:15.195  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:46:15.196  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:15.197  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:15.197  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 15:46:15.197  4173  4185 D BluetoothAdapterProperties: ScanMode =  20
,08-30 15:46:15.197  4173  4185 D BluetoothAdapterProperties: State =  11
08-30 15:46:15.198  4173  4185 D BluetoothAdapterProperties: Setting state to 12
,08-30 15:46:15.198  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:46:15.198   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-30 15:46:15.198  1366  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:46:15.199  4173  4185 I BluetoothAdapterState: Entering OnState
,08-30 15:46:15.199  4173  4189 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:46:15.199  4173  4189 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:46:15.200  3946  3956 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:46:15.202  1945  2231 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:15.202  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:15.202  1366  2232 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:46:15.204   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:15.204  1366  1378 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:46:15.204  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:15.205  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:46:15.205  1366  1366 D PanProfile: Bluetooth service connected
08-30 15:46:15.206  3946  3958 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:46:15.206  3946  3956 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:46:15.206   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:15.206   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:15.207  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:15.207  1366  2232 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:46:15.208   874   874 D BluetoothA2dp: Proxy object connected
,08-30 15:46:15.209  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:15.209  1366  1366 D BluetoothA2dp: Proxy object connected
08-30 15:46:15.210  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:46:15.211  1366  1366 D BluetoothInputDevice: Proxy object connected
08-30 15:46:15.211  1366  1366 D HidProfile: Bluetooth service connected
08-30 15:46:15.211  1366  2232 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:46:15.211  4173  4173 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 15:46:15.213  4173  4173 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 15:46:15.213  1366  1366 D BluetoothMap: Proxy object connected
08-30 15:46:15.213  1366  1366 D MapProfile: Bluetooth service connected
08-30 15:46:15.213  1366  1366 D BluetoothMap: getConnectedDevices()
,08-30 15:46:15.213  3946  3958 D BluetoothPan: onBluetoothStateChange on: true
,08-30 15:46:15.215   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 15:46:15.217  4173  4173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:15.218  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:15.218  3946  3946 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 15:46:15.219  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:15.220  4173  4173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:15.221  4173  4173 D ObexServerSockets: Succeed to create listening sockets 
,08-30 15:46:15.221  4173  4173 D ObexServerSockets0: startAccept()
,08-30 15:46:15.221  4173  4173 D ObexServerSockets0: prepareForNewConnect()
08-30 15:46:15.223  3946  3946 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 15:46:15.224  4173  4173 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 15:46:15.224  4173  4173 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 15:46:15.224  4173  4173 D BluetoothMapService: onReceive
08-30 15:46:15.224  4173  4173 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:46:15.224  4173  4173 D BluetoothMapService: STATE_ON
,08-30 15:46:15.225  4173  4213 D ObexServerSockets0: Accepting socket connection...
08-30 15:46:15.226  4173  4214 D ObexServerSockets0: Accepting socket connection...
08-30 15:46:15.229  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:46:15.233  3946  3946 D BluetoothA2dp: Proxy object connected
,08-30 15:46:15.235  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:15.241  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:46:15.243  3946  3946 D BluetoothPbap: Proxy object connected
,08-30 15:46:15.243  3946  3946 D PbapServerProfile: Bluetooth service connected
,08-30 15:46:15.247  1366  1366 D BluetoothPbap: Proxy object connected
,08-30 15:46:15.247  1366  1366 D PbapServerProfile: Bluetooth service connected
,08-30 15:46:15.250  4173  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:46:15.251  4173  4173 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 15:46:15.251  4173  4173 D ObexServerSockets0: prepareForNewConnect()
,08-30 15:46:15.267  4173  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:46:15.268  4173  4222 I BtOppRfcommListener: Accept thread started.
,08-30 15:46:15.299  1366  1378 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.299  1945  2085 D BluetoothHeadset: Proxy object connected
08-30 15:46:15.299  1366  1366 D HeadsetProfile: Bluetooth service connected
08-30 15:46:15.300   874   874 D BluetoothHeadset: Proxy object connected
08-30 15:46:15.300   874   874 D BluetoothHeadset: Proxy object connected
08-30 15:46:15.300  1366  1379 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.300   874   874 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.302  1945  1958 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.302  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-30 15:46:15.304   874   891 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.307   874   891 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.326  3946  3956 D BluetoothHeadset: Proxy object connected
,08-30 15:46:15.327  3946  3946 D HeadsetProfile: Bluetooth service connected
,08-30 15:46:16.673  4173  4185 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 15:46:16.674  4173  4185 D BluetoothAdapterProperties: Setting state to 13
,08-30 15:46:16.674  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:46:16.676  4173  4185 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 15:46:16.685  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:16.686  4173  4173 D BluetoothMapService: onReceive
,08-30 15:46:16.686  4173  4173 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:46:16.687  4173  4173 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:46:16.687  4173  4173 D BluetoothMapService: MAP Service closeService in
08-30 15:46:16.688  4173  4173 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 15:46:16.688  4173  4173 D ObexServerSockets0: shutdown(block = true)
08-30 15:46:16.689  4173  4213 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 15:46:16.693  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:16.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:16.695  4173  4173 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:46:16.695  4173  4189 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:46:16.695  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:46:16.698  4173  4214 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 15:46:16.698  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:16.698  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 15:46:16.698  4173  4200 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 15:46:16.699  4173  4173 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:46:16.699  4173  4173 I BtOppRfcommListener: stopping Accept Thread
08-30 15:46:16.699  4173  4222 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:46:16.700  4173  4222 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:46:16.704  4173  4173 D HeadsetService: Received stop request...Stopping profile...
08-30 15:46:16.705  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 15:46:16.707  4173  4173 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:16.707  1945  1959 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.707  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:16.707  4173  4173 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:46:16.707   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.707  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:46:16.707   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:16.707  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:16.707  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:16.708  3946  3958 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.709  4173  4173 D A2dpService: Received stop request...Stopping profile...
08-30 15:46:16.709  4173  4206 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:46:16.710  1366  1379 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.709  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:46:16.710  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:16.710   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 15:46:16.713   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 15:46:16.713  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:16.715  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-30 15:46:16.715  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-30 15:46:16.716  3946  3946 D HeadsetProfile: Bluetooth service disconnected
08-30 15:46:16.716  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:16.717  4173  4173 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:46:16.718  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.717  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 15:46:16.718  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.718  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.718  4173  4189 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-30 15:46:16.718  4173  4173 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:46:16.719  3946  3946 D DockEventReceiver: finishStartingService: stopping service
08-30 15:46:16.719  4173  4173 D HidService: Received stop request...Stopping profile...
08-30 15:46:16.720  4173  4173 D HidService: Stopping Bluetooth HidService
08-30 15:46:16.721  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-30 15:46:16.721  3946  3946 D BluetoothA2dp: Proxy object disconnected
08-30 15:46:16.721  1366  1366 D HidProfile: Bluetooth service disconnected
08-30 15:46:16.722  4173  4173 D HealthService: Received stop request...Stopping profile...
08-30 15:46:16.722  3946  3946 D BluetoothInputDevice: Proxy object disconnected
08-30 15:46:16.723  3946  3946 D HidProfile: Bluetooth service disconnected
08-30 15:46:16.724  4173  4173 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:16.724  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:16.724  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:16.724  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:16.727  4173  4173 D PanService: Received stop request...Stopping profile...
,08-30 15:46:16.728  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:46:16.728  1366  1366 D PanProfile: Bluetooth service disconnected
,08-30 15:46:16.729  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:16.729  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 15:46:16.729  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.729  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.730  4173  4197 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:46:16.730  4173  4197 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:46:16.730  4173  4197 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:46:16.730  4173  4197 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-30 15:46:16.730  4173  4173 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:46:16.730  4173  4173 D BluetoothMapService: stop()
08-30 15:46:16.731  4173  4173 D BluetoothMapAppObserver: deinitObservers()
08-30 15:46:16.731  4173  4173 D BluetoothMapAppObserver: removeReceiver()
08-30 15:46:16.731  3946  3946 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:46:16.732  4173  4173 V BluetoothAdapterState: isTurningOff()=true
,08-30 15:46:16.733  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:16.733  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:16.731  3946  3946 D PanProfile: Bluetooth service disconnected
08-30 15:46:16.733  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:16.733  1366  1366 D BluetoothMap: Proxy object disconnected
08-30 15:46:16.733  1366  1366 D MapProfile: Bluetooth service disconnected
08-30 15:46:16.733  3946  3946 D BluetoothMap: Proxy object disconnected
08-30 15:46:16.733  3946  3946 D MapProfile: Bluetooth service disconnected
,08-30 15:46:16.733  4173  4173 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:46:16.733  4173  4189 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:46:16.733  4173  4173 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:46:16.734  4173  4173 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:16.734  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:16.734  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:16.734  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:16.734  4173  4173 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:46:16.734  4173  4189 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 15:46:16.735  4173  4173 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:46:16.736  1366  1366 D BluetoothPbap: Proxy object disconnected
08-30 15:46:16.736  1366  1366 D PbapServerProfile: Bluetooth service disconnected
08-30 15:46:16.736  4173  4173 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:16.736  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:16.736  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:16.737  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:16.737  3946  3946 D BluetoothPbap: Proxy object disconnected
08-30 15:46:16.737  3946  3946 D PbapServerProfile: Bluetooth service disconnected
08-30 15:46:16.737  4173  4173 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:46:16.737  4173  4173 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:46:16.739  4173  4173 D BluetoothMapService: MAP Service closeService in
08-30 15:46:16.739  4173  4173 V BluetoothAdapterState: isTurningOff()=true
08-30 15:46:16.739  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:16.739  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:16.740  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:16.740  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 15:46:16.740  4173  4185 D BluetoothAdapterProperties: Setting state to 15
08-30 15:46:16.740  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 15:46:16.740  4173  4173 D BluetoothMapService: cleanup()
08-30 15:46:16.740  4173  4185 I BluetoothAdapterState: Entering BleOnState
08-30 15:46:16.741  4173  4173 D BluetoothMapService: MAP Service closeService in
08-30 15:46:16.741   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.741  1366  2232 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.742  3946  4226 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:46:16.742  1945  2374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.743  3946  3958 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.743  1366  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:46:16.743   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.744  1366  1378 D BluetoothPan: onBluetoothStateChange on: false
,08-30 15:46:16.745  3946  3956 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:46:16.745  3946  4226 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:46:16.746  3946  3958 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:46:16.746   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:46:16.746   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:46:16.746  1366  2232 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 15:46:16.747  1366  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:46:16.747  1366  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:46:16.748  3946  3956 D BluetoothPan: onBluetoothStateChange on: false
,08-30 15:46:16.748  4173  4185 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 15:46:16.749  4173  4185 D BluetoothAdapterProperties: Setting state to 16
,08-30 15:46:16.749  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 15:46:16.749  4173  4185 D BluetoothAdapterProperties: onBleDisable
08-30 15:46:16.750  4173  4185 I BluetoothAdapterState: Entering PendingCommandState
08-30 15:46:16.750  4173  4186 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 15:46:16.751  4173  4197 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 15:46:16.751  4173  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:46:16.753  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:16.754  4173  4189 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:46:16.754  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:16.755  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:46:16.755  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:16.756  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:16.759  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:16.760  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:46:16.951  4173  4189 I bt_hci  : shut_down
,08-30 15:46:16.962  4173  4193 I bt_vendor: low_power_mode_cb
08-30 15:46:16.963  4173  4193 D bt_hwcfg: hw_epilog_process
,08-30 15:46:16.979  4173  4193 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 15:46:16.980  4173  4193 I bt_vendor: epilog_cb
08-30 15:46:16.980  4173  4193 I bt_hci  : epilog_finished_callback
,08-30 15:46:16.986  4173  4189 I bt_hci_h4: hal_close
,08-30 15:46:16.987  4173  4189 I bt_userial_vendor: device fd = 51 close
,08-30 15:46:17.102  4173  4186 D bt_stack_manager: event_shut_down_stack finished.
,08-30 15:46:17.103  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 15:46:17.109  4173  4173 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:46:17.109  4173  4185 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 15:46:17.110  4173  4173 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 15:46:17.111  4173  4173 D BtGatt.GattService: stop()
08-30 15:46:17.111  4173  4173 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 15:46:17.116  4173  4173 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:17.116  4173  4173 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:17.117  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:17.117  4173  4173 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 15:46:17.118  4173  4185 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 15:46:17.119  4173  4185 D BluetoothAdapterProperties: Setting state to 10
08-30 15:46:17.119  4173  4185 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 15:46:17.121  4173  4185 I BluetoothAdapterState: Entering OffState
,08-30 15:46:17.122   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 15:46:17.147  4173  4173 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 15:46:17.147  4173  4173 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 15:46:17.148  4173  4173 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 15:46:17.150  4173  4186 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 15:46:17.161  4173  4186 D bt_stack_manager: event_clean_up_stack finished.
,08-30 15:46:17.167  4173  4173 I art     : System.exit called, status: 0
,08-30 15:46:17.168  4173  4173 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:46:17.238   874   884 I ActivityManager: Process com.android.bluetooth (pid 4173) has died
,08-30 15:46:18.144   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-30 15:46:19.670  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:46:19.671  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:22.678  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:22.679  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c80927 added. We now have 6 listener(s)
08-30 15:46:22.679  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:22.683  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:22.683  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1ff7d4 added. We now have 7 listener(s)
,08-30 15:46:22.684  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:22.685  3868  3915 I System.out: IsBluetoothEnabled
,08-30 15:46:22.697  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:22.748   874   891 I ActivityManager: Start proc 4234:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 15:46:22.884  4234  4234 D AdapterServiceConfig: Adding HeadsetService
,08-30 15:46:22.885  4234  4234 D AdapterServiceConfig: Adding A2dpService
08-30 15:46:22.885  4234  4234 D AdapterServiceConfig: Adding HidService
08-30 15:46:22.885  4234  4234 D AdapterServiceConfig: Adding HealthService
,08-30 15:46:22.885  4234  4234 D AdapterServiceConfig: Adding PanService
08-30 15:46:22.886  4234  4234 D AdapterServiceConfig: Adding GattService
08-30 15:46:22.886  4234  4234 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 15:46:22.902  4234  4234 D BluetoothAdapterState: make() - Creating AdapterState
08-30 15:46:22.902   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af8d6ef:true
,08-30 15:46:22.906  4234  4234 I bt_bluedroid: init
,08-30 15:46:22.907  4234  4246 I BluetoothAdapterState: Entering OffState
,08-30 15:46:22.913  4234  4247 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 15:46:22.914  4234  4247 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 15:46:22.914  4234  4247 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 15:46:22.914  4234  4247 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 15:46:22.918  4234  4234 I bt_bluedroid: get_profile_interface socket
,08-30 15:46:22.920  4234  4234 I bt_bluedroid: get_profile_interface sdp
,08-30 15:46:22.923  4234  4245 I bt_bluedroid: config_hci_snoop_log
,08-30 15:46:22.924   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 15:46:22.924  4234  4250 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:46:22.933  4234  4250 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:46:22.938  4234  4246 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 15:46:22.938  4234  4246 D BluetoothAdapterProperties: Setting state to 14
08-30 15:46:22.939  4234  4246 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 15:46:22.943  4234  4246 D BluetoothBondStateMachine: make
,08-30 15:46:22.948  4234  4251 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 15:46:22.956  4234  4246 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:22.957  4234  4234 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 15:46:22.959  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:22.960  4234  4234 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:46:22.960  4234  4234 D BtGatt.GattService: Received start request. Starting profile...
,08-30 15:46:22.961  4234  4234 D BtGatt.GattService: start()
08-30 15:46:22.961  4234  4234 I bt_bluedroid: get_profile_interface gatt
08-30 15:46:22.961  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:22.962  4234  4234 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:46:22.970  4234  4234 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:22.970  4234  4234 V BluetoothAdapterState: isTurningOn()=false
08-30 15:46:22.970  4234  4234 V BluetoothAdapterState: isBleTurningOn()=true
08-30 15:46:22.970  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:22.971  4234  4246 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 15:46:22.972  4234  4246 I bt_bluedroid: enable
08-30 15:46:22.972  4234  4247 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 15:46:22.973  4234  4247 I bt_hci  : start_up
,08-30 15:46:22.994  4234  4247 I bt_vendor: alloc value 0xb399c189
,08-30 15:46:22.994  4234  4247 I bt_vendor: init
08-30 15:46:22.994  4234  4247 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 15:46:22.995  4234  4247 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 15:46:23.104  4234  4247 D bt_hci  : start_up starting async portion
,08-30 15:46:23.105  4234  4254 I bt_hci  : event_finish_startup
,08-30 15:46:23.105  4234  4254 I bt_hci_h4: hal_open
,08-30 15:46:23.106  4234  4254 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 15:46:23.118  4234  4254 I bt_userial_vendor: device fd = 51 open
,08-30 15:46:23.146  4234  4254 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:46:23.178  4234  4254 D bt_hwcfg: Chipset BCM4354A2
,08-30 15:46:23.178  4234  4254 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 15:46:23.179  4234  4254 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 15:46:23.833  4234  4254 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 15:46:23.834  4234  4254 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 15:46:23.836  4234  4254 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 15:46:23.952  4234  4254 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:46:23.954  4234  4254 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 15:46:23.982  4234  4254 I bt_hwcfg: vendor lib fwcfg completed
,08-30 15:46:23.982  4234  4254 I bt_vendor: firmware callback
08-30 15:46:23.983  4234  4254 I bt_hci  : firmware_config_callback
,08-30 15:46:23.995  4234  4256 I bt_btu  : btu_task pending for preload complete event
,08-30 15:46:23.995  4234  4256 I bt_btu_task: Bluetooth chip preload is complete
08-30 15:46:23.996  4234  4256 I bt_btu  : btu_task received preload complete event
,08-30 15:46:24.007  4234  4256 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:46:24.008  4234  4256 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:46:24.008  4234  4256 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 15:46:24.008  4234  4256 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:46:24.009  4234  4256 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 15:46:24.009  4234  4256 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 15:46:24.009  4234  4256 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 15:46:24.010  4234  4256 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:46:24.010  4234  4256 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 15:46:24.010  4234  4256 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 15:46:24.011  4234  4256 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:46:24.011  4234  4256 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 15:46:24.012  4234  4256 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:46:24.013  4234  4256 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 15:46:24.013  4234  4256 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:46:24.147  4234  4256 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-30 15:46:24.148  4234  4256 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-30 15:46:24.160  4234  4250 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 15:46:24.163  4234  4250 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:46:24.164  4234  4250 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:46:24.168  4234  4250 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:46:24.172  4234  4250 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:46:24.173  4234  4250 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:46:24.175  4234  4250 D bt_hci  : do_postload posting postload work item
08-30 15:46:24.176  4234  4254 I bt_hci  : event_postload
,08-30 15:46:24.176  4234  4254 I bt_vendor: sco_config_cb
08-30 15:46:24.176  4234  4254 I bt_hci  : sco_config_callback postload finished.
08-30 15:46:24.177  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:24.178  4234  4250 D bt_bte_conf: Device ID record 1 : primary
,08-30 15:46:24.178  4234  4250 D bt_bte_conf:   vendorId            = 000f
08-30 15:46:24.178  4234  4250 D bt_bte_conf:   vendorIdSource      = 0001
08-30 15:46:24.179  4234  4250 D bt_bte_conf:   product             = 1200
08-30 15:46:24.179  4234  4250 D bt_bte_conf:   version             = 1436
08-30 15:46:24.179  4234  4250 D bt_bte_conf:   clientExecutableURL = 
,08-30 15:46:24.179  4234  4250 D bt_bte_conf:   serviceDescription  = 
,08-30 15:46:24.179  4234  4250 D bt_bte_conf:   documentationURL    = 
08-30 15:46:24.180  4234  4250 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 15:46:24.180  4234  4247 D bt_stack_manager: event_start_up_stack finished
,08-30 15:46:24.181  4234  4254 I bt_vendor: low_power_mode_cb
08-30 15:46:24.181  4234  4246 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 15:46:24.182  4234  4246 D BluetoothAdapterProperties: Setting state to 15
08-30 15:46:24.182  4234  4246 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 15:46:24.183  4234  4246 I BluetoothAdapterState: Entering BleOnState
08-30 15:46:24.189  4234  4246 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 15:46:24.190  4234  4246 D BluetoothAdapterProperties: Setting state to 11
08-30 15:46:24.190  4234  4246 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 15:46:24.195  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.196  4234  4234 D HeadsetService: Received start request. Starting profile...
,08-30 15:46:24.200  4234  4234 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 15:46:24.200  4234  4234 D HeadsetStateMachine: make
08-30 15:46:24.202  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:24.212  4234  4246 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:46:24.213  4234  4234 D HeadsetStateMachine: max_hf_connections = 1
,08-30 15:46:24.213  4234  4234 I bt_bluedroid: get_profile_interface handsfree
,08-30 15:46:24.214  4234  4250 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 15:46:24.214  4234  4250 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 15:46:24.222  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.223  4234  4234 D A2dpService: Received start request. Starting profile...
,08-30 15:46:24.225  4234  4234 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 15:46:24.225  4234  4234 I bt_bluedroid: get_profile_interface avrcp
,08-30 15:46:24.239  4234  4234 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 15:46:24.239  4234  4234 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:46:24.239  4234  4234 D A2dpStateMachine: make
,08-30 15:46:24.241  4234  4234 I bt_bluedroid: get_profile_interface a2dp
,08-30 15:46:24.243  4234  4250 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 15:46:24.246  4234  4265 D A2dpStateMachine: Enter Disconnected: -2
,08-30 15:46:24.246  4234  4234 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:46:24.247  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.248  4234  4234 D HidService: Received start request. Starting profile...
08-30 15:46:24.248  4234  4234 I bt_bluedroid: get_profile_interface hidhost
08-30 15:46:24.248  4234  4234 D HidService: setHidService(): set to: null
,08-30 15:46:24.248  4234  4250 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-30 15:46:24.249  4234  4250 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 15:46:24.250  4234  4234 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 15:46:24.250  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.251  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:46:24.251  4234  4234 D HealthService: Received start request. Starting profile...
08-30 15:46:24.253  4234  4234 I bt_bluedroid: get_profile_interface health
,08-30 15:46:24.254  4234  4234 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 15:46:24.255  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.256  4234  4234 D PanService: Received start request. Starting profile...
08-30 15:46:24.256  4234  4234 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:46:24.256  4234  4234 I bt_bluedroid: get_profile_interface pan
08-30 15:46:24.257  4234  4250 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 15:46:24.260  4234  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:24.261  4234  4234 D BluetoothMapService: Received start request. Starting profile...
08-30 15:46:24.261  4234  4234 D BluetoothMapService: start()
,08-30 15:46:24.263  4234  4234 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 15:46:24.264  4234  4234 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 15:46:24.264  4234  4234 D BluetoothMapAppObserver: createReceiver()
,08-30 15:46:24.265  4234  4234 D BluetoothMapAppObserver: initObservers()
,08-30 15:46:24.265  4234  4234 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 15:46:24.273  4234  4262 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 15:46:24.274  4234  4234 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:24.274  4234  4234 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:24.274  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:46:24.274  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:24.276  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isTurningOff()=false
08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isTurningOn()=true
08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:46:24.279  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:46:24.280  4234  4234 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:46:24.280  4234  4234 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:46:24.280  4234  4234 V BluetoothAdapterState: isBleTurningOn()=false,
,08-30 15:46:24.280  4234  4234 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:46:24.280  4234  4246 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 15:46:24.280  4234  4246 D BluetoothAdapterProperties: ScanMode =  20
,08-30 15:46:24.280  4234  4246 D BluetoothAdapterProperties: State =  11
,08-30 15:46:24.283  4234  4250 D BluetoothAdapterProperties: Scan Mode:21
,08-30 15:46:24.283  4234  4246 D BluetoothAdapterProperties: Setting state to 12
,08-30 15:46:24.283  4234  4250 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:46:24.283  4234  4246 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 15:46:24.283   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:24.283  4234  4246 I BluetoothAdapterState: Entering OnState,
08-30 15:46:24.284  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=true,
,08-30 15:46:24.286  3946  4226 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:24.287  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:24.290  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:24.290  1945  1959 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:24.291  3946  3958 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:24.292  1366  2232 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:46:24.293  4234  4234 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 15:46:24.293  4234  4234 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 15:46:24.294   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:46:24.295  4234  4234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:24.295  1366  1379 D BluetoothPan: onBluetoothStateChange on: true
,08-30 15:46:24.298  4234  4234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:46:24.298  3946  3956 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:46:24.299  4234  4234 D ObexServerSockets: Succeed to create listening sockets 
,08-30 15:46:24.299  4234  4234 D ObexServerSockets0: startAccept()
08-30 15:46:24.299  4234  4234 D ObexServerSockets0: prepareForNewConnect()
08-30 15:46:24.300  3946  3956 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:46:24.302  3946  3958 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:46:24.303  4234  4234 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 15:46:24.303  4234  4234 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 15:46:24.304  4234  4270 D ObexServerSockets0: Accepting socket connection...
08-30 15:46:24.305  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:46:24.305  1366  1366 D PanProfile: Bluetooth service connected
08-30 15:46:24.306  4234  4271 D ObexServerSockets0: Accepting socket connection...
08-30 15:46:24.308   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:46:24.308   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:46:24.310   874   874 D BluetoothA2dp: Proxy object connected
08-30 15:46:24.311  3946  3946 D BluetoothInputDevice: Proxy object connected
,08-30 15:46:24.311  1366  2232 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:46:24.311  3946  3946 D HidProfile: Bluetooth service connected
08-30 15:46:24.314  3946  3946 D BluetoothA2dp: Proxy object connected
08-30 15:46:24.314  1366  1366 D BluetoothA2dp: Proxy object connected
08-30 15:46:24.314  1366  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:46:24.316  3946  3946 D BluetoothMap: Proxy object connected
,08-30 15:46:24.316  3946  3946 D MapProfile: Bluetooth service connected
08-30 15:46:24.316  3946  3946 D BluetoothMap: getConnectedDevices()
08-30 15:46:24.316  1366  1366 D BluetoothInputDevice: Proxy object connected
08-30 15:46:24.316  1366  1366 D HidProfile: Bluetooth service connected
08-30 15:46:24.316  1366  1378 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:46:24.319  1366  1366 D BluetoothMap: Proxy object connected
,08-30 15:46:24.319  1366  1366 D MapProfile: Bluetooth service connected
08-30 15:46:24.319  1366  1366 D BluetoothMap: getConnectedDevices()
08-30 15:46:24.319  3946  3958 D BluetoothPan: onBluetoothStateChange on: true
,08-30 15:46:24.321  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:46:24.321  3946  3946 D PanProfile: Bluetooth service connected
,08-30 15:46:24.322   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 15:46:24.324  4234  4234 D BluetoothMapService: onReceive
,08-30 15:46:24.324  4234  4234 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:46:24.324  4234  4234 D BluetoothMapService: STATE_ON
,08-30 15:46:24.325  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:24.331  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:46:24.338  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:46:24.340  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:46:24.345  3946  3946 D BluetoothPbap: Proxy object connected
,08-30 15:46:24.345  3946  3946 D PbapServerProfile: Bluetooth service connected
,08-30 15:46:24.351  4234  4234 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 15:46:24.351  1366  1366 D BluetoothPbap: Proxy object connected
,08-30 15:46:24.351  4234  4234 D ObexServerSockets0: prepareForNewConnect()
08-30 15:46:24.351  1366  1366 D PbapServerProfile: Bluetooth service connected
,08-30 15:46:24.354  4234  4276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:46:24.378  4234  4280 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:46:24.380  4234  4280 I BtOppRfcommListener: Accept thread started.
,08-30 15:46:24.386  1945  2374 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.386   874   874 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.386   874   874 D BluetoothHeadset: Proxy object connected
08-30 15:46:24.387  3946  4226 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.388  3946  3946 D HeadsetProfile: Bluetooth service connected
,08-30 15:46:24.389  1366  1379 D BluetoothHeadset: Proxy object connected
08-30 15:46:24.389  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-30 15:46:24.389   874   874 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.391  1945  2231 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.393  3946  3958 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.394  3946  3946 D HeadsetProfile: Bluetooth service connected
,08-30 15:46:24.395   874   891 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.408   874   891 D BluetoothHeadset: Proxy object connected
,08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:24.721  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:24.728  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:24.732  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:24.732  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c174d7d added. We now have 8 listener(s)
08-30 15:46:24.733  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:24.738   874  2259 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-30 15:46:24.738   874  2259 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:46:24.750  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:24.751   874  1997 D WifiService: setWifiEnabled: true pid=3868, uid=10000
,08-30 15:46:24.752   874  1997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:46:24.766   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:24.786  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:24.793  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:24.802   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-30 15:46:24.803   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 15:46:24.804   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 15:46:24.805   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:46:24.805   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 15:46:24.805   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 15:46:24.805   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 15:46:24.820   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 15:46:24.821   372   872 D CommandListener: Setting iface cfg
08-30 15:46:24.821   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:46:24.822   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 15:46:24.822   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 15:46:24.874   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-30 15:46:24.875   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-30 15:46:24.878   874  1308 E native  : do suspend true
,08-30 15:46:24.922   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:25.777  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:25.784  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:25.796  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 15:46:25.799  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 15:46:25.806  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@612c15a Bundle[{}]
,08-30 15:46:25.807  3868  3915 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:46:25.807  3868  3915 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 15:46:25.808  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 15:46:25.808  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:46:25.809  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 15:46:25.810  3868  3915 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 15:46:25.814  3868  3915 I System.out: Running OutgoingSocketThread
,08-30 15:46:25.817  3868  4286 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,08-30 15:46:25.819  3868  4286 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44544
,08-30 15:46:25.820  3868  4286 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 15:46:26.284   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:46:26.388   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=10.94 delta 1000 -> 994
,08-30 15:46:26.391   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 15:46:26.392   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:46:26.410   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 15:46:26.489   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 15:46:26.494  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 15:46:26.818  3868  3915 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,08-30 15:46:26.818  3868  3915 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,08-30 15:46:26.828  3868  3915 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-30 15:46:26.831  3868  3915 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 15:46:26.832  3868  3915 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,08-30 15:46:26.838  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:46:26.838  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b364472 added. We now have 2 listener(s)
,08-30 15:46:26.840  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:26.840  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:26.840  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:26.840  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:26.841  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12210c3 added. We now have 9 listener(s)
08-30 15:46:26.841  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:26.842  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:46:26.849  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:26.857  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:26.861  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:26.862  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:26.862  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:26.863  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a504479 added. We now have 3 listener(s)
,08-30 15:46:26.865  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:26.867  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:26.868  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:26.869  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:26.869  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:46:26.869  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:26.870  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a035be added. We now have 10 listener(s)
08-30 15:46:26.870  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:26.871  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:26.871  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:46:26.871  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:26.872  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:26.872  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.872  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:26.873  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:26.873  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b364472 removed from the list
,08-30 15:46:26.873  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:26.873  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12210c3 removed from the list
08-30 15:46:26.874  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:26.874  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:26.876  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.876  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:26.878  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:46:26.879  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:26.879  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:26.879  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12210c3 not in the list
08-30 15:46:26.879  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.880  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:46:26.882  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:26.883  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:26.883  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:26.883  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a035be removed from the list
08-30 15:46:26.883  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:26.884  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.884  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:26.884  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 15:46:26.884  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a504479 removed from the list
,08-30 15:46:26.886  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:26.887  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8af61f added. We now have 2 listener(s)
,08-30 15:46:26.892  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:46:26.893  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:26.893  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:26.893  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:26.894  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3226d6c added. We now have 9 listener(s)
08-30 15:46:26.894  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:26.895  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:46:26.900  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:26.910  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:26.916  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:26.917  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:26.917  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:46:26.917  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@925efca added. We now have 3 listener(s)
,08-30 15:46:26.918  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:46:26.920  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:26.924  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:26.925  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:46:26.925  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:26.926  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:26.926  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:26.926  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@472d53b added. We now have 10 listener(s)
08-30 15:46:26.927  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:26.927  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:46:26.934  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:46:26.934  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 15:46:26.934  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:26.934  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:46:26.940  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:46:26.941  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:46:26.948  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:46:26.949  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:46:26.949  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:46:26.953  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:46:26.953  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:46:26.954  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:46:26.954  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:26.957  4234  4245 D BtGatt.GattService: registerClient() - UUID=e82d43b0-af6f-478d-97d8-eb3854d9bd53
,08-30 15:46:26.958  4234  4250 D BtGatt.GattService: onClientRegistered() - UUID=e82d43b0-af6f-478d-97d8-eb3854d9bd53, clientIf=5
,08-30 15:46:26.959  3868  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:46:26.960  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:46:26.960  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-30 15:46:26.961  4234  4244 D BtGatt.GattService: start scan with filters
08-30 15:46:26.963   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:46:26.967  4234  4253 D BtGatt.ScanManager: handling starting scan
,08-30 15:46:26.968  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:46:26.968  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:46:26.969  4234  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c00e4e
,08-30 15:46:26.971  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 15:46:26.971  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:46:26.973  4234  4250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:46:26.973  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:26.973   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 15:46:26.974   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:46:26.974  4234  4253 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 15:46:26.974   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 15:46:26.975  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:26.976  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:26.976  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:46:26.978  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 15:46:26.981  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:46:26.981  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:26.982  4234  4253 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:46:26.982  4234  4253 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:46:26.984  3868  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:46:26.984  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:26.985  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:46:26.985  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.985  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:46:26.985  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 15:46:26.985  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:46:26.986  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:46:26.986  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:46:26.986  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:26.986  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:46:26.988  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:26.989  4234  4244 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:46:26.990  4234  4272 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:46:26.990  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:46:26.990  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:46:26.990  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:46:26.990  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:26.990  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:46:26.991  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:26.991  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:46:26.992  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:46:26.992  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:46:26.993  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:26.993  4234  4250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:46:26.993  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:26.995  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:26.995  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:26.995  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:46:26.997   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:46:26.998  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:26.998  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:26.998  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:26.998  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:26.999  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:26.999  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:26.999  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:26.999  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8af61f removed from the list
08-30 15:46:26.999  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:26.999  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3226d6c removed from the list
,08-30 15:46:26.999  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:26.999  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.000  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:27.000  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.000  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.001  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:27.001  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.001  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3226d6c not in the list
,08-30 15:46:27.001  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.001  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.003  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.003  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.003  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.003  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@472d53b removed from the list
,08-30 15:46:27.003  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:46:27.003  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.003  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.003  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.003  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@925efca removed from the list
08-30 15:46:27.003  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
,08-30 15:46:27.003  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:27.004  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:27.004  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f8a17 added. We now have 2 listener(s)
,08-30 15:46:27.006  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:46:27.006  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.006  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:27.006  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:27.007  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1afe04 added. We now have 9 listener(s)
08-30 15:46:27.007  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:27.007  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:46:27.009  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:27.012   372   872 D CommandListener: Setting iface cfg
,08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:27.012  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:27.013  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:46:27.013  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:27.013  4234  4253 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:46:27.014  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:27.014  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:27.015  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:27.015  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e44ae22 added. We now have 3 listener(s)
08-30 15:46:27.015   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 15:46:27.016  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:46:27.018  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:27.018  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:27.019  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.019  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:27.019  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:27.019  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:46:27.019  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.019  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b0b3 added. We now have 10 listener(s)
,08-30 15:46:27.019  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:27.019  4234  4253 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:27.020  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:46:27.021   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 15:46:27.022  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:46:27.023  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:46:27.023  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:46:27.023  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:27.023  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:46:27.024  4234  4250 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:27.024  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.025  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:46:27.025  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:46:27.026   874  4289 D DhcpClient: Receive thread started
08-30 15:46:27.028  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:46:27.028  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:46:27.028  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:46:27.030  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:46:27.030  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:46:27.030  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-30 15:46:27.031  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:27.032  4234  4272 D BtGatt.GattService: registerClient() - UUID=763b23d8-8fb6-4c09-b8d7-39b33ff5ac22
08-30 15:46:27.032  4234  4250 D BtGatt.GattService: onClientRegistered() - UUID=763b23d8-8fb6-4c09-b8d7-39b33ff5ac22, clientIf=5
08-30 15:46:27.033  3868  4151 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 15:46:27.033  4234  4263 D BtGatt.GattService: start scan with filters,
,08-30 15:46:27.034  4234  4253 D BtGatt.ScanManager: handling starting scan
08-30 15:46:27.034  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:46:27.034  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:46:27.034  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:46:27.035  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:46:27.037  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:27.037  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:27.037  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:46:27.039  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 15:46:27.039  4234  4250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:46:27.039  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.039  4234  4253 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:46:27.041  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:46:27.042  3868  3915 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 15:46:27.042  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:27.042  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:27.042  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:27.042  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.042  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 15:46:27.042  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:46:27.042  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.042  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f8a17 removed from the list
08-30 15:46:27.042  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:27.042  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1afe04 removed from the list
08-30 15:46:27.042  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:27.042  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:27.043  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.043  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-30 15:46:27.043  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.043  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:27.043  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:46:27.043  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.043  4234  4253 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 15:46:27.043  4234  4253 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 15:46:27.043  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.044  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.044  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.044  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1afe04 not in the list
08-30 15:46:27.044  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:46:27.044  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:46:27.044  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:46:27.044  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:27.044  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:46:27.044  3868  3915 D BluetoothAdapter: STATE_ON
08-30 15:46:27.045  4234  4245 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:46:27.045  4234  4272 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:46:27.045  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:46:27.045  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:46:27.045  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:46:27.046  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:27.046  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:46:27.046  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:27.046  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:46:27.046  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:46:27.046  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:46:27.047  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.047  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.048  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.048  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.048  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:27.048  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b0b3 removed from the list
08-30 15:46:27.048  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:27.048  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.048  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.048  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryMa,nagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:27.048  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.048  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.048  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e44ae22 removed from the list
08-30 15:46:27.049  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:27.049  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e63a50f added. We now have 2 listener(s)
08-30 15:46:27.050  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:27.050  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.050  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:27.050  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:27.050  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@552099c added. We now have 9 listener(s)
08-30 15:46:27.050  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:27.050  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:46:27.052  4234  4250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:46:27.052  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.052  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:27.054  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:46:27.055  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:46:27.056  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:46:27.056  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:27.056  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@901df7a added. We now have 3 listener(s)
08-30 15:46:27.056  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 15:46:27.056  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:27.056  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.057  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:27.058  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:46:27.058  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.058  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:46:27.058  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:27.059  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3f832b added. We now have 10 listener(s),
08-30 15:46:27.059  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:27.059  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:46:27.059  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 15:46:27.059  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 15:46:27.059  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:27.059  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:46:27.061  3868  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 15:46:27.061  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:46:27.062  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:46:27.062  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:27.062  4234  4253 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:46:27.063  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:46:27.063  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 15:46:27.063  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:46:27.065  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:46:27.065  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:46:27.066  3868  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:46:27.066  3868  3915 D BluetoothAdapter: STATE_ON
,08-30 15:46:27.067  4234  4272 D BtGatt.GattService: registerClient() - UUID=1abbe89d-5ed7-4889-8dcc-ac08380b3e61
08-30 15:46:27.067  4234  4250 D BtGatt.GattService: onClientRegistered() - UUID=1abbe89d-5ed7-4889-8dcc-ac08380b3e61, clientIf=5
08-30 15:46:27.068  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:46:27.068  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:27.068  4234  4253 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:27.068  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 15:46:27.068  4234  4244 D BtGatt.GattService: start scan with filters
,08-30 15:46:27.070  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 15:46:27.070  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 15:46:27.070  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:46:27.070  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 15:46:27.072  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:46:27.072  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:46:27.072  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:46:27.072  4234  4250 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:27.072  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.073  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:46:27.073  4234  4253 D BtGatt.ScanManager: handling starting scan
,08-30 15:46:27.076  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:46:27.076  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:27.076  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:27.076  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.076  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:27.076  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:46:27.076  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.076  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e63a50f removed from the list
,08-30 15:46:27.076  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.076  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@552099c removed from the list
08-30 15:46:27.076  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:27.077  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:27.077  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.077  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 15:46:27.077  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.077  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.078  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@552099c not in the list
,08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:46:27.078  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:46:27.078  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:46:27.078  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:46:27.078  3868  3915 D BluetoothAdapter: STATE_ON
08-30 15:46:27.078  4234  4250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:46:27.079  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:46:27.079  4234  4253 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 15:46:27.079  4234  4244 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:46:27.079  4234  4245 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:46:27.079  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:46:27.079  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:46:27.079  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 15:46:27.080  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:46:27.080  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:46:27.080  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:27.080  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:46:27.080  3868  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:46:27.080  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:46:27.081  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.081  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:46:27.081  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:46:27.081  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:46:27.081  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.082  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.082  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.082  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3f832b removed from the list
08-30 15:46:27.082  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.082  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.082  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.082  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.082  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@901df7a removed from the list
08-30 15:46:27.082  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-30 15:46:27.082  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b12707 added. We now have 2 listener(s)
08-30 15:46:27.083  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:46:27.083  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.083  4234  4253 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:46:27.083  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:27.083  4234  4253 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 15:46:27.084  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.084  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:27.084  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:46:27.084  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bbf034 added. We now have 9 listener(s)
08-30 15:46:27.084  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:46:27.084  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:46:27.086  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:46:27.088  3868  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:46:27.089  3868  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:46:27.090  3868  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:46:27.091  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:46:27.091  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a58e3d2 added. We now have 3 listener(s)
08-30 15:46:27.091  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:27.091  4234  4250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:46:27.091  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.092  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:46:27.093  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:46:27.093  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:46:27.093  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:46:27.093  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:46:27.093  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af2ca3 added. We now have 10 listener(s)
08-30 15:46:27.093  3868  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:46:27.093  3868  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:46:27.093  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:46:27.093  3868  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:46:27.093  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.093  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.093  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:46:27.093  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.094  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b12707 removed from the list
08-30 15:46:27.094  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:27.094  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bbf034 removed from the list
08-30 15:46:27.094  3868  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:46:27.094  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.094  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.094  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.095  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.095  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:46:27.095  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:46:27.095  3868  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bbf034 not in the list
08-30 15:46:27.095  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:46:27.095  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.096  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:46:27.096  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:46:27.096  3868  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:46:27.096  3868  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af2ca3 removed from the list
08-30 15:46:27.096  3868  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:46:27.096  3868  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:46:27.096  3868  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:46:27.096  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:46:27.096  3868  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:46:27.096  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.096  3868  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a58e3d2 removed from the list
08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-30 15:46:27.097  3868  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:46:27.102  3868  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
,08-30 15:46:27.102  3868  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
08-30 15:46:27.102  3868  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:46:27.102  4234  4250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:46:27.102  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.102  4234  4253 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:46:27.103  3868  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
08-30 15:46:27.104  3868  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
,08-30 15:46:27.104  3868  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 15:46:27.105  3868  3915 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 15:46:27.106  3868  3915 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 15:46:27.106  3868  3915 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 15:46:27.106  3868  3915 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 15:46:27.106  3868  3915 D com.test.thalitest.ThaliTestRunner: Total duration: 22818 ms
,08-30 15:46:27.107  3868  3915 I jxcore-log: *Native tests were executed*
08-30 15:46:27.107  3868  3915 I jxcore-log: 
08-30 15:46:27.107   874  1308 E native  : do suspend false
08-30 15:46:27.107  3868  3915 I jxcore-log: Total number of executed tests:  80
08-30 15:46:27.107  3868  3915 I jxcore-log: 
08-30 15:46:27.107  3868  3915 I jxcore-log: Number of passed tests:  80
08-30 15:46:27.107  3868  3915 I jxcore-log: 
08-30 15:46:27.107  4234  4250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:46:27.107  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.108  3868  3915 I jxcore-log: Number of failed tests:  0
08-30 15:46:27.108  3868  3915 I jxcore-log: 
08-30 15:46:27.108  4234  4253 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:46:27.108  3868  3915 I jxcore-log: Number of ignored tests:  0
08-30 15:46:27.108  3868  3915 I jxcore-log: 
,08-30 15:46:27.108  3868  3915 I jxcore-log: Total duration:  22818
08-30 15:46:27.108  3868  3915 I jxcore-log: 
08-30 15:46:27.108  3868  3915 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 15:46:27.108  3868  3915 I jxcore-log: 
,08-30 15:46:27.113  4234  4250 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:46:27.113  4234  4250 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:46:27.116  3868  3868 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 15:46:27.117  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.117  3868  3915 I jxcore-log: 
08-30 15:46:27.117   874  1871 D DhcpClient: Broadcasting DHCPDISCOVER
08-30 15:46:27.118  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.118  3868  3915 I jxcore-log: 
08-30 15:46:27.119  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.119  3868  3915 I jxcore-log: 
08-30 15:46:27.120  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.120  3868  3915 I jxcore-log: 
08-30 15:46:27.120  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.120  3868  3915 I jxcore-log: 
08-30 15:46:27.121  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.121  3868  3915 I jxcore-log: 
,08-30 15:46:27.123  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.123  3868  3915 I jxcore-log: 
,08-30 15:46:27.124  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.124  3868  3915 I jxcore-log: 
08-30 15:46:27.124  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.124  3868  3915 I jxcore-log: 
08-30 15:46:27.124  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.124  3868  3915 I jxcore-log: 
08-30 15:46:27.125  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.125  3868  3915 I jxcore-log: 
08-30 15:46:27.126  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:46:27.126  3868  3915 I jxcore-log: 
,08-30 15:46:27.127  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.127  3868  3915 I jxcore-log: 
08-30 15:46:27.127  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.127  3868  3915 I jxcore-log: 
08-30 15:46:27.128  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.128  3868  3915 I jxcore-log: 
08-30 15:46:27.128  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.128  3868  3915 I jxcore-log: 
,08-30 15:46:27.129  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.129  3868  3915 I jxcore-log: 
,08-30 15:46:27.129  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.129  3868  3915 I jxcore-log: 
08-30 15:46:27.129  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.129  3868  3915 I jxcore-log: 
08-30 15:46:27.130  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.130  3868  3915 I jxcore-log: 
08-30 15:46:27.130  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.130  3868  3915 I jxcore-log: 
,08-30 15:46:27.131  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.131  3868  3915 I jxcore-log: 
08-30 15:46:27.131  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.131  3868  3915 I jxcore-log: 
08-30 15:46:27.132  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.132  3868  3915 I jxcore-log: 
,08-30 15:46:27.132  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.132  3868  3915 I jxcore-log: 
,08-30 15:46:27.133  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:46:27.133  3868  3915 I jxcore-log: 
08-30 15:46:27.133  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.133  3868  3915 I jxcore-log: 
08-30 15:46:27.134  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.134  3868  3915 I jxcore-log: 
08-30 15:46:27.134  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 15:46:27.134  3868  3915 I jxcore-log: 
08-30 15:46:27.134  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.134  3868  3915 I jxcore-log: 
08-30 15:46:27.135  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.135  3868  3915 I jxcore-log: 
,08-30 15:46:27.135  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.135  3868  3915 I jxcore-log: 
,08-30 15:46:27.136  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:46:27.136  3868  3915 I jxcore-log: 
,08-30 15:46:27.139   874  4289 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-30 15:46:27.140   874  1871 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-30 15:46:27.141   874  1871 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 15:46:27.154   874  4289 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 15:46:27.155   874  1871 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 15:46:27.157   372   872 D CommandListener: Setting iface cfg
,08-30 15:46:27.162   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 15:46:27.166   874  1308 E native  : do suspend true
08-30 15:46:27.166   874  1871 D DhcpClient: Scheduling renewal in 86399s
,08-30 15:46:27.179   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 15:46:27.180   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 15:46:27.181   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 15:46:27.184   874  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 15:46:27.184   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:46:27.211   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 15:46:27.211   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 15:46:27.213   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 15:46:27.213   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 15:46:27.214   874  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 15:46:27.220   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 15:46:27.224   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 15:46:27.225   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 15:46:27.225   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 15:46:27.225   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 15:46:27.225   874  1310 D ConnectivityService:    accepting network in place of null
08-30 15:46:27.225   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 15:46:27.226   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:46:27.237   874  4288 D NetlinkSocketObserver: NeighborEvent{elapsedMs=226178, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 15:46:27.244   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:27.261   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:46:27.265   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 15:46:27.267   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:27.269   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 15:46:27.270   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:46:27.280  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:46:27.281  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:46:27.283  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:46:27.283  3868  3915 I jxcore-log: 
,08-30 15:46:27.293  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 15:46:27.296  1720  1720 D SystemUpdateService: onCreate
,08-30 15:46:27.299  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:46:27.306   874  4287 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 15:46:27.323  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 15:46:27.325  1720  2450 I iu.UploadsManager: num queued entries: 0
,08-30 15:46:27.328  1720  4302 I SystemUpdateService: active receiver: enabled
,08-30 15:46:27.333  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:46:27.334  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:46:27.336  4027  4027 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:46:27.341  1720  4304 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 15:46:27.341  1720  4304 W BaseAppContext: Using Auth Proxy for data requests.
08-30 15:46:27.342  4027  4027 D SprintDMHelper: simOperator: 
,08-30 15:46:27.342  4027  4027 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:46:27.356  1720  4304 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:46:27.369  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:46:27.370  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:46:27.373  1720  2450 I iu.UploadsManager: num updated entries: 0
,08-30 15:46:27.373  1720  2450 I iu.SyncManager: NEXT; no task
,08-30 15:46:27.375  1720  4302 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:46:27.376   874  4287 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:46:27 GMT], X-Android-Received-Millis=[1472564787375], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472564787347]}
,08-30 15:46:27.376   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 15:46:27.377   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-30 15:46:27.377   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 15:46:27.378   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 15:46:27.399  1720  4302 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 15:46:27.399  1720  4302 I SystemUpdateService: now status is 0 (complete)
,08-30 15:46:27.400  1720  4302 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 15:46:27.400  1720  4302 I SystemUpdateService: file has been verified
,08-30 15:46:27.400  1720  4302 I SystemUpdateService: OTA package size = 12249756
,08-30 15:46:27.415  1720  4302 I SystemUpdateService: showing system update notification
,08-30 15:46:27.429  1519  2047 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 15:46:27.429  1519  2047 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 15:46:27.429  1519  2047 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 15:46:27.435  1720  1720 D SystemUpdateService: onDestroy
,08-30 15:46:27.441  1519  2047 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:46:27.473  1720  4304 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-30 15:46:27.496  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:46:27.497  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:46:27.497  3868  3915 I jxcore-log: 
,08-30 15:46:27.505  3997  4307 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 15:46:27.529  3916  4313 V GoogleAuthProtoRequest: [331] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:46:27.548  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 15:46:27.549  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:46:27.549  3868  3915 I jxcore-log: 
,08-30 15:46:27.568  1519  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 15:46:27.568  1519  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 15:46:27.568  1519  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:46:27.568  1519  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:46:27.582  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 15:46:27.584  3868  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:46:27.584  3868  3915 I jxcore-log: 
,08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 15:46:27.584  3916  4313 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 15:46:27.756  4292  4292 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 15:46:27.761  4292  4292 D AndroidRuntime: CheckJNI is OFF
,08-30 15:46:27.804  4292  4292 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 15:46:27.851  4292  4292 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 15:46:27.875  4292  4292 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 15:46:27.884   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 15:46:27.884   874   887 I ActivityManager: Killing 3868:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 15:46:28.001   874   897 W PackageSettings: Skipping PackageSetting{fa9dba3 com.example.hello/10273} due to missing metadata
,08-30 15:46:28.018   874  1951 I WindowState: WIN DEATH: Window{9e1edc9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:46:28.019   874  1942 D GraphicsStats: Buffer count: 2
,08-30 15:46:28.019   874  1309 D WifiService: Client connection lost with reason: 4
,08-30 15:46:28.050   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 15:46:28.050   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 15:46:28.051   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-30 15:46:28.051   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 15:46:28.051   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.051   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.051   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 15:46:28.051   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 15:46:28.051   874   887 I ActivityManager:   Force finishing activity ActivityRecord{416847a u0 com.test.thalitest/.MainActivity t2}
,08-30 15:46:28.055   874   897 I art     : Starting a blocking GC Explicit
,08-30 15:46:28.068   874   884 W ActivityManager: Spurious death for ProcessRecord{a3ed4e 0:com.test.thalitest/u0a0}, curProc for 3868: null
,08-30 15:46:28.104   874   897 I art     : Explicit concurrent mark sweep GC freed 51757(3MB) AllocSpace objects, 8(168KB) LOS objects, 33% free, 29MB/43MB, paused 883us total 48.082ms
,08-30 15:46:28.133   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 15:46:28.135  4292  4292 I art     : System.exit called, status: 0
,08-30 15:46:28.135  4292  4292 I AndroidRuntime: VM exiting with result code 0.
,08-30 15:46:28.143   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 15:46:28.161   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 15:46:28.167  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 15:46:28.167  4234  4234 D BluetoothMapAppObserver: onReceive
,08-30 15:46:28.167  4234  4234 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 15:46:28.170  2028  2294 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 15:46:28.174   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 15:46:28.174  3643  3643 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 15:46:28.179  1874  4326 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 15:46:28.189  1874  4326 I Decoder : createOrResetDecoder
,08-30 15:46:28.215   874  1713 I ActivityManager: Start proc 4329:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 15:46:28.218  1945  1945 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 15:46:28.234  1519  1519 I ConfigService: onCreate
,08-30 15:46:28.246  4329  4329 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 15:46:28.267  1874  4326 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 15:46:28.273   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 15:46:28.276   874  1942 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3868 uid 10000
,08-30 15:46:28.278  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-30 15:46:28.303  1960  2045 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 15:46:28.304   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 15:46:28.304   874   886 E PackageManager: Failed to write settings, restoring backup
08-30 15:46:28.304   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 15:46:28.304   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 15:46:28.304   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 15:46:28.304   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 15:46:28.304   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 15:46:28.304   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.304   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.304   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.309   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 15:46:28.309   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 15:46:28.309   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:46:28.309   874   887 E DropBoxManagerService: 	... 13 more
,08-30 15:46:28.312  4329  4329 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 15:46:28.317   874  1996 I ActivityManager: Start proc 4346:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 15:46:28.318  1960  2045 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 15:46:28.318  1960  2045 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1960
08-30 15:46:28.318  1960  2045 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.318  1960  2045 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.320   874  4353 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:46:28.320   874  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:46:28.320   874  4353 E DropBoxManagerService: 	... 5 more
,08-30 15:46:28.321   874  1942 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 15:46:28.327  1874  4326 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 15:46:28.329  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 15:46:28.329  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 15:46:28.331  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 15:46:28.331  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 15:46:28.332  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 15:46:28.332  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 15:46:28.333  1874  4326 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 15:46:28.333  1874  4326 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 15:46:28.333  1874  4326 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 15:46:28.333  1874  4326 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-30 15:46:28.333  1874  4326 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 15:46:28.333  1874  4326 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 15:46:28.334   874   884 I ActivityManager: Start proc 4361:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 15:46:28.339  1960  2045 I Process : Sending signal. PID: 1960 SIG: 9
,08-30 15:46:28.356  4329  4357 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 15:46:28.369  4329  4343 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.369  4329  4343 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
,08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.369  4329  4343 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.383  4361  4361 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 15:46:28.447  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 15:46:28.450  1519  1519 D AndroidRuntime: Shutting down VM
,08-30 15:46:28.451  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
08-30 15:46:28.451  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
08-30 15:46:28.451  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.dat,abase.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 15:46:28.451  1519  1519 E AndroidRuntime: 	... 8 more
08-30 15:46:28.454   874  4379 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:46:28.454   874  4379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:46:28.454   874  4379 E DropBoxManagerService: 	... 5 more
,08-30 15:46:28.458  1519  1519 I Process : Sending signal. PID: 1519 SIG: 9
,08-30 15:46:28.466   874   885 D GraphicsStats: Buffer count: 1
,08-30 15:46:28.466   874  2259 I WindowState: WIN DEATH: Window{f9247 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 15:46:28.483   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1960) has died
,08-30 15:46:28.483   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 15:46:28.484   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 15:46:28.510   874   887 I ActivityManager: Start proc 4380:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 15:46:28.511   874  1997 I ActivityManager: Killing 3697:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 15:46:28.523   874  1309 D WifiService: Client connection lost with reason: 4
,08-30 15:46:28.548  4329  4343 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 15:46:28.554  4329  4357 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.554  4329  4357 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.556  4329  4357 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 15:46:28.556  4329  4357 E AndroidRuntime: Process: android.process.acore, PID: 4329
08-30 15:46:28.556  4329  4357 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.556  4329  4357 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:46:28.558  4329  4343 I Process : Sending signal. PID: 4329 SIG: 9
,08-30 15:46:28.580   874  4392 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:46:28.580   874  4392 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:46:28.580   874  4392 E DropBoxManagerService: 	... 5 more
,08-30 15:46:28.583   874  1951 I ActivityManager: Process com.google.process.gapps (pid 1519) has died
,08-30 15:46:28.584   874  1951 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-30 15:46:28.584   874  1951 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,08-30 15:46:28.584   874  1951 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-30 15:46:28.584   874  1951 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
08-30 15:46:28.587  1720  4378 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@c365e37
,08-30 15:46:28.598  1720  1720 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-30 15:46:28.619   874   885 I ActivityManager: Start proc 4393:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-30 15:46:28.622   874  1997 I ActivityManager: Process android.process.acore (pid 4329) has died
,08-30 15:46:28.622   874  1997 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40962ms
,08-30 15:46:28.633  4380  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:28.633  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:46:28.633  4380  4380 D AndroidRuntime: Shutting down VM
08-30 15:46:28.645  4380  4380 E AndroidRuntime: FATAL EXCEPTION: main
08-30 15:46:28.645  4380  4380 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4380
08-30 15:46:28.645  4380  4380 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 15:46:28.645  4380  4380 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 15:46:28.645  4380  4380 E Andr
```
