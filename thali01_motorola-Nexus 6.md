#### Test 814185776bb1ff3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 09:53:51.890  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:53:51.897  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 09:53:51.900  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 09:53:51.932  1529  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 09:53:51.932  1529  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 09:53:51.932  1529  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:53:51.932  1529  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 09:53:51.970  3654  3654 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 09:53:51.971  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 09:53:51.972  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-29 09:53:52.526  3926  3926 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 09:53:52.531  3926  3926 D AndroidRuntime: CheckJNI is OFF
08-29 09:53:52.574  3926  3926 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 09:53:52.623  3926  3926 I Radio-JNI: register_android_hardware_Radio DONE
08-29 09:53:52.646  3926  3926 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 09:53:52.650   873  1379 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 09:53:52.699  1992  3885 W SearchService: Abort, client detached.
08-29 09:53:52.700  3926  3926 D AndroidRuntime: Shutting down VM
08-29 09:53:52.711  1992  2325 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c517cc9
08-29 09:53:52.712  1992  2336 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 09:53:52.711  1992  1992 I HotwordDetector: Closing mic
08-29 09:53:52.732   873  2176 I ActivityManager: Start proc 3935:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 09:53:52.775   377  2338 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 09:53:52.776   377  2338 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 09:53:52.789   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 09:53:52.793  1992  2331 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 09:53:52.794  1992  2335 I MicroRecognitionRnrImpl: Detection finished
08-29 09:53:52.809  3935  3935 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 09:53:52.834  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 09:53:52.842  3935  3935 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 293-296)
08-29 09:53:52.842  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:53:52.857  3935  3935 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a7f7339}
08-29 09:53:52.858  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:53:52.858  3935  3935 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 09:53:52.865  3935  3935 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 09:53:52.867  3935  3935 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 09:53:52.886  3935  3935 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 09:53:52.897  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:53:52.897  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:53:52.897  3935  3935 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 09:53:52.897  3935  3935 I Adreno  : Build Date                       : 10/20/15
08-29 09:53:52.897  3935  3935 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 09:53:52.897  3935  3935 I Adreno  : Local Branch                     : M14
08-29 09:53:52.897  3935  3935 I Adreno  : Remote Branch                    : 
08-29 09:53:52.897  3935  3935 I Adreno  : Remote Branch                    : 
08-29 09:53:52.897  3935  3935 I Adreno  : Reconstruct Branch               : 
,08-29 09:53:52.962   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@873d6cf:true
,08-29 09:53:53.000  3935  3935 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 09:53:53.013  3935  3935 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 09:53:53.081  3935  3974 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 09:53:53.091  3935  3960 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 09:53:53.141  3935  3974 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 09:53:53.226   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms
,08-29 09:53:53.243  1860  1860 I Keyboard.Facilitator: onFinishInput()
,08-29 09:53:53.301  3935  3935 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3935
,08-29 09:53:53.431  3935  3935 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 09:53:53.532   873  1944 I ActivityManager: Killing 3361:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 09:53:53.569   873  1944 I ActivityManager: Killing 3561:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,08-29 09:53:53.685  3935  3976 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1699481296
,08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 09:53:53.696  3935  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d6246d added. We now have 1 listener(s)
08-29 09:53:53.701  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-29 09:53:53.702  3935  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:53:53.702  3935  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:53:53.703  3935  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 09:53:53.707  3935  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764f4f0 added. We now have 1 listener(s)
08-29 09:53:53.707  3935  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:53.713   873  1316 D WifiService: New client listening to asynchronous messages
08-29 09:53:53.715  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:53:53.715  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 09:53:53.716  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 09:53:53.716  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 09:53:53.716  3935  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 09:53:53.718  3935  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:53.718  3935  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-29 09:53:53.723  3935  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:53.724  3935  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:53:53.724  3935  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 09:53:53.724  3935  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:53:53.724  3935  3976 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 09:53:53.789  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:53.791  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:53.792  3935  3935 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 09:53:54.501  3935  3986 W jxcore-log: Initializing JXcore engine
08-29 09:53:54.501  3935  3986 W jxcore-log: JXcore engine is ready
,08-29 09:53:54.541  3986  3986 W Thread-362: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 09:53:54.541  3986  3986 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12162]" dev="sockfs" ino=12162 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 09:53:54.541  3986  3986 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 09:53:54.541  3986  3986 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24544]" dev="sockfs" ino=24544 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 09:53:54.554  3935  3986 W jxcore-log: Starting JXcore engine
,08-29 09:53:54.669  3935  3986 W jxcore-log: Platform android
08-29 09:53:54.669  3935  3986 W jxcore-log: 
,08-29 09:53:54.669  3935  3986 W jxcore-log: Process ARCH arm
08-29 09:53:54.669  3935  3986 W jxcore-log: 
,08-29 09:53:54.705   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 09:53:54.909  3935  3986 I jxcore-log: JXcore Cordova bridge is ready!
08-29 09:53:54.909  3935  3986 I jxcore-log: 
,08-29 09:53:54.910  3935  3986 W jxcore-log: JXcore engine is started
,08-29 09:53:54.916  3935  3976 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 09:53:54.923  3935  3935 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 09:53:55.133   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 09:53:57.734   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 09:54:02.504  3188  3994 V KeepSync: Connecting to GoogleApiClient
,08-29 09:54:02.505   873  2198 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 09:54:02.564  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:02.567  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:02.599  1529  2326 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 09:54:02.600  1529  2326 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 09:54:02.600  1529  2326 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:02.600  1529  2326 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:02.624  1756  3995 V BaseAuthAsyncOperation: access token request failed
,08-29 09:54:02.625  3188  3994 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 09:54:02.685  1529  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 09:54:02.686  1529  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 09:54:02.686  1529  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:02.686  1529  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:02.715  3188  3994 E KeepSync: IOException
08-29 09:54:02.715  3188  3994 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 09:54:02.715  3188  3994 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 09:54:02.715  3188  3994 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 09:54:02.715  3188  3994 E KeepSync: 	... 10 more
08-29 09:54:02.715  3188  3994 W KeepSync: Sync result 2
,08-29 09:54:02.730   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 09:54:04.924  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 09:54:04.924  3935  3986 I jxcore-log: 
,08-29 09:54:04.927  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 09:54:04.927  3935  3986 I jxcore-log: 
,08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:04.942  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:04.948  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:04.950  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 09:54:04.950  3935  3986 I jxcore-log: 
08-29 09:54:04.952  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 09:54:04.952  3935  3986 I jxcore-log: 
,08-29 09:54:05.449  3935  3986 D executeNativeTests: Running unit tests
,08-29 09:54:05.507  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:05.507  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd added. We now have 2 listener(s)
,08-29 09:54:05.508  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:05.508  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:05.508  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:05.508  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:05.508  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 added. We now have 2 listener(s)
08-29 09:54:05.509  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:05.509  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:54:05.513  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.530  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:05.533  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.533  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:05.536  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 09:54:05.538  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:54:05.539  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 09:54:05.542  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.543  3935  3986 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 09:54:05.544  3935  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:54:05.544  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:54:05.545  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:54:05.545  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 09:54:05.548  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:05.549  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.550  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.550  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.551  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.551  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.551  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.552  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:05.552  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd removed from the list
,08-29 09:54:05.552  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.552  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 removed from the list
08-29 09:54:05.553  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:05.553  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.554  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.554  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.556  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.557  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:05.557  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.557  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.559  3935  3986 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 09:54:05.559  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:05.559  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.559  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.560  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.560  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.560  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.560  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.560  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.560  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.560  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.560  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.560  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.560  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.560  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.562  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.562  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.562  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.562  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
,08-29 09:54:05.566  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:54:05.566  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:54:05.567  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:54:05.568  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:54:05.568  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.568  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.568  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.568  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.568  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.568  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.568  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.568  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.569  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.569  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.569  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.569  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.569  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.569  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.569  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.570  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.570  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.570  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.570  3935  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:54:05.572  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.577  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.579  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.579  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:05.579  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:05.579  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:05.579  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:05.579  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.579  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:05.586  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.588  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:54:05.588  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:05.589  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.599  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:05.602  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:54:05.603  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:05.608  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 09:54:05.614  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 09:54:05.615  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:54:05.616  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:54:05.619  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:54:05.620  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.624  2664  2676 D BtGatt.GattService: registerClient() - UUID=c0856d62-3425-4170-aa0b-ae4f6b4879f3
08-29 09:54:05.626  2664  2708 D BtGatt.GattService: onClientRegistered() - UUID=c0856d62-3425-4170-aa0b-ae4f6b4879f3, clientIf=5
08-29 09:54:05.627  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:54:05.629  2664  2675 D BtGatt.GattService: start scan with filters
08-29 09:54:05.632  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:54:05.632  2664  2724 D BtGatt.ScanManager: handling starting scan
08-29 09:54:05.632  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:05.632  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:05.632  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:54:05.634  2664  2724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
08-29 09:54:05.635  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.635  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:54:05.635  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.636  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:54:05.638  3935  3986 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:54:05.641  2664  2708 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:54:05.641  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.642  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.642  3935  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:54:05.642  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.642  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:54:05.642  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.642  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:05.642  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:54:05.642  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:05.642  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:05.642  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:05.643  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:05.643  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:54:05.644  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.645  2664  2676 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:54:05.645  2664  2724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:54:05.645  2664  2830 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:54:05.646  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:05.646  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:05.646  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:54:05.646  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:05.646  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:05.648  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.648  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:05.648  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:05.648  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:05.649  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.650  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.650  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.650  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.650  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.650  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.650  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.650  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.650  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.650  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.650  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.651  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.651  3935  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:54:05.653  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:05.653  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.654  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.656  2664  2724 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:05.657  2664  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.658  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.659  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.660  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:05.660  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:05.660  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:05.660  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:05.660  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.660  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:05.662  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.664  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:54:05.664  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:05.666  2664  2708 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:05.666  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.667  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.669  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:05.670  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:54:05.671  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:05.673  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:05.674  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.675  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:54:05.675  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:54:05.675  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:54:05.677  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.680  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 09:54:05.680  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.680  2664  2724 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:05.680  2664  2830 D BtGatt.GattService: registerClient() - UUID=c0ab83a3-647b-4335-9ef4-1a220ed9128c
08-29 09:54:05.680  2664  2708 D BtGatt.GattService: onClientRegistered() - UUID=c0ab83a3-647b-4335-9ef4-1a220ed9128c, clientIf=5
08-29 09:54:05.681  3935  3947 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:54:05.682  2664  2819 D BtGatt.GattService: start scan with filters
08-29 09:54:05.685  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:54:05.685  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:05.685  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:05.685  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:54:05.686  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:05.686  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.686  2664  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:54:05.688  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.688  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:54:05.688  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.689  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:54:05.691  2664  2708 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:54:05.691  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.692  3935  3986 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:54:05.693  2664  2724 D BtGatt.ScanManager: handling starting scan
08-29 09:54:05.694  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.694  3935  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:54:05.694  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.694  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:54:05.695  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.695  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:05.695  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:54:05.695  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:05.695  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:05.695  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:05.695  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:05.695  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:54:05.696  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.696  2664  2830 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:54:05.696  2664  2819 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:54:05.697  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:05.697  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:05.697  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:54:05.697  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:05.697  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:05.698  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.698  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:05.698  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:05.698  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:05.698  2664  2708 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:54:05.698  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.699  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.699  2664  2724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:54:05.700  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.700  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.700  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.700  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.700  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.700  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.700  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.700  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.700  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.700  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.701  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.701  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.703  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:05.701  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.704  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.704  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.704  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.704  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.704  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.704  2664  2724 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:05.704  2664  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:05.705  3935  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:54:05.706  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.711  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.713  2664  2708 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:05.713  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.713  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.713  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:05.713  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:05.713  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:05.713  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:05.713  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.713  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:05.717  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:54:05.717  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:05.718  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:05.718  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.718  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.721  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:05.722  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:54:05.722  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:05.724  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 09:54:05.724  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.724  2664  2724 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:05.725  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.727  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:54:05.727  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:54:05.727  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:54:05.727  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.730  2664  2675 D BtGatt.GattService: registerClient() - UUID=26a07836-aee9-4fee-936a-1184184486b0
08-29 09:54:05.730  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:05.730  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.730  2664  2708 D BtGatt.GattService: onClientRegistered() - UUID=26a07836-aee9-4fee-936a-1184184486b0, clientIf=5
08-29 09:54:05.730  2664  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:54:05.730  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:54:05.731  2664  2830 D BtGatt.GattService: start scan with filters
08-29 09:54:05.736  2664  2708 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:54:05.737  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.737  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:54:05.737  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:05.737  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:05.737  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:54:05.739  2664  2724 D BtGatt.ScanManager: handling starting scan
08-29 09:54:05.739  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.739  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:54:05.739  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:05.741  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:54:05.744  3935  3986 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:54:05.745  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.745  3935  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:54:05.745  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.745  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:54:05.745  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.745  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:05.745  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:54:05.745  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:05.746  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:05.746  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:05.746  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:05.746  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:54:05.747  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:05.748  2664  2708 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:54:05.748  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.748  2664  2830 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:54:05.748  2664  2724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:54:05.749  2664  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:54:05.749  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:05.749  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:05.749  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:54:05.749  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:05.749  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:05.750  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.750  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:05.750  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:05.751  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:05.751  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.752  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.752  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.752  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.753  3935  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:54:05.753  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.753  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.753  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.753  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.753  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.753  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:05.753  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.753  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.753  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.753  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.753  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.754  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.754  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.754  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.754  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.755  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.755  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.755  3935  3986 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 09:54:05.756  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.756  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.756  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.756  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.756  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.756  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:05.756  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.756  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.756  2664  2724 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:05.756  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.757  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.757  2664  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:05.757  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.757  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.757  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.757  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.757  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.757  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.758  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.758  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.758  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.758  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.759  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:54:05.759  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.759  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.759  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.759  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.759  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.760  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.760  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.760  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.760  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.760  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.760  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.760  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.760  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.760  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.761  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.761  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.761  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.761  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.762  3935  3986 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 09:54:05.762  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.762  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.762  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.762  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.762  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.762  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.762  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.762  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.762  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.762  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.763  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.763  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.763  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.763  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.764  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.764  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.764  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.764  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.764  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 09:54:05.764  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.764  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.765  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.765  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.765  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.765  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.765  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.765  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.765  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.765  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.765  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.765  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.765  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.765  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.766  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.766  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.766  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.766  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.767  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 09:54:05.768  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:54:05.768  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:54:05.769  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:54:05.769  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:54:05.769  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:54:05.769  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.769  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.769  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.770  2664  2708 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:05.770  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.770  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.770  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.770  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.770  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.770  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.770  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.770  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.771  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.771  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.771  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.771  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.772  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.772  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.772  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.772  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.773  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:54:05.773  3935  3986 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:54:05.773  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:54:05.777  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:54:05.777  3935  3986 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:54:05.777  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:54:05.778  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:54:05.779  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:54:05.779  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 09:54:05.780  3935  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:54:05.780  3935  3986 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 09:54:05.780  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:54:05.780  3935  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:54:05.780  3935  3986 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 09:54:05.780  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:54:05.780  3935  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:54:05.780  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 09:54:05.781  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:05.781  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.783  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 09:54:05.784  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 09:54:05.784  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 09:54:05.785  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 09:54:05.785  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 09:54:05.785  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 09:54:05.785  3935  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:54:05.785  3935  3986 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 09:54:05.785  3935  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
08-29 09:54:05.786  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.786  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.786  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.786  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.786  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.786  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.786  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 09:54:05.787  3935  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:05.787  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.787  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.787  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.787  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.787  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.787  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.787  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.787  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.788  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.788  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.788  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.788  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.789  3935  3986 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 09:54:05.789  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.789  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.790  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.790  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.790  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.790  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.790  2664  2708 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 09:54:05.790  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.790  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.790  2664  2724 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:05.790  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.790  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.790  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.790  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.790  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.790  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.791  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.791  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.791  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.791  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.791  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.792  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
08-29 09:54:05.792  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 426)
08-29 09:54:05.792  3935  3986 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 09:54:05.792  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.792  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.792  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.792  3935  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
,08-29 09:54:05.792  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.793  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.793  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.793  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
,08-29 09:54:05.793  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.793  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.793  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.793  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.793  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.793  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.793  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.794  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.794  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.794  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.794  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.794  2664  2814 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-29 09:54:05.794  3935  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 09:54:05.794  3935  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-29 09:54:05.794  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:54:05.794  3935  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 09:54:05.795  3935  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:54:05.794  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 426)
,08-29 09:54:05.795  3935  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 09:54:05.795  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:54:05.795  3935  3986 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-29 09:54:05.795  3935  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:54:05.795  3935  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:54:05.795  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:54:05.795  3935  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 09:54:05.795  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:05.795  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.795  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.795  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:54:05.795  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.795  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.796  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
,08-29 09:54:05.796  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.796  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.796  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:05.796  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.796  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.796  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.796  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.797  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.797  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.797  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:05.797  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.797  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.797  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.797  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.797  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
,08-29 09:54:05.797  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.798  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.798  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:05.798  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.798  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.798  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:05.798  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.798  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.798  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.798  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.798  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.798  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:05.798  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.798  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.798  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.799  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.799  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.799  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.799  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.799  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
,08-29 09:54:05.799  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.799  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.799  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.799  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.799  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.800  2664  2708 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:05.800  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.800  2664  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:54:05.800  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.801  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:05.801  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.801  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.803  3935  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:54:05.803  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 09:54:05.804  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:54:05.805  3935  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:54:05.805  3935  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 09:54:05.806  2664  2708 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 09:54:05.806  2664  2708 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:05.806  3935  3935 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 09:54:05.806  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:54:05.806  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 09:54:05.806  3935  4001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:05.806  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.806  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:54:05.807  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 09:54:05.807  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:54:05.807  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.807  3935  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:54:05.807  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.807  3935  3935 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:54:05.807  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.807  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:54:05.808  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:05.808  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:05.808  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.808  3935  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:54:05.808  3935  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:54:05.808  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 09:54:05.808  3935  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:54:05.810  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:05.810  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.810  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.810  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:05.810  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.810  3935  3935 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:54:05.810  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:05.810  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.810  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.810  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.811  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.811  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.811  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.811  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:05.811  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.811  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.811  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.811  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.811  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:05.812  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.813  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.813  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.813  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.813  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.815  3935  3986 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 09:54:05.815  3935  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:54:05.815  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:54:05.816  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:54:05.816  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.816  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.816  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:54:05.816  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.816  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.816  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.816  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.817  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:05.817  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.817  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.817  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.817  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.817  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.817  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.818  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.819  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:05.819  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.819  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.823  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.823  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:05.823  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.823  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.823  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.824  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.824  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.824  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.824  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
,08-29 09:54:05.824  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:05.824  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.824  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.824  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.824  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.825  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.826  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.826  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.826  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.827  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:05.827  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:54:05.827  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:05.827  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:05.827  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.827  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.828  3935  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab85fd not in the list
08-29 09:54:05.828  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.828  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.828  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:05.828  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.828  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.828  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:05.828  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:05.830  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:05.830  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:05.830  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:05.830  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18952f2 not in the list
08-29 09:54:05.832  3935  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 09:54:05.832  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:54:05.832  3935  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-29 09:54:05.832  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:54:05.832  3935  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 09:54:05.832  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 09:54:05.835  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:54:05.835  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 09:54:05.836  3935  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 09:54:05.836  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:54:05.836  3935  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 09:54:05.836  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:54:05.837  3935  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 09:54:05.837  3935  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 09:54:05.838  3935  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-29 09:54:05.838  3935  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 09:54:05.838  3935  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 09:54:05.839  3935  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 09:54:05.839  3935  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 09:54:05.839  3935  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 09:54:05.840  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:05.841  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba6884 added. We now have 2 listener(s)
08-29 09:54:05.841  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:05.843  3935  3986 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 09:54:05.844   873  2176 D WifiService: setWifiEnabled: true pid=3935, uid=10000
08-29 09:54:05.844   873  2176 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:05.845  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:05.845  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74ee86d added. We now have 3 listener(s)
08-29 09:54:05.845  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:05.856  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:05.856  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b85ca2 added. We now have 4 listener(s)
08-29 09:54:05.856  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:05.858  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:05.858  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a04fd33 added. We now have 5 listener(s)
08-29 09:54:05.859  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:05.863   873  1928 D WifiService: setWifiEnabled: false pid=3935, uid=10000
,08-29 09:54:05.863   873  1928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:05.871  2664  2704 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 09:54:05.871  2664  2704 D BluetoothAdapterProperties: Setting state to 13
08-29 09:54:05.871  2664  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 09:54:05.872  2664  2704 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 09:54:05.873  2664  2704 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:54:05.874  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:05.875  2664  2708 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:05.875  2664  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 09:54:05.876  2664  2664 D BluetoothMapService: onReceive
,08-29 09:54:05.876  2664  2664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:05.876  2664  2664 D BluetoothMapService: STATE_TURNING_OFF
08-29 09:54:05.876  2664  2664 D BluetoothMapService: MAP Service closeService in
08-29 09:54:05.877  2664  2664 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 09:54:05.877  2664  2664 D ObexServerSockets0: shutdown(block = true),
08-29 09:54:05.877  2664  2664 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 09:54:05.877  2664  2841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 09:54:05.877  2664  2664 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 09:54:05.878  2664  2843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 09:54:05.878  2664  2814 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!,
,08-29 09:54:05.878  2664  2664 I BtOppRfcommListener: stopping Accept Thread
,08-29 09:54:05.879  2664  3576 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:54:05.880  2664  3576 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 09:54:05.880  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:54:05.881   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:54:05.881   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[],
,08-29 09:54:05.881   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:54:05.881   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:05.884  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.884  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.885  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:05.885  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.885  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:05.890  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.892  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.892   873  1878 D DhcpClient: Clearing IP address
,08-29 09:54:05.893   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:54:05.895  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:05.895  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.896  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:05.896  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:05.898  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.900  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.902  1529  2175 V NativeCrypto: Read error: ssl=0xaec62c00: I/O error during system call, Connection timed out
,08-29 09:54:05.902   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:05.902  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.904  1529  2175 V NativeCrypto: SSL shutdown failed: ssl=0xaec62c00: I/O error during system call, Broken pipe
,08-29 09:54:05.906   873  3269 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-29 09:54:05.907   873  1868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-29 09:54:05.908   873  1868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 09:54:05.909   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 09:54:05.909   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 09:54:05.910   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 09:54:05.913   873   886 I ActivityManager: Start proc 4005:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 09:54:05.916  2664  2664 D HeadsetService: Received stop request...Stopping profile...
08-29 09:54:05.919   396   396 E Parcel  : Reading a NULL string not supported here.
,08-29 09:54:05.922   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-29 09:54:05.924   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:54:05.924   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 09:54:05.924   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 09:54:05.927   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:05.927   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:05.927  1373  1389 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:05.928   873  1879 D DhcpClient: Receive thread stopped
08-29 09:54:05.929   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:54:05.930  2664  2664 D A2dpService: Received stop request...Stopping profile...
08-29 09:54:05.931  2664  2823 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:54:05.933  2664  2664 D HidService: Received stop request...Stopping profile...
08-29 09:54:05.933  2664  2664 D HidService: Stopping Bluetooth HidService
,08-29 09:54:05.934   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 09:54:05.934  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:05.934  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:05.934  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:05.935  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.935  2664  2664 D HealthService: Received stop request...Stopping profile...
,08-29 09:54:05.937  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:05.937  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:05.937  2664  2664 D PanService: Received stop request...Stopping profile...
,08-29 09:54:05.938  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:05.938  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:05.940   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:05.941  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:05.941  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:05.941  2664  2664 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:54:05.941  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:05.941  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:05.941  2664  2664 D BluetoothMapService: stop()
08-29 09:54:05.942  2664  2664 D BluetoothMapAppObserver: deinitObservers()
08-29 09:54:05.942  2664  2664 D BluetoothMapAppObserver: removeReceiver()
08-29 09:54:05.945  2664  2664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:54:05.946  2664  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:54:05.946  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 09:54:05.946  2664  2664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:54:05.946  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:05.946  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 09:54:05.946  2664  2708 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 09:54:05.946  2664  2664 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:54:05.946  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:05.946  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:05.947  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.948  2664  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 09:54:05.948  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:05.948  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:05.948  2664  2811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 09:54:05.948  2664  2811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:05.948  2664  2811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:05.948  2664  2811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:05.949   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 09:54:05.951  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:05.951  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:05.951  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:05.952  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.952  2664  2664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:54:05.952  2664  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:54:05.952  2177  2359 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:05.953  2664  2664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:54:05.953  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:05.953  2664  2664 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:05.953  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:05.953  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.953  2664  2664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:54:05.954  2664  2708 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 09:54:05.954  2664  2664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:54:05.955  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:05.955  1920  1935 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:05.955  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:05.955  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:05.955  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.955   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:05.956   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:05.956  2664  2664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:54:05.956  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-29 09:54:05.956  2664  2664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 09:54:05.956  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:05.957  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-29 09:54:05.957  1373  1373 D HidProfile: Bluetooth service disconnected
08-29 09:54:05.957  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:54:05.957  1373  1373 D PanProfile: Bluetooth service disconnected
08-29 09:54:05.957  1373  1373 D BluetoothMap: Proxy object disconnected
08-29 09:54:05.957  1373  1373 D MapProfile: Bluetooth service disconnected
,08-29 09:54:05.957  2664  2664 D BluetoothMapService: MAP Service closeService in
08-29 09:54:05.958  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:05.958  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:05.958  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:05.958  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:05.959  2664  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:54:05.959  2664  2704 D BluetoothAdapterProperties: Setting state to 15
08-29 09:54:05.959  2664  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 09:54:05.959  2664  2664 D BluetoothMapService: cleanup()
08-29 09:54:05.959  2664  2664 D BluetoothMapService: MAP Service closeService in
08-29 09:54:05.960   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:05.960  1920  2071 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:05.960   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:05.960  1373  4014 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:54:05.961  1373  4018 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:54:05.961  1373  1389 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:05.961  2664  2704 I BluetoothAdapterState: Entering BleOnState
08-29 09:54:05.961   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:54:05.962  1373  1979 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 09:54:05.962  1373  4016 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:54:05.963   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:05.963  1373  1398 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:54:05.965  2664  2704 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 09:54:05.965  2664  2704 D BluetoothAdapterProperties: Setting state to 16
,08-29 09:54:05.965  2664  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:54:05.970  2664  2704 D BluetoothAdapterProperties: onBleDisable
08-29 09:54:05.970  2664  2704 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:54:05.970  2664  2705 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 09:54:05.971  2664  2811 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 09:54:05.971  2664  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:05.972  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:05.972  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:05.976  2664  2708 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:05.977  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:05.977  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:05.978  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:05.980  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:05.989   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:06.006  4005  4005 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 09:54:06.012   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:06.013   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 09:54:06.014   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-29 09:54:06.017   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:06.018  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.019  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:06.025  3577  3577 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9d6246d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 09:54:06.031  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:06.037  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:06.037   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f0b213:true
,08-29 09:54:06.049   873  1928 I ActivityManager: Start proc 4028:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 09:54:06.067   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 09:54:06.068   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:54:06.080  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 09:54:06.082  4005  4005 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 09:54:06.084  4005  4005 D BluetoothMap: Create BluetoothMap proxy object
,08-29 09:54:06.092  4005  4005 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 09:54:06.104  4005  4005 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:06.109   873  1944 I ActivityManager: Killing 3123:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-29 09:54:06.179  2664  2708 I bt_hci  : shut_down
,08-29 09:54:06.180  2664  2725 D bt_hwcfg: hw_epilog_process
,08-29 09:54:06.191  2664  2725 I bt_vendor: low_power_mode_cb
,08-29 09:54:06.211  2664  2725 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:54:06.211  2664  2725 I bt_vendor: epilog_cb
,08-29 09:54:06.211  2664  2725 I bt_hci  : epilog_finished_callback
,08-29 09:54:06.218  2664  2708 I bt_hci_h4: hal_close
,08-29 09:54:06.219  2664  2708 I bt_userial_vendor: device fd = 51 close
,08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.260  4028  4028 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.260  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.261  4028  4028 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.261  4028  4028 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:06.261  4028  4028 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:06.299   873  1944 I ActivityManager: Start proc 4058:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-29 09:54:06.300   873  1944 I ActivityManager: Killing 3577:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 09:54:06.310  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:54:06.454  2664  2705 D bt_stack_manager: event_shut_down_stack finished.
,08-29 09:54:06.455  2664  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 09:54:06.457  2664  2664 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:54:06.457  2664  2664 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 09:54:06.457  2664  2664 D BtGatt.GattService: stop()
,08-29 09:54:06.457  2664  2664 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 09:54:06.458  2664  2704 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 09:54:06.459  2664  2664 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:54:06.459  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:06.460  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:06.460  2664  2664 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:54:06.460  2664  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 09:54:06.461  2664  2704 D BluetoothAdapterProperties: Setting state to 10
08-29 09:54:06.461  2664  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 09:54:06.462  2664  2704 I BluetoothAdapterState: Entering OffState
,08-29 09:54:06.463   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 09:54:06.471  4058  4058 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 09:54:06.475  2664  2664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 09:54:06.475  2664  2664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:54:06.475  2664  2705 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 09:54:06.477  2664  2664 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 09:54:06.480  2664  2705 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:54:06.488  2664  2664 I art     : System.exit called, status: 0
,08-29 09:54:06.488  2664  2664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:54:06.553  4028  4055 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 09:54:06.584   873  2176 I ActivityManager: Process com.android.bluetooth (pid 2664) has died
,08-29 09:54:06.607  4058  4058 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 09:54:06.629  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:06.630   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7488062:true
,08-29 09:54:06.649   873  2176 I ActivityManager: Start proc 4087:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 09:54:06.651  4005  4005 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding A2dpService
08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding HidService
,08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding HealthService
,08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding PanService
,08-29 09:54:06.718  4087  4087 D AdapterServiceConfig: Adding GattService
,08-29 09:54:06.719  4087  4087 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 09:54:06.722   873  3269 I ActivityManager: Killing 3618:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 09:54:06.775  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:06.790  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 09:54:06.794  1756  1756 D SystemUpdateService: onCreate
,08-29 09:54:06.800  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:54:06.805  1756  4099 I SystemUpdateService: active receiver: enabled
,08-29 09:54:06.808  1756  4099 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 09:54:06.811  1756  4099 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 09:54:06.811  1756  4099 I SystemUpdateService: now status is 0 (complete)
,08-29 09:54:06.811  1756  4099 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 09:54:06.811  1756  4099 I SystemUpdateService: file has been verified
,08-29 09:54:06.812  1756  4099 I SystemUpdateService: OTA package size = 12249756
,08-29 09:54:06.824  1756  4099 I SystemUpdateService: showing system update notification
,08-29 09:54:06.844  1756  1756 D SystemUpdateService: onDestroy
,08-29 09:54:06.854  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:54:06.859  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 09:54:06.860  1756  2424 I iu.UploadsManager: num queued entries: 0
08-29 09:54:06.860  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 09:54:06.862  1756  2424 I iu.UploadsManager: num updated entries: 0
,08-29 09:54:06.865  1756  2424 I iu.SyncManager: NEXT; no task
,08-29 09:54:06.876   873  1991 I ActivityManager: Start proc 4101:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 09:54:06.908  4101  4101 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 09:54:06.911  4101  4101 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:06.919  4101  4101 D SprintDMHelper: simOperator: 
08-29 09:54:06.919  4101  4101 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:54:06.937   873  1991 I ActivityManager: Start proc 4113:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 09:54:06.941   873  1991 I ActivityManager: Killing 1690:android.process.acore/u0a5 (adj 15): empty #17
,08-29 09:54:07.083   873  1991 I ActivityManager: Start proc 4128:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 09:54:07.086  3202  4127 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-29 09:54:07.089   873  2002 I ActivityManager: Killing 3788:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 09:54:07.169  4128  4128 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 09:54:07.230  4128  4128 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 09:54:07.230  4128  4128 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 09:54:07.230  4128  4128 I GAv4    :   adb logcat -s GAv4
,08-29 09:54:07.246  4128  4128 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:54:07.254  4128  4128 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:54:07.288  4128  4145 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:54:07.394  4128  4128 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 09:54:07.440  4128  4128 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 09:54:07.449  4128  4128 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4901-4904)
,08-29 09:54:07.449  4128  4128 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 09:54:07.463  4128  4128 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {75602dd}
,08-29 09:54:07.463  4128  4128 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 09:54:07.464  4128  4128 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 09:54:07.472  4128  4128 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 09:54:07.474  4128  4128 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 09:54:07.487  4128  4128 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 09:54:07.501  4128  4128 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 09:54:07.501  4128  4128 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 09:54:07.501  4128  4128 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 09:54:07.501  4128  4128 I Adreno  : Build Date                       : 10/20/15
08-29 09:54:07.501  4128  4128 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 09:54:07.501  4128  4128 I Adreno  : Local Branch                     : M14
08-29 09:54:07.501  4128  4128 I Adreno  : Remote Branch                    : 
08-29 09:54:07.501  4128  4128 I Adreno  : Remote Branch                    : 
08-29 09:54:07.501  4128  4128 I Adreno  : Reconstruct Branch               : 
,08-29 09:54:07.552  4128  4174 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 09:54:07.568  4128  4128 I NSApplication: Starting up...
,08-29 09:54:07.616   873   883 I ActivityManager: Start proc 4179:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 09:54:07.620   873   883 I ActivityManager: Killing 3803:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 09:54:07.699  4179  4179 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 09:54:07.895   873  3269 I ActivityManager: Killing 2254:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 09:54:08.888   873  2199 D WifiService: setWifiEnabled: true pid=3935, uid=10000
08-29 09:54:08.888   873  2199 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:08.902   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-29 09:54:08.908  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:08.909  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:08.909  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:08.909  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:08.912  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:08.913  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:08.913  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:08.913  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:08.936   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-29 09:54:08.937   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 09:54:08.938   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 09:54:08.939   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 09:54:08.939   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 09:54:08.939   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 09:54:08.939   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 09:54:08.957   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 09:54:08.958   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.62 rxSuccessRate=12.25 delta 1000 -> 994
,08-29 09:54:08.959   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:08.960   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-29 09:54:08.960   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:54:08.968   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 09:54:08.969   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 09:54:08.971   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 09:54:08.971   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:08.997   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 09:54:09.059   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 09:54:09.066  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 09:54:09.510  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:54:09.556  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 09:54:09.559  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 09:54:09.564   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 09:54:09.579   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:54:09.580   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 09:54:09.580   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:09.606   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:09.622   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:09.623   873  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 09:54:09.635   873  1317 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 09:54:09.637   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 09:54:09.652   873  4202 D DhcpClient: Receive thread started
,08-29 09:54:09.733   873  1315 E native  : do suspend false
,08-29 09:54:09.752   873  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 09:54:09.774   873  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-29 09:54:09.776   873  1878 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-29 09:54:09.779   873  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 09:54:09.794   873  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 09:54:09.795   873  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 09:54:09.799   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:09.810   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 09:54:09.812   873  1878 D DhcpClient: Scheduling renewal in 86399s
,08-29 09:54:09.830   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 09:54:09.833   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 09:54:09.833   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 09:54:09.835   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 09:54:09.842   873  1317 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 09:54:09.849   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,08-29 09:54:09.884   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 09:54:09.884   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 09:54:09.886   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 09:54:09.887   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 09:54:09.888   873  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 09:54:09.895   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 09:54:09.899   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 09:54:09.899   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 09:54:09.899   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:09.899   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 09:54:09.899   873  1317 D ConnectivityService:    accepting network in place of null
08-29 09:54:09.900   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:54:09.900   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:54:09.913   873  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137368, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:54:09.936   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:09.970   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:09.981   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 09:54:09.981   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:09.984   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 09:54:09.986   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:54:10.001  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:10.001  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:10.001  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:10.001  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:10.004  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:10.004  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:10.004  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:10.005  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:10.008   873  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:818::200e
,08-29 09:54:10.014  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 09:54:10.018  1756  1756 D SystemUpdateService: onCreate
08-29 09:54:10.022  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:54:10.027  1756  4212 I SystemUpdateService: active receiver: enabled
,08-29 09:54:10.032  1756  4212 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 09:54:10.037  1756  4212 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 09:54:10.037  1756  4212 I SystemUpdateService: now status is 0 (complete)
08-29 09:54:10.038  1756  4212 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 09:54:10.038  1756  4212 I SystemUpdateService: file has been verified
,08-29 09:54:10.038  1756  4212 I SystemUpdateService: OTA package size = 12249756
,08-29 09:54:10.041  1756  4212 I SystemUpdateService: showing system update notification
,08-29 09:54:10.050  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 09:54:10.054  1756  4216 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 09:54:10.055  1756  4216 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:54:10.055  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 09:54:10.051  1756  2424 I iu.UploadsManager: num queued entries: 0
,08-29 09:54:10.056  1756  2424 I iu.UploadsManager: num updated entries: 0
,08-29 09:54:10.056  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 09:54:10.056  1756  4216 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 09:54:10.058  1756  2424 I iu.SyncManager: NEXT; no task
,08-29 09:54:10.060  4101  4101 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:10.063  1756  1756 D SystemUpdateService: onDestroy
,08-29 09:54:10.064  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:10.065  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:10.071  4101  4101 D SprintDMHelper: simOperator: 
,08-29 09:54:10.071  4101  4101 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:54:10.088   873  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:54:10 GMT], X-Android-Received-Millis=[1472457250088], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472457250053]}
,08-29 09:54:10.092   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:54:10.092   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-29 09:54:10.092   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:10.094   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 09:54:10.096  1529  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 09:54:10.096  1529  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 09:54:10.096  1529  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:10.096  1529  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:10.119  1756  4216 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-29 09:54:10.170  1529  2326 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 09:54:10.170  1529  2326 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 09:54:10.170  1529  2326 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:10.170  1529  2326 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:10.184  3695  4219 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 09:54:10.184  3695  4219 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jdm.a(PG:82)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jcs.o(PG:406)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jcn.a(PG:1379)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jcs.i(PG:143)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at blb.a(PG:3937)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at czp.a(PG:18188)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at czp.a(PG:9081)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at czq.run(PG:1686)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 09:54:10.184  3695  4219 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jdj.a(PG:4091)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jdj.a(PG:1125)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jdm.a(PG:77)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	... 12 more
08-29 09:54:10.184  3695  4219 E HttpOperation: Caused by: faj: BadAuthentication
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at fal.a(PG:38)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	at jdj.a(PG:4089)
08-29 09:54:10.184  3695  4219 E HttpOperation: 	... 14 more
,08-29 09:54:10.211  3202  4221 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 09:54:10.218  1529  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 09:54:10.218  1529  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 09:54:10.218  1529  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:10.218  1529  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:10.236  3695  4219 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 09:54:10.236  3695  4219 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jdm.a(PG:82)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jcs.o(PG:406)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jcn.a(PG:1379)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jcs.i(PG:143)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at hec.a(PG:42)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at hee.a(PG:102)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at czr.a(PG:65)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at kka.a(PG:108)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at czp.a(PG:19176)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at czp.a(PG:9081)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at czq.run(PG:1686)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 09:54:10.236  3695  4219 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jdj.a(PG:4091)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jdj.a(PG:1125)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jdm.a(PG:77)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	... 15 more
08-29 09:54:10.236  3695  4219 E HttpOperation: Caused by: faj: BadAuthentication
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at fal.a(PG:38)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	at jdj.a(PG:4089)
08-29 09:54:10.236  3695  4219 E HttpOperation: 	... 17 more
,08-29 09:54:10.237  3695  4219 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 09:54:10.237  3695  4219 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at hec.a(PG:42)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at hee.a(PG:102)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at czr.a(PG:65)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at kka.a(PG:108)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	... 15 more
08-29 09:54:10.237  3695  4219 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at fal.a(PG:38)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 09:54:10.237  3695  4219 E ExperimentLoader: 	... 17 more
,08-29 09:54:10.335   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131692, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 09:54:10.980   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 09:54:11.667   873   883 I ActivityManager: Killing 3827:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 09:54:11.896   873  2199 D WifiService: setWifiEnabled: false pid=3935, uid=10000
,08-29 09:54:11.897   873  2199 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:11.937  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 09:54:11.944   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 09:54:11.945   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 09:54:11.945   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:54:11.946   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:11.969   873  1878 D DhcpClient: Clearing IP address
,08-29 09:54:11.969   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:54:11.973   373   871 D CommandListener: Setting iface cfg
08-29 09:54:11.977  1529  4227 V NativeCrypto: Read error: ssl=0x9b234400: I/O error during system call, Connection timed out
08-29 09:54:11.982  1529  4227 V NativeCrypto: SSL shutdown failed: ssl=0x9b234400: I/O error during system call, Broken pipe
,08-29 09:54:11.990   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 09:54:11.990   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 09:54:11.996   396   396 E Parcel  : Reading a NULL string not supported here.
08-29 09:54:11.997   873  4202 D DhcpClient: Receive thread stopped
,08-29 09:54:12.017   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 09:54:12.019   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:12.019   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:54:12.020   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:54:12.033   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 09:54:12.038   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 09:54:12.042  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:12.042  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:12.042  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:12.042  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:12.044  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:12.044  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:12.044  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:12.044  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:12.046  2177  2359 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:12.061   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:12.084   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:12.085   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 09:54:12.085   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:12.089   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:12.090  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:12.091  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:12.095  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 09:54:12.098  1756  1756 D SystemUpdateService: onCreate
08-29 09:54:12.100  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:54:12.107  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:54:12.110  1756  2424 I iu.UploadsManager: num queued entries: 0
08-29 09:54:12.110  1756  2424 I iu.UploadsManager: num updated entries: 0
,08-29 09:54:12.117  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:54:12.119  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 09:54:12.120  4101  4101 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:12.124  4101  4101 D SprintDMHelper: simOperator: 
,08-29 09:54:12.124  4101  4101 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:54:12.128  1756  4239 I SystemUpdateService: active receiver: enabled
,08-29 09:54:12.143  1756  2424 I iu.SyncManager: NEXT; no task
,08-29 09:54:12.149   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 09:54:12.150   873  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 09:54:12.152  3202  4244 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 09:54:12.156  1756  4239 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 09:54:12.161  1756  4239 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 09:54:12.161  1756  4239 I SystemUpdateService: now status is 0 (complete)
08-29 09:54:12.161  1756  4239 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 09:54:12.162  1756  4239 I SystemUpdateService: file has been verified
08-29 09:54:12.162  1756  4239 I SystemUpdateService: OTA package size = 12249756
,08-29 09:54:12.167  1756  4239 I SystemUpdateService: showing system update notification
,08-29 09:54:12.187  1756  1756 D SystemUpdateService: onDestroy
,08-29 09:54:12.295  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:12.335  1529  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 09:54:12.335  1529  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 09:54:12.335  1529  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 09:54:12.335  1529  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:12.357  3654  3654 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 09:54:12.358  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 09:54:12.359  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 09:54:14.953   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4622c30:true
08-29 09:54:14.954  4087  4087 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:54:14.959  4087  4087 I bt_bluedroid: init
,08-29 09:54:14.959  4087  4247 I BluetoothAdapterState: Entering OffState
,08-29 09:54:14.967  4087  4248 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 09:54:14.967  4087  4248 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 09:54:14.968  4087  4248 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 09:54:14.968  4087  4248 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 09:54:14.971  4087  4087 I bt_bluedroid: get_profile_interface socket
,08-29 09:54:14.974  4087  4087 I bt_bluedroid: get_profile_interface sdp
08-29 09:54:14.976  4087  4251 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 09:54:14.979  4087  4097 I bt_bluedroid: config_hci_snoop_log
,08-29 09:54:14.980  4087  4251 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 09:54:14.982   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 09:54:14.988  4087  4247 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 09:54:14.989  4087  4247 D BluetoothAdapterProperties: Setting state to 14
08-29 09:54:14.989  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:54:14.992  4087  4247 D BluetoothBondStateMachine: make
,08-29 09:54:14.995  4087  4252 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:54:14.999  4087  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:54:15.000  4087  4087 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:54:15.002  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:15.003  4087  4087 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:54:15.004  4087  4087 D BtGatt.GattService: Received start request. Starting profile...
,08-29 09:54:15.004  4087  4087 D BtGatt.GattService: start()
08-29 09:54:15.004  4087  4087 I bt_bluedroid: get_profile_interface gatt
,08-29 09:54:15.005  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:15.005  4087  4087 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:54:15.012  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:54:15.012  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:15.012  4087  4087 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 09:54:15.012  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:15.012  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 09:54:15.013  4087  4247 I bt_bluedroid: enable
,08-29 09:54:15.013  4087  4248 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 09:54:15.013  4087  4248 I bt_hci  : start_up
,08-29 09:54:15.020  4087  4248 I bt_vendor: alloc value 0xb3939189
,08-29 09:54:15.020  4087  4248 I bt_vendor: init
,08-29 09:54:15.020  4087  4248 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 09:54:15.020  4087  4248 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:54:15.125  4087  4248 D bt_hci  : start_up starting async portion
,08-29 09:54:15.127  4087  4255 I bt_hci  : event_finish_startup
,08-29 09:54:15.127  4087  4255 I bt_hci_h4: hal_open,
,08-29 09:54:15.128  4087  4255 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 09:54:15.146  4087  4255 I bt_userial_vendor: device fd = 51 open
,08-29 09:54:15.168  4087  4255 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:54:15.200  4087  4255 D bt_hwcfg: Chipset BCM4354A2
,08-29 09:54:15.200  4087  4255 D bt_hwcfg: Target name = [BCM4354A2]
08-29 09:54:15.201  4087  4255 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 09:54:15.886  4087  4255 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:54:15.888  4087  4255 D bt_hwcfg: Settlement delay -- 100 ms
08-29 09:54:15.888  4087  4255 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:54:16.005  4087  4255 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:54:16.006  4087  4255 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 09:54:16.035  4087  4255 I bt_hwcfg: vendor lib fwcfg completed
,08-29 09:54:16.036  4087  4255 I bt_vendor: firmware callback
,08-29 09:54:16.036  4087  4255 I bt_hci  : firmware_config_callback
,08-29 09:54:16.047  4087  4257 I bt_btu  : btu_task pending for preload complete event
,08-29 09:54:16.047  4087  4257 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:54:16.048  4087  4257 I bt_btu  : btu_task received preload complete event
,08-29 09:54:16.059  4087  4257 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:54:16.060  4087  4257 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 09:54:16.060  4087  4257 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 09:54:16.060  4087  4257 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:54:16.061  4087  4257 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 09:54:16.061  4087  4257 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 09:54:16.062  4087  4257 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 09:54:16.063  4087  4257 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:54:16.063  4087  4257 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 09:54:16.064  4087  4257 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 09:54:16.064  4087  4257 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:54:16.065  4087  4257 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:54:16.065  4087  4257 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:54:16.065  4087  4257 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 09:54:16.066  4087  4257 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:54:16.200  4087  4257 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-29 09:54:16.200  4087  4257 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-29 09:54:16.213  4087  4251 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:54:16.215  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:54:16.216  4087  4251 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 09:54:16.220  4087  4251 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 09:54:16.223  4087  4251 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:16.223  4087  4251 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 09:54:16.224  4087  4251 D bt_hci  : do_postload posting postload work item
,08-29 09:54:16.224  4087  4255 I bt_hci  : event_postload
,08-29 09:54:16.224  4087  4255 I bt_vendor: sco_config_cb
,08-29 09:54:16.224  4087  4255 I bt_hci  : sco_config_callback postload finished.
08-29 09:54:16.228  4087  4251 D bt_bte_conf: Device ID record 1 : primary
08-29 09:54:16.228  4087  4251 D bt_bte_conf:   vendorId            = 000f
08-29 09:54:16.228  4087  4251 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 09:54:16.228  4087  4251 D bt_bte_conf:   product             = 1200
08-29 09:54:16.228  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.229  4087  4251 D bt_bte_conf:   version             = 1436
,08-29 09:54:16.229  4087  4251 D bt_bte_conf:   clientExecutableURL = 
08-29 09:54:16.229  4087  4251 D bt_bte_conf:   serviceDescription  = 
08-29 09:54:16.229  4087  4251 D bt_bte_conf:   documentationURL    = 
08-29 09:54:16.230  4087  4251 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 09:54:16.230  4087  4248 D bt_stack_manager: event_start_up_stack finished
08-29 09:54:16.232  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.233  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:54:16.233  4087  4247 D BluetoothAdapterProperties: Setting state to 15
,08-29 09:54:16.233  4087  4255 I bt_vendor: low_power_mode_cb
,08-29 09:54:16.234  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 09:54:16.235  4087  4247 I BluetoothAdapterState: Entering BleOnState
,08-29 09:54:16.240  4087  4247 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 09:54:16.240  4087  4247 D BluetoothAdapterProperties: Setting state to 11
08-29 09:54:16.240  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 09:54:16.250  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
08-29 09:54:16.253  4087  4087 D HeadsetService: Received start request. Starting profile...
08-29 09:54:16.254  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:16.257  4087  4087 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:16.257  4087  4087 D HeadsetStateMachine: make
,08-29 09:54:16.261  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:16.266  4087  4087 D HeadsetStateMachine: max_hf_connections = 1
,08-29 09:54:16.266  4087  4087 I bt_bluedroid: get_profile_interface handsfree
08-29 09:54:16.266  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 09:54:16.266  4087  4251 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-29 09:54:16.267  4087  4247 I BluetoothAdapterState: Entering PendingCommandState,
,08-29 09:54:16.272  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:16.272  4087  4087 D A2dpService: Received start request. Starting profile...
,08-29 09:54:16.273  4087  4087 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:54:16.273  4087  4087 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:54:16.279  4087  4087 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:54:16.279  4087  4087 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:16.279  4087  4087 D A2dpStateMachine: make
,08-29 09:54:16.280  4087  4087 I bt_bluedroid: get_profile_interface a2dp
08-29 09:54:16.280  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 09:54:16.283  4087  4266 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:54:16.283  4087  4087 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 09:54:16.285  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:16.286  4087  4087 D HidService: Received start request. Starting profile...
08-29 09:54:16.286  4005  4005 D BluetoothInputDevice: Proxy object connected
08-29 09:54:16.286  4087  4087 I bt_bluedroid: get_profile_interface hidhost
08-29 09:54:16.287  4087  4251 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-29 09:54:16.287  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:54:16.287  4087  4087 D HidService: setHidService(): set to: null
08-29 09:54:16.287  4087  4087 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 09:54:16.288  4005  4005 D HidProfile: Bluetooth service connected
08-29 09:54:16.288  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
08-29 09:54:16.289  4087  4087 D HealthService: Received start request. Starting profile...
,08-29 09:54:16.290  4087  4087 I bt_bluedroid: get_profile_interface health
,08-29 09:54:16.291  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
08-29 09:54:16.292  4087  4087 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 09:54:16.292  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:16.294  4087  4087 D PanService: Received start request. Starting profile...
08-29 09:54:16.295  4087  4087 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:54:16.295  4087  4087 I bt_bluedroid: get_profile_interface pan
08-29 09:54:16.295  4087  4251 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 09:54:16.296  4005  4005 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 09:54:16.296  4005  4005 D PanProfile: Bluetooth service connected
,08-29 09:54:16.301  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:16.303  4087  4087 D BluetoothMapService: Received start request. Starting profile...
08-29 09:54:16.303  4087  4087 D BluetoothMapService: start()
08-29 09:54:16.303  4005  4005 D BluetoothMap: Proxy object connected
08-29 09:54:16.304  4005  4005 D MapProfile: Bluetooth service connected
08-29 09:54:16.304  4005  4005 D BluetoothMap: getConnectedDevices()
08-29 09:54:16.305  4005  4005 D BluetoothMap: Bluetooth is Not enabled
08-29 09:54:16.305  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 09:54:16.306  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 09:54:16.306  4087  4087 D BluetoothMapAppObserver: createReceiver()
,08-29 09:54:16.307  4087  4087 D BluetoothMapAppObserver: initObservers()
08-29 09:54:16.307  4087  4087 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 09:54:16.311  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:54:16.311  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:16.311  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:16.311  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:16.313  4087  4264 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:16.313  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:16.314  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:16.314  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:54:16.314  4087  4247 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:54:16.314  4087  4247 D BluetoothAdapterProperties: State =  11
,08-29 09:54:16.315  4087  4247 D BluetoothAdapterProperties: Setting state to 12
08-29 09:54:16.315  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:54:16.315   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:16.315  4087  4247 I BluetoothAdapterState: Entering OnState
08-29 09:54:16.315  4005  4017 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:54:16.316  1920  2286 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.316   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.316  1373  1398 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:54:16.317  4087  4251 D BluetoothAdapterProperties: Scan Mode:21
,08-29 09:54:16.317  4087  4251 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:16.318  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:16.319  1373  1373 D PanProfile: Bluetooth service connected
08-29 09:54:16.319  1373  4018 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:16.320  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:16.321  1373  1373 D BluetoothInputDevice: Proxy object connected
08-29 09:54:16.321  1373  1373 D HidProfile: Bluetooth service connected
,08-29 09:54:16.321  1373  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:16.322  4005  4021 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:16.322  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:16.322   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:16.324  1373  1979 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 09:54:16.325   873   873 D BluetoothA2dp: Proxy object connected
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:16.325  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:16.326  1373  1373 D BluetoothMap: Proxy object connected
,08-29 09:54:16.326  1373  1373 D MapProfile: Bluetooth service connected
08-29 09:54:16.326  1373  1373 D BluetoothMap: getConnectedDevices()
08-29 09:54:16.326  4005  4017 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:54:16.327  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:16.328  1373  1398 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 09:54:16.330  4005  4021 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 09:54:16.330   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.330  1373  4018 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:16.331  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 09:54:16.332  4087  4087 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 09:54:16.332  1373  1373 D BluetoothA2dp: Proxy object connected
,08-29 09:54:16.334  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:16.334   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 09:54:16.337  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:16.337  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.338  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.339  4087  4087 D ObexServerSockets: Succeed to create listening sockets 
08-29 09:54:16.339  4087  4087 D ObexServerSockets0: startAccept()
08-29 09:54:16.339  4087  4087 D ObexServerSockets0: prepareForNewConnect()
08-29 09:54:16.340  4087  4087 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 09:54:16.341  4087  4087 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:54:16.341  4005  4005 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 09:54:16.341  4087  4087 D BluetoothMapService: onReceive
08-29 09:54:16.341  4087  4087 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.341  4087  4087 D BluetoothMapService: STATE_ON
,08-29 09:54:16.343  4087  4273 D ObexServerSockets0: Accepting socket connection...
,08-29 09:54:16.343  4087  4272 D ObexServerSockets0: Accepting socket connection...
,08-29 09:54:16.347  4005  4005 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 09:54:16.352  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:16.354  4005  4005 D BluetoothA2dp: Proxy object connected
,08-29 09:54:16.356  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:16.362  1373  1373 D BluetoothPbap: Proxy object connected
,08-29 09:54:16.362  1373  1373 D PbapServerProfile: Bluetooth service connected
08-29 09:54:16.363  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:54:16.363  4087  4087 D ObexServerSockets0: prepareForNewConnect()
08-29 09:54:16.363  4005  4005 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:16.365  4005  4005 D BluetoothPbap: Proxy object connected
08-29 09:54:16.365  4005  4005 D PbapServerProfile: Bluetooth service connected
,08-29 09:54:16.369  4087  4277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:16.386  4087  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:16.387  4087  4281 I BtOppRfcommListener: Accept thread started.
,08-29 09:54:16.417   873   873 D BluetoothHeadset: Proxy object connected
,08-29 09:54:16.417   873   873 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.417  1373  1398 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.417  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:16.417  1920  1935 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.417   873   873 D BluetoothHeadset: Proxy object connected
,08-29 09:54:16.421  1373  4018 D BluetoothHeadset: Proxy object connected
,08-29 09:54:16.421  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:16.430   873   890 D BluetoothHeadset: Proxy object connected
,08-29 09:54:16.450  4005  4017 D BluetoothHeadset: Proxy object connected
,08-29 09:54:16.454  4005  4005 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:17.905   873  1317 D ConnectivityService: handlePromptUnvalidated 101
,08-29 09:54:17.917  4087  4247 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 09:54:17.918  4087  4247 D BluetoothAdapterProperties: Setting state to 13
,08-29 09:54:17.918  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 09:54:17.920  4087  4247 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:54:17.925  4087  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:54:17.929  4087  4251 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:17.930  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 09:54:17.933  4087  4087 D BluetoothMapService: onReceive
,08-29 09:54:17.933  4087  4087 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:17.934  4087  4087 D BluetoothMapService: STATE_TURNING_OFF,
08-29 09:54:17.934  4087  4087 D BluetoothMapService: MAP Service closeService in
,08-29 09:54:17.934  4087  4087 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 09:54:17.935  4087  4087 D ObexServerSockets0: shutdown(block = true)
08-29 09:54:17.936  4087  4272 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 09:54:17.938  4087  4087 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:54:17.939  4087  4087 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:54:17.939  4087  4260 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 09:54:17.940  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:17.940  4087  4273 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:17.940  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:17.942  4087  4087 I BtOppRfcommListener: stopping Accept Thread
08-29 09:54:17.942  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:17.942  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:17.943  4087  4281 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:54:17.943  4087  4281 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:54:17.946  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:17.947  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:17.948  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:17.948  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:17.948  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:17.951  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:17.954  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:17.956  4087  4087 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:54:17.960   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:17.960   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:17.961  1373  4016 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:17.962  4005  4017 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:17.962  4087  4087 D A2dpService: Received stop request...Stopping profile...
,08-29 09:54:17.962  1920  2071 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:17.963  4087  4266 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:54:17.963   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 09:54:17.964   873   873 D BluetoothA2dp: Proxy object disconnected
,08-29 09:54:17.965  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-29 09:54:17.965  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:17.966  4087  4087 D HidService: Received stop request...Stopping profile...
08-29 09:54:17.967  4005  4005 D DockEventReceiver: finishStartingService: stopping service
08-29 09:54:17.967  4087  4087 D HidService: Stopping Bluetooth HidService
08-29 09:54:17.968  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-29 09:54:17.968  1373  1373 D HidProfile: Bluetooth service disconnected
08-29 09:54:17.968  4005  4005 D HeadsetProfile: Bluetooth service disconnected
,08-29 09:54:17.968  4005  4005 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:17.969  4005  4005 D BluetoothInputDevice: Proxy object disconnected
08-29 09:54:17.969  4005  4005 D HidProfile: Bluetooth service disconnected
08-29 09:54:17.971  4087  4087 D HealthService: Received stop request...Stopping profile...
,08-29 09:54:17.975  4087  4087 D PanService: Received stop request...Stopping profile...
,08-29 09:54:17.976  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 09:54:17.976  1373  1373 D PanProfile: Bluetooth service disconnected
08-29 09:54:17.976  4005  4005 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:54:17.976  4005  4005 D PanProfile: Bluetooth service disconnected
08-29 09:54:17.976  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:17.976  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:17.976  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:17.976  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:17.978  4087  4087 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:54:17.978  4087  4087 D BluetoothMapService: stop()
,08-29 09:54:17.979  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:17.979  4087  4087 D BluetoothMapAppObserver: deinitObservers()
08-29 09:54:17.980  4087  4087 D BluetoothMapAppObserver: removeReceiver()
,08-29 09:54:17.982  4005  4005 D BluetoothMap: Proxy object disconnected
08-29 09:54:17.982  4005  4005 D MapProfile: Bluetooth service disconnected
,08-29 09:54:17.983  1373  1373 D BluetoothMap: Proxy object disconnected
08-29 09:54:17.983  1373  1373 D MapProfile: Bluetooth service disconnected
08-29 09:54:17.983  4087  4087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 09:54:17.983  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:54:17.983  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:17.983  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:17.983  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 09:54:17.984  4087  4251 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-29 09:54:17.983  4087  4087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:54:17.985  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:54:17.985  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:17.985  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:17.985  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:17.986  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 09:54:17.986  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:17.986  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:54:17.987  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:17.987  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:17.987  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:17.987  4087  4257 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 09:54:17.987  4087  4257 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:17.987  4087  4257 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 09:54:17.987  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:17.987  4087  4257 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:17.987  4087  4087 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:54:17.987  4087  4087 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 09:54:17.988  4087  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:54:17.988  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:54:17.988  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:17.988  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:54:17.988  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:17.988  4087  4087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:54:17.988  4087  4251 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 09:54:17.989  4087  4087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 09:54:17.989  4087  4087 V BluetoothAdapterState: isTurningOff()=true
08-29 09:54:17.989  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:17.989  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:17.989  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:17.989  4087  4087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 09:54:17.989  4087  4087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 09:54:17.994  1373  1373 D BluetoothPbap: Proxy object disconnected
,08-29 09:54:17.994  4005  4005 D BluetoothPbap: Proxy object disconnected
08-29 09:54:17.996  4087  4087 D BluetoothMapService: MAP Service closeService in
08-29 09:54:17.996  4087  4087 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:54:17.996  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-29 09:54:17.996  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:17.996  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:17.996  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:54:17.997  4087  4247 D BluetoothAdapterProperties: Setting state to 15
,08-29 09:54:17.997  4087  4087 D BluetoothMapService: cleanup()
08-29 09:54:17.997  4087  4087 D BluetoothMapService: MAP Service closeService in
,08-29 09:54:17.997  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 09:54:17.994  1373  1373 D PbapServerProfile: Bluetooth service disconnected
,08-29 09:54:17.998  4087  4247 I BluetoothAdapterState: Entering BleOnState
,08-29 09:54:17.999   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.000  4005  4021 D BluetoothPan: onBluetoothStateChange on: false
,08-29 09:54:18.000  1920  1942 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.000   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.001  4005  4017 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.001  1373  4019 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:54:18.001  1373  4016 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 09:54:18.002  1373  1398 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.002  4005  4021 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 09:54:17.994  4005  4005 D PbapServerProfile: Bluetooth service disconnected
08-29 09:54:18.002  4005  4017 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:18.003   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:18.003  1373  4018 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 09:54:18.003  4005  4021 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 09:54:18.004  1373  1979 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:54:18.004  4005  4017 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 09:54:18.005   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:18.005  1373  1389 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:18.005  4087  4247 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 09:54:18.005  4087  4247 D BluetoothAdapterProperties: Setting state to 16
,08-29 09:54:18.006  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:54:18.006  4087  4247 D BluetoothAdapterProperties: onBleDisable
08-29 09:54:18.006  4087  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:54:18.006  4087  4248 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 09:54:18.007  4087  4251 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:18.009  4087  4257 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 09:54:18.009  4087  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:54:18.010  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:18.010  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:18.013  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:18.014  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:18.015  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:54:18.016  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:18.022  4005  4005 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:18.209  4087  4251 I bt_hci  : shut_down
,08-29 09:54:18.210  4087  4255 D bt_hwcfg: hw_epilog_process
,08-29 09:54:18.223  4087  4255 I bt_vendor: low_power_mode_cb
,08-29 09:54:18.254  4087  4255 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:54:18.254  4087  4255 I bt_vendor: epilog_cb
08-29 09:54:18.254  4087  4255 I bt_hci  : epilog_finished_callback
,08-29 09:54:18.263  4087  4251 I bt_hci_h4: hal_close
,08-29 09:54:18.265  4087  4251 I bt_userial_vendor: device fd = 51 close
,08-29 09:54:18.382  4087  4248 D bt_stack_manager: event_shut_down_stack finished.
,08-29 09:54:18.384  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 09:54:18.391  4087  4247 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 09:54:18.391  4087  4087 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:54:18.393  4087  4087 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:54:18.393  4087  4087 D BtGatt.GattService: stop()
08-29 09:54:18.393  4087  4087 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 09:54:18.398  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:18.398  4087  4087 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:18.398  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:18.399  4087  4087 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:54:18.400  4087  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 09:54:18.400  4087  4247 D BluetoothAdapterProperties: Setting state to 10
08-29 09:54:18.401  4087  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 09:54:18.403  4087  4247 I BluetoothAdapterState: Entering OffState
,08-29 09:54:18.404   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 09:54:18.426  4087  4087 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 09:54:18.427  4087  4087 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:54:18.427  4087  4248 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 09:54:18.438  4087  4087 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 09:54:18.443  4087  4248 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:54:18.447  4087  4087 I art     : System.exit called, status: 0
,08-29 09:54:18.448  4087  4087 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:54:18.525   873  2200 I ActivityManager: Process com.android.bluetooth (pid 4087) has died
,08-29 09:54:20.914  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:20.915  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:22.702   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 09:54:22.711  1860  1860 I Keyboard.Facilitator: onFinishInput()
,08-29 09:54:22.716   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 09:54:22.716   873   893 I Adreno  : Build Date                       : 10/20/15
08-29 09:54:22.716   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 09:54:22.716   873   893 I Adreno  : Local Branch                     : M14
08-29 09:54:22.716   873   893 I Adreno  : Remote Branch                    : 
08-29 09:54:22.716   873   893 I Adreno  : Remote Branch                    : 
08-29 09:54:22.716   873   893 I Adreno  : Reconstruct Branch               : 
,08-29 09:54:22.756   281  1731 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (260 us)
,08-29 09:54:23.428  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 09:54:23.428  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 09:54:23.462   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 09:54:23.464  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c9a0ed7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7e9e69, 16908290=android.view.AbsSavedState$1@7e9e69}, android:focusedViewId=100}]}]
08-29 09:54:23.464  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 09:54:23.464  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:54:23.465  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 09:54:23.470   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 09:54:23.474   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 09:54:23.474   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-29 09:54:23.474   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 09:54:23.711   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 09:54:23.716   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
,08-29 09:54:23.717   873  1341 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
08-29 09:54:23.721   873   893 I DreamManagerService: Entering dreamland.
,08-29 09:54:23.723   873   893 I PowerManagerService: Dozing...
08-29 09:54:23.724   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 09:54:23.792   377  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 09:54:23.793   377  1323 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 09:54:23.800   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 09:54:23.811   873  1315 E native  : do suspend false
,08-29 09:54:23.820  1909  4292 D NfcService: Discovery configuration equal, not updating.
,08-29 09:54:23.853   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 09:54:23.856   873  1315 E native  : do suspend true
,08-29 09:54:23.922  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:23.922  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@863a0ee added. We now have 6 listener(s)
,08-29 09:54:23.923  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:23.926  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:23.926  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@388398f added. We now have 7 listener(s)
,08-29 09:54:23.928   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 09:54:23.928  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:23.928   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 09:54:23.929  3935  3986 I System.out: IsBluetoothEnabled
,08-29 09:54:23.940  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:23.964   873   890 I ActivityManager: Start proc 4296:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 09:54:24.069  4296  4296 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:54:24.070  4296  4296 D AdapterServiceConfig: Adding A2dpService
,08-29 09:54:24.070  4296  4296 D AdapterServiceConfig: Adding HidService
08-29 09:54:24.070  4296  4296 D AdapterServiceConfig: Adding HealthService
08-29 09:54:24.071  4296  4296 D AdapterServiceConfig: Adding PanService
,08-29 09:54:24.071  4296  4296 D AdapterServiceConfig: Adding GattService
08-29 09:54:24.071  4296  4296 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 09:54:24.087   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3f8608:true
,08-29 09:54:24.087  4296  4296 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:54:24.092  4296  4296 I bt_bluedroid: init
,08-29 09:54:24.094  4296  4310 I BluetoothAdapterState: Entering OffState
,08-29 09:54:24.103  4296  4311 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 09:54:24.103  4296  4311 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 09:54:24.103  4296  4311 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 09:54:24.104  4296  4311 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 09:54:24.107  4296  4296 I bt_bluedroid: get_profile_interface socket
,08-29 09:54:24.112  4296  4314 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 09:54:24.114  4296  4314 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 09:54:24.113  4296  4296 I bt_bluedroid: get_profile_interface sdp
,08-29 09:54:24.122  4296  4309 I bt_bluedroid: config_hci_snoop_log
,08-29 09:54:24.127   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 09:54:24.137  4296  4310 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 09:54:24.137  4296  4310 D BluetoothAdapterProperties: Setting state to 14
,08-29 09:54:24.138  4296  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:54:24.142  4296  4310 D BluetoothBondStateMachine: make
,08-29 09:54:24.146  4296  4315 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:54:24.153  4296  4310 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:54:24.156  4296  4296 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:54:24.164  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:24.166  4296  4296 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:54:24.167  4296  4296 D BtGatt.GattService: Received start request. Starting profile...
,08-29 09:54:24.167  4296  4296 D BtGatt.GattService: start()
,08-29 09:54:24.167  4296  4296 I bt_bluedroid: get_profile_interface gatt
,08-29 09:54:24.168  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:24.168  4296  4296 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:54:24.182  4296  4296 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:24.182  4296  4296 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:54:24.182  4296  4296 V BluetoothAdapterState: isBleTurningOn()=true
08-29 09:54:24.182  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:24.183  4296  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 09:54:24.184  4296  4310 I bt_bluedroid: enable
08-29 09:54:24.184  4296  4311 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 09:54:24.185  4296  4311 I bt_hci  : start_up
,08-29 09:54:24.200  4296  4311 I bt_vendor: alloc value 0xb39a7189
,08-29 09:54:24.200  4296  4311 I bt_vendor: init
08-29 09:54:24.200  4296  4311 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 09:54:24.200  4296  4311 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:54:24.308  4296  4311 D bt_hci  : start_up starting async portion
,08-29 09:54:24.308  4296  4318 I bt_hci  : event_finish_startup
08-29 09:54:24.309  4296  4318 I bt_hci_h4: hal_open
08-29 09:54:24.309  4296  4318 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 09:54:24.317  4296  4318 I bt_userial_vendor: device fd = 51 open
,08-29 09:54:24.349  4296  4318 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:54:24.381  4296  4318 D bt_hwcfg: Chipset BCM4354A2
,08-29 09:54:24.381  4296  4318 D bt_hwcfg: Target name = [BCM4354A2]
08-29 09:54:24.382  4296  4318 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 09:54:25.047  4296  4318 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:54:25.048  4296  4318 D bt_hwcfg: Settlement delay -- 100 ms
08-29 09:54:25.049  4296  4318 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:54:25.165  4296  4318 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:54:25.166  4296  4318 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 09:54:25.196  4296  4318 I bt_hwcfg: vendor lib fwcfg completed
,08-29 09:54:25.196  4296  4318 I bt_vendor: firmware callback
,08-29 09:54:25.197  4296  4318 I bt_hci  : firmware_config_callback
,08-29 09:54:25.208  4296  4320 I bt_btu  : btu_task pending for preload complete event
,08-29 09:54:25.208  4296  4320 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:54:25.208  4296  4320 I bt_btu  : btu_task received preload complete event
,08-29 09:54:25.218  4296  4320 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 09:54:25.219  4296  4320 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 09:54:25.219  4296  4320 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:54:25.219  4296  4320 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:54:25.219  4296  4320 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:54:25.219  4296  4320 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 09:54:25.220  4296  4320 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 09:54:25.220  4296  4320 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:54:25.220  4296  4320 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:54:25.220  4296  4320 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 09:54:25.220  4296  4320 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:54:25.221  4296  4320 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:54:25.221  4296  4320 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:54:25.221  4296  4320 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 09:54:25.221  4296  4320 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:54:25.352  4296  4320 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3924d9d
,08-29 09:54:25.353  4296  4320 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3924d9d 
,08-29 09:54:25.364  4296  4314 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:54:25.368  4296  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:54:25.369  4296  4314 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 09:54:25.373  4296  4314 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 09:54:25.376  4296  4314 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:25.376  4296  4314 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 09:54:25.377  4296  4314 D bt_hci  : do_postload posting postload work item
,08-29 09:54:25.377  4296  4318 I bt_hci  : event_postload
,08-29 09:54:25.377  4296  4318 I bt_vendor: sco_config_cb
,08-29 09:54:25.377  4296  4318 I bt_hci  : sco_config_callback postload finished.
,08-29 09:54:25.379  4296  4314 D bt_bte_conf: Device ID record 1 : primary
,08-29 09:54:25.379  4296  4314 D bt_bte_conf:   vendorId            = 000f
08-29 09:54:25.380  4296  4314 D bt_bte_conf:   vendorIdSource      = 0001
08-29 09:54:25.380  4296  4314 D bt_bte_conf:   product             = 1200
08-29 09:54:25.380  4296  4314 D bt_bte_conf:   version             = 1436
08-29 09:54:25.380  4296  4314 D bt_bte_conf:   clientExecutableURL = 
,08-29 09:54:25.380  4296  4314 D bt_bte_conf:   serviceDescription  = 
08-29 09:54:25.381  4296  4314 D bt_bte_conf:   documentationURL    = 
08-29 09:54:25.381  4296  4314 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 09:54:25.381  4296  4311 D bt_stack_manager: event_start_up_stack finished
,08-29 09:54:25.381  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:25.383  4296  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:54:25.383  4296  4318 I bt_vendor: low_power_mode_cb
08-29 09:54:25.384  4296  4310 D BluetoothAdapterProperties: Setting state to 15
08-29 09:54:25.384  4296  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 09:54:25.387  4296  4310 I BluetoothAdapterState: Entering BleOnState
08-29 09:54:25.389  4296  4310 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 09:54:25.390  4296  4310 D BluetoothAdapterProperties: Setting state to 11
08-29 09:54:25.390  4296  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 09:54:25.398  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.399  4296  4296 D HeadsetService: Received start request. Starting profile...
,08-29 09:54:25.402  4296  4296 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:25.402  4296  4296 D HeadsetStateMachine: make
08-29 09:54:25.407  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:25.417  4296  4310 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:54:25.419  4296  4296 D HeadsetStateMachine: max_hf_connections = 1
,08-29 09:54:25.420  4296  4296 I bt_bluedroid: get_profile_interface handsfree
,08-29 09:54:25.420  4296  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 09:54:25.420  4296  4314 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 09:54:25.429  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.430  4296  4296 D A2dpService: Received start request. Starting profile...
,08-29 09:54:25.432  4296  4296 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 09:54:25.433  4296  4296 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:54:25.447  4296  4296 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:54:25.447  4296  4296 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:25.448  4296  4296 D A2dpStateMachine: make
,08-29 09:54:25.450  4296  4296 I bt_bluedroid: get_profile_interface a2dp
,08-29 09:54:25.451  4296  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 09:54:25.452  4296  4330 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:54:25.453  4296  4296 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 09:54:25.454  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.455  4296  4296 D HidService: Received start request. Starting profile...
,08-29 09:54:25.455  4296  4296 I bt_bluedroid: get_profile_interface hidhost
,08-29 09:54:25.455  4296  4314 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39063e5
08-29 09:54:25.456  4296  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:54:25.456  4296  4296 D HidService: setHidService(): set to: null
,08-29 09:54:25.457  4296  4296 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 09:54:25.458  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.460  4296  4296 D HealthService: Received start request. Starting profile...
,08-29 09:54:25.462  4296  4296 I bt_bluedroid: get_profile_interface health
08-29 09:54:25.463  4296  4296 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
08-29 09:54:25.464  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.464  4296  4296 D PanService: Received start request. Starting profile...
,08-29 09:54:25.465  4296  4296 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 09:54:25.465  4296  4296 I bt_bluedroid: get_profile_interface pan
08-29 09:54:25.466  4296  4314 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:54:25.480  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:25.483  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:25.484  4296  4296 D BluetoothMapService: Received start request. Starting profile...
08-29 09:54:25.484  4296  4296 D BluetoothMapService: start()
,08-29 09:54:25.487  4296  4296 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 09:54:25.487  4296  4296 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 09:54:25.488  4296  4296 D BluetoothMapAppObserver: createReceiver()
,08-29 09:54:25.488  4296  4296 D BluetoothMapAppObserver: initObservers()
,08-29 09:54:25.489  4296  4296 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 09:54:25.495  4296  4296 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:54:25.495  4296  4296 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:25.495  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.495  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:25.496  4296  4328 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 09:54:25.496  4296  4296 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.497  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:54:25.498  4296  4296 V BluetoothAdapterState: isTurningOff()=false
08-29 09:54:25.498  4296  4296 V BluetoothAdapterState: isTurningOn()=true
08-29 09:54:25.498  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.498  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:25.498  4296  4296 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:54:25.499  4296  4296 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:54:25.499  4296  4296 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:54:25.499  4296  4296 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:54:25.499  4296  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:54:25.499  4296  4310 D BluetoothAdapterProperties: ScanMode =  20
,08-29 09:54:25.500  4296  4310 D BluetoothAdapterProperties: State =  11
,08-29 09:54:25.505  4296  4314 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:54:25.505  4296  4310 D BluetoothAdapterProperties: Setting state to 12
,08-29 09:54:25.505  4296  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:54:25.505  4296  4314 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:25.506   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:25.506  4296  4310 I BluetoothAdapterState: Entering OnState
,08-29 09:54:25.506  4005  4017 D BluetoothPan: onBluetoothStateChange on: true
,08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:25.510  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:25.512  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:25.514  1920  2071 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:25.515  4296  4296 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:54:25.515   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:25.515  4296  4296 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 09:54:25.516  4005  4021 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:25.517  4296  4296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:25.517  1373  1398 D BluetoothPan: onBluetoothStateChange on: true
,08-29 09:54:25.519  4296  4296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:25.520  1373  4018 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:25.520  4296  4296 D ObexServerSockets: Succeed to create listening sockets 
08-29 09:54:25.521  4296  4296 D ObexServerSockets0: startAccept()
,08-29 09:54:25.521  4296  4296 D ObexServerSockets0: prepareForNewConnect()
,08-29 09:54:25.523  1373  1389 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:25.523  4296  4296 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 09:54:25.523  4296  4296 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:54:25.524  4005  4017 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:25.524  4296  4336 D ObexServerSockets0: Accepting socket connection...
08-29 09:54:25.525  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:25.525  1373  1373 D PanProfile: Bluetooth service connected
08-29 09:54:25.525  1373  1373 D BluetoothInputDevice: Proxy object connected
08-29 09:54:25.526  1373  1373 D HidProfile: Bluetooth service connected
,08-29 09:54:25.527  4005  4021 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:25.528  4296  4335 D ObexServerSockets0: Accepting socket connection...
,08-29 09:54:25.530   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:25.531  1373  4016 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:54:25.531   873   873 D BluetoothA2dp: Proxy object connected
,08-29 09:54:25.530  4005  4005 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 09:54:25.532  4005  4005 D PanProfile: Bluetooth service connected
,08-29 09:54:25.532  4005  4005 D BluetoothInputDevice: Proxy object connected
,08-29 09:54:25.532  4005  4005 D HidProfile: Bluetooth service connected
08-29 09:54:25.533  1373  1373 D BluetoothMap: Proxy object connected
,08-29 09:54:25.533  4005  4021 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:54:25.533  1373  1373 D MapProfile: Bluetooth service connected
,08-29 09:54:25.533  1373  1373 D BluetoothMap: getConnectedDevices()
,08-29 09:54:25.536  1373  1398 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:54:25.536  4005  4005 D BluetoothA2dp: Proxy object connected
,08-29 09:54:25.537  4005  4017 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:54:25.539   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:25.539  4005  4005 D BluetoothMap: Proxy object connected
08-29 09:54:25.539  4005  4005 D MapProfile: Bluetooth service connected
,08-29 09:54:25.540  4005  4005 D BluetoothMap: getConnectedDevices()
,08-29 09:54:25.540  1373  4018 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:25.542  1373  1373 D BluetoothA2dp: Proxy object connected
,08-29 09:54:25.545   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 09:54:25.546  4296  4296 D BluetoothMapService: onReceive
,08-29 09:54:25.546  4296  4296 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:25.546  4296  4296 D BluetoothMapService: STATE_ON
,08-29 09:54:25.549  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:25.555  4005  4005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:25.565  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:25.566  4005  4005 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:25.573  4005  4005 D BluetoothPbap: Proxy object connected
08-29 09:54:25.573  4005  4005 D PbapServerProfile: Bluetooth service connected
,08-29 09:54:25.574  4296  4296 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:54:25.575  4296  4296 D ObexServerSockets0: prepareForNewConnect()
,08-29 09:54:25.575  1373  1373 D BluetoothPbap: Proxy object connected
08-29 09:54:25.575  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-29 09:54:25.588  4296  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:25.613   873   873 D BluetoothHeadset: Proxy object connected
,08-29 09:54:25.613   873   873 D BluetoothHeadset: Proxy object connected
,08-29 09:54:25.613  4296  4348 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:25.613  1373  4014 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.613  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:25.614  4005  4337 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.614  1920  1942 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.614  4005  4005 D HeadsetProfile: Bluetooth service connected
08-29 09:54:25.614   873   873 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.615  1920  2286 D BluetoothHeadset: Proxy object connected
,08-29 09:54:25.616  4296  4348 I BtOppRfcommListener: Accept thread started.
08-29 09:54:25.616   873   890 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.616  4005  4017 D BluetoothHeadset: Proxy object connected
08-29 09:54:25.618  4005  4005 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:25.623  1373  1398 D BluetoothHeadset: Proxy object connected
,08-29 09:54:25.623  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:25.640   873   890 D BluetoothHeadset: Proxy object connected
,08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:25.964  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:25.971  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:25.974  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:25.975  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@624441c added. We now have 8 listener(s)
08-29 09:54:25.975  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:25.980   873  2198 D WifiService: setWifiEnabled: false pid=3935, uid=10000
08-29 09:54:25.980   873  2198 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:25.993  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:25.994   873  3269 D WifiService: setWifiEnabled: true pid=3935, uid=10000
,08-29 09:54:25.995   873  3269 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:26.008   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:26.022  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:26.030  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:26.039   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-29 09:54:26.040   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 09:54:26.041   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 09:54:26.042   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 09:54:26.042   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 09:54:26.042   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 09:54:26.042   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 09:54:26.059   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,08-29 09:54:26.060   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 09:54:26.060   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 09:54:26.064   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:26.071   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-29 09:54:26.071   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:54:26.076   873  1315 E native  : do suspend true
,08-29 09:54:26.087   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 09:54:26.088   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 09:54:26.094   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 09:54:26.094   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:26.102   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 09:54:26.171   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 09:54:26.173  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 09:54:26.594  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:54:26.629  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 09:54:26.629  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 09:54:26.631   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 09:54:26.636   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 09:54:26.637   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:26.637   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 09:54:26.652   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:26.663   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:26.663   873  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 09:54:26.670   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 09:54:26.711   873  4356 D DhcpClient: Receive thread started
,08-29 09:54:26.797   873  1315 E native  : do suspend false
,08-29 09:54:26.818   873  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 09:54:26.832   873  4356 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 09:54:26.833   873  1878 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 09:54:26.836   873  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 09:54:26.848   873  4356 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 09:54:26.849   873  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 09:54:26.854   373   871 D CommandListener: Setting iface cfg
,08-29 09:54:26.867   873  1878 D DhcpClient: Scheduling renewal in 86399s
,08-29 09:54:26.870   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 09:54:26.873   873  1315 E native  : do suspend true
,08-29 09:54:26.892   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 09:54:26.896   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 09:54:26.897   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 09:54:26.900   873  1317 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 09:54:26.909   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:54:26.987   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 09:54:26.988   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 09:54:26.992   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 09:54:26.996   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 09:54:27.000   873  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:27.012  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:27.012   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 09:54:27.016  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:27.017   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-29 09:54:27.017   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 09:54:27.017   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 09:54:27.017   873  1317 D ConnectivityService:    accepting network in place of null
08-29 09:54:27.017   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 09:54:27.018   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:54:27.019   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:54:27.027  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 09:54:27.029  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 09:54:27.033   873  4355 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154488, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:54:27.033  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c9a0ed7 Bundle[{}]
,08-29 09:54:27.036  3935  3986 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 09:54:27.036  3935  3986 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 09:54:27.037  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 09:54:27.038  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:54:27.039  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 09:54:27.040  3935  3986 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 09:54:27.047  3935  3986 I System.out: Running OutgoingSocketThread
,08-29 09:54:27.049   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:27.050  3935  4362 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 456)
,08-29 09:54:27.052  3935  4362 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48483
,08-29 09:54:27.052  3935  4362 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:54:27.096   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:54:27.105   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 09:54:27.106   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:27.113   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 09:54:27.115   873  4354 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:818::200e
,08-29 09:54:27.117   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:27.141  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:27.144  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:27.152  1756  1756 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 09:54:27.157  1756  1756 D SystemUpdateService: onCreate
,08-29 09:54:27.161  1756  1756 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:54:27.168  1756  4366 I SystemUpdateService: active receiver: enabled
,08-29 09:54:27.177  1756  4366 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 09:54:27.180  1756  4366 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 09:54:27.180  1756  4366 I SystemUpdateService: now status is 0 (complete)
,08-29 09:54:27.180  1756  4366 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 09:54:27.181  1756  4366 I SystemUpdateService: file has been verified
,08-29 09:54:27.184  1756  1756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 09:54:27.191  1756  2424 I iu.UploadsManager: num queued entries: 0
,08-29 09:54:27.181  1756  4366 I SystemUpdateService: OTA package size = 12249756
08-29 09:54:27.192  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:54:27.195  1756  1756 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 09:54:27.199  4101  4101 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:27.200  1756  4369 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 09:54:27.200  1756  4369 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:54:27.202  1756  4369 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
08-29 09:54:27.204  4101  4101 D SprintDMHelper: simOperator: 
08-29 09:54:27.204  4101  4101 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:54:27.213  1756  2424 I iu.UploadsManager: num updated entries: 0
,08-29 09:54:27.215  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:27.219  1756  4366 I SystemUpdateService: showing system update notification
,08-29 09:54:27.222   873  4354 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:54:27 GMT], X-Android-Received-Millis=[1472457267221], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472457267187]}
,08-29 09:54:27.222  1756  2424 I iu.SyncManager: NEXT; no task
08-29 09:54:27.223   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 09:54:27.223   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 09:54:27.223   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 09:54:27.223  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:54:27.232   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 09:54:27.258  1756  1756 D SystemUpdateService: onDestroy
,08-29 09:54:27.275  1529  2326 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 09:54:27.275  1529  2326 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 09:54:27.275  1529  2326 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 09:54:27.275  1529  2326 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 09:54:27.294  1756  4369 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-29 09:54:27.346  3202  4371 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 09:54:28.050  3935  3986 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 457)
,08-29 09:54:28.050  3935  3986 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 457)
,08-29 09:54:28.063  3935  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 462)
,08-29 09:54:28.066  3935  3986 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 09:54:28.066  3935  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 463)
,08-29 09:54:28.070  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.070  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9b825 added. We now have 2 listener(s)
,08-29 09:54:28.073  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 09:54:28.073  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.073  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:54:28.073  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:28.074  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cddfa added. We now have 9 listener(s)
,08-29 09:54:28.074  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.075  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:28.082  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:28.091  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:28.095  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:28.096  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:28.096  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.097  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3f8608 added. We now have 3 listener(s)
,08-29 09:54:28.101  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:28.103   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 09:54:28.103  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 09:54:28.103  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:54:28.104  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.104  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:28.105  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@112b1a1 added. We now have 10 listener(s)
,08-29 09:54:28.105  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.105  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:28.106  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:28.106  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:28.106  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.106  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.107  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:28.107  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.107  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9b825 removed from the list
08-29 09:54:28.107  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:28.107  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:28.108  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cddfa removed from the list
08-29 09:54:28.108  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:28.108  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.109  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.110  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.113  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:28.113  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.113  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.113  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cddfa not in the list
,08-29 09:54:28.113  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.114  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.115  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:28.116  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:54:28.116  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.116  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@112b1a1 removed from the list
,08-29 09:54:28.116  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.117  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.117  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.117  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.117  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3f8608 removed from the list
08-29 09:54:28.119  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.120  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9adfc6 added. We now have 2 listener(s)
,08-29 09:54:28.125  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 09:54:28.126  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.126  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:54:28.127  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:28.127  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d43cb87 added. We now have 9 listener(s)
,08-29 09:54:28.127  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.128  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:28.136  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:28.145  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:28.149  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:28.149  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:28.150  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:28.150  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@687c6dd added. We now have 3 listener(s)
,08-29 09:54:28.152  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:28.152  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:54:28.152  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.152  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:28.152  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2553252 added. We now have 10 listener(s)
08-29 09:54:28.152  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.153  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:54:28.153  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:28.153  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 09:54:28.153  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:28.153  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:28.156  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:28.157  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:54:28.157  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:54:28.162  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:28.167  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:54:28.169  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:54:28.169  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:28.176  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:54:28.176  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:54:28.177  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:54:28.178  3935  3986 D BluetoothAdapter: STATE_ON
,08-29 09:54:28.185  4296  4340 D BtGatt.GattService: registerClient() - UUID=984dcdfb-3894-4ac0-bd54-03b02ed645c8
,08-29 09:54:28.187  4296  4314 D BtGatt.GattService: onClientRegistered() - UUID=984dcdfb-3894-4ac0-bd54-03b02ed645c8, clientIf=5
,08-29 09:54:28.188  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 09:54:28.191  4296  4327 D BtGatt.GattService: start scan with filters
,08-29 09:54:28.199  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:54:28.199  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:54:28.199  4296  4317 D BtGatt.ScanManager: handling starting scan
08-29 09:54:28.199  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 09:54:28.200  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:54:28.203  4296  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83a8dfb
,08-29 09:54:28.208  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:28.209  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:28.208  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-29 09:54:28.212  4296  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 09:54:28.213  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.214  4296  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 09:54:28.222  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:54:28.231  3935  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 09:54:28.232  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:54:28.233  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:28.233  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.234  4296  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:28.235  4296  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:28.235  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:54:28.235  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.236  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:28.236  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 09:54:28.236  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:28.236  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:28.237  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:54:28.237  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:28.237  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:54:28.239  3935  3986 D BluetoothAdapter: STATE_ON
,08-29 09:54:28.240  4296  4309 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:54:28.242  4296  4327 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 09:54:28.243  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:28.243  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:28.243  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:54:28.244  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 09:54:28.244  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:28.246  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:28.247  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:28.247  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 09:54:28.247  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:28.249  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:54:28.251  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:28.251  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 09:54:28.252  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:28.257  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:28.258  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:28.258  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:28.258  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.258  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.258  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:28.259  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:28.259  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9adfc6 removed from the list
08-29 09:54:28.259  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.259  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d43cb87 removed from the list
08-29 09:54:28.259  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:28.260  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.261  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.261  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.263  4296  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:28.263  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.263  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:28.263  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.264  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.264  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d43cb87 not in the list
08-29 09:54:28.264  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.264  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.266  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:28.267  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:28.267  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.267  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2553252 removed from the list
08-29 09:54:28.267  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:54:28.267  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.268  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.268  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:28.268  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@687c6dd removed from the list
,08-29 09:54:28.270  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:28.270  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0219e added. We now have 2 listener(s)
,08-29 09:54:28.273  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 09:54:28.273  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.273  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.273  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:28.273  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db0a47f added. We now have 9 listener(s)
08-29 09:54:28.273  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.274  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:28.275  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:28.276  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.278  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:28.284  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:28.286  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 09:54:28.286  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.286  4296  4317 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:54:28.287  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:28.288  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:28.288  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.289  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa1f495 added. We now have 3 listener(s)
,08-29 09:54:28.291  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:28.292  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.292  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:54:28.292  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:28.292  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b9aa added. We now have 10 listener(s)
08-29 09:54:28.292  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.292  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:28.292  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:28.293  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:28.293  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.294  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:28.294  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:28.294  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:28.294  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.294  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:28.294  4296  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:54:28.298  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:28.300  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:54:28.300  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:54:28.304  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:28.304  4296  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 09:54:28.304  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.305  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:54:28.305  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:28.308  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:54:28.308  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:54:28.309  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:54:28.309  3935  3986 D BluetoothAdapter: STATE_ON
,08-29 09:54:28.311  4296  4340 D BtGatt.GattService: registerClient() - UUID=d2b3f0bd-5f14-44fb-b9ee-1008ccd71cb4
,08-29 09:54:28.312  4296  4314 D BtGatt.GattService: onClientRegistered() - UUID=d2b3f0bd-5f14-44fb-b9ee-1008ccd71cb4, clientIf=5
,08-29 09:54:28.312  3935  3947 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:54:28.313  4296  4309 D BtGatt.GattService: start scan with filters
,08-29 09:54:28.316  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:54:28.316  4296  4317 D BtGatt.ScanManager: handling starting scan
08-29 09:54:28.316  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:28.316  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:28.316  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:54:28.318  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:28.319  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:28.319  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:54:28.321  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:54:28.324  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:54:28.324  3935  3986 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 09:54:28.324  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:28.325  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:28.325  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:54:28.325  4296  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:54:28.325  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.325  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.325  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.325  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:28.325  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:28.325  4296  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:54:28.325  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0219e removed from the list
08-29 09:54:28.325  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.325  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db0a47f removed from the list
08-29 09:54:28.325  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:28.326  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:28.326  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.326  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 09:54:28.326  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.327  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:28.327  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:28.328  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.328  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.328  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db0a47f not in the list
08-29 09:54:28.328  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:28.328  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:28.328  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:28.328  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:28.328  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:54:28.329  3935  3986 D BluetoothAdapter: STATE_ON
08-29 09:54:28.329  4296  4326 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:54:28.330  4296  4340 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:54:28.330  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:28.330  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:28.330  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:54:28.331  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:28.331  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:28.332  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:28.332  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 09:54:28.332  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:28.332  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:28.332  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.334  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 09:54:28.334  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:28.334  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:28.334  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.334  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:54:28.334  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.334  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b9aa removed from the list
08-29 09:54:28.335  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.335  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.335  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.335  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.335  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa1f495 removed from the list
08-29 09:54:28.335  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:28.335  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.336  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:28.336  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc0c676 added. We now have 2 listener(s)
,08-29 09:54:28.336  4296  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:28.336  4296  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:28.337  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 09:54:28.337  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.338  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.338  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:28.338  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d0a477 added. We now have 9 listener(s)
08-29 09:54:28.338  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:28.338  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:28.341  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:28.346  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:28.349  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:28.349  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:28.349  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.350  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fad214d added. We now have 3 listener(s)
,08-29 09:54:28.352  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:28.352  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.352  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.352  4296  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:28.352  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:28.352  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.352  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6ad402 added. We now have 10 listener(s)
08-29 09:54:28.352  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:28.353  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:28.353  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:54:28.353  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 09:54:28.353  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:28.353  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:28.353  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:28.357  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:28.358  3935  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
08-29 09:54:28.358  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:28.359  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:28.359  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.362  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:28.363  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:54:28.363  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:28.367  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:54:28.367  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:54:28.367  3935  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:54:28.368  3935  3986 D BluetoothAdapter: STATE_ON
,08-29 09:54:28.371  4296  4309 D BtGatt.GattService: registerClient() - UUID=479e16a7-8b94-4853-8cd6-77ae14f02e13
,08-29 09:54:28.372  4296  4314 D BtGatt.GattService: onClientRegistered() - UUID=479e16a7-8b94-4853-8cd6-77ae14f02e13, clientIf=5
08-29 09:54:28.372  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 09:54:28.372  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:54:28.372  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.372  4296  4317 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:28.372  4296  4327 D BtGatt.GattService: start scan with filters
,08-29 09:54:28.378  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:54:28.378  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:28.378  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 09:54:28.378  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:54:28.379  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:28.379  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.379  4296  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:54:28.382  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:28.382  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:54:28.382  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:28.384  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:54:28.386  4296  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:54:28.386  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.388  4296  4317 D BtGatt.ScanManager: handling starting scan
,08-29 09:54:28.390  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:28.390  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:28.390  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:54:28.390  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.390  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.390  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:28.390  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.390  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc0c676 removed from the list
,08-29 09:54:28.390  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:28.390  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d0a477 removed from the list,
,08-29 09:54:28.390  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:28.391  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:54:28.391  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.391  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 09:54:28.391  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.391  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:28.392  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:54:28.392  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.392  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.392  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d0a477 not in the list
08-29 09:54:28.393  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:54:28.393  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 09:54:28.393  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:54:28.393  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 09:54:28.393  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:54:28.393  3935  3986 D BluetoothAdapter: STATE_ON
,08-29 09:54:28.394  4296  4338 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:54:28.395  4296  4308 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 09:54:28.395  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:28.395  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 09:54:28.395  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:54:28.395  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:28.396  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:54:28.397  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:28.397  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:28.397  3935  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:28.397  4296  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:54:28.397  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.397  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:28.398  4296  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:54:28.398  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.400  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.400  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:28.400  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.400  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6ad402 removed from the list
08-29 09:54:28.400  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.400  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:28.400  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.400  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.400  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:28.400  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:28.400  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fad214d removed from the list
08-29 09:54:28.400  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:28.401  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:28.401  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb62e4e added. We now have 2 listener(s)
08-29 09:54:28.403  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:28.403  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:28.403  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.403  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:28.404  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01ab6f added. We now have 9 listener(s)
08-29 09:54:28.404  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:28.404  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:54:28.404  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 09:54:28.405  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.405  4296  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:28.405  4296  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:54:28.408  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-29 09:54:28.412  3935  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:28.415  3935  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-29 09:54:28.415  3935  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:28.416  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:28.416  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea2d05 added. We now have 3 listener(s)
08-29 09:54:28.418  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 09:54:28.418  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-29 09:54:28.418  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:28.418  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:28.418  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ae15a added. We now have 10 listener(s)
08-29 09:54:28.418  3935  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:28.419  3935  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:28.419  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:54:28.419  3935  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:54:28.419  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:54:28.419  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:54:28.419  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:54:28.421  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.421  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb62e4e removed from the list
08-29 09:54:28.421  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:28.422  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01ab6f removed from the list
,08-29 09:54:28.422  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 09:54:28.425  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:28.425  3935  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:28.425  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:28.426  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.426  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:28.427  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 09:54:28.427  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.427  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:54:28.427  3935  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01ab6f not in the list
08-29 09:54:28.427  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.428  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 09:54:28.429  4296  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:54:28.430  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.430  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:28.430  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:54:28.430  3935  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:28.430  3935  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ae15a removed from the list
,08-29 09:54:28.430  3935  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:28.431  3935  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:28.431  3935  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 09:54:28.431  3935  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:28.431  3935  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea2d05 removed from the list
,08-29 09:54:28.435  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 09:54:28.435  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:54:28.435  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 09:54:28.436  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:28.436  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 09:54:28.436  3935  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:28.441  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:54:28.441  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:54:28.444  3935  4379 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: My test thread name)
,08-29 09:54:28.445  3935  4379 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 470, thread name: My test thread name)
08-29 09:54:28.445  3935  4379 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 470, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:54:28.448  3935  4380 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: My test thread name)
,08-29 09:54:28.448  3935  4380 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 472, thread name: My test thread name)
08-29 09:54:28.449  3935  4380 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:54:28.449  4296  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 09:54:28.449  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.451  3935  3986 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 09:54:28.451  3935  3986 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 09:54:28.451  3935  3986 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-29 09:54:28.451  3935  3986 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-29 09:54:28.451  3935  3986 D com.test.thalitest.ThaliTestRunner: Total duration: 22945 ms
08-29 09:54:28.451  4296  4317 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:28.453  3935  3986 I jxcore-log: Total number of executed tests:  80,
08-29 09:54:28.453  3935  3986 I jxcore-log: 
08-29 09:54:28.453  3935  3986 I jxcore-log: Number of passed tests:  80
08-29 09:54:28.453  3935  3986 I jxcore-log: 
08-29 09:54:28.453  3935  3986 I jxcore-log: Number of failed tests:  0
08-29 09:54:28.453  3935  3986 I jxcore-log: 
,08-29 09:54:28.454  3935  3986 I jxcore-log: Number of ignored tests:  0
08-29 09:54:28.454  3935  3986 I jxcore-log: 
08-29 09:54:28.454  3935  3986 I jxcore-log: Total duration:  22945
08-29 09:54:28.454  3935  3986 I jxcore-log: 
08-29 09:54:28.454  3935  3986 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-29 09:54:28.454  3935  3986 I jxcore-log: 
08-29 09:54:28.457  4296  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:54:28.457  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.457  4296  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:54:28.459  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.459  3935  3986 I jxcore-log: 
08-29 09:54:28.462  3935  3935 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 09:54:28.463  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.463  3935  3986 I jxcore-log: 
08-29 09:54:28.463  4296  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:54:28.463  4296  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:54:28.464  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.464  3935  3986 I jxcore-log: 
08-29 09:54:28.465  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.465  3935  3986 I jxcore-log: 
08-29 09:54:28.466  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.466  3935  3986 I jxcore-log: 
08-29 09:54:28.467  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.467  3935  3986 I jxcore-log: 
08-29 09:54:28.469  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.469  3935  3986 I jxcore-log: 
08-29 09:54:28.471  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.471  3935  3986 I jxcore-log: 
,08-29 09:54:28.472  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.472  3935  3986 I jxcore-log: 
08-29 09:54:28.473  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:28.473  3935  3986 I jxcore-log: 
08-29 09:54:28.474  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:28.474  3935  3986 I jxcore-log: 
08-29 09:54:28.475  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:28.475  3935  3986 I jxcore-log: 
08-29 09:54:28.476  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.476  3935  3986 I jxcore-log: 
08-29 09:54:28.476  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.476  3935  3986 I jxcore-log: 
08-29 09:54:28.477  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.477  3935  3986 I jxcore-log: 
08-29 09:54:28.478  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.478  3935  3986 I jxcore-log: 
08-29 09:54:28.478  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.478  3935  3986 I jxcore-log: 
08-29 09:54:28.479  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.479  3935  3986 I jxcore-log: 
08-29 09:54:28.480  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.480  3935  3986 I jxcore-log: 
08-29 09:54:28.480  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.480  3935  3986 I jxcore-log: 
,08-29 09:54:28.482  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.482  3935  3986 I jxcore-log: 
,08-29 09:54:28.483  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:28.483  3935  3986 I jxcore-log: 
08-29 09:54:28.484  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:28.484  3935  3986 I jxcore-log: 
,08-29 09:54:28.484  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:28.484  3935  3986 I jxcore-log: 
,08-29 09:54:28.485  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.485  3935  3986 I jxcore-log: 
,08-29 09:54:28.486  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.486  3935  3986 I jxcore-log: 
08-29 09:54:28.486  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.486  3935  3986 I jxcore-log: 
,08-29 09:54:28.487  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.487  3935  3986 I jxcore-log: 
,08-29 09:54:28.488  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.488  3935  3986 I jxcore-log: 
,08-29 09:54:28.488  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:28.488  3935  3986 I jxcore-log: 
,08-29 09:54:28.752  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:54:28.754  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:28.754  3935  3986 I jxcore-log: 
,08-29 09:54:28.834  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:54:28.836  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:28.836  3935  3986 I jxcore-log: 
,08-29 09:54:28.901  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:54:28.903  3935  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:28.903  3935  3986 I jxcore-log: 
,08-29 09:54:29.113  4381  4381 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 09:54:29.118  4381  4381 D AndroidRuntime: CheckJNI is OFF
,08-29 09:54:29.162  4381  4381 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 09:54:29.210  4381  4381 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 09:54:29.233  4381  4381 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 09:54:29.243   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-29 09:54:29.244   873   886 I ActivityManager: Killing 3935:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 09:54:29.330   873  2176 D GraphicsStats: Buffer count: 2
,08-29 09:54:29.331   873  2176 I WindowState: WIN DEATH: Window{45e11bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 09:54:29.342   873  1316 D WifiService: Client connection lost with reason: 4
,08-29 09:54:29.385   873   896 W PackageSettings: Skipping PackageSetting{3ec737c com.example.hello/10273} due to missing metadata
,08-29 09:54:29.419   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 09:54:29.420   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 09:54:29.420   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-29 09:54:29.420   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 09:54:29.420   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.420   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.420   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 09:54:29.420   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 09:54:29.421   873   886 I ActivityManager:   Force finishing activity ActivityRecord{ea25e94 u0 com.test.thalitest/.MainActivity t2}
08-29 09:54:29.424   873   896 I art     : Starting a blocking GC Explicit
,08-29 09:54:29.442   873  2002 W ActivityManager: Spurious death for ProcessRecord{27b6bed 0:com.test.thalitest/u0a0}, curProc for 3935: null
,08-29 09:54:29.479   873   896 I art     : Explicit concurrent mark sweep GC freed 13818(962KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.063ms total 54.391ms
,08-29 09:54:29.536   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 09:54:29.542  4381  4381 I art     : System.exit called, status: 0
,08-29 09:54:29.542  4381  4381 I AndroidRuntime: VM exiting with result code 0.
08-29 09:54:29.543   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 09:54:29.567   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 09:54:29.570  4296  4296 D BluetoothMapAppObserver: onReceive
08-29 09:54:29.570  4296  4296 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 09:54:29.577  1860  1860 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 09:54:29.580   873  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 09:54:29.582  1860  4392 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 09:54:29.583  3774  3774 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 09:54:29.585  2177  2321 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 09:54:29.590  1860  4392 I Decoder : createOrResetDecoder
,08-29 09:54:29.637  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 09:54:29.650   873  3269 I ActivityManager: Start proc 4395:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 09:54:29.654  1529  1529 I ConfigService: onCreate
,08-29 09:54:29.658  1529  4402 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-29 09:54:29.680   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 09:54:29.685  1860  4392 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 09:54:29.700  4395  4395 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 09:54:29.714   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 09:54:29.715   873   885 E PackageManager: Failed to write settings, restoring backup
08-29 09:54:29.715   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 09:54:29.715   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 09:54:29.715   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 09:54:29.715   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 09:54:29.715   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 09:54:29.715   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.715   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.715   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:29.715   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3935 uid 10000
,08-29 09:54:29.717  1860  1860 I Keyboard.Facilitator: onFinishInput()
,08-29 09:54:29.717  1938  2018 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 09:54:29.719   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-29 09:54:29.719   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 09:54:29.719   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:29.719   873   886 E DropBoxManagerService: 	... 13 more
,08-29 09:54:29.723  1860  4392 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 09:54:29.725  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 09:54:29.725  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 09:54:29.727  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 09:54:29.727  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 09:54:29.728  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 09:54:29.728  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 09:54:29.731   873  1991 I ActivityManager: Start proc 4409:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 09:54:29.736  1938  2018 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 09:54:29.736  1938  2018 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-29 09:54:29.736  1938  2018 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.736  1938  2018 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:29.738   873  1944 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 09:54:29.738   873  4420 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:29.738   873  4420 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:29.738   873  4420 E DropBoxManagerService: 	... 5 more
,08-29 09:54:29.745  1860  4392 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 09:54:29.745  1860  4392 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 09:54:29.745  1860  4392 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 09:54:29.745  1860  4392 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 09:54:29.745  1860  4392 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 09:54:29.745  1860  4392 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-29 09:54:29.748  1938  2018 I Process : Sending signal. PID: 1938 SIG: 9
,08-29 09:54:29.782  4395  4395 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 09:54:29.803   873  1379 D GraphicsStats: Buffer count: 1
,08-29 09:54:29.803   873  1928 I WindowState: WIN DEATH: Window{21c0556 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 09:54:29.805   873  2198 I ActivityManager: Start proc 4427:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 09:54:29.815  4395  4425 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 09:54:29.821   873  1400 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1938) has died
08-29 09:54:29.821   873  1400 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 09:54:29.823   873  1400 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 09:54:29.830  4395  4423 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.830  4395  4423 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.830  4395  4423 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:29.847   873   886 I ActivityManager: Start proc 4439:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 09:54:29.869  4427  4427 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 09:54:29.885   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 09:54:29.886  1529  1529 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error,
08-29 09:54:29.887  1529  1529 D AndroidRuntime: Shutting down VM
,08-29 09:54:29.888  1529  1529 E AndroidRuntime: FATAL EXCEPTION: main
08-29 09:54:29.888  1529  1529 E AndroidRuntime: Process: com.google.process.gapps, PID: 1529
08-29 09:54:29.888  1529  1529 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 09:54:29.888  1529  1529 E AndroidRuntime: 	... 8 more
,08-29 09:54:29.890   873  4454 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:29.890   873  4454 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:29.890   873  4454 E DropBoxManagerService: 	... 5 more
,08-29 09:54:29.891  1529  1529 I Process : Sending signal. PID: 1529 SIG: 9
,08-29 09:54:29.900  4439  4439 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:29.900  4439  4439 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:54:29.900  4439  4439 D AndroidRuntime: Shutting down VM
,08-29 09:54:29.907  4439  4439 E AndroidRuntime: FATAL EXCEPTION: main
08-29 09:54:29.907  4439  4439 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4439
08-29 09:54:29.907  4439  4439 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:29.907  4439  4439 E AndroidRuntime: 	... 10 more
08-29 09:54:29.909   873  3269 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 09:54:29.909  4439  4439 I Process : Sending signal. PID: 4439 SIG: 9
,08-29 09:54:29.915   873  4457 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:29.915   873  4457 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:29.915   873  4457 E DropBoxManagerService: 	... 5 more
,08-29 09:54:29.926   873  1316 D WifiService: Client connection lost with reason: 4
,08-29 09:54:29.927  1756  4455 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@94e239b
,08-29 09:54:29.931   873   883 I ActivityManager: Process com.google.process.gapps (pid 1529) has died
,08-29 09:54:29.931   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-29 09:54:29.932   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 10999ms
,08-29 09:54:29.932   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
08-29 09:54:29.932   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-29 09:54:29.938  1756  1756 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 09:54:29.946   873  1379 I ActivityManager: Start proc 4458:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-29 09:54:29.947   873  1991 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4439) has died
,08-29 09:54:29.948   873  1991 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 09:54:29.957  4395  4423 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 09:54:29.964   873   886 I ActivityManager: Start proc 4469:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 09:54:29.981  4458  4458 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 09:54:29.986  4458  4458 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-29 09:54:29.988  4458  4458 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:29.988  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:54:29.989  4458  4458 D AndroidRuntime: Shutting down VM
08-29 09:54:29.989  4458  4458 E AndroidRuntime: FATAL EXCEPTION: main
08-29 09:54:29.989  4458  4458 E AndroidRuntime: Process: com.google.process.gapps, PID: 4458
08-29 09:54:29.989  4458  4458 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:54:29.989  4458  4458 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:29.989  4458  4458 E AndroidRuntime: 	... 10 more
,08-29 09:54:29.992  4458  4458 I Process : Sending signal. PID: 4458 SIG: 9
,08-29 09:54:29.993   873  4485 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:29.993   873  4485 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:29.993   873  4485 E DropBoxManagerService: 	... 5 more
,08-29 09:54:29.997  4395  4425 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.997  4395  4425 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:29.998  4395  4425 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 09:54:29.998  4395  4425 E AndroidRuntime: Process: android.process.acore, PID: 4395
08-29 09:54:29.998  4395  4425 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:29.998  4395  4425 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:54:30.002  4395  4425 I Process : Sending signal. PID: 4395 SIG: 9
,08-29 09:54:30.002   873  4486 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:30.002   873  4486 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:30.002   873  4486 E DropBoxManagerService: 	... 5 more
,08-29 09:54:30.005  4469  4469 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:30.005  4469  4469 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:54:30.005  4469  4469 D AndroidRuntime: Shutting down VM
08-29 09:54:30.008  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 09:54:30.008  1756  1756 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-29 09:54:30.013  1756  1756 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 09:54:30.013  1756  1756 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 09:54:30.016  1756  4487 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-29 09:54:30.018  4469  4469 E AndroidRuntime: FATAL EXCEPTION: main
08-29 09:54:30.018  4469  4469 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4469
08-29 09:54:30.018  4469  4469 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 09:54:30.018  4469  4469 E AndroidRuntime: 	... 10 more
,08-29 09:54:30.024   873  4489 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:30.024   873  4489 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:30.024   873  4489 E DropBoxManagerService: 	... 5 more
,08-29 09:54:30.025   873  1928 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 09:54:30.026  4469  4469 I Process : Sending signal. PID: 4469 SIG: 9
08-29 09:54:30.030   873  3269 I ActivityManager: Process com.google.process.gapps (pid 4458) has died
08-29 09:54:30.030  1756  4487 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 09:54:30.030  1756  4487 E AndroidRuntime: Process: com.google.android.gms, PID: 1756
08-29 09:54:30.030  1756  4487 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 09:54:30.030  1756  4487 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-29 09:54:30.031   873  3269 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a5cd936 u0 com.google.android.gms/.auth.GetToken}
08-29 09:54:30.031   873  3269 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{80e8001 u0 com.google.android.gms/.config.ConfigService}
08-29 09:54:30.031   873  3269 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{766fc02 u0 com.google.android.gms/.gcm.GcmService}
08-29 09:54:30.031   873  3269 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{2097620 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,08-29 09:54:30.043   873  3269 I ActivityManager: Start proc 4491:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-29 09:54:30.045   873  1928 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4469) has died
,08-29 09:54:30.047   873  4501 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:30.047   873  4501 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:54:30.047   873  4501 E DropBoxManagerService: 	... 5 more
08-29 09:54:30.047   873  1928 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 09:54:30.053  1992  4490 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-29 09:54:30.060   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
