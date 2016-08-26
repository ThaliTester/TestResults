#### Test 797638309aa2d44_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,08-26 16:54:33.093   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
08-26 16:54:33.795  3792  3792 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 16:54:33.800  3792  3792 D AndroidRuntime: CheckJNI is OFF
08-26 16:54:33.843  3792  3792 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 16:54:33.893  3792  3792 I Radio-JNI: register_android_hardware_Radio DONE
08-26 16:54:33.914  3792  3792 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 16:54:33.918   873  2003 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 16:54:33.944  2033  2046 W SearchService: Abort, client detached.
08-26 16:54:33.947  2033  2033 I HotwordDetector: Closing mic
08-26 16:54:33.951  2033  2351 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@76fc438
08-26 16:54:33.953  2033  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 16:54:33.962  3792  3792 D AndroidRuntime: Shutting down VM
08-26 16:54:33.991   873   884 I ActivityManager: Start proc 3801:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 16:54:34.001   377  2362 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 16:54:34.003   377  2362 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 16:54:34.011   377  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 16:54:34.012  2033  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 16:54:34.012  2033  2356 I MicroRecognitionRnrImpl: Detection finished
08-26 16:54:34.053  3801  3801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 16:54:34.077  3801  3801 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 16:54:34.083  3801  3801 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7340-7343)
08-26 16:54:34.083  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 16:54:34.095  3801  3801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {df2825}
08-26 16:54:34.095  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 16:54:34.095  3801  3801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 16:54:34.101  3801  3801 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 16:54:34.102  3801  3801 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 16:54:34.111  3801  3801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 16:54:34.121  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 16:54:34.121  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 16:54:34.121  3801  3801 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 16:54:34.121  3801  3801 I Adreno  : Build Date                       : 10/20/15
08-26 16:54:34.121  3801  3801 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 16:54:34.121  3801  3801 I Adreno  : Local Branch                     : M14
08-26 16:54:34.121  3801  3801 I Adreno  : Remote Branch                    : 
08-26 16:54:34.121  3801  3801 I Adreno  : Remote Branch                    : 
08-26 16:54:34.121  3801  3801 I Adreno  : Reconstruct Branch               : 
08-26 16:54:34.168   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f633731:true
,08-26 16:54:34.230  3801  3801 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 16:54:34.241  3801  3801 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-26 16:54:34.303  3801  3839 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-26 16:54:34.317  3801  3826 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-26 16:54:34.360  3801  3839 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 16:54:34.426   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms
08-26 16:54:34.433  1880  1880 I Keyboard.Facilitator: onFinishInput()
08-26 16:54:34.451  3801  3801 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3801
08-26 16:54:34.557  3801  3801 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 16:54:34.776   873  2097 I ActivityManager: Killing 2983:com.google.android.calendar/u0a37 (adj 15): empty #17
08-26 16:54:34.786  3801  3840 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1657800400
08-26 16:54:34.790  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 16:54:34.790  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 16:54:34.790  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 16:54:34.790  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 16:54:34.790  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 16:54:34.791  3801  3840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c731199 added. We now have 1 listener(s)
08-26 16:54:34.793  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-26 16:54:34.794  3801  3840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:54:34.794  3801  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:54:34.795  3801  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 16:54:34.798  3801  3840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d00f50c added. We now have 1 listener(s)
08-26 16:54:34.798  3801  3840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:54:34.800   873  1317 D WifiService: New client listening to asynchronous messages
08-26 16:54:34.801  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:54:34.801  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 16:54:34.801  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 16:54:34.802  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 16:54:34.802  3801  3840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 16:54:34.813   873  2097 I ActivityManager: Killing 3201:com.google.android.gm/u0a78 (adj 15): empty #18
08-26 16:54:34.862  3801  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:34.862  3801  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-26 16:54:34.869  3801  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:34.870  3801  3840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:34.870  3801  3840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 16:54:34.870  3801  3840 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:34.871  3801  3840 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 16:54:34.872  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:34.874  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:34.893  3801  3801 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 16:54:35.625  3801  3850 W jxcore-log: Initializing JXcore engine
08-26 16:54:35.625  3801  3850 W jxcore-log: JXcore engine is ready
08-26 16:54:35.662  3850  3850 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-26 16:54:35.662  3850  3850 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10019]" dev="sockfs" ino=10019 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 16:54:35.662  3850  3850 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 16:54:35.662  3850  3850 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27706]" dev="sockfs" ino=27706 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-26 16:54:35.676  3801  3850 W jxcore-log: Starting JXcore engine
08-26 16:54:35.755  3801  3850 W jxcore-log: Platform android
08-26 16:54:35.755  3801  3850 W jxcore-log: 
08-26 16:54:35.755  3801  3850 W jxcore-log: Process ARCH arm
08-26 16:54:35.755  3801  3850 W jxcore-log: 
08-26 16:54:35.940  3801  3850 I jxcore-log: JXcore Cordova bridge is ready!
08-26 16:54:35.940  3801  3850 I jxcore-log: 
08-26 16:54:35.941  3801  3850 W jxcore-log: JXcore engine is started
08-26 16:54:35.951  3801  3840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 16:54:35.967  3801  3801 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 16:54:39.244   873  1906 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 16:54:39.529   873  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 16:54:43.230  3044  3859 V KeepSync: Connecting to GoogleApiClient
,08-26 16:54:43.230   873  2098 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 16:54:43.272  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 16:54:43.274  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 16:54:43.300  1511  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 16:54:43.300  1511  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 16:54:43.300  1511  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 16:54:43.300  1511  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:43.313  1719  3860 V BaseAuthAsyncOperation: access token request failed
,08-26 16:54:43.314  3044  3859 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 16:54:43.356  1511  2998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 16:54:43.356  1511  2998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 16:54:43.356  1511  2998 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 16:54:43.356  1511  2998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:43.371  3044  3859 E KeepSync: IOException
08-26 16:54:43.371  3044  3859 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 16:54:43.371  3044  3859 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 16:54:43.371  3044  3859 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 16:54:43.371  3044  3859 E KeepSync: 	... 10 more
,08-26 16:54:43.371  3044  3859 W KeepSync: Sync result 2
,08-26 16:54:43.374   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 125729, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-26 16:54:44.548  3570  3863 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 16:54:44.567  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-26 16:54:44.567  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-26 16:54:44.567  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:54:44.567  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:44.580  3570  3863 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-26 16:54:44.581  3570  3863 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-26 16:54:44.671  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 16:54:44.683  1511  3865 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-26 16:54:44.685  1511  3865 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 16:54:44.692  1511  2998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 16:54:44.693  1511  2998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 16:54:44.693  1511  2998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:54:44.693  1511  2998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:44.706  3495  3495 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 16:54:44.706  3495  3495 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 16:54:44.706  3495  3495 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-26 16:54:44.707  1511  3865 W Uploader:  no longer exists, so no auth token.
,08-26 16:54:45.791  1511  3865 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-26 16:54:45.791  1511  3865 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 16:54:45.792  1511  3865 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:54:45.792  1511  3865 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:45.816  1511  3865 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 16:54:45.816  1511  3865 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 16:54:45.816  1511  3865 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 16:54:46.090  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 16:54:46.090  3801  3850 I jxcore-log: 
,08-26 16:54:46.092  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 16:54:46.092  3801  3850 I jxcore-log: 
,08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:46.102  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:46.107  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:46.109  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 16:54:46.109  3801  3850 I jxcore-log: 
,08-26 16:54:46.111  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 16:54:46.111  3801  3850 I jxcore-log: 
,08-26 16:54:46.524  1511  3865 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-26 16:54:46.525  1511  3865 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 16:54:46.525  1511  3865 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 16:54:46.525  1511  3865 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:46.542  1511  3865 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 16:54:46.542  1511  3865 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 16:54:46.542  1511  3865 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 16:54:46.673  3801  3850 D executeNativeTests: Running unit tests
,08-26 16:54:46.736  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:54:46.736  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 added. We now have 2 listener(s)
,08-26 16:54:46.737  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:54:46.738  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:54:46.738  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:54:46.738  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:46.738  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae added. We now have 2 listener(s)
08-26 16:54:46.738  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:46.742  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 16:54:46.744  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:46.753  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:46.757  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.757  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:46.760  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 16:54:46.761  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 16:54:46.763  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 16:54:46.765  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:46.770  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:46.773  3801  3850 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 16:54:46.774  3801  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 16:54:46.774  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:46.774  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 16:54:46.774  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:46.775  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.775  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.775  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:54:46.776  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.776  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.776  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:46.776  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:54:46.776  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 removed from the list
,08-26 16:54:46.776  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.776  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae removed from the list
,08-26 16:54:46.776  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.777  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.777  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.777  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.778  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:46.778  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.778  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.778  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.780  3801  3850 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 16:54:46.780  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.780  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:54:46.780  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.781  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.781  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.781  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.781  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.781  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.781  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.781  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:54:46.781  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.781  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.781  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.781  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.782  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:46.782  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.782  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.782  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list,
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 16:54:46.788  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 16:54:46.789  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 16:54:46.790  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 16:54:46.790  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 16:54:46.790  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-26 16:54:46.790  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 16:54:46.790  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 16:54:46.790  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.790  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.790  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.790  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 16:54:46.790  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.790  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.790  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.790  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.790  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.791  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.791  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.791  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.791  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.791  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.793  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.793  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.793  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.793  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.794  3801  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 16:54:46.795  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:46.798  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:46.799  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:46.800  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:46.800  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:54:46.800  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:54:46.800  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 16:54:46.800  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:46.800  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:54:46.803  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 16:54:46.803  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 16:54:46.804  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:46.814  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:46.815  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:54:46.817  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 16:54:46.817  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:54:46.819  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 16:54:46.821  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 16:54:46.821  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 16:54:46.821  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 16:54:46.822  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 16:54:46.822  3801  3850 D BluetoothAdapter: STATE_ON
,08-26 16:54:46.826  2691  2704 D BtGatt.GattService: registerClient() - UUID=75f86688-bad4-435e-ad40-6857a9141579
,08-26 16:54:46.827  2691  2711 D BtGatt.GattService: onClientRegistered() - UUID=75f86688-bad4-435e-ad40-6857a9141579, clientIf=5
08-26 16:54:46.828  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 16:54:46.829  2691  2813 D BtGatt.GattService: start scan with filters
,08-26 16:54:46.833  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 16:54:46.833  2691  2714 D BtGatt.ScanManager: handling starting scan
08-26 16:54:46.833  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 16:54:46.834  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 16:54:46.834  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 16:54:46.834  2691  2714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
08-26 16:54:46.836  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 16:54:46.837  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 16:54:46.837  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:54:46.839  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:54:46.841  3801  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 16:54:46.843  2691  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 16:54:46.843  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.843  2691  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 16:54:46.845  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.845  3801  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 16:54:46.845  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.845  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 16:54:46.845  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.845  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 16:54:46.845  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 16:54:46.845  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:54:46.845  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 16:54:46.845  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 16:54:46.846  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:54:46.846  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 16:54:46.847  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:54:46.848  2691  2832 D BtGatt.GattService: stopScan() - queue size =1
08-26 16:54:46.848  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 16:54:46.848  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.848  2691  2813 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 16:54:46.848  2691  2714 D BtGatt.ScanManager: Starting BLE batch scan
08-26 16:54:46.849  2691  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 16:54:46.849  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:46.849  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 16:54:46.849  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 16:54:46.849  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 16:54:46.849  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 16:54:46.851  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:54:46.852  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 16:54:46.852  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:54:46.852  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:54:46.853  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:54:46.855  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:54:46.855  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:54:46.855  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:46.856  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.856  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.856  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:46.856  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.856  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.856  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.856  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.856  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.857  3801  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 16:54:46.859  2691  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 16:54:46.859  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.858  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:46.863  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:46.863  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:46.863  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.866  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:46.866  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:54:46.867  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:54:46.867  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 16:54:46.867  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 16:54:46.868  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:46.867  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:46.868  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 16:54:46.869  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 16:54:46.869  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.869  2691  2714 D BtGatt.ScanManager: stopping BLe Batch
,08-26 16:54:46.870  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:46.870  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 16:54:46.871  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 16:54:46.873  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:54:46.873  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 16:54:46.873  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 16:54:46.874  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 16:54:46.874  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.874  2691  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 16:54:46.876  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 16:54:46.876  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 16:54:46.876  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 16:54:46.877  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:54:46.878  2691  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 16:54:46.878  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.878  2691  2704 D BtGatt.GattService: registerClient() - UUID=7db5cf3d-a67f-4ce1-9340-ac9a4b69ada6
,08-26 16:54:46.878  2691  2711 D BtGatt.GattService: onClientRegistered() - UUID=7db5cf3d-a67f-4ce1-9340-ac9a4b69ada6, clientIf=5
08-26 16:54:46.879  3801  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 16:54:46.879  2691  2832 D BtGatt.GattService: start scan with filters
,08-26 16:54:46.880  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 16:54:46.880  2691  2714 D BtGatt.ScanManager: handling starting scan
08-26 16:54:46.880  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 16:54:46.880  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 16:54:46.881  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 16:54:46.882  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:54:46.882  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 16:54:46.882  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:54:46.883  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:54:46.884  2691  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 16:54:46.884  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.885  2691  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 16:54:46.885  3801  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 16:54:46.887  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.887  3801  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 16:54:46.887  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:54:46.887  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 16:54:46.887  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.887  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 16:54:46.887  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 16:54:46.887  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:54:46.887  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-26 16:54:46.887  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 16:54:46.887  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 16:54:46.887  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 16:54:46.888  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:54:46.888  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 16:54:46.888  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.888  2691  2704 D BtGatt.GattService: stopScan() - queue size =1
08-26 16:54:46.888  2691  2714 D BtGatt.ScanManager: Starting BLE batch scan
08-26 16:54:46.888  2691  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 16:54:46.889  2691  2832 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 16:54:46.889  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:46.889  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 16:54:46.889  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 16:54:46.889  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 16:54:46.889  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 16:54:46.890  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:46.890  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 16:54:46.890  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-26 16:54:46.890  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:54:46.890  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:54:46.891  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:46.891  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:46.891  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:54:46.891  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.892  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.892  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:46.892  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.892  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.892  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.892  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.892  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 16:54:46.892  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.892  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 16:54:46.893  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.893  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:54:46.893  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.893  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.894  3801  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 16:54:46.895  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:46.895  2691  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 16:54:46.895  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:46.898  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:46.899  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 16:54:46.899  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.899  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:46.899  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:46.900  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:54:46.900  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:54:46.900  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 16:54:46.900  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:46.900  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 16:54:46.902  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:46.903  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 16:54:46.903  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-26 16:54:46.903  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 16:54:46.903  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.903  2691  2714 D BtGatt.ScanManager: stopping BLe Batch
08-26 16:54:46.904  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:46.905  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:54:46.906  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 16:54:46.906  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:54:46.908  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 16:54:46.908  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.908  2691  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 16:54:46.908  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 16:54:46.908  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 16:54:46.908  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 16:54:46.909  3801  3850 D BluetoothAdapter: STATE_ON
,08-26 16:54:46.910  2691  2832 D BtGatt.GattService: registerClient() - UUID=15d024b0-9fd1-48fc-804c-5b28c4e7d346
,08-26 16:54:46.911  2691  2711 D BtGatt.GattService: onClientRegistered() - UUID=15d024b0-9fd1-48fc-804c-5b28c4e7d346, clientIf=5
08-26 16:54:46.911  3801  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 16:54:46.911  2691  2702 D BtGatt.GattService: start scan with filters,
08-26 16:54:46.911  2691  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 16:54:46.911  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.913  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 16:54:46.913  2691  2714 D BtGatt.ScanManager: handling starting scan
08-26 16:54:46.913  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 16:54:46.913  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 16:54:46.913  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 16:54:46.915  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:54:46.916  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:54:46.916  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 16:54:46.916  2691  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 16:54:46.916  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.917  2691  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 16:54:46.918  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:54:46.920  3801  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 16:54:46.921  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.921  3801  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 16:54:46.921  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:54:46.921  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 16:54:46.921  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.921  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 16:54:46.921  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 16:54:46.921  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 16:54:46.921  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 16:54:46.921  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 16:54:46.921  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:54:46.921  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 16:54:46.922  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 16:54:46.922  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.922  2691  2714 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 16:54:46.922  2691  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 16:54:46.922  3801  3850 D BluetoothAdapter: STATE_ON
,08-26 16:54:46.923  2691  2702 D BtGatt.GattService: stopScan() - queue size =1
08-26 16:54:46.923  2691  2704 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 16:54:46.924  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 16:54:46.924  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 16:54:46.924  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 16:54:46.924  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 16:54:46.924  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 16:54:46.925  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:46.925  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 16:54:46.925  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:54:46.925  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 16:54:46.926  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:46.926  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:46.927  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:54:46.927  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:46.927  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.927  3801  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 16:54:46.927  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.927  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.927  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:54:46.927  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.927  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:46.928  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.928  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.928  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.928  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:54:46.928  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.928  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.928  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.929  2691  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 16:54:46.929  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.930  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:46.931  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.931  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.931  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.931  3801  3850 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 16:54:46.931  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.931  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.931  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 16:54:46.932  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.932  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.932  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.932  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.932  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.932  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.932  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:54:46.932  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.932  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.932  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.932  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.933  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.933  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.933  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.933  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.933  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 16:54:46.934  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.934  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.934  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:54:46.934  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.934  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.934  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.934  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 16:54:46.934  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:54:46.934  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
,08-26 16:54:46.934  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.934  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.934  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.934  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.934  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.934  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.935  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.935  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.935  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:54:46.935  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.936  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.936  3801  3850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 16:54:46.936  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.936  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.937  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.937  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:54:46.937  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.937  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.937  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.937  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.937  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.937  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.937  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.937  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.938  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.938  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.938  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.939  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.939  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.939  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.939  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 16:54:46.939  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.940  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.940  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.940  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.940  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.940  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.940  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
,08-26 16:54:46.940  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.940  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.940  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.940  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.940  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.941  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.941  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.941  2691  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 16:54:46.941  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.941  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.941  2691  2714 D BtGatt.ScanManager: stopping BLe Batch
08-26 16:54:46.941  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.941  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.942  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.942  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 16:54:46.943  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:46.943  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:46.943  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:46.943  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 16:54:46.943  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:46.943  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.944  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:54:46.944  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.944  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.944  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.944  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.944  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.944  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.944  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.944  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.944  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.944  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.944  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.944  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.945  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.945  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.945  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.945  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.946  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:46.946  3801  3850 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 16:54:46.946  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 16:54:46.948  2691  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 16:54:46.948  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.948  2691  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 16:54:46.949  1511  3865 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-26 16:54:46.949  1511  3865 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 16:54:46.949  1511  3865 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:54:46.949  1511  3865 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 16:54:46.954  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:46.954  3801  3850 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 16:54:46.954  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 16:54:46.955  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 16:54:46.955  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 16:54:46.955  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 16:54:46.955  2691  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 16:54:46.955  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 16:54:46.955  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 16:54:46.955  2691  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-26 16:54:46.956  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 16:54:46.957  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 16:54:46.957  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 16:54:46.957  3801  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 16:54:46.957  3801  3850 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 16:54:46.957  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:46.957  3801  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 16:54:46.957  3801  3850 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 16:54:46.957  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:46.957  3801  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 16:54:46.957  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-26 16:54:46.960  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 16:54:46.960  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 16:54:46.960  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 16:54:46.961  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 16:54:46.961  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 16:54:46.961  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-26 16:54:46.961  3801  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:46.961  3801  3850 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 16:54:46.961  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.961  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.961  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.962  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.962  3801  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-26 16:54:46.962  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.962  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.962  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 16:54:46.963  1511  3865 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 16:54:46.963  1511  3865 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 16:54:46.963  1511  3865 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-26 16:54:46.963  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.963  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.963  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.963  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.963  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.963  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.963  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.963  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.964  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.964  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:54:46.964  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.964  3801  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:54:46.964  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.965  3801  3850 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 16:54:46.965  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.965  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.965  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.965  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:54:46.965  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.965  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.965  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.965  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.965  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.966  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.966  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.966  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.966  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.966  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.966  3801  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-26 16:54:46.966  3801  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
08-26 16:54:46.967  3801  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-26 16:54:46.968  2691  2803 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 16:54:46.968  3801  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
08-26 16:54:46.970  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.970  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:54:46.970  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.970  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.971  3801  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 16:54:46.971  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.971  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.971  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.971  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.971  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.971  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.971  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.971  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.971  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.971  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.971  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.971  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.971  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.971  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.972  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:46.972  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.972  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.972  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.973  3801  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 16:54:46.973  3801  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 16:54:46.973  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 16:54:46.974  3801  3850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 16:54:46.974  3801  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 16:54:46.974  3801  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 16:54:46.974  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:46.974  3801  3850 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 16:54:46.974  3801  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-26 16:54:46.974  3801  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 16:54:46.975  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:46.975  3801  3850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 16:54:46.975  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.975  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.975  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.975  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:54:46.975  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.975  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.975  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.975  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.976  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.976  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.976  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.976  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.976  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.976  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.977  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.977  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.977  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.977  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.977  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.977  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.977  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.977  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.978  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.978  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.978  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.978  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.978  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.978  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.978  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.978  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.978  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.978  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.978  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
,08-26 16:54:46.978  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.978  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.978  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.978  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.978  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.978  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.978  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.979  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.979  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.979  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.979  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.979  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.979  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.979  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.980  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.980  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.980  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.980  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.981  3801  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 16:54:46.981  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:46.982  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 16:54:46.982  3801  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 16:54:46.982  3801  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 16:54:46.983  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 16:54:46.983  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 16:54:46.983  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 16:54:46.983  3801  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:54:46.983  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.983  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-26 16:54:46.983  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 16:54:46.983  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 16:54:46.983  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.984  3801  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-26 16:54:46.984  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.984  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 16:54:46.984  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.984  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 16:54:46.984  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 16:54:46.984  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 16:54:46.984  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.984  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.984  3801  3879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 16:54:46.984  3801  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 16:54:46.985  3801  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 16:54:46.985  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:54:46.985  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.985  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:46.985  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.985  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:46.985  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.985  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.985  3801  3801 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-26 16:54:46.985  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.985  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:46.985  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.985  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.985  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
,08-26 16:54:46.985  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.985  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.986  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.986  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.986  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.986  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.986  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.987  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.987  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.987  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.987  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.988  3801  3850 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 16:54:46.988  3801  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 16:54:46.988  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:46.988  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:46.988  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.988  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:54:46.988  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.988  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.988  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.988  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.988  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.989  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.989  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.989  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.989  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.989  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.989  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.989  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.990  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:46.990  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.990  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.990  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.992  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:46.992  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.993  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.993  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:54:46.993  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.993  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.993  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
08-26 16:54:46.993  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.993  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
,08-26 16:54:46.993  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.993  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.993  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.993  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:46.993  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.994  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.994  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.994  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.994  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.995  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:46.995  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:46.995  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:46.995  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:46.995  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.995  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.995  3801  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d029 not in the list
,08-26 16:54:46.995  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:46.995  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.995  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:46.995  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.995  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:46.995  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:46.996  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:46.996  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:46.996  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:46.996  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:46.996  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0b4fae not in the list
08-26 16:54:46.997  3801  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 16:54:46.997  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 16:54:46.997  3801  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 16:54:46.997  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 16:54:46.997  3801  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-26 16:54:46.997  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:46.999  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 16:54:46.999  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 16:54:47.000  3801  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 16:54:47.000  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 16:54:47.000  3801  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 16:54:47.000  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 16:54:47.000  3801  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 16:54:47.000  3801  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 16:54:47.000  3801  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 16:54:47.001  3801  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 16:54:47.001  3801  3850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-26 16:54:47.001  3801  3850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 16:54:47.001  3801  3850 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 16:54:47.001  3801  3850 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 16:54:47.002  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:47.002  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a299ee0 added. We now have 2 listener(s)
08-26 16:54:47.002  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:47.004  3801  3850 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 16:54:47.004   873  2098 D WifiService: setWifiEnabled: true pid=3801, uid=10000
08-26 16:54:47.004   873  2098 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 16:54:47.005  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:47.005  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3611599 added. We now have 3 listener(s)
08-26 16:54:47.005  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:47.008  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:54:47.008  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@241005e added. We now have 4 listener(s)
08-26 16:54:47.008  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:47.009  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:54:47.009  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7dfc3f added. We now have 5 listener(s)
08-26 16:54:47.010  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:47.011   873  1400 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-26 16:54:47.011   873  1400 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:47.014  2691  2707 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 16:54:47.014  2691  2707 D BluetoothAdapterProperties: Setting state to 13
,08-26 16:54:47.014  2691  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 16:54:47.015  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:47.015  2691  2707 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 16:54:47.016  2691  2707 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:54:47.017  2691  2691 D BluetoothMapService: onReceive
08-26 16:54:47.017  2691  2691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 16:54:47.017  2691  2691 D BluetoothMapService: STATE_TURNING_OFF
08-26 16:54:47.017  2691  2691 D BluetoothMapService: MAP Service closeService in
08-26 16:54:47.017  2691  2691 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 16:54:47.017  2691  2691 D ObexServerSockets0: shutdown(block = true)
,08-26 16:54:47.017  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 16:54:47.018  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 16:54:47.018  2691  2833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 16:54:47.018  2691  2803 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-26 16:54:47.018  2691  2834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-26 16:54:47.018  2691  2691 I BtOppRfcommListener: stopping Accept Thread
08-26 16:54:47.019  2691  3414 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:47.019  2691  3414 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 16:54:47.020  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:47.020  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:47.020  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 16:54:47.021  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:47.021  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:47.021  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:54:47.022   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 16:54:47.022   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 16:54:47.022   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 16:54:47.022   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:54:47.023  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:47.025  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:47.028  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:47.028  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:47.028  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.028  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:47.029   873   886 I ActivityManager: Start proc 3882:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 16:54:47.029  2691  2711 D BluetoothAdapterProperties: Scan Mode:20
,08-26 16:54:47.029  2691  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 16:54:47.031  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:47.031  2691  2691 D HeadsetService: Received stop request...Stopping profile...
08-26 16:54:47.032   873  1908 D DhcpClient: Clearing IP address,
08-26 16:54:47.032   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:47.034  1965  2290 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:47.034   373   871 D CommandListener: Setting iface cfg,
08-26 16:54:47.035   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:47.035  1373  2072 D BluetoothHeadset: Proxy object disconnected
,08-26 16:54:47.035   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:47.035   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:47.036  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:47.036  1511  2496 V NativeCrypto: Read error: ssl=0x9aec7200: I/O error during system call, Connection timed out
08-26 16:54:47.037  1511  2496 V NativeCrypto: SSL shutdown failed: ssl=0x9aec7200: I/O error during system call, Broken pipe
08-26 16:54:47.039   873  1401 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-26 16:54:47.039   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 16:54:47.040   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 16:54:47.040   873  1886 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-26 16:54:47.040  1511  3865 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
08-26 16:54:47.041  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:47.041   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-26 16:54:47.041   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 16:54:47.043  2691  2691 D A2dpService: Received stop request...Stopping profile...
08-26 16:54:47.043  2691  2815 D A2dpStateMachine: Exit Disconnected: -1
,08-26 16:54:47.045   396   396 E Parcel  : Reading a NULL string not supported here.
08-26 16:54:47.047   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 16:54:47.049  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-26 16:54:47.049   873   873 D BluetoothA2dp: Proxy object disconnected
08-26 16:54:47.050  2691  2691 D HidService: Received stop request...Stopping profile...
,08-26 16:54:47.050  2691  2691 D HidService: Stopping Bluetooth HidService
08-26 16:54:47.051   873  1886 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-26 16:54:47.053  2691  2691 D HealthService: Received stop request...Stopping profile...
08-26 16:54:47.054  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:47.054  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-26 16:54:47.055  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:47.055  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:47.055  1373  1373 D BluetoothA2dp: Proxy object disconnected
,08-26 16:54:47.055  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-26 16:54:47.055  1373  1373 D HidProfile: Bluetooth service disconnected
,08-26 16:54:47.056  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 16:54:47.056  2691  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008,
,08-26 16:54:47.056  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 16:54:47.056  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 16:54:47.056  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:47.056  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:54:47.056  2691  2711 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
08-26 16:54:47.057  2691  2691 D PanService: Received stop request...Stopping profile...
08-26 16:54:47.058  2691  2691 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 16:54:47.058  2691  2691 D BluetoothMapService: stop()
08-26 16:54:47.059  2691  2691 D BluetoothMapAppObserver: deinitObservers()
08-26 16:54:47.059  2691  2691 D BluetoothMapAppObserver: removeReceiver(),
08-26 16:54:47.060  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:47.061  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-26 16:54:47.061  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:47.061  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:54:47.063  2691  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 16:54:47.063  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 16:54:47.063  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:47.063  2691  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:47.063  2691  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:47.063  2691  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 16:54:47.063  2691  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:47.063   873  1910 D DhcpClient: Receive thread stopped
08-26 16:54:47.064  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-26 16:54:47.064  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:47.064  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:47.064  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:54:47.064  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 16:54:47.064  2691  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 16:54:47.065  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 16:54:47.065  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:47.065  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:47.065  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:47.065  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:47.065  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 16:54:47.065  2691  2711 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 16:54:47.065  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:54:47.066  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:47.066  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-26 16:54:47.066  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:47.066  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:47.066  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-26 16:54:47.066  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 16:54:47.067  2691  2691 D BluetoothMapService: MAP Service closeService in
08-26 16:54:47.067  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-26 16:54:47.067  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:47.067  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:47.067  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:54:47.067  2691  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 16:54:47.067  2691  2707 D BluetoothAdapterProperties: Setting state to 15
08-26 16:54:47.067  2691  2691 D BluetoothMapService: cleanup()
,08-26 16:54:47.067  2691  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 16:54:47.067  2691  2691 D BluetoothMapService: MAP Service closeService in
08-26 16:54:47.068  1373  1385 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 16:54:47.068  2691  2707 I BluetoothAdapterState: Entering BleOnState
08-26 16:54:47.068   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 16:54:47.068  1373  1391 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:54:47.069  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 16:54:47.069   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-26 16:54:47.069  1965  2164 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:47.070  1373  2072 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:47.070  1373  1391 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 16:54:47.070   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:47.071   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:47.071  1373  1385 D BluetoothPan: onBluetoothStateChange on: false
,08-26 16:54:47.071  2691  2707 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 16:54:47.071  2691  2707 D BluetoothAdapterProperties: Setting state to 16
,08-26 16:54:47.071  2691  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 16:54:47.072  2691  2707 D BluetoothAdapterProperties: onBleDisable
,08-26 16:54:47.072  2691  2707 I BluetoothAdapterState: Entering PendingCommandState
08-26 16:54:47.072  2691  2708 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 16:54:47.073  2691  2789 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 16:54:47.073  2691  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 16:54:47.073  2691  2711 D BluetoothAdapterProperties: Scan Mode:20
08-26 16:54:47.076  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:47.076  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:47.076  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:47.076  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:47.079  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:47.079  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:54:47.079  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.079  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:47.080  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:47.082  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:47.097   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 16:54:47.116   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:54:47.116   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:47.117   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 16:54:47.117   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:47.118   873   890 D Tethering: MasterInitialState.processMessage what=3
08-26 16:54:47.121  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:47.122   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 16:54:47.122  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:47.123  3404  3404 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c731199 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 16:54:47.125  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:47.126  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:47.126  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.126  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:47.127   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 16:54:47.128  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:47.128  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:47.128  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:47.128  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:47.129  1894  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:47.130  3882  3882 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 16:54:47.142  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 16:54:47.147  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:54:47.149   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cae3e46:true
,08-26 16:54:47.159   873  2289 I ActivityManager: Start proc 3903:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 16:54:47.173   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-26 16:54:47.174   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 16:54:47.181  3882  3882 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 16:54:47.183  3882  3882 D BluetoothMap: Create BluetoothMap proxy object
,08-26 16:54:47.193  3903  3903 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 16:54:47.195  3882  3882 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 16:54:47.212  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:54:47.214   873  1696 I ActivityManager: Killing 3404:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 16:54:47.275  2691  2711 I bt_hci  : shut_down
,08-26 16:54:47.275  2691  2715 D bt_hwcfg: hw_epilog_process
,08-26 16:54:47.278  2691  2715 I bt_vendor: low_power_mode_cb
,08-26 16:54:47.298  2691  2715 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 16:54:47.298  2691  2715 I bt_vendor: epilog_cb
,08-26 16:54:47.298  2691  2715 I bt_hci  : epilog_finished_callback
,08-26 16:54:47.300  2691  2711 I bt_hci_h4: hal_close
,08-26 16:54:47.301  2691  2711 I bt_userial_vendor: device fd = 51 close
,08-26 16:54:47.394  3903  3903 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.394  3903  3903 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.394  3903  3903 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.394  3903  3903 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.394  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.395  3903  3903 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.395  3903  3903 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.395  3903  3903 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.395  3903  3903 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:54:47.395  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:54:47.408  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 16:54:47.415  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:54:47.427  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:54:47.436   873  2003 I ActivityManager: Killing 3448:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 16:54:47.486  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 16:54:47.501  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 16:54:47.513  1719  1719 D SystemUpdateService: onCreate
,08-26 16:54:47.526  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 16:54:47.531  2691  2708 D bt_stack_manager: event_shut_down_stack finished.
08-26 16:54:47.532  2691  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 16:54:47.539  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 16:54:47.539  2691  2707 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 16:54:47.540  2691  2691 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 16:54:47.541  2691  2691 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 16:54:47.541  2691  2691 D BtGatt.GattService: stop()
08-26 16:54:47.541  2691  2691 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 16:54:47.545  2691  2691 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:54:47.545  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:47.546  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:47.546  2691  2691 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 16:54:47.547  2691  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 16:54:47.547  2691  2707 D BluetoothAdapterProperties: Setting state to 10
08-26 16:54:47.547  2691  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 16:54:47.548  2691  2707 I BluetoothAdapterState: Entering OffState
,08-26 16:54:47.550   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 16:54:47.551  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 16:54:47.552  1719  3936 I SystemUpdateService: active receiver: enabled
,08-26 16:54:47.554  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 16:54:47.556  1719  2459 I iu.UploadsManager: num queued entries: 0
,08-26 16:54:47.558  1719  2459 I iu.UploadsManager: num updated entries: 0
,08-26 16:54:47.562  1719  3936 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 16:54:47.564  1719  2459 I iu.SyncManager: NEXT; no task
,08-26 16:54:47.565  1719  3936 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 16:54:47.565  1719  3936 I SystemUpdateService: now status is 0 (complete)
08-26 16:54:47.565  1719  3936 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 16:54:47.565  1719  3936 I SystemUpdateService: file has been verified
,08-26 16:54:47.565  1719  3936 I SystemUpdateService: OTA package size = 12249756
,08-26 16:54:47.576  1719  3936 I SystemUpdateService: showing system update notification
,08-26 16:54:47.584   873  1401 I ActivityManager: Start proc 3938:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 16:54:47.589  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 16:54:47.589  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 16:54:47.589  2691  2691 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 16:54:47.590  2691  2708 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 16:54:47.592  2691  2708 D bt_stack_manager: event_clean_up_stack finished.
,08-26 16:54:47.601  2691  2691 I art     : System.exit called, status: 0
,08-26 16:54:47.601  2691  2691 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 16:54:47.630  3938  3938 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 16:54:47.632  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:47.640  3938  3938 D SprintDMHelper: simOperator: 
08-26 16:54:47.640  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 16:54:47.689   873  1986 I ActivityManager: Start proc 3953:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 16:54:47.694   873   884 I ActivityManager: Process com.android.bluetooth (pid 2691) has died
08-26 16:54:47.695  1719  1719 D SystemUpdateService: onDestroy
,08-26 16:54:47.724  3903  3924 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 16:54:47.806   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0e2983:true
,08-26 16:54:47.824  2213  3968 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 16:54:47.850   873   884 I ActivityManager: Start proc 3969:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 16:54:47.862   873   884 I ActivityManager: Killing 1697:android.process.acore/u0a5 (adj 15): empty #17
,08-26 16:54:47.922  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 16:54:47.979  3969  3969 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 16:54:47.979  3969  3969 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 16:54:47.979  3969  3969 I GAv4    :   adb logcat -s GAv4
,08-26 16:54:47.997  3969  3969 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 16:54:48.004  3969  3969 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 16:54:48.037  3969  3986 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 16:54:48.145  3969  3969 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 16:54:48.182  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 16:54:48.199  3969  3969 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 1449-1458)
08-26 16:54:48.199  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 16:54:48.208  3969  3969 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d8e9309}
,08-26 16:54:48.208  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 16:54:48.209  3969  3969 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 16:54:48.218  3969  3969 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 16:54:48.219  3969  3969 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 16:54:48.235  3969  3969 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 16:54:48.251  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 16:54:48.251  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 16:54:48.252  3969  3969 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 16:54:48.252  3969  3969 I Adreno  : Build Date                       : 10/20/15
08-26 16:54:48.252  3969  3969 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 16:54:48.252  3969  3969 I Adreno  : Local Branch                     : M14
08-26 16:54:48.252  3969  3969 I Adreno  : Remote Branch                    : 
08-26 16:54:48.252  3969  3969 I Adreno  : Remote Branch                    : 
08-26 16:54:48.252  3969  3969 I Adreno  : Reconstruct Branch               : 
,08-26 16:54:48.303  3969  4015 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 16:54:48.325  3969  3969 I NSApplication: Starting up...
,08-26 16:54:48.364   873  2076 I ActivityManager: Start proc 4020:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 16:54:48.366   873  2076 I ActivityManager: Killing 3643:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 16:54:48.438  4020  4020 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 16:54:48.683   873  1695 I ActivityManager: Killing 3659:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 16:54:50.023   873  2076 D WifiService: setWifiEnabled: true pid=3801, uid=10000
,08-26 16:54:50.024   873  2076 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:50.036   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-26 16:54:50.045  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:50.046  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:50.046  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:50.047  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:50.050  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:50.050  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:54:50.050  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:50.051  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:50.072   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-26 16:54:50.073   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 16:54:50.074   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 16:54:50.075   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 16:54:50.075   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 16:54:50.075   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 16:54:50.076   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 16:54:50.092   873  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.12 rxSuccessRate=16.25 delta 1000 -> 994
08-26 16:54:50.092   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 16:54:50.094   373   871 D CommandListener: Setting iface cfg
,08-26 16:54:50.096   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 16:54:50.096   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 16:54:50.101   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 16:54:50.101   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 16:54:50.101   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:54:50.101   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 16:54:50.112   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 16:54:50.185   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 16:54:50.187  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 16:54:50.604  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 16:54:50.644  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 16:54:50.644  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 16:54:50.651   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 16:54:50.663   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 16:54:50.663   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:54:50.664   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 16:54:50.685   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:54:50.698   373   871 D CommandListener: Setting iface cfg
,08-26 16:54:50.699   873  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 16:54:50.714   873  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 16:54:50.717   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 16:54:50.727   873  4048 D DhcpClient: Receive thread started
,08-26 16:54:50.810   873  1316 E native  : do suspend false
,08-26 16:54:50.831   873  1908 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 16:54:50.867   873  4048 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,08-26 16:54:50.869   873  1908 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,08-26 16:54:50.874   873  1908 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 16:54:50.892   873  4048 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 16:54:50.894   873  1908 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 16:54:50.900   373   871 D CommandListener: Setting iface cfg
,08-26 16:54:50.911   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 16:54:50.922   873  1908 D DhcpClient: Scheduling renewal in 86399s
,08-26 16:54:50.938   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 16:54:50.942   873  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 16:54:50.942   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101],
,08-26 16:54:50.944   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 16:54:50.947   873  1318 D ConnectivityService: Adding iface wlan0 to network 101
08-26 16:54:50.962   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 16:54:51.034   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 16:54:51.034   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 16:54:51.036   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 16:54:51.040   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 16:54:51.044   873  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 16:54:51.054   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 16:54:51.060   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 16:54:51.060   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 16:54:51.060   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:51.060   873  1318 D ConnectivityService:    accepting network in place of null
08-26 16:54:51.060   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 16:54:51.061   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 16:54:51.062   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 16:54:51.071   873  4047 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 16:54:51.104   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:54:51.140   873  4046 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:816::200e
08-26 16:54:51.140   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:54:51.148   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 16:54:51.149   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:51.159   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 16:54:51.159   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:51.169  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.169  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:51.169  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:51.169  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:51.178  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.178  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.178  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.178  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:54:51.186  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 16:54:51.188  1719  1719 D SystemUpdateService: onCreate
,08-26 16:54:51.193  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 16:54:51.196  1719  4058 I SystemUpdateService: active receiver: enabled
,08-26 16:54:51.199  1719  4058 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 16:54:51.203  1719  4058 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 16:54:51.203  1719  4058 I SystemUpdateService: now status is 0 (complete)
08-26 16:54:51.203  1719  4058 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 16:54:51.203  1719  4058 I SystemUpdateService: file has been verified
08-26 16:54:51.203  1719  4058 I SystemUpdateService: OTA package size = 12249756
,08-26 16:54:51.206  1719  4058 I SystemUpdateService: showing system update notification
,08-26 16:54:51.213   873  4046 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 14:54:51 GMT], X-Android-Received-Millis=[1472223291212], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472223291184]}
,08-26 16:54:51.216   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 16:54:51.216   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 16:54:51.216   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 16:54:51.217  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-26 16:54:51.218   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 16:54:51.222  1719  2459 I iu.UploadsManager: num queued entries: 0
,08-26 16:54:51.222  1719  2459 I iu.UploadsManager: num updated entries: 0
,08-26 16:54:51.224  1719  2459 I iu.SyncManager: NEXT; no task
,08-26 16:54:51.224  1719  4062 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 16:54:51.224  1719  4062 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 16:54:51.225  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 16:54:51.226  1719  4062 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 16:54:51.227  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 16:54:51.230  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:51.237  1719  1719 D SystemUpdateService: onDestroy
,08-26 16:54:51.239  3938  3938 D SprintDMHelper: simOperator: 
,08-26 16:54:51.239  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 16:54:51.265  1511  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 16:54:51.265  1511  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 16:54:51.265  1511  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:54:51.265  1511  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:54:51.285  1719  4062 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-26 16:54:51.384  2213  4065 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 16:54:52.147   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 16:54:52.932   873  1695 I ActivityManager: Killing 2094:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 16:54:53.029   873  2003 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-26 16:54:53.030   873  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:53.057  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 16:54:53.059   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 16:54:53.060   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 16:54:53.060   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 16:54:53.061   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:54:53.084   873  1908 D DhcpClient: Clearing IP address
,08-26 16:54:53.085   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-26 16:54:53.088   373   871 D CommandListener: Setting iface cfg
,08-26 16:54:53.096  1511  4070 V NativeCrypto: Read error: ssl=0x9b2dde00: I/O error during system call, Connection timed out
,08-26 16:54:53.101  1511  4070 V NativeCrypto: SSL shutdown failed: ssl=0x9b2dde00: I/O error during system call, Broken pipe
,08-26 16:54:53.102   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 16:54:53.103   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 16:54:53.110   396   396 E Parcel  : Reading a NULL string not supported here.
,08-26 16:54:53.114   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 16:54:53.116   873  4048 D DhcpClient: Receive thread stopped
08-26 16:54:53.117   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 16:54:53.124   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-26 16:54:53.128   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 16:54:53.136   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 16:54:53.138  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:53.139  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:53.139  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:53.139  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:53.139  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:53.140  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:53.140  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:53.140  1894  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:53.141   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 16:54:53.160   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:54:53.184   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:54:53.184   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 16:54:53.185   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:53.187   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 16:54:53.189  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:53.191  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:53.197  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 16:54:53.201  1719  1719 D SystemUpdateService: onCreate
,08-26 16:54:53.203  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 16:54:53.206  1719  4079 I SystemUpdateService: active receiver: enabled
,08-26 16:54:53.212  1719  4079 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 16:54:53.212  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 16:54:53.218  1719  2459 I iu.UploadsManager: num queued entries: 0
,08-26 16:54:53.219  1719  2459 I iu.UploadsManager: num updated entries: 0
,08-26 16:54:53.220  1719  4079 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 16:54:53.220  1719  4079 I SystemUpdateService: now status is 0 (complete)
08-26 16:54:53.221  1719  4079 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 16:54:53.221  1719  4079 I SystemUpdateService: file has been verified
08-26 16:54:53.221  1719  4079 I SystemUpdateService: OTA package size = 12249756
,08-26 16:54:53.223  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 16:54:53.224  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 16:54:53.226  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:53.231  3938  3938 D SprintDMHelper: simOperator: 
,08-26 16:54:53.231  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 16:54:53.257  1719  2459 I iu.SyncManager: NEXT; no task
08-26 16:54:53.257  2213  4084 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 16:54:53.257   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-26 16:54:53.262  1719  4079 I SystemUpdateService: showing system update notification
,08-26 16:54:53.282  1719  1719 D SystemUpdateService: onDestroy
,08-26 16:54:56.085   873   890 I ActivityManager: Start proc 4087:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 16:54:56.221  4087  4087 D AdapterServiceConfig: Adding HeadsetService
,08-26 16:54:56.222  4087  4087 D AdapterServiceConfig: Adding A2dpService
08-26 16:54:56.223  4087  4087 D AdapterServiceConfig: Adding HidService
08-26 16:54:56.223  4087  4087 D AdapterServiceConfig: Adding HealthService
,08-26 16:54:56.224  4087  4087 D AdapterServiceConfig: Adding PanService
08-26 16:54:56.225  4087  4087 D AdapterServiceConfig: Adding GattService
,08-26 16:54:56.225  4087  4087 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 16:54:56.256   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9ca5a1:true
,08-26 16:54:56.256  4087  4087 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 16:54:56.264  4087  4087 I bt_bluedroid: init
,08-26 16:54:56.264  4087  4099 I BluetoothAdapterState: Entering OffState
,08-26 16:54:56.270  4087  4100 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 16:54:56.270  4087  4100 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 16:54:56.270  4087  4100 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 16:54:56.270  4087  4100 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 16:54:56.270  4087  4087 I bt_bluedroid: get_profile_interface socket
08-26 16:54:56.272  4087  4087 I bt_bluedroid: get_profile_interface sdp
,08-26 16:54:56.278  4087  4103 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 16:54:56.280  4087  4098 I bt_bluedroid: config_hci_snoop_log
,08-26 16:54:56.281   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-26 16:54:56.281  4087  4103 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 16:54:56.288  4087  4099 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 16:54:56.289  4087  4099 D BluetoothAdapterProperties: Setting state to 14
,08-26 16:54:56.289  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 16:54:56.294  4087  4099 D BluetoothBondStateMachine: make
,08-26 16:54:56.298  4087  4104 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 16:54:56.304  4087  4099 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:54:56.305  4087  4087 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 16:54:56.307  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:56.307  4087  4087 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 16:54:56.308  4087  4087 D BtGatt.GattService: Received start request. Starting profile...
,08-26 16:54:56.308  4087  4087 D BtGatt.GattService: start()
08-26 16:54:56.308  4087  4087 I bt_bluedroid: get_profile_interface gatt
,08-26 16:54:56.309  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
08-26 16:54:56.309  4087  4087 D BtGatt.AdvertiseManager: advertise manager created
,08-26 16:54:56.315  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:54:56.315  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:56.315  4087  4087 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 16:54:56.315  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:56.315  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 16:54:56.316  4087  4099 I bt_bluedroid: enable
08-26 16:54:56.316  4087  4100 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 16:54:56.317  4087  4100 I bt_hci  : start_up
,08-26 16:54:56.324  4087  4100 I bt_vendor: alloc value 0xb39a8189
,08-26 16:54:56.324  4087  4100 I bt_vendor: init,
,08-26 16:54:56.324  4087  4100 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 16:54:56.324  4087  4100 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 16:54:56.432  4087  4100 D bt_hci  : start_up starting async portion
,08-26 16:54:56.433  4087  4107 I bt_hci  : event_finish_startup
08-26 16:54:56.433  4087  4107 I bt_hci_h4: hal_open
,08-26 16:54:56.434  4087  4107 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 16:54:56.442  4087  4107 I bt_userial_vendor: device fd = 51 open
,08-26 16:54:56.474  4087  4107 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 16:54:56.506  4087  4107 D bt_hwcfg: Chipset BCM4354A2
08-26 16:54:56.506  4087  4107 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 16:54:56.507  4087  4107 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 16:54:57.174  4087  4107 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 16:54:57.175  4087  4107 D bt_hwcfg: Settlement delay -- 100 ms
08-26 16:54:57.176  4087  4107 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 16:54:57.292  4087  4107 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 16:54:57.294  4087  4107 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 16:54:57.324  4087  4107 I bt_hwcfg: vendor lib fwcfg completed
,08-26 16:54:57.324  4087  4107 I bt_vendor: firmware callback
08-26 16:54:57.324  4087  4107 I bt_hci  : firmware_config_callback
,08-26 16:54:57.335  4087  4109 I bt_btu  : btu_task pending for preload complete event
,08-26 16:54:57.335  4087  4109 I bt_btu_task: Bluetooth chip preload is complete
08-26 16:54:57.335  4087  4109 I bt_btu  : btu_task received preload complete event
,08-26 16:54:57.345  4087  4109 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 16:54:57.345  4087  4109 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 16:54:57.346  4087  4109 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 16:54:57.346  4087  4109 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 16:54:57.346  4087  4109 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 16:54:57.347  4087  4109 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 16:54:57.347  4087  4109 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 16:54:57.347  4087  4109 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 16:54:57.347  4087  4109 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 16:54:57.348  4087  4109 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 16:54:57.348  4087  4109 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 16:54:57.348  4087  4109 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 16:54:57.348  4087  4109 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 16:54:57.349  4087  4109 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 16:54:57.349  4087  4109 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 16:54:57.485  4087  4109 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3925d9d
08-26 16:54:57.485  4087  4109 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3925d9d 
,08-26 16:54:57.506  4087  4103 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-26 16:54:57.508  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 16:54:57.508  4087  4103 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 16:54:57.512  4087  4103 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 16:54:57.515  4087  4103 D BluetoothAdapterProperties: Scan Mode:20
,08-26 16:54:57.517  4087  4103 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 16:54:57.517  4087  4103 D bt_hci  : do_postload posting postload work item
,08-26 16:54:57.519  4087  4107 I bt_hci  : event_postload
,08-26 16:54:57.519  4087  4107 I bt_vendor: sco_config_cb
,08-26 16:54:57.520  4087  4107 I bt_hci  : sco_config_callback postload finished.
,08-26 16:54:57.521  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:57.524  4087  4103 D bt_bte_conf: Device ID record 1 : primary
,08-26 16:54:57.524  4087  4103 D bt_bte_conf:   vendorId            = 000f
,08-26 16:54:57.525  4087  4103 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 16:54:57.525  4087  4103 D bt_bte_conf:   product             = 1200
,08-26 16:54:57.525  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:57.525  4087  4103 D bt_bte_conf:   version             = 1436
,08-26 16:54:57.526  4087  4103 D bt_bte_conf:   clientExecutableURL = 
08-26 16:54:57.527  4087  4103 D bt_bte_conf:   serviceDescription  = 
08-26 16:54:57.527  4087  4103 D bt_bte_conf:   documentationURL    = 
,08-26 16:54:57.527  4087  4103 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 16:54:57.528  4087  4100 D bt_stack_manager: event_start_up_stack finished
08-26 16:54:57.529  4087  4107 I bt_vendor: low_power_mode_cb
,08-26 16:54:57.530  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 16:54:57.530  4087  4099 D BluetoothAdapterProperties: Setting state to 15
08-26 16:54:57.530  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 16:54:57.536  4087  4099 I BluetoothAdapterState: Entering BleOnState
,08-26 16:54:57.547  4087  4099 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 16:54:57.547  4087  4099 D BluetoothAdapterProperties: Setting state to 11
08-26 16:54:57.547  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 16:54:57.552  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:57.553  4087  4087 D HeadsetService: Received start request. Starting profile...
,08-26 16:54:57.557  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:57.558  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:57.560  4087  4087 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 16:54:57.561  4087  4087 D HeadsetStateMachine: make
,08-26 16:54:57.561  4087  4099 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:54:57.568  4087  4087 D HeadsetStateMachine: max_hf_connections = 1
,08-26 16:54:57.569  4087  4087 I bt_bluedroid: get_profile_interface handsfree
,08-26 16:54:57.569  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 16:54:57.569  4087  4103 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 16:54:57.572  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
08-26 16:54:57.573  4087  4087 D A2dpService: Received start request. Starting profile...
,08-26 16:54:57.573  4087  4087 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 16:54:57.574  4087  4087 I bt_bluedroid: get_profile_interface avrcp
,08-26 16:54:57.580  4087  4087 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 16:54:57.580  4087  4087 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:54:57.580  4087  4087 D A2dpStateMachine: make
08-26 16:54:57.581  4087  4087 I bt_bluedroid: get_profile_interface a2dp
,08-26 16:54:57.582  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 16:54:57.582  4087  4118 D A2dpStateMachine: Enter Disconnected: -2
,08-26 16:54:57.583  4087  4087 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 16:54:57.584  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:57.585  4087  4087 D HidService: Received start request. Starting profile...
,08-26 16:54:57.586  3882  3882 D BluetoothInputDevice: Proxy object connected
08-26 16:54:57.586  4087  4087 I bt_bluedroid: get_profile_interface hidhost
08-26 16:54:57.586  4087  4103 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39073e5
08-26 16:54:57.586  4087  4087 D HidService: setHidService(): set to: null
08-26 16:54:57.586  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 16:54:57.586  3882  3882 D HidProfile: Bluetooth service connected
08-26 16:54:57.587  4087  4087 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 16:54:57.587  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:57.588  4087  4087 D HealthService: Received start request. Starting profile...
08-26 16:54:57.589  4087  4087 I bt_bluedroid: get_profile_interface health
08-26 16:54:57.590  4087  4087 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 16:54:57.591  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:57.592  4087  4087 D PanService: Received start request. Starting profile...
,08-26 16:54:57.592  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 16:54:57.592  4087  4087 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 16:54:57.592  4087  4087 I bt_bluedroid: get_profile_interface pan
08-26 16:54:57.593  3882  3882 D PanProfile: Bluetooth service connected
08-26 16:54:57.593  4087  4103 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 16:54:57.595  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:54:57.596  4087  4087 D BluetoothMapService: Received start request. Starting profile...
,08-26 16:54:57.596  3882  3882 D BluetoothMap: Proxy object connected
08-26 16:54:57.596  4087  4087 D BluetoothMapService: start()
08-26 16:54:57.597  3882  3882 D MapProfile: Bluetooth service connected
,08-26 16:54:57.597  3882  3882 D BluetoothMap: getConnectedDevices()
08-26 16:54:57.598  3882  3882 D BluetoothMap: Bluetooth is Not enabled
08-26 16:54:57.599  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 16:54:57.599  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 16:54:57.599  4087  4087 D BluetoothMapAppObserver: createReceiver()
,08-26 16:54:57.601  4087  4087 D BluetoothMapAppObserver: initObservers()
08-26 16:54:57.601  4087  4087 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 16:54:57.609  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-26 16:54:57.609  4087  4087 V BluetoothAdapterState: isTurningOn()=true
,08-26 16:54:57.609  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:57.609  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:57.609  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:54:57.611  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:54:57.611  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-26 16:54:57.611  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:57.611  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:54:57.611  4087  4116 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOn()=true
,08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:57.612  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:57.613  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-26 16:54:57.613  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-26 16:54:57.613  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:57.613  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:57.613  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 16:54:57.613  4087  4099 D BluetoothAdapterProperties: ScanMode =  20
08-26 16:54:57.613  4087  4099 D BluetoothAdapterProperties: State =  11
08-26 16:54:57.614  4087  4099 D BluetoothAdapterProperties: Setting state to 12
08-26 16:54:57.614  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 16:54:57.615  4087  4099 I BluetoothAdapterState: Entering OnState
08-26 16:54:57.615  3882  3897 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 16:54:57.616  1373  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-26 16:54:57.616  4087  4103 D BluetoothAdapterProperties: Scan Mode:21
08-26 16:54:57.617  4087  4103 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:54:57.619   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 16:54:57.619  1373  1373 D BluetoothMap: Proxy object connected
08-26 16:54:57.619  1373  1373 D MapProfile: Bluetooth service connected
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:57.619  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:57.619  1373  1373 D BluetoothMap: getConnectedDevices()
,08-26 16:54:57.620  1373  2072 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 16:54:57.621   873   873 D BluetoothA2dp: Proxy object connected
08-26 16:54:57.622  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:57.623  3882  3895 D BluetoothPan: onBluetoothStateChange on: true
,08-26 16:54:57.623  1373  1373 D BluetoothA2dp: Proxy object connected
08-26 16:54:57.624  1373  2207 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 16:54:57.625   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:54:57.625  1373  1373 D BluetoothInputDevice: Proxy object connected
08-26 16:54:57.625  1373  1373 D HidProfile: Bluetooth service connected
,08-26 16:54:57.625  1965  1975 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:57.625  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:57.627  1373  2207 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:54:57.627  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 16:54:57.628  4087  4087 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 16:54:57.628  1373  2072 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 16:54:57.630  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:54:57.630  3882  3897 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 16:54:57.631  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:57.631   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:54:57.631   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:54:57.632  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:54:57.632  1373  1391 D BluetoothPan: onBluetoothStateChange on: true
08-26 16:54:57.633  4087  4087 D ObexServerSockets: Succeed to create listening sockets 
08-26 16:54:57.633  4087  4087 D ObexServerSockets0: startAccept()
08-26 16:54:57.633  4087  4087 D ObexServerSockets0: prepareForNewConnect()
,08-26 16:54:57.634  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 16:54:57.634  3882  3895 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 16:54:57.634  1373  1373 D PanProfile: Bluetooth service connected
,08-26 16:54:57.635  4087  4087 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 16:54:57.635  4087  4087 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 16:54:57.637  4087  4126 D ObexServerSockets0: Accepting socket connection...
08-26 16:54:57.639   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 16:54:57.639  4087  4087 D BluetoothMapService: onReceive
08-26 16:54:57.639  4087  4087 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:57.639  4087  4087 D BluetoothMapService: STATE_ON
08-26 16:54:57.637  4087  4125 D ObexServerSockets0: Accepting socket connection...
08-26 16:54:57.641  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 16:54:57.641  3882  3882 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 16:54:57.643  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:57.647  3882  3882 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 16:54:57.654  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 16:54:57.656  3882  3882 D BluetoothA2dp: Proxy object connected
,08-26 16:54:57.660  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 16:54:57.661  4087  4087 D ObexServerSockets0: prepareForNewConnect()
08-26 16:54:57.662  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:54:57.666  3882  3882 D DockEventReceiver: finishStartingService: stopping service
08-26 16:54:57.672  1373  1373 D BluetoothPbap: Proxy object connected
,08-26 16:54:57.672  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-26 16:54:57.674  3882  3882 D BluetoothPbap: Proxy object connected
,08-26 16:54:57.674  3882  3882 D PbapServerProfile: Bluetooth service connected
,08-26 16:54:57.683  4087  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:54:57.704  4087  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:54:57.705  4087  4134 I BtOppRfcommListener: Accept thread started.
,08-26 16:54:57.729  1965  2164 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.729   873   873 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.730  1373  2207 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.731   873   873 D BluetoothHeadset: Proxy object connected
08-26 16:54:57.731   873   873 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.731  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-26 16:54:57.731   873   890 D BluetoothHeadset: Proxy object connected
08-26 16:54:57.731   873   890 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.751  3882  3897 D BluetoothHeadset: Proxy object connected
,08-26 16:54:57.753  3882  3882 D HeadsetProfile: Bluetooth service connected
,08-26 16:54:59.050  4087  4099 D BluetoothAdapterState: Current state: ON, message: 23
08-26 16:54:59.050  4087  4099 D BluetoothAdapterProperties: Setting state to 13
,08-26 16:54:59.050  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 16:54:59.052  4087  4099 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 16:54:59.056  4087  4099 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:54:59.063   873  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-26 16:54:59.065  4087  4087 D BluetoothMapService: onReceive
08-26 16:54:59.066  4087  4087 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:59.066  4087  4087 D BluetoothMapService: STATE_TURNING_OFF
08-26 16:54:59.067  4087  4087 D BluetoothMapService: MAP Service closeService in
08-26 16:54:59.067  4087  4087 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 16:54:59.068  4087  4087 D ObexServerSockets0: shutdown(block = true)
08-26 16:54:59.069  4087  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 16:54:59.070  4087  4087 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 16:54:59.071  4087  4126 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 16:54:59.071  4087  4111 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 16:54:59.072  4087  4087 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 16:54:59.073  4087  4087 I BtOppRfcommListener: stopping Accept Thread
,08-26 16:54:59.074  4087  4134 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:59.074  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:59.074  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:59.078  4087  4103 D BluetoothAdapterProperties: Scan Mode:20
08-26 16:54:59.078  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:59.078  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:59.078  4087  4134 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 16:54:59.078  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 16:54:59.085  4087  4087 D HeadsetService: Received stop request...Stopping profile...
08-26 16:54:59.085  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:59.086  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:59.087  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:59.088  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:59.090  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 16:54:59.090  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:59.091  1965  1977 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:59.091  4087  4087 D A2dpService: Received stop request...Stopping profile...
08-26 16:54:59.092  4087  4118 D A2dpStateMachine: Exit Disconnected: -1
08-26 16:54:59.092  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:59.093   873   873 D BluetoothHeadset: Proxy object disconnected
,08-26 16:54:59.094  1373  2072 D BluetoothHeadset: Proxy object disconnected
,08-26 16:54:59.094  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:59.094  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-26 16:54:59.094  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:59.094  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.095   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:59.097  3882  3897 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:59.097   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:59.097  4087  4087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 16:54:59.097   873   873 D BluetoothA2dp: Proxy object disconnected
08-26 16:54:59.097  4087  4087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:54:59.098  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:59.098  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:59.098  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:59.098  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 16:54:59.098  4087  4103 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-26 16:54:59.098  4087  4087 D HidService: Received stop request...Stopping profile...
08-26 16:54:59.098  4087  4087 D HidService: Stopping Bluetooth HidService
08-26 16:54:59.098  3882  3882 D BluetoothA2dp: Proxy object disconnected
08-26 16:54:59.100  4087  4087 D HealthService: Received stop request...Stopping profile...
,08-26 16:54:59.103  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:59.103  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:59.103  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:59.103  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.104  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-26 16:54:59.104  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-26 16:54:59.104  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-26 16:54:59.104  1373  1373 D HidProfile: Bluetooth service disconnected
08-26 16:54:59.104  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 16:54:59.104  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:59.105  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 16:54:59.105  4087  4109 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:59.105  4087  4109 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:59.105  4087  4109 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 16:54:59.105  4087  4109 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:59.106  4087  4087 D PanService: Received stop request...Stopping profile...
08-26 16:54:59.107  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 16:54:59.107  1373  1373 D PanProfile: Bluetooth service disconnected
,08-26 16:54:59.107  3882  3882 D DockEventReceiver: finishStartingService: stopping service
08-26 16:54:59.108  4087  4087 D BluetoothMapService: Received stop request...Stopping profile...
08-26 16:54:59.108  4087  4087 D BluetoothMapService: stop()
08-26 16:54:59.109  3882  3882 D HeadsetProfile: Bluetooth service disconnected
08-26 16:54:59.109  4087  4087 D BluetoothMapAppObserver: deinitObservers()
08-26 16:54:59.109  4087  4087 D BluetoothMapAppObserver: removeReceiver()
,08-26 16:54:59.109  3882  3882 D BluetoothInputDevice: Proxy object disconnected
08-26 16:54:59.109  3882  3882 D HidProfile: Bluetooth service disconnected
08-26 16:54:59.110  1373  1373 D BluetoothMap: Proxy object disconnected
08-26 16:54:59.110  1373  1373 D MapProfile: Bluetooth service disconnected
08-26 16:54:59.111  3882  3882 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 16:54:59.111  3882  3882 D PanProfile: Bluetooth service disconnected
,08-26 16:54:59.112  3882  3882 D BluetoothMap: Proxy object disconnected
08-26 16:54:59.112  3882  3882 D MapProfile: Bluetooth service disconnected
,08-26 16:54:59.114  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:54:59.115  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-26 16:54:59.115  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:59.115  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:59.115  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.116  4087  4087 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 16:54:59.116  4087  4103 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 16:54:59.116  4087  4087 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 16:54:59.116  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:59.117  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:59.117  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:59.117  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.117  4087  4087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 16:54:59.117  4087  4103 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 16:54:59.117  4087  4087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:54:59.118  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-26 16:54:59.118  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-26 16:54:59.118  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:59.118  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.118  4087  4087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 16:54:59.118  4087  4087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 16:54:59.119  4087  4087 D BluetoothMapService: MAP Service closeService in
,08-26 16:54:59.119  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-26 16:54:59.119  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:59.119  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:54:59.120  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:54:59.120  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 16:54:59.120  4087  4099 D BluetoothAdapterProperties: Setting state to 15
08-26 16:54:59.120  4087  4087 D BluetoothMapService: cleanup()
08-26 16:54:59.120  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 16:54:59.120  4087  4087 D BluetoothMapService: MAP Service closeService in
08-26 16:54:59.121  4087  4099 I BluetoothAdapterState: Entering BleOnState
,08-26 16:54:59.122  3882  3897 D BluetoothMap: onBluetoothStateChange: up=false
08-26 16:54:59.123  1373  1373 D BluetoothPbap: Proxy object disconnected
08-26 16:54:59.123  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-26 16:54:59.123  1373  2207 D BluetoothMap: onBluetoothStateChange: up=false
08-26 16:54:59.124  3882  3882 D BluetoothPbap: Proxy object disconnected
08-26 16:54:59.124  3882  3882 D PbapServerProfile: Bluetooth service disconnected
,08-26 16:54:59.125   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:54:59.125  1373  2072 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:54:59.126  3882  3897 D BluetoothPan: onBluetoothStateChange on: false
,08-26 16:54:59.128  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 16:54:59.128   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:59.129  1965  2290 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 16:54:59.129  1373  2207 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:59.129  3882  3895 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:54:59.130  1373  2072 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 16:54:59.131  3882  4140 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 16:54:59.131  3882  3897 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:59.132   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:59.132   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:59.132  1373  1391 D BluetoothPan: onBluetoothStateChange on: false
08-26 16:54:59.133  3882  3895 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 16:54:59.133  4087  4099 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 16:54:59.133  4087  4099 D BluetoothAdapterProperties: Setting state to 16
08-26 16:54:59.133  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 16:54:59.134  4087  4099 D BluetoothAdapterProperties: onBleDisable
08-26 16:54:59.135  4087  4100 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 16:54:59.136  4087  4099 I BluetoothAdapterState: Entering PendingCommandState
08-26 16:54:59.136  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:59.136  4087  4109 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 16:54:59.136  4087  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 16:54:59.137  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:59.139  4087  4103 D BluetoothAdapterProperties: Scan Mode:20
08-26 16:54:59.140  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:59.141  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:59.141  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 16:54:59.145  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:54:59.150  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:54:59.337  4087  4103 I bt_hci  : shut_down
,08-26 16:54:59.339  4087  4107 I bt_vendor: low_power_mode_cb
,08-26 16:54:59.358  4087  4107 D bt_hwcfg: hw_epilog_process
,08-26 16:54:59.367  4087  4107 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 16:54:59.367  4087  4107 I bt_vendor: epilog_cb
,08-26 16:54:59.367  4087  4107 I bt_hci  : epilog_finished_callback
,08-26 16:54:59.375  4087  4103 I bt_hci_h4: hal_close
,08-26 16:54:59.376  4087  4103 I bt_userial_vendor: device fd = 51 close
,08-26 16:54:59.508  4087  4100 D bt_stack_manager: event_shut_down_stack finished.
,08-26 16:54:59.509  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 16:54:59.514  4087  4099 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 16:54:59.515  4087  4087 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 16:54:59.516  4087  4087 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 16:54:59.517  4087  4087 D BtGatt.GattService: stop()
08-26 16:54:59.517  4087  4087 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 16:54:59.522  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:54:59.522  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-26 16:54:59.523  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:54:59.523  4087  4087 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 16:54:59.524  4087  4099 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 16:54:59.525  4087  4099 D BluetoothAdapterProperties: Setting state to 10
08-26 16:54:59.526  4087  4099 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 16:54:59.528  4087  4099 I BluetoothAdapterState: Entering OffState
08-26 16:54:59.530   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 16:54:59.556  4087  4087 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 16:54:59.556  4087  4087 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 16:54:59.557  4087  4100 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 16:54:59.566  4087  4100 D bt_stack_manager: event_clean_up_stack finished.
,08-26 16:54:59.567  4087  4087 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 16:54:59.573  4087  4087 I art     : System.exit called, status: 0
,08-26 16:54:59.573  4087  4087 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 16:54:59.618   873  1695 I ActivityManager: Process com.android.bluetooth (pid 4087) has died
,08-26 16:55:02.046  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:02.047  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:05.054  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:05.055  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9247255 added. We now have 6 listener(s)
08-26 16:55:05.055  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:05.060  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:05.061  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@218c46a added. We now have 7 listener(s)
08-26 16:55:05.061  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:05.062  3801  3850 I System.out: IsBluetoothEnabled
,08-26 16:55:05.074  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:05.118   873   890 I ActivityManager: Start proc 4145:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 16:55:05.248  4145  4145 D AdapterServiceConfig: Adding HeadsetService
,08-26 16:55:05.249  4145  4145 D AdapterServiceConfig: Adding A2dpService
08-26 16:55:05.250  4145  4145 D AdapterServiceConfig: Adding HidService,
08-26 16:55:05.251  4145  4145 D AdapterServiceConfig: Adding HealthService
,08-26 16:55:05.251  4145  4145 D AdapterServiceConfig: Adding PanService
08-26 16:55:05.252  4145  4145 D AdapterServiceConfig: Adding GattService
,08-26 16:55:05.252  4145  4145 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 16:55:05.271   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c0b8ba:true
,08-26 16:55:05.272  4145  4145 D BluetoothAdapterState: make() - Creating AdapterState,
,08-26 16:55:05.277  4145  4145 I bt_bluedroid: init
,08-26 16:55:05.278  4145  4157 I BluetoothAdapterState: Entering OffState
,08-26 16:55:05.283  4145  4158 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 16:55:05.284  4145  4158 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 16:55:05.284  4145  4158 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
08-26 16:55:05.284  4145  4158 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 16:55:05.286  4145  4145 I bt_bluedroid: get_profile_interface socket
,08-26 16:55:05.288  4145  4145 I bt_bluedroid: get_profile_interface sdp
,08-26 16:55:05.292  4145  4156 I bt_bluedroid: config_hci_snoop_log
,08-26 16:55:05.292  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 16:55:05.294   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 16:55:05.296  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 16:55:05.301  4145  4157 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 16:55:05.302  4145  4157 D BluetoothAdapterProperties: Setting state to 14
08-26 16:55:05.302  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 16:55:05.306  4145  4157 D BluetoothBondStateMachine: make
,08-26 16:55:05.311  4145  4162 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 16:55:05.317  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:55:05.321  4145  4145 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 16:55:05.329  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:05.331  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 16:55:05.332  4145  4145 D BtGatt.GattService: Received start request. Starting profile...
,08-26 16:55:05.333  4145  4145 D BtGatt.GattService: start()
,08-26 16:55:05.333  4145  4145 I bt_bluedroid: get_profile_interface gatt
,08-26 16:55:05.336  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
08-26 16:55:05.336  4145  4145 D BtGatt.AdvertiseManager: advertise manager created
,08-26 16:55:05.351  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:55:05.351  4145  4145 V BluetoothAdapterState: isTurningOn()=false
08-26 16:55:05.352  4145  4145 V BluetoothAdapterState: isBleTurningOn()=true
08-26 16:55:05.352  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:55:05.353  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 16:55:05.354  4145  4157 I bt_bluedroid: enable
08-26 16:55:05.354  4145  4158 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 16:55:05.357  4145  4158 I bt_hci  : start_up
,08-26 16:55:05.371  4145  4158 I bt_vendor: alloc value 0xb39a8189
08-26 16:55:05.371  4145  4158 I bt_vendor: init
,08-26 16:55:05.371  4145  4158 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 16:55:05.372  4145  4158 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 16:55:05.477  4145  4158 D bt_hci  : start_up starting async portion
08-26 16:55:05.478  4145  4165 I bt_hci  : event_finish_startup
,08-26 16:55:05.478  4145  4165 I bt_hci_h4: hal_open
,08-26 16:55:05.479  4145  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 16:55:05.490  4145  4165 I bt_userial_vendor: device fd = 51 open
,08-26 16:55:05.520  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 16:55:05.552  4145  4165 D bt_hwcfg: Chipset BCM4354A2
08-26 16:55:05.552  4145  4165 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 16:55:05.553  4145  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 16:55:06.226  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 16:55:06.228  4145  4165 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 16:55:06.229  4145  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 16:55:06.346  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 16:55:06.347  4145  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 16:55:06.375  4145  4165 I bt_hwcfg: vendor lib fwcfg completed
,08-26 16:55:06.376  4145  4165 I bt_vendor: firmware callback
08-26 16:55:06.376  4145  4165 I bt_hci  : firmware_config_callback
,08-26 16:55:06.388  4145  4168 I bt_btu  : btu_task pending for preload complete event
,08-26 16:55:06.389  4145  4168 I bt_btu_task: Bluetooth chip preload is complete
,08-26 16:55:06.389  4145  4168 I bt_btu  : btu_task received preload complete event
,08-26 16:55:06.399  4145  4168 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 16:55:06.400  4145  4168 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 16:55:06.400  4145  4168 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 16:55:06.400  4145  4168 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 16:55:06.401  4145  4168 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 16:55:06.401  4145  4168 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 16:55:06.401  4145  4168 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 16:55:06.401  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 16:55:06.402  4145  4168 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 16:55:06.402  4145  4168 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 16:55:06.402  4145  4168 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 16:55:06.402  4145  4168 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 16:55:06.403  4145  4168 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 16:55:06.403  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 16:55:06.403  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 16:55:06.542  4145  4168 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3925d9d
,08-26 16:55:06.543  4145  4168 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3925d9d 
,08-26 16:55:06.549  4145  4161 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 16:55:06.551  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 16:55:06.552  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 16:55:06.556  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 16:55:06.559  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,08-26 16:55:06.560  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 16:55:06.560  4145  4161 D bt_hci  : do_postload posting postload work item
,08-26 16:55:06.561  4145  4165 I bt_hci  : event_postload
,08-26 16:55:06.561  4145  4165 I bt_vendor: sco_config_cb
,08-26 16:55:06.561  4145  4165 I bt_hci  : sco_config_callback postload finished.
,08-26 16:55:06.567  4145  4161 D bt_bte_conf: Device ID record 1 : primary
,08-26 16:55:06.568  4145  4161 D bt_bte_conf:   vendorId            = 000f
08-26 16:55:06.568  4145  4161 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 16:55:06.568  4145  4161 D bt_bte_conf:   product             = 1200
08-26 16:55:06.568  4145  4161 D bt_bte_conf:   version             = 1436,
08-26 16:55:06.568  4145  4161 D bt_bte_conf:   clientExecutableURL = 
,08-26 16:55:06.569  4145  4161 D bt_bte_conf:   serviceDescription  = 
08-26 16:55:06.569  4145  4161 D bt_bte_conf:   documentationURL    = 
,08-26 16:55:06.569  4145  4161 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 16:55:06.570  4145  4158 D bt_stack_manager: event_start_up_stack finished,
08-26 16:55:06.572  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 16:55:06.573  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:06.573  4145  4157 D BluetoothAdapterProperties: Setting state to 15
,08-26 16:55:06.573  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 16:55:06.574  4145  4157 I BluetoothAdapterState: Entering BleOnState
,08-26 16:55:06.576  4145  4165 I bt_vendor: low_power_mode_cb
08-26 16:55:06.578  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 16:55:06.578  4145  4157 D BluetoothAdapterProperties: Setting state to 11
,08-26 16:55:06.579  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 16:55:06.587  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:06.590  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87,
08-26 16:55:06.593  4145  4145 D HeadsetService: Received start request. Starting profile...
08-26 16:55:06.598  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,08-26 16:55:06.598  4145  4145 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 16:55:06.598  4145  4145 D HeadsetStateMachine: make
,08-26 16:55:06.607  4145  4145 D HeadsetStateMachine: max_hf_connections = 1
,08-26 16:55:06.607  4145  4145 I bt_bluedroid: get_profile_interface handsfree
08-26 16:55:06.607  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 16:55:06.609  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 16:55:06.610  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
08-26 16:55:06.611  4145  4145 D A2dpService: Received start request. Starting profile...
08-26 16:55:06.611  4145  4145 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 16:55:06.612  4145  4145 I bt_bluedroid: get_profile_interface avrcp
,08-26 16:55:06.618  4145  4145 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 16:55:06.618  4145  4145 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:55:06.618  4145  4145 D A2dpStateMachine: make
,08-26 16:55:06.619  4145  4145 I bt_bluedroid: get_profile_interface a2dp
,08-26 16:55:06.620  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 16:55:06.625  4145  4177 D A2dpStateMachine: Enter Disconnected: -2
,08-26 16:55:06.627  4145  4145 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 16:55:06.628  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:06.628  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:55:06.629  4145  4145 D HidService: Received start request. Starting profile...
08-26 16:55:06.629  4145  4145 I bt_bluedroid: get_profile_interface hidhost
08-26 16:55:06.629  4145  4161 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39073e5
08-26 16:55:06.630  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 16:55:06.630  4145  4145 D HidService: setHidService(): set to: null
,08-26 16:55:06.631  4145  4145 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 16:55:06.633  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:06.633  4145  4145 D HealthService: Received start request. Starting profile...
,08-26 16:55:06.635  4145  4145 I bt_bluedroid: get_profile_interface health
,08-26 16:55:06.635  4145  4145 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 16:55:06.637  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:06.637  4145  4145 D PanService: Received start request. Starting profile...
,08-26 16:55:06.638  4145  4145 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 16:55:06.638  4145  4145 I bt_bluedroid: get_profile_interface pan
08-26 16:55:06.638  4145  4161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 16:55:06.641  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:06.641  4145  4145 D BluetoothMapService: Received start request. Starting profile...
,08-26 16:55:06.642  4145  4145 D BluetoothMapService: start()
,08-26 16:55:06.645  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 16:55:06.646  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 16:55:06.646  4145  4145 D BluetoothMapAppObserver: createReceiver()
,08-26 16:55:06.648  4145  4145 D BluetoothMapAppObserver: initObservers()
08-26 16:55:06.648  4145  4145 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 16:55:06.660  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:55:06.660  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-26 16:55:06.661  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:55:06.661  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:55:06.664  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:55:06.664  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,08-26 16:55:06.664  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:55:06.664  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:55:06.666  4145  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 16:55:06.666  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:55:06.667  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-26 16:55:06.668  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-26 16:55:06.669  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 16:55:06.669  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 16:55:06.669  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 16:55:06.669  4145  4157 D BluetoothAdapterProperties: ScanMode =  20
08-26 16:55:06.669  4145  4157 D BluetoothAdapterProperties: State =  11
08-26 16:55:06.670  4145  4161 D BluetoothAdapterProperties: Scan Mode:21
08-26 16:55:06.671  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:55:06.671  4145  4157 D BluetoothAdapterProperties: Setting state to 12
08-26 16:55:06.671  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 16:55:06.671  4145  4157 I BluetoothAdapterState: Entering OnState
08-26 16:55:06.672  3882  3897 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 16:55:06.674  1373  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-26 16:55:06.676  3882  3882 D BluetoothMap: Proxy object connected
08-26 16:55:06.676  3882  3882 D MapProfile: Bluetooth service connected
08-26 16:55:06.676  3882  3882 D BluetoothMap: getConnectedDevices()
,08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:06.677  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:06.680   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 16:55:06.680  1373  1373 D BluetoothMap: Proxy object connected
08-26 16:55:06.681  1373  1373 D MapProfile: Bluetooth service connected
,08-26 16:55:06.681  1373  1373 D BluetoothMap: getConnectedDevices()
08-26 16:55:06.682  1373  2072 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 16:55:06.684  3882  4140 D BluetoothPan: onBluetoothStateChange on: true
08-26 16:55:06.686  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 16:55:06.687  4145  4145 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 16:55:06.689  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:06.689  1373  1391 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 16:55:06.691  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:55:06.697   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:06.697  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:06.697  1965  2167 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:06.697  1373  2207 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:06.698  4145  4145 D ObexServerSockets: Succeed to create listening sockets 
08-26 16:55:06.698  4145  4145 D ObexServerSockets0: startAccept()
08-26 16:55:06.698  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,08-26 16:55:06.698  3882  3897 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 16:55:06.700  4145  4145 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 16:55:06.700  4145  4145 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 16:55:06.701  1373  1373 D BluetoothA2dp: Proxy object connected
08-26 16:55:06.701   873   873 D BluetoothA2dp: Proxy object connected
,08-26 16:55:06.702  1373  2072 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 16:55:06.704  1373  1373 D BluetoothInputDevice: Proxy object connected
08-26 16:55:06.704  1373  1373 D HidProfile: Bluetooth service connected
08-26 16:55:06.704  4145  4184 D ObexServerSockets0: Accepting socket connection...
,08-26 16:55:06.706  3882  3895 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 16:55:06.707  4145  4185 D ObexServerSockets0: Accepting socket connection...
,08-26 16:55:06.709  3882  4140 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:55:06.709   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:55:06.710   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:06.710  1373  2207 D BluetoothPan: onBluetoothStateChange on: true
,08-26 16:55:06.710  3882  3882 D BluetoothA2dp: Proxy object connected
,08-26 16:55:06.712  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 16:55:06.712  1373  1373 D PanProfile: Bluetooth service connected
08-26 16:55:06.712  3882  3897 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 16:55:06.713  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 16:55:06.713  3882  3882 D PanProfile: Bluetooth service connected
08-26 16:55:06.714  3882  3882 D BluetoothInputDevice: Proxy object connected
,08-26 16:55:06.714  3882  3882 D HidProfile: Bluetooth service connected
08-26 16:55:06.715   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 16:55:06.715  4145  4145 D BluetoothMapService: onReceive
08-26 16:55:06.716  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:06.716  4145  4145 D BluetoothMapService: STATE_ON
08-26 16:55:06.717  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:06.722  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 16:55:06.730  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:55:06.730  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:55:06.736  3882  3882 D BluetoothPbap: Proxy object connected
,08-26 16:55:06.736  3882  3882 D PbapServerProfile: Bluetooth service connected
,08-26 16:55:06.737  1373  1373 D BluetoothPbap: Proxy object connected
08-26 16:55:06.737  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-26 16:55:06.742  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 16:55:06.742  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,08-26 16:55:06.750  4145  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:55:06.760  4145  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:55:06.761  4145  4194 I BtOppRfcommListener: Accept thread started.
,08-26 16:55:06.799  1965  1975 D BluetoothHeadset: Proxy object connected
,08-26 16:55:06.799   873   873 D BluetoothHeadset: Proxy object connected
08-26 16:55:06.799  1373  2207 D BluetoothHeadset: Proxy object connected
08-26 16:55:06.800   873   873 D BluetoothHeadset: Proxy object connected
08-26 16:55:06.800  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-26 16:55:06.801  3882  4140 D BluetoothHeadset: Proxy object connected
,08-26 16:55:06.802   873   873 D BluetoothHeadset: Proxy object connected
08-26 16:55:06.802  3882  3882 D HeadsetProfile: Bluetooth service connected
,08-26 16:55:06.809  3882  3897 D BluetoothHeadset: Proxy object connected
,08-26 16:55:06.810   873   890 D BluetoothHeadset: Proxy object connected
,08-26 16:55:06.811   873   890 D BluetoothHeadset: Proxy object connected
,08-26 16:55:06.813  3882  3882 D HeadsetProfile: Bluetooth service connected
,08-26 16:55:06.840   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 16:55:06.853  1880  1880 I Keyboard.Facilitator: onFinishInput()
,08-26 16:55:06.865   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 16:55:06.865   873   893 I Adreno  : Build Date                       : 10/20/15
08-26 16:55:06.865   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 16:55:06.865   873   893 I Adreno  : Local Branch                     : M14
08-26 16:55:06.865   873   893 I Adreno  : Remote Branch                    : 
08-26 16:55:06.865   873   893 I Adreno  : Remote Branch                    : 
08-26 16:55:06.865   873   893 I Adreno  : Reconstruct Branch               : 
,08-26 16:55:06.900   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (393 us)
,08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:07.092  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:07.095  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:07.097  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:07.097  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4601d5b added. We now have 8 listener(s)
,08-26 16:55:07.097  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:07.102   873   883 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-26 16:55:07.102   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:55:07.109  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:07.110   873  1401 D WifiService: setWifiEnabled: true pid=3801, uid=10000
,08-26 16:55:07.110   873  1401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:55:07.126   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-26 16:55:07.135  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:07.141  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:55:07.157   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-26 16:55:07.158   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 16:55:07.159   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 16:55:07.160   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 16:55:07.160   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 16:55:07.160   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 16:55:07.160   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 16:55:07.173   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 16:55:07.173   873  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.26 rxSuccessRate=0.30 delta 1000 -> 1000
,08-26 16:55:07.174   373   871 D CommandListener: Setting iface cfg
08-26 16:55:07.175   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 16:55:07.175   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 16:55:07.183   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 16:55:07.185   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 16:55:07.190   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 16:55:07.190   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:55:07.213   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 16:55:07.282   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 16:55:07.284  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 16:55:07.572  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 16:55:07.572  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 16:55:07.611   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 16:55:07.611  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8108923 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@54069f8, 16908290=android.view.AbsSavedState$1@54069f8}, android:focusedViewId=100}]}]
08-26 16:55:07.611  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 16:55:07.612  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 16:55:07.612  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 16:55:07.615   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 16:55:07.619   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 16:55:07.620   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-26 16:55:07.620   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 16:55:07.641   873   882 I art     : Background partial concurrent mark sweep GC freed 13326(867KB) AllocSpace objects, 3(136KB) LOS objects, 33% free, 28MB/43MB, paused 1.658ms total 110.906ms
,08-26 16:55:07.775  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 16:55:07.811  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 16:55:07.811  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 16:55:07.814   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 16:55:07.823   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 16:55:07.823   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 16:55:07.824   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:55:07.834   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 16:55:07.835   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,08-26 16:55:07.838   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 16:55:07.838   873  1342 D SurfaceControl: Excessive delay in setPowerMode(): 219ms
,08-26 16:55:07.845   873   893 I DreamManagerService: Entering dreamland.
,08-26 16:55:07.846   873   893 I PowerManagerService: Dozing...
,08-26 16:55:07.847   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 16:55:07.849   373   871 D CommandListener: Setting iface cfg
,08-26 16:55:07.850   873  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 16:55:07.865   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 16:55:07.865   873  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-26 16:55:07.868   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 16:55:07.880   873  4204 D DhcpClient: Receive thread started
,08-26 16:55:07.893   377  1324 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 16:55:07.893   377  1324 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 16:55:07.912  1950  4206 D NfcService: Discovery configuration equal, not updating.
,08-26 16:55:07.961   873  1316 E native  : do suspend false
,08-26 16:55:07.983   873  1908 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 16:55:07.995   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 16:55:07.999   873  4204 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-26 16:55:08.001   873  1908 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
08-26 16:55:08.004   873  1908 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 16:55:08.015   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 16:55:08.023   873  4204 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 16:55:08.024   873  1908 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-26 16:55:08.027   873  1316 E native  : do suspend false
08-26 16:55:08.029   373   871 D CommandListener: Setting iface cfg
,08-26 16:55:08.032   377  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-26 16:55:08.032   377  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 16:55:08.040   873  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 16:55:08.051   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-26 16:55:08.052   873  1908 D DhcpClient: Scheduling renewal in 86399s
08-26 16:55:08.053   873  1316 E native  : do suspend true
,08-26 16:55:08.069   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 16:55:08.072   873  1316 D WifiConfigStore: No blacklist allowed without epno enabled
08-26 16:55:08.073   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 16:55:08.075   873  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 16:55:08.097   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:08.124  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:08.128   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 16:55:08.129   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 16:55:08.130  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:55:08.131   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 16:55:08.132   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 16:55:08.133   873  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 16:55:08.141  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 16:55:08.142   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 16:55:08.142  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 16:55:08.143  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8108923 Bundle[{}]
,08-26 16:55:08.144  3801  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 16:55:08.144  3801  3850 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 16:55:08.145  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 16:55:08.145  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 16:55:08.146  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 16:55:08.146  3801  3850 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 16:55:08.147   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-26 16:55:08.147   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 16:55:08.147   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-26 16:55:08.147   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 16:55:08.147   873  1318 D ConnectivityService:    accepting network in place of null
,08-26 16:55:08.148   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 16:55:08.149   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 16:55:08.151  3801  3850 I System.out: Running OutgoingSocketThread
,08-26 16:55:08.152  3801  4214 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 421)
08-26 16:55:08.153  3801  4214 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41808
,08-26 16:55:08.153  3801  4214 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 16:55:08.160   873  4203 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151420, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 16:55:08.177   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:55:08.207   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 16:55:08.212   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 16:55:08.213   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:55:08.221   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 16:55:08.222   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:08.234  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:08.237  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:55:08.247  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 16:55:08.256  1719  1719 D SystemUpdateService: onCreate
,08-26 16:55:08.260  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 16:55:08.261   873  4202 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:814::200e
,08-26 16:55:08.281  1719  4219 I SystemUpdateService: active receiver: enabled
,08-26 16:55:08.284  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 16:55:08.287  1719  2459 I iu.UploadsManager: num queued entries: 0
,08-26 16:55:08.287  1719  2459 I iu.UploadsManager: num updated entries: 0
,08-26 16:55:08.288  1719  2459 I iu.SyncManager: NEXT; no task
,08-26 16:55:08.297  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 16:55:08.299  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-26 16:55:08.300  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:55:08.307  1719  4222 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 16:55:08.307  1719  4222 W BaseAppContext: Using Auth Proxy for data requests.,
,08-26 16:55:08.309  3938  3938 D SprintDMHelper: simOperator: 
,08-26 16:55:08.309  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,08-26 16:55:08.315  1719  4222 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 16:55:08.318  1719  4219 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 16:55:08.321  1719  4219 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 16:55:08.321  1719  4219 I SystemUpdateService: now status is 0 (complete)
,08-26 16:55:08.321  1719  4219 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 16:55:08.332  1719  4219 I SystemUpdateService: file has been verified
08-26 16:55:08.333  1719  4219 I SystemUpdateService: OTA package size = 12249756
,08-26 16:55:08.339   873  4202 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 14:55:08 GMT], X-Android-Received-Millis=[1472223308338], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472223308306]}
,08-26 16:55:08.340   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 16:55:08.341   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-26 16:55:08.341   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 16:55:08.350   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 16:55:08.351  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 16:55:08.354  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 16:55:08.355  1719  4219 I SystemUpdateService: showing system update notification
,08-26 16:55:08.389  1719  1719 D SystemUpdateService: onDestroy
,08-26 16:55:08.390  1511  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-26 16:55:08.390  1511  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 16:55:08.390  1511  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 16:55:08.390  1511  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 16:55:08.408  1719  4222 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-26 16:55:08.458  2213  4224 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 16:55:09.154  3801  3850 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 422)
,08-26 16:55:09.154  3801  3850 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 422)
,08-26 16:55:09.164  3801  3850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-26 16:55:09.166  3801  3850 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 16:55:09.166  3801  3850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 428)
,08-26 16:55:09.172  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.172  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a86ded1 added. We now have 2 listener(s)
,08-26 16:55:09.174  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.174  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.174  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 16:55:09.174  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:09.174  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f6bd36 added. We now have 9 listener(s)
08-26 16:55:09.174  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.175  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:09.178  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:09.184  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:09.187  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:55:09.187  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:09.188  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:09.188  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2da4 added. We now have 3 listener(s)
,08-26 16:55:09.191  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:09.192  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 16:55:09.192  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.192  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.192  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.192  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9970d added. We now have 10 listener(s)
,08-26 16:55:09.193  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:09.193  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:09.193  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:09.193  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:09.193  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:55:09.193  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.193  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:09.193  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 16:55:09.193  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a86ded1 removed from the list
,08-26 16:55:09.194  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.194  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f6bd36 removed from the list
08-26 16:55:09.196  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:09.196  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:55:09.196  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.197  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.197  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.198  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.198  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:55:09.198  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:55:09.198  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f6bd36 not in the list
08-26 16:55:09.198  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.198  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.200  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.200  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:55:09.200  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.200  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9970d removed from the list
08-26 16:55:09.200  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.200  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.200  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.200  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.200  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2da4 removed from the list
08-26 16:55:09.201  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.201  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae976c2 added. We now have 2 listener(s)
08-26 16:55:09.203  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.203  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.203  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 16:55:09.204  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.204  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dcd3 added. We now have 9 listener(s)
08-26 16:55:09.204  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.204  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:09.207  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:09.211   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:09.211  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:09.213  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.214  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:09.214  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:09.214  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e059709 added. We now have 3 listener(s)
08-26 16:55:09.216  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.216  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 16:55:09.216  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.216  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.216  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65c3d0e added. We now have 10 listener(s)
08-26 16:55:09.216  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.216  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:09.217  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:55:09.217  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:55:09.217  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:09.217  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 16:55:09.220  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:09.226  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:09.226  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 16:55:09.226  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 16:55:09.232  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:55:09.233  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 16:55:09.233  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:55:09.238  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 16:55:09.238  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 16:55:09.238  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 16:55:09.239  3801  3850 D BluetoothAdapter: STATE_ON
,08-26 16:55:09.244  4145  4186 D BtGatt.GattService: registerClient() - UUID=aacd5155-3bce-4c25-8abe-549abe5556fa
,08-26 16:55:09.245  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=aacd5155-3bce-4c25-8abe-549abe5556fa, clientIf=5
,08-26 16:55:09.246  3801  4034 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 16:55:09.247  4145  4174 D BtGatt.GattService: start scan with filters
,08-26 16:55:09.251  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 16:55:09.251  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 16:55:09.251  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 16:55:09.251  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 16:55:09.251  4145  4164 D BtGatt.ScanManager: handling starting scan
,08-26 16:55:09.254  4145  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dbb87
,08-26 16:55:09.254  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 16:55:09.255  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 16:55:09.256  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 16:55:09.257  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:55:09.259  4145  4161 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 16:55:09.259  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.260  4145  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 16:55:09.260  3801  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 16:55:09.260  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:09.260  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 16:55:09.260  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.260  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 16:55:09.260  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 16:55:09.261  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:55:09.261  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 16:55:09.261  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 16:55:09.261  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:55:09.261  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 16:55:09.262  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:55:09.262  4145  4155 D BtGatt.GattService: stopScan() - queue size =1
,08-26 16:55:09.263  4145  4186 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 16:55:09.264  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 16:55:09.264  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 16:55:09.264  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 16:55:09.264  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 16:55:09.264  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 16:55:09.265  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:55:09.265  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 16:55:09.265  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:55:09.265  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 16:55:09.266  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.268  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:55:09.268  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:55:09.268  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:55:09.271  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:55:09.272  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 16:55:09.272  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.271  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:55:09.272  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:09.272  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:55:09.272  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.272  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.272  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.273  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae976c2 removed from the list
,08-26 16:55:09.273  4145  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-26 16:55:09.273  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 16:55:09.273  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dcd3 removed from the list
,08-26 16:55:09.273  4145  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 16:55:09.273  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:55:09.273  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.274  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.274  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.275  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.275  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:55:09.275  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 16:55:09.275  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2dcd3 not in the list
,08-26 16:55:09.275  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.276  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.276  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.277  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:55:09.277  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:55:09.277  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65c3d0e removed from the list
,08-26 16:55:09.277  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.277  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.277  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.277  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 16:55:09.277  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e059709 removed from the list
,08-26 16:55:09.278  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.278  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7231c1a added. We now have 2 listener(s)
08-26 16:55:09.280  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 16:55:09.280  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 16:55:09.280  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.280  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:09.281  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29f134b added. We now have 9 listener(s)
,08-26 16:55:09.281  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.281  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 16:55:09.284  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:09.289  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:09.292  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.292  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:55:09.293  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.293  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42c1e41 added. We now have 3 listener(s)
,08-26 16:55:09.295  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 16:55:09.295  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 16:55:09.295  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,08-26 16:55:09.295  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.295  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 16:55:09.295  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f46dfe6 added. We now have 10 listener(s)
,08-26 16:55:09.295  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.296  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:09.297  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:09.297  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 16:55:09.298  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 16:55:09.298  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:09.298  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:55:09.298  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 16:55:09.299  4145  4161 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 16:55:09.299  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.301  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 16:55:09.301  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 16:55:09.305  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 16:55:09.306  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 16:55:09.306  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.306  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 16:55:09.306  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:55:09.310  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 16:55:09.310  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 16:55:09.310  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 16:55:09.311  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:55:09.313  4145  4183 D BtGatt.GattService: registerClient() - UUID=01a5d7c8-f99e-4679-aec4-9cf5a5518da3
08-26 16:55:09.313  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=01a5d7c8-f99e-4679-aec4-9cf5a5518da3, clientIf=5
,08-26 16:55:09.314  3801  4034 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 16:55:09.314  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 16:55:09.314  4145  4182 D BtGatt.GattService: start scan with filters
08-26 16:55:09.314  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.315  4145  4164 D BtGatt.ScanManager: stopping BLe Batch
,08-26 16:55:09.317  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 16:55:09.317  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 16:55:09.317  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 16:55:09.317  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 16:55:09.319  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 16:55:09.319  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 16:55:09.320  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-26 16:55:09.320  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 16:55:09.320  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.320  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 16:55:09.321  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:55:09.323  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:09.324  3801  3850 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 16:55:09.324  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:09.324  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:09.324  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:55:09.324  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.324  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.324  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 16:55:09.324  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.325  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7231c1a removed from the list
08-26 16:55:09.325  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.325  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29f134b removed from the list
08-26 16:55:09.325  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:09.325  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.325  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.325  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 16:55:09.325  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 16:55:09.325  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.325  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.325  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.326  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.326  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.326  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.326  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29f134b not in the list
08-26 16:55:09.327  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:55:09.327  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 16:55:09.327  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 16:55:09.327  4145  4164 D BtGatt.ScanManager: handling starting scan
08-26 16:55:09.327  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:55:09.327  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 16:55:09.327  3801  3850 D BluetoothAdapter: STATE_ON
08-26 16:55:09.328  4145  4183 D BtGatt.GattService: stopScan() - queue size =1
,08-26 16:55:09.328  4145  4182 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 16:55:09.329  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 16:55:09.329  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 16:55:09.329  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 16:55:09.329  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 16:55:09.329  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 16:55:09.331  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:55:09.331  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 16:55:09.331  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:55:09.331  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:55:09.331  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.332  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:55:09.332  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:55:09.332  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:55:09.332  4145  4161 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 16:55:09.333  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.333  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:55:09.333  4145  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 16:55:09.333  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.333  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.333  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f46dfe6 removed from the list
08-26 16:55:09.333  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.333  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.333  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.333  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.333  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42c1e41 removed from the list
08-26 16:55:09.334  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.334  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6911472 added. We now have 2 listener(s)
08-26 16:55:09.336  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.336  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 16:55:09.336  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.337  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.337  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ca0c3 added. We now have 9 listener(s)
,08-26 16:55:09.337  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.337  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 16:55:09.338  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 16:55:09.338  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.338  4145  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-26 16:55:09.339  4145  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 16:55:09.341  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:09.344  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:09.346  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:55:09.346  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:55:09.347  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 16:55:09.347  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2455479 added. We now have 3 listener(s)
08-26 16:55:09.349  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:09.349  4145  4161 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 16:55:09.349  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.350  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.350  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.350  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.350  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:09.350  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d805be added. We now have 10 listener(s)
08-26 16:55:09.351  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:09.351  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:09.351  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:55:09.351  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:55:09.351  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:55:09.351  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:09.351  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 16:55:09.354  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 16:55:09.354  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.354  3801  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 16:55:09.355  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 16:55:09.358  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:55:09.358  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 16:55:09.358  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:55:09.360  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 16:55:09.360  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.360  4145  4164 D BtGatt.ScanManager: stopping BLe Batch
,08-26 16:55:09.361  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 16:55:09.361  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 16:55:09.361  3801  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 16:55:09.362  3801  3850 D BluetoothAdapter: STATE_ON,
,08-26 16:55:09.363  4145  4186 D BtGatt.GattService: registerClient() - UUID=e74ea138-7f90-4d31-9653-f862b29dcec1
,08-26 16:55:09.364  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=e74ea138-7f90-4d31-9653-f862b29dcec1, clientIf=5
08-26 16:55:09.364  3801  4033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 16:55:09.364  4145  4183 D BtGatt.GattService: start scan with filters
,08-26 16:55:09.366  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 16:55:09.366  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 16:55:09.366  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.366  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 16:55:09.366  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 16:55:09.366  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 16:55:09.366  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 16:55:09.368  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:55:09.368  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 16:55:09.368  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 16:55:09.370  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 16:55:09.371  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 16:55:09.371  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.372  4145  4164 D BtGatt.ScanManager: handling starting scan,
,08-26 16:55:09.374  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:55:09.374  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:09.374  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:55:09.374  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.374  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.374  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 16:55:09.374  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.374  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6911472 removed from the list
08-26 16:55:09.374  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.374  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ca0c3 removed from the list
,08-26 16:55:09.375  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:09.375  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.375  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.375  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 16:55:09.375  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.375  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.376  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ca0c3 not in the list
,08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:55:09.376  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 16:55:09.376  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:55:09.376  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 16:55:09.377  3801  3850 D BluetoothAdapter: STATE_ON
,08-26 16:55:09.377  4145  4155 D BtGatt.GattService: stopScan() - queue size =1
,08-26 16:55:09.378  4145  4161 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 16:55:09.378  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.378  4145  4186 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 16:55:09.378  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:55:09.378  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 16:55:09.378  4145  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 16:55:09.378  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 16:55:09.378  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 16:55:09.378  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 16:55:09.379  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 16:55:09.379  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 16:55:09.379  3801  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:55:09.379  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:55:09.380  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.381  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.381  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.381  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.381  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 16:55:09.381  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d805be removed from the list
08-26 16:55:09.381  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.381  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.381  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.381  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:55:09.381  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.381  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2455479 removed from the list
,08-26 16:55:09.381  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:55:09.382  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:09.382  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0abfca added. We now have 2 listener(s)
08-26 16:55:09.383  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 16:55:09.383  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.384  4145  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-26 16:55:09.384  4145  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 16:55:09.384  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.384  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.384  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:09.384  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:09.384  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3f653b added. We now have 9 listener(s)
08-26 16:55:09.384  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.385  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:09.387  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:09.390  3801  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:09.391  3801  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 16:55:09.392  3801  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:55:09.392  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:09.392  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1819b1 added. We now have 3 listener(s)
08-26 16:55:09.393  4145  4161 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 16:55:09.393  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.394  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:09.394  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 16:55:09.395  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:09.395  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-26 16:55:09.395  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.395  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fd0e96 added. We now have 10 listener(s)
,08-26 16:55:09.395  3801  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.395  3801  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:55:09.395  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:55:09.395  3801  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:09.396  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.396  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.396  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:09.396  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:09.396  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.396  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0abfca removed from the list
08-26 16:55:09.396  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:55:09.396  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3f653b removed from the list
08-26 16:55:09.396  3801  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:55:09.396  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.397  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.397  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.398  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 16:55:09.398  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.398  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.398  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 16:55:09.398  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:09.398  3801  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3f653b not in the list
08-26 16:55:09.398  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:09.398  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:09.399  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:09.399  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:09.399  3801  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:55:09.400  3801  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fd0e96 removed from the list
08-26 16:55:09.400  3801  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:09.400  3801  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:55:09.400  3801  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:09.400  3801  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:09.400  3801  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1819b1 removed from the list
08-26 16:55:09.401  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-26 16:55:09.401  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 16:55:09.402  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
08-26 16:55:09.402  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:09.402  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 16:55:09.402  3801  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 16:55:09.404  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 16:55:09.404  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.404  4145  4164 D BtGatt.ScanManager: stopping BLe Batch
08-26 16:55:09.408  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 16:55:09.409  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 16:55:09.409  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 16:55:09.410  3801  4232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: My test thread name)
08-26 16:55:09.410  3801  4232 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: My test thread name)
,08-26 16:55:09.411  3801  4232 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 16:55:09.413  3801  4233 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,08-26 16:55:09.413  3801  4233 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-26 16:55:09.413  3801  4233 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 16:55:09.414  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 16:55:09.414  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 16:55:09.415  3801  3850 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 16:55:09.415  3801  3850 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 16:55:09.415  3801  3850 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 16:55:09.416  3801  3850 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 16:55:09.416  3801  3850 D com.test.thalitest.ThaliTestRunner: Total duration: 22681 ms,
,08-26 16:55:09.417  3801  3850 I jxcore-log: *Native tests were executed*
08-26 16:55:09.417  3801  3850 I jxcore-log: 
,08-26 16:55:09.418  3801  3850 I jxcore-log: Total number of executed tests:  80
08-26 16:55:09.418  3801  3850 I jxcore-log: 
08-26 16:55:09.418  3801  3850 I jxcore-log: Number of passed tests:  80
08-26 16:55:09.418  3801  3850 I jxcore-log: 
08-26 16:55:09.418  3801  3850 I jxcore-log: Number of failed tests:  0
08-26 16:55:09.418  3801  3850 I jxcore-log: 
,08-26 16:55:09.418  3801  3850 I jxcore-log: Number of ignored tests:  0
08-26 16:55:09.418  3801  3850 I jxcore-log: 
08-26 16:55:09.419  3801  3850 I jxcore-log: Total duration:  22681
08-26 16:55:09.419  3801  3850 I jxcore-log: 
08-26 16:55:09.419  3801  3850 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 16:55:09.419  3801  3850 I jxcore-log: 
,08-26 16:55:09.423  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.423  3801  3850 I jxcore-log: 
08-26 16:55:09.427  3801  3801 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 16:55:09.428  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.428  3801  3850 I jxcore-log: 
08-26 16:55:09.429  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.429  3801  3850 I jxcore-log: 
08-26 16:55:09.430  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.430  3801  3850 I jxcore-log: 
08-26 16:55:09.431  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.431  3801  3850 I jxcore-log: 
08-26 16:55:09.432  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.432  3801  3850 I jxcore-log: 
08-26 16:55:09.435  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.435  3801  3850 I jxcore-log: 
08-26 16:55:09.436  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.436  3801  3850 I jxcore-log: 
08-26 16:55:09.437  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.437  3801  3850 I jxcore-log: 
,08-26 16:55:09.438  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.438  3801  3850 I jxcore-log: 
08-26 16:55:09.438  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.438  3801  3850 I jxcore-log: 
08-26 16:55:09.439  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 16:55:09.439  3801  3850 I jxcore-log: 
08-26 16:55:09.440  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.440  3801  3850 I jxcore-log: 
,08-26 16:55:09.441  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.441  3801  3850 I jxcore-log: 
,08-26 16:55:09.442  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.442  3801  3850 I jxcore-log: 
,08-26 16:55:09.442  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.442  3801  3850 I jxcore-log: 
08-26 16:55:09.443  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.443  3801  3850 I jxcore-log: 
08-26 16:55:09.443  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.443  3801  3850 I jxcore-log: 
08-26 16:55:09.444  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.444  3801  3850 I jxcore-log: 
08-26 16:55:09.445  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.445  3801  3850 I jxcore-log: 
08-26 16:55:09.445  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.445  3801  3850 I jxcore-log: 
08-26 16:55:09.446  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.446  3801  3850 I jxcore-log: 
,08-26 16:55:09.446  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.446  3801  3850 I jxcore-log: 
08-26 16:55:09.447  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:09.447  3801  3850 I jxcore-log: 
08-26 16:55:09.448  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.448  3801  3850 I jxcore-log: 
08-26 16:55:09.448  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 16:55:09.448  3801  3850 I jxcore-log: 
08-26 16:55:09.449  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-26 16:55:09.449  3801  3850 I jxcore-log: 
,08-26 16:55:09.450  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.450  3801  3850 I jxcore-log: 
08-26 16:55:09.450  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.450  3801  3850 I jxcore-log: 
08-26 16:55:09.451  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.451  3801  3850 I jxcore-log: 
08-26 16:55:09.452  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.452  3801  3850 I jxcore-log: 
08-26 16:55:09.452  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:09.452  3801  3850 I jxcore-log: 
,08-26 16:55:09.768  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 16:55:09.770  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 16:55:09.770  3801  3850 I jxcore-log: 
,08-26 16:55:09.833  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 16:55:09.834  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 16:55:09.834  3801  3850 I jxcore-log: 
,08-26 16:55:09.882  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 16:55:09.884  3801  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 16:55:09.884  3801  3850 I jxcore-log: 
,08-26 16:55:10.054  4234  4234 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 16:55:10.059  4234  4234 D AndroidRuntime: CheckJNI is OFF
,08-26 16:55:10.102  4234  4234 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 16:55:10.169  4234  4234 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 16:55:10.195  4234  4234 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 16:55:10.208   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 16:55:10.208   873   886 I ActivityManager: Killing 3801:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 16:55:10.278   873  2098 D GraphicsStats: Buffer count: 2
08-26 16:55:10.278   873  1317 D WifiService: Client connection lost with reason: 4
08-26 16:55:10.279   873   884 I WindowState: WIN DEATH: Window{361fbb4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 16:55:10.324   873   896 W PackageSettings: Skipping PackageSetting{8c6a758 com.example.hello/10273} due to missing metadata
,08-26 16:55:10.349   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 16:55:10.349   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 16:55:10.350   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-26 16:55:10.350   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 16:55:10.350   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.350   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.350   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 16:55:10.350   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 16:55:10.350   873   886 I ActivityManager:   Force finishing activity ActivityRecord{76f8045 u0 com.test.thalitest/.MainActivity t2}
08-26 16:55:10.356   873   896 I art     : Starting a blocking GC Explicit
,08-26 16:55:10.360   873   883 W ActivityManager: Spurious death for ProcessRecord{ce9663a 0:com.test.thalitest/u0a0}, curProc for 3801: null
,08-26 16:55:10.400   873   896 I art     : Explicit concurrent mark sweep GC freed 41572(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 794us total 44.429ms
08-26 16:55:10.421   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 16:55:10.428  4234  4234 I art     : System.exit called, status: 0
,08-26 16:55:10.428  4234  4234 I AndroidRuntime: VM exiting with result code 0.
,08-26 16:55:10.432   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 16:55:10.445   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 16:55:10.451  4145  4145 D BluetoothMapAppObserver: onReceive
08-26 16:55:10.451  4145  4145 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 16:55:10.455  1894  2233 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 16:55:10.458   873  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 16:55:10.460  3629  3629 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 16:55:10.479  1880  1880 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 16:55:10.492  1965  1965 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 16:55:10.502  1880  4247 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 16:55:10.508   873  1986 I ActivityManager: Start proc 4248:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 16:55:10.529  1880  4247 I Decoder : createOrResetDecoder
,08-26 16:55:10.538   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 16:55:10.544  1511  1511 I ConfigService: onCreate
,08-26 16:55:10.546  4248  4248 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 16:55:10.557  1880  4247 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 16:55:10.569   873  1400 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3801 uid 10000
,08-26 16:55:10.570  1880  1880 I Keyboard.Facilitator: onFinishInput()
,08-26 16:55:10.575  1978  2073 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 16:55:10.575   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 16:55:10.576   873   885 E PackageManager: Failed to write settings, restoring backup
08-26 16:55:10.576   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 16:55:10.576   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 16:55:10.576   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 16:55:10.576   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 16:55:10.576   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 16:55:10.576   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.576   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.576   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 16:55:10.577   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-26 16:55:10.577   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 16:55:10.577   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.577   873   886 E DropBoxManagerService: 	... 13 more
,08-26 16:55:10.587   873  2097 I ActivityManager: Start proc 4261:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 16:55:10.587  1978  2073 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 16:55:10.587  1978  2073 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1978
08-26 16:55:10.587  1978  2073 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.587  1978  2073 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 16:55:10.593   873  2076 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 16:55:10.597  1978  2073 I Process : Sending signal. PID: 1978 SIG: 9
,08-26 16:55:10.607  1880  4247 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 16:55:10.607   873  4269 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.607   873  4269 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.607   873  4269 E DropBoxManagerService: 	... 5 more
08-26 16:55:10.609   873  1343 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-26 16:55:10.609  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 16:55:10.609  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-26 16:55:10.609   873  1343 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-26 16:55:10.609   873  1343 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-26 16:55:10.609   873  1343 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-26 16:55:10.609   873  1343 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-26 16:55:10.609   873  1343 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-26 16:55:10.609   873  1343 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-26 16:55:10.609   873  1343 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,08-26 16:55:10.610   873  1343 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-26 16:55:10.610   873  1343 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-26 16:55:10.610   873  1343 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-26 16:55:10.610   873  1343 W System.err: 	... 4 more
08-26 16:55:10.610   873  1343 D skia    : ------- write threw an exception
,08-26 16:55:10.625  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 16:55:10.625  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 16:55:10.632  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-26 16:55:10.632  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 16:55:10.634  1880  4247 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-26 16:55:10.634  1880  4247 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 16:55:10.635  1880  4247 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-26 16:55:10.636  1880  4247 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-26 16:55:10.636  1880  4247 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 16:55:10.636  1880  4247 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-26 16:55:10.636  4248  4248 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 16:55:10.647  4248  4278 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 16:55:10.656  4248  4266 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.656  4248  4266 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 16:55:10.656   873   883 I ActivityManager: Start proc 4279:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694),
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.658  4248  4266 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 16:55:10.673   873   884 D GraphicsStats: Buffer count: 1
,08-26 16:55:10.673   873  2095 I WindowState: WIN DEATH: Window{7f53a98 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 16:55:10.689   873  1696 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1978) has died
08-26 16:55:10.690   873  1696 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 16:55:10.691   873  1696 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 16:55:10.705  4279  4279 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 16:55:10.710   873   886 I ActivityManager: Start proc 4292:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 16:55:10.733  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 16:55:10.734  1511  1511 D AndroidRuntime: Shutting down VM
08-26 16:55:10.735  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-26 16:55:10.735  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-26 16:55:10.735  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 16:55:10.735  1511  1511 E AndroidRuntime: 	... 8 more
,08-26 16:55:10.739   873  4307 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.739   873  4307 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.739   873  4307 E DropBoxManagerService: 	... 5 more
,08-26 16:55:10.742  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405),
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:55:10.755  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:55:10.755  4292  4292 D AndroidRuntime: Shutting down VM
08-26 16:55:10.757   873  1696 I ActivityManager: Killing 3687:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 16:55:10.778  4248  4266 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 16:55:10.784  4248  4278 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.784  4248  4278 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 16:55:10.785  4248  4278 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 16:55:10.785  4248  4278 E AndroidRuntime: Process: android.process.acore, PID: 4248
08-26 16:55:10.785  4248  4278 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.785  4248  4278 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 16:55:10.787  4248  4266 I Process : Sending signal. PID: 4248 SIG: 9
,08-26 16:55:10.791   873  1317 D WifiService: Client connection lost with reason: 4
,08-26 16:55:10.813   873  2289 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
,08-26 16:55:10.813   873  2289 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,08-26 16:55:10.814   873  2289 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
,08-26 16:55:10.814   873  2289 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
,08-26 16:55:10.814   873  2289 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,08-26 16:55:10.816  4292  4292 E AndroidRuntime: FATAL EXCEPTION: main
08-26 16:55:10.816  4292  4292 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4292
08-26 16:55:10.816  4292  4292 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 16:55:10.816  4292  4292 E AndroidRuntime: 	... 10 more
08-26 16:55:10.819  1719  1719 W RocketImpressions: ClearcutLogger connection suspended: 1
08-26 16:55:10.821   873  4310 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.821   873  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.821   873  4310 E DropBoxManagerService: 	... 5 more
,08-26 16:55:10.838   873  1696 I ActivityManager: Start proc 4312:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-26 16:55:10.842   873  1695 I ActivityManager: Process android.process.acore (pid 4248) has died
,08-26 16:55:10.842   873  1695 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40971ms
08-26 16:55:10.844   873  2289 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 16:55:10.849  4292  4292 I Process : Sending signal. PID: 4292 SIG: 9
,08-26 16:55:10.851   873  4322 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.851   873  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.851   873  4322 E DropBoxManagerService: 	... 5 more
,08-26 16:55:10.873  4312  4312 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-26 16:55:10.879  4312  4312 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 16:55:10.883  4312  4312 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:55:10.883  4312  4312 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 16:55:10.884  4312  4312 D AndroidRuntime: Shutting down VM
08-26 16:55:10.884  4312  4312 E AndroidRuntime: FATAL EXCEPTION: main
08-26 16:55:10.884  4312  4312 E AndroidRuntime: Process: com.google.process.gapps, PID: 4312
08-26 16:55:10.884  4312  4312 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 16:55:10.884  4312  4312 E AndroidRuntime: 	... 10 more
,08-26 16:55:10.888   873  4327 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.888   873  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.888   873  4327 E DropBoxManagerService: 	... 5 more
,08-26 16:55:10.890   873  2003 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4292) has died
,08-26 16:55:10.890  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 16:55:10.890  1719  1719 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 16:55:10.891   873  2003 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 16:55:10.896  4312  4312 I Process : Sending signal. PID: 4312 SIG: 9
,08-26 16:55:10.897  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 16:55:10.897  1719  1719 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 16:55:10.902  1719  4328 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 16:55:10.907   873   886 I ActivityManager: Start proc 4330:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 16:55:10.918  1719  4328 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-26 16:55:10.918  1719  4328 E AndroidRuntime: Process: com.google.android.gms, PID: 1719
08-26 16:55:10.918  1719  4328 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 16:55:10.918  1719  4328 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-26 16:55:10.921   873  4343 E DropBoxManagerService: Can't write: system_app_crash
08-26 16:55:10.921   873  4343 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 16:55:10.921   873  4343 E DropBoxManagerService: 	... 5 more
,08-26 16:55:10.924  1719  4328 I Process : Sending signal. PID: 1719 SIG: 9
,08-26 16:55:10.934   873  1400 I ActivityManager: Process com.google.process.gapps (pid 4312) has died
,08-26 16:55:10.934   873  1400 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{d0cdcfa u0 com.google.android.gms/.config.ConfigService}
,08-26 16:55:10.934   873  1400 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{97b8db2 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-26 16:55:10.935   873  1400 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8981485 u0 com.google.android.gms/.auth.GetToken}
08-26 16:55:10.935   873  1400 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6412dbf u0 com.google.android.gms/.gcm.GcmService}
,08-26 16:55:10.946   873  1400 I ActivityManager: Start proc 4344:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-26 16:55:10.948  2033  4341 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-26 16:55:10.959   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
