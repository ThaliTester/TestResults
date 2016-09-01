#### Test 835917643a9a586_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system,
09-01 11:31:35.403   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-01 11:31:36.077  3884  3884 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 11:31:36.081  3884  3884 D AndroidRuntime: CheckJNI is OFF
09-01 11:31:36.117  3884  3884 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 11:31:36.160  3884  3884 I Radio-JNI: register_android_hardware_Radio DONE
09-01 11:31:36.179  3884  3884 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-01 11:31:36.187   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 11:31:36.233  2092  2113 W SearchService: Abort, client detached.
09-01 11:31:36.240  3884  3884 D AndroidRuntime: Shutting down VM
09-01 11:31:36.242  2092  2092 I HotwordDetector: Closing mic
09-01 11:31:36.243  2092  2361 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@dc57d76
09-01 11:31:36.243  2092  2369 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-01 11:31:36.256   872  2015 I ActivityManager: Start proc 3893:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-01 11:31:36.304   375  2371 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-01 11:31:36.305   375  2371 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-01 11:31:36.310   375  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-01 11:31:36.311  2092  2364 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-01 11:31:36.312  2092  2368 I MicroRecognitionRnrImpl: Detection finished
09-01 11:31:36.340  3893  3893 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-01 11:31:36.362  3893  3893 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-01 11:31:36.368  3893  3893 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8496-8499)
09-01 11:31:36.368  3893  3893 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:31:36.384  3893  3893 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {580b081}
09-01 11:31:36.385  3893  3893 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:31:36.386  3893  3893 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:31:36.397  3893  3893 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-01 11:31:36.400  3893  3893 E SysUtils: ApplicationContext is null in ApplicationStatus
09-01 11:31:36.421  3893  3893 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-01 11:31:36.435  3893  3893 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:31:36.435  3893  3893 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:31:36.435  3893  3893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:31:36.435  3893  3893 I Adreno  : Build Date                       : 10/20/15
09-01 11:31:36.435  3893  3893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:31:36.435  3893  3893 I Adreno  : Local Branch                     : M14
09-01 11:31:36.435  3893  3893 I Adreno  : Remote Branch                    : 
09-01 11:31:36.435  3893  3893 I Adreno  : Remote Branch                    : 
09-01 11:31:36.435  3893  3893 I Adreno  : Reconstruct Branch               : 
,09-01 11:31:36.503   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7070a67:true
,09-01 11:31:36.555  3893  3893 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 11:31:36.572  3893  3893 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-01 11:31:36.646  3893  3932 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-01 11:31:36.655  3893  3918 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-01 11:31:36.694  3893  3932 I OpenGLRenderer: Initialized EGL, version 1.4
09-01 11:31:36.745   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +503ms
09-01 11:31:36.751  1902  1902 I Keyboard.Facilitator: onFinishInput()
09-01 11:31:36.804  3893  3893 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3893
09-01 11:31:36.892  3893  3893 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-01 11:31:37.053   872  2014 I ActivityManager: Killing 2655:com.google.android.calendar/u0a37 (adj 15): empty #17
09-01 11:31:37.084   872  2014 I ActivityManager: Killing 3187:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-01 11:31:37.093  3893  3934 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1680344784
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-01 11:31:37.101  3893  3934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43f056c added. We now have 1 listener(s)
09-01 11:31:37.106  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-01 11:31:37.107  3893  3934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:31:37.108  3893  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:31:37.108  3893  3934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:31:37.113  3893  3934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54a4d3b added. We now have 1 listener(s)
09-01 11:31:37.113  3893  3934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:31:37.120   872  1313 D WifiService: New client listening to asynchronous messages
09-01 11:31:37.120  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:31:37.121  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 11:31:37.122  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 11:31:37.123  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 11:31:37.123  3893  3934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-01 11:31:37.126  3893  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:37.126  3893  3934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-01 11:31:37.135  3893  3934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:37.136  3893  3934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:37.136  3893  3934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 11:31:37.136  3893  3934 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:31:37.138  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:37.139  3893  3934 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:31:37.140  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:37.337  3893  3893 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-01 11:31:37.973  3893  3941 W jxcore-log: Initializing JXcore engine
09-01 11:31:37.973  3893  3941 W jxcore-log: JXcore engine is ready
09-01 11:31:38.007  3941  3941 W Thread-353: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-01 11:31:38.007  3941  3941 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10733]" dev="sockfs" ino=10733 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-01 11:31:38.007  3941  3941 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-01 11:31:38.007  3941  3941 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27159]" dev="sockfs" ino=27159 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-01 11:31:38.022  3893  3941 W jxcore-log: Starting JXcore engine
09-01 11:31:38.100  3893  3941 W jxcore-log: Platform android
09-01 11:31:38.100  3893  3941 W jxcore-log: 
09-01 11:31:38.100  3893  3941 W jxcore-log: Process ARCH arm
09-01 11:31:38.100  3893  3941 W jxcore-log: 
09-01 11:31:38.288  3893  3941 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:31:38.288  3893  3941 I jxcore-log: 
09-01 11:31:38.289  3893  3941 W jxcore-log: JXcore engine is started
09-01 11:31:38.298  3893  3934 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-01 11:31:38.302  3893  3893 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:31:38.425   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 11:31:41.450   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 11:31:41.774   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-01 11:31:44.477   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 11:31:46.460  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:31:46.465  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:31:46.466  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:31:46.485  1482  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 11:31:46.485  1482  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 11:31:46.485  1482  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 11:31:46.485  1482  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:31:46.498  3645  3645 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 11:31:46.498  3645  3645 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 11:31:46.498  3645  3645 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-01 11:31:47.949  3207  3954 V KeepSync: Connecting to GoogleApiClient
,09-01 11:31:47.950   872  2005 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 11:31:48.058  1482  3137 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-01 11:31:48.058  1482  3137 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-01 11:31:48.058  1482  3137 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:31:48.058  1482  3137 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:31:48.079  1682  3955 V BaseAuthAsyncOperation: access token request failed
,09-01 11:31:48.080  3207  3954 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 11:31:48.166  1482  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-01 11:31:48.166  1482  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-01 11:31:48.167  1482  1498 I GLSUser : [GLSUser] Extracting token using key: Auth,
,09-01 11:31:48.167  1482  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:31:48.203  3207  3954 E KeepSync: IOException
09-01 11:31:48.203  3207  3954 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 11:31:48.203  3207  3954 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 11:31:48.203  3207  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 11:31:48.203  3207  3954 E KeepSync: 	... 10 more
,09-01 11:31:48.203  3207  3954 W KeepSync: Sync result 2
,09-01 11:31:48.217   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 11:31:48.323  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:31:48.323  3893  3941 I jxcore-log: 
,09-01 11:31:48.325  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:31:48.325  3893  3941 I jxcore-log: 
,09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:48.334  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:31:48.336  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:31:48.338  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:31:48.338  3893  3941 I jxcore-log: 
,09-01 11:31:48.340  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:31:48.340  3893  3941 I jxcore-log: 
,09-01 11:31:48.837  3893  3941 D executeNativeTests: Running unit tests
,09-01 11:31:48.896  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:31:48.896  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 added. We now have 2 listener(s)
09-01 11:31:48.897  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:31:48.897  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:31:48.897  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:31:48.898  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:31:48.898  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a added. We now have 2 listener(s)
09-01 11:31:48.898  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:31:48.899  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:31:48.901  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:48.914  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:31:48.920  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:31:48.921  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:31:48.923  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:48.928  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:31:48.930  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:48.933  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 11:31:48.933  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:31:48.934  3893  3941 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 11:31:48.935  3893  3941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:31:48.935  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:31:48.935  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:31:48.935  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:31:48.935  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:48.935  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:48.935  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:48.939  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:48.939  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.939  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:48.939  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:31:48.940  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 removed from the list
,09-01 11:31:48.940  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:48.940  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a removed from the list
09-01 11:31:48.940  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:48.940  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.940  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.940  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.941  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:48.941  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:48.941  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:48.941  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:48.943  3893  3941 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:31:48.944  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:48.944  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:48.944  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:48.944  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:31:48.944  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-01 11:31:48.944  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.944  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:48.944  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 11:31:48.944  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:48.945  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:31:48.945  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.945  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:48.945  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-01 11:31:48.945  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.949  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:48.949  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:48.949  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:48.950  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-01 11:31:48.954  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:31:48.955  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:31:48.956  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:31:48.956  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:48.956  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:48.957  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:48.957  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:48.957  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.957  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.957  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:48.957  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:31:48.957  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:48.957  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:48.957  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.957  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.957  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:48.957  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:48.958  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:48.959  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:48.959  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:48.959  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
,09-01 11:31:48.960  3893  3941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:31:48.962  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:48.970  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:48.972  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:48.972  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:31:48.972  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:31:48.972  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:31:48.972  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:31:48.972  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:48.973  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:31:48.974  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:48.980  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:31:48.980  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:31:48.982  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:48.986  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:31:48.988  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:31:48.989  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:31:48.991  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 11:31:48.994  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 11:31:48.994  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:31:48.994  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:31:48.995  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:31:48.996  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:31:49.002  2841  3032 D BtGatt.GattService: registerClient() - UUID=1efc4db8-5308-47b3-9d1b-ccebe1f9b40d
09-01 11:31:49.003  2841  2860 D BtGatt.GattService: onClientRegistered() - UUID=1efc4db8-5308-47b3-9d1b-ccebe1f9b40d, clientIf=5
09-01 11:31:49.004  3893  3905 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:31:49.004  2841  2852 D BtGatt.GattService: start scan with filters
09-01 11:31:49.009  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:31:49.010  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:31:49.010  2841  2864 D BtGatt.ScanManager: handling starting scan
09-01 11:31:49.010  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:31:49.010  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:31:49.012  2841  2864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:31:49.013  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:31:49.013  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:31:49.013  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:31:49.015  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 11:31:49.017  3893  3941 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:31:49.020  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.020  3893  3941 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:31:49.020  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.020  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:31:49.020  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.020  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:31:49.020  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:31:49.020  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:31:49.020  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:31:49.020  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:31:49.021  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:31:49.021  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:31:49.022  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:31:49.023  2841  3032 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:31:49.023  2841  2852 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:31:49.024  2841  2860 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:31:49.024  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.024  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:31:49.024  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:31:49.024  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:31:49.024  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:31:49.024  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:31:49.025  2841  2864 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 11:31:49.025  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:31:49.026  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:31:49.026  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:31:49.026  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:31:49.027  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:49.027  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.028  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.028  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:31:49.028  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.028  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.028  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:49.028  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.028  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.028  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.028  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.028  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.029  3893  3941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:31:49.031  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:49.038  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:31:49.038  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:49.039  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:49.039  2841  2864 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:31:49.039  2841  2864 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:31:49.041  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.042  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:31:49.043  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:31:49.043  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:31:49.043  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:31:49.043  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:49.043  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:31:49.044  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.048  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:49.049  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:31:49.049  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:31:49.056  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:31:49.057  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:31:49.057  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:31:49.060  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:31:49.060  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:31:49.060  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:31:49.061  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:31:49.064  2841  2853 D BtGatt.GattService: registerClient() - UUID=e5d0562d-b54d-4015-ba22-50f8060cda86
09-01 11:31:49.064  2841  2860 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:31:49.064  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.064  2841  2860 D BtGatt.GattService: onClientRegistered() - UUID=e5d0562d-b54d-4015-ba22-50f8060cda86, clientIf=5
09-01 11:31:49.065  3893  3905 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:31:49.065  2841  3032 D BtGatt.GattService: start scan with filters
09-01 11:31:49.067  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:31:49.068  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:31:49.068  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:31:49.068  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:31:49.071  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:31:49.071  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:31:49.071  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:31:49.072  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 11:31:49.075  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:31:49.075  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.078  3893  3941 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:31:49.081  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.081  3893  3941 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:31:49.081  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.081  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:31:49.081  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.081  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:31:49.082  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:31:49.082  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:31:49.082  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:31:49.082  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:31:49.082  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:31:49.082  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:31:49.083  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:31:49.083  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.083  2841  2864 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:31:49.083  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:31:49.084  2841  2852 D BtGatt.GattService: stopScan() - queue size =0
09-01 11:31:49.085  2841  2989 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:31:49.085  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:31:49.085  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:31:49.085  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:31:49.085  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:31:49.086  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:31:49.088  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:31:49.088  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:31:49.088  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 11:31:49.089  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:31:49.089  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:49.090  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:31:49.090  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.090  2841  2864 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:31:49.091  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:31:49.091  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.091  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:31:49.091  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.092  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.092  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:49.092  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:49.092  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.092  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.093  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.093  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.093  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.093  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.095  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.095  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.095  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.095  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
,09-01 11:31:49.096  2841  2860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:31:49.096  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.097  3893  3941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:31:49.098  2841  2864 D BtGatt.ScanManager: handling starting scan
09-01 11:31:49.098  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:31:49.104  2841  2860 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:31:49.104  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:49.104  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:49.104  2841  2864 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:31:49.107  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:31:49.107  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:31:49.107  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:31:49.108  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:31:49.108  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:31:49.108  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:31:49.108  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:31:49.109  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:31:49.110  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.110  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:49.110  2841  2864 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:31:49.110  2841  2864 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:31:49.111  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.113  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:31:49.113  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:31:49.119  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:31:49.120  2841  2860 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:31:49.120  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.120  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:31:49.120  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:31:49.124  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:31:49.124  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:31:49.124  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:31:49.125  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:31:49.127  2841  3032 D BtGatt.GattService: registerClient() - UUID=f79e8738-cc08-48ae-8a4b-09be00d465e3
,09-01 11:31:49.127  2841  2860 D BtGatt.GattService: onClientRegistered() - UUID=f79e8738-cc08-48ae-8a4b-09be00d465e3, clientIf=5
09-01 11:31:49.127  3893  3903 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:31:49.128  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:31:49.128  2841  2853 D BtGatt.GattService: start scan with filters
09-01 11:31:49.128  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:31:49.131  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:31:49.131  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:31:49.131  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:31:49.132  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:31:49.134  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:31:49.134  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:31:49.134  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:31:49.135  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 11:31:49.135  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:31:49.135  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.136  2841  2864 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:31:49.143  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:31:49.139  3893  3941 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:31:49.144  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.144  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.144  3893  3941 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:31:49.144  2841  2864 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:31:49.144  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.144  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:31:49.145  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.145  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:31:49.145  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:31:49.145  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:31:49.145  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:31:49.145  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:31:49.145  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:31:49.145  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:31:49.146  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:31:49.147  2841  2853 D BtGatt.GattService: stopScan() - queue size =0
,09-01 11:31:49.149  2841  2852 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-01 11:31:49.149  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:31:49.149  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:31:49.150  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:31:49.150  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:31:49.150  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:31:49.152  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:31:49.152  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:31:49.152  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:31:49.152  2841  2860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:31:49.152  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:31:49.152  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:31:49.152  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:31:49.154  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.154  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:31:49.154  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.154  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:31:49.154  3893  3941 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:31:49.154  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.154  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.154  2841  2864 D BtGatt.ScanManager: handling starting scan
09-01 11:31:49.154  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.154  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.154  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:31:49.154  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.154  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.154  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.155  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.155  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.155  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.155  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.156  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.156  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.156  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.156  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
,09-01 11:31:49.157  3893  3941 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 11:31:49.157  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.157  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.158  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.158  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.158  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.158  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.158  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.158  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.158  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.158  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:31:49.158  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.159  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.159  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.159  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.160  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.160  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:31:49.160  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.160  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.161  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:31:49.161  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.161  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.161  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:31:49.161  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:31:49.161  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.162  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.162  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.162  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.162  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.162  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.162  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.162  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.162  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.162  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.163  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.163  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:31:49.163  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.163  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.164  2841  2860 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:31:49.164  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.164  2841  2864 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 11:31:49.164  3893  3941 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:31:49.164  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:31:49.164  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.165  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.165  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.165  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.165  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.165  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:49.165  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.165  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.165  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.165  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.165  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.165  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.165  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.167  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.167  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:31:49.167  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.167  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
,09-01 11:31:49.168  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-01 11:31:49.168  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.168  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.168  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:31:49.168  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.168  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.168  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.168  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:49.168  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:31:49.168  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.168  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.168  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.169  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.169  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.169  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.170  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:31:49.170  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.170  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:31:49.170  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.171  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:31:49.171  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:31:49.171  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:31:49.171  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:31:49.171  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:31:49.171  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:31:49.171  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.172  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.172  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.172  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:31:49.172  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.172  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.172  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.172  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.172  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.172  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.172  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.172  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.172  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.173  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.174  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:31:49.174  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.174  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.175  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.175  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:31:49.175  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:31:49.175  2841  2864 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:31:49.175  2841  2864 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:31:49.176  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:31:49.176  3893  3941 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:31:49.176  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-01 11:31:49.182  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:31:49.182  3893  3941 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 11:31:49.182  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:31:49.183  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:31:49.184  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:31:49.185  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:31:49.185  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:31:49.185  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:31:49.185  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:31:49.186  3893  3941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:31:49.186  3893  3941 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:31:49.186  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-01 11:31:49.186  3893  3941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:31:49.186  3893  3941 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:31:49.186  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:31:49.186  3893  3941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:31:49.186  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 11:31:49.190  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 11:31:49.191  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:31:49.191  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:31:49.191  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:31:49.191  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:31:49.191  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:31:49.192  3893  3941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:31:49.192  3893  3941 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-01 11:31:49.192  3893  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 417)
09-01 11:31:49.193  2841  2860 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:31:49.193  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.193  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.193  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.193  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.193  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.193  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.193  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.193  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:31:49.194  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.194  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.194  3893  3956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:31:49.194  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.194  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.194  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.194  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.194  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.194  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.195  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.195  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.195  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.195  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
,09-01 11:31:49.195  3893  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 417
09-01 11:31:49.195  3893  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 417)
09-01 11:31:49.196  3893  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 417)
09-01 11:31:49.196  3893  3941 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:31:49.196  3893  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 417)
09-01 11:31:49.196  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.196  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.196  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.197  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:31:49.197  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.197  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.197  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:49.197  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.197  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.197  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.197  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.197  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.197  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.197  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.198  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.198  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.198  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.198  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.200  3893  3941 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:31:49.200  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.200  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.200  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:31:49.200  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.200  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.200  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.200  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.200  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.200  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.200  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.200  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.200  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.200  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.200  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.201  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.201  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.201  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.201  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 11:31:49.201  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.201  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:31:49.202  3893  3941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:31:49.202  3893  3941 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:31:49.202  3893  3941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:31:49.202  3893  3941 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:31:49.202  3893  3941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:31:49.202  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:31:49.203  3893  3941 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:31:49.203  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:31:49.203  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.203  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.203  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.203  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.203  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.203  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.203  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.203  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.203  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.203  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.203  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.203  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.203  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.204  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.204  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:31:49.204  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.204  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.205  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.205  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:31:49.205  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.205  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.205  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.205  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.205  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.205  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.205  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.205  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.205  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.205  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.205  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.205  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.205  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.205  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.205  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:31:49.205  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.206  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.206  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.206  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.206  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.206  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.206  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.206  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.206  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.206  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.206  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.206  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.207  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:31:49.207  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.207  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.207  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.208  3893  3941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:31:49.208  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:31:49.209  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:31:49.209  3893  3941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-01 11:31:49.209  3893  3941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:31:49.209  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:31:49.210  3893  3893 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:31:49.210  3893  3893 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:31:49.210  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.210  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:31:49.210  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.210  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.211  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:31:49.211  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.211  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:31:49.211  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:31:49.212  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.212  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.212  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.212  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.212  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.212  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.212  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.212  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.212  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.212  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.212  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:31:49.212  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.213  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.213  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.213  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.214  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.214  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.214  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:31:49.214  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.214  2841  2860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:31:49.214  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.214  2841  2864 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:31:49.215  3893  3941 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 11:31:49.215  3893  3941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:31:49.215  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:31:49.215  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:31:49.216  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.216  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.216  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.216  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.216  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.216  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.216  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.216  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:31:49.216  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.216  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.216  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.216  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.216  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.216  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.217  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.217  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.217  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.217  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.218  3893  3958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:31:49.218  3893  3958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 11:31:49.219  3893  3893 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-01 11:31:49.222  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.222  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.222  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.222  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.222  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.223  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.223  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
09-01 11:31:49.223  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.223  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.223  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.223  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.223  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:31:49.223  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.223  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.223  2841  2860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:31:49.223  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:31:49.223  2841  2864 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:31:49.224  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.224  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.224  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.224  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.224  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:31:49.224  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:31:49.224  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:31:49.225  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:31:49.225  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.225  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.225  3893  3941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd786c5 not in the list
,09-01 11:31:49.225  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.225  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.225  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:31:49.225  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.225  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.225  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:31:49.225  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:31:49.226  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:31:49.226  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:31:49.226  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:31:49.226  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@732981a not in the list
09-01 11:31:49.227  3893  3941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:31:49.227  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-01 11:31:49.227  3893  3941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:31:49.227  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:31:49.227  3893  3941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 11:31:49.227  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:31:49.229  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:31:49.229  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:31:49.229  3893  3941 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:31:49.229  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-01 11:31:49.229  3893  3941 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:31:49.229  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:31:49.229  3893  3941 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:31:49.229  3893  3941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:31:49.230  3893  3941 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:31:49.231  2841  2860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:31:49.231  2841  2860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:31:49.231  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:31:49.231  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b1d96c added. We now have 2 listener(s)
09-01 11:31:49.231  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:31:49.232  3893  3941 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:31:49.233   872  1496 D WifiService: setWifiEnabled: true pid=3893, uid=10000
09-01 11:31:49.233   872  1496 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:31:49.233  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:31:49.233  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@580ab35 added. We now have 3 listener(s)
09-01 11:31:49.233  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:31:49.239  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:31:49.239  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf13bca added. We now have 4 listener(s)
09-01 11:31:49.239  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:31:49.241  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:31:49.241  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2a313b added. We now have 5 listener(s)
09-01 11:31:49.241  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:31:49.242   872  2049 D WifiService: setWifiEnabled: false pid=3893, uid=10000
09-01 11:31:49.242   872  2049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:31:49.246  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:31:49.247  2841  2856 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 11:31:49.247  2841  2856 D BluetoothAdapterProperties: Setting state to 13
,09-01 11:31:49.247  2841  2856 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:31:49.248  2841  2856 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:31:49.248  2841  2856 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:31:49.249  2841  2860 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:31:49.249  2841  2856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21,
09-01 11:31:49.250  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:49.250  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:31:49.250  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.250  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.250  2841  2841 D BluetoothMapService: onReceive
,09-01 11:31:49.251  2841  2841 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:31:49.251  2841  2841 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:31:49.251  2841  2841 D BluetoothMapService: MAP Service closeService in,
,09-01 11:31:49.251  2841  2841 D BluetoothMapMasInstance0: MAP Service shutdown
,09-01 11:31:49.251  2841  2841 D ObexServerSockets0: shutdown(block = true)
09-01 11:31:49.251  2841  2841 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 11:31:49.251  2841  2841 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 11:31:49.252  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:31:49.252  2841  3036 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-01 11:31:49.252  2841  2985 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 11:31:49.252  2841  3035 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-01 11:31:49.253  2841  2841 I BtOppRfcommListener: stopping Accept Thread
,09-01 11:31:49.253  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.254  2841  3592 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 11:31:49.254  2841  3592 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 11:31:49.255  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.257  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:49.257  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:49.258  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-01 11:31:49.258  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:49.259  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 11:31:49.261  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.262  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 11:31:49.263  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:49.264   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:31:49.264   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-01 11:31:49.264   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:31:49.264   872   885 I ActivityManager: Start proc 3961:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-01 11:31:49.264   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:31:49.266  2841  2841 D HeadsetService: Received stop request...Stopping profile...
09-01 11:31:49.267   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 11:31:49.267   872   872 D BluetoothHeadset: Proxy object disconnected
,09-01 11:31:49.267  1368  1393 D BluetoothHeadset: Proxy object disconnected
09-01 11:31:49.268   872   872 D BluetoothHeadset: Proxy object disconnected
,09-01 11:31:49.268  2006  2112 D BluetoothHeadset: Proxy object disconnected
,09-01 11:31:49.270  2841  2841 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:31:49.270  2841  2841 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:31:49.270  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:31:49.270  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.272  1368  1368 D HeadsetProfile: Bluetooth service disconnected
,09-01 11:31:49.273  2841  2841 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 11:31:49.273  2841  2841 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:31:49.273  2841  2860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-01 11:31:49.273  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:31:49.273  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:31:49.273  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:31:49.273  2841  2860 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 11:31:49.274  2841  2841 D A2dpService: Received stop request...Stopping profile...
,09-01 11:31:49.274  2841  3000 D A2dpStateMachine: Exit Disconnected: -1
,09-01 11:31:49.280   872   872 D BluetoothA2dp: Proxy object disconnected
,09-01 11:31:49.282  1368  1368 D BluetoothA2dp: Proxy object disconnected
09-01 11:31:49.284  2841  2841 D HidService: Received stop request...Stopping profile...
,09-01 11:31:49.284  2841  2841 D HidService: Stopping Bluetooth HidService
09-01 11:31:49.284   872  2110 D DhcpClient: Clearing IP address
09-01 11:31:49.284   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:31:49.287  1368  1368 D BluetoothInputDevice: Proxy object disconnected
09-01 11:31:49.287  1368  1368 D HidProfile: Bluetooth service disconnected
09-01 11:31:49.287  2841  2841 D HealthService: Received stop request...Stopping profile...
09-01 11:31:49.288   371   870 D CommandListener: Setting iface cfg
09-01 11:31:49.289  1482  2549 V NativeCrypto: Read error: ssl=0x9ac7f800: I/O error during system call, Connection timed out
09-01 11:31:49.289   872  2116 D DhcpClient: Receive thread stopped
09-01 11:31:49.289  2841  2841 V BluetoothAdapterState: isTurningOff()=true
09-01 11:31:49.289  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.289  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.289  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.290  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:31:49.290  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:31:49.290  1482  2549 V NativeCrypto: SSL shutdown failed: ssl=0x9ac7f800: I/O error during system call, Broken pipe
09-01 11:31:49.291  2841  2953 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:31:49.291  2841  2953 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:31:49.291  2841  2953 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:31:49.291  2841  2953 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:31:49.291  2841  2860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-01 11:31:49.291   872  2015 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-01 11:31:49.294   872  2098 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-01 11:31:49.296   872  2098 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-01 11:31:49.296   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-01 11:31:49.297   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-01 11:31:49.297   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:31:49.299   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
09-01 11:31:49.300   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:31:49.300   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:31:49.300   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-01 11:31:49.300  2841  2841 D PanService: Received stop request...Stopping profile...
09-01 11:31:49.302   401   401 E Parcel  : Reading a NULL string not supported here.
09-01 11:31:49.303   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:31:49.309  2841  2841 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:31:49.310  2841  2841 D BluetoothMapService: stop()
09-01 11:31:49.310  2841  2841 D BluetoothMapAppObserver: deinitObservers()
09-01 11:31:49.310  2841  2841 D BluetoothMapAppObserver: removeReceiver()
,09-01 11:31:49.311  2841  2841 V BluetoothAdapterState: isTurningOff()=true
09-01 11:31:49.311  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.311  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.311  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.313   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 11:31:49.317  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:49.318  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:49.318  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.318  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:31:49.319  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:31:49.319  1368  1368 D PanProfile: Bluetooth service disconnected
09-01 11:31:49.320  1368  1368 D BluetoothMap: Proxy object disconnected
09-01 11:31:49.320  1368  1368 D MapProfile: Bluetooth service disconnected
09-01 11:31:49.320  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:49.320  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:49.320  2841  2841 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:31:49.320  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.320  2841  2860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 11:31:49.320  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:31:49.320  2841  2841 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:31:49.321   872  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 11:31:49.321  2841  2841 V BluetoothAdapterState: isTurningOff()=true
09-01 11:31:49.321  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.321  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.321  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.321  2841  2841 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:31:49.321  2841  2860 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 11:31:49.321  2841  2841 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:31:49.322  2841  2841 V BluetoothAdapterState: isTurningOff()=true
09-01 11:31:49.322  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.322  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.322  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.322  2841  2841 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:31:49.323  2841  2841 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:31:49.325  1850  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:31:49.326   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:31:49.326  2841  2841 D BluetoothMapService: MAP Service closeService in
09-01 11:31:49.326  2841  2841 V BluetoothAdapterState: isTurningOff()=true
09-01 11:31:49.326  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.326  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.326  2841  2841 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:49.327  2841  2856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 11:31:49.327  2841  2856 D BluetoothAdapterProperties: Setting state to 15
09-01 11:31:49.327  2841  2856 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 11:31:49.328  2841  2856 I BluetoothAdapterState: Entering BleOnState
09-01 11:31:49.328  1368  1384 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:31:49.329  1368  2126 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:31:49.330  1368  1393 D BluetoothA2dp: onBluetoothStateChange: up=,false
09-01 11:31:49.330  1368  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:31:49.331   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:31:49.331  1368  2126 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:31:49.331   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:31:49.331  2006  2112 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:31:49.331   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:31:49.331   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:31:49.332  1368  1393 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:31:49.333  2841  2856 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 11:31:49.333  2841  2856 D BluetoothAdapterProperties: Setting state to 16
09-01 11:31:49.333  2841  2856 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 11:31:49.334  2841  2856 D BluetoothAdapterProperties: onBleDisable
09-01 11:31:49.334  2841  2841 D BluetoothMapService: cleanup()
09-01 11:31:49.334  2841  2841 D BluetoothMapService: MAP Service closeService in
09-01 11:31:49.334  2841  2856 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:31:49.334  2841  2857 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 11:31:49.335  2841  2953 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 11:31:49.335  2841  2953 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:31:49.337  2841  2860 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:31:49.338  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:49.339  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:31:49.340  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:49.340  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:31:49.342  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:49.343  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo:, No relevant state changes
09-01 11:31:49.361  3961  3961 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-01 11:31:49.363   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 11:31:49.384   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 11:31:49.385   872  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 11:31:49.385   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:31:49.386   872   889 D Tethering: MasterInitialState.processMessage what=3
09-01 11:31:49.389  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:49.391  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:49.392  3529  3529 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@46735 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-01 11:31:49.399  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:31:49.403   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f89acc:true
,09-01 11:31:49.404  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:31:49.416   872  2053 I ActivityManager: Start proc 3981:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 11:31:49.424  3961  3961 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 11:31:49.426  3961  3961 D BluetoothMap: Create BluetoothMap proxy object
,09-01 11:31:49.434  3961  3961 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 11:31:49.439   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-01 11:31:49.440   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 11:31:49.448  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 11:31:49.453  3961  3961 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:31:49.459   872  2049 I ActivityManager: Killing 3331:com.google.android.gm/u0a78 (adj 15): empty #17
,09-01 11:31:49.536  2841  2860 I bt_hci  : shut_down
,09-01 11:31:49.537  2841  2865 D bt_hwcfg: hw_epilog_process
,09-01 11:31:49.538  2841  2865 I bt_vendor: low_power_mode_cb
,09-01 11:31:49.562  2841  2865 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-01 11:31:49.562  2841  2865 I bt_vendor: epilog_cb
09-01 11:31:49.562  2841  2865 I bt_hci  : epilog_finished_callback
,09-01 11:31:49.565  2841  2860 I bt_hci_h4: hal_close
,09-01 11:31:49.565  2841  2860 I bt_userial_vendor: device fd = 51 close
,09-01 11:31:49.617  3981  3981 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.617  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=46 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:31:49.618  3981  3981 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:31:49.618  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:31:49.685   872  2028 I ActivityManager: Start proc 4012:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-01 11:31:49.686   872  2028 I ActivityManager: Killing 3529:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-01 11:31:49.712  3893  3893 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:31:49.742  2841  2857 D bt_stack_manager: event_shut_down_stack finished.
,09-01 11:31:49.743  2841  2856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 11:31:49.745  2841  2856 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-01 11:31:49.745  2841  2841 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:31:49.746  2841  2841 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:31:49.746  2841  2841 D BtGatt.GattService: stop()
,09-01 11:31:49.746  2841  2841 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:31:49.748  2841  2841 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:31:49.749  2841  2841 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:49.749  2841  2841 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:49.749  2841  2841 V BluetoothAdapterState: isBleTurningOff()=true
,09-01 11:31:49.750  2841  2856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-01 11:31:49.750  2841  2856 D BluetoothAdapterProperties: Setting state to 10
,09-01 11:31:49.751  2841  2856 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-01 11:31:49.752  2841  2856 I BluetoothAdapterState: Entering OffState
,09-01 11:31:49.752   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-01 11:31:49.758  4012  4012 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-01 11:31:49.766  2841  2841 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-01 11:31:49.766  2841  2841 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 11:31:49.766  2841  2841 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:31:49.767  2841  2857 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 11:31:49.768  2841  2857 D bt_stack_manager: event_clean_up_stack finished.
,09-01 11:31:49.772  2841  2841 I art     : System.exit called, status: 0
,09-01 11:31:49.772  2841  2841 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 11:31:49.840  4012  4012 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-01 11:31:49.862   872  2054 I ActivityManager: Process com.android.bluetooth (pid 2841) has died
,09-01 11:31:49.910  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:31:49.929   872  1395 I ActivityManager: Start proc 4039:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-01 11:31:49.935  3961  3961 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:31:49.951  3981  4009 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 11:31:50.011   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b316f2c:true
,09-01 11:31:50.017  4039  4039 D AdapterServiceConfig: Adding HeadsetService
,09-01 11:31:50.018  4039  4039 D AdapterServiceConfig: Adding A2dpService
,09-01 11:31:50.019  4039  4039 D AdapterServiceConfig: Adding HidService
,09-01 11:31:50.019  4039  4039 D AdapterServiceConfig: Adding HealthService
,09-01 11:31:50.020  4039  4039 D AdapterServiceConfig: Adding PanService
,09-01 11:31:50.020  4039  4039 D AdapterServiceConfig: Adding GattService
09-01 11:31:50.020  4039  4039 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 11:31:50.024   872  1395 I ActivityManager: Killing 3417:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-01 11:31:50.084  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:31:50.106  1682  1682 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:31:50.113  1682  1682 D SystemUpdateService: onCreate
,09-01 11:31:50.123  1682  1682 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 11:31:50.128  1682  4052 I SystemUpdateService: active receiver: enabled
,09-01 11:31:50.139  1682  4052 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:31:50.141  1682  4052 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-01 11:31:50.141  1682  4052 I SystemUpdateService: now status is 0 (complete)
,09-01 11:31:50.141  1682  4052 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:31:50.142  1682  4052 I SystemUpdateService: file has been verified
09-01 11:31:50.142  1682  4052 I SystemUpdateService: OTA package size = 12249756
09-01 11:31:50.143  1682  4052 I SystemUpdateService: showing system update notification
,09-01 11:31:50.156  1682  1682 D SystemUpdateService: onDestroy
,09-01 11:31:50.167  1682  1682 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 11:31:50.170  1682  2527 I iu.UploadsManager: num queued entries: 0
,09-01 11:31:50.170  1682  2527 I iu.UploadsManager: num updated entries: 0
09-01 11:31:50.171  1682  2527 I iu.SyncManager: NEXT; no task
,09-01 11:31:50.174  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:31:50.176  1682  1682 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:31:50.191   872  2005 I ActivityManager: Start proc 4054:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 11:31:50.228  4054  4054 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-01 11:31:50.231  4054  4054 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:31:50.236  4054  4054 D SprintDMHelper: simOperator: 
09-01 11:31:50.236  4054  4054 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:31:50.252   872  1967 I ActivityManager: Start proc 4066:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 11:31:50.252   872  1967 I ActivityManager: Killing 1701:android.process.acore/u0a5 (adj 15): empty #17
,09-01 11:31:50.431   872  1967 I ActivityManager: Start proc 4081:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-01 11:31:50.436  2802  4080 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-01 11:31:50.439   872   883 I ActivityManager: Killing 3750:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-01 11:31:50.507  4081  4081 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-01 11:31:50.565  4081  4081 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 11:31:50.565  4081  4081 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 11:31:50.565  4081  4081 I GAv4    :   adb logcat -s GAv4
,09-01 11:31:50.583  4081  4081 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:31:50.593  4081  4081 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:31:50.623  4081  4098 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:31:50.729  4081  4081 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-01 11:31:50.770  4081  4081 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-01 11:31:50.778  4081  4081 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2906-2908)
09-01 11:31:50.778  4081  4081 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:31:50.791  4081  4081 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19e87a5}
,09-01 11:31:50.792  4081  4081 I LibraryLoader: Expected native library version number "",actual native library version number "",
,09-01 11:31:50.793  4081  4081 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 11:31:50.801  4081  4081 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 11:31:50.803  4081  4081 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 11:31:50.820  4081  4081 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 11:31:50.832  4081  4081 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 11:31:50.832  4081  4081 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 11:31:50.832  4081  4081 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:31:50.832  4081  4081 I Adreno  : Build Date                       : 10/20/15
09-01 11:31:50.832  4081  4081 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:31:50.832  4081  4081 I Adreno  : Local Branch                     : M14
09-01 11:31:50.832  4081  4081 I Adreno  : Remote Branch                    : 
09-01 11:31:50.832  4081  4081 I Adreno  : Remote Branch                    : 
09-01 11:31:50.832  4081  4081 I Adreno  : Reconstruct Branch               : 
,09-01 11:31:50.896  4081  4081 I NSApplication: Starting up...
,09-01 11:31:50.909  4081  4127 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 11:31:50.931   872  2005 I ActivityManager: Start proc 4132:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-01 11:31:50.932   872  2005 I ActivityManager: Killing 3763:com.android.musicfx/u0a18 (adj 15): empty #17
,09-01 11:31:51.012  4132  4132 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-01 11:31:51.214   872  1967 I ActivityManager: Killing 3557:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-01 11:31:52.255   872  2015 D WifiService: setWifiEnabled: true pid=3893, uid=10000
,09-01 11:31:52.256   872  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:31:52.273   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-01 11:31:52.280  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:52.280  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:31:52.281  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:52.281  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:31:52.284  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:52.284  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:31:52.285  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:52.285  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:31:52.301   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-01 11:31:52.302   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 11:31:52.303   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 11:31:52.304   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 11:31:52.304   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-01 11:31:52.305   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-01 11:31:52.305   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 11:31:52.325   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 11:31:52.326   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=11.50 delta 1000 -> 994
,09-01 11:31:52.327   371   870 D CommandListener: Setting iface cfg
,09-01 11:31:52.328   872  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-01 11:31:52.328   872  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 11:31:52.338   872  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 11:31:52.338   872  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 11:31:52.339   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-01 11:31:52.339   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:31:52.367   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 11:31:52.441   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 11:31:52.445  1422  1422 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 11:31:52.875  1422  1422 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:31:52.913  1422  1422 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 11:31:52.914  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 11:31:52.922   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:31:52.933   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:31:52.933   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:31:52.934   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 11:31:52.952   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:31:52.963   371   870 D CommandListener: Setting iface cfg
09-01 11:31:52.964   872  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-01 11:31:52.978   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 11:31:52.979   872  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-01 11:31:52.980   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 11:31:53.003   872  4157 D DhcpClient: Receive thread started
,09-01 11:31:53.087   872  1310 E native  : do suspend false
,09-01 11:31:53.110   872  2110 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 11:31:53.123   872  4157 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,09-01 11:31:53.125   872  2110 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,09-01 11:31:53.133   872  2110 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 11:31:53.145   872  4157 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 11:31:53.145   872  2110 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 11:31:53.149   371   870 D CommandListener: Setting iface cfg
,09-01 11:31:53.154   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 11:31:53.158   872  2110 D DhcpClient: Scheduling renewal in 86399s
,09-01 11:31:53.168   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 11:31:53.169   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 11:31:53.171   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:31:53.172   872  1314 D ConnectivityService: Adding iface wlan0 to network 101
,09-01 11:31:53.180   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 11:31:53.223   872  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 11:31:53.223   872  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-01 11:31:53.225   872  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-01 11:31:53.226   872  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-01 11:31:53.228   872  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-01 11:31:53.249   872  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 11:31:53.255   872  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-01 11:31:53.255   872  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-01 11:31:53.255   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-01 11:31:53.256   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 11:31:53.256   872  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-01 11:31:53.256   872  1314 D ConnectivityService:    accepting network in place of null
09-01 11:31:53.258   872  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:31:53.269   872  4156 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135399, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 11:31:53.313   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:31:53.356   872  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.86,2a00:1450:400d:802::200e
,09-01 11:31:53.364   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:31:53.370   872  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:31:53.370   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:31:53.374   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:31:53.379   872  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-01 11:31:53.386  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:53.387  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:53.387  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:53.387  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:53.393  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:31:53.393  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:31:53.393  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:53.393  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:31:53.399  1682  1682 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:31:53.405  1682  1682 D SystemUpdateService: onCreate
,09-01 11:31:53.408   872  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:31:53 GMT], X-Android-Received-Millis=[1472722313407], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472722313400]}
,09-01 11:31:53.409   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 11:31:53.409   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-01 11:31:53.409   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:31:53.409  1682  1682 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-01 11:31:53.410   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 11:31:53.414  1682  4168 I SystemUpdateService: active receiver: enabled
,09-01 11:31:53.417  1682  4168 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:31:53.421  1682  4168 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 11:31:53.421  1682  4168 I SystemUpdateService: now status is 0 (complete)
09-01 11:31:53.421  1682  4168 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:31:53.421  1682  4168 I SystemUpdateService: file has been verified
09-01 11:31:53.422  1682  4168 I SystemUpdateService: OTA package size = 12249756
,09-01 11:31:53.428  1682  4168 I SystemUpdateService: showing system update notification
,09-01 11:31:53.435  1682  1682 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 11:31:53.441  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 11:31:53.441  1682  4174 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-01 11:31:53.441  1682  4174 W BaseAppContext: Using Auth Proxy for data requests.
09-01 11:31:53.443  1682  1682 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 11:31:53.443  1682  4174 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
09-01 11:31:53.443  1682  2527 I iu.UploadsManager: num queued entries: 0
09-01 11:31:53.444  1682  2527 I iu.UploadsManager: num updated entries: 0
09-01 11:31:53.444  1682  2527 I iu.SyncManager: NEXT; no task
09-01 11:31:53.446  4054  4054 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:31:53.449  4054  4054 D SprintDMHelper: simOperator: 
09-01 11:31:53.449  4054  4054 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:31:53.452  1682  1682 D SystemUpdateService: onDestroy
,09-01 11:31:53.458  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:31:53.460  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:31:53.502  1482  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 11:31:53.503  1482  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-01 11:31:53.503  1482  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:31:53.503  1482  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:31:53.516  1682  4174 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-01 11:31:53.546  1482  1493 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 11:31:53.546  1482  1493 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 11:31:53.547  1482  1493 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:31:53.547  1482  1493 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-01 11:31:53.556  3172  4171 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 11:31:53.556  3172  4171 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jdm.a(PG:82)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jcs.o(PG:406)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jcn.a(PG:1379)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jcs.i(PG:143)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at blb.a(PG:3937)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at czp.a(PG:18188)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at czp.a(PG:9081)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at czq.run(PG:1686)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:31:53.556  3172  4171 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jdj.a(PG:4091)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jdj.a(PG:1125)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jdm.a(PG:77)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	... 12 more
09-01 11:31:53.556  3172  4171 E HttpOperation: Caused by: faj: BadAuthentication
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at fal.a(PG:38)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	at jdj.a(PG:4089)
09-01 11:31:53.556  3172  4171 E HttpOperation: 	... 14 more
,09-01 11:31:53.593  1482  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 11:31:53.593  1482  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-01 11:31:53.593  1482  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 11:31:53.593  1482  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:31:53.606  3172  4171 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 11:31:53.606  3172  4171 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jdm.a(PG:82)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jcs.o(PG:406)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jcn.a(PG:1379)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jcs.i(PG:143)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at hec.a(PG:42)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at hee.a(PG:102)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at czr.a(PG:65)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at kka.a(PG:108)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at czp.a(PG:19176)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at czp.a(PG:9081)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at czq.run(PG:1686)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:31:53.606  3172  4171 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jdj.a(PG:4091)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jdj.a(PG:1125)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jdm.a(PG:77)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	... 15 more
09-01 11:31:53.606  3172  4171 E HttpOperation: Caused by: faj: BadAuthentication
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at fal.a(PG:38)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	at jdj.a(PG:4089)
09-01 11:31:53.606  3172  4171 E HttpOperation: 	... 17 more
,09-01 11:31:53.607  3172  4171 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 11:31:53.607  3172  4171 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
,09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at hec.a(PG:42)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at hee.a(PG:102)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at czr.a(PG:65)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at kka.a(PG:108)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at czp.a(PG:9081)
,09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	... 15 more,
09-01 11:31:53.607  3172  4171 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at fal.a(PG:38)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 11:31:53.607  3172  4171 E ExperimentLoader: 	... 17 more
,09-01 11:31:53.613  2802  4176 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 11:31:53.724   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 132149, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 11:31:54.371   872  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-01 11:31:55.021   872  1967 I ActivityManager: Killing 3788:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-01 11:31:55.263   872  1496 D WifiService: setWifiEnabled: false pid=3893, uid=10000
,09-01 11:31:55.264   872  1496 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:31:55.292  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 11:31:55.295   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 11:31:55.295   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-01 11:31:55.295   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:31:55.295   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:31:55.312   872  2110 D DhcpClient: Clearing IP address
,09-01 11:31:55.312   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:31:55.317   371   870 D CommandListener: Setting iface cfg
,09-01 11:31:55.326  1482  4183 V NativeCrypto: Read error: ssl=0x9ab3e000: I/O error during system call, Connection timed out
,09-01 11:31:55.329  1482  4183 V NativeCrypto: SSL shutdown failed: ssl=0x9ab3e000: I/O error during system call, Broken pipe
09-01 11:31:55.331   872  2058 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-01 11:31:55.331   872  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-01 11:31:55.331   872  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.86,2a00:1450:400d:802::200e
09-01 11:31:55.334   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:31:55.334   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-01 11:31:55.338   401   401 E Parcel  : Reading a NULL string not supported here.
,09-01 11:31:55.339   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
09-01 11:31:55.340   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:31:55.344   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:31:55.348   872  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-01 11:31:55.350   872  4157 D DhcpClient: Receive thread stopped
,09-01 11:31:55.356   872  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-01 11:31:55.356   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:31:55.361  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-01 11:31:55.361  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:31:55.361  1850  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:31:55.361  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:55.362  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:31:55.363   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:31:55.365  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:55.365  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:31:55.366  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:31:55.366  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:31:55.393   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:31:55.421   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:31:55.422   872  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-01 11:31:55.422   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:31:55.425   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:31:55.441  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:55.442  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:55.450  1682  1682 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:31:55.454  1682  1682 D SystemUpdateService: onCreate
,09-01 11:31:55.456  1682  1682 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 11:31:55.470  1682  4192 I SystemUpdateService: active receiver: enabled
,09-01 11:31:55.476  1682  4192 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:31:55.478  1682  1682 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 11:31:55.480  1682  2527 I iu.UploadsManager: num queued entries: 0
,09-01 11:31:55.484  1682  4192 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-01 11:31:55.484  1682  4192 I SystemUpdateService: now status is 0 (complete)
09-01 11:31:55.484  1682  4192 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:31:55.484  1682  4192 I SystemUpdateService: file has been verified
09-01 11:31:55.485  1682  4192 I SystemUpdateService: OTA package size = 12249756
,09-01 11:31:55.487  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:31:55.488  1682  1682 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:31:55.481  1682  2527 I iu.UploadsManager: num updated entries: 0
,09-01 11:31:55.490  4054  4054 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:31:55.494  4054  4054 D SprintDMHelper: simOperator: 
,09-01 11:31:55.494  4054  4054 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:31:55.497   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-01 11:31:55.498   872  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-01 11:31:55.498   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 11:31:55.521  2802  4196 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 11:31:55.525  1682  2527 I iu.SyncManager: NEXT; no task
,09-01 11:31:55.541  1682  4192 I SystemUpdateService: showing system update notification
,09-01 11:31:55.580  1682  1682 D SystemUpdateService: onDestroy
,09-01 11:31:58.305   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@127c868:true
,09-01 11:31:58.305  4039  4039 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 11:31:58.310  4039  4039 I bt_bluedroid: init
,09-01 11:31:58.311  4039  4199 I BluetoothAdapterState: Entering OffState
,09-01 11:31:58.316  4039  4200 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 11:31:58.317  4039  4200 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:31:58.317  4039  4200 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 11:31:58.318  4039  4200 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 11:31:58.319  4039  4039 I bt_bluedroid: get_profile_interface socket
09-01 11:31:58.322  4039  4039 I bt_bluedroid: get_profile_interface sdp
,09-01 11:31:58.325  4039  4203 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:31:58.327  4039  4050 I bt_bluedroid: config_hci_snoop_log
09-01 11:31:58.328  4039  4203 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:31:58.332   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 11:31:58.341  4039  4199 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 11:31:58.341  4039  4199 D BluetoothAdapterProperties: Setting state to 14
,09-01 11:31:58.342  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 11:31:58.346  4039  4199 D BluetoothBondStateMachine: make
,09-01 11:31:58.352  4039  4205 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 11:31:58.360  4039  4039 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 11:31:58.361  4039  4199 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:31:58.363  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:31:58.364  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:31:58.364  4039  4039 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:31:58.365  4039  4039 D BtGatt.GattService: start()
09-01 11:31:58.365  4039  4039 I bt_bluedroid: get_profile_interface gatt
,09-01 11:31:58.365  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:31:58.366  4039  4039 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:31:58.374  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:31:58.374  4039  4039 V BluetoothAdapterState: isTurningOn()=false
09-01 11:31:58.374  4039  4039 V BluetoothAdapterState: isBleTurningOn()=true
,09-01 11:31:58.374  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:58.374  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-01 11:31:58.374  4039  4199 I bt_bluedroid: enable
09-01 11:31:58.375  4039  4200 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 11:31:58.375  4039  4200 I bt_hci  : start_up
,09-01 11:31:58.382  4039  4200 I bt_vendor: alloc value 0xb39b9189
,09-01 11:31:58.382  4039  4200 I bt_vendor: init
09-01 11:31:58.383  4039  4200 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-01 11:31:58.383  4039  4200 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 11:31:58.491  4039  4200 D bt_hci  : start_up starting async portion
09-01 11:31:58.492  4039  4208 I bt_hci  : event_finish_startup
09-01 11:31:58.492  4039  4208 I bt_hci_h4: hal_open
09-01 11:31:58.492  4039  4208 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 11:31:58.501  4039  4208 I bt_userial_vendor: device fd = 51 open
,09-01 11:31:58.533  4039  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:31:58.565  4039  4208 D bt_hwcfg: Chipset BCM4354A2
,09-01 11:31:58.565  4039  4208 D bt_hwcfg: Target name = [BCM4354A2]
,09-01 11:31:58.566  4039  4208 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 11:31:59.240  4039  4208 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 11:31:59.242  4039  4208 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 11:31:59.242  4039  4208 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 11:31:59.359  4039  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:31:59.360  4039  4208 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 11:31:59.389  4039  4208 I bt_hwcfg: vendor lib fwcfg completed
,09-01 11:31:59.390  4039  4208 I bt_vendor: firmware callback
,09-01 11:31:59.390  4039  4208 I bt_hci  : firmware_config_callback
,09-01 11:31:59.401  4039  4212 I bt_btu  : btu_task pending for preload complete event
,09-01 11:31:59.401  4039  4212 I bt_btu_task: Bluetooth chip preload is complete
,09-01 11:31:59.402  4039  4212 I bt_btu  : btu_task received preload complete event
,09-01 11:31:59.414  4039  4212 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 11:31:59.415  4039  4212 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:31:59.415  4039  4212 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 11:31:59.415  4039  4212 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:31:59.416  4039  4212 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:31:59.416  4039  4212 I         : BTE_InitTraceLevels -- TRC_A2D
,09-01 11:31:59.416  4039  4212 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:31:59.417  4039  4212 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:31:59.417  4039  4212 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:31:59.417  4039  4212 I         : BTE_InitTraceLevels -- TRC_PAN
,09-01 11:31:59.417  4039  4212 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:31:59.418  4039  4212 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 11:31:59.418  4039  4212 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:31:59.418  4039  4212 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:31:59.418  4039  4212 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 11:31:59.553  4039  4212 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,09-01 11:31:59.553  4039  4212 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,09-01 11:31:59.564  4039  4203 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 11:31:59.565  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 11:31:59.566  4039  4203 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:31:59.569  4039  4203 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:31:59.573  4039  4203 D BluetoothAdapterProperties: Scan Mode:20
,09-01 11:31:59.573  4039  4203 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:31:59.574  4039  4203 D bt_hci  : do_postload posting postload work item
,09-01 11:31:59.575  4039  4208 I bt_hci  : event_postload
,09-01 11:31:59.575  4039  4208 I bt_vendor: sco_config_cb
09-01 11:31:59.575  4039  4208 I bt_hci  : sco_config_callback postload finished.
,09-01 11:31:59.578  4039  4203 D bt_bte_conf: Device ID record 1 : primary
,09-01 11:31:59.578  4039  4203 D bt_bte_conf:   vendorId            = 000f
,09-01 11:31:59.578  4039  4203 D bt_bte_conf:   vendorIdSource      = 0001
09-01 11:31:59.578  4039  4203 D bt_bte_conf:   product             = 1200
,09-01 11:31:59.579  4039  4203 D bt_bte_conf:   version             = 1436
,09-01 11:31:59.579  4039  4203 D bt_bte_conf:   clientExecutableURL = 
,09-01 11:31:59.579  4039  4203 D bt_bte_conf:   serviceDescription  = 
,09-01 11:31:59.579  4039  4203 D bt_bte_conf:   documentationURL    = 
09-01 11:31:59.580  4039  4203 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-01 11:31:59.580  4039  4200 D bt_stack_manager: event_start_up_stack finished
,09-01 11:31:59.581  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:59.583  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-01 11:31:59.583  4039  4199 D BluetoothAdapterProperties: Setting state to 15
09-01 11:31:59.583  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 11:31:59.583  4039  4208 I bt_vendor: low_power_mode_cb,
09-01 11:31:59.585  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:59.587  4039  4199 I BluetoothAdapterState: Entering BleOnState
,09-01 11:31:59.592  4039  4199 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 11:31:59.592  4039  4199 D BluetoothAdapterProperties: Setting state to 11,
09-01 11:31:59.593  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 11:31:59.603  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:31:59.605  4039  4039 D HeadsetService: Received start request. Starting profile...
,09-01 11:31:59.614  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:59.617  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:59.619  4039  4039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 11:31:59.620  4039  4039 D HeadsetStateMachine: make
,09-01 11:31:59.627  4039  4199 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:31:59.632  4039  4039 D HeadsetStateMachine: max_hf_connections = 1
,09-01 11:31:59.633  4039  4039 I bt_bluedroid: get_profile_interface handsfree
09-01 11:31:59.633  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-01 11:31:59.633  4039  4203 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 11:31:59.637  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:31:59.638  4039  4039 D A2dpService: Received start request. Starting profile...
,09-01 11:31:59.639  4039  4039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:31:59.639  4039  4039 I bt_bluedroid: get_profile_interface avrcp
,09-01 11:31:59.645  4039  4039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:31:59.645  4039  4039 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:31:59.646  4039  4039 D A2dpStateMachine: make
,09-01 11:31:59.647  4039  4039 I bt_bluedroid: get_profile_interface a2dp
,09-01 11:31:59.648  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 11:31:59.650  4039  4220 D A2dpStateMachine: Enter Disconnected: -2
,09-01 11:31:59.651  4039  4039 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 11:31:59.652  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:31:59.653  4039  4039 D HidService: Received start request. Starting profile...
09-01 11:31:59.653  4039  4039 I bt_bluedroid: get_profile_interface hidhost
09-01 11:31:59.653  3961  3961 D BluetoothInputDevice: Proxy object connected
09-01 11:31:59.654  4039  4203 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
,09-01 11:31:59.654  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-01 11:31:59.654  4039  4039 D HidService: setHidService(): set to: null
09-01 11:31:59.654  3961  3961 D HidProfile: Bluetooth service connected
09-01 11:31:59.656  4039  4039 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 11:31:59.656  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:31:59.657  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:31:59.658  4039  4039 D HealthService: Received start request. Starting profile...
,09-01 11:31:59.659  4039  4039 I bt_bluedroid: get_profile_interface health
,09-01 11:31:59.660  4039  4039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:31:59.661  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:31:59.662  3961  3961 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:31:59.662  4039  4039 D PanService: Received start request. Starting profile...
09-01 11:31:59.662  4039  4039 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-01 11:31:59.663  4039  4039 I bt_bluedroid: get_profile_interface pan
09-01 11:31:59.663  3961  3961 D PanProfile: Bluetooth service connected
09-01 11:31:59.663  4039  4203 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 11:31:59.665  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:31:59.667  3961  3961 D BluetoothMap: Proxy object connected
,09-01 11:31:59.667  4039  4039 D BluetoothMapService: Received start request. Starting profile...
09-01 11:31:59.667  4039  4039 D BluetoothMapService: start()
09-01 11:31:59.667  3961  3961 D MapProfile: Bluetooth service connected
,09-01 11:31:59.667  3961  3961 D BluetoothMap: getConnectedDevices()
,09-01 11:31:59.668  3961  3961 D BluetoothMap: Bluetooth is Not enabled
09-01 11:31:59.669  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 11:31:59.670  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 11:31:59.670  4039  4039 D BluetoothMapAppObserver: createReceiver()
,09-01 11:31:59.671  4039  4039 D BluetoothMapAppObserver: initObservers()
09-01 11:31:59.671  4039  4039 D BluetoothMapAppObserver: getEnabledAccountItems(),
09-01 11:31:59.679  4039  4039 V BluetoothAdapterState: isTurningOff()=false
09-01 11:31:59.679  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:31:59.679  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:59.679  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:31:59.681  4039  4218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isTurningOff()=false
09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isTurningOff()=false
09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:31:59.682  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:31:59.683  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:31:59.684  4039  4039 V BluetoothAdapterState: isTurningOff()=false
09-01 11:31:59.684  4039  4039 V BluetoothAdapterState: isTurningOn()=true
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isTurningOn()=true
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isTurningOff()=false
09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:31:59.685  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:31:59.686  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:31:59.686  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 11:31:59.686  4039  4199 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:31:59.686  4039  4199 D BluetoothAdapterProperties: State =  11
,09-01 11:31:59.686  4039  4199 D BluetoothAdapterProperties: Setting state to 12
09-01 11:31:59.687  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:31:59.687  4039  4199 I BluetoothAdapterState: Entering OnState
09-01 11:31:59.688  3961  3973 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:31:59.688  4039  4203 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:31:59.689  1368  1384 D BluetoothPan: onBluetoothStateChange on: true
,09-01 11:31:59.689  4039  4203 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:31:59.690  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:31:59.690  1368  1368 D PanProfile: Bluetooth service connected
09-01 11:31:59.691  1368  2126 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:59.692  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:31:59.694  1368  1368 D BluetoothMap: Proxy object connected
09-01 11:31:59.694  1368  1368 D MapProfile: Bluetooth service connected
09-01 11:31:59.694  1368  1368 D BluetoothMap: getConnectedDevices()
09-01 11:31:59.694  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:31:59.695  1368  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:31:59.697  1368  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 11:31:59.698  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:31:59.699  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:31:59.699  1368  1368 D BluetoothInputDevice: Proxy object connected
09-01 11:31:59.699  1368  1368 D HidProfile: Bluetooth service connected
09-01 11:31:59.699   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:31:59.699  3961  3972 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:31:59.700  3961  3973 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:31:59.700  4039  4039 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 11:31:59.701  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:31:59.701  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:31:59.701  1368  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:31:59.702   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:31:59.702  2006  2021 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:31:59.703  3961  3972 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:31:59.703   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:31:59.703   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:31:59.704  1368  2126 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:31:59.704  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:31:59.705  4039  4039 D ObexServerSockets: Succeed to create listening sockets 
09-01 11:31:59.705  4039  4039 D ObexServerSockets0: startAccept()
09-01 11:31:59.705  4039  4039 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:31:59.706   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 11:31:59.707  4039  4039 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 11:31:59.708  4039  4226 D ObexServerSockets0: Accepting socket connection...
,09-01 11:31:59.709  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:31:59.709  4039  4039 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 11:31:59.709  4039  4227 D ObexServerSockets0: Accepting socket connection...
,09-01 11:31:59.710   872   872 D BluetoothA2dp: Proxy object connected
,09-01 11:31:59.710  1368  1368 D BluetoothA2dp: Proxy object connected
09-01 11:31:59.710  4039  4039 D BluetoothMapService: onReceive
09-01 11:31:59.710  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:31:59.711  4039  4039 D BluetoothMapService: STATE_ON
09-01 11:31:59.711  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:31:59.713  3961  3961 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-01 11:31:59.717  3961  3961 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-01 11:31:59.723  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:31:59.726  3961  3961 D BluetoothA2dp: Proxy object connected
,09-01 11:31:59.731  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:31:59.735  3961  3961 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:31:59.740  3961  3961 D BluetoothPbap: Proxy object connected
,09-01 11:31:59.741  1368  1368 D BluetoothPbap: Proxy object connected
09-01 11:31:59.741  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:31:59.741  3961  3961 D PbapServerProfile: Bluetooth service connected
09-01 11:31:59.741  4039  4039 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:31:59.742  1368  1368 D PbapServerProfile: Bluetooth service connected
,09-01 11:31:59.752  4039  4234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:31:59.770  4039  4238 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:31:59.772  4039  4238 I BtOppRfcommListener: Accept thread started.
,09-01 11:31:59.803   872   872 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.803   872   872 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.804  2006  2112 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.804  1368  2126 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.805  1368  1368 D HeadsetProfile: Bluetooth service connected
,09-01 11:31:59.805   872   872 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.806  2006  2020 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.806   872   889 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.821  3961  3973 D BluetoothHeadset: Proxy object connected
,09-01 11:31:59.822  3961  3961 D HeadsetProfile: Bluetooth service connected
,09-01 11:32:01.261   872  1314 D ConnectivityService: handlePromptUnvalidated 101
,09-01 11:32:01.284  4039  4199 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 11:32:01.285  4039  4199 D BluetoothAdapterProperties: Setting state to 13
,09-01 11:32:01.285  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 11:32:01.287  4039  4199 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 11:32:01.290  4039  4199 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:32:01.294  4039  4203 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:32:01.295  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-01 11:32:01.301  4039  4039 D BluetoothMapService: onReceive
,09-01 11:32:01.302  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:32:01.302  4039  4039 D BluetoothMapService: STATE_TURNING_OFF
,09-01 11:32:01.303  4039  4039 D BluetoothMapService: MAP Service closeService in
,09-01 11:32:01.303  4039  4039 D BluetoothMapMasInstance0: MAP Service shutdown
,09-01 11:32:01.304  4039  4039 D ObexServerSockets0: shutdown(block = true)
,09-01 11:32:01.306  4039  4226 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-01 11:32:01.309  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:01.309  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:32:01.311  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:32:01.312  4039  4227 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 11:32:01.313  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:32:01.313  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:32:01.313  4039  4214 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 11:32:01.314  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:32:01.315  4039  4039 I BtOppRfcommListener: stopping Accept Thread
09-01 11:32:01.315  4039  4238 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:32:01.318  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:32:01.322  4039  4238 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:32:01.323  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:01.323  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:32:01.326  3893  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:32:01.326  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:32:01.330  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:01.332  4039  4039 D HeadsetService:, Received stop request...Stopping profile...
09-01 11:32:01.333  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:01.335   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 11:32:01.335   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 11:32:01.335  4039  4039 D A2dpService: Received stop request...Stopping profile...
09-01 11:32:01.336  4039  4220 D A2dpStateMachine: Exit Disconnected: -1
,09-01 11:32:01.336  1368  2126 D BluetoothHeadset: Proxy object disconnected
09-01 11:32:01.336  1368  1368 D HeadsetProfile: Bluetooth service disconnected
09-01 11:32:01.336   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 11:32:01.336  2006  2021 D BluetoothHeadset: Proxy object disconnected
09-01 11:32:01.337  3961  3973 D BluetoothHeadset: Proxy object disconnected
,09-01 11:32:01.340  1368  1368 D BluetoothA2dp: Proxy object disconnected
09-01 11:32:01.341   872   872 D BluetoothA2dp: Proxy object disconnected
,09-01 11:32:01.341  4039  4039 D HidService: Received stop request...Stopping profile...
,09-01 11:32:01.341  4039  4039 D HidService: Stopping Bluetooth HidService
09-01 11:32:01.342  1368  1368 D BluetoothInputDevice: Proxy object disconnected
,09-01 11:32:01.342  1368  1368 D HidProfile: Bluetooth service disconnected
09-01 11:32:01.344  4039  4039 D HealthService: Received stop request...Stopping profile...
,09-01 11:32:01.346  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:32:01.349  3961  3961 D DockEventReceiver: finishStartingService: stopping service
09-01 11:32:01.349  4039  4039 D PanService: Received stop request...Stopping profile...
,09-01 11:32:01.350  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:32:01.350  1368  1368 D PanProfile: Bluetooth service disconnected
,09-01 11:32:01.351  4039  4039 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:32:01.351  4039  4039 D BluetoothMapService: stop()
,09-01 11:32:01.351  3961  3961 D HeadsetProfile: Bluetooth service disconnected
,09-01 11:32:01.351  3961  3961 D BluetoothA2dp: Proxy object disconnected
,09-01 11:32:01.351  4039  4039 D BluetoothMapAppObserver: deinitObservers()
09-01 11:32:01.351  4039  4039 D BluetoothMapAppObserver: removeReceiver()
09-01 11:32:01.352  3961  3961 D BluetoothInputDevice: Proxy object disconnected
09-01 11:32:01.352  3961  3961 D HidProfile: Bluetooth service disconnected
09-01 11:32:01.352  1368  1368 D BluetoothMap: Proxy object disconnected
09-01 11:32:01.352  1368  1368 D MapProfile: Bluetooth service disconnected
,09-01 11:32:01.353  4039  4039 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:32:01.353  4039  4039 V BluetoothAdapterState: isTurningOn()=false,
09-01 11:32:01.353  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:32:01.353  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:01.353  3961  3961 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 11:32:01.353  3961  3961 D PanProfile: Bluetooth service disconnected
,09-01 11:32:01.353  3961  3961 D BluetoothMap: Proxy object disconnected
09-01 11:32:01.354  3961  3961 D MapProfile: Bluetooth service disconnected
09-01 11:32:01.355  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:32:01.355  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 11:32:01.355  4039  4039 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:32:01.355  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:32:01.355  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.355  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:01.355  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:32:01.355  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:32:01.355  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:32:01.356  4039  4039 V BluetoothAdapterState: isTurningOff()=true
09-01 11:32:01.356  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:32:01.356  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.357  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:01.357  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-01 11:32:01.355  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 11:32:01.357  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:32:01.357  4039  4203 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-01 11:32:01.357  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 11:32:01.357  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:32:01.357  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:32:01.357  4039  4212 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:32:01.357  4039  4212 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-01 11:32:01.358  4039  4212 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:32:01.358  4039  4212 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:32:01.359  4039  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 11:32:01.359  1368  1368 D BluetoothPbap: Proxy object disconnected
09-01 11:32:01.359  1368  1368 D PbapServerProfile: Bluetooth service disconnected
,09-01 11:32:01.360  4039  4039 V BluetoothAdapterState: isTurningOff()=true
09-01 11:32:01.360  3961  3961 D BluetoothPbap: Proxy object disconnected
09-01 11:32:01.360  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:32:01.360  3961  3961 D PbapServerProfile: Bluetooth service disconnected
09-01 11:32:01.360  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.360  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:01.360  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...,
09-01 11:32:01.360  4039  4203 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 11:32:01.361  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:32:01.361  4039  4039 V BluetoothAdapterState: isTurningOff()=true
09-01 11:32:01.361  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:32:01.361  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.361  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:01.362  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-01 11:32:01.362  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:32:01.362  4039  4039 D BluetoothMapService: MAP Service closeService in
09-01 11:32:01.362  4039  4039 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:32:01.362  4039  4039 V BluetoothAdapterState: isTurningOn()=false
09-01 11:32:01.362  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.362  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:01.363  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 11:32:01.363  4039  4199 D BluetoothAdapterProperties: Setting state to 15
,09-01 11:32:01.363  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 11:32:01.363  4039  4199 I BluetoothAdapterState: Entering BleOnState
,09-01 11:32:01.363  4039  4039 D BluetoothMapService: cleanup()
09-01 11:32:01.364  4039  4039 D BluetoothMapService: MAP Service closeService in
09-01 11:32:01.365  3961  3973 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:32:01.366  1368  1384 D BluetoothPan: onBluetoothStateChange on: false
,09-01 11:32:01.367  3961  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:32:01.368  1368  2126 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:32:01.368  1368  1393 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:32:01.369  1368  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:32:01.369   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:32:01.369  3961  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 11:32:01.370  3961  3972 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:32:01.370  3961  3973 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:32:01.371  1368  2126 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:32:01.371   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 11:32:01.371  2006  2112 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:32:01.371  3961  3972 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:32:01.372   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:32:01.372   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:32:01.372  1368  1393 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:32:01.372  4039  4199 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 11:32:01.372  4039  4199 D BluetoothAdapterProperties: Setting state to 16
,09-01 11:32:01.373  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 11:32:01.373  4039  4199 D BluetoothAdapterProperties: onBleDisable
09-01 11:32:01.374  4039  4199 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:32:01.374  4039  4200 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 11:32:01.375  4039  4212 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 11:32:01.375  4039  4212 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:32:01.376  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:01.376  4039  4203 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:32:01.377  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:01.378  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:32:01.379  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:01.381  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:01.384  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:32:01.387  3961  3961 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:32:01.575  4039  4203 I bt_hci  : shut_down
09-01 11:32:01.575  4039  4208 D bt_hwcfg: hw_epilog_process
09-01 11:32:01.577  4039  4208 I bt_vendor: low_power_mode_cb
,09-01 11:32:01.607  4039  4208 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 11:32:01.608  4039  4208 I bt_vendor: epilog_cb
,09-01 11:32:01.608  4039  4208 I bt_hci  : epilog_finished_callback
,09-01 11:32:01.618  4039  4203 I bt_hci_h4: hal_close
,09-01 11:32:01.619  4039  4203 I bt_userial_vendor: device fd = 51 close
,09-01 11:32:01.736  4039  4200 D bt_stack_manager: event_shut_down_stack finished.
,09-01 11:32:01.737  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 11:32:01.745  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:32:01.744  4039  4199 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-01 11:32:01.746  4039  4039 D BtGatt.GattService: Received stop request...Stopping profile...
,09-01 11:32:01.746  4039  4039 D BtGatt.GattService: stop()
09-01 11:32:01.747  4039  4039 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 11:32:01.752  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:32:01.752  4039  4039 V BluetoothAdapterState: isTurningOn()=false
09-01 11:32:01.752  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:01.753  4039  4039 V BluetoothAdapterState: isBleTurningOff()=true
09-01 11:32:01.753  4039  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 11:32:01.754  4039  4199 D BluetoothAdapterProperties: Setting state to 10
,09-01 11:32:01.754  4039  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-01 11:32:01.756  4039  4199 I BluetoothAdapterState: Entering OffState
,09-01 11:32:01.759   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 11:32:01.789  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-01 11:32:01.789  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-01 11:32:01.789  4039  4200 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 11:32:01.797  4039  4200 D bt_stack_manager: event_clean_up_stack finished.
09-01 11:32:01.797  4039  4039 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 11:32:01.802  4039  4039 I art     : System.exit called, status: 0
09-01 11:32:01.803  4039  4039 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 11:32:01.901   872  1496 I ActivityManager: Process com.android.bluetooth (pid 4039) has died
,09-01 11:32:04.281  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:32:04.281  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:07.047  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:32:07.070  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:32:07.076  1482  1482 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:32:07.161  1482  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 11:32:07.162  1482  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 11:32:07.162  1482  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:32:07.163  1482  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:32:07.228  3645  3645 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 11:32:07.229  3645  3645 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 11:32:07.234  3645  3645 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-01 11:32:07.285  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:32:07.285  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21dc5b1 added. We now have 6 listener(s)
09-01 11:32:07.285  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:07.288  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:32:07.288  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf4a96 added. We now have 7 listener(s)
09-01 11:32:07.288  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:07.290  3893  3941 I System.out: IsBluetoothEnabled
,09-01 11:32:07.298  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:07.336   872   889 I ActivityManager: Start proc 4250:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 11:32:07.466  4250  4250 D AdapterServiceConfig: Adding HeadsetService
,09-01 11:32:07.467  4250  4250 D AdapterServiceConfig: Adding A2dpService
,09-01 11:32:07.467  4250  4250 D AdapterServiceConfig: Adding HidService
,09-01 11:32:07.467  4250  4250 D AdapterServiceConfig: Adding HealthService
,09-01 11:32:07.467  4250  4250 D AdapterServiceConfig: Adding PanService
,09-01 11:32:07.468  4250  4250 D AdapterServiceConfig: Adding GattService
,09-01 11:32:07.468  4250  4250 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 11:32:07.486   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44921f:true
,09-01 11:32:07.486  4250  4250 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 11:32:07.493  4250  4250 I bt_bluedroid: init
,09-01 11:32:07.494  4250  4262 I BluetoothAdapterState: Entering OffState
,09-01 11:32:07.499  4250  4263 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:32:07.499  4250  4263 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-01 11:32:07.500  4250  4263 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 11:32:07.500  4250  4263 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 11:32:07.502  4250  4250 I bt_bluedroid: get_profile_interface socket
09-01 11:32:07.504  4250  4250 I bt_bluedroid: get_profile_interface sdp
,09-01 11:32:07.509  4250  4260 I bt_bluedroid: config_hci_snoop_log
,09-01 11:32:07.509  4250  4266 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 11:32:07.510   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 11:32:07.513  4250  4266 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:32:07.521  4250  4262 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 11:32:07.522  4250  4262 D BluetoothAdapterProperties: Setting state to 14
09-01 11:32:07.522  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 11:32:07.527  4250  4262 D BluetoothBondStateMachine: make
,09-01 11:32:07.532  4250  4267 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 11:32:07.540  4250  4262 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:32:07.543  4250  4250 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 11:32:07.552  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:07.555  4250  4250 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:32:07.556  4250  4250 D BtGatt.GattService: Received start request. Starting profile...
,09-01 11:32:07.557  4250  4250 D BtGatt.GattService: start()
09-01 11:32:07.557  4250  4250 I bt_bluedroid: get_profile_interface gatt
,09-01 11:32:07.559  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:32:07.559  4250  4250 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:32:07.573  4250  4250 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:32:07.574  4250  4250 V BluetoothAdapterState: isTurningOn()=false
09-01 11:32:07.574  4250  4250 V BluetoothAdapterState: isBleTurningOn()=true
09-01 11:32:07.574  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:07.575  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 11:32:07.576  4250  4262 I bt_bluedroid: enable
09-01 11:32:07.576  4250  4263 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 11:32:07.577  4250  4263 I bt_hci  : start_up
,09-01 11:32:07.601  4250  4263 I bt_vendor: alloc value 0xb3a1b189
,09-01 11:32:07.601  4250  4263 I bt_vendor: init
09-01 11:32:07.601  4250  4263 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 11:32:07.602  4250  4263 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 11:32:07.713  4250  4263 D bt_hci  : start_up starting async portion
,09-01 11:32:07.713  4250  4270 I bt_hci  : event_finish_startup
,09-01 11:32:07.714  4250  4270 I bt_hci_h4: hal_open
,09-01 11:32:07.714  4250  4270 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 11:32:07.725  4250  4270 I bt_userial_vendor: device fd = 51 open
,09-01 11:32:07.755  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:32:07.785  4250  4270 D bt_hwcfg: Chipset BCM4354A2
,09-01 11:32:07.786  4250  4270 D bt_hwcfg: Target name = [BCM4354A2]
,09-01 11:32:07.786  4250  4270 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 11:32:08.451  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 11:32:08.452  4250  4270 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 11:32:08.453  4250  4270 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 11:32:08.570  4250  4270 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:32:08.571  4250  4270 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 11:32:08.600  4250  4270 I bt_hwcfg: vendor lib fwcfg completed
,09-01 11:32:08.600  4250  4270 I bt_vendor: firmware callback
,09-01 11:32:08.600  4250  4270 I bt_hci  : firmware_config_callback
,09-01 11:32:08.614  4250  4272 I bt_btu  : btu_task pending for preload complete event
,09-01 11:32:08.614  4250  4272 I bt_btu_task: Bluetooth chip preload is complete
09-01 11:32:08.614  4250  4272 I bt_btu  : btu_task received preload complete event
,09-01 11:32:08.626  4250  4272 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 11:32:08.627  4250  4272 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-01 11:32:08.627  4250  4272 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:32:08.627  4250  4272 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:32:08.628  4250  4272 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 11:32:08.628  4250  4272 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:32:08.628  4250  4272 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:32:08.628  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTM
,09-01 11:32:08.629  4250  4272 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:32:08.629  4250  4272 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:32:08.629  4250  4272 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:32:08.630  4250  4272 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 11:32:08.630  4250  4272 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:32:08.630  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:32:08.630  4250  4272 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 11:32:08.763  4250  4272 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3998d9d
,09-01 11:32:08.764  4250  4272 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3998d9d 
,09-01 11:32:08.795  4250  4266 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 11:32:08.797  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 11:32:08.798  4250  4266 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:32:08.801  4250  4266 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:32:08.805  4250  4266 D BluetoothAdapterProperties: Scan Mode:20
,09-01 11:32:08.806  4250  4266 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:32:08.806  4250  4266 D bt_hci  : do_postload posting postload work item
,09-01 11:32:08.806  4250  4270 I bt_hci  : event_postload
09-01 11:32:08.807  4250  4270 I bt_vendor: sco_config_cb
09-01 11:32:08.807  4250  4270 I bt_hci  : sco_config_callback postload finished.
,09-01 11:32:08.809  4250  4266 D bt_bte_conf: Device ID record 1 : primary
,09-01 11:32:08.809  4250  4266 D bt_bte_conf:   vendorId            = 000f
,09-01 11:32:08.809  4250  4266 D bt_bte_conf:   vendorIdSource      = 0001
,09-01 11:32:08.810  4250  4266 D bt_bte_conf:   product             = 1200
,09-01 11:32:08.810  4250  4266 D bt_bte_conf:   version             = 1436
,09-01 11:32:08.810  4250  4266 D bt_bte_conf:   clientExecutableURL = 
,09-01 11:32:08.810  4250  4266 D bt_bte_conf:   serviceDescription  = 
,09-01 11:32:08.810  4250  4266 D bt_bte_conf:   documentationURL    = 
,09-01 11:32:08.810  4250  4266 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-01 11:32:08.811  4250  4263 D bt_stack_manager: event_start_up_stack finished
,09-01 11:32:08.812  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:08.813  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-01 11:32:08.814  4250  4270 I bt_vendor: low_power_mode_cb
,09-01 11:32:08.814  4250  4262 D BluetoothAdapterProperties: Setting state to 15
,09-01 11:32:08.815  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-01 11:32:08.816  4250  4262 I BluetoothAdapterState: Entering BleOnState
09-01 11:32:08.825  4250  4262 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-01 11:32:08.825  4250  4262 D BluetoothAdapterProperties: Setting state to 11
09-01 11:32:08.825  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-01 11:32:08.831  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:32:08.832  4250  4250 D HeadsetService: Received start request. Starting profile...
09-01 11:32:08.835  4250  4250 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:32:08.835  4250  4250 D HeadsetStateMachine: make
09-01 11:32:08.848  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:08.849  4250  4262 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:32:08.849  4250  4250 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:32:08.849  4250  4250 I bt_bluedroid: get_profile_interface handsfree
09-01 11:32:08.850  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 11:32:08.850  4250  4266 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 11:32:08.856  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:08.857  4250  4250 D A2dpService: Received start request. Starting profile...
,09-01 11:32:08.858  4250  4250 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:32:08.858  4250  4250 I bt_bluedroid: get_profile_interface avrcp
,09-01 11:32:08.864  4250  4250 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:32:08.864  4250  4250 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-01 11:32:08.864  4250  4250 D A2dpStateMachine: make
,09-01 11:32:08.866  4250  4250 I bt_bluedroid: get_profile_interface a2dp
09-01 11:32:08.867  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048,
,09-01 11:32:08.869  4250  4280 D A2dpStateMachine: Enter Disconnected: -2
,09-01 11:32:08.870  4250  4250 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 11:32:08.871  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:08.871  4250  4250 D HidService: Received start request. Starting profile...
09-01 11:32:08.872  4250  4250 I bt_bluedroid: get_profile_interface hidhost
09-01 11:32:08.872  4250  4266 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397a3e5
09-01 11:32:08.872  4250  4266 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 11:32:08.872  4250  4250 D HidService: setHidService(): set to: null
09-01 11:32:08.873  4250  4250 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:32:08.874  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:08.874  4250  4250 D HealthService: Received start request. Starting profile...
,09-01 11:32:08.876  4250  4250 I bt_bluedroid: get_profile_interface health
,09-01 11:32:08.876  4250  4250 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:32:08.877  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
09-01 11:32:08.877  4250  4250 D PanService: Received start request. Starting profile...
,09-01 11:32:08.879  4250  4250 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-01 11:32:08.879  4250  4250 I bt_bluedroid: get_profile_interface pan
09-01 11:32:08.880  4250  4266 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 11:32:08.883  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:08.883  4250  4250 D BluetoothMapService: Received start request. Starting profile...
09-01 11:32:08.883  4250  4250 D BluetoothMapService: start()
,09-01 11:32:08.885  4250  4250 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 11:32:08.886  4250  4250 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 11:32:08.886  4250  4250 D BluetoothMapAppObserver: createReceiver()
,09-01 11:32:08.887  4250  4250 D BluetoothMapAppObserver: initObservers()
,09-01 11:32:08.888  4250  4250 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 11:32:08.897  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:32:08.897  4250  4278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:32:08.898  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-01 11:32:08.898  4250  4250 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:32:08.898  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:08.898  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:32:08.902  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOff()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isTurningOn()=true
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:32:08.903  4250  4250 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:32:08.904  4250  4262 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-01 11:32:08.904  4250  4262 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:32:08.904  4250  4262 D BluetoothAdapterProperties: State =  11
09-01 11:32:08.906  4250  4266 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:32:08.906  4250  4262 D BluetoothAdapterProperties: Setting state to 12
09-01 11:32:08.906  4250  4262 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 11:32:08.906  4250  4262 I BluetoothAdapterState: Entering OnState
,09-01 11:32:08.908  4250  4266 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:32:08.908  3961  3973 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:08.910  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:32:08.911  1368  2126 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:32:08.911  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:32:08.912  3961  3973 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:32:08.913  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:32:08.913  1368  1368 D PanProfile: Bluetooth service connected
09-01 11:32:08.913  4250  4250 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:32:08.914  4250  4250 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 11:32:08.914  1368  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:32:08.915  4250  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:32:08.915  1368  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:32:08.915  1368  1368 D BluetoothMap: Proxy object connected
09-01 11:32:08.915  1368  1368 D MapProfile: Bluetooth service connected
09-01 11:32:08.915  1368  1368 D BluetoothMap: getConnectedDevices()
,09-01 11:32:08.916  1368  2126 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 11:32:08.917  4250  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:32:08.918   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:32:08.918  3961  3972 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:32:08.918  3961  3973 D BluetoothPan: onBluetoothStateChange on: true
,09-01 11:32:08.918  4250  4250 D ObexServerSockets: Succeed to create listening sockets 
09-01 11:32:08.918  4250  4250 D ObexServerSockets0: startAccept()
09-01 11:32:08.918  4250  4250 D ObexServerSockets0: prepareForNewConnect()
09-01 11:32:08.920  3961  3972 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:32:08.920  4250  4250 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 11:32:08.921  4250  4250 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 11:32:08.921  4250  4288 D ObexServerSockets0: Accepting socket connection...
09-01 11:32:08.921  3961  3961 D BluetoothMap: Proxy object connected
,09-01 11:32:08.921  3961  3961 D MapProfile: Bluetooth service connected
09-01 11:32:08.921  3961  3961 D BluetoothMap: getConnectedDevices()
09-01 11:32:08.922  1368  1368 D BluetoothA2dp: Proxy object connected
09-01 11:32:08.923  1368  2126 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:32:08.923  4250  4289 D ObexServerSockets0: Accepting socket connection...
09-01 11:32:08.923   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:32:08.923  2006  2020 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:32:08.924  1368  1368 D BluetoothInputDevice: Proxy object connected
09-01 11:32:08.924  3961  3973 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:32:08.924  1368  1368 D HidProfile: Bluetooth service connected
09-01 11:32:08.926   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:32:08.926   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:32:08.926   872   872 D BluetoothA2dp: Proxy object connected
,09-01 11:32:08.926  1368  1393 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:32:08.926  3961  3961 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:32:08.926  3961  3961 D PanProfile: Bluetooth service connected
09-01 11:32:08.926  3961  3961 D BluetoothA2dp: Proxy object connected
09-01 11:32:08.928  3961  3961 D BluetoothInputDevice: Proxy object connected
09-01 11:32:08.928  3961  3961 D HidProfile: Bluetooth service connected
09-01 11:32:08.929   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 11:32:08.929  4250  4250 D BluetoothMapService: onReceive
,09-01 11:32:08.930  4250  4250 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:32:08.930  4250  4250 D BluetoothMapService: STATE_ON
09-01 11:32:08.930  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:08.937  3961  3961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:32:08.944  3961  3961 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:32:08.944  1482  1482 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:32:08.955  3961  3961 D BluetoothPbap: Proxy object connected
,09-01 11:32:08.955  1368  1368 D BluetoothPbap: Proxy object connected
09-01 11:32:08.955  1368  1368 D PbapServerProfile: Bluetooth service connected
,09-01 11:32:08.956  3961  3961 D PbapServerProfile: Bluetooth service connected
,09-01 11:32:08.960  4250  4250 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 11:32:08.960  4250  4250 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:32:08.963  4250  4293 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:32:08.980  4250  4297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:32:08.981  4250  4297 I BtOppRfcommListener: Accept thread started.
,09-01 11:32:09.020   872   872 D BluetoothHeadset: Proxy object connected
09-01 11:32:09.021   872   872 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.022  1368  2126 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.022  1368  1368 D HeadsetProfile: Bluetooth service connected
,09-01 11:32:09.022   872   872 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.023  2006  2021 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.024  1368  1393 D BluetoothHeadset: Proxy object connected
09-01 11:32:09.024  3961  3973 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.025  3961  3961 D HeadsetProfile: Bluetooth service connected
09-01 11:32:09.025   872   889 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.033  2006  2112 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.033   872   889 D BluetoothHeadset: Proxy object connected
,09-01 11:32:09.033  1368  1368 D HeadsetProfile: Bluetooth service connected
,09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:09.320  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:32:09.328  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:32:09.331  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:32:09.332  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@700a617 added. We now have 8 listener(s)
09-01 11:32:09.332  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:09.337   872  2054 D WifiService: setWifiEnabled: false pid=3893, uid=10000
09-01 11:32:09.338   872  2054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:32:09.350  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:09.351   872   883 D WifiService: setWifiEnabled: true pid=3893, uid=10000
09-01 11:32:09.352   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:32:09.361   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:09.369  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:09.376  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:32:09.378  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:32:09.384  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:32:09.392   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-01 11:32:09.393   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 11:32:09.394   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 11:32:09.394  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-01 11:32:09.394   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 11:32:09.395   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 11:32:09.395   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 11:32:09.395   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 11:32:09.395  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 11:32:09.401  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a44a5f Bundle[{}]
,09-01 11:32:09.404  3893  3941 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 11:32:09.405  3893  3941 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-01 11:32:09.407  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-01 11:32:09.408   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 11:32:09.408   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.23 delta 1000 -> 1000
,09-01 11:32:09.409  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:32:09.410   371   870 D CommandListener: Setting iface cfg
,09-01 11:32:09.411   872  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-01 11:32:09.411   872  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 11:32:09.412  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:32:09.414   872  1308 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:32:09.414   872  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-01 11:32:09.414  3893  3941 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 11:32:09.418  3893  3941 I System.out: Running OutgoingSocketThread
,09-01 11:32:09.419  3893  4302 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 447)
,09-01 11:32:09.422  3893  4302 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39114
09-01 11:32:09.422  3893  4302 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 11:32:09.423   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-01 11:32:09.423   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:32:09.437   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 11:32:09.486   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 11:32:09.489  1422  1422 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 11:32:10.219  1422  1422 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:32:10.259  1422  1422 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 11:32:10.260  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 11:32:10.266   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:32:10.273   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:32:10.274   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:32:10.274   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 11:32:10.297   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:32:10.313   371   870 D CommandListener: Setting iface cfg
,09-01 11:32:10.314   872  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-01 11:32:10.337   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 11:32:10.337   872  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-01 11:32:10.338   872  4306 D DhcpClient: Receive thread started
,09-01 11:32:10.344   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 11:32:10.421  3893  3941 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 448)
,09-01 11:32:10.421  3893  3941 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 448)
,09-01 11:32:10.431  3893  3941 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,09-01 11:32:10.434  3893  3941 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-01 11:32:10.434  3893  3941 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,09-01 11:32:10.438  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.439  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aabea04 added. We now have 2 listener(s)
,09-01 11:32:10.439   872  1310 E native  : do suspend false
,09-01 11:32:10.440  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:32:10.441  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.441  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.441  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.441  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f980bed added. We now have 9 listener(s)
09-01 11:32:10.441  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:10.442  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:32:10.445  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:10.452  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:32:10.455  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:32:10.455  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:32:10.455  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.456  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65f8cb3 added. We now have 3 listener(s)
09-01 11:32:10.457  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:32:10.458  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.458  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.458  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.458  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.459  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ffa270 added. We now have 10 listener(s)
09-01 11:32:10.459  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.459  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:32:10.459  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:32:10.459  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:32:10.459  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.459  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.460  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:32:10.460  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.460  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aabea04 removed from the list
09-01 11:32:10.460  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.460  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f980bed removed from the list
09-01 11:32:10.462   872  2110 D DhcpClient: Broadcasting DHCPDISCOVER
09-01 11:32:10.463  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.463  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:32:10.463  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.464  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.464  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.465  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.465  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.465  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.465  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f980bed not in the list
09-01 11:32:10.465  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.465  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.467  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.467  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.467  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.467  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ffa270 removed from the list
09-01 11:32:10.467  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.467  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.467  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.467  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.467  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65f8cb3 removed from the list
09-01 11:32:10.468  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.468  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af679e9 added. We now have 2 listener(s)
09-01 11:32:10.470  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:32:10.470  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.470  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.470  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.471  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74d166e added. We now have 9 listener(s)
09-01 11:32:10.471  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.471  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:32:10.474  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:32:10.475   872  4306 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
09-01 11:32:10.477   872  2110 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
09-01 11:32:10.479   872  2110 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:10.481  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:32:10.484  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:32:10.484  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:32:10.485  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.485  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94759c added. We now have 3 listener(s)
09-01 11:32:10.486  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.487  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.491  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:32:10.491  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.491  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.492  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.492   872  4306 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-01 11:32:10.493   872  2110 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-01 11:32:10.492  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3cba5 added. We now have 10 listener(s)
09-01 11:32:10.496  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.496  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:32:10.496  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:32:10.496  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:32:10.496  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:32:10.496  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:32:10.497   371   870 D CommandListener: Setting iface cfg
09-01 11:32:10.502   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-01 11:32:10.503  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:32:10.503  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:32:10.505   872  2110 D DhcpClient: Scheduling renewal in 86399s
09-01 11:32:10.511   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-01 11:32:10.511  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:32:10.512   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
09-01 11:32:10.512  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:32:10.512  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:32:10.513   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:32:10.515   872  1314 D ConnectivityService: Adding iface wlan0 to network 102
,09-01 11:32:10.517   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:32:10.525  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:32:10.529  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:32:10.529  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:32:10.530  3893  3941 D BluetoothAdapter: STATE_ON
09-01 11:32:10.534  4250  4286 D BtGatt.GattService: registerClient() - UUID=6ae882e7-aba4-4df2-a20b-c7d22ba173d4
,09-01 11:32:10.535  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=6ae882e7-aba4-4df2-a20b-c7d22ba173d4, clientIf=5
,09-01 11:32:10.536  3893  3905 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 11:32:10.537  4250  4285 D BtGatt.GattService: start scan with filters
,09-01 11:32:10.541  4250  4269 D BtGatt.ScanManager: handling starting scan
,09-01 11:32:10.541  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:32:10.541  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 11:32:10.541  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:32:10.542  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:32:10.543  4250  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a22a103
,09-01 11:32:10.545  4250  4266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:32:10.545  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.546  4250  4269 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:32:10.547  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:32:10.547  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:32:10.548  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:32:10.548  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.548  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:32:10.548  4250  4269 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:32:10.548  4250  4269 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-01 11:32:10.550  4250  4266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-01 11:32:10.550  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.551  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:32:10.552  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:32:10.552  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.555  3893  3941 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 11:32:10.555  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:32:10.555  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 11:32:10.555  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.556  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:32:10.556  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:32:10.556  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:32:10.556  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:32:10.556  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:32:10.556  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:32:10.556  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:32:10.557  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:32:10.558  4250  4285 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:32:10.565  4250  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-01 11:32:10.566  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 11:32:10.566  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 11:32:10.566  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 11:32:10.566  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:32:10.566  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:32:10.567  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:32:10.567  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.567  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:32:10.567  4250  4269 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:32:10.567  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:32:10.567  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 11:32:10.568  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:32:10.568  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:32:10.569  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:32:10.569  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:32:10.569  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:32:10.570  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:32:10.570  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.570  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:32:10.571  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:32:10.571  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:32:10.571  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:32:10.572  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.572  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:32:10.572  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.572  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.572  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:32:10.572  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:32:10.572  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af679e9 removed from the list
09-01 11:32:10.572  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.572  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74d166e removed from the list
,09-01 11:32:10.572  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:32:10.572  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.573  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.573  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:10.574  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.574  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.574  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.574  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74d166e not in the list
09-01 11:32:10.574  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.574  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:10.575  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.575  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.575  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.575  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3cba5 removed from the list
09-01 11:32:10.575  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.575   872  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 11:32:10.575  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.575  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.575  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.575   872  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-01 11:32:10.575  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94759c removed from the list
09-01 11:32:10.576  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:32:10.576  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a7d21 added. We now have 2 listener(s)
,09-01 11:32:10.576   872  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-01 11:32:10.578   872  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-01 11:32:10.578  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:32:10.578  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.578  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.578  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:32:10.579  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d8546 added. We now have 9 listener(s)
09-01 11:32:10.579  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.579   872  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-01 11:32:10.579  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:32:10.586  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:32:10.591  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:32:10.592  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:32:10.592   872  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:32:10.592  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:32:10.592  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.593  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5fdc34 added. We now have 3 listener(s)
,09-01 11:32:10.593  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.594  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:32:10.595  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.595  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:32:10.595  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.595  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:10.595  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b20ca5d added. We now have 10 listener(s)
09-01 11:32:10.595  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.595  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:32:10.596  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:32:10.596  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:32:10.596  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 11:32:10.596  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:32:10.596  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:32:10.596   872  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-01 11:32:10.596   872  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-01 11:32:10.596   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 11:32:10.597   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:32:10.597   872  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-01 11:32:10.597   872  1314 D ConnectivityService:    accepting network in place of null
09-01 11:32:10.599   872  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-01 11:32:10.599  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:32:10.599  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:32:10.602  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:32:10.602  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:32:10.602  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:32:10.605  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:32:10.605  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:32:10.605  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:32:10.606  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:32:10.608  4250  4260 D BtGatt.GattService: registerClient() - UUID=1c7268fa-46b3-4b4c-b645-342f84893d2a
,09-01 11:32:10.608  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=1c7268fa-46b3-4b4c-b645-342f84893d2a, clientIf=5
,09-01 11:32:10.608  3893  3903 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:32:10.609  4250  4286 D BtGatt.GattService: start scan with filters
,09-01 11:32:10.612  4250  4269 D BtGatt.ScanManager: handling starting scan
,09-01 11:32:10.613  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:32:10.613  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:32:10.613  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:32:10.613  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:32:10.615  4250  4266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:32:10.615  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.615  4250  4269 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 11:32:10.615  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:32:10.615  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:32:10.615  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:32:10.616  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:32:10.617  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 11:32:10.617  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.617  4250  4269 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:32:10.617  4250  4269 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-01 11:32:10.618  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:32:10.618  3893  3941 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-01 11:32:10.619  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:32:10.619  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:32:10.619  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:32:10.619  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.619  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:32:10.619  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:32:10.619  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.619  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a7d21 removed from the list
,09-01 11:32:10.620  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.620  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d8546 removed from the list
,09-01 11:32:10.620  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:32:10.620  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:32:10.620  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.620  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-01 11:32:10.620  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.620  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:32:10.621  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.621  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.621  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:32:10.621  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d8546 not in the list
09-01 11:32:10.621  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 11:32:10.621  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:32:10.621  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:32:10.622  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 11:32:10.622  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:32:10.622  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:32:10.623  4250  4261 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:32:10.623  4250  4285 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:32:10.624  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 11:32:10.624  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:32:10.624  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 11:32:10.624  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:32:10.624  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:32:10.625  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:32:10.625  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:32:10.625  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:32:10.625  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-01 11:32:10.625  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:10.626  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:32:10.626  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:32:10.626  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:32:10.627  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.627  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:32:10.627  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.627  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b20ca5d removed from the list
09-01 11:32:10.627  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:32:10.627  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.627  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.627  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:32:10.627  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5fdc34 removed from the list
,09-01 11:32:10.627  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:32:10.628  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c24af59 added. We now have 2 listener(s)
,09-01 11:32:10.629  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,09-01 11:32:10.629  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:32:10.629  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:32:10.629  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:32:10.629  4250  4266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:32:10.629  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.629  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f71e added. We now have 9 listener(s),
09-01 11:32:10.630  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:10.630  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:32:10.632  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:32:10.633   872  4305 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152763, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-01 11:32:10.633   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 11:32:10.636  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 11:32:10.637  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:32:10.638  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:32:10.641  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:32:10.641  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:32:10.642  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.642  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2e7dcc added. We now have 3 listener(s)
09-01 11:32:10.642  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:32:10.642  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.642  4250  4269 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:32:10.643  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:10.647  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:10.647  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:32:10.647  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.647  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:32:10.647  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:32:10.648  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.648  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:32:10.648  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.648  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7e815 added. We now have 10 listener(s)
09-01 11:32:10.648  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:32:10.648  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:32:10.648  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:32:10.649  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:32:10.649  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:32:10.649  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:32:10.651  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-01 11:32:10.651  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.653  3893  3941 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:32:10.653  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:32:10.658  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:32:10.658  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:32:10.658  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:32:10.660  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:32:10.661  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 11:32:10.661  3893  3941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:32:10.661  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:32:10.662  4250  4261 D BtGatt.GattService: registerClient() - UUID=839092df-c4ff-426a-8317-a96e75d77941
,09-01 11:32:10.663  4250  4266 D BtGatt.GattService: onClientRegistered() - UUID=839092df-c4ff-426a-8317-a96e75d77941, clientIf=5
09-01 11:32:10.663  3893  3905 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:32:10.663   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 11:32:10.663  4250  4285 D BtGatt.GattService: start scan with filters
,09-01 11:32:10.665  4250  4269 D BtGatt.ScanManager: handling starting scan
09-01 11:32:10.666  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:32:10.666  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 11:32:10.666  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:32:10.666  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:32:10.667   872  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-01 11:32:10.667   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:32:10.669   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:32:10.676  3893  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:32:10.677   872  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-01 11:32:10.678  4250  4266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:32:10.678  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.678  4250  4269 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:32:10.678  3893  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:32:10.681  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.681  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:32:10.681  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:32:10.681  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:32:10.683  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:32:10.684  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:32:10.684  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.684  4250  4269 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:32:10.684  4250  4269 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-01 11:32:10.687  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:32:10.687  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:32:10.687  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:32:10.687  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.687  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:32:10.687  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:32:10.687  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:32:10.687  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c24af59 removed from the list
09-01 11:32:10.687  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.687  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f71e removed from the list
,09-01 11:32:10.687  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:32:10.687  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:32:10.688  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:32:10.688  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 11:32:10.688  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.688  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:32:10.689  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.689  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:32:10.689  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.689  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f71e not in the list
09-01 11:32:10.689  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 11:32:10.689  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:32:10.689  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:32:10.689  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 11:32:10.690  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:32:10.690  3893  3941 D BluetoothAdapter: STATE_ON
,09-01 11:32:10.691  1682  1682 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:32:10.691  4250  4285 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:32:10.692  4250  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-01 11:32:10.693  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:32:10.693  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 11:32:10.693  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 11:32:10.693  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:32:10.693  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:32:10.694  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:32:10.694  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:32:10.694  3893  3941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 11:32:10.694  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:32:10.695  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.696  4250  4266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:32:10.696  1682  1682 D SystemUpdateService: onCreate
09-01 11:32:10.696  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.696  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:32:10.696  3893  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:32:10.696  3893  3893 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:32:10.697  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.697  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.697  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.697  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7e815 removed from the list
,09-01 11:32:10.697  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.697  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.697  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:10.697  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.697  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2e7dcc removed from the list
09-01 11:32:10.698  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:32:10.698  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96bf091 added. We now have 2 listener(s)
09-01 11:32:10.698  1682  1682 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-01 11:32:10.699  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:32:10.700  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:32:10.700  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.700  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.700  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767cbf6 added. We now have 9 listener(s)
09-01 11:32:10.700  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:10.700  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:32:10.700  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.700  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:32:10.703  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:32:10.707  3893  3941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:32:10.707  4250  4266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-01 11:32:10.707  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.708  4250  4269 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:32:10.709  3893  3941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:32:10.709  3893  3941 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:32:10.711  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:32:10.711  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:32:10.712  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bccba64 added. We now have 3 listener(s)
,09-01 11:32:10.712  4250  4266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:32:10.712  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:32:10.713  4250  4269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:32:10.713  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:32:10.713  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:32:10.713  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:32:10.713  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:32:10.713  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44e04cd added. We now have 10 listener(s)
09-01 11:32:10.713  3893  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:32:10.713  3893  3941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:32:10.714  3893  3941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:32:10.714  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:32:10.714  3893  3941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:32:10.714  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:32:10.714  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.714  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:32:10.714  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.714  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96bf091 removed from the list
09-01 11:32:10.714  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.714  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767cbf6 removed from the list
09-01 11:32:10.714  3893  3941 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:32:10.715  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.715  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.715  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:32:10.716  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.716  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.716  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.716  3893  3941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767cbf6 not in the list
09-01 11:32:10.717  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.717  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.717  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:32:10.717  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:32:10.717  3893  3941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:32:10.717  3893  3941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44e04cd removed from the list
09-01 11:32:10.717  3893  3941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:32:10.717  3893  3941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:32:10.717  3893  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:32:10.717  3893  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:32:10.717  3893  3941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bccba64 removed from the list
,09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 11:32:10.718  3893  3941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:32:10.718  4250  4266 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:32:10.719  4250  4266 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:32:10.722  3893  4320 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,09-01 11:32:10.722  3893  4320 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
09-01 11:32:10.723  3893  4320 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:32:10.724  3893  4321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,09-01 11:32:10.724  3893  4321 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
09-01 11:32:10.724  3893  4321 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:32:10.725  3893  3941 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 11:32:10.725  3893  3941 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-01 11:32:10.725  3893  3941 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:32:10.725  3893  3941 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:32:10.725  3893  3941 D com.test.thalitest.ThaliTestRunner: Total duration: 21831 ms
,09-01 11:32:10.727  3893  3941 I jxcore-log: *Native tests were executed*
09-01 11:32:10.727  3893  3941 I jxcore-log: 
09-01 11:32:10.727  1682  1682 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 11:32:10.727  3893  3941 I jxcore-log: Total number of executed tests:  80
09-01 11:32:10.727  3893  3941 I jxcore-log: 
09-01 11:32:10.727  3893  3941 I jxcore-log: Number of passed tests:  80
09-01 11:32:10.727  3893  3941 I jxcore-log: 
09-01 11:32:10.727  3893  3941 I jxcore-log: Number of failed tests:  0
09-01 11:32:10.727  3893  3941 I jxcore-log: 
09-01 11:32:10.727  3893  3941 I jxcore-log: Number of ignored tests:  0
09-01 11:32:10.727  3893  3941 I jxcore-log: 
,09-01 11:32:10.727  3893  3941 I jxcore-log: Total duration:  21831
09-01 11:32:10.727  3893  3941 I jxcore-log: 
09-01 11:32:10.728  3893  3941 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:32:10.728  3893  3941 I jxcore-log: 
,09-01 11:32:10.730  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.730  3893  3941 I jxcore-log: 
09-01 11:32:10.733  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.733  3893  3941 I jxcore-log: 
09-01 11:32:10.734  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.734  3893  3941 I jxcore-log: 
09-01 11:32:10.735  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.735  3893  3941 I jxcore-log: 
09-01 11:32:10.736  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.736  3893  3941 I jxcore-log: 
09-01 11:32:10.737  3893  3893 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:32:10.737  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.737  3893  3941 I jxcore-log: 
09-01 11:32:10.739  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.739  3893  3941 I jxcore-log: 
09-01 11:32:10.739  1682  2527 I iu.UploadsManager: num queued entries: 0
09-01 11:32:10.739  1682  2527 I iu.UploadsManager: num updated entries: 0
09-01 11:32:10.740  1682  2527 I iu.SyncManager: NEXT; no task
09-01 11:32:10.740  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.740  3893  3941 I jxcore-log: 
09-01 11:32:10.741  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.741  3893  3941 I jxcore-log: 
09-01 11:32:10.741  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:32:10.741  3893  3941 I jxcore-log: 
09-01 11:32:10.740  1682  4316 I SystemUpdateService: active receiver: enabled
09-01 11:32:10.742  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.742  3893  3941 I jxcore-log: 
09-01 11:32:10.743  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.743  3893  3941 I jxcore-log: 
09-01 11:32:10.743  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.743  3893  3941 I jxcore-log: 
09-01 11:32:10.744  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 11:32:10.744  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.744  3893  3941 I jxcore-log: 
09-01 11:32:10.745  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.745  3893  3941 I jxcore-log: 
09-01 11:32:10.745  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.745  3893  3941 I jxcore-log: 
09-01 11:32:10.746  1682  1682 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 11:32:10.746  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.746  3893  3941 I jxcore-log: 
09-01 11:32:10.746  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.746  3893  3941 I jxcore-log: 
09-01 11:32:10.747  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.747  3893  3941 I jxcore-log: 
09-01 11:32:10.747  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.747  3893  3941 I jxcore-log: 
09-01 11:32:10.748  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.748  3893  3941 I jxcore-log: 
09-01 11:32:10.748  4054  4054 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:32:10.748  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:32:10.748  3893  3941 I jxcore-log: 
09-01 11:32:10.749  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.749  3893  3941 I jxcore-log: 
09-01 11:32:10.749  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.749  3893  3941 I jxcore-log: 
09-01 11:32:10.750  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.750  3893  3941 I jxcore-log: 
,09-01 11:32:10.750  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.750  3893  3941 I jxcore-log: 
09-01 11:32:10.751  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:32:10.751  3893  3941 I jxcore-log: 
,09-01 11:32:10.751  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.751  3893  3941 I jxcore-log: 
,09-01 11:32:10.752  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.752  3893  3941 I jxcore-log: 
09-01 11:32:10.752  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:32:10.752  3893  3941 I jxcore-log: 
,09-01 11:32:10.755  4054  4054 D SprintDMHelper: simOperator: 
09-01 11:32:10.755  4054  4054 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:32:10.766  1682  4319 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 11:32:10.766  1682  4319 W BaseAppContext: Using Auth Proxy for data requests.
,09-01 11:32:10.781  1682  4319 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 11:32:10.792  1682  4316 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:32:10.808  1682  4316 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 11:32:10.808  1682  4316 I SystemUpdateService: now status is 0 (complete)
09-01 11:32:10.808  1682  4316 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:32:10.808  1682  4316 I SystemUpdateService: file has been verified
09-01 11:32:10.808  1682  4316 I SystemUpdateService: OTA package size = 12249756
,09-01 11:32:10.825  1682  4316 I SystemUpdateService: showing system update notification
,09-01 11:32:10.843  1482  3137 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-01 11:32:10.843  1482  3137 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 11:32:10.843  1482  3137 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:32:10.843  1482  3137 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:32:10.847  1682  1682 D SystemUpdateService: onDestroy
,09-01 11:32:10.852   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-01 11:32:10.855  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-01 11:32:10.859   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:32:10.859   872   892 I Adreno  : Build Date                       : 10/20/15
09-01 11:32:10.859   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:32:10.859   872   892 I Adreno  : Local Branch                     : M14
09-01 11:32:10.859   872   892 I Adreno  : Remote Branch                    : 
09-01 11:32:10.859   872   892 I Adreno  : Remote Branch                    : 
09-01 11:32:10.859   872   892 I Adreno  : Reconstruct Branch               : 
,09-01 11:32:10.868  1682  4319 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-01 11:32:10.880   281  1298 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (96 us)
,09-01 11:32:10.906  2802  4323 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 11:32:11.051   872  2014 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-01 11:32:11.058   872  1496 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-01 11:32:11.063   872  1495 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-01 11:32:11.070  3893  3893 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:32:11.072  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:32:11.072  3893  3941 I jxcore-log: 
,09-01 11:32:11.127  3893  3893 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:32:11.131  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:32:11.131  3893  3941 I jxcore-log: 
,09-01 11:32:11.197  3893  3893 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:32:11.201  3893  3941 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:32:11.201  3893  3941 I jxcore-log: 
,09-01 11:32:11.329  4325  4325 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-01 11:32:11.334  4325  4325 D AndroidRuntime: CheckJNI is OFF
,09-01 11:32:11.374  4325  4325 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-01 11:32:11.413  4325  4325 I Radio-JNI: register_android_hardware_Radio DONE
,09-01 11:32:11.417  3893  3893 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:32:11.417  3893  3893 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 11:32:11.434  4325  4325 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 11:32:11.449   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
09-01 11:32:11.450  3893  3893 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a44a5f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e3cb182, 16908290=android.view.AbsSavedState$1@e3cb182}, android:focusedViewId=100}]}]
09-01 11:32:11.450  3893  3893 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 11:32:11.450  3893  3893 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:32:11.450  3893  3893 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-01 11:32:11.451   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-01 11:32:11.453   872   885 I ActivityManager: Killing 3893:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-01 11:32:11.456   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-01 11:32:11.461   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-01 11:32:11.463   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,09-01 11:32:11.463   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-01 11:32:11.517   872  1967 I WindowState: WIN DEATH: Window{d15b57 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 11:32:11.517   872  2028 D GraphicsStats: Buffer count: 2
09-01 11:32:11.518   872  1313 D WifiService: Client connection lost with reason: 4
,09-01 11:32:11.537   872   885 W ActivityManager: Force removing ActivityRecord{3c6294c u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,09-01 11:32:11.552   872  1395 W ActivityManager: Spurious death for ProcessRecord{7af35c1 0:com.test.thalitest/u0a0}, curProc for 3893: null
,09-01 11:32:11.554   872   895 W PackageSettings: Skipping PackageSetting{553cd64 com.example.hello/10273} due to missing metadata
,09-01 11:32:11.580   872   895 I art     : Starting a blocking GC Explicit
,09-01 11:32:11.658   872  4304 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.92,2a00:1450:400d:802::200e
,09-01 11:32:11.661   872   895 I art     : Explicit concurrent mark sweep GC freed 13412(900KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 800us total 79.276ms
,09-01 11:32:11.668   872  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-01 11:32:11.684   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-01 11:32:11.688   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-01 11:32:11.688   872  4304 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:32:11 GMT], X-Android-Received-Millis=[1472722331687], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472722331680]}
,09-01 11:32:11.688   872  1338 D SurfaceControl: Excessive delay in setPowerMode(): 227ms
09-01 11:32:11.689   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 11:32:11.690   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-01 11:32:11.690   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-01 11:32:11.691   872   892 I DreamManagerService: Entering dreamland.
09-01 11:32:11.691   872   892 I PowerManagerService: Dozing...
09-01 11:32:11.691   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-01 11:32:11.694   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:32:11.695   872  4304 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10011
09-01 11:32:11.696   872  4304 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.92,2a00:1450:400d:802::200e
,09-01 11:32:11.703   872  4304 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:32:11 GMT], X-Android-Received-Millis=[1472722331702], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472722331698]}
09-01 11:32:11.705   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 11:32:11.705   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-01 11:32:11.708   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-01 11:32:11.714  4325  4325 I art     : System.exit called, status: 0
,09-01 11:32:11.714  4325  4325 I AndroidRuntime: VM exiting with result code 0.
,09-01 11:32:11.725   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-01 11:32:11.727   872  1983 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3893 uid 10000
,09-01 11:32:11.738  4250  4250 D BluetoothMapAppObserver: onReceive
,09-01 11:32:11.738  4250  4250 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-01 11:32:11.740  1850  2246 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 11:32:11.743  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-01 11:32:11.747  3736  3736 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-01 11:32:11.748   872  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:32:11.750  1902  1902 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-01 11:32:11.769  2006  2006 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-01 11:32:11.776   872   883 I ActivityManager: Start proc 4347:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-01 11:32:11.826  1902  4351 I Keyboard.Facilitator.DecoderInitializer: run()
,09-01 11:32:11.829  4347  4347 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-01 11:32:11.831  1902  4351 I Decoder : createOrResetDecoder
,09-01 11:32:11.838   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 11:32:11.849   375  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-01 11:32:11.850   375  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-01 11:32:11.854  1482  1482 I ConfigService: onCreate
,09-01 11:32:11.854   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 11:32:11.859   872  1310 E native  : do suspend false
,09-01 11:32:11.866   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 11:32:11.868  1902  4351 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-01 11:32:11.892   872  1337 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-01 11:32:11.892   872  1337 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-01 11:32:11.892   872  1337 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-01 11:32:11.892   872  1337 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
09-01 11:32:11.893   872  1337 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-01 11:32:11.893   872  1337 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-01 11:32:11.893   872  1337 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-01 11:32:11.893   872  1337 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
09-01 11:32:11.893   872  1337 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-01 11:32:11.893   872  1337 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-01 11:32:11.893   872  1337 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-01 11:32:11.893   872  1337 W System.err: 	... 4 more
09-01 11:32:11.893   872  1337 D skia    : ------- write threw an exception
,09-01 11:32:11.897  4347  4347 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-01 11:32:11.899  2022  2114 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-01 11:32:11.900   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-01 11:32:11.900   872   884 E PackageManager: Failed to write settings, restoring backup
09-01 11:32:11.900   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-01 11:32:11.900   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-01 11:32:11.900   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-01 11:32:11.900   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-01 11:32:11.900   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-01 11:32:11.900   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:11.900   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:11.900   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:32:11.905   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-01 11:32:11.905   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 11:32:11.905   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:11.905   872   885 E DropBoxManagerService: 	... 13 more
,09-01 11:32:11.909  1902  4351 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-01 11:32:11.911   872  2053 I ActivityManager: Start proc 4366:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-01 11:32:11.912  2022  2114 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-01 11:32:11.912  2022  2114 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2022
09-01 11:32:11.912  2022  2114 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:11.912  2022  2114 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:32:11.915   872  2005 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 11:32:11.915   872  4377 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:11.915   872  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:11.915   872  4377 E DropBoxManagerService: 	... 5 more
,09-01 11:32:11.916  1991  4375 D NfcService: Discovery configuration equal, not updating.
,09-01 11:32:11.921  2022  2114 I Process : Sending signal. PID: 2022 SIG: 9
,09-01 11:32:11.931   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:32:11.933   872  1310 E native  : do suspend true
,09-01 11:32:11.932  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-01 11:32:11.933  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-01 11:32:11.941   872  2015 I ActivityManager: Start proc 4382:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-01 11:32:11.940  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-01 11:32:11.952  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-01 11:32:11.974  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-01 11:32:11.975  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-01 11:32:11.975  1902  4351 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-01 11:32:11.975  1902  4351 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-01 11:32:11.975  1902  4351 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-01 11:32:11.975  1902  4351 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-01 11:32:11.976  1902  4351 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-01 11:32:11.976  1902  4351 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-01 11:32:11.985  4347  4381 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-01 11:32:11.990   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-01 11:32:11.990   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-01 11:32:11.997   872  2028 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{1a20e6b u-1 android.intent.action.SCREEN_OFF} to ReceiverList{cbd264b 2022 com.google.android.googlequicksearchbox/10028/u0 remote:b719b1a}: process crashing
09-01 11:32:12.004  4382  4382 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-01 11:32:12.022  4347  4381 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.022  4347  4381 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-01 11:32:12.022  4347  4381 E AndroidRuntime: Process: android.process.acore, PID: 4347
09-01 11:32:12.022  4347  4381 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.022  4347  4381 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.022  4347  4381 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:32:12.025   872  4398 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:12.025   872  4398 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:12.025   872  4398 E DropBoxManagerService: 	... 5 more
,09-01 11:32:12.031  4347  4381 I Process : Sending signal. PID: 4347 SIG: 9
,09-01 11:32:12.046  1482  1482 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-01 11:32:12.046  1482  1482 D AndroidRuntime: Shutting down VM
,09-01 11:32:12.047   279   279 E lowmemorykiller: Error writing /proc/4347/oom_score_adj; errno=22
,09-01 11:32:12.047  1482  1482 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:32:12.047  1482  1482 E AndroidRuntime: Process: com.google.process.gapps, PID: 1482
09-01 11:32:12.047  1482  1482 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-01 11:32:12.047  1482  1482 E AndroidRuntime: 	... 8 more
,09-01 11:32:12.050   872  4403 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:12.050   872  4403 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:12.050   872  4403 E DropBoxManagerService: 	... 5 more
,09-01 11:32:12.053  1482  1482 I Process : Sending signal. PID: 1482 SIG: 9
,09-01 11:32:12.058   872  2028 D GraphicsStats: Buffer count: 1
,09-01 11:32:12.058   872  1495 I WindowState: WIN DEATH: Window{d5a520d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-01 11:32:12.073   872   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2022) has died
,09-01 11:32:12.074   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-01 11:32:12.075   872   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 11:32:12.080   279   279 E lowmemorykiller: Error writing /proc/4347/oom_score_adj; errno=22
,09-01 11:32:12.100  1682  4400 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@6d7b1d2
,09-01 11:32:12.100   872  1313 D WifiService: Client connection lost with reason: 4
09-01 11:32:12.101   872   885 I ActivityManager: Start proc 4404:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 11:32:12.102   872  2014 I ActivityManager: Process com.google.process.gapps (pid 1482) has died
,09-01 11:32:12.102   872  2014 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-01 11:32:12.102   872  2014 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
09-01 11:32:12.103   872  2014 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-01 11:32:12.103   872  2014 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,09-01 11:32:12.118   872  2054 I ActivityManager: Start proc 4416:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-01 11:32:12.123   872   890 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,09-01 11:32:12.124   872   890 W DisplayManagerService: Failed to notify process 4347 that displays changed, assuming it died.
09-01 11:32:12.124   872   890 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:32:12.124   872   890 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-01 11:32:12.136  1682  1682 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-01 11:32:12.146   872  1983 I ActivityManager: Process android.process.acore (pid 4347) has died
,09-01 11:32:12.147   872  1983 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30956ms
,09-01 11:32:12.166  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-01 11:32:12.166  1682  1682 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-01 11:32:12.168  4416  4416 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-01 11:32:12.171  4404  4404 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
,09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:32:12.171  4404  4404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:32:12.171  4404  4404 D AndroidRuntime: Shutting down VM
,09-01 11:32:12.174  4416  4416 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-01 11:32:12.175  1682  1682 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-01 11:32:12.175  1682  1682 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:32:12.177  4416  4416 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:32:12.177  4416  4416 D AndroidRuntime: Shutting down VM
09-01 11:32:12.178  4416  4416 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:32:12.178  4416  4416 E AndroidRuntime: Process: com.google.process.gapps, PID: 4416
09-01 11:32:12.178  4416  4416 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
0,9-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:32:12.178  4416  4416 E AndroidRuntime: 	... 10 more
09-01 11:32:12.178  1682  4431 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-01 11:32:12.182  4416  4416 I Process : Sending signal. PID: 4416 SIG: 9
09-01 11:32:12.185  4404  4404 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:32:12.185  4404  4404 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4404
09-01 11:32:12.185  4404  4404 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-,01 11:32:12.185  4404  4404 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:32:12.185  4404  4404 E AndroidRuntime: 	... 10 more
09-01 11:32:12.187   872  4432 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:12.187   872  4432 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:12.187   872  4432 E DropBoxManagerService: 	... 5 more
09-01 11:32:12.190   872  2015 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 11:32:12.192   872  4434 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:12.192   872  4434 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:12.192   872  4434 E DropBoxManagerService: 	... 5 more
09-01 11:32:12.201   872   885 I ActivityManager: Start proc 4435:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
09-01 11:32:12.202  4404  4404 I Process : Sending signal. PID: 4404 SIG: 9
09-01 11:32:12.209  1682  4431 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-01 11:32:12.209  1682  4431 E AndroidRuntime: Process: com.google.android.gms, PID: 1682
09-01 11:32:12.209  1682  4431 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:32:12.209  1682  4431 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:32:12.210  2092  4430 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-01 11:32:12.214   872  4445 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:32:12.214   872  4445 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:32:12.214   872  4445 E DropBoxManagerService: 	... 5 more
09-01 11:32:12.223  1682  4431 I Process : Sending signal. PID: 1682 SIG: 9
09-01 11:32:12.230   872  1496 I ActivityManager: Process com.google.process.gapps (pid 4416) has died
09-01 11:32:12.230   872  1496 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{f43b8b5 u0 com.google.android.gms/.gcm.GcmService}
09-01 11:32:12.230   872  1496 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b901d28 u0 com.google.android.gms/.auth.GetToken}
09-01 11:32:12.231   872  1496 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8582403 u0 com.google.android.gms/.config.ConfigService}
09-01 11:32:12.231   872  1496 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{4aab54f u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,09-01 11:32:12.242   872  1496 I ActivityManager: Start proc 4448:com.google.process.gapps/u0a11 for restart com.google.process.gapps
09-01 11:32:12.243   872  2005 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4404) has died
09-01 11:32:12.244   872  2005 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 11:32:12.252   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
