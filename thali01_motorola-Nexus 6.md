#### Test 846390993028cf2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 14:51:27.251   872  1852 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
09-09 14:51:27.366  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:51:27.376  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:51:27.378  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:51:27.413  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 14:51:27.414  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 14:51:27.414  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:27.414  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 14:51:27.439  3596  3596 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 14:51:27.439  3596  3596 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 14:51:27.440  3596  3596 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 14:51:28.178  3867  3867 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 14:51:28.183  3867  3867 D AndroidRuntime: CheckJNI is OFF
09-09 14:51:28.223  3867  3867 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 14:51:28.271  3867  3867 I Radio-JNI: register_android_hardware_Radio DONE
09-09 14:51:28.293  3867  3867 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 14:51:28.297   872  1944 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 14:51:28.338  2056  2077 W SearchService: Abort, client detached.
09-09 14:51:28.345  2056  2056 I HotwordDetector: Closing mic
09-09 14:51:28.346  2056  2327 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e5b05d2
09-09 14:51:28.347  2056  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 14:51:28.348  3867  3867 D AndroidRuntime: Shutting down VM
09-09 14:51:28.366   872  2096 I ActivityManager: Start proc 3876:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 14:51:28.401   376  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 14:51:28.403   376  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 14:51:28.416   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 14:51:28.418  2056  2335 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 14:51:28.418  2056  2342 I MicroRecognitionRnrImpl: Detection finished
09-09 14:51:28.451  3876  3876 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 14:51:28.475  3876  3876 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 14:51:28.483  3876  3876 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9999-2)
09-09 14:51:28.483  3876  3876 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:51:28.496  3876  3876 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2552b72}
09-09 14:51:28.497  3876  3876 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:51:28.497  3876  3876 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 14:51:28.505  3876  3876 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 14:51:28.506  3876  3876 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 14:51:28.524  3876  3876 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 14:51:28.538  3876  3876 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:51:28.538  3876  3876 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:51:28.539  3876  3876 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 14:51:28.539  3876  3876 I Adreno  : Build Date                       : 10/20/15
09-09 14:51:28.539  3876  3876 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 14:51:28.539  3876  3876 I Adreno  : Local Branch                     : M14
09-09 14:51:28.539  3876  3876 I Adreno  : Remote Branch                    : 
09-09 14:51:28.539  3876  3876 I Adreno  : Remote Branch                    : 
09-09 14:51:28.539  3876  3876 I Adreno  : Reconstruct Branch               : 
,09-09 14:51:28.602   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c8e2fe6:true
,09-09 14:51:28.622  3876  3876 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 14:51:28.634  3876  3876 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 14:51:28.709  3876  3914 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 14:51:28.716  3876  3901 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 14:51:28.755  3876  3914 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 14:51:28.876   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +526ms
,09-09 14:51:28.883  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-09 14:51:28.994  3876  3876 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3876
,09-09 14:51:29.182  3876  3876 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 14:51:29.189   872  2015 I ActivityManager: Killing 3062:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 14:51:29.238   872  2015 I ActivityManager: Killing 3271:com.google.android.gm/u0a78 (adj 15): empty #18
,09-09 14:51:29.381  3876  3918 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1695614672
,09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 14:51:29.386  3876  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@645a856 added. We now have 1 listener(s),
,09-09 14:51:29.389  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 14:51:29.390  3876  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:51:29.391  3876  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:51:29.391  3876  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 14:51:29.397  3876  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe154ad added. We now have 1 listener(s)
09-09 14:51:29.398  3876  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:51:29.401   872  1307 D WifiService: New client listening to asynchronous messages
,09-09 14:51:29.402  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:51:29.402  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 14:51:29.403  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 14:51:29.403  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 14:51:29.403  3876  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 14:51:29.406  3876  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:51:29.406  3876  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 14:51:29.411  3876  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:29.412  3876  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:29.412  3876  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 14:51:29.412  3876  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:51:29.413  3876  3918 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 14:51:29.428  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:29.432  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:29.457  3876  3876 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 14:51:30.301  3876  3927 W jxcore-log: Initializing JXcore engine
,09-09 14:51:30.301  3876  3927 W jxcore-log: JXcore engine is ready
,09-09 14:51:30.396  3927  3927 W Thread-350: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 14:51:30.396  3927  3927 W Thread-350: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9657]" dev="sockfs" ino=9657 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 14:51:30.396  3927  3927 W Thread-350: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 14:51:30.396  3927  3927 W Thread-350: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26802]" dev="sockfs" ino=26802 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 14:51:30.411  3876  3927 W jxcore-log: Starting JXcore engine
,09-09 14:51:30.541  3876  3927 W jxcore-log: Platform android
09-09 14:51:30.541  3876  3927 W jxcore-log: 
,09-09 14:51:30.541  3876  3927 W jxcore-log: Process ARCH arm
09-09 14:51:30.541  3876  3927 W jxcore-log: 
,09-09 14:51:30.732  3876  3927 I jxcore-log: JXcore Cordova bridge is ready!
09-09 14:51:30.732  3876  3927 I jxcore-log: 
,09-09 14:51:30.732  3876  3927 W jxcore-log: JXcore engine is started
09-09 14:51:30.732   872  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 14:51:30.746  3876  3918 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 14:51:30.750  3876  3876 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 14:51:35.577  3120  3935 V KeepSync: Connecting to GoogleApiClient
,09-09 14:51:35.577   872  1994 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 14:51:35.623  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:35.625  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:35.641  1510  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 14:51:35.641  1510  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 14:51:35.641  1510  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:35.642  1510  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:35.652  1705  3936 V BaseAuthAsyncOperation: access token request failed
,09-09 14:51:35.653  3120  3935 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 14:51:35.692  1510  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 14:51:35.692  1510  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 14:51:35.692  1510  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:35.693  1510  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:35.709  3120  3935 E KeepSync: IOException
09-09 14:51:35.709  3120  3935 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 14:51:35.709  3120  3935 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 14:51:35.709  3120  3935 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 14:51:35.709  3120  3935 E KeepSync: 	... 10 more
,09-09 14:51:35.710  3120  3935 W KeepSync: Sync result 2
,09-09 14:51:35.723   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126999, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:51:40.726  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 14:51:40.726  3876  3927 I jxcore-log: 
,09-09 14:51:40.729  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 14:51:40.729  3876  3927 I jxcore-log: 
,09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:40.754  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:40.761  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:51:40.767  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 14:51:40.767  3876  3927 I jxcore-log: 
,09-09 14:51:40.774  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 14:51:40.774  3876  3927 I jxcore-log: 
,09-09 14:51:41.300  3876  3927 D executeNativeTests: Running unit tests
,09-09 14:51:41.358  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:51:41.358  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 added. We now have 2 listener(s)
,09-09 14:51:41.359  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:51:41.359  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:51:41.359  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:51:41.359  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:41.359  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 added. We now have 2 listener(s)
09-09 14:51:41.359  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:41.360  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:51:41.364  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.376  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:41.380  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:51:41.380  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:51:41.382  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 14:51:41.382  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:51:41.382  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:51:41.383  3876  3927 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 14:51:41.384  3876  3927 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:51:41.384  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:51:41.384  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:51:41.384  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:51:41.384  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.385  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.385  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.385  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.385  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.386  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:51:41.386  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:51:41.386  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 removed from the list
09-09 14:51:41.386  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.386  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 removed from the list
09-09 14:51:41.391  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.399  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.399  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.399  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.400  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.400  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.400  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.400  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.400  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.401  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.402  3876  3927 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 14:51:41.403  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.403  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.403  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.404  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.404  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.404  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.405  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.406  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.406  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.406  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.407  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.407  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.407  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.407  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.410  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.410  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.410  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.410  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.416  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:51:41.416  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:51:41.416  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:51:41.417  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:51:41.418  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:51:41.418  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.418  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.418  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.419  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.419  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.419  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.419  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.419  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.419  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.419  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.419  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.419  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.419  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.419  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.420  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.420  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.420  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.420  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.421  3876  3927 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:51:41.423  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.429  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:51:41.432  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.432  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:51:41.433  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:51:41.433  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 14:51:41.433  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:51:41.433  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.433  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:51:41.434  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:41.436  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:41.437  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:51:41.437  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:51:41.444  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:51:41.446  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 14:51:41.447  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:51:41.450  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 14:51:41.454  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 14:51:41.454  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 14:51:41.454  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:51:41.455  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 14:51:41.456  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:51:41.461  2701  2809 D BtGatt.GattService: registerClient() - UUID=61da833e-0785-4e8b-a5d2-a1492682e5b8
,09-09 14:51:41.462  2701  2734 D BtGatt.GattService: onClientRegistered() - UUID=61da833e-0785-4e8b-a5d2-a1492682e5b8, clientIf=5
,09-09 14:51:41.463  3876  3888 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:51:41.464  2701  2713 D BtGatt.GattService: start scan with filters
,09-09 14:51:41.468  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 14:51:41.469  2701  2738 D BtGatt.ScanManager: handling starting scan
09-09 14:51:41.470  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:51:41.471  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 14:51:41.472  2701  2738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:41.472  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:51:41.479  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:51:41.481  2701  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 14:51:41.481  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:51:41.481  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:51:41.482  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 14:51:41.482  2701  2738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 14:51:41.488  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:51:41.489  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:51:41.489  2701  2738 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:51:41.489  2701  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:51:41.489  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:51:41.496  3876  3927 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 14:51:41.501  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:51:41.501  2701  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 14:51:41.501  3876  3927 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:51:41.501  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.501  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:51:41.501  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 14:51:41.502  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.502  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 14:51:41.502  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 14:51:41.502  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:51:41.503  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 14:51:41.503  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 14:51:41.506  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:51:41.506  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 14:51:41.507  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 14:51:41.507  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.507  3876  3927 D BluetoothAdapter: STATE_ON
09-09 14:51:41.508  2701  2809 D BtGatt.GattService: stopScan() - queue size =1
,09-09 14:51:41.509  2701  2713 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:51:41.509  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:51:41.510  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:51:41.510  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 14:51:41.510  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:51:41.510  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:51:41.511  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:51:41.511  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:51:41.511  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:51:41.511  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:51:41.512  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:51:41.514  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.514  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:51:41.514  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.515  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.515  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.515  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:51:41.515  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
,09-09 14:51:41.515  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.515  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.515  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.515  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:51:41.515  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:51:41.515  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.515  2701  2738 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:51:41.516  3876  3927 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:51:41.517  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.522  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:41.522  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:51:41.522  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.522  2701  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:51:41.523  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:51:41.523  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:51:41.524  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:51:41.525  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 14:51:41.525  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:51:41.525  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.525  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:41.525  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:51:41.527  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.530  2701  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 14:51:41.530  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.530  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:51:41.530  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:51:41.533  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:51:41.534  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:51:41.534  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:51:41.537  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 14:51:41.537  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 14:51:41.537  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:51:41.538  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:51:41.539  2701  2801 D BtGatt.GattService: registerClient() - UUID=3d1a0a51-5e1e-4464-b1cb-1632c1b4b615
,09-09 14:51:41.540  2701  2734 D BtGatt.GattService: onClientRegistered() - UUID=3d1a0a51-5e1e-4464-b1cb-1632c1b4b615, clientIf=5
,09-09 14:51:41.540  3876  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 14:51:41.541  2701  2809 D BtGatt.GattService: start scan with filters
,09-09 14:51:41.543  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 14:51:41.543  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:51:41.543  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:51:41.543  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:51:41.543  2701  2738 D BtGatt.ScanManager: handling starting scan
,09-09 14:51:41.545  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:51:41.545  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 14:51:41.545  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:51:41.546  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:51:41.548  3876  3927 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 14:51:41.549  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:51:41.549  3876  3927 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 14:51:41.549  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:51:41.550  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 14:51:41.550  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:51:41.550  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 14:51:41.550  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 14:51:41.550  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 14:51:41.550  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,09-09 14:51:41.550  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 14:51:41.550  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 14:51:41.550  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:51:41.550  3876  3927 D BluetoothAdapter: STATE_ON
09-09 14:51:41.550  2701  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 14:51:41.550  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.551  2701  2738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 14:51:41.551  2701  2801 D BtGatt.GattService: stopScan() - queue size =1
,09-09 14:51:41.551  2701  2809 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 14:51:41.552  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:51:41.552  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:51:41.552  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:51:41.552  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:51:41.552  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 14:51:41.552  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:51:41.552  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 14:51:41.553  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 14:51:41.553  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,09-09 14:51:41.553  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:51:41.554  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:51:41.554  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.554  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:51:41.554  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.554  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.554  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
,09-09 14:51:41.554  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.554  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.554  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:51:41.554  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.554  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.554  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:51:41.555  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:51:41.556  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:51:41.556  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-09 14:51:41.556  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:51:41.556  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
,09-09 14:51:41.556  3876  3927 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:51:41.557  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:51:41.557  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.557  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:51:41.558  2701  2738 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:51:41.558  2701  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.560  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:41.562  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.562  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:51:41.562  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:51:41.562  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:51:41.562  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:51:41.562  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.562  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:51:41.566  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.567  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:51:41.568  2701  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:51:41.568  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.569  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:51:41.570  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.573  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:51:41.573  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.574  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:51:41.575  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:51:41.575  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:51:41.579  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:51:41.579  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.580  2701  2738 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:51:41.581  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 14:51:41.581  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:51:41.581  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:51:41.582  3876  3927 D BluetoothAdapter: STATE_ON
09-09 14:51:41.584  2701  2809 D BtGatt.GattService: registerClient() - UUID=f35bd183-a565-474c-a278-0dd183565425
09-09 14:51:41.584  2701  2734 D BtGatt.GattService: onClientRegistered() - UUID=f35bd183-a565-474c-a278-0dd183565425, clientIf=5
09-09 14:51:41.585  3876  3917 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 14:51:41.585  2701  2714 D BtGatt.GattService: start scan with filters
09-09 14:51:41.585  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:51:41.585  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.586  2701  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:51:41.589  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:51:41.590  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:51:41.590  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:51:41.590  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:51:41.590  2701  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:51:41.590  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.592  2701  2738 D BtGatt.ScanManager: handling starting scan
09-09 14:51:41.593  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:51:41.593  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:51:41.593  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:51:41.595  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 14:51:41.596  2701  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:51:41.596  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.597  2701  2738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:51:41.598  3876  3927 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:51:41.598  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.598  3876  3927 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:51:41.602  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.602  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 14:51:41.602  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.602  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:51:41.602  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:51:41.602  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:51:41.602  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:51:41.602  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.602  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:51:41.602  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:51:41.602  2701  2738 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:51:41.602  2701  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:51:41.602  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:51:41.603  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:51:41.603  3876  3927 D BluetoothAdapter: STATE_ON
09-09 14:51:41.604  2701  2714 D BtGatt.GattService: stopScan() - queue size =1
09-09 14:51:41.604  2701  2713 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:51:41.604  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:51:41.605  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:51:41.605  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:51:41.605  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:51:41.605  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:51:41.606  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.606  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:51:41.606  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:51:41.606  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:51:41.606  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:51:41.607  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.607  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:51:41.607  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.608  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.608  3876  3927 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:51:41.608  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.608  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.608  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.608  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.608  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:51:41.609  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.609  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.609  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.609  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.609  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.609  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.609  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.610  2701  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:51:41.610  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.610  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.611  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.611  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.611  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.611  3876  3927 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 14:51:41.612  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.612  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.612  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.612  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.612  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.612  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.613  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.613  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.613  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.613  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.613  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.613  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.613  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.613  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.614  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.614  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.614  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.614  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.615  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:51:41.615  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.615  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:51:41.615  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.615  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.616  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.616  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.616  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.616  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.616  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.616  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.616  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.616  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.616  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.616  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.616  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.617  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.618  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.618  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.618  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.618  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.619  3876  3927 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 14:51:41.619  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.619  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.619  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.619  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.619  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.619  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.619  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.619  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.620  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.620  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.620  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.620  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.620  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.620  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.621  2701  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:51:41.621  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.621  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:51:41.621  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.621  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.621  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.621  2701  2738 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:51:41.622  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 14:51:41.622  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.622  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.622  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.622  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.622  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.622  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.622  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.622  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.623  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.623  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.623  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.623  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.623  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.623  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.624  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.624  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.624  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.624  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.626  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:51:41.627  2701  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:51:41.627  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.627  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:51:41.627  2701  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 14:51:41.627  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:51:41.627  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:51:41.627  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:51:41.628  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:51:41.628  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.628  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.628  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.628  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.628  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.628  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.628  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.628  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.629  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.629  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.629  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.629  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.629  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.629  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.630  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.630  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.630  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.630  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.630  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:51:41.631  3876  3927 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:51:41.631  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:51:41.633  2701  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:51:41.633  2701  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:51:41.635  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:51:41.635  3876  3927 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:51:41.636  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:51:41.637  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:51:41.639  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:51:41.639  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:51:41.639  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 14:51:41.639  3876  3927 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:51:41.639  3876  3927 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 14:51:41.639  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:51:41.639  3876  3927 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:51:41.639  3876  3927 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 14:51:41.640  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:51:41.640  3876  3927 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:51:41.640  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 14:51:41.644  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 14:51:41.644  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 14:51:41.644  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 14:51:41.645  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 14:51:41.645  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 14:51:41.645  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 14:51:41.645  3876  3927 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:51:41.645  3876  3927 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 14:51:41.646  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.646  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.646  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.646  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.646  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.647  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.647  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 14:51:41.647  3876  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 414)
09-09 14:51:41.647  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.647  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.647  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.647  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.647  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.647  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.647  3876  3942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 414
09-09 14:51:41.648  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.648  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.649  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.649  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.649  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.649  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.649  3876  3941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:51:41.650  3876  3927 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 14:51:41.650  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.650  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.650  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.650  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.651  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.651  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.651  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.651  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.651  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.651  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.651  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.651  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.651  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.651  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.653  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.653  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.653  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.653  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.653  3876  3927 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 14:51:41.654  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.654  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.654  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.654  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.654  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.654  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.654  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.654  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.654  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.655  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.655  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.655  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.655  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.655  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.655  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.656  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.656  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.656  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.656  3876  3927 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 14:51:41.656  3876  3927 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 14:51:41.656  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:51:41.656  3876  3927 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 14:51:41.657  3876  3927 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:51:41.657  3876  3927 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 14:51:41.657  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:51:41.657  3876  3927 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 14:51:41.657  3876  3927 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:51:41.657  3876  3927 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:51:41.657  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:51:41.657  3876  3927 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 14:51:41.657  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.657  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.657  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.658  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.658  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.658  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.658  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.658  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.658  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.658  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.658  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.658  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.658  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.658  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.660  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.660  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.660  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.660  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.660  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.660  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.660  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.660  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.660  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.661  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.661  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.661  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.661  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.661  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.661  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.661  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.661  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.661  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.661  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.661  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.661  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.661  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.662  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.662  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.662  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.662  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.662  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.662  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.662  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.662  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.662  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.662  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.662  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.663  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.664  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.664  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.664  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.665  3876  3927 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 14:51:41.665  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.666  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 14:51:41.667  3876  3927 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 14:51:41.667  3876  3927 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 14:51:41.667  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 14:51:41.667  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 14:51:41.667  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:51:41.668  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.668  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 14:51:41.668  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 14:51:41.669  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 14:51:41.669  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.669  3876  3927 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 14:51:41.669  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 14:51:41.669  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.669  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.669  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:51:41.669  3876  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 14:51:41.669  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:51:41.669  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:51:41.669  3876  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 14:51:41.670  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.670  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.671  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.671  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.671  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:51:41.671  3876  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 14:51:41.671  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:51:41.672  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.672  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.672  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.672  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.672  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.672  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.672  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.672  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.672  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.672  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.672  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.673  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.673  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.673  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.673  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.673  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.673  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.674  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.674  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.675  3876  3927 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 14:51:41.675  3876  3927 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:51:41.675  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:51:41.675  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:51:41.675  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.675  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.675  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.676  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.676  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.676  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.676  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.676  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.676  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.676  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.676  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.676  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.676  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.676  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.677  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.677  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.677  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.678  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.680  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.681  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.681  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.681  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.681  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.681  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.681  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.681  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:51:41.681  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.681  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.681  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.681  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.681  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.682  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.682  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.682  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.682  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.682  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.683  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:51:41.683  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:51:41.683  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:51:41.683  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:51:41.684  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.684  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.684  3876  3927 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cbda6 not in the list
09-09 14:51:41.684  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.684  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.684  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:51:41.684  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.684  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.684  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:51:41.684  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:51:41.685  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:51:41.685  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:51:41.685  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:51:41.685  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe983e7 not in the list
09-09 14:51:41.686  3876  3927 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 14:51:41.686  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:51:41.686  3876  3927 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 14:51:41.686  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:51:41.686  3876  3927 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 14:51:41.687  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:51:41.688  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:51:41.688  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 14:51:41.689  3876  3927 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 14:51:41.689  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:51:41.689  3876  3927 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 14:51:41.689  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:51:41.689  3876  3927 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 14:51:41.689  3876  3927 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 14:51:41.690  3876  3927 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 14:51:41.691  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:41.691  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9108671 added. We now have 2 listener(s)
09-09 14:51:41.691  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:41.693  3876  3927 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 14:51:41.693   872  2015 D WifiService: setWifiEnabled: true pid=3876, uid=10000
09-09 14:51:41.693   872  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:51:41.694  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:41.694  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@165dc56 added. We now have 3 listener(s)
09-09 14:51:41.694  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:41.699  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:41.699  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20534d7 added. We now have 4 listener(s)
09-09 14:51:41.699  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:41.701  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:41.701  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79b31c4 added. We now have 5 listener(s)
09-09 14:51:41.701  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:41.702   872  2096 D WifiService: setWifiEnabled: false pid=3876, uid=10000
09-09 14:51:41.702   872  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:51:41.707  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:51:41.708  2701  2730 D BluetoothAdapterState: Current state: ON, message: 23
09-09 14:51:41.708  2701  2730 D BluetoothAdapterProperties: Setting state to 13
09-09 14:51:41.708  2701  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:51:41.709  2701  2730 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:51:41.709  2701  2730 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:51:41.712  2701  2701 D BluetoothMapService: onReceive
09-09 14:51:41.712  2701  2701 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:51:41.712  2701  2701 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:51:41.712  2701  2701 D BluetoothMapService: MAP Service closeService in
09-09 14:51:41.712  2701  2701 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 14:51:41.712  2701  2701 D ObexServerSockets0: shutdown(block = true)
09-09 14:51:41.712  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:51:41.713  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:51:41.713  2701  2810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 14:51:41.713  2701  2798 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 14:51:41.714  2701  2811 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 14:51:41.714  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.714  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:51:41.714  2701  2701 I BtOppRfcommListener: stopping Accept Thread
09-09 14:51:41.715  2701  3502 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:51:41.715  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.715  2701  3502 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:51:41.715  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.715  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:51:41.718  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.720  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:51:41.720  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.722   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:51:41.722   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 14:51:41.722   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:51:41.722   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:51:41.724  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:41.724  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:51:41.725  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.725  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:41.728  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.728   872  1862 D DhcpClient: Clearing IP address
09-09 14:51:41.728   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:51:41.729   872   885 I ActivityManager: Start proc 3946:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 14:51:41.730  2701  2734 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:51:41.731  2701  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 14:51:41.731   372   871 D CommandListener: Setting iface cfg
,09-09 14:51:41.734  1510  2446 V NativeCrypto: Read error: ssl=0x9ac3ca00: I/O error during system call, Connection timed out
09-09 14:51:41.736  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.737  2701  2701 D HeadsetService: Received stop request...Stopping profile...
,09-09 14:51:41.739  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:41.739  1510  2446 V NativeCrypto: SSL shutdown failed: ssl=0x9ac3ca00: I/O error during system call, Broken pipe
09-09 14:51:41.740   872   872 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:41.740  1974  2130 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:41.741   872   872 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:41.741  1349  1367 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:41.742   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 14:51:41.742   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 14:51:41.742   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-09 14:51:41.743   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 14:51:41.743   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:51:41.744  2701  2701 D A2dpService: Received stop request...Stopping profile...
09-09 14:51:41.744  2701  2804 D A2dpStateMachine: Exit Disconnected: -1
,09-09 14:51:41.745  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-09 14:51:41.745   412   412 E Parcel  : Reading a NULL string not supported here.
,09-09 14:51:41.745   872   872 D BluetoothA2dp: Proxy object disconnected
,09-09 14:51:41.746  1349  1349 D BluetoothA2dp: Proxy object disconnected
,09-09 14:51:41.747  2701  2701 D HidService: Received stop request...Stopping profile...
,09-09 14:51:41.747  2701  2701 D HidService: Stopping Bluetooth HidService
09-09 14:51:41.748  1349  1349 D BluetoothInputDevice: Proxy object disconnected
,09-09 14:51:41.748  1349  1349 D HidProfile: Bluetooth service disconnected
09-09 14:51:41.748   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:51:41.750  2701  2701 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:51:41.750  2701  2701 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:51:41.750  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:51:41.751  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:41.753  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 14:51:41.753  2701  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-09 14:51:41.753  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:51:41.753  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:51:41.753  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:41.754  2701  2734 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
09-09 14:51:41.754  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:51:41.754  2701  2701 D HealthService: Received stop request...Stopping profile...
,09-09 14:51:41.755   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 14:51:41.758   872  1875 D DhcpClient: Receive thread stopped
09-09 14:51:41.759  2701  2701 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:51:41.759  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:41.759  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:51:41.759  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:41.761  2701  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 14:51:41.762   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 14:51:41.763  2701  2701 D PanService: Received stop request...Stopping profile...
,09-09 14:51:41.763  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:41.763  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:51:41.763  2701  2796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:51:41.763  2701  2796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 14:51:41.763  2701  2796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:51:41.763  2701  2796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 14:51:41.764  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:41.764  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:41.765  2701  2701 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:51:41.765  2701  2701 D BluetoothMapService: stop()
09-09 14:51:41.765  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.765  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:41.765  2701  2701 D BluetoothMapAppObserver: deinitObservers()
09-09 14:51:41.765  2701  2701 D BluetoothMapAppObserver: removeReceiver()
09-09 14:51:41.767  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:41.767  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:41.767   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:51:41.767  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:41.767  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:41.767  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:41.767  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:41.767  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:41.767  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:41.768  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:51:41.768  2701  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:51:41.768  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:51:41.768  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:41.768  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:41.768  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:41.768  2701  2701 V Blueto,othAdapterState: isBleTurningOff()=false
09-09 14:51:41.768  1861  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:51:41.770  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:51:41.771  2701  2734 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 14:51:41.771  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:51:41.771  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:41.771  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:41.771  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:41.771  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:41.771  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:51:41.772  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:51:41.772  2701  2701 D BluetoothMapService: MAP Service closeService in
09-09 14:51:41.772  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:41.772  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:41.772  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:41.772  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:41.773  2701  2701 D BluetoothMapService: cleanup()
09-09 14:51:41.773  2701  2701 D BluetoothMapService: MAP Service closeService in
09-09 14:51:41.773  2701  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 14:51:41.773  2701  2730 D BluetoothAdapterProperties: Setting state to 15
09-09 14:51:41.773  2701  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 14:51:41.774  1349  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:51:41.774  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:51:41.775  2701  2730 I BluetoothAdapterState: Entering BleOnState
09-09 14:51:41.775  1349  1349 D PanProfile: Bluetooth service disconnected
09-09 14:51:41.775  1349  1349 D BluetoothMap: Proxy object disconnected
09-09 14:51:41.775  1349  1349 D MapProfile: Bluetooth service disconnected
09-09 14:51:41.775   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:41.775  1349  2121 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:41.776   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:51:41.776  1974  2130 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:41.776  1349  2121 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:51:41.777  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:51:41.777   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:41.777   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:41.778  1349  1367 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:51:41.779  1349  2121 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:51:41.781  2701  2730 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 14:51:41.781  2701  2730 D BluetoothAdapterProperties: Setting state to 16
09-09 14:51:41.781  2701  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 14:51:41.782  2701  2730 D BluetoothAdapterProperties: onBleDisable
09-09 14:51:41.782  2701  2730 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:51:41.782  2701  2731 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 14:51:41.782  2701  2796 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 14:51:41.782  2701  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:41.783  3876  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 414)
09-09 14:51:41.783  2701  2,734 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:51:41.786  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.787  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.787  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.788  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.799   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:41.807  3946  3946 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 14:51:41.816   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:41.816   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 14:51:41.817   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:41.817  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:51:41.819   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:51:41.820  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.821  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:41.821  3447  3447 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6d49bf5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 14:51:41.827  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:51:41.831   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f93b63a:true
,09-09 14:51:41.839   872  2008 I ActivityManager: Start proc 3964:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 14:51:41.863   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-09 14:51:41.864   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 14:51:41.864  3946  3946 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 14:51:41.867  3946  3946 D BluetoothMap: Create BluetoothMap proxy object
,09-09 14:51:41.871  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 14:51:41.875  3946  3946 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 14:51:41.892  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:51:41.894   872  2095 I ActivityManager: Killing 3447:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 14:51:41.985  2701  2734 I bt_hci  : shut_down
,09-09 14:51:41.985  2701  2740 D bt_hwcfg: hw_epilog_process
,09-09 14:51:41.997  2701  2740 I bt_vendor: low_power_mode_cb,
,09-09 14:51:42.025  2701  2740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 14:51:42.025  2701  2740 I bt_vendor: epilog_cb
,09-09 14:51:42.025  2701  2740 I bt_hci  : epilog_finished_callback
,09-09 14:51:42.032  2701  2734 I bt_hci_h4: hal_close
,09-09 14:51:42.032  2701  2734 I bt_userial_vendor: device fd = 51 close
,09-09 14:51:42.064  3964  3964 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:51:42.064  3964  3964 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:51:42.064  3964  3964 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:51:42.064  3964  3964 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.064  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:51:42.065  3964  3964 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:51:42.065  3964  3964 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:51:42.065  3964  3964 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:51:42.065  3964  3964 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:51:42.065  3964  3964 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:51:42.106   872  1481 I ActivityManager: Start proc 3996:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 14:51:42.108   872  1481 I ActivityManager: Killing 3649:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 14:51:42.156  2701  2731 D bt_stack_manager: event_shut_down_stack finished.
,09-09 14:51:42.156  2701  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-09 14:51:42.161  2701  2701 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:51:42.161  2701  2730 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 14:51:42.161  2701  2701 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:51:42.161  2701  2701 D BtGatt.GattService: stop()
09-09 14:51:42.162  2701  2701 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 14:51:42.163  2701  2701 V BluetoothAdapterState: isTurningOff()=false
09-09 14:51:42.163  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:42.163  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:42.163  2701  2701 V BluetoothAdapterState: isBleTurningOff()=true
09-09 14:51:42.163  2701  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 14:51:42.163  2701  2730 D BluetoothAdapterProperties: Setting state to 10
09-09 14:51:42.163  2701  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 14:51:42.164  2701  2730 I BluetoothAdapterState: Entering OffState
09-09 14:51:42.166   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-09 14:51:42.172  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:51:42.178  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 14:51:42.178  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 14:51:42.178  2701  2701 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 14:51:42.179  2701  2731 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 14:51:42.181  2701  2731 D bt_stack_manager: event_clean_up_stack finished.
,09-09 14:51:42.195  2701  2701 I art     : System.exit called, status: 0
,09-09 14:51:42.195  2701  2701 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 14:51:42.199  3996  3996 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 14:51:42.260   872   883 I ActivityManager: Process com.android.bluetooth (pid 2701) has died
,09-09 14:51:42.306  3996  3996 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 14:51:42.327  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:51:42.358   872  2095 I ActivityManager: Start proc 4024:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-09 14:51:42.360  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:51:42.372  3964  3992 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 14:51:42.428   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442d99a:true
,09-09 14:51:42.437  4024  4024 D AdapterServiceConfig: Adding HeadsetService
09-09 14:51:42.437  4024  4024 D AdapterServiceConfig: Adding A2dpService
,09-09 14:51:42.437  4024  4024 D AdapterServiceConfig: Adding HidService
09-09 14:51:42.437  4024  4024 D AdapterServiceConfig: Adding HealthService
,09-09 14:51:42.438  4024  4024 D AdapterServiceConfig: Adding PanService
09-09 14:51:42.438  4024  4024 D AdapterServiceConfig: Adding GattService
09-09 14:51:42.439  4024  4024 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 14:51:42.442   872  2008 I ActivityManager: Killing 3686:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-09 14:51:42.496  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:51:42.518  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:51:42.523  1705  1705 D SystemUpdateService: onCreate
,09-09 14:51:42.526  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:51:42.529  1705  4036 I SystemUpdateService: active receiver: enabled
,09-09 14:51:42.531  1705  4036 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:51:42.533  1705  4036 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 14:51:42.533  1705  4036 I SystemUpdateService: now status is 0 (complete)
,09-09 14:51:42.533  1705  4036 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 14:51:42.533  1705  4036 I SystemUpdateService: file has been verified
,09-09 14:51:42.533  1705  4036 I SystemUpdateService: OTA package size = 12249756
,09-09 14:51:42.537  1705  4036 I SystemUpdateService: showing system update notification
,09-09 14:51:42.548  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 14:51:42.550  1705  2410 I iu.UploadsManager: num queued entries: 0
,09-09 14:51:42.551  1705  2410 I iu.UploadsManager: num updated entries: 0
,09-09 14:51:42.553  1705  2410 I iu.SyncManager: NEXT; no task
,09-09 14:51:42.561  1705  1705 D SystemUpdateService: onDestroy
,09-09 14:51:42.566  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:51:42.567  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:51:42.584   872   883 I ActivityManager: Start proc 4038:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 14:51:42.622  4038  4038 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 14:51:42.625  4038  4038 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:42.632  4038  4038 D SprintDMHelper: simOperator: 
09-09 14:51:42.632  4038  4038 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:51:42.662   872  1944 I ActivityManager: Start proc 4050:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 14:51:42.663   872  1944 I ActivityManager: Killing 3528:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 14:51:42.809   872  2097 I ActivityManager: Start proc 4065:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 14:51:42.811  2760  4064 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 14:51:42.816   872  2095 I ActivityManager: Killing 3579:android.process.acore/u0a5 (adj 15): empty #17
,09-09 14:51:42.894  4065  4065 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 14:51:42.955  4065  4065 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 14:51:42.955  4065  4065 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 14:51:42.955  4065  4065 I GAv4    :   adb logcat -s GAv4
,09-09 14:51:42.970  4065  4065 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:51:42.975  4065  4065 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:51:43.001  4065  4082 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:51:43.107  4065  4065 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 14:51:43.146  4065  4065 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 14:51:43.156  4065  4065 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4669-4675)
,09-09 14:51:43.156  4065  4065 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 14:51:43.173  4065  4065 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d36d306}
,09-09 14:51:43.173  4065  4065 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:51:43.174  4065  4065 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 14:51:43.183  4065  4065 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 14:51:43.185  4065  4065 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 14:51:43.199  4065  4065 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 14:51:43.215  4065  4065 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 14:51:43.215  4065  4065 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:51:43.215  4065  4065 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
,09-09 14:51:43.215  4065  4065 I Adreno  : Build Date                       : 10/20/15
09-09 14:51:43.215  4065  4065 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 14:51:43.215  4065  4065 I Adreno  : Local Branch                     : M14
09-09 14:51:43.215  4065  4065 I Adreno  : Remote Branch                    : 
09-09 14:51:43.215  4065  4065 I Adreno  : Remote Branch                    : 
09-09 14:51:43.215  4065  4065 I Adreno  : Reconstruct Branch               : 
,09-09 14:51:43.274  4065  4065 I NSApplication: Starting up...
,09-09 14:51:43.287  4065  4114 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 14:51:43.325   872  2019 I ActivityManager: Start proc 4119:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 14:51:43.329   872  2019 I ActivityManager: Killing 3760:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 14:51:43.392  4119  4119 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 14:51:43.569   872   882 I ActivityManager: Killing 3777:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 14:51:44.721   872  1986 D WifiService: setWifiEnabled: true pid=3876, uid=10000
,09-09 14:51:44.721   872  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:51:44.734   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-09 14:51:44.741  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:44.741  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:44.741  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:44.742  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:44.745  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:44.746  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:44.746  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:44.746  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:51:44.785   872  1306 D WifiConfigStore: loaded 0 passpoint configs
09-09 14:51:44.786   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 14:51:44.788   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 14:51:44.790   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:51:44.791   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 14:51:44.791   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 14:51:44.791   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 14:51:44.810   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.12 rxSuccessRate=14.75 delta 1000 -> 994
,09-09 14:51:44.810   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 14:51:44.813   372   871 D CommandListener: Setting iface cfg
,09-09 14:51:44.818   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 14:51:44.819   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 14:51:44.819   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 14:51:44.819   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:51:44.827   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 14:51:44.862   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 14:51:44.863   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 14:51:44.898   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 14:51:44.903  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 14:51:45.345  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:51:45.402  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 14:51:45.404  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 14:51:45.416   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:51:45.423   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:51:45.423   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:51:45.424   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 14:51:45.440   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:51:45.453   372   871 D CommandListener: Setting iface cfg
,09-09 14:51:45.453   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 14:51:45.466   872  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 14:51:45.467   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 14:51:45.510   872  4142 D DhcpClient: Receive thread started
,09-09 14:51:45.596   872  1306 E native  : do suspend false
,09-09 14:51:45.616   872  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 14:51:45.632   872  4142 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,09-09 14:51:45.633   872  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,09-09 14:51:45.637   872  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 14:51:45.656   872  4142 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 14:51:45.658   872  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 14:51:45.663   372   871 D CommandListener: Setting iface cfg
,09-09 14:51:45.674   872  1862 D DhcpClient: Scheduling renewal in 86399s
,09-09 14:51:45.676   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 14:51:45.698   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 14:51:45.701   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-09 14:51:45.701   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:45.702   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 14:51:45.705   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 14:51:45.720   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 14:51:45.753   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:51:45.753   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 14:51:45.754   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 14:51:45.755   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 14:51:45.756   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 14:51:45.763   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:45.769   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 14:51:45.770   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:45.770   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:45.770   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 14:51:45.770   872  1308 D ConnectivityService:    accepting network in place of null
09-09 14:51:45.770   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:51:45.771   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:51:45.797   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:45.827   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:45.834   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:51:45.834   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:45.842   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:45.844   872   889 D Tethering: MasterInitialState.processMessage what=3
09-09 14:51:45.850  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:45.850  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:51:45.851  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:45.851  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:45.858  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:51:45.858  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:51:45.858  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:45.858  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:51:45.875  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:51:45.878  1705  1705 D SystemUpdateService: onCreate
,09-09 14:51:45.883  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:51:45.885  1705  4153 I SystemUpdateService: active receiver: enabled
,09-09 14:51:45.889  1705  4153 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:51:45.891  1705  4153 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 14:51:45.891  1705  4153 I SystemUpdateService: now status is 0 (complete)
,09-09 14:51:45.891  1705  4153 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 14:51:45.892  1705  4153 I SystemUpdateService: file has been verified
,09-09 14:51:45.892  1705  4153 I SystemUpdateService: OTA package size = 12249756
,09-09 14:51:45.898  1705  4153 I SystemUpdateService: showing system update notification
,09-09 14:51:45.902  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 14:51:45.903  1705  2410 I iu.UploadsManager: num queued entries: 0
,09-09 14:51:45.904  1705  2410 I iu.UploadsManager: num updated entries: 0
,09-09 14:51:45.905  1705  2410 I iu.SyncManager: NEXT; no task
,09-09 14:51:45.908  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:51:45.910  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:51:45.910  1705  4156 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 14:51:45.910  1705  4156 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 14:51:45.912  1705  4156 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
09-09 14:51:45.913  4038  4038 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:45.917  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:45.919  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:45.921  4038  4038 D SprintDMHelper: simOperator: 
,09-09 14:51:45.921  4038  4038 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:51:45.930   872   884 I ActivityManager: Start proc 4158:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-09 14:51:45.932  1705  1705 D SystemUpdateService: onDestroy
,09-09 14:51:45.968  1510  2312 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 14:51:45.968  1510  2312 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 14:51:45.968  1510  2312 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:45.968  1510  2312 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:45.974  4158  4158 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-09 14:51:45.985  1705  4156 E MDM     : [173] SitrepService.a: Error sending sitrep.
,09-09 14:51:46.049  4158  4158 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 14:51:46.059  4158  4158 I BooksApp: Created application version: 3.6.9 (30609)
,09-09 14:51:46.093  1510  4086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 14:51:46.093  1510  4086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 14:51:46.093  1510  4086 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 14:51:46.093  1510  4086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:46.108  3635  4173 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 14:51:46.108  3635  4173 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jdm.a(PG:82)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jcs.o(PG:406),
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jcn.a(PG:1379)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jcs.i(PG:143)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at blb.a(PG:3937)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at czp.a(PG:18188)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at czp.a(PG:9081)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at czq.run(PG:1686)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:51:46.108  3635  4173 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jdj.a(PG:4091)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jdj.a(PG:1125)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jdm.a(PG:77)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	... 12 more
09-09 14:51:46.108  3635  4173 E HttpOperation: Caused by: faj: BadAuthentication
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at fal.a(PG:38)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	at jdj.a(PG:4089)
09-09 14:51:46.108  3635  4173 E HttpOperation: 	... 14 more
,09-09 14:51:46.141  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 14:51:46.141  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 14:51:46.141  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 14:51:46.141  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:46.155  3635  4173 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 14:51:46.155  3635  4173 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jdm.a(PG:82)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jcs.o(PG:406)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jcn.a(PG:1379)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jcs.i(PG:143)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at hec.a(PG:42)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at hee.a(PG:102)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at czr.a(PG:65)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at kka.a(PG:108)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at czp.a(PG:19176)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at czp.a(PG:9081)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at czq.run(PG:1686)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:51:46.155  3635  4173 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jdj.a(PG:4091)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jdj.a(PG:1125)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jdm.a(PG:77)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	... 15 more
09-09 14:51:46.155  3635  4173 E HttpOperation: Caused by: faj: BadAuthentication
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at fal.a(PG:38)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	at jdj.a(PG:4089)
09-09 14:51:46.155  3635  4173 E HttpOperation: 	... 17 more
,09-09 14:51:46.156  3635  4173 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 14:51:46.156  3635  4173 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at hec.a(PG:42)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at hee.a(PG:102)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at czr.a(PG:65)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at kka.a(PG:108)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	... 15 more
09-09 14:51:46.156  3635  4173 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at fal.a(PG:38)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 14:51:46.156  3635  4173 E ExperimentLoader: 	... 17 more
,09-09 14:51:46.184  4158  4181 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 14:51:46.243   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129469, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:51:46.328  4158  4188 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 14:51:46.405  1510  4086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 14:51:46.405  1510  4086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 14:51:46.405  1510  4086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:46.405  1510  4086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:46.471  1510  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 14:51:46.471  1510  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 14:51:46.471  1510  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:46.471  1510  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:46.494  4158  4188 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 14:51:46.496  4158  4181 E BooksSync: Soft error
09-09 14:51:46.496  4158  4181 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 14:51:46.496  4158  4181 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 14:51:46.496  4158  4181 E BooksSync: Sync error
09-09 14:51:46.496  4158  4181 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 14:51:46.496  4158  4181 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 14:51:46.496  4158  4181 I BooksSync: Finished books sync
,09-09 14:51:46.561   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:51:46.833   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 14:51:47.456   872  1481 I ActivityManager: Killing 2098:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 14:51:47.726   872  2096 D WifiService: setWifiEnabled: false pid=3876, uid=10000
,09-09 14:51:47.726   872  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:51:47.754  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 14:51:47.756   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 14:51:47.756   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 14:51:47.756   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:51:47.756   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:51:47.774   872  1862 D DhcpClient: Clearing IP address
,09-09 14:51:47.774   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-09 14:51:47.777   372   871 D CommandListener: Setting iface cfg
,09-09 14:51:47.785   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 14:51:47.785   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 14:51:47.790   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 14:51:47.792   412   412 E Parcel  : Reading a NULL string not supported here.
09-09 14:51:47.793   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:51:47.799   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-09 14:51:47.802   872  4142 D DhcpClient: Receive thread stopped
09-09 14:51:47.808   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 14:51:47.809   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:51:47.811   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 14:51:47.817  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:47.818  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:47.818  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:47.818  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:47.819  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:47.819  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:47.819  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:47.819  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:47.819  1861  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:51:47.861   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:47.880   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:51:47.880   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 14:51:47.881   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:47.883   872   889 D Tethering: MasterInitialState.processMessage what=3,
,09-09 14:51:47.886  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:47.887  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:47.895  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:51:47.899  1705  1705 D SystemUpdateService: onCreate
,09-09 14:51:47.901  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:51:47.912  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 14:51:47.924  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:51:47.925  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:51:47.927  1705  4199 I SystemUpdateService: active receiver: enabled
09-09 14:51:47.928  4038  4038 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:51:47.933  4038  4038 D SprintDMHelper: simOperator: 
,09-09 14:51:47.933  4038  4038 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:51:47.944  1705  2410 I iu.UploadsManager: num queued entries: 0
,09-09 14:51:47.951  1705  2410 I iu.UploadsManager: num updated entries: 0
,09-09 14:51:47.958  1705  4199 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:51:47.978  1705  4199 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 14:51:47.978  1705  4199 I SystemUpdateService: now status is 0 (complete)
,09-09 14:51:47.978  1705  4199 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 14:51:47.978  1705  4199 I SystemUpdateService: file has been verified
09-09 14:51:47.978  1705  4199 I SystemUpdateService: OTA package size = 12249756
,09-09 14:51:47.973  1705  2410 I iu.SyncManager: NEXT; no task
,09-09 14:51:47.988  4065  4065 I art     : Waiting for a blocking GC DisableMovingGc
,09-09 14:51:47.991  4065  4065 I art     : Starting a blocking GC DisableMovingGc
,09-09 14:51:47.997   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-09 14:51:47.998   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 14:51:48.024  1705  4199 I SystemUpdateService: showing system update notification
,09-09 14:51:48.031  1705  1705 D SystemUpdateService: onDestroy
,09-09 14:51:50.778   872  4140 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-09 14:51:50.779   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 14:51:50.784   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a1a996:true
,09-09 14:51:50.784  4024  4024 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 14:51:50.788  4024  4024 I bt_bluedroid: init
09-09 14:51:50.789  4024  4205 I BluetoothAdapterState: Entering OffState
,09-09 14:51:50.791  4024  4206 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 14:51:50.791  4024  4206 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 14:51:50.791  4024  4206 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 14:51:50.791  4024  4206 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:51:50.792  4024  4024 I bt_bluedroid: get_profile_interface socket
,09-09 14:51:50.794  4024  4024 I bt_bluedroid: get_profile_interface sdp
,09-09 14:51:50.798  4024  4035 I bt_bluedroid: config_hci_snoop_log
,09-09 14:51:50.800  4024  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 14:51:50.801  4024  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:51:50.802   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 14:51:50.809  4024  4205 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 14:51:50.809  4024  4205 D BluetoothAdapterProperties: Setting state to 14
09-09 14:51:50.809  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 14:51:50.812  4024  4205 D BluetoothBondStateMachine: make
,09-09 14:51:50.815  4024  4210 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 14:51:50.820  4024  4024 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 14:51:50.820  4024  4205 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:51:50.824  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:50.825  4024  4024 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:51:50.826  4024  4024 D BtGatt.GattService: Received start request. Starting profile...
09-09 14:51:50.826  4024  4024 D BtGatt.GattService: start()
,09-09 14:51:50.826  4024  4024 I bt_bluedroid: get_profile_interface gatt
,09-09 14:51:50.828  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
09-09 14:51:50.828  4024  4024 D BtGatt.AdvertiseManager: advertise manager created
,09-09 14:51:50.834  4024  4024 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:51:50.835  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:50.835  4024  4024 V BluetoothAdapterState: isBleTurningOn()=true
09-09 14:51:50.835  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:50.836  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 14:51:50.836  4024  4205 I bt_bluedroid: enable
,09-09 14:51:50.836  4024  4206 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 14:51:50.837  4024  4206 I bt_hci  : start_up
,09-09 14:51:50.844  4024  4206 I bt_vendor: alloc value 0xb3a45189
,09-09 14:51:50.844  4024  4206 I bt_vendor: init
09-09 14:51:50.844  4024  4206 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 14:51:50.844  4024  4206 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 14:51:50.954  4024  4206 D bt_hci  : start_up starting async portion
,09-09 14:51:50.955  4024  4213 I bt_hci  : event_finish_startup
,09-09 14:51:50.955  4024  4213 I bt_hci_h4: hal_open
09-09 14:51:50.956  4024  4213 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 14:51:50.969  4024  4213 I bt_userial_vendor: device fd = 51 open
09-09 14:51:50.969  2760  4170 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-09 14:51:50.969  2760  4170 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-09 14:51:50.971  2760  4170 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 14:51:50.995  4024  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:51:51.026  4024  4213 D bt_hwcfg: Chipset BCM4354A2
,09-09 14:51:51.027  4024  4213 D bt_hwcfg: Target name = [BCM4354A2]
09-09 14:51:51.027  4024  4213 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 14:51:51.080  4158  4179 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 14:51:51.195  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:51.232  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:51.236  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:51.274  1510  4086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 14:51:51.274  1510  4086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 14:51:51.274  1510  4086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:51.274  1510  4086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:51.304  3596  3596 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 14:51:51.305  3596  3596 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 14:51:51.306  3596  3596 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 14:51:51.526  4024  4213 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 14:51:51.527  4024  4213 D bt_hwcfg: Settlement delay -- 100 ms
09-09 14:51:51.527  4024  4213 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 14:51:51.644  4024  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:51:51.645  4024  4213 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 14:51:51.675  4024  4213 I bt_hwcfg: vendor lib fwcfg completed
,09-09 14:51:51.675  4024  4213 I bt_vendor: firmware callback
09-09 14:51:51.675  4024  4213 I bt_hci  : firmware_config_callback
,09-09 14:51:51.687  4024  4218 I bt_btu  : btu_task pending for preload complete event
,09-09 14:51:51.687  4024  4218 I bt_btu_task: Bluetooth chip preload is complete
09-09 14:51:51.688  4024  4218 I bt_btu  : btu_task received preload complete event
,09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 14:51:51.696  4024  4218 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:51:51.697  4024  4218 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 14:51:51.831  4024  4218 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c2d9d
,09-09 14:51:51.832  4024  4218 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c2d9d 
,09-09 14:51:51.842  4024  4209 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 14:51:51.843  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 14:51:51.844  4024  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:51:51.854  4024  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:51:51.857  4024  4209 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:51:51.857  4024  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 14:51:51.861  4024  4209 D bt_hci  : do_postload posting postload work item
,09-09 14:51:51.861  4024  4213 I bt_hci  : event_postload
09-09 14:51:51.862  4024  4213 I bt_vendor: sco_config_cb,
,09-09 14:51:51.862  4024  4213 I bt_hci  : sco_config_callback postload finished.
09-09 14:51:51.864  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:51.868  4024  4213 I bt_vendor: low_power_mode_cb
09-09 14:51:51.867  4024  4209 D bt_bte_conf: Device ID record 1 : primary
,09-09 14:51:51.868  4024  4209 D bt_bte_conf:   vendorId            = 000f
,09-09 14:51:51.868  4024  4209 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 14:51:51.869  4024  4209 D bt_bte_conf:   product             = 1200
,09-09 14:51:51.869  4024  4209 D bt_bte_conf:   version             = 1436
09-09 14:51:51.869  4024  4209 D bt_bte_conf:   clientExecutableURL = 
09-09 14:51:51.869  4024  4209 D bt_bte_conf:   serviceDescription  = ,
09-09 14:51:51.869  4024  4209 D bt_bte_conf:   documentationURL    = 
09-09 14:51:51.869  4024  4209 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 14:51:51.869  4024  4206 D bt_stack_manager: event_start_up_stack finished
09-09 14:51:51.870  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 14:51:51.870  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:51.870  4024  4205 D BluetoothAdapterProperties: Setting state to 15
09-09 14:51:51.870  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 14:51:51.871  4024  4205 I BluetoothAdapterState: Entering BleOnState
09-09 14:51:51.875  4024  4205 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 14:51:51.876  4024  4205 D BluetoothAdapterProperties: Setting state to 11
09-09 14:51:51.876  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 14:51:51.883  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:51.885  4024  4024 D HeadsetService: Received start request. Starting profile...
,09-09 14:51:51.889  4024  4024 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:51:51.889  4024  4024 D HeadsetStateMachine: make
,09-09 14:51:51.890  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:51.893  4024  4205 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:51:51.894  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 14:51:51.901  4024  4024 D HeadsetStateMachine: max_hf_connections = 1
,09-09 14:51:51.901  4024  4024 I bt_bluedroid: get_profile_interface handsfree
,09-09 14:51:51.903  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 14:51:51.904  4024  4209 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 14:51:51.906  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:51.907  4024  4024 D A2dpService: Received start request. Starting profile...
09-09 14:51:51.907  4024  4024 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 14:51:51.908  4024  4024 I bt_bluedroid: get_profile_interface avrcp
,09-09 14:51:51.915  4024  4024 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 14:51:51.915  4024  4024 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:51:51.915  4024  4024 D A2dpStateMachine: make,
,09-09 14:51:51.917  4024  4024 I bt_bluedroid: get_profile_interface a2dp
,09-09 14:51:51.920  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 14:51:51.920  4024  4228 D A2dpStateMachine: Enter Disconnected: -2
09-09 14:51:51.921  4024  4024 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 14:51:51.923  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:51.924  4024  4024 D HidService: Received start request. Starting profile...,
09-09 14:51:51.924  4024  4024 I bt_bluedroid: get_profile_interface hidhost
,09-09 14:51:51.924  3946  3946 D BluetoothInputDevice: Proxy object connected
09-09 14:51:51.924  4024  4209 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a43e5
09-09 14:51:51.924  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 14:51:51.924  4024  4024 D HidService: setHidService(): set to: null
09-09 14:51:51.925  4024  4024 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:51:51.925  3946  3946 D HidProfile: Bluetooth service connected
,09-09 14:51:51.926  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
09-09 14:51:51.926  4024  4024 D HealthService: Received start request. Starting profile...
,09-09 14:51:51.927  4024  4024 I bt_bluedroid: get_profile_interface health
,09-09 14:51:51.928  4024  4024 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 14:51:51.929  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:51:51.930  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:51:51.930  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:51:51.931  4024  4024 D PanService: Received start request. Starting profile...
,09-09 14:51:51.931  4024  4024 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:51:51.931  3946  3946 D PanProfile: Bluetooth service connected
,09-09 14:51:51.931  4024  4024 I bt_bluedroid: get_profile_interface pan
09-09 14:51:51.932  4024  4209 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 14:51:51.936  4024  4024 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
09-09 14:51:51.937  3946  3946 D BluetoothMap: Proxy object connected
,09-09 14:51:51.937  3946  3946 D MapProfile: Bluetooth service connected
,09-09 14:51:51.938  3946  3946 D BluetoothMap: getConnectedDevices()
09-09 14:51:51.938  4024  4024 D BluetoothMapService: Received start request. Starting profile...
09-09 14:51:51.938  4024  4024 D BluetoothMapService: start()
09-09 14:51:51.938  3946  3946 D BluetoothMap: Bluetooth is Not enabled
09-09 14:51:51.941  4024  4024 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 14:51:51.941  4024  4024 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 14:51:51.941  4024  4024 D BluetoothMapAppObserver: createReceiver()
09-09 14:51:51.942  4024  4024 D BluetoothMapAppObserver: initObservers()
,09-09 14:51:51.943  4024  4024 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 14:51:51.949  4024  4024 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:51:51.950  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.950  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.950  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:51.950  4024  4225 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isTurningOff()=false
09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isTurningOff()=false
09-09 14:51:51.951  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isTurningOff()=false
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.952  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:51.953  4024  4024 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:51:51.953  4024  4024 V BluetoothAdapterState: isTurningOn()=true
09-09 14:51:51.953  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:51.953  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:51.953  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 14:51:51.953  4024  4205 D BluetoothAdapterProperties: ScanMode =  20
,09-09 14:51:51.953  4024  4205 D BluetoothAdapterProperties: State =  11
09-09 14:51:51.954  4024  4205 D BluetoothAdapterProperties: Setting state to 12
09-09 14:51:51.954  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:51:51.954  3946  3958 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:51:51.954  4024  4205 I BluetoothAdapterState: Entering OnState
09-09 14:51:51.955  1349  2121 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 14:51:51.957  4024  4209 D BluetoothAdapterProperties: Scan Mode:21
,09-09 14:51:51.957  1349  1349 D BluetoothInputDevice: Proxy object connected
09-09 14:51:51.958  4024  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:51:51.958  1349  1349 D HidProfile: Bluetooth service connected
09-09 14:51:51.959   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:51:51.959  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:51:51.960   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:51.961  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:51:51.961  1974  1985 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:51:51.961  3946  3956 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:51:51.962   872   872 D BluetoothA2dp: Proxy object connected
09-09 14:51:51.962  1349  2121 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:51:51.963  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:51:51.964  1349  1349 D BluetoothMap: Proxy object connected
,09-09 14:51:51.964  1349  1349 D MapProfile: Bluetooth service connected
09-09 14:51:51.965  1349  1349 D BluetoothMap: getConnectedDevices()
,09-09 14:51:51.966  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:51.967  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:51:51.968  1349  1349 D BluetoothA2dp: Proxy object connected
,09-09 14:51:51.969  4024  4024 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 14:51:51.969  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:51.969  3946  3958 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:51:51.969   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:51:51.970  4024  4024 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 14:51:51.970   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:51:51.970  1349  2121 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:51:51.971  4024  4024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:51:51.972  1349  1367 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:51:51.973  4024  4024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:51:51.974  4024  4024 D ObexServerSockets: Succeed to create listening sockets 
09-09 14:51:51.974  4024  4024 D ObexServerSockets0: startAccept()
09-09 14:51:51.974  4024  4024 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:51:51.974  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:51:51.974  1349  1349 D PanProfile: Bluetooth service connected
,09-09 14:51:51.975  3946  3956 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:51:51.976  4024  4024 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 14:51:51.976  4024  4024 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 14:51:51.978   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 14:51:51.978  4024  4233 D ObexServerSockets0: Accepting socket connection...
,09-09 14:51:51.978  4024  4234 D ObexServerSockets0: Accepting socket connection...
,09-09 14:51:51.980  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:51.980  4024  4024 D BluetoothMapService: onReceive
,09-09 14:51:51.980  4024  4024 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:51:51.980  4024  4024 D BluetoothMapService: STATE_ON
09-09 14:51:51.981  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:51.981  3946  3946 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 14:51:51.985  3946  3946 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 14:51:51.991  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:51:51.993  3946  3946 D BluetoothA2dp: Proxy object connected
,09-09 14:51:51.998  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:51:51.999  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:51:52.008  3946  3946 D BluetoothPbap: Proxy object connected
,09-09 14:51:52.008  1349  1349 D BluetoothPbap: Proxy object connected
09-09 14:51:52.008  1349  1349 D PbapServerProfile: Bluetooth service connected
09-09 14:51:52.008  3946  3946 D PbapServerProfile: Bluetooth service connected
,09-09 14:51:52.009  4024  4024 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 14:51:52.009  4024  4024 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:51:52.022  4024  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:51:52.045  4024  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:51:52.047  4024  4243 I BtOppRfcommListener: Accept thread started.
,09-09 14:51:52.061   872   872 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.061  1974  2130 D BluetoothHeadset: Proxy object connected
09-09 14:51:52.062  1974  1987 D BluetoothHeadset: Proxy object connected
09-09 14:51:52.062   872   872 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.062  1349  1360 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.062   872   872 D BluetoothHeadset: Proxy object connected
09-09 14:51:52.063  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-09 14:51:52.069   872   889 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.070   872   889 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.088  3946  3956 D BluetoothHeadset: Proxy object connected
,09-09 14:51:52.089  3946  3946 D HeadsetProfile: Bluetooth service connected
,09-09 14:51:53.742  4024  4205 D BluetoothAdapterState: Current state: ON, message: 23
09-09 14:51:53.742  4024  4205 D BluetoothAdapterProperties: Setting state to 13
,09-09 14:51:53.743  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 14:51:53.745  4024  4205 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:51:53.747  4024  4205 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:51:53.758  4024  4024 D BluetoothMapService: onReceive
09-09 14:51:53.758  4024  4024 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:51:53.759  4024  4024 D BluetoothMapService: STATE_TURNING_OFF
,09-09 14:51:53.760  4024  4024 D BluetoothMapService: MAP Service closeService in
09-09 14:51:53.760  4024  4024 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 14:51:53.760  4024  4024 D ObexServerSockets0: shutdown(block = true)
09-09 14:51:53.760  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:53.761  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:51:53.762  4024  4233 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 14:51:53.763  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:53.763  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:53.763  4024  4209 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:51:53.766  4024  4024 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:51:53.766  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 14:51:53.766  4024  4234 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-09 14:51:53.768  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:51:53.768  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:51:53.769  4024  4220 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 14:51:53.770  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:51:53.771  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:51:53.771  4024  4024 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:51:53.771  4024  4024 I BtOppRfcommListener: stopping Accept Thread
,09-09 14:51:53.772  4024  4243 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:51:53.772   872  1308 D ConnectivityService: handlePromptUnvalidated 101
09-09 14:51:53.772  4024  4243 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:51:53.776  4024  4024 D HeadsetService: Received stop request...Stopping profile...
09-09 14:51:53.776  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:53.778  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:51:53.778   872   872 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:53.779  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 14:51:53.779  1974  1985 D BluetoothHeadset: Proxy object disconnected
09-09 14:51:53.779   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 14:51:53.779  4024  4024 D A2dpService: Received stop request...Stopping profile...
09-09 14:51:53.779  1349  1360 D BluetoothHeadset: Proxy object disconnected
09-09 14:51:53.779  4024  4228 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:51:53.781  3946  3956 D BluetoothHeadset: Proxy object disconnected
,09-09 14:51:53.782   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 14:51:53.782   872   872 D BluetoothA2dp: Proxy object disconnected
09-09 14:51:53.784  3946  3946 D HeadsetProfile: Bluetooth service disconnected
09-09 14:51:53.784  4024  4024 D HidService: Received stop request...Stopping profile...
,09-09 14:51:53.785  4024  4024 D HidService: Stopping Bluetooth HidService
09-09 14:51:53.786  3946  3946 D BluetoothA2dp: Proxy object disconnected
09-09 14:51:53.786  4024  4024 D HealthService: Received stop request...Stopping profile...
,09-09 14:51:53.788  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-09 14:51:53.788  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-09 14:51:53.788  1349  1349 D BluetoothInputDevice: Proxy object disconnected
09-09 14:51:53.788  1349  1349 D HidProfile: Bluetooth service disconnected
09-09 14:51:53.789  4024  4024 D PanService: Received stop request...Stopping profile...
,09-09 14:51:53.790  4024  4024 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:53.790  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:53.790  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:53.790  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:53.791  4024  4024 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:51:53.791  4024  4024 D BluetoothMapService: stop()
09-09 14:51:53.791  3946  3946 D DockEventReceiver: finishStartingService: stopping service
09-09 14:51:53.792  4024  4024 D BluetoothMapAppObserver: deinitObservers()
,09-09 14:51:53.792  4024  4024 D BluetoothMapAppObserver: removeReceiver()
09-09 14:51:53.793  3946  3946 D BluetoothInputDevice: Proxy object disconnected
,09-09 14:51:53.794  3946  3946 D HidProfile: Bluetooth service disconnected
09-09 14:51:53.794  4024  4024 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:51:53.795  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-09 14:51:53.795  4024  4024 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 14:51:53.795  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:53.795  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:51:53.795  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:53.795  4024  4209 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 14:51:53.795  3946  3946 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:51:53.796  3946  3946 D PanProfile: Bluetooth service disconnected
09-09 14:51:53.796  3946  3946 D BluetoothMap: Proxy object disconnected
,09-09 14:51:53.797  3946  3946 D MapProfile: Bluetooth service disconnected
09-09 14:51:53.797  4024  4024 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:53.797  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:53.797  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:53.797  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:51:53.800  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:53.800  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:51:53.800  4024  4218 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:51:53.800  4024  4218 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 14:51:53.800  4024  4218 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:51:53.800  4024  4218 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:51:53.800  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 14:51:53.805  4024  4024 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:51:53.806  4024  4024 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:51:53.806  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:53.806  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:53.806  4024  4024 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:51:53.806  4024  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:51:53.806  4024  4024 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:51:53.806  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:51:53.806  4024  4024 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:51:53.806  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:53.807  4024  4024 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:51:53.807  4024  4209 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 14:51:53.807  4024  4024 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:51:53.807  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:53.808  4024  4024 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:51:53.808  4024  4024 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:51:53.808  4024  4024 D BluetoothMapService: MAP Service closeService in
,09-09 14:51:53.809  4024  4024 V BluetoothAdapterState: isTurningOff()=true
09-09 14:51:53.809  4024  4024 V BluetoothAdapterState: isTurningOn()=false
09-09 14:51:53.809  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:53.809  4024  4024 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:51:53.809  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 14:51:53.809  4024  4205 D BluetoothAdapterProperties: Setting state to 15
09-09 14:51:53.809  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 14:51:53.809  4024  4205 I BluetoothAdapterState: Entering BleOnState
,09-09 14:51:53.810  3946  3956 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:51:53.810  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:51:53.810  1349  1349 D PanProfile: Bluetooth service disconnected
09-09 14:51:53.810  1349  1349 D BluetoothMap: Proxy object disconnected
09-09 14:51:53.810  1349  1349 D MapProfile: Bluetooth service disconnected
09-09 14:51:53.810  3946  3958 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.811  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:51:53.811  4024  4024 D BluetoothMapService: cleanup()
,09-09 14:51:53.811  4024  4024 D BluetoothMapService: MAP Service closeService in
09-09 14:51:53.812   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.812  1349  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.812   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:51:53.812  3946  3946 D BluetoothPbap: Proxy object disconnected
09-09 14:51:53.813  3946  3946 D PbapServerProfile: Bluetooth service disconnected
09-09 14:51:53.813  1974  2130 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.813  1349  1349 D BluetoothPbap: Proxy object disconnected
09-09 14:51:53.813  1349  1349 D PbapServerProfile: Bluetooth service disconnected
09-09 14:51:53.813  3946  3958 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:51:53.815  1349  1367 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:51:53.818  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 14:51:53.819  3946  4246 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:51:53.820  3946  3956 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 14:51:53.820   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.820   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:51:53.820  1349  2121 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 14:51:53.823  1349  1367 D BluetoothPan: onBluetoothStateChange on: false
,09-09 14:51:53.823  3946  3958 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 14:51:53.824  4024  4205 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-09 14:51:53.824  4024  4205 D BluetoothAdapterProperties: Setting state to 16
09-09 14:51:53.824  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 14:51:53.825  4024  4205 D BluetoothAdapterProperties: onBleDisable
09-09 14:51:53.825  4024  4205 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:51:53.825  4024  4206 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 14:51:53.826  4024  4218 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 14:51:53.826  4024  4218 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:51:53.829  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:53.830  4024  4209 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:51:53.831  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:53.833  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:53.833  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:51:53.834  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:53.841  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:51:53.844  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:51:54.034  4024  4209 I bt_hci  : shut_down
,09-09 14:51:54.036  4024  4213 D bt_hwcfg: hw_epilog_process
,09-09 14:51:54.038  4024  4213 I bt_vendor: low_power_mode_cb
,09-09 14:51:54.068  4024  4213 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 14:51:54.068  4024  4213 I bt_vendor: epilog_cb
09-09 14:51:54.069  4024  4213 I bt_hci  : epilog_finished_callback
,09-09 14:51:54.079  4024  4209 I bt_hci_h4: hal_close
,09-09 14:51:54.081  4024  4209 I bt_userial_vendor: device fd = 51 close
,09-09 14:51:54.218  4024  4206 D bt_stack_manager: event_shut_down_stack finished.
,09-09 14:51:54.219  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 14:51:54.224  4024  4024 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:51:54.224  4024  4205 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 14:51:54.226  4024  4024 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:51:54.226  4024  4024 D BtGatt.GattService: stop()
,09-09 14:51:54.226  4024  4024 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 14:51:54.230  4024  4024 V BluetoothAdapterState: isTurningOff()=false
09-09 14:51:54.231  4024  4024 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:51:54.231  4024  4024 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:51:54.231  4024  4024 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 14:51:54.232  4024  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 14:51:54.233  4024  4205 D BluetoothAdapterProperties: Setting state to 10
09-09 14:51:54.235  4024  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 14:51:54.238  4024  4205 I BluetoothAdapterState: Entering OffState
,09-09 14:51:54.238   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 14:51:54.257  4024  4024 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 14:51:54.258  4024  4024 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 14:51:54.258  4024  4206 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-09 14:51:54.258  4024  4024 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 14:51:54.262  4024  4206 D bt_stack_manager: event_clean_up_stack finished.
,09-09 14:51:54.265  4024  4024 I art     : System.exit called, status: 0
09-09 14:51:54.265  4024  4024 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 14:51:54.332   872  2015 I ActivityManager: Process com.android.bluetooth (pid 4024) has died
,09-09 14:51:56.110  3596  3607 D Finsky  : [289] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-09 14:51:56.128  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:51:56.183  1510  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 14:51:56.183  1510  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-09 14:51:56.184  1510  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:51:56.185  1510  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:51:56.228  3596  3607 D Finsky  : [289] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-09 14:51:56.740  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:51:56.740  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:51:58.818   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 14:51:58.832  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-09 14:51:58.842   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 14:51:58.842   872   892 I Adreno  : Build Date                       : 10/20/15
09-09 14:51:58.842   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 14:51:58.842   872   892 I Adreno  : Local Branch                     : M14
09-09 14:51:58.842   872   892 I Adreno  : Remote Branch                    : 
09-09 14:51:58.842   872   892 I Adreno  : Remote Branch                    : 
09-09 14:51:58.842   872   892 I Adreno  : Reconstruct Branch               : 
,09-09 14:51:58.894   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (378 us)
,09-09 14:51:59.529  3876  3876 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 14:51:59.529  3876  3876 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 14:51:59.565   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 14:51:59.567  3876  3876 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c073235 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@47b67e2, 16908290=android.view.AbsSavedState$1@47b67e2}, android:focusedViewId=100}]}]
,09-09 14:51:59.567  3876  3876 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 14:51:59.567  3876  3876 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 14:51:59.567  3876  3876 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 14:51:59.580   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 14:51:59.585   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 14:51:59.589   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-09 14:51:59.589   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 14:51:59.611   872   881 I art     : Background partial concurrent mark sweep GC freed 19610(1509KB) AllocSpace objects, 9(324KB) LOS objects, 33% free, 29MB/43MB, paused 1.201ms total 102.434ms
,09-09 14:51:59.747  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:51:59.747  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfe4773 added. We now have 6 listener(s)
09-09 14:51:59.748  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:51:59.751  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:51:59.752  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7fba630 added. We now have 7 listener(s)
,09-09 14:51:59.752  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:51:59.753  3876  3927 I System.out: IsBluetoothEnabled
,09-09 14:51:59.766  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:51:59.814   872   889 I ActivityManager: Start proc 4259:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 14:51:59.819   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 14:51:59.823   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 14:51:59.824   872  1329 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-09 14:51:59.830   872   892 I DreamManagerService: Entering dreamland.
,09-09 14:51:59.831   872   892 I PowerManagerService: Dozing...
09-09 14:51:59.832   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 14:51:59.869   376  1477 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 14:51:59.869   376  1477 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 14:51:59.874   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:51:59.880   872  1306 E native  : do suspend false
,09-09 14:51:59.890  1960  4272 D NfcService: Discovery configuration equal, not updating.
,09-09 14:51:59.910   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:51:59.913   872  1306 E native  : do suspend true
,09-09 14:51:59.925  4259  4259 D AdapterServiceConfig: Adding HeadsetService
,09-09 14:51:59.926  4259  4259 D AdapterServiceConfig: Adding A2dpService
,09-09 14:51:59.927  4259  4259 D AdapterServiceConfig: Adding HidService
,09-09 14:51:59.927  4259  4259 D AdapterServiceConfig: Adding HealthService
,09-09 14:51:59.928  4259  4259 D AdapterServiceConfig: Adding PanService
09-09 14:51:59.929  4259  4259 D AdapterServiceConfig: Adding GattService
,09-09 14:51:59.929  4259  4259 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 14:51:59.946   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d979af:true
,09-09 14:51:59.947  4259  4259 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 14:51:59.953  4259  4259 I bt_bluedroid: init
,09-09 14:51:59.953  4259  4274 I BluetoothAdapterState: Entering OffState
,09-09 14:51:59.961  4259  4275 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 14:51:59.961  4259  4275 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 14:51:59.961  4259  4275 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 14:51:59.962  4259  4275 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 14:51:59.965  4259  4259 I bt_bluedroid: get_profile_interface socket
09-09 14:51:59.970  4259  4259 I bt_bluedroid: get_profile_interface sdp
,09-09 14:51:59.971  4259  4278 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:51:59.974  4259  4278 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:52:00.007   376  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 14:52:00.007   376  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 14:52:00.016  4259  4270 I bt_bluedroid: config_hci_snoop_log
,09-09 14:52:00.021   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 14:52:00.038  4259  4274 D BluetoothAdapterState: Current state: OFF, message: 0
09-09 14:52:00.039  4259  4274 D BluetoothAdapterProperties: Setting state to 14
09-09 14:52:00.039  4259  4274 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 14:52:00.046  4259  4274 D BluetoothBondStateMachine: make
,09-09 14:52:00.054  4259  4279 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 14:52:00.057  4259  4274 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:52:00.060  4259  4259 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 14:52:00.066  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:00.068  4259  4259 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:52:00.070  4259  4259 D BtGatt.GattService: Received start request. Starting profile...
,09-09 14:52:00.071  4259  4259 D BtGatt.GattService: start()
,09-09 14:52:00.072  4259  4259 I bt_bluedroid: get_profile_interface gatt
,09-09 14:52:00.075  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:00.075  4259  4259 D BtGatt.AdvertiseManager: advertise manager created
,09-09 14:52:00.090  4259  4259 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:52:00.091  4259  4259 V BluetoothAdapterState: isTurningOn()=false
09-09 14:52:00.091  4259  4259 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 14:52:00.091  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:52:00.092  4259  4274 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 14:52:00.093  4259  4274 I bt_bluedroid: enable
09-09 14:52:00.093  4259  4275 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 14:52:00.094  4259  4275 I bt_hci  : start_up
,09-09 14:52:00.101  4259  4275 I bt_vendor: alloc value 0xb3a55189
09-09 14:52:00.101  4259  4275 I bt_vendor: init
,09-09 14:52:00.102  4259  4275 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 14:52:00.102  4259  4275 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 14:52:00.208  4259  4275 D bt_hci  : start_up starting async portion
,09-09 14:52:00.209  4259  4284 I bt_hci  : event_finish_startup
,09-09 14:52:00.209  4259  4284 I bt_hci_h4: hal_open
09-09 14:52:00.209  4259  4284 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 14:52:00.219  4259  4284 I bt_userial_vendor: device fd = 51 open
,09-09 14:52:00.251  4259  4284 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:52:00.283  4259  4284 D bt_hwcfg: Chipset BCM4354A2
,09-09 14:52:00.284  4259  4284 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 14:52:00.286  4259  4284 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 14:52:00.953  4259  4284 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 14:52:00.954  4259  4284 D bt_hwcfg: Settlement delay -- 100 ms
09-09 14:52:00.955  4259  4284 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 14:52:01.073  4259  4284 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:52:01.075  4259  4284 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 14:52:01.102  4259  4284 I bt_hwcfg: vendor lib fwcfg completed
,09-09 14:52:01.103  4259  4284 I bt_vendor: firmware callback
,09-09 14:52:01.103  4259  4284 I bt_hci  : firmware_config_callback
,09-09 14:52:01.114  4259  4288 I bt_btu  : btu_task pending for preload complete event
,09-09 14:52:01.114  4259  4288 I bt_btu_task: Bluetooth chip preload is complete
09-09 14:52:01.115  4259  4288 I bt_btu  : btu_task received preload complete event
,09-09 14:52:01.124  4259  4288 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:52:01.125  4259  4288 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:52:01.125  4259  4288 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:52:01.125  4259  4288 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 14:52:01.125  4259  4288 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:52:01.126  4259  4288 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:52:01.126  4259  4288 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 14:52:01.126  4259  4288 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:52:01.126  4259  4288 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 14:52:01.127  4259  4288 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 14:52:01.127  4259  4288 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:52:01.127  4259  4288 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 14:52:01.127  4259  4288 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 14:52:01.128  4259  4288 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:52:01.128  4259  4288 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 14:52:01.261  4259  4288 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d2d9d
,09-09 14:52:01.261  4259  4288 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d2d9d 
,09-09 14:52:01.273  4259  4278 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 14:52:01.275  4259  4278 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 14:52:01.275  4259  4278 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:52:01.278  4259  4278 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:52:01.281  4259  4278 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:52:01.282  4259  4278 D BluetoothAdapterProperties: Discoverable Timeout:120,
09-09 14:52:01.282  4259  4278 D bt_hci  : do_postload posting postload work item
09-09 14:52:01.283  4259  4284 I bt_hci  : event_postload
09-09 14:52:01.283  4259  4284 I bt_vendor: sco_config_cb
09-09 14:52:01.283  4259  4284 I bt_hci  : sco_config_callback postload finished.
,09-09 14:52:01.289  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:01.289  4259  4278 D bt_bte_conf: Device ID record 1 : primary
,09-09 14:52:01.289  4259  4278 D bt_bte_conf:   vendorId            = 000f
09-09 14:52:01.290  4259  4278 D bt_bte_conf:   vendorIdSource      = 0001
09-09 14:52:01.290  4259  4278 D bt_bte_conf:   product             = 1200
09-09 14:52:01.290  4259  4278 D bt_bte_conf:   version             = 1436
09-09 14:52:01.291  4259  4278 D bt_bte_conf:   clientExecutableURL = 
09-09 14:52:01.291  4259  4278 D bt_bte_conf:   serviceDescription  = 
,09-09 14:52:01.292  4259  4278 D bt_bte_conf:   documentationURL    = 
09-09 14:52:01.292  4259  4278 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 14:52:01.292  4259  4275 D bt_stack_manager: event_start_up_stack finished
09-09 14:52:01.294  4259  4274 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 14:52:01.295  4259  4274 D BluetoothAdapterProperties: Setting state to 15
09-09 14:52:01.295  4259  4274 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 14:52:01.296  4259  4284 I bt_vendor: low_power_mode_cb
09-09 14:52:01.297  4259  4274 I BluetoothAdapterState: Entering BleOnState
09-09 14:52:01.302  4259  4274 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 14:52:01.302  4259  4274 D BluetoothAdapterProperties: Setting state to 11
,09-09 14:52:01.303  4259  4274 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 14:52:01.315  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 14:52:01.319  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:01.320  4259  4259 D HeadsetService: Received start request. Starting profile...
09-09 14:52:01.325  4259  4259 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 14:52:01.325  4259  4259 D HeadsetStateMachine: make
,09-09 14:52:01.328  4259  4274 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:52:01.334  4259  4259 D HeadsetStateMachine: max_hf_connections = 1
,09-09 14:52:01.334  4259  4259 I bt_bluedroid: get_profile_interface handsfree
,09-09 14:52:01.335  4259  4278 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-09 14:52:01.335  4259  4278 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 14:52:01.339  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:01.339  4259  4259 D A2dpService: Received start request. Starting profile...
09-09 14:52:01.340  4259  4259 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:52:01.340  4259  4259 I bt_bluedroid: get_profile_interface avrcp
,09-09 14:52:01.346  4259  4259 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 14:52:01.347  4259  4259 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:52:01.347  4259  4259 D A2dpStateMachine: make
,09-09 14:52:01.348  4259  4259 I bt_bluedroid: get_profile_interface a2dp
,09-09 14:52:01.349  4259  4278 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 14:52:01.350  4259  4297 D A2dpStateMachine: Enter Disconnected: -2
,09-09 14:52:01.350  4259  4259 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 14:52:01.351  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
09-09 14:52:01.352  4259  4259 D HidService: Received start request. Starting profile...
,09-09 14:52:01.352  4259  4259 I bt_bluedroid: get_profile_interface hidhost
09-09 14:52:01.352  4259  4259 D HidService: setHidService(): set to: null
09-09 14:52:01.353  4259  4259 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 14:52:01.354  4259  4278 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b43e5
09-09 14:52:01.354  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:01.354  4259  4278 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 14:52:01.354  4259  4259 D HealthService: Received start request. Starting profile...
,09-09 14:52:01.356  4259  4259 I bt_bluedroid: get_profile_interface health
,09-09 14:52:01.358  4259  4259 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 14:52:01.359  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:52:01.359  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:01.360  4259  4259 D PanService: Received start request. Starting profile...
,09-09 14:52:01.360  4259  4259 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:52:01.360  4259  4259 I bt_bluedroid: get_profile_interface pan
09-09 14:52:01.360  4259  4278 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 14:52:01.362  4259  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
,09-09 14:52:01.363  4259  4259 D BluetoothMapService: Received start request. Starting profile...
09-09 14:52:01.363  4259  4259 D BluetoothMapService: start()
,09-09 14:52:01.365  4259  4259 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 14:52:01.366  4259  4259 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 14:52:01.366  4259  4259 D BluetoothMapAppObserver: createReceiver()
,09-09 14:52:01.367  4259  4259 D BluetoothMapAppObserver: initObservers()
09-09 14:52:01.368  4259  4259 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 14:52:01.376  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.376  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.376  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.376  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:52:01.378  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.378  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.378  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:52:01.379  4259  4295 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:52:01.379  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.380  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.380  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.380  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:52:01.381  4259  4259 V BluetoothAdapterState: isTurningOff()=false
09-09 14:52:01.382  4259  4259 V BluetoothAdapterState: isTurningOn()=true
09-09 14:52:01.382  4259  4259 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:52:01.382  4259  4259 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:52:01.383  4259  4274 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 14:52:01.383  4259  4274 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:52:01.383  4259  4274 D BluetoothAdapterProperties: State =  11
,09-09 14:52:01.383  4259  4274 D BluetoothAdapterProperties: Setting state to 12
09-09 14:52:01.383  4259  4274 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:52:01.384  4259  4278 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:52:01.384  3946  3958 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:52:01.384  4259  4278 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:52:01.384  4259  4274 I BluetoothAdapterState: Entering OnState
09-09 14:52:01.388  3946  3956 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:52:01.388  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:52:01.389  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected,
09-09 14:52:01.389  1349  2121 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:52:01.389  3946  3946 D PanProfile: Bluetooth service connected
09-09 14:52:01.391  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:52:01.391   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:52:01.392  1349  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:52:01.392  1349  1349 D BluetoothInputDevice: Proxy object connected
09-09 14:52:01.392   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:52:01.392  1349  1349 D HidProfile: Bluetooth service connected
09-09 14:52:01.393  1974  1985 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:52:01.394   872   872 D BluetoothA2dp: Proxy object connected
09-09 14:52:01.394  3946  4246 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 14:52:01.395  4259  4259 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 14:52:01.396  4259  4259 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 14:52:01.396  3946  3946 D BluetoothInputDevice: Proxy object connected
09-09 14:52:01.397  1349  1360 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:52:01.397  3946  3946 D HidProfile: Bluetooth service connected
09-09 14:52:01.398  4259  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:52:01.399  1349  2121 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:52:01.400  4259  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:52:01.401  1349  1349 D BluetoothA2dp: Proxy object connected
,09-09 14:52:01.402  3946  3956 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:52:01.402  4259  4259 D ObexServerSockets: Succeed to create listening sockets 
09-09 14:52:01.402  4259  4259 D ObexServerSockets0: startAccept()
09-09 14:52:01.402  4259  4259 D ObexServerSockets0: prepareForNewConnect()
09-09 14:52:01.403  3946  3958 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:52:01.404  4259  4259 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 14:52:01.404  4259  4259 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 14:52:01.405  4259  4303 D ObexServerSockets0: Accepting socket connection...
,09-09 14:52:01.405  4259  4304 D ObexServerSockets0: Accepting socket connection...
09-09 14:52:01.406  1349  1349 D BluetoothMap: Proxy object connected
09-09 14:52:01.406  1349  1349 D MapProfile: Bluetooth service connected
09-09 14:52:01.406  1349  1349 D BluetoothMap: getConnectedDevices()
09-09 14:52:01.406  3946  3946 D BluetoothA2dp: Proxy object connected
09-09 14:52:01.406   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:52:01.406   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:52:01.406  1349  1367 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 14:52:01.408  3946  3946 D BluetoothMap: Proxy object connected
09-09 14:52:01.408  3946  3946 D MapProfile: Bluetooth service connected
09-09 14:52:01.408  1349  2121 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:52:01.408  3946  3946 D BluetoothMap: getConnectedDevices()
09-09 14:52:01.410  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:52:01.410  1349  1349 D PanProfile: Bluetooth service connected
,09-09 14:52:01.410  3946  4246 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 14:52:01.412   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 14:52:01.414  4259  4259 D BluetoothMapService: onReceive
09-09 14:52:01.414  4259  4259 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:52:01.414  4259  4259 D BluetoothMapService: STATE_ON
09-09 14:52:01.415  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:01.421  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:52:01.427  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:52:01.429  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:52:01.437  3946  3946 D BluetoothPbap: Proxy object connected
,09-09 14:52:01.438  3946  3946 D PbapServerProfile: Bluetooth service connected
,09-09 14:52:01.440  1349  1349 D BluetoothPbap: Proxy object connected
,09-09 14:52:01.440  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-09 14:52:01.444  4259  4259 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 14:52:01.444  4259  4259 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:52:01.448  4259  4309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:52:01.465  4259  4313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:52:01.466  4259  4313 I BtOppRfcommListener: Accept thread started.
,09-09 14:52:01.491   872   872 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.491   872   889 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.491  1974  2130 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.491   872   872 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.492  1349  1367 D BluetoothHeadset: Proxy object connected
,09-09 14:52:01.492  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-09 14:52:01.492  3946  3956 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.492   872   872 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.493  1349  1360 D BluetoothHeadset: Proxy object connected
09-09 14:52:01.494  1974  1987 D BluetoothHeadset: Proxy object connected
,09-09 14:52:01.494  3946  3946 D HeadsetProfile: Bluetooth service connected
09-09 14:52:01.494  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-09 14:52:01.506   872   889 D BluetoothHeadset: Proxy object connected
,09-09 14:52:01.506   872   889 D BluetoothHeadset: Proxy object connected
,09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:52:01.789  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:52:01.797  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:52:01.800  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:52:01.802  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be892a9 added. We now have 8 listener(s)
09-09 14:52:01.802  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:52:01.808   872   882 D WifiService: setWifiEnabled: false pid=3876, uid=10000
,09-09 14:52:01.808   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:52:01.820  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:01.821   872  1986 D WifiService: setWifiEnabled: true pid=3876, uid=10000
09-09 14:52:01.822   872  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:52:01.834   872  1306 D WifiConfigStore: Loading config and enabling all networks ,
,09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:52:01.849  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:52:01.854  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:52:01.857  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:52:01.857   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-09 14:52:01.859   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 14:52:01.859   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 14:52:01.860   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:52:01.860  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:52:01.860   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 14:52:01.860   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 14:52:01.861   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 14:52:01.864  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 14:52:01.865  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 14:52:01.867  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c073235 Bundle[{}]
09-09 14:52:01.868  3876  3927 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 14:52:01.868  3876  3927 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 14:52:01.868  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 14:52:01.873  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 14:52:01.874  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 14:52:01.874  3876  3927 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 14:52:01.877   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 14:52:01.878   372   871 D CommandListener: Setting iface cfg
,09-09 14:52:01.878   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,09-09 14:52:01.879   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 14:52:01.880   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 14:52:01.880   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 14:52:01.881  3876  3927 I System.out: Running OutgoingSocketThread
,09-09 14:52:01.882  3876  4318 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 445)
09-09 14:52:01.883  3876  4318 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43184
,09-09 14:52:01.883  3876  4318 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 14:52:01.896   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 14:52:01.896   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 14:52:01.897   872  1306 E native  : do suspend true
,09-09 14:52:01.908   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 14:52:01.908   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:52:01.921   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 14:52:02.008   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 14:52:02.015  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 14:52:02.502  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:52:02.546  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 14:52:02.549  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 14:52:02.558   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:52:02.570   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:52:02.572   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 14:52:02.572   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:52:02.602   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:52:02.614   372   871 D CommandListener: Setting iface cfg
,09-09 14:52:02.615   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 14:52:02.622   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 14:52:02.641   872  4322 D DhcpClient: Receive thread started
,09-09 14:52:02.725   872  1306 E native  : do suspend false
,09-09 14:52:02.741   872  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 14:52:02.754   872  4322 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,09-09 14:52:02.755   872  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,09-09 14:52:02.758   872  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 14:52:02.771   872  4322 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 14:52:02.772   872  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 14:52:02.777   372   871 D CommandListener: Setting iface cfg
,09-09 14:52:02.788   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 14:52:02.788   872  1862 D DhcpClient: Scheduling renewal in 86399s
,09-09 14:52:02.791   872  1306 E native  : do suspend true
,09-09 14:52:02.816   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 14:52:02.819   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 14:52:02.820   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 14:52:02.821   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 14:52:02.829   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 14:52:02.883  3876  3927 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 446)
09-09 14:52:02.883  3876  3927 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 446)
09-09 14:52:02.885  3876  3927 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
09-09 14:52:02.886  3876  3927 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 14:52:02.886  3876  3927 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,09-09 14:52:02.887   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 14:52:02.888   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 14:52:02.889  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:02.889  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66c202e added. We now have 2 listener(s)
,09-09 14:52:02.891  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:02.891  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:02.891  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:02.891  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:52:02.891  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6be7cf added. We now have 9 listener(s)
09-09 14:52:02.891  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-09 14:52:02.891   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 14:52:02.893  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:52:02.896   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 14:52:02.898   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 14:52:02.898  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:52:02.906  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:52:02.909   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:52:02.910  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:52:02.910  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:52:02.912  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:02.912  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb065 added. We now have 3 listener(s)
09-09 14:52:02.912  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:02.914  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:02.914  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:02.914   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 14:52:02.915   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 14:52:02.915   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 14:52:02.915   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 14:52:02.915   872  1308 D ConnectivityService:    accepting network in place of null
09-09 14:52:02.915  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:02.914  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:02.915   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:52:02.916  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:02.916  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9e113a added. We now have 10 listener(s)
,09-09 14:52:02.916  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:52:02.916  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:52:02.916  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:02.916  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:52:02.916  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:02.916   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:52:02.916  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.917  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:02.917  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:02.917  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66c202e removed from the list
09-09 14:52:02.917  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:02.917  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6be7cf removed from the list
,09-09 14:52:02.917  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:52:02.917  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.918  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.918  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.919  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:02.919  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:02.919  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:02.920  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6be7cf not in the list
,09-09 14:52:02.920  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.920  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.921  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:02.921  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:02.921  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:02.921  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9e113a removed from the list
09-09 14:52:02.922  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:02.922  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.922  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.922  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:52:02.922  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb065 removed from the list
09-09 14:52:02.923  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:02.923  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56931eb added. We now have 2 listener(s)
09-09 14:52:02.925  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:02.925  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:02.925  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:52:02.925  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:02.925  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c20b48 added. We now have 9 listener(s)
09-09 14:52:02.925  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:02.926  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:52:02.928  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:02.933  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:52:02.935  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:52:02.935  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:52:02.935  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:02.935  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acc0706 added. We now have 3 listener(s)
09-09 14:52:02.937  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:02.937  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:52:02.937  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:52:02.937  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:02.937  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a701c7 added. We now have 10 listener(s)
09-09 14:52:02.937  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:02.938  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:52:02.938  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:52:02.938  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:52:02.938  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:52:02.938  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:52:02.940  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:02.941  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:52:02.941  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:52:02.944  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:02.944   872  4321 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:52:02.946  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:52:02.946  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:52:02.946  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:52:02.948   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 14:52:02.950  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:52:02.950  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:52:02.950  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:52:02.950  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:52:02.953  4259  4305 D BtGatt.GattService: registerClient() - UUID=f76c94b4-e354-47cc-a4a9-c467fb156051
,09-09 14:52:02.954  4259  4278 D BtGatt.GattService: onClientRegistered() - UUID=f76c94b4-e354-47cc-a4a9-c467fb156051, clientIf=5
09-09 14:52:02.954  3876  3888 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:52:02.955  4259  4302 D BtGatt.GattService: start scan with filters
,09-09 14:52:02.959  4259  4283 D BtGatt.ScanManager: handling starting scan
,09-09 14:52:02.960  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 14:52:02.960  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:52:02.960  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 14:52:02.961  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:52:02.961  4259  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b21c6c
09-09 14:52:02.963  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:52:02.963  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:52:02.963  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:52:02.965  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 14:52:02.966  4259  4278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:52:02.966  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:02.966  4259  4283 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 14:52:02.968  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 14:52:02.968  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:02.968  4259  4283 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:52:02.968  4259  4283 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 14:52:02.969  3876  3927 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:52:02.969  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:02.969  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 14:52:02.969  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:02.969  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:52:02.969  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:52:02.969  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 14:52:02.969  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:52:02.969  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:52:02.969  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:52:02.969  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:52:02.970  4259  4278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:52:02.970  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:02.971  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:52:02.971  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:02.973  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:52:02.973  4259  4305 D BtGatt.GattService: stopScan() - queue size =1
,09-09 14:52:02.974  4259  4302 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 14:52:02.974  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:52:02.974  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 14:52:02.974  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:52:02.974  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:52:02.974  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 14:52:02.975  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:52:02.976  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:02.976  4259  4283 D BtGatt.ScanManager: stopping BLe Batch
,09-09 14:52:02.976  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:52:02.976  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 14:52:02.976  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:52:02.976  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:52:02.977  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:52:02.978  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:52:02.978  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:52:02.978  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:52:02.978  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:02.978  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:52:02.979  4259  4283 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:52:02.980  4259  4278 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:52:02.980  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:02.982  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:52:02.982  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:02.983  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:52:02.983  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:02.983  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.983  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:02.983  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:02.983  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56931eb removed from the list
09-09 14:52:02.983  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:02.983  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c20b48 removed from the list
,09-09 14:52:02.983  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:52:02.983  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.983  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.984  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.984   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 14:52:02.984  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:02.984  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:52:02.985  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:52:02.985  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c20b48 not in the list
09-09 14:52:02.985  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.985  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:02.986  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:52:02.986  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:02.986  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:52:02.986  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a701c7 removed from the list
09-09 14:52:02.986  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:52:02.986  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:02.986  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:02.986  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:02.986  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acc0706 removed from the list
,09-09 14:52:02.987  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:02.987  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f07f363 added. We now have 2 listener(s)
09-09 14:52:02.989   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 14:52:02.990  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:02.990  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:52:02.990  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:02.989   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:52:02.991  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:02.991  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41cfb60 added. We now have 9 listener(s)
09-09 14:52:02.991  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:52:02.995  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:52:02.995   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 14:52:02.996   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:52:03.003  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:03.005  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:52:03.007  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:03.009  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:52:03.011  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.011  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:52:03.011  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:03.011  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6f0de added. We now have 3 listener(s)
09-09 14:52:03.013  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:03.015  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:03.015  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:03.015  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:03.015  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:52:03.016  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:03.016  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc62bf added. We now have 10 listener(s)
09-09 14:52:03.016  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:03.016  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:52:03.016  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:52:03.016  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:52:03.017  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:52:03.017  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:52:03.017  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:52:03.018  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:52:03.019  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:52:03.019  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:52:03.022  1705  1705 D SystemUpdateService: onCreate
,09-09 14:52:03.023  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:52:03.023  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:52:03.024  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:52:03.026  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 14:52:03.027  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:52:03.027  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:52:03.027  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:52:03.027  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:52:03.029  4259  4305 D BtGatt.GattService: registerClient() - UUID=1508eaec-3319-4ab5-9c13-a9876be38c45
,09-09 14:52:03.029  4259  4278 D BtGatt.GattService: onClientRegistered() - UUID=1508eaec-3319-4ab5-9c13-a9876be38c45, clientIf=5
,09-09 14:52:03.030  3876  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:52:03.030  4259  4294 D BtGatt.GattService: start scan with filters
,09-09 14:52:03.033  4259  4283 D BtGatt.ScanManager: handling starting scan
,09-09 14:52:03.033  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:52:03.033  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:52:03.033  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:52:03.033  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:52:03.035  4259  4278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:52:03.035  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.035  4259  4283 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 14:52:03.036  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:52:03.036  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.037  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:52:03.037  4259  4283 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:52:03.037  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:52:03.037  4259  4283 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:52:03.037  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:52:03.039  4259  4278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:52:03.039  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.040  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 14:52:03.040  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.040  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 14:52:03.043  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:52:03.043  3876  3927 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 14:52:03.043  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:52:03.044  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:03.044  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:52:03.044  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:03.044  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.044  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 14:52:03.044  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.044  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f07f363 removed from the list
09-09 14:52:03.044  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.045  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41cfb60 removed from the list
09-09 14:52:03.045  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:52:03.045  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:03.045  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.045  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 14:52:03.045  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.045  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:03.046  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:52:03.046  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:03.046  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.046  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41cfb60 not in the list
09-09 14:52:03.046  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:52:03.046  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:52:03.046  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 14:52:03.047  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:52:03.047  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:52:03.047  3876  3927 D BluetoothAdapter: STATE_ON
09-09 14:52:03.048  4259  4294 D BtGatt.GattService: stopScan() - queue size =1
,09-09 14:52:03.048  4259  4302 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:52:03.049  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:52:03.049  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:52:03.049  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:52:03.049  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 14:52:03.049  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:52:03.049  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.049  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:52:03.049  4259  4283 D BtGatt.ScanManager: stopping BLe Batch
,09-09 14:52:03.050  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:52:03.050  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 14:52:03.050  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:52:03.050  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:52:03.051  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:03.052  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:52:03.052  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:52:03.052  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:52:03.052  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:03.052  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:52:03.052  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.052  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:52:03.052  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc62bf removed from the list
09-09 14:52:03.053  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:03.053  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.053  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.053  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:03.053  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.053  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6f0de removed from the list
09-09 14:52:03.053  4259  4283 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:52:03.053  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:03.054  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e6bdb added. We now have 2 listener(s)
09-09 14:52:03.054  4259  4278 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:52:03.055  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.055  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:52:03.055  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:03.055  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:52:03.056  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:03.056  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b2d678 added. We now have 9 listener(s)
09-09 14:52:03.056  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:03.056  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 14:52:03.056  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:52:03.060  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:03.064  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:52:03.066  1705  2410 I iu.UploadsManager: num queued entries: 0
,09-09 14:52:03.066  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.067  1705  2410 I iu.UploadsManager: num updated entries: 0
09-09 14:52:03.067  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:52:03.067  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:52:03.068  1705  4331 I SystemUpdateService: active receiver: enabled
,09-09 14:52:03.069  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:03.068  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72a3db6 added. We now have 3 listener(s)
09-09 14:52:03.070  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:52:03.077  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:52:03.077  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:03.079  4038  4038 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:52:03.080  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:52:03.080  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:03.080  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:52:03.081  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:03.081  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8deab7 added. We now have 10 listener(s)
,09-09 14:52:03.082  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:03.082  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:52:03.082  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:52:03.082  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:52:03.083  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:52:03.083  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:52:03.084  4038  4038 D SprintDMHelper: simOperator: 
,09-09 14:52:03.084  4038  4038 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 14:52:03.091   872  4320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-09 14:52:03.091  3876  3927 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:52:03.091  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:52:03.096  1705  4334 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 14:52:03.096  1705  4334 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 14:52:03.096  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:52:03.097  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:52:03.097  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:52:03.100  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:52:03.100  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:52:03.100  3876  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 14:52:03.101  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:52:03.102  4259  4270 D BtGatt.GattService: registerClient() - UUID=8030384b-90ce-4542-86d0-3efc267966fd
,09-09 14:52:03.102  4259  4278 D BtGatt.GattService: onClientRegistered() - UUID=8030384b-90ce-4542-86d0-3efc267966fd, clientIf=5
,09-09 14:52:03.103  3876  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:52:03.103  4259  4305 D BtGatt.GattService: start scan with filters
,09-09 14:52:03.105  1705  4334 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
09-09 14:52:03.106  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:52:03.106  4259  4283 D BtGatt.ScanManager: handling starting scan
09-09 14:52:03.106  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:52:03.106  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:52:03.106  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:52:03.108  4259  4278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:52:03.108  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.108  4259  4283 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:52:03.109  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:52:03.109  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:52:03.109  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:52:03.109  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:52:03.109  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.109  4259  4283 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:52:03.110  4259  4283 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:52:03.111  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 14:52:03.112  4259  4278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 14:52:03.112  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.113  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:52:03.113  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.115  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:52:03.116  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:03.116  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:52:03.116  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:03.116  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.116  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:52:03.116  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.116  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e6bdb removed from the list
09-09 14:52:03.116  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.116  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b2d678 removed from the list
,09-09 14:52:03.116  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:52:03.116  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:03.117  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.117  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 14:52:03.117  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.117  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:52:03.118  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:03.118  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:03.119  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:52:03.119  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:52:03.119  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b2d678 not in the list
09-09 14:52:03.119  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:52:03.119  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 14:52:03.119  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:52:03.119  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:52:03.119  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:52:03.120  3876  3927 D BluetoothAdapter: STATE_ON
,09-09 14:52:03.121  4259  4269 D BtGatt.GattService: stopScan() - queue size =1
09-09 14:52:03.122  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:52:03.124  4259  4270 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 14:52:03.125  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:52:03.125  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:52:03.125  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 14:52:03.125  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:52:03.125  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 14:52:03.127  4259  4278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:52:03.127  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.127  4259  4283 D BtGatt.ScanManager: stopping BLe Batch
,09-09 14:52:03.133  4259  4278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 14:52:03.133  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:52:03.134  4259  4283 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 14:52:03.135  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:52:03.135  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:52:03.135  3876  3927 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:52:03.135  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:52:03.135  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:03.136  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:52:03.137  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:52:03.137  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:52:03.137  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:52:03.137  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:52:03.137  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.137  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8deab7 removed from the list
09-09 14:52:03.137  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:52:03.137  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.137  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:03.137  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.137  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72a3db6 removed from the list
09-09 14:52:03.138  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:03.138  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58c7b53 added. We now have 2 listener(s)
,09-09 14:52:03.139  1705  4331 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 14:52:03.140  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:52:03.140  4259  4278 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:52:03.140  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:52:03.140  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:03.140  4259  4278 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:52:03.140  1705  2410 I iu.SyncManager: NEXT; no task
09-09 14:52:03.141  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:03.141  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95fc90 added. We now have 9 listener(s)
09-09 14:52:03.141  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:03.142  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:52:03.144  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:52:03.147  1705  4331 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 14:52:03.148  1705  4331 I SystemUpdateService: now status is 0 (complete)
,09-09 14:52:03.148  1705  4331 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 14:52:03.148  1705  4331 I SystemUpdateService: file has been verified
09-09 14:52:03.148  1705  4331 I SystemUpdateService: OTA package size = 12249756
,09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:03.149  3876  3927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:52:03.151  3876  3927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:52:03.152  3876  3927 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:52:03.152  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:52:03.153  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56f4d8e added. We now have 3 listener(s)
,09-09 14:52:03.155  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:52:03.155  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:52:03.155  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:03.155  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:52:03.155  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d979af added. We now have 10 listener(s)
09-09 14:52:03.155  3876  3927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:52:03.155  3876  3927 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:52:03.155  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:03.155  3876  3927 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:52:03.155  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:52:03.156  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.156  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:52:03.156  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.157  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:03.157  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58c7b53 removed from the list
09-09 14:52:03.157  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.157  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95fc90 removed from the list
,09-09 14:52:03.159  1705  4331 I SystemUpdateService: showing system update notification
,09-09 14:52:03.160  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:52:03.160  3876  3927 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:52:03.160  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:03.161  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.161  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:03.163  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:52:03.163  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:52:03.164  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:52:03.164  3876  3927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95fc90 not in the list
09-09 14:52:03.164  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:52:03.164  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:52:03.165  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:52:03.165  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:52:03.165  3876  3927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:52:03.165  3876  3927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d979af removed from the list
09-09 14:52:03.165  3876  3927 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:52:03.165  3876  3927 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:52:03.165  3876  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:52:03.166  3876  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:52:03.166  3876  3927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56f4d8e removed from the list
09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 14:52:03.167  3876  3927 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:52:03.170  1705  1705 D SystemUpdateService: onDestroy
09-09 14:52:03.174  1510  4086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 14:52:03.174  1510  4086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 14:52:03.174  1510  4086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:52:03.174  1510  4086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 14:52:03.175  3876  4340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
09-09 14:52:03.175  3876  4340 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
09-09 14:52:03.175  3876  4340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 14:52:03.177  3876  4341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
09-09 14:52:03.177  3876  4341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
09-09 14:52:03.177  3876  4341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 14:52:03.179  3876  3927 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 14:52:03.180  3876  3927 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 14:52:03.180  3876  3927 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-09 14:52:03.180  3876  3927 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 14:52:03.180  3876  3927 D com.test.thalitest.ThaliTestRunner: Total duration: 21823 ms
09-09 14:52:03.184  3876  3927 I jxcore-log: *Native tests were executed*
09-09 14:52:03.184  3876  3927 I jxcore-log: 
09-09 14:52:03.184  3876  3927 I jxcore-log: Total number of executed tests:  80
09-09 14:52:03.184  3876  3927 I jxcore-log: 
09-09 14:52:03.184  3876  3927 I jxcore-log: Number of passed tests:  80
09-09 14:52:03.184  3876  3927 I jxcore-log: 
09-09 14:52:03.184  3876  3927 I jxcore-log: Number of failed tests:  0
09-09 14:52:03.184  3876  3927 I jxcore-log: 
09-09 14:52:03.184  3876  3927 I jxcore-log: Number of ignored tests:  0
09-09 14:52:03.184  3876  3927 I jxcore-log: 
09-09 14:52:03.185  3876  3927 I jxcore-log: Total duration:  21823
09-09 14:52:03.185  3876  3927 I jxcore-log: 
09-09 14:52:03.185  3876  3927 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 14:52:03.185  3876  3927 I jxcore-log: 
09-09 14:52:03.189  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.189  3876  3927 I jxcore-log: 
,09-09 14:52:03.192  1705  4334 E MDM     : [178] SitrepService.a: Error sending sitrep.
09-09 14:52:03.193  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.193  3876  3927 I jxcore-log: 
09-09 14:52:03.194  3876  3876 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 14:52:03.194  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.194  3876  3927 I jxcore-log: 
09-09 14:52:03.196  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.196  3876  3927 I jxcore-log: 
09-09 14:52:03.197  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.197  3876  3927 I jxcore-log: 
09-09 14:52:03.198  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.198  3876  3927 I jxcore-log: 
09-09 14:52:03.200  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.200  3876  3927 I jxcore-log: 
09-09 14:52:03.201  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.201  3876  3927 I jxcore-log: 
09-09 14:52:03.202  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.202  3876  3927 I jxcore-log: 
09-09 14:52:03.203  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:52:03.203  3876  3927 I jxcore-log: 
09-09 14:52:03.204  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:52:03.204  3876  3927 I jxcore-log: 
09-09 14:52:03.204  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:52:03.204  3876  3927 I jxcore-log: 
09-09 14:52:03.205  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.205  3876  3927 I jxcore-log: 
09-09 14:52:03.206  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.206  3876  3927 I jxcore-log: 
09-09 14:52:03.206  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.206  3876  3927 I jxcore-log: 
09-09 14:52:03.207  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.207  3876  3927 I jxcore-log: 
09-09 14:52:03.208  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.208  3876  3927 I jxcore-log: 
09-09 14:52:03.208   872  4320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:52:03 GMT], X-Android-Received-Millis=[1473425523208], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473425523181]}
09-09 14:52:03.208  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.208  3876  3927 I jxcore-log: 
09-09 14:52:03.209   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 14:52:03.209   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 14:52:03.209   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:52:03.210   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:52:03.211  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.211  3876  3927 I jxcore-log: 
09-09 14:52:03.212  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.212  3876  3927 I jxcore-log: 
,09-09 14:52:03.213  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.213  3876  3927 I jxcore-log: 
09-09 14:52:03.214  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:52:03.214  3876  3927 I jxcore-log: 
,09-09 14:52:03.215  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:52:03.215  3876  3927 I jxcore-log: 
09-09 14:52:03.215  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:52:03.215  3876  3927 I jxcore-log: 
09-09 14:52:03.216  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:52:03.216  3876  3927 I jxcore-log: 
,09-09 14:52:03.217  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.217  3876  3927 I jxcore-log: 
09-09 14:52:03.217  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.217  3876  3927 I jxcore-log: 
09-09 14:52:03.218  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.218  3876  3927 I jxcore-log: 
,09-09 14:52:03.218  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.218  3876  3927 I jxcore-log: 
09-09 14:52:03.219  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:52:03.219  3876  3927 I jxcore-log: 
,09-09 14:52:03.289  2760  4336 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 14:52:03.480  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:52:03.483  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:52:03.483  3876  3927 I jxcore-log: 
,09-09 14:52:03.553  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:52:03.556  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:52:03.556  3876  3927 I jxcore-log: 
,09-09 14:52:03.638  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:52:03.641  3876  3927 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:52:03.641  3876  3927 I jxcore-log: 
,09-09 14:52:03.869  4346  4346 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 14:52:03.873  4346  4346 D AndroidRuntime: CheckJNI is OFF
,09-09 14:52:03.913  4346  4346 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 14:52:03.958  4346  4346 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 14:52:03.982  4346  4346 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 14:52:03.988   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 14:52:03.994   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-09 14:52:03.995   872   885 I ActivityManager: Killing 3876:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 14:52:04.092   872  2015 D GraphicsStats: Buffer count: 2
,09-09 14:52:04.093   872   882 I WindowState: WIN DEATH: Window{7b85e96 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:52:04.093   872  1307 D WifiService: Client connection lost with reason: 4
,09-09 14:52:04.103   872   895 W PackageSettings: Skipping PackageSetting{fa32089 com.example.hello/10273} due to missing metadata
,09-09 14:52:04.135   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-09 14:52:04.135   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 14:52:04.136   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-09 14:52:04.136   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 14:52:04.136   872   885 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 14:52:04.136   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.136   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.136   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:52:04.136   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-09 14:52:04.136   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4050c3f u0 com.test.thalitest/.MainActivity t4}
09-09 14:52:04.141   872  2095 W ActivityManager: Spurious death for ProcessRecord{5df5ff8 0:com.test.thalitest/u0a0}, curProc for 3876: null
,09-09 14:52:04.151   872   895 I art     : Starting a blocking GC Explicit
,09-09 14:52:04.206   872   895 I art     : Explicit concurrent mark sweep GC freed 55408(3MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 677us total 50.281ms
,09-09 14:52:04.233   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 14:52:04.239  4346  4346 I art     : System.exit called, status: 0
,09-09 14:52:04.240  4346  4346 I AndroidRuntime: VM exiting with result code 0.
,09-09 14:52:04.245   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 14:52:04.258   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 14:52:04.265  4259  4259 D BluetoothMapAppObserver: onReceive
,09-09 14:52:04.265  4259  4259 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 14:52:04.265   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 14:52:04.267  1861  2288 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 14:52:04.271  3746  3746 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 14:52:04.273  1892  1892 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-09 14:52:04.303  1974  1974 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 14:52:04.315   872  2097 I ActivityManager: Start proc 4363:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 14:52:04.315  1892  4361 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 14:52:04.341  1892  4361 I Decoder : createOrResetDecoder
,09-09 14:52:04.346  4363  4363 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 14:52:04.353   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 14:52:04.361  1510  1510 I ConfigService: onCreate
,09-09 14:52:04.363  1510  4375 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:52:04.363  1510  4375 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:52:04.363  1510  4375 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:52:04.365  1510  4375 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-09 14:52:04.373   872  1704 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3876 uid 10000
,09-09 14:52:04.375  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-09 14:52:04.376  1892  4361 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 14:52:04.386  1988  2091 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-09 14:52:04.389   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 14:52:04.390   872   884 E PackageManager: Failed to write settings, restoring backup
09-09 14:52:04.390   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 14:52:04.390   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 14:52:04.390   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 14:52:04.390   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 14:52:04.390   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 14:52:04.390   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.390   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.390   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:52:04.394   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-09 14:52:04.394   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 14:52:04.394   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.394   872   885 E DropBoxManagerService: 	... 13 more
,09-09 14:52:04.399   872  1704 I ActivityManager: Start proc 4380:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-09 14:52:04.399  1988  2091 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 14:52:04.399  1988  2091 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1988
09-09 14:52:04.399  1988  2091 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.399  1988  2091 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:52:04.402   872  1922 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 14:52:04.402   872  4385 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:52:04.402   872  4385 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.402   872  4385 E DropBoxManagerService: 	... 5 more
,09-09 14:52:04.405  1988  2091 I Process : Sending signal. PID: 1988 SIG: 9
,09-09 14:52:04.411  1892  4361 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-09 14:52:04.413  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-09 14:52:04.413  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 14:52:04.415  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-09 14:52:04.415  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 14:52:04.415  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 14:52:04.415  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-09 14:52:04.424  1892  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-09 14:52:04.424  1892  4361 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 14:52:04.424  1892  4361 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 14:52:04.425  1892  4361 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-09 14:52:04.427  4363  4363 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 14:52:04.425  1892  4361 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 14:52:04.427  1892  4361 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 14:52:04.444   872  2015 I ActivityManager: Start proc 4393:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 14:52:04.447  4363  4396 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 14:52:04.464  4363  4396 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.464  4363  4396 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:52:04.465  4363  4396 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 14:52:04.465  4363  4396 E AndroidRuntime: Process: android.process.acore, PID: 4363
09-09 14:52:04.465  4363  4396 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
,09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.465  4363  4396 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:52:04.469   872  4407 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:52:04.469   872  4407 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.469   872  4407 E DropBoxManagerService: 	... 5 more
,09-09 14:52:04.470  4363  4396 I Process : Sending signal. PID: 4363 SIG: 9
,09-09 14:52:04.488  4393  4393 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 14:52:04.492   872   883 D GraphicsStats: Buffer count: 1
,09-09 14:52:04.492   872  1922 I WindowState: WIN DEATH: Window{e8d3fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-09 14:52:04.503   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1988) has died
,09-09 14:52:04.503   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 14:52:04.507   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 14:52:04.524   872   885 I ActivityManager: Start proc 4410:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:52:04.540  1510  1510 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-09 14:52:04.540  1510  1510 D AndroidRuntime: Shutting down VM
,09-09 14:52:04.541  1510  1510 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:52:04.541  1510  1510 E AndroidRuntime: Process: com.google.process.gapps, PID: 1510
09-09 14:52:04.541  1510  1510 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 14:52:04.541  1510  1510 E AndroidRuntime: 	... 8 more
09-09 14:52:04.542   279   279 E lowmemorykiller: Error writing /proc/4363/oom_score_adj; errno=22
,09-09 14:52:04.545   279   279 E lowmemorykiller: Error writing /proc/4363/oom_score_adj; errno=22
,09-09 14:52:04.549   872  4425 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:52:04.549   872  4425 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.549   872  4425 E DropBoxManagerService: 	... 5 more
09-09 14:52:04.551  1510  1510 I Process : Sending signal. PID: 1510 SIG: 9
,09-09 14:52:04.568  1705  4422 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,09-09 14:52:04.568  1705  4422 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@53d85db
,09-09 14:52:04.568   872  1922 I ActivityManager: Process com.google.process.gapps (pid 1510) early provider death
,09-09 14:52:04.577  4410  4410 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:52:04.577  4410  4410 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:52:04.578  4410  4410 D AndroidRuntime: Shutting down VM
,09-09 14:52:04.598   872  1307 D WifiService: Client connection lost with reason: 4
,09-09 14:52:04.600   872  1922 I ActivityManager: Process com.google.process.gapps (pid 1510) has died
,09-09 14:52:04.601   872  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,09-09 14:52:04.601   872  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 10999ms
09-09 14:52:04.601   872  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
09-09 14:52:04.601   872  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,09-09 14:52:04.605   872  1986 W ActivityManager: Spurious death for ProcessRecord{3b306b8 0:com.google.process.gapps/u0a11}, curProc for 1510: null
,09-09 14:52:04.608  4410  4410 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:52:04.608  4410  4410 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4410
09-09 14:52:04.608  4410  4410 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:52:04.608  4410  4410 E AndroidRuntime: 	... 10 more
,09-09 14:52:04.627   872   883 I ActivityManager: Start proc 4428:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-09 14:52:04.629   872  1986 I ActivityManager: Process android.process.acore (pid 4363) has died
,09-09 14:52:04.629   872  1986 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40971ms
,09-09 14:52:04.633  1705  1705 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-09 14:52:04.635   872  2015 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:52:04.635   872  4433 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:52:04.635   872  4433 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.635   872  4433 E DropBoxManagerService: 	... 5 more
,09-09 14:52:04.637  4410  4410 I Process : Sending signal. PID: 4410 SIG: 9
,09-09 14:52:04.645   872  2096 I ActivityManager: Killing 3803:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 14:52:04.703   872  2095 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4410) has died
,09-09 14:52:04.704   872  2095 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 14:52:04.717  4428  4428 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-09 14:52:04.719   872   885 I ActivityManager: Start proc 4443:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:52:04.725  4428  4428 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-09 14:52:04.728  4428  4428 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:52:04.728  4428  4428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:52:04.728  4428  4428 D AndroidRuntime: Shutting down VM
,09-09 14:52:04.729  4428  4428 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:52:04.729  4428  4428 E AndroidRuntime: Process: com.google.process.gapps, PID: 4428
09-09 14:52:04.729  4428  4428 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:52:04.729  4428  4428 E AndroidRuntime: 	... 10 more
09-09 14:52:04.731  4428  4428 I Process : Sending signal. PID: 4428 SIG: 9
09-09 14:52:04.732   872  4455 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:52:04.732   872  4455 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:52:04.732   872  4455 E DropBoxManagerService: 	... 5 more

```
