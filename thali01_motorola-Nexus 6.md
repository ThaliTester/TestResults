#### Test 82642184cbac892_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 02:46:07.319  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 02:46:07.336  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 02:46:07.342  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 02:46:07.423  1525  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 02:46:07.423  1525  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 02:46:07.424  1525  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 02:46:07.424  1525  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 02:46:07.457  3629  3629 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 02:46:07.459  3629  3629 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 02:46:07.460  3629  3629 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-30 02:46:07.999  3932  3932 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 02:46:08.004  3932  3932 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:08.047  3932  3932 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 02:46:08.096  3932  3932 I Radio-JNI: register_android_hardware_Radio DONE
08-30 02:46:08.117  3932  3932 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 02:46:08.121   874  1379 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 02:46:08.150  1998  2012 W SearchService: Abort, client detached.
08-30 02:46:08.168  3932  3932 D AndroidRuntime: Shutting down VM
08-30 02:46:08.172  1998  2313 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e755d94
08-30 02:46:08.172  1998  2329 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 02:46:08.173  1998  1998 I HotwordDetector: Closing mic
08-30 02:46:08.191   874  1976 I ActivityManager: Start proc 3941:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 02:46:08.225   376  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 02:46:08.227   376  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 02:46:08.236   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 02:46:08.239  1998  2323 I MicroRecognitionRnrImpl: Detection finished
08-30 02:46:08.240  1998  2319 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 02:46:08.265  3941  3941 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 02:46:08.289  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 02:46:08.296  3941  3941 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2929-2932)
08-30 02:46:08.297  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:46:08.311  3941  3941 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {230db18}
08-30 02:46:08.312  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:46:08.312  3941  3941 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 02:46:08.321  3941  3941 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 02:46:08.330  3941  3941 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 02:46:08.374  3941  3941 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 02:46:08.392  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 02:46:08.392  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 02:46:08.392  3941  3941 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 02:46:08.392  3941  3941 I Adreno  : Build Date                       : 10/20/15
08-30 02:46:08.392  3941  3941 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 02:46:08.392  3941  3941 I Adreno  : Local Branch                     : M14
08-30 02:46:08.392  3941  3941 I Adreno  : Remote Branch                    : 
08-30 02:46:08.392  3941  3941 I Adreno  : Remote Branch                    : 
08-30 02:46:08.392  3941  3941 I Adreno  : Reconstruct Branch               : 
,08-30 02:46:08.476   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bf9bd8e:true
,08-30 02:46:08.517  3941  3941 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 02:46:08.534  3941  3941 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 02:46:08.596  3941  3980 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:46:08.608  3941  3966 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 02:46:08.666  3941  3980 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:46:08.769   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms
,08-30 02:46:08.776  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-30 02:46:08.836  3941  3941 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3941
,08-30 02:46:08.998   874  1976 I ActivityManager: Killing 3306:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 02:46:09.004  3941  3941 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 02:46:09.057   874  1976 I ActivityManager: Killing 2645:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-30 02:46:09.146  3941  3982 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681917648
,08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 02:46:09.156  3941  3982 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5929d1c added. We now have 1 listener(s)
,08-30 02:46:09.161  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 02:46:09.162  3941  3982 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 02:46:09.163  3941  3982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 02:46:09.163  3941  3982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 02:46:09.167  3941  3982 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b9ccab added. We now have 1 listener(s)
08-30 02:46:09.167  3941  3982 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 02:46:09.170   874  1317 D WifiService: New client listening to asynchronous messages
,08-30 02:46:09.171  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 02:46:09.171  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:46:09.171  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:46:09.171  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:46:09.171  3941  3982 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 02:46:09.174  3941  3982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 02:46:09.174  3941  3982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 02:46:09.178  3941  3982 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:09.178  3941  3982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:46:09.178  3941  3982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:46:09.179  3941  3982 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 02:46:09.179  3941  3982 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 02:46:09.239  3941  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:46:09.241  3941  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:46:09.243  3941  3941 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 02:46:09.500   874  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 02:46:10.106  3941  3992 W jxcore-log: Initializing JXcore engine
,08-30 02:46:10.106  3941  3992 W jxcore-log: JXcore engine is ready
,08-30 02:46:10.141  3992  3992 W Thread-354: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 02:46:10.141  3992  3992 W Thread-354: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10555]" dev="sockfs" ino=10555 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 02:46:10.141  3992  3992 W Thread-354: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 02:46:10.141  3992  3992 W Thread-354: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25060]" dev="sockfs" ino=25060 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 02:46:10.156  3941  3992 W jxcore-log: Starting JXcore engine
,08-30 02:46:10.238  3941  3992 W jxcore-log: Platform android
08-30 02:46:10.238  3941  3992 W jxcore-log: 
,08-30 02:46:10.239  3941  3992 W jxcore-log: Process ARCH arm
08-30 02:46:10.239  3941  3992 W jxcore-log: 
,08-30 02:46:10.561  3941  3992 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:46:10.561  3941  3992 I jxcore-log: 
,08-30 02:46:10.561  3941  3992 W jxcore-log: JXcore engine is started
,08-30 02:46:10.569  3941  3982 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:46:10.574  3941  3941 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 02:46:12.934   874  2072 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 02:46:15.003  3716  3998 V KeepSync: Connecting to GoogleApiClient
08-30 02:46:15.004   874  1912 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 02:46:15.052  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 02:46:15.055  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 02:46:15.080  1525  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 02:46:15.081  1525  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 02:46:15.081  1525  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 02:46:15.081  1525  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 02:46:15.142  1758  4000 V BaseAuthAsyncOperation: access token request failed
,08-30 02:46:15.144  3716  3998 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 02:46:15.181  1525  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 02:46:15.181  1525  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 02:46:15.181  1525  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 02:46:15.182  1525  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 02:46:15.212  3716  3998 E KeepSync: IOException
08-30 02:46:15.212  3716  3998 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 02:46:15.212  3716  3998 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 02:46:15.212  3716  3998 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 02:46:15.212  3716  3998 E KeepSync: 	... 10 more
,08-30 02:46:15.212  3716  3998 W KeepSync: Sync result 2
,08-30 02:46:15.216   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128714, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 02:46:24.713  3941  3992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:46:24.713  3941  3992 I jxcore-log: 
,08-30 02:46:24.717  3941  3992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:46:24.717  3941  3992 I jxcore-log: 
,08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:24.729  3941  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 02:46:24.735  3941  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 02:46:24.741  3941  3992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:46:24.741  3941  3992 I jxcore-log: 
,08-30 02:46:24.748  3941  3992 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:46:24.748  3941  3992 I jxcore-log: 
,08-30 02:46:25.117  3941  3992 I jxcore-log: Running unit tests
08-30 02:46:25.117  3941  3992 I jxcore-log: 
,08-30 02:46:25.118  3941  3992 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:46:25.118  3941  3992 I jxcore-log: Failed to execute UT.
08-30 02:46:25.118  3941  3992 I jxcore-log: 
08-30 02:46:25.119  3941  3992 I jxcore-log: Unit Test app is loaded
08-30 02:46:25.119  3941  3992 I jxcore-log: 
,08-30 02:46:25.127  3941  3992 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:46:25.127  3941  3992 I jxcore-log: 
,08-30 02:46:25.136  3941  3941 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:46:25.143  3941  3992 I jxcore-log: My device name is: motorola-Nexus 6
08-30 02:46:25.143  3941  3992 I jxcore-log: 
,08-30 02:46:25.152  3941  3992 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 02:46:25.152  3941  3992 I jxcore-log: 
,08-30 02:46:27.570  3941  3992 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:46:27.570  3941  3992 I jxcore-log: 
,08-30 02:46:28.017  3941  3992 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:46:28.017  3941  3992 I jxcore-log: 
,08-30 02:46:28.041  3941  3992 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:46:28.041  3941  3992 I jxcore-log: 
,08-30 02:46:29.389  3941  3992 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:46:29.389  3941  3992 I jxcore-log: 
,08-30 02:46:29.619  3941  3992 I jxcore-log: ERROR runTests: 
08-30 02:46:29.619  3941  3992 I jxcore-log: 
,08-30 02:46:29.622  3941  3992 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:29.622  3941  3992 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:46:29.623  3941  3992 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:46:29.623  3941  3992 I jxcore-log: 
,08-30 02:46:29.633  3941  3992 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _functionName: 'loadFile',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _lineNumber: '26',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _columnNumber: '11',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:46:29.633  3941  3992 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _functionName: '',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _lineNumber: '38',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _columnNumber: '7',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:46:29.633  3941  3992 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _functionName: '',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _lineNumber: '35',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _columnNumber: '3',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:46:29.633  3941  3992 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _lineNumber: '621',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _columnNumber: '8',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:46:29.633  3941  3992 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _lineNumber: '651',
08-30 02:46:29.633  3941  3992 I jxcore-log:     _columnNumber: '1',
08-30 02:46:29.633  3941  3992 I jxcore-log:    
,08-30 02:46:29.634  3941  3992 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:46:29.634  3941  3992 I jxcore-log: 
,08-30 02:46:29.634  3941  3992 E jxcore-log: Error: 
08-30 02:46:29.634  3941  3992 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:29.634  3941  3992 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:46:29.634  3941  3992 E jxcore-log: 
,08-30 02:46:30.341  4005  4005 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 02:46:30.346  4005  4005 D AndroidRuntime: CheckJNI is OFF
,08-30 02:46:30.382  4005  4005 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 02:46:30.421  4005  4005 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 02:46:30.442  4005  4005 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:46:30.454   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-30 02:46:30.455   874   887 I ActivityManager: Killing 3941:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 02:46:30.506   874  1306 W InputDispatcher: channel '816a63e com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-30 02:46:30.506   874  1306 E InputDispatcher: channel '816a63e com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-30 02:46:30.529   874  1920 D GraphicsStats: Buffer count: 2
,08-30 02:46:30.529   874  2263 I WindowState: WIN DEATH: Window{816a63e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 02:46:30.529   874  2263 W InputDispatcher: Attempted to unregister already unregistered input channel '816a63e com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-30 02:46:30.529   874  1317 D WifiService: Client connection lost with reason: 4
,08-30 02:46:30.549   874   887 W ActivityManager: Force removing ActivityRecord{fa6b1c7 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-30 02:46:30.561   874   897 W PackageSettings: Skipping PackageSetting{3073967 com.example.hello/10273} due to missing metadata
,08-30 02:46:30.592   874   897 I art     : Starting a blocking GC Explicit
,08-30 02:46:30.608   874  1912 W ActivityManager: Spurious death for ProcessRecord{35a0a7c 0:com.test.thalitest/u0a0}, curProc for 3941: null
,08-30 02:46:30.640   874  3257 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3941 uid 10000
,08-30 02:46:30.642  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-30 02:46:30.693   874   897 I art     : Explicit concurrent mark sweep GC freed 42917(2MB) AllocSpace objects, 11(268KB) LOS objects, 33% free, 29MB/43MB, paused 2.598ms total 99.386ms
,08-30 02:46:30.716  1998  4019 I MicroRecognitionRnrImpl: Starting detection.
,08-30 02:46:30.717  1998  4020 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@c1109ea
,08-30 02:46:30.721   376  4022 I AudioFlinger: AudioFlinger's thread 0xb3300000 ready to run
,08-30 02:46:30.722   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 02:46:30.723  1998  4020 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@c1109ea
,08-30 02:46:30.733   376  4022 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-30 02:46:30.733   376  4022 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-30 02:46:30.733   376  4022 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-30 02:46:30.735   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 02:46:30.738  4005  4005 I art     : System.exit called, status: 0
08-30 02:46:30.738  4005  4005 I AndroidRuntime: VM exiting with result code 0.
08-30 02:46:30.739   376  4022 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-30 02:46:30.748   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 02:46:30.781  2811  2811 D BluetoothMapAppObserver: onReceive
,08-30 02:46:30.781  2811  2811 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 02:46:30.783   874  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 02:46:30.789  1866  1866 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 02:46:30.789  2191  2274 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 02:46:30.788  3780  3780 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 02:46:30.795  1866  4027 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 02:46:30.804  1866  4027 I Decoder : createOrResetDecoder
,08-30 02:46:30.825  1998  1998 I HotwordWorkerImpl: onReady
,08-30 02:46:30.827  1931  1931 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 02:46:30.851  1709  4030 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 02:46:30.855  1525  1525 I ConfigService: onCreate
,08-30 02:46:30.865  1525  1525 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-30 02:46:30.865  1525  1525 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-30 02:46:30.865   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 02:46:30.873  1866  4027 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 02:46:30.878  1758  4033 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 02:46:30.878  1758  4033 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 02:46:30.888  1758  4033 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-30 02:46:30.896  1758  4033 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:30.896  1758  4033 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:30.897  1758  4033 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:30.898  1758  4033 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-30 02:46:30.900  1758  4038 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 02:46:30.901  1758  4038 E DriveAsyncService: disk I/O error (code 3850)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 02:46:30.901  1758  4038 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:46:30.901  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 02:46:30.902  1758  1758 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-30 02:46:30.904  1709  1735 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjDDF0729ED) - 
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:30.906  1758  4039 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:30.907  1758  4039 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:30.909  1758  4039 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-30 02:46:30.909  1758  4039 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-30 02:46:30.910  1758  4039 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-30 02:46:30.911  1758  4039 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-30 02:46:30.912  1758  4039 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-30 02:46:30.913  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 02:46:30.913  1758  1758 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
--------- beginning of crash
08-30 02:46:30.913  1758  4039 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-30 02:46:30.913  1758  4039 E AndroidRuntime: Process: com.google.android.gms, PID: 1758
08-30 02:46:30.913  1758  4039 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:30.913  1758  4039 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:46:30.936   874  4043 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:46:30.936   874  4043 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:30.936   874  4043 E DropBoxManagerService: 	... 5 more
08-30 02:46:30.941   874  4046 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 02:46:30.942  1866  4027 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 02:46:30.944  1998  4042 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 02:46:30.958  1758  4041 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 02:46:30.959  1758  4041 I Process : Sending signal. PID: 1758 SIG: 9
08-30 02:46:30.961  1944  2475 E ReflectionEngine: Failed to save models
08-30 02:46:30.961  1944  2475 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:30.961  1944  2475 E ReflectionEngine: 	... 16 more
08-30 02:46:30.962  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 02:46:30.963  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 02:46:30.971  1998  4042 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 02:46:30.976   874  4046 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 02:46:30.976   874  4046 I Adreno  : Build Date                       : 10/20/15
08-30 02:46:30.976   874  4046 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 02:46:30.976   874  4046 I Adreno  : Local Branch                     : M14
08-30 02:46:30.976   874  4046 I Adreno  : Remote Branch                    : 
08-30 02:46:30.976   874  4046 I Adreno  : Remote Branch                    : 
08-30 02:46:30.976   874  4046 I Adreno  : Reconstruct Branch               : 
,08-30 02:46:30.980  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 02:46:30.980  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 02:46:30.980  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 02:46:30.980  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 02:46:30.981  1866  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 02:46:30.981  1866  4027 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 02:46:30.981  1866  4027 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 02:46:30.981  1866  4027 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 02:46:30.981  1866  4027 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 02:46:30.981  1866  4027 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-30 02:46:30.982   874  4046 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 02:46:30.987  1709  4030 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-30 02:46:30.988  1709  4030 I Process : Sending signal. PID: 1709 SIG: 9
08-30 02:46:30.990   874  3257 I ActivityManager: Start proc 4048:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-30 02:46:30.998   874  2264 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5515dff)
,08-30 02:46:31.000   874  1319 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:46:31.000   874  1319 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:46:31.009   874  1392 I ActivityManager: Start proc 4062:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-30 02:46:31.014  1998  4042 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-30 02:46:31.014  1998  4042 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 02:46:31.014  1998  4042 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1998
08-30 02:46:31.014  1998  4042 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.014  1998  4042 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: Failed to write the stream file
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(Reflection,ServiceHandler.java:101)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.014  1944  2475 E ObservedEventLogger: 	... 16 more
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: Failed to write the stream file
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 02:46:31.017  1944  2475 E ObservedEventL,ogger: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.017  1944  2475 E ObservedEventLogger: 	... 16 more
08-30 02:46:31.018   874  2263 I ActivityManager: Process com.google.android.gms (pid 1758) has died
08-30 02:46:31.019   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
08-30 02:46:31.019   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-30 02:46:31.020   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-30 02:46:31.020   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
08-30 02:46:31.020   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-30 02:46:31.020   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
08-30 02:46:31.021   874  2263 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
08-30 02:46:31.031   874  4077 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:46:31.031   874  4077 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.031   874  4077 E DropBoxManagerService: 	... 5 more
,08-30 02:46:31.075  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-30 02:46:31.079  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-30 02:46:31.103  4048  4079 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.103  4048  4079 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:46:31.108   280   280 E lowmemorykiller: Error writing /proc/1709/oom_score_adj; errno=22
08-30 02:46:31.112   280   280 E lowmemorykiller: Error writing /proc/1709/oom_score_adj; errno=22
,08-30 02:46:31.119  1998  1998 I HotwordDetector: Closing mic
,08-30 02:46:31.119  1998  2313 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c1109ea
,08-30 02:46:31.119  1998  4020 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-30 02:46:31.104  4048  4079 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 02:46:31.104  4048  4079 E AndroidRuntime: Process: com.android.keychain, PID: 4048
08-30 02:46:31.104  4048  4079 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.104  4048  4079 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:46:31.124   874   874 I ActivityManager: Start proc 4082:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
08-30 02:46:31.129   874  4087 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:46:31.129   874  4087 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.129   874  4087 E DropBoxManagerService: 	... 5 more
,08-30 02:46:31.135  1998  4089 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-30 02:46:31.161  1944  2157 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-30 02:46:31.169   376  4022 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-30 02:46:31.170   376  4022 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-30 02:46:31.173   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 02:46:31.180  1998  4019 I MicroRecognitionRnrImpl: Detection finished
,08-30 02:46:31.180  1998  2319 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-30 02:46:31.183   280   280 E lowmemorykiller: Error writing /proc/1709/oom_score_adj; errno=22
,08-30 02:46:31.190   874  2263 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@bdd8206 attribute=null, token = android.os.BinderProxy@7bdff8a
,08-30 02:46:31.199  1944  2020 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 02:46:31.201   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 02:46:31.202   874   886 E PackageManager: Failed to write settings, restoring backup
08-30 02:46:31.202   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 02:46:31.202   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 02:46:31.202   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 02:46:31.202   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 02:46:31.202   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 02:46:31.202   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.202   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.202   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:31.203   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 02:46:31.203   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 02:46:31.203   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.203   874   887 E DropBoxManagerService: 	... 13 more
,08-30 02:46:31.206  4082  4082 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-30 02:46:31.218   874  1379 I ActivityManager: Start proc 4097:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-30 02:46:31.221  1944  2020 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 02:46:31.221  1944  2020 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-30 02:46:31.221  1944  2020 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.221  1944  2020 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:46:31.226   874  4046 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 02:46:31.226   874  4046 I Adreno  : Build Date                       : 10/20/15
08-30 02:46:31.226   874  4046 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 02:46:31.226   874  4046 I Adreno  : Local Branch                     : M14
08-30 02:46:31.226   874  4046 I Adreno  : Remote Branch                    : 
08-30 02:46:31.226   874  4046 I Adreno  : Remote Branch                    : 
08-30 02:46:31.226   874  4046 I Adreno  : Reconstruct Branch               : 
,08-30 02:46:31.227   874  3256 I ActivityManager: Process android.process.acore (pid 1709) has died
,08-30 02:46:31.227   874  3256 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 20793ms
,08-30 02:46:31.230   874  4109 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:46:31.230   874  4109 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.230   874  4109 E DropBoxManagerService: 	... 5 more
08-30 02:46:31.231   874  1379 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-30 02:46:31.231   874  1379 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 02:46:31.232   874  4046 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:46:31.237   874  1379 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 02:46:31.239   874  1379 I ActivityManager: Killing 1944:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-30 02:46:31.284   874  2263 D GraphicsStats: Buffer count: 2
,08-30 02:46:31.310   874  1379 I ActivityManager: Start proc 4111:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 02:46:31.322   874  1912 W ActivityManager: Spurious death for ProcessRecord{c13eba6 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1944: null
,08-30 02:46:31.325   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-30 02:46:31.325   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-30 02:46:31.325   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-30 02:46:31.325   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-30 02:46:31.325   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-30 02:46:31.325   282   282 E qdoverlay: MdpCtrl close error in unset
,08-30 02:46:31.329   874   892 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-30 02:46:31.347   874   887 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7ff78af u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2d0c089 1998 com.google.android.googlequicksearchbox:search/10028/u0 remote:a925f90}: process crashing
,08-30 02:46:31.362  4111  4111 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 02:46:31.362  4111  4111 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 02:46:31.362  4111  4111 D AndroidRuntime: Shutting down VM
,08-30 02:46:31.368  4111  4111 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:46:31.368  4111  4111 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4111
08-30 02:46:31.368  4111  4111 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 02:46:31.368  4111  4111 E AndroidRuntime: 	... 10 more
08-30 02:46:31.370   874  4124 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:46:31.370   874  4124 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 02:46:31.370   874  4124 E DropBoxManagerService: 	... 5 more
08-30 02:46:31.380   874  3256 I ActivityManager: Start proc 4125:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,08-30 02:46:31.526   282   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 02:46:31.527   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-30 02:46:31.527   282   282 E qdoverlay: MdpCtrl close error in unset

```
