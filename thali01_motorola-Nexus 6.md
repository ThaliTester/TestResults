#### Test 845006541145c7f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 21:13:29.289   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 21:13:29.766  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 21:13:29.772  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 21:13:29.774  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 21:13:29.806  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 21:13:29.806  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 21:13:29.806  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:13:29.806  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 21:13:29.832  3555  3555 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 21:13:29.833  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 21:13:29.833  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-08 21:13:30.039  3805  3805 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 21:13:30.044  3805  3805 D AndroidRuntime: CheckJNI is OFF
09-08 21:13:30.086  3805  3805 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 21:13:30.136  3805  3805 I Radio-JNI: register_android_hardware_Radio DONE
09-08 21:13:30.157  3805  3805 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 21:13:30.161   874  1611 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 21:13:30.209  2085  2108 W SearchService: Abort, client detached.
09-08 21:13:30.218  2085  2085 I HotwordDetector: Closing mic
09-08 21:13:30.219  2085  2338 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@75f08e3
09-08 21:13:30.219  2085  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 21:13:30.220  3805  3805 D AndroidRuntime: Shutting down VM
09-08 21:13:30.249   874  2072 I ActivityManager: Start proc 3814:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 21:13:30.268   375  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 21:13:30.270   375  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 21:13:30.273   375  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 21:13:30.275  2085  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 21:13:30.276  2085  2342 I MicroRecognitionRnrImpl: Detection finished
09-08 21:13:30.317  3814  3814 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 21:13:30.338  3814  3814 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 21:13:30.344  3814  3814 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4834-4837)
09-08 21:13:30.344  3814  3814 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:13:30.355  3814  3814 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6266b2d}
09-08 21:13:30.356  3814  3814 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:13:30.356  3814  3814 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 21:13:30.362  3814  3814 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 21:13:30.363  3814  3814 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 21:13:30.376  3814  3814 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 21:13:30.386  3814  3814 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 21:13:30.386  3814  3814 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 21:13:30.386  3814  3814 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 21:13:30.386  3814  3814 I Adreno  : Build Date                       : 10/20/15
09-08 21:13:30.386  3814  3814 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 21:13:30.386  3814  3814 I Adreno  : Local Branch                     : M14
09-08 21:13:30.386  3814  3814 I Adreno  : Remote Branch                    : 
09-08 21:13:30.386  3814  3814 I Adreno  : Remote Branch                    : 
09-08 21:13:30.386  3814  3814 I Adreno  : Reconstruct Branch               : 
,09-08 21:13:30.452   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@679c2dc:true
,09-08 21:13:30.503  3814  3814 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 21:13:30.520  3814  3814 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 21:13:30.615  3814  3853 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 21:13:30.639  3814  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 21:13:30.678  3814  3853 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 21:13:30.756   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +530ms
,09-08 21:13:30.769  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-08 21:13:30.804  3814  3814 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3814
,09-08 21:13:30.892  3814  3814 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 21:13:31.041   874  2042 I ActivityManager: Killing 3255:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 21:13:31.061  3814  3855 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1713768144
,09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 21:13:31.065  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd72488 added. We now have 1 listener(s)
,09-08 21:13:31.069  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 21:13:31.070  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:13:31.070  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 21:13:31.070  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 21:13:31.074  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cdc07 added. We now have 1 listener(s)
,09-08 21:13:31.074  3814  3855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:13:31.078   874  1317 D WifiService: New client listening to asynchronous messages
,09-08 21:13:31.079  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:13:31.079  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 21:13:31.079  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 21:13:31.079  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-08 21:13:31.079  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
09-08 21:13:31.089   874  2042 I ActivityManager: Killing 3165:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-08 21:13:31.131  3814  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:13:31.131  3814  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 21:13:31.135  3814  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:31.135  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:31.135  3814  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 21:13:31.135  3814  3855 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:13:31.136  3814  3855 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 21:13:31.274  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:31.275  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:31.277  3814  3814 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 21:13:31.935   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 21:13:32.296  3814  3865 W jxcore-log: Initializing JXcore engine
,09-08 21:13:32.296  3814  3865 W jxcore-log: JXcore engine is ready
,09-08 21:13:32.356  3865  3865 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8786 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 21:13:32.356  3865  3865 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12669]" dev="sockfs" ino=12669 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 21:13:32.356  3865  3865 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-08 21:13:32.356  3865  3865 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26059]" dev="sockfs" ino=26059 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 21:13:32.369  3814  3865 W jxcore-log: Starting JXcore engine
,09-08 21:13:32.477  3814  3865 W jxcore-log: Platform android
09-08 21:13:32.477  3814  3865 W jxcore-log: 
,09-08 21:13:32.477  3814  3865 W jxcore-log: Process ARCH arm
09-08 21:13:32.477  3814  3865 W jxcore-log: 
,09-08 21:13:32.734  3814  3865 I jxcore-log: JXcore Cordova bridge is ready!
09-08 21:13:32.734  3814  3865 I jxcore-log: 
,09-08 21:13:32.734  3814  3865 W jxcore-log: JXcore engine is started
,09-08 21:13:32.745  3814  3855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 21:13:32.750  3814  3814 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 21:13:34.960   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 21:13:37.301  3065  3873 V KeepSync: Connecting to GoogleApiClient
,09-08 21:13:37.302   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 21:13:37.363  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:13:37.365  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:13:37.407  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 21:13:37.408  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 21:13:37.408  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:13:37.408  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:37.447  1723  3874 V BaseAuthAsyncOperation: access token request failed
09-08 21:13:37.449  3065  3873 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 21:13:37.545  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 21:13:37.545  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 21:13:37.545  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:13:37.545  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:37.572  3065  3873 E KeepSync: IOException
09-08 21:13:37.572  3065  3873 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 21:13:37.572  3065  3873 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:13:37.572  3065  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 21:13:37.572  3065  3873 E KeepSync: 	... 10 more
,09-08 21:13:37.573  3065  3873 W KeepSync: Sync result 2
,09-08 21:13:37.580   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131720, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:13:44.053   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 21:13:44.331   874  2136 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:13:46.595  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 21:13:46.595  3814  3865 I jxcore-log: 
,09-08 21:13:46.597  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 21:13:46.597  3814  3865 I jxcore-log: 
,09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:46.605  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:46.611  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:13:46.618  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 21:13:46.618  3814  3865 I jxcore-log: 
,09-08 21:13:46.626  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 21:13:46.626  3814  3865 I jxcore-log: 
,09-08 21:13:47.007  3814  3865 D ExecuteNativeTests: Running unit tests
,09-08 21:13:47.101  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:13:47.101  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 added. We now have 2 listener(s)
09-08 21:13:47.103  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:13:47.103  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:13:47.103  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:13:47.103  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:13:47.103  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 added. We now have 2 listener(s)
09-08 21:13:47.103  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:13:47.103  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 21:13:47.110  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.123  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:47.129  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.130  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:13:47.138  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.139  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 21:13:47.139  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 21:13:47.140  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 21:13:47.144  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.145  3814  3865 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 21:13:47.146  3814  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 21:13:47.146  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 21:13:47.146  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 21:13:47.147  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 21:13:47.150  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.151  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.151  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:13:47.152  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.154  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.154  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.154  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:13:47.154  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 removed from the list
09-08 21:13:47.154  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.154  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 removed from the list
09-08 21:13:47.154  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.154  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.155  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.155  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.156  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.156  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.156  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.156  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.157  3814  3865 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 21:13:47.158  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-08 21:13:47.158  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.158  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.158  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.158  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.158  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.158  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.158  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.158  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.158  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.159  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.159  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.159  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.159  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.160  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:13:47.160  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.160  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.160  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 21:13:47.165  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 21:13:47.166  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 21:13:47.167  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 21:13:47.167  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.167  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:13:47.167  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.167  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.167  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.167  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.167  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
,09-08 21:13:47.167  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.168  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.168  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.168  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.168  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.168  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.168  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.169  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.169  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.169  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.169  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.170  3814  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-08 21:13:47.171  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.176  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:47.178  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:13:47.178  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:13:47.178  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:13:47.178  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 21:13:47.178  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 21:13:47.179  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.179  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.180  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.182  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.183  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:13:47.183  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 21:13:47.187  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 21:13:47.189  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 21:13:47.189  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 21:13:47.192  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 21:13:47.194  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 21:13:47.194  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 21:13:47.194  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 21:13:47.195  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 21:13:47.196  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.200  2719  2917 D BtGatt.GattService: registerClient() - UUID=3f6a4586-742f-4693-939d-45e9b08edccf
,09-08 21:13:47.201  2719  2770 D BtGatt.GattService: onClientRegistered() - UUID=3f6a4586-742f-4693-939d-45e9b08edccf, clientIf=5
09-08 21:13:47.202  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 21:13:47.203  2719  2731 D BtGatt.GattService: start scan with filters
,09-08 21:13:47.206  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 21:13:47.206  2719  2774 D BtGatt.ScanManager: handling starting scan
09-08 21:13:47.206  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 21:13:47.207  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:13:47.207  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 21:13:47.208  2719  2774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:47.209  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:13:47.210  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:13:47.211  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 21:13:47.212  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 21:13:47.215  3814  3865 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 21:13:47.216  2719  2770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 21:13:47.216  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.217  2719  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 21:13:47.218  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 21:13:47.218  3814  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 21:13:47.219  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:13:47.219  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 21:13:47.219  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.219  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:13:47.219  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 21:13:47.219  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:13:47.219  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 21:13:47.219  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:13:47.220  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 21:13:47.220  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 21:13:47.220  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.221  2719  2917 D BtGatt.GattService: stopScan() - queue size =1
,09-08 21:13:47.221  2719  2731 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 21:13:47.222  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.222  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:13:47.222  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 21:13:47.222  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 21:13:47.222  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 21:13:47.223  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.224  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.224  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:13:47.224  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.225  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.225  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:13:47.225  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.226  2719  2774 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:13:47.226  2719  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 21:13:47.227  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.227  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.227  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:13:47.229  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.229  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:13:47.233  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:13:47.233  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:13:47.233  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:13:47.233  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 21:13:47.234  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 21:13:47.235  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.235  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.235  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.235  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.235  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.235  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.235  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.235  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.235  3814  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 21:13:47.236  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.236  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.236  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.236  2719  2770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:13:47.236  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.237  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:13:47.239  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.239  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.239  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.241  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 21:13:47.241  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.242  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.246  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:47.247  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:13:47.248  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:13:47.248  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.248  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:13:47.248  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:13:47.248  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 21:13:47.248  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 21:13:47.248  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.248  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.250  2719  2774 D BtGatt.ScanManager: stopping BLe Batch
,09-08 21:13:47.250  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.252  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.253  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:13:47.256  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 21:13:47.256  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.257  2719  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 21:13:47.257  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 21:13:47.257  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 21:13:47.257  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 21:13:47.258  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.260  2719  2917 D BtGatt.GattService: registerClient() - UUID=1f3c1960-0b44-4472-88fb-403a09af0155
,09-08 21:13:47.260  2719  2770 D BtGatt.GattService: onClientRegistered() - UUID=1f3c1960-0b44-4472-88fb-403a09af0155, clientIf=5
09-08 21:13:47.261  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 21:13:47.261  2719  2733 D BtGatt.GattService: start scan with filters
,09-08 21:13:47.262  2719  2770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 21:13:47.262  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.264  2719  2774 D BtGatt.ScanManager: handling starting scan
,09-08 21:13:47.265  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 21:13:47.265  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 21:13:47.265  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:13:47.265  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 21:13:47.267  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:13:47.268  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:13:47.268  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 21:13:47.269  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 21:13:47.271  2719  2770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 21:13:47.271  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.271  2719  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 21:13:47.272  3814  3865 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 21:13:47.274  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 21:13:47.274  3814  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 21:13:47.274  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.274  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 21:13:47.274  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.274  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:13:47.275  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 21:13:47.275  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:13:47.275  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 21:13:47.275  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:13:47.275  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 21:13:47.275  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 21:13:47.276  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.276  2719  2918 D BtGatt.GattService: stopScan() - queue size =1
09-08 21:13:47.276  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:13:47.276  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.276  2719  2774 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:13:47.276  2719  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 21:13:47.277  2719  2917 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 21:13:47.277  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.277  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:13:47.277  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 21:13:47.277  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 21:13:47.277  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 21:13:47.278  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.278  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.278  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:13:47.278  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 21:13:47.279  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 21:13:47.280  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.280  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 21:13:47.280  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.280  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.280  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.280  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.280  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.280  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.280  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.280  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.280  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 21:13:47.282  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.282  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:13:47.285  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:13:47.285  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 21:13:47.285  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:13:47.285  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.286  2719  2770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:13:47.286  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.286  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.288  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 21:13:47.289  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.289  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.291  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 21:13:47.291  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.292  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:13:47.292  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.293  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.297  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 21:13:47.297  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.297  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.298  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:13:47.298  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:13:47.298  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.298  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.298  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.299  2719  2774 D BtGatt.ScanManager: stopping BLe Batch
,09-08 21:13:47.300  3814  3865 D BluetoothAdapter: STATE_ON,
09-08 21:13:47.300  3814  3865 D BluetoothLeScanner: could not find callback wrapper
,09-08 21:13:47.300  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.300  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.300  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.301  3814  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 21:13:47.303  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:13:47.304  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 21:13:47.304  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.304  2719  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.307  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:47.309  2719  2770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 21:13:47.309  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.310  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.310  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:13:47.310  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:13:47.311  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 21:13:47.313  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.313  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 21:13:47.313  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.314  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.315  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.317  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:13:47.323  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 21:13:47.323  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 21:13:47.323  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 21:13:47.323  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.327  2719  2918 D BtGatt.GattService: registerClient() - UUID=d41978de-f8ce-43d8-ac95-880ec6f8e1bf
,09-08 21:13:47.327  2719  2770 D BtGatt.GattService: onClientRegistered() - UUID=d41978de-f8ce-43d8-ac95-880ec6f8e1bf, clientIf=5
,09-08 21:13:47.328  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 21:13:47.328  2719  2917 D BtGatt.GattService: start scan with filters
,09-08 21:13:47.331  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 21:13:47.331  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 21:13:47.331  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:13:47.331  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 21:13:47.331  2719  2774 D BtGatt.ScanManager: handling starting scan,
,09-08 21:13:47.334  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:13:47.334  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:13:47.334  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 21:13:47.335  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 21:13:47.336  2719  2770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 21:13:47.337  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.337  2719  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 21:13:47.338  3814  3865 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 21:13:47.338  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.338  3814  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 21:13:47.338  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:13:47.338  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 21:13:47.338  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.338  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:13:47.338  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 21:13:47.338  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:13:47.338  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 21:13:47.338  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 21:13:47.338  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 21:13:47.339  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 21:13:47.339  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.339  2719  2731 D BtGatt.GattService: stopScan() - queue size =1
09-08 21:13:47.340  2719  2918 D BtGatt.GattService: unregisterClient() - clientIf=5,
09-08 21:13:47.340  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:13:47.340  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:13:47.340  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 21:13:47.340  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 21:13:47.341  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 21:13:47.341  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.341  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.341  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 21:13:47.341  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.342  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.342  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.342  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.342  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:13:47.343  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:13:47.343  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.342  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.343  3814  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 21:13:47.343  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.343  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.343  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.343  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.343  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:13:47.343  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.343  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.343  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.343  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.343  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.344  2719  2774 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:13:47.344  2719  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 21:13:47.345  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.345  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 21:13:47.348  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:13:47.348  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:13:47.348  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:13:47.348  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.349  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.350  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.350  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.350  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:13:47.352  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:13:47.352  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.352  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.354  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.354  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.354  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.355  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.355  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.355  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.356  2719  2770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:13:47.356  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.356  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.356  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.357  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:13:47.357  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.357  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.358  3814  3865 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 21:13:47.358  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.358  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.358  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.359  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.359  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.359  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.359  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.359  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.359  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.359  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.359  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.359  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.359  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.359  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.360  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 21:13:47.360  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.360  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.360  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.360  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.361  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.361  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.361  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.361  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.361  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.362  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 21:13:47.362  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.362  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.362  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:13:47.362  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.362  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.362  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.362  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.362  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.362  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.362  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.362  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.363  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.363  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.363  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.365  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.365  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 21:13:47.365  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.366  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.366  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.366  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.366  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.366  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.367  3814  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 21:13:47.367  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.367  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.367  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.367  2719  2770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:13:47.367  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.368  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.368  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.368  2719  2774 D BtGatt.ScanManager: stopping BLe Batch
09-08 21:13:47.368  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.368  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.368  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.368  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.368  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.368  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.368  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.368  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.368  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.370  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.370  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.370  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.370  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.370  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.371  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.371  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.371  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.371  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.371  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.372  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:13:47.372  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.372  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.372  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.372  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.372  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.372  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.372  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.372  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.372  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.373  2719  2770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 21:13:47.373  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:13:47.372  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.373  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.373  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.373  2719  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 21:13:47.374  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.374  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.374  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.375  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.375  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.375  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.375  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.375  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.376  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 21:13:47.377  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 21:13:47.378  2719  2770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 21:13:47.378  2719  2770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:13:47.378  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 21:13:47.380  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 21:13:47.380  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 21:13:47.380  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 21:13:47.380  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.380  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.380  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.380  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.381  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.381  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.381  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.381  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.381  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.381  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.381  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.381  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.381  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.381  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.384  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.384  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 21:13:47.384  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.385  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:13:47.385  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.385  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:13:47.385  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.385  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.386  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 21:13:47.386  3814  3865 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 21:13:47.386  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 21:13:47.388  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 21:13:47.388  3814  3865 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 21:13:47.388  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 21:13:47.388  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 21:13:47.388  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 21:13:47.388  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 21:13:47.389  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 21:13:47.390  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-08 21:13:47.390  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 21:13:47.390  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 21:13:47.390  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 21:13:47.390  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 21:13:47.390  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 21:13:47.391  3814  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 21:13:47.391  3814  3865 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 21:13:47.391  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 21:13:47.391  3814  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 21:13:47.392  3814  3865 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 21:13:47.392  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 21:13:47.392  3814  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 21:13:47.392  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 21:13:47.395  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-08 21:13:47.396  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 21:13:47.396  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-08 21:13:47.398  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-08 21:13:47.398  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 21:13:47.398  3814  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-08 21:13:47.398  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 21:13:47.399  3814  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 21:13:47.399  3814  3865 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-08 21:13:47.400  3814  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:13:47.402  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 21:13:47.402  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.402  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.403  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.403  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.403  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.404  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 21:13:47.405  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
,09-08 21:13:47.405  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.405  3814  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-08 21:13:47.406  3814  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
,09-08 21:13:47.406  3814  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
09-08 21:13:47.407  2719  2912 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,09-08 21:13:47.406  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.408  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.408  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.408  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:13:47.413  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.417  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.408  3814  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
,09-08 21:13:47.418  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.418  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.418  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.418  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.418  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.419  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:13:47.419  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.419  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.419  3814  3865 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 21:13:47.419  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.420  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.420  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:13:47.420  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.420  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.420  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-08 21:13:47.420  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.420  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.420  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.420  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.420  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.420  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.420  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.420  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.421  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.421  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.422  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.422  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.423  3814  3865 D BluetoothLeScanner: could not find callback wrapper
,09-08 21:13:47.423  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.423  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.423  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.423  3814  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 21:13:47.423  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.423  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.423  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.423  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.423  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.423  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.424  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.424  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.424  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.424  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 21:13:47.424  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.424  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.424  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.424  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.424  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:13:47.424  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.424  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:13:47.425  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.425  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.425  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.425  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:13:47.426  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.426  3814  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 21:13:47.426  3814  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 21:13:47.426  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 21:13:47.426  3814  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 21:13:47.426  3814  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 21:13:47.426  3814  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-08 21:13:47.426  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 21:13:47.426  3814  3865 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 21:13:47.427  3814  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-08 21:13:47.427  3814  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 21:13:47.427  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 21:13:47.427  3814  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 21:13:47.427  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.427  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:13:47.427  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.427  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:13:47.427  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.427  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.427  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.427  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.427  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
,09-08 21:13:47.427  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.427  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.428  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.428  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.428  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.429  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:13:47.429  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.429  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.430  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.430  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.430  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.430  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.430  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.430  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.430  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.430  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.431  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.431  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.431  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.431  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.431  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.431  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.431  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.431  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.431  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.431  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:13:47.431  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.431  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.431  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.431  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.431  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.431  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.431  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.431  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.431  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.431  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.432  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.432  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.432  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.432  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.432  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.432  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.433  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.433  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.433  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.434  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.434  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.434  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.434  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.434  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.435  3814  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 21:13:47.435  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.436  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 21:13:47.437  3814  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 21:13:47.437  3814  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 21:13:47.438  3814  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 21:13:47.438  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 21:13:47.438  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 21:13:47.439  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.439  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 21:13:47.439  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 21:13:47.439  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 21:13:47.439  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.439  3814  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 21:13:47.440  3814  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 21:13:47.440  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.440  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.440  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:13:47.440  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 21:13:47.441  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:13:47.441  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 21:13:47.441  3814  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 21:13:47.442  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.442  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.442  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.442  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.442  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:13:47.442  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.443  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.443  3814  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 21:13:47.443  3814  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 21:13:47.443  3814  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 21:13:47.444  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.444  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.444  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.444  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:13:47.445  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.445  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.445  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.446  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.446  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.446  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.446  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.446  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.447  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.447  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.447  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.447  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.447  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:13:47.447  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.447  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:13:47.452  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:13:47.453  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:13:47.453  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:13:47.453  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.454  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.458  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:13:47.458  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.458  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:13:47.462  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:13:47.462  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:13:47.463  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.466  3814  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 21:13:47.466  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:13:47.467  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.467  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.469  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.469  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.469  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.470  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.470  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.470  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.470  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.470  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.472  3814  3865 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 21:13:47.472  3814  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 21:13:47.473  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 21:13:47.475  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 21:13:47.475  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.475  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.476  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.476  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.477  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.477  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.477  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.477  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.477  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.477  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.477  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.478  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.478  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.478  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.479  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.480  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.480  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.481  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.481  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.481  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.481  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.481  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.488  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.488  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.488  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.489  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.489  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.489  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.489  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.489  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.489  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.490  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.490  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.490  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.490  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.490  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.492  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.492  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.492  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.493  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.493  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.494  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.494  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.494  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.495  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:13:47.495  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:13:47.495  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:13:47.496  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:13:47.496  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.496  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.496  3814  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0d783 not in the list
09-08 21:13:47.496  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.496  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.496  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:13:47.497  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.497  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.497  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:13:47.497  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:13:47.498  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:13:47.499  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:13:47.499  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:13:47.499  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:13:47.500  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:13:47.500  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:13:47.500  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:13:47.500  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187dd00 not in the list
09-08 21:13:47.501  3814  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 21:13:47.502  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 21:13:47.502  3814  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 21:13:47.502  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 21:13:47.502  3814  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 21:13:47.502  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 21:13:47.505  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 21:13:47.505  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 21:13:47.506  3814  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 21:13:47.506  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 21:13:47.507  3814  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 21:13:47.507  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 21:13:47.507  3814  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 21:13:47.507  3814  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 21:13:47.508  3814  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 21:13:47.508  3814  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 21:13:47.509  3814  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 21:13:47.509  3814  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 21:13:47.509  3814  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 21:13:47.509  3814  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 21:13:47.511  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:13:47.511  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed3e706 added. We now have 2 listener(s)
09-08 21:13:47.511  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:13:47.514  3814  3865 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 21:13:47.514   874  2116 D WifiService: setWifiEnabled: true pid=3814, uid=10000
09-08 21:13:47.514   874  2116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 21:13:47.516  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:13:47.516  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54161c7 added. We now have 3 listener(s)
09-08 21:13:47.516  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:13:47.525  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:13:47.525  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8b73f4 added. We now have 4 listener(s)
09-08 21:13:47.525  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:13:47.527  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:13:47.527  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e6ce71d added. We now have 5 listener(s)
09-08 21:13:47.527  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:13:47.530   874   885 D WifiService: setWifiEnabled: false pid=3814, uid=10000
09-08 21:13:47.530   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 21:13:47.535  2719  2765 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 21:13:47.535  2719  2765 D BluetoothAdapterProperties: Setting state to 13
09-08 21:13:47.535  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 21:13:47.535  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:13:47.536  2719  2765 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 21:13:47.537  2719  2765 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:13:47.540  2719  2719 D BluetoothMapService: onReceive
09-08 21:13:47.540  2719  2719 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 21:13:47.540  2719  2719 D BluetoothMapService: STATE_TURNING_OFF
09-08 21:13:47.540  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 21:13:47.541  2719  2719 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 21:13:47.541  2719  2719 D ObexServerSockets0: shutdown(block = true)
,09-08 21:13:47.542  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 21:13:47.542  2719  2929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 21:13:47.542  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 21:13:47.542  2719  2912 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 21:13:47.542  2719  2930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 21:13:47.543  2719  2719 I BtOppRfcommListener: stopping Accept Thread
09-08 21:13:47.543  2719  3458 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 21:13:47.543  2719  3458 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 21:13:47.545  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.545  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:13:47.546  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:47.546  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.546  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:13:47.550  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.554  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.560  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 21:13:47.561  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:47.561  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:13:47.563  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-08 21:13:47.564  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:13:47.564   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 21:13:47.564   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 21:13:47.564   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 21:13:47.565   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 21:13:47.565   874   887 I ActivityManager: Start proc 3884:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 21:13:47.566  2719  2770 D BluetoothAdapterProperties: Scan Mode:20
,09-08 21:13:47.566  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 21:13:47.574  2719  2719 D HeadsetService: Received stop request...Stopping profile...
09-08 21:13:47.578   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:47.578   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:47.579  1998  3548 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:47.580  1360  1716 D BluetoothHeadset: Proxy object disconnected
,09-08 21:13:47.580  1360  1360 D HeadsetProfile: Bluetooth service disconnected
09-08 21:13:47.580   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:47.583  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.583   874  2144 D DhcpClient: Clearing IP address
09-08 21:13:47.584   371   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 21:13:47.586  2719  2719 V BluetoothAdapterState: isTurningOff()=true,
09-08 21:13:47.586  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.586  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.587   371   872 D CommandListener: Setting iface cfg
,09-08 21:13:47.588  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.591  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:47.591  1509  2550 V NativeCrypto: Read error: ssl=0x9a184000: I/O error during system call, Connection timed out
,09-08 21:13:47.592   874  2156 D DhcpClient: Receive thread stopped
,09-08 21:13:47.593  1509  2550 V NativeCrypto: SSL shutdown failed: ssl=0x9a184000: I/O error during system call, Broken pipe
,09-08 21:13:47.594  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:47.595  2719  2719 D A2dpService: Received stop request...Stopping profile...
09-08 21:13:47.595   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 21:13:47.595   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 21:13:47.595  2719  2924 D A2dpStateMachine: Exit Disconnected: -1
,09-08 21:13:47.600   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 21:13:47.600   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 21:13:47.601   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 21:13:47.603  1360  1360 D BluetoothA2dp: Proxy object disconnected
09-08 21:13:47.603   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 21:13:47.606   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 21:13:47.609  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 21:13:47.609  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 21:13:47.609  2719  2770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-08 21:13:47.609  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:47.609  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:47.609  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 21:13:47.610  2719  2770 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 21:13:47.611  2719  2719 D HidService: Received stop request...Stopping profile...
,09-08 21:13:47.611  2719  2719 D HidService: Stopping Bluetooth HidService
09-08 21:13:47.612  1360  1360 D BluetoothInputDevice: Proxy object disconnected
,09-08 21:13:47.612  1360  1360 D HidProfile: Bluetooth service disconnected
09-08 21:13:47.612  2719  2719 D HealthService: Received stop request...Stopping profile...
09-08 21:13:47.612   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 21:13:47.614   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 21:13:47.616  2719  2719 D PanService: Received stop request...Stopping profile...
09-08 21:13:47.617  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 21:13:47.617  1360  1360 D PanProfile: Bluetooth service disconnected
09-08 21:13:47.618  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:47.618  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:13:47.618  2719  2719 D BluetoothMapService: Received stop request...Stopping profile...
09-08 21:13:47.618  2719  2719 D BluetoothMapService: stop()
09-08 21:13:47.618  1868  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 21:13:47.619  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:47.619  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:47.620  2719  2719 D BluetoothMapAppObserver: deinitObservers()
09-08 21:13:47.620  2719  2719 D BluetoothMapAppObserver: removeReceiver()
09-08 21:13:47.624   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 21:13:47.626  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:47.626  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:47.626  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:47.626  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:47.626  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.626  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:47.627  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:47.627  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:47.628  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:47.628  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.628  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.628  2719  2770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 21:13:47.628  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:47.628  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 21:13:47.628  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 21:13:47.628  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 21:13:47.629  2719  2894 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 21:13:47.629  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 21:13:47.629  2719  2894 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 21:13:47.629  2719  2894 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 21:13:47.629  2719  2770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 21:13:47.629  2719  2894 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:47.629  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 21:13:47.629  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.629  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.630  2719  2770 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 21:13:47.630  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:47.630  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 21:13:47.630  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 21:13:47.634  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 21:13:47.634  2719,  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:47.634  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:47.634  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:47.634  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:47.634  1360  1360 D BluetoothMap: Proxy object disconnected
09-08 21:13:47.634  1360  1360 D MapProfile: Bluetooth service disconnected
09-08 21:13:47.635  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 21:13:47.635  2719  2765 D BluetoothAdapterProperties: Setting state to 15
09-08 21:13:47.635  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 21:13:47.635  2719  2765 I BluetoothAdapterState: Entering BleOnState
09-08 21:13:47.636  2719  2719 D BluetoothMapService: cleanup()
09-08 21:13:47.636  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 21:13:47.636  1360  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 21:13:47.636  1360  1372 D BluetoothPan: onBluetoothStateChange on: false
09-08 21:13:47.637  1360  1716 D BluetoothMap: onBluetoothStateChange: up=false
09-08 21:13:47.640   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:47.640   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:47.641  1998  2009 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:47.641   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 21:13:47.641  1360  1378 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 21:13:47.642  1360  1716 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 21:13:47.643  1360  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:47.644   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:47.645  2719  2765 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 21:13:47.645  2719  2765 D BluetoothAdapterProperties: Setting state to 16
09-08 21:13:47.645  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 21:13:47.645  2719  2765 D BluetoothAdapterProperties: onBleDisable
09-08 21:13:47.645  2719  2765 I BluetoothAdapterState: Entering PendingCommandState
09-08 21:13:47.645  2719  2766 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 21:13:47.646  2719  2770 D BluetoothAdapterProperties: Scan Mode:20
09-08 21:13:47.647  2719  2894 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 21:13:47.647  2719  2894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 21:13:47.648  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:47.648  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:47.649  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.651  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.652  3814  3814 V io.jxcore.node.Conn,ectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.659  3884  3884 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-08 21:13:47.665   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 21:13:47.670  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 21:13:47.676  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 21:13:47.684   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6bfb18:true
09-08 21:13:47.687   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 21:13:47.688   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 21:13:47.688   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 21:13:47.689   874  2075 I ActivityManager: Start proc 3900:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-08 21:13:47.692   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 21:13:47.694  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.695  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:47.698  3446  3446 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@201ba0f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 21:13:47.708  3884  3884 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 21:13:47.709  3884  3884 D BluetoothMap: Create BluetoothMap proxy object
09-08 21:13:47.716  3884  3884 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 21:13:47.729  3900  3900 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 21:13:47.731  3884  3884 D DockEventReceiver: finishStartingService: stopping service
,09-08 21:13:47.734   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 21:13:47.738   874   885 I ActivityManager: Killing 3007:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 21:13:47.738   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 21:13:47.850  2719  2770 I bt_hci  : shut_down
,09-08 21:13:47.850  2719  2775 D bt_hwcfg: hw_epilog_process
,09-08 21:13:47.851  2719  2775 I bt_vendor: low_power_mode_cb
,09-08 21:13:47.879  2719  2775 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 21:13:47.879  2719  2775 I bt_vendor: epilog_cb
09-08 21:13:47.880  2719  2775 I bt_hci  : epilog_finished_callback
,09-08 21:13:47.887  2719  2770 I bt_hci_h4: hal_close
,09-08 21:13:47.888  2719  2770 I bt_userial_vendor: device fd = 51 close
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.954  3900  3900 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:13:47.954  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 21:13:47.967  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 21:13:47.991   874  1693 I ActivityManager: Start proc 3934:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 21:13:47.992   874  1693 I ActivityManager: Killing 3446:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 21:13:48.060  3900  3927 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 21:13:48.089  2719  2766 D bt_stack_manager: event_shut_down_stack finished.
,09-08 21:13:48.090  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 21:13:48.090  3934  3934 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 21:13:48.093  2719  2719 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 21:13:48.093  2719  2765 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 21:13:48.094  2719  2719 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 21:13:48.094  2719  2719 D BtGatt.GattService: stop()
,09-08 21:13:48.095  2719  2719 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 21:13:48.109  2719  2719 V BluetoothAdapterState: isTurningOff()=false
09-08 21:13:48.109  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:48.109  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:48.109  2719  2719 V BluetoothAdapterState: isBleTurningOff()=true
09-08 21:13:48.110  2719  2765 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 21:13:48.110  2719  2765 D BluetoothAdapterProperties: Setting state to 10
09-08 21:13:48.110  2719  2765 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 21:13:48.111  2719  2765 I BluetoothAdapterState: Entering OffState
09-08 21:13:48.114   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 21:13:48.125  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 21:13:48.125  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 21:13:48.125  2719  2766 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-08 21:13:48.127  2719  2766 D bt_stack_manager: event_clean_up_stack finished.
09-08 21:13:48.127  2719  2719 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 21:13:48.135  2719  2719 I art     : System.exit called, status: 0
,09-08 21:13:48.135  2719  2719 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 21:13:48.205   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@954f3ea:true
,09-08 21:13:48.227   874  2074 I ActivityManager: Process com.android.bluetooth (pid 2719) has died
,09-08 21:13:48.242  3934  3934 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 21:13:48.271  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 21:13:48.297   874  2075 I ActivityManager: Start proc 3962:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-08 21:13:48.299  3884  3884 D DockEventReceiver: finishStartingService: stopping service
,09-08 21:13:48.386  3962  3962 D AdapterServiceConfig: Adding HeadsetService
,09-08 21:13:48.386  3962  3962 D AdapterServiceConfig: Adding A2dpService
,09-08 21:13:48.387  3962  3962 D AdapterServiceConfig: Adding HidService
,09-08 21:13:48.387  3962  3962 D AdapterServiceConfig: Adding HealthService
09-08 21:13:48.387  3962  3962 D AdapterServiceConfig: Adding PanService
,09-08 21:13:48.387  3962  3962 D AdapterServiceConfig: Adding GattService
09-08 21:13:48.387  3962  3962 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 21:13:48.389   874  2072 I ActivityManager: Killing 3510:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 21:13:48.423  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 21:13:48.445  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 21:13:48.460  1723  1723 D SystemUpdateService: onCreate
,09-08 21:13:48.468  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 21:13:48.472  1723  3974 I SystemUpdateService: active receiver: enabled
,09-08 21:13:48.477  1723  3974 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 21:13:48.488  1723  3974 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 21:13:48.488  1723  3974 I SystemUpdateService: now status is 0 (complete)
09-08 21:13:48.488  1723  3974 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 21:13:48.488  1723  3974 I SystemUpdateService: file has been verified
09-08 21:13:48.488  1723  3974 I SystemUpdateService: OTA package size = 12249756
,09-08 21:13:48.492  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 21:13:48.493  1723  2528 I iu.UploadsManager: num queued entries: 0
,09-08 21:13:48.494  1723  2528 I iu.UploadsManager: num updated entries: 0
,09-08 21:13:48.494  1723  2528 I iu.SyncManager: NEXT; no task
09-08 21:13:48.494  1723  3974 I SystemUpdateService: showing system update notification
,09-08 21:13:48.505  1723  1723 D SystemUpdateService: onDestroy
,09-08 21:13:48.510  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 21:13:48.511  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 21:13:48.526   874  1392 I ActivityManager: Start proc 3976:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 21:13:48.569  3976  3976 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 21:13:48.572  3976  3976 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 21:13:48.580  3976  3976 D SprintDMHelper: simOperator: 
,09-08 21:13:48.580  3976  3976 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 21:13:48.611   874  1693 I ActivityManager: Start proc 3988:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher,
,09-08 21:13:48.612   874  1693 I ActivityManager: Killing 1694:android.process.acore/u0a5 (adj 15): empty #17
,09-08 21:13:48.762   874  1693 I ActivityManager: Start proc 4003:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 21:13:48.765  3116  4002 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 21:13:48.768   874  2072 I ActivityManager: Killing 3669:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 21:13:48.829  4003  4003 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 21:13:48.872  4003  4003 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 21:13:48.872  4003  4003 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 21:13:48.872  4003  4003 I GAv4    :   adb logcat -s GAv4
,09-08 21:13:48.892  4003  4003 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 21:13:48.898  4003  4003 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 21:13:48.924  4003  4020 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 21:13:49.072  4003  4003 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 21:13:49.104  4003  4003 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 21:13:49.119  4003  4003 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 3602-3612)
,09-08 21:13:49.119  4003  4003 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 21:13:49.130  4003  4003 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36be191}
,09-08 21:13:49.130  4003  4003 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 21:13:49.131  4003  4003 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 21:13:49.141  4003  4003 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 21:13:49.143  4003  4003 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 21:13:49.164  4003  4003 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 21:13:49.176  4003  4003 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 21:13:49.176  4003  4003 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 21:13:49.176  4003  4003 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 21:13:49.176  4003  4003 I Adreno  : Build Date                       : 10/20/15
09-08 21:13:49.176  4003  4003 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 21:13:49.176  4003  4003 I Adreno  : Local Branch                     : M14
09-08 21:13:49.176  4003  4003 I Adreno  : Remote Branch                    : 
09-08 21:13:49.176  4003  4003 I Adreno  : Remote Branch                    : 
09-08 21:13:49.176  4003  4003 I Adreno  : Reconstruct Branch               : 
,09-08 21:13:49.244  4003  4003 I NSApplication: Starting up...
,09-08 21:13:49.252  4003  4049 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 21:13:49.287   874  2075 I ActivityManager: Start proc 4054:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 21:13:49.293   874  2075 I ActivityManager: Killing 3683:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 21:13:49.370  4054  4054 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 21:13:49.588   874  1711 I ActivityManager: Killing 3491:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 21:13:50.549   874  2072 D WifiService: setWifiEnabled: true pid=3814, uid=10000
,09-08 21:13:50.550   874  2072 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 21:13:50.573   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-08 21:13:50.582  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:50.583  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:13:50.584  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:50.584  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:13:50.587  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:50.588  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:50.588  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:50.588  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:13:50.603   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-08 21:13:50.605   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 21:13:50.606   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 21:13:50.606   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 21:13:50.607   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 21:13:50.607   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 21:13:50.607   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 21:13:50.622   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 21:13:50.623   371   872 D CommandListener: Setting iface cfg
,09-08 21:13:50.624   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-08 21:13:50.624   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 21:13:50.626   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=6.88 delta 1000 -> 1000
,09-08 21:13:50.626   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
09-08 21:13:50.627   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 21:13:50.646   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 21:13:50.646   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 21:13:50.652   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 21:13:50.710   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 21:13:50.715  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 21:13:51.149  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 21:13:51.198  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 21:13:51.200  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 21:13:51.208   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 21:13:51.226   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 21:13:51.227   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 21:13:51.227   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 21:13:51.251   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 21:13:51.263   371   872 D CommandListener: Setting iface cfg
,09-08 21:13:51.264   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 21:13:51.279   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-08 21:13:51.283   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 21:13:51.308   874  4079 D DhcpClient: Receive thread started
,09-08 21:13:51.395   874  1316 E native  : do suspend false
,09-08 21:13:51.419   874  2144 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 21:13:51.433   874  4079 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172677, domain null
,09-08 21:13:51.434   874  2144 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172677 seconds
,09-08 21:13:51.457   874  2144 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 21:13:51.472   874  4079 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 21:13:51.473   874  2144 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 21:13:51.477   371   872 D CommandListener: Setting iface cfg
,09-08 21:13:51.480   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 21:13:51.487   874  2144 D DhcpClient: Scheduling renewal in 86399s
,09-08 21:13:51.494   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 21:13:51.496   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 21:13:51.497   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 21:13:51.497   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 21:13:51.498   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 21:13:51.519   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 21:13:51.536   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 21:13:51.536   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 21:13:51.537   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-08 21:13:51.538   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 21:13:51.539   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 21:13:51.551   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 21:13:51.555   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-08 21:13:51.555   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 21:13:51.556   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 21:13:51.556   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 21:13:51.556   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 21:13:51.556   874  1318 D ConnectivityService:    accepting network in place of null
09-08 21:13:51.557   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 21:13:51.570   874  4078 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 21:13:51.574   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:13:51.594   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:13:51.597   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 21:13:51.597   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 21:13:51.599   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 21:13:51.599   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 21:13:51.603  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:51.604  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:51.604  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:51.604  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:51.605  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:13:51.605  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:13:51.606  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:51.606  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:13:51.611  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 21:13:51.613  1723  1723 D SystemUpdateService: onCreate
,09-08 21:13:51.616  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 21:13:51.619  1723  4089 I SystemUpdateService: active receiver: enabled
,09-08 21:13:51.629  1723  4089 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 21:13:51.632  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 21:13:51.633  1723  2528 I iu.UploadsManager: num queued entries: 0
,09-08 21:13:51.633  1723  2528 I iu.UploadsManager: num updated entries: 0
,09-08 21:13:51.634  1723  2528 I iu.SyncManager: NEXT; no task
,09-08 21:13:51.634  1723  4089 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 21:13:51.635  1723  4089 I SystemUpdateService: now status is 0 (complete)
09-08 21:13:51.635  1723  4089 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 21:13:51.635  1723  4089 I SystemUpdateService: file has been verified
,09-08 21:13:51.635  1723  4089 I SystemUpdateService: OTA package size = 12249756
,09-08 21:13:51.637  1723  4089 I SystemUpdateService: showing system update notification
,09-08 21:13:51.640  1723  4094 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 21:13:51.640  1723  4094 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 21:13:51.641  1723  4094 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
09-08 21:13:51.642  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 21:13:51.643  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 21:13:51.645   874  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-08 21:13:51.646  3976  3976 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 21:13:51.648  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:13:51.649  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 21:13:51.650  3976  3976 D SprintDMHelper: simOperator: 
09-08 21:13:51.650  3976  3976 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 21:13:51.660  1723  1723 D SystemUpdateService: onDestroy
,09-08 21:13:51.687  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 21:13:51.687  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 21:13:51.687  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:13:51.687  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:51.701  1723  4094 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-08 21:13:51.705   874  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 19:13:51 GMT], X-Android-Received-Millis=[1473362031704], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473362031681]}
,09-08 21:13:51.706   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 21:13:51.706   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-08 21:13:51.706   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 21:13:51.707   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 21:13:51.755  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:13:51.772  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 21:13:51.773  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 21:13:51.773  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:13:51.773  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:51.781  3116  4096 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 21:13:51.802  3555  3555 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 21:13:51.802  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 21:13:51.802  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 21:13:51.841  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:13:51.841  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 21:13:51.842  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:13:51.842  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:51.861  3023  4100 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 21:13:51.861  3023  4100 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at blb.a(PG:3937)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at czp.a(PG:18188)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:13:51.861  3023  4100 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	... 12 more
09-08 21:13:51.861  3023  4100 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at fal.a(PG:38)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:13:51.861  3023  4100 E HttpOperation: 	... 14 more
,09-08 21:13:51.924  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 21:13:51.924  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:13:51.924  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:13:51.924  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:13:51.957  3023  4100 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 21:13:51.957  3023  4100 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at hec.a(PG:42)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at hee.a(PG:102)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at czr.a(PG:65)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at kka.a(PG:108)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at czp.a(PG:19176)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:13:51.957  3023  4100 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	... 15 more
09-08 21:13:51.957  3023  4100 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at fal.a(PG:38)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:13:51.957  3023  4100 E HttpOperation: 	... 17 more
,09-08 21:13:51.958  3023  4100 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 21:13:51.958  3023  4100 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at hec.a(PG:42)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at hee.a(PG:102)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at czr.a(PG:65)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at kka.a(PG:108)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113),
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	... 15 more
09-08 21:13:51.958  3023  4100 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at fal.a(PG:38)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 21:13:51.958  3023  4100 E ExperimentLoader: 	... 17 more
,09-08 21:13:52.050   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 132245, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:13:52.598   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 21:13:53.296   874   884 I ActivityManager: Killing 3635:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-08 21:13:53.566   874  1712 D WifiService: setWifiEnabled: false pid=3814, uid=10000
,09-08 21:13:53.566   874  1712 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 21:13:53.606  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 21:13:53.614   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 21:13:53.615   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 21:13:53.615   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 21:13:53.615   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 21:13:53.639   874  2144 D DhcpClient: Clearing IP address
,09-08 21:13:53.640   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 21:13:53.645   371   872 D CommandListener: Setting iface cfg
,09-08 21:13:53.648  1509  4104 V NativeCrypto: Read error: ssl=0x9a184000: I/O error during system call, Connection timed out
,09-08 21:13:53.652  1509  4104 V NativeCrypto: SSL shutdown failed: ssl=0x9a184000: I/O error during system call, Broken pipe
,09-08 21:13:53.661   874  1611 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-08 21:13:53.661   874  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-08 21:13:53.663   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 21:13:53.663   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 21:13:53.668   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 21:13:53.668   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 21:13:53.669   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 21:13:53.670   874  4079 D DhcpClient: Receive thread stopped
09-08 21:13:53.672   874  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-08 21:13:53.674   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 21:13:53.678   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 21:13:53.678   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 21:13:53.680  1868  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 21:13:53.681  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:53.682  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:53.682  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:53.682  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:53.683  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:53.683  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:53.683  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:53.683  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:13:53.685   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 21:13:53.704   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:13:53.732   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:13:53.733   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 21:13:53.733   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 21:13:53.737   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 21:13:53.738  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:53.739  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:53.747  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 21:13:53.751  1723  1723 D SystemUpdateService: onCreate
,09-08 21:13:53.753  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 21:13:53.761  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 21:13:53.768  1723  4116 I SystemUpdateService: active receiver: enabled
,09-08 21:13:53.763  1723  2528 I iu.UploadsManager: num queued entries: 0
,09-08 21:13:53.770  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 21:13:53.771  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 21:13:53.774  1723  2528 I iu.UploadsManager: num updated entries: 0
,09-08 21:13:53.774  1723  2528 I iu.SyncManager: NEXT; no task
,09-08 21:13:53.777  3976  3976 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-08 21:13:53.786  3976  3976 D SprintDMHelper: simOperator: 
09-08 21:13:53.786  3976  3976 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 21:13:53.813  1723  4116 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 21:13:53.817  3116  4120 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 21:13:53.822   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 21:13:53.823   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 21:13:53.823   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 21:13:53.825  1723  4116 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 21:13:53.825  1723  4116 I SystemUpdateService: now status is 0 (complete)
09-08 21:13:53.826  1723  4116 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 21:13:53.826  1723  4116 I SystemUpdateService: file has been verified
,09-08 21:13:53.827  1723  4116 I SystemUpdateService: OTA package size = 12249756
,09-08 21:13:53.832  1723  4116 I SystemUpdateService: showing system update notification
,09-08 21:13:53.841  1723  1723 D SystemUpdateService: onDestroy
,09-08 21:13:56.615   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e87ffd1:true
,09-08 21:13:56.615  3962  3962 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 21:13:56.621  3962  3962 I bt_bluedroid: init
,09-08 21:13:56.622  3962  4124 I BluetoothAdapterState: Entering OffState
,09-08 21:13:56.627  3962  4125 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 21:13:56.627  3962  4125 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 21:13:56.627  3962  4125 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 21:13:56.628  3962  4125 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 21:13:56.630  3962  3962 I bt_bluedroid: get_profile_interface socket
09-08 21:13:56.632  3962  3962 I bt_bluedroid: get_profile_interface sdp
09-08 21:13:56.635  3962  4128 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 21:13:56.637  3962  4128 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 21:13:56.640  3962  3972 I bt_bluedroid: config_hci_snoop_log
,09-08 21:13:56.644   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 21:13:56.656  3962  4124 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 21:13:56.657  3962  4124 D BluetoothAdapterProperties: Setting state to 14
09-08 21:13:56.658  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 21:13:56.663  3962  4124 D BluetoothBondStateMachine: make
,09-08 21:13:56.668  3962  4129 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 21:13:56.677  3962  4124 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:13:56.680  3962  3962 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 21:13:56.688  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:56.690  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 21:13:56.692  3962  3962 D BtGatt.GattService: Received start request. Starting profile...
,09-08 21:13:56.692  3962  3962 D BtGatt.GattService: start()
09-08 21:13:56.692  3962  3962 I bt_bluedroid: get_profile_interface gatt
,09-08 21:13:56.695  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:56.696  3962  3962 D BtGatt.AdvertiseManager: advertise manager created
,09-08 21:13:56.715  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:13:56.716  3962  3962 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:56.716  3962  3962 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 21:13:56.716  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:56.718  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 21:13:56.718  3962  4124 I bt_bluedroid: enable
,09-08 21:13:56.719  3962  4125 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 21:13:56.720  3962  4125 I bt_hci  : start_up
,09-08 21:13:56.746  3962  4125 I bt_vendor: alloc value 0xb39e9189
,09-08 21:13:56.746  3962  4125 I bt_vendor: init
,09-08 21:13:56.746  3962  4125 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 21:13:56.746  3962  4125 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 21:13:56.858  3962  4125 D bt_hci  : start_up starting async portion
,09-08 21:13:56.858  3962  4132 I bt_hci  : event_finish_startup,
09-08 21:13:56.859  3962  4132 I bt_hci_h4: hal_open
09-08 21:13:56.859  3962  4132 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 21:13:56.867  3962  4132 I bt_userial_vendor: device fd = 51 open
,09-08 21:13:56.898  3962  4132 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 21:13:56.929  3962  4132 D bt_hwcfg: Chipset BCM4354A2
,09-08 21:13:56.930  3962  4132 D bt_hwcfg: Target name = [BCM4354A2]
09-08 21:13:56.931  3962  4132 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 21:13:57.603  3962  4132 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 21:13:57.605  3962  4132 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 21:13:57.605  3962  4132 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 21:13:57.722  3962  4132 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 21:13:57.723  3962  4132 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 21:13:57.752  3962  4132 I bt_hwcfg: vendor lib fwcfg completed
,09-08 21:13:57.752  3962  4132 I bt_vendor: firmware callback
09-08 21:13:57.753  3962  4132 I bt_hci  : firmware_config_callback
,09-08 21:13:57.763  3962  4134 I bt_btu  : btu_task pending for preload complete event
,09-08 21:13:57.764  3962  4134 I bt_btu_task: Bluetooth chip preload is complete
09-08 21:13:57.764  3962  4134 I bt_btu  : btu_task received preload complete event
,09-08 21:13:57.773  3962  4134 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 21:13:57.774  3962  4134 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 21:13:57.774  3962  4134 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 21:13:57.774  3962  4134 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 21:13:57.775  3962  4134 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 21:13:57.775  3962  4134 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 21:13:57.775  3962  4134 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 21:13:57.775  3962  4134 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 21:13:57.776  3962  4134 I         : BTE_InitTraceLevels -- TRC_GAP
,09-08 21:13:57.776  3962  4134 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 21:13:57.776  3962  4134 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 21:13:57.777  3962  4134 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 21:13:57.777  3962  4134 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 21:13:57.777  3962  4134 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 21:13:57.778  3962  4134 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 21:13:57.913  3962  4134 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,09-08 21:13:57.913  3962  4134 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,09-08 21:13:57.937  3962  4128 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-08 21:13:57.938  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 21:13:57.939  3962  4128 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 21:13:57.946  3962  4128 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 21:13:57.951  3962  4128 D BluetoothAdapterProperties: Scan Mode:20
09-08 21:13:57.952  3962  4128 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 21:13:57.953  3962  4128 D bt_hci  : do_postload posting postload work item
09-08 21:13:57.953  3962  4132 I bt_hci  : event_postload
,09-08 21:13:57.953  3962  4132 I bt_vendor: sco_config_cb
,09-08 21:13:57.954  3962  4132 I bt_hci  : sco_config_callback postload finished.
,09-08 21:13:57.957  3962  4128 D bt_bte_conf: Device ID record 1 : primary
,09-08 21:13:57.958  3962  4128 D bt_bte_conf:   vendorId            = 000f
,09-08 21:13:57.958  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:57.958  3962  4128 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 21:13:57.958  3962  4128 D bt_bte_conf:   product             = 1200
09-08 21:13:57.958  3962  4128 D bt_bte_conf:   version             = 1436
,09-08 21:13:57.958  3962  4128 D bt_bte_conf:   clientExecutableURL = 
09-08 21:13:57.959  3962  4128 D bt_bte_conf:   serviceDescription  = 
,09-08 21:13:57.959  3962  4128 D bt_bte_conf:   documentationURL    = 
,09-08 21:13:57.959  3962  4128 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 21:13:57.960  3962  4125 D bt_stack_manager: event_start_up_stack finished
09-08 21:13:57.961  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-08 21:13:57.962  3962  4124 D BluetoothAdapterProperties: Setting state to 15
,09-08 21:13:57.962  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:57.962  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 21:13:57.965  3962  4124 I BluetoothAdapterState: Entering BleOnState
09-08 21:13:57.967  3962  4132 I bt_vendor: low_power_mode_cb
09-08 21:13:57.972  3962  4124 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 21:13:57.972  3962  4124 D BluetoothAdapterProperties: Setting state to 11
09-08 21:13:57.972  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 21:13:57.983  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
09-08 21:13:57.984  3962  3962 D HeadsetService: Received start request. Starting profile...
09-08 21:13:57.987  3962  3962 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 21:13:57.987  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:57.987  3962  3962 D HeadsetStateMachine: make
09-08 21:13:57.992  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:58.001  3962  3962 D HeadsetStateMachine: max_hf_connections = 1
,09-08 21:13:58.001  3962  3962 I bt_bluedroid: get_profile_interface handsfree
09-08 21:13:58.001  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 21:13:58.001  3962  4128 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-08 21:13:58.002  3962  4124 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:13:58.011  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:58.012  3962  3962 D A2dpService: Received start request. Starting profile...,
,09-08 21:13:58.013  3962  3962 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 21:13:58.013  3962  3962 I bt_bluedroid: get_profile_interface avrcp
,09-08 21:13:58.019  3962  3962 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 21:13:58.020  3962  3962 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 21:13:58.020  3962  3962 D A2dpStateMachine: make
,09-08 21:13:58.021  3962  3962 I bt_bluedroid: get_profile_interface a2dp
,09-08 21:13:58.023  3962  3962 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 21:13:58.021  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 21:13:58.024  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
09-08 21:13:58.024  3962  4144 D A2dpStateMachine: Enter Disconnected: -2
09-08 21:13:58.025  3884  3884 D BluetoothInputDevice: Proxy object connected
09-08 21:13:58.026  3962  3962 D HidService: Received start request. Starting profile...
09-08 21:13:58.026  3884  3884 D HidProfile: Bluetooth service connected
09-08 21:13:58.026  3962  3962 I bt_bluedroid: get_profile_interface hidhost
09-08 21:13:58.027  3962  3962 D HidService: setHidService(): set to: null
09-08 21:13:58.027  3962  4128 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
09-08 21:13:58.027  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 21:13:58.027  3962  3962 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 21:13:58.028  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
09-08 21:13:58.028  3962  3962 D HealthService: Received start request. Starting profile...
,09-08 21:13:58.030  3962  3962 I bt_bluedroid: get_profile_interface health
,09-08 21:13:58.030  3962  3962 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 21:13:58.031  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:58.032  3884  3884 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 21:13:58.032  3962  3962 D PanService: Received start request. Starting profile...
09-08 21:13:58.033  3962  3962 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 21:13:58.033  3962  3962 I bt_bluedroid: get_profile_interface pan
09-08 21:13:58.033  3884  3884 D PanProfile: Bluetooth service connected
09-08 21:13:58.033  3962  4128 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 21:13:58.035  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:13:58.037  3884  3884 D BluetoothMap: Proxy object connected
,09-08 21:13:58.037  3962  3962 D BluetoothMapService: Received start request. Starting profile...
09-08 21:13:58.037  3962  3962 D BluetoothMapService: start()
09-08 21:13:58.037  3884  3884 D MapProfile: Bluetooth service connected
09-08 21:13:58.037  3884  3884 D BluetoothMap: getConnectedDevices()
09-08 21:13:58.038  3884  3884 D BluetoothMap: Bluetooth is Not enabled
,09-08 21:13:58.039  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 21:13:58.039  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 21:13:58.039  3962  3962 D BluetoothMapAppObserver: createReceiver()
,09-08 21:13:58.040  3962  3962 D BluetoothMapAppObserver: initObservers()
09-08 21:13:58.041  3962  3962 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 21:13:58.047  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:13:58.047  3962  3962 V BluetoothAdapterState: isTurningOn()=true
09-08 21:13:58.047  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:58.047  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false,
09-08 21:13:58.047  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isTurningOn()=true
09-08 21:13:58.049  3962  4142 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isTurningOff()=false
09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isTurningOn()=true
,09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:58.049  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isTurningOn()=true
,09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isTurningOff()=false
09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isTurningOn()=true
,09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:13:58.050  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:58.051  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:13:58.051  3962  3962 V BluetoothAdapterState: isTurningOn()=true
,09-08 21:13:58.051  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:58.051  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:58.051  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 21:13:58.052  3962  4124 D BluetoothAdapterProperties: ScanMode =  20
09-08 21:13:58.052  3962  4124 D BluetoothAdapterProperties: State =  11
09-08 21:13:58.052  3962  4124 D BluetoothAdapterProperties: Setting state to 12,
,09-08 21:13:58.052  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 21:13:58.053  3962  4124 I BluetoothAdapterState: Entering OnState
,09-08 21:13:58.053  3884  3894 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 21:13:58.053  3962  4128 D BluetoothAdapterProperties: Scan Mode:21
,09-08 21:13:58.053  3962  4128 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 21:13:58.054  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:58.057  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:13:58.059  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:13:58.059  1360  1360 D BluetoothA2dp: Proxy object connected
09-08 21:13:58.059  3884  3895 D BluetoothPan: onBluetoothStateChange on: true
,09-08 21:13:58.060  3884  3894 D BluetoothMap: onBluetoothStateChange: up=true
09-08 21:13:58.061  1360  1716 D BluetoothPan: onBluetoothStateChange on: true
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:58.063  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:58.063  1360  1378 D BluetoothMap: onBluetoothStateChange: up=true
09-08 21:13:58.063  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 21:13:58.064  1360  1360 D PanProfile: Bluetooth service connected
09-08 21:13:58.065  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:58.065   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:13:58.065  1360  1360 D BluetoothMap: Proxy object connected
09-08 21:13:58.065  1360  1360 D MapProfile: Bluetooth service connected
,09-08 21:13:58.065  1360  1360 D BluetoothMap: getConnectedDevices()
09-08 21:13:58.065  3884  3895 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 21:13:58.066  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 21:13:58.066  3962  3962 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 21:13:58.068   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 21:13:58.068  1998  2010 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:13:58.069   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 21:13:58.069  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 21:13:58.069   874   874 D BluetoothA2dp: Proxy object connected
09-08 21:13:58.069  1360  1716 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 21:13:58.071  1360  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 21:13:58.071  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 21:13:58.072  1360  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:13:58.072  1360  1360 D BluetoothInputDevice: Proxy object connected
,09-08 21:13:58.072  1360  1360 D HidProfile: Bluetooth service connected
09-08 21:13:58.073  3962  3962 D ObexServerSockets: Succeed to create listening sockets 
09-08 21:13:58.074  3962  3962 D ObexServerSockets0: startAccept()
09-08 21:13:58.074  3962  3962 D ObexServerSockets0: prepareForNewConnect()
09-08 21:13:58.074   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 21:13:58.076  3962  3962 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 21:13:58.076  3962  3962 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 21:13:58.077   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 21:13:58.077  3962  4149 D ObexServerSockets0: Accepting socket connection...
09-08 21:13:58.078  3962  4150 D ObexServerSockets0: Accepting socket connection...
,09-08 21:13:58.078  3962  3962 D BluetoothMapService: onReceive
09-08 21:13:58.078  3962  3962 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 21:13:58.078  3962  3962 D BluetoothMapService: STATE_ON
09-08 21:13:58.079  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:58.081  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:58.081  3884  3884 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 21:13:58.084  3884  3884 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 21:13:58.090  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 21:13:58.092  3884  3884 D BluetoothA2dp: Proxy object connected
,09-08 21:13:58.096  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 21:13:58.103  3884  3884 D DockEventReceiver: finishStartingService: stopping service
,09-08 21:13:58.104  1360  1360 D BluetoothPbap: Proxy object connected
09-08 21:13:58.104  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 21:13:58.104  3962  3962 D ObexServerSockets0: prepareForNewConnect()
09-08 21:13:58.104  1360  1360 D PbapServerProfile: Bluetooth service connected
,09-08 21:13:58.106  3884  3884 D BluetoothPbap: Proxy object connected
09-08 21:13:58.106  3884  3884 D PbapServerProfile: Bluetooth service connected
,09-08 21:13:58.114  3962  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:13:58.127  3962  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:13:58.129  3962  4159 I BtOppRfcommListener: Accept thread started.
,09-08 21:13:58.166   874   874 D BluetoothHeadset: Proxy object connected
09-08 21:13:58.166   874   874 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.167  1998  2302 D BluetoothHeadset: Proxy object connected
09-08 21:13:58.167  1360  1716 D BluetoothHeadset: Proxy object connected
09-08 21:13:58.167   874   874 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.167  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-08 21:13:58.168   874   891 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.168  1998  2119 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.174  1360  1372 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.174  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-08 21:13:58.175   874   891 D BluetoothHeadset: Proxy object connected
,09-08 21:13:58.187  3884  3894 D BluetoothHeadset: Proxy object connected
09-08 21:13:58.188  3884  3884 D HeadsetProfile: Bluetooth service connected
,09-08 21:13:58.370   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 21:13:58.377  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-08 21:13:58.384   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 21:13:58.384   874   894 I Adreno  : Build Date                       : 10/20/15
09-08 21:13:58.384   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 21:13:58.384   874   894 I Adreno  : Local Branch                     : M14
09-08 21:13:58.384   874   894 I Adreno  : Remote Branch                    : 
09-08 21:13:58.384   874   894 I Adreno  : Remote Branch                    : 
09-08 21:13:58.384   874   894 I Adreno  : Reconstruct Branch               : 
,09-08 21:13:58.425   280   299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (163 us)
,09-08 21:13:59.011  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 21:13:59.011  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 21:13:59.049   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 21:13:59.050  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b0586b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@be85363, 16908290=android.view.AbsSavedState$1@be85363}, android:focusedViewId=100}]}]
,09-08 21:13:59.050  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 21:13:59.050  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 21:13:59.050  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-08 21:13:59.056   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-08 21:13:59.060   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-08 21:13:59.069   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a24000
,09-08 21:13:59.071   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-08 21:13:59.311   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 21:13:59.320   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 21:13:59.322   874  1341 D SurfaceControl: Excessive delay in setPowerMode(): 261ms
,09-08 21:13:59.326   874   894 I DreamManagerService: Entering dreamland.
,09-08 21:13:59.327   874   894 I PowerManagerService: Dozing...
,09-08 21:13:59.329   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 21:13:59.410   375  3827 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-08 21:13:59.411   375  3827 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 21:13:59.419   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 21:13:59.426   874  1316 E native  : do suspend false
,09-08 21:13:59.440  1985  4164 D NfcService: Discovery configuration equal, not updating.
,09-08 21:13:59.466   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 21:13:59.470   874  1316 E native  : do suspend true
,09-08 21:13:59.547   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 21:13:59.547   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 21:13:59.560   874  1318 D ConnectivityService: handlePromptUnvalidated 101
,09-08 21:13:59.591  3962  4124 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 21:13:59.591  3962  4124 D BluetoothAdapterProperties: Setting state to 13
09-08 21:13:59.592  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 21:13:59.593  3962  4124 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 21:13:59.595  3962  4124 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:13:59.605  3962  4128 D BluetoothAdapterProperties: Scan Mode:20
09-08 21:13:59.606  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 21:13:59.611  3962  3962 D HeadsetService: Received stop request...Stopping profile...
,09-08 21:13:59.615  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:59.615  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:59.617  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:59.617  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:59.618  3962  3962 D A2dpService: Received stop request...Stopping profile...
09-08 21:13:59.618  3962  4144 D A2dpStateMachine: Exit Disconnected: -1
09-08 21:13:59.619   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:59.619   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:59.620  1998  2119 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:59.620  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:13:59.620  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:13:59.621  1360  1378 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:59.621  1360  1360 D HeadsetProfile: Bluetooth service disconnected
09-08 21:13:59.622  1360  1360 D BluetoothA2dp: Proxy object disconnected
,09-08 21:13:59.622  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 21:13:59.623  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:13:59.623  3884  3894 D BluetoothHeadset: Proxy object disconnected
,09-08 21:13:59.624   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 21:13:59.624  3884  3884 D BluetoothA2dp: Proxy object disconnected
09-08 21:13:59.624  3884  3884 D HeadsetProfile: Bluetooth service disconnected
09-08 21:13:59.624  3962  3962 D HidService: Received stop request...Stopping profile...
,09-08 21:13:59.624   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 21:13:59.624  3962  3962 D HidService: Stopping Bluetooth HidService
,09-08 21:13:59.626  1360  1360 D BluetoothInputDevice: Proxy object disconnected
09-08 21:13:59.626  1360  1360 D HidProfile: Bluetooth service disconnected
,09-08 21:13:59.627  3884  3884 D BluetoothInputDevice: Proxy object disconnected
,09-08 21:13:59.627  3884  3884 D HidProfile: Bluetooth service disconnected
09-08 21:13:59.628  3962  3962 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:59.628  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,09-08 21:13:59.628  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:59.628  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:59.629  3962  3962 D HealthService: Received stop request...Stopping profile...
,09-08 21:13:59.632  3962  3962 D PanService: Received stop request...Stopping profile...
,09-08 21:13:59.633  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 21:13:59.633  1360  1360 D PanProfile: Bluetooth service disconnected
,09-08 21:13:59.634  3884  3884 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 21:13:59.634  3962  3962 D BluetoothMapService: Received stop request...Stopping profile...
09-08 21:13:59.635  3962  3962 D BluetoothMapService: stop()
,09-08 21:13:59.635  3884  3884 D PanProfile: Bluetooth service disconnected
,09-08 21:13:59.635  3962  3962 D BluetoothMapAppObserver: deinitObservers()
,09-08 21:13:59.635  3962  3962 D BluetoothMapAppObserver: removeReceiver()
,09-08 21:13:59.637  1360  1360 D BluetoothMap: Proxy object disconnected
09-08 21:13:59.637  1360  1360 D MapProfile: Bluetooth service disconnected
09-08 21:13:59.638  3884  3884 D BluetoothMap: Proxy object disconnected
09-08 21:13:59.638  3884  3884 D MapProfile: Bluetooth service disconnected
,09-08 21:13:59.639  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 21:13:59.639  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 21:13:59.639  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-08 21:13:59.639  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 21:13:59.639  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:59.640  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:59.640  3962  4128 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-08 21:13:59.640  3962  3962 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:59.640  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,09-08 21:13:59.640  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:59.640  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:59.642  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:59.642  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 21:13:59.642  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:59.642  3962  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 21:13:59.642  3962  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 21:13:59.642  3962  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 21:13:59.642  3962  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 21:13:59.642  3962  3962 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:59.642  3962  3962 V BluetoothAdapterState: isTurningOn()=false,
,09-08 21:13:59.642  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:13:59.643  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:13:59.643  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 21:13:59.643  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 21:13:59.643  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,09-08 21:13:59.644  3962  3962 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:59.643  3962  4128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 21:13:59.644  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:59.644  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:59.644  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 21:13:59.645  3962  4128 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 21:13:59.645  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 21:13:59.645  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,09-08 21:13:59.645  3962  3962 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:59.645  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:59.645  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:59.645  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 21:13:59.645  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 21:13:59.648  3962  3962 D BluetoothMapService: MAP Service closeService in
09-08 21:13:59.648  3962  3962 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 21:13:59.648  3962  3962 D ObexServerSockets0: shutdown(block = true)
,09-08 21:13:59.649  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 21:13:59.649  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:59.649  3962  4150 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 21:13:59.650  3962  4149 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 21:13:59.650  3962  4136 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 21:13:59.651  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 21:13:59.651  3962  3962 V BluetoothAdapterState: isTurningOff()=true
09-08 21:13:59.651  3962  3962 V BluetoothAdapterState: isTurningOn()=false
09-08 21:13:59.651  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:13:59.651  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:13:59.651  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 21:13:59.651  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 21:13:59.651  3962  4124 D BluetoothAdapterProperties: Setting state to 15
09-08 21:13:59.651  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 21:13:59.651  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:59.652  3962  4124 I BluetoothAdapterState: Entering BleOnState
09-08 21:13:59.652  3962  3962 D BluetoothMapService: cleanup()
09-08 21:13:59.652  3962  3962 D BluetoothMapService: MAP Service closeService in
09-08 21:13:59.653  3962  3962 I BtOppRfcommListener: stopping Accept Thread
09-08 21:13:59.653  3962  4159 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 21:13:59.653  3962  4159 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 21:13:59.654  3884  3894 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 21:13:59.655  1360  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 21:13:59.656  3884  3895 D BluetoothPan: onBluetoothStateChange on: false
09-08 21:13:59.656  3884  3894 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 21:13:59.657  3884  3895 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 21:13:59.658  1360  1716 D BluetoothPan: onBluetoothStateChange on: false
09-08 21:13:59.660  1360  1372 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 21:13:59.660   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:59.661  3884  3894 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 21:13:59.662   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 21:13:59.662  1998  2009 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:59.663   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 21:13:59.664  1360  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 21:13:59.664  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 21:13:59.666  1360  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 21:13:59.668  3884  3895 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:59.668  1360  1716 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 21:13:59.668   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 21:13:59.669  3962  4124 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-08 21:13:59.669  3962  4124 D BluetoothAdapterProperties: Setting state to 16
09-08 21:13:59.669  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 21:13:59.670  3962  4124 D BluetoothAdapterProperties: onBleDisable
,09-08 21:13:59.670  3962  4124 I BluetoothAdapterState: Entering PendingCommandState
09-08 21:13:59.670  3962  4125 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 21:13:59.672  3962  4134 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 21:13:59.672  3962  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 21:13:59.673  3962  4128 D BluetoothAdapterProperties: Scan Mode:20
09-08 21:13:59.677  3884  3884 D DockEventReceiver: finishStartingService: stopping service
09-08 21:13:59.679  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:13:59.681  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:59.683  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:59.684  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 21:13:59.685  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:13:59.689  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 21:13:59.695  3884  3884 D DockEventReceiver: finishStartingService: stopping service
,09-08 21:13:59.873  3962  4128 I bt_hci  : shut_down
,09-08 21:13:59.885  3962  4132 I bt_vendor: low_power_mode_cb
,09-08 21:13:59.885  3962  4132 D bt_hwcfg: hw_epilog_process
,09-08 21:13:59.908  3962  4132 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 21:13:59.908  3962  4132 I bt_vendor: epilog_cb
,09-08 21:13:59.908  3962  4132 I bt_hci  : epilog_finished_callback
,09-08 21:13:59.914  3962  4128 I bt_hci_h4: hal_close
,09-08 21:13:59.916  3962  4128 I bt_userial_vendor: device fd = 51 close
,09-08 21:14:00.041  3962  4125 D bt_stack_manager: event_shut_down_stack finished.
09-08 21:14:00.043  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 21:14:00.050  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 21:14:00.051  3962  4124 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 21:14:00.051  3962  3962 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 21:14:00.052  3962  3962 D BtGatt.GattService: stop()
,09-08 21:14:00.052  3962  3962 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 21:14:00.057  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:14:00.058  3962  3962 V BluetoothAdapterState: isTurningOn()=false
09-08 21:14:00.058  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:14:00.058  3962  3962 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 21:14:00.059  3962  4124 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 21:14:00.060  3962  4124 D BluetoothAdapterProperties: Setting state to 10
09-08 21:14:00.060  3962  4124 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 21:14:00.062  3962  4124 I BluetoothAdapterState: Entering OffState
09-08 21:14:00.064   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 21:14:00.088  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 21:14:00.089  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 21:14:00.089  3962  4125 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 21:14:00.092  3962  3962 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 21:14:00.099  3962  4125 D bt_stack_manager: event_clean_up_stack finished.
,09-08 21:14:00.105  3962  3962 I art     : System.exit called, status: 0
,09-08 21:14:00.105  3962  3962 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 21:14:00.148   874  2072 I ActivityManager: Process com.android.bluetooth (pid 3962) has died
,09-08 21:14:02.586  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 21:14:02.587  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:04.330  1868  2655 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 21:14:05.595  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:05.595  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce5db60 added. We now have 6 listener(s)
,09-08 21:14:05.595  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:14:05.599  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:05.600  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f5d819 added. We now have 7 listener(s)
09-08 21:14:05.600  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:14:05.601  3814  3865 I System.out: IsBluetoothEnabled
,09-08 21:14:05.613  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:05.661   874   891 I ActivityManager: Start proc 4177:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 21:14:05.789  4177  4177 D AdapterServiceConfig: Adding HeadsetService
,09-08 21:14:05.790  4177  4177 D AdapterServiceConfig: Adding A2dpService
,09-08 21:14:05.790  4177  4177 D AdapterServiceConfig: Adding HidService
,09-08 21:14:05.790  4177  4177 D AdapterServiceConfig: Adding HealthService
,09-08 21:14:05.791  4177  4177 D AdapterServiceConfig: Adding PanService
,09-08 21:14:05.791  4177  4177 D AdapterServiceConfig: Adding GattService
,09-08 21:14:05.791  4177  4177 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 21:14:05.805   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb35c9:true
,09-08 21:14:05.805  4177  4177 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 21:14:05.810  4177  4177 I bt_bluedroid: init
,09-08 21:14:05.811  4177  4189 I BluetoothAdapterState: Entering OffState
,09-08 21:14:05.816  4177  4190 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 21:14:05.816  4177  4190 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 21:14:05.816  4177  4190 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 21:14:05.817  4177  4190 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 21:14:05.818  4177  4177 I bt_bluedroid: get_profile_interface socket
,09-08 21:14:05.820  4177  4177 I bt_bluedroid: get_profile_interface sdp
,09-08 21:14:05.824  4177  4188 I bt_bluedroid: config_hci_snoop_log
,09-08 21:14:05.825  4177  4193 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 21:14:05.827   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-08 21:14:05.828  4177  4193 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 21:14:05.838  4177  4189 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 21:14:05.838  4177  4189 D BluetoothAdapterProperties: Setting state to 14
,09-08 21:14:05.839  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 21:14:05.842  4177  4189 D BluetoothBondStateMachine: make
,09-08 21:14:05.847  4177  4194 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 21:14:05.857  4177  4189 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:14:05.859  4177  4177 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 21:14:05.871  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:05.873  4177  4177 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 21:14:05.876  4177  4177 D BtGatt.GattService: Received start request. Starting profile...
,09-08 21:14:05.876  4177  4177 D BtGatt.GattService: start()
,09-08 21:14:05.876  4177  4177 I bt_bluedroid: get_profile_interface gatt
,09-08 21:14:05.877  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:05.877  4177  4177 D BtGatt.AdvertiseManager: advertise manager created
,09-08 21:14:05.887  4177  4177 V BluetoothAdapterState: isTurningOff()=false
09-08 21:14:05.887  4177  4177 V BluetoothAdapterState: isTurningOn()=false
09-08 21:14:05.887  4177  4177 V BluetoothAdapterState: isBleTurningOn()=true
09-08 21:14:05.887  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:14:05.888  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 21:14:05.888  4177  4189 I bt_bluedroid: enable
,09-08 21:14:05.889  4177  4190 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 21:14:05.889  4177  4190 I bt_hci  : start_up
,09-08 21:14:05.897  4177  4190 I bt_vendor: alloc value 0xb3a3a189
09-08 21:14:05.897  4177  4190 I bt_vendor: init
09-08 21:14:05.897  4177  4190 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 21:14:05.898  4177  4190 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 21:14:06.005  4177  4190 D bt_hci  : start_up starting async portion
,09-08 21:14:06.006  4177  4197 I bt_hci  : event_finish_startup
,09-08 21:14:06.006  4177  4197 I bt_hci_h4: hal_open
,09-08 21:14:06.006  4177  4197 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 21:14:06.016  4177  4197 I bt_userial_vendor: device fd = 51 open
,09-08 21:14:06.048  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 21:14:06.080  4177  4197 D bt_hwcfg: Chipset BCM4354A2
,09-08 21:14:06.080  4177  4197 D bt_hwcfg: Target name = [BCM4354A2]
09-08 21:14:06.081  4177  4197 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 21:14:06.739  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 21:14:06.740  4177  4197 D bt_hwcfg: Settlement delay -- 100 ms
09-08 21:14:06.741  4177  4197 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 21:14:06.857  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 21:14:06.858  4177  4197 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 21:14:06.888  4177  4197 I bt_hwcfg: vendor lib fwcfg completed
,09-08 21:14:06.889  4177  4197 I bt_vendor: firmware callback
09-08 21:14:06.889  4177  4197 I bt_hci  : firmware_config_callback
,09-08 21:14:06.901  4177  4199 I bt_btu  : btu_task pending for preload complete event
,09-08 21:14:06.901  4177  4199 I bt_btu_task: Bluetooth chip preload is complete
09-08 21:14:06.902  4177  4199 I bt_btu  : btu_task received preload complete event
,09-08 21:14:06.912  4177  4199 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 21:14:06.912  4177  4199 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 21:14:06.912  4177  4199 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 21:14:06.912  4177  4199 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 21:14:06.913  4177  4199 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 21:14:06.913  4177  4199 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 21:14:06.913  4177  4199 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 21:14:06.914  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 21:14:06.914  4177  4199 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 21:14:06.914  4177  4199 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 21:14:06.914  4177  4199 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 21:14:06.915  4177  4199 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 21:14:06.915  4177  4199 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 21:14:06.915  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 21:14:06.915  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 21:14:07.047  4177  4199 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b7d9d
09-08 21:14:07.047  4177  4199 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b7d9d 
,09-08 21:14:07.052  4177  4193 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 21:14:07.055  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 21:14:07.055  4177  4193 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 21:14:07.057  4177  4193 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 21:14:07.058  4177  4193 D BluetoothAdapterProperties: Scan Mode:20
,09-08 21:14:07.059  4177  4193 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 21:14:07.059  4177  4193 D bt_hci  : do_postload posting postload work item
,09-08 21:14:07.059  4177  4197 I bt_hci  : event_postload
,09-08 21:14:07.060  4177  4197 I bt_vendor: sco_config_cb
,09-08 21:14:07.060  4177  4197 I bt_hci  : sco_config_callback postload finished.
,09-08 21:14:07.060  4177  4193 D bt_bte_conf: Device ID record 1 : primary
,09-08 21:14:07.060  4177  4193 D bt_bte_conf:   vendorId            = 000f
,09-08 21:14:07.061  4177  4193 D bt_bte_conf:   vendorIdSource      = 0001
09-08 21:14:07.061  4177  4193 D bt_bte_conf:   product             = 1200,
,09-08 21:14:07.061  4177  4193 D bt_bte_conf:   version             = 1436
,09-08 21:14:07.061  4177  4193 D bt_bte_conf:   clientExecutableURL = 
09-08 21:14:07.061  4177  4193 D bt_bte_conf:   serviceDescription  = 
,09-08 21:14:07.061  4177  4193 D bt_bte_conf:   documentationURL    = 
09-08 21:14:07.061  4177  4193 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 21:14:07.061  4177  4190 D bt_stack_manager: event_start_up_stack finished
,09-08 21:14:07.062  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-08 21:14:07.062  4177  4189 D BluetoothAdapterProperties: Setting state to 15
09-08 21:14:07.062  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 21:14:07.063  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:07.063  4177  4189 I BluetoothAdapterState: Entering BleOnState
,09-08 21:14:07.068  4177  4189 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 21:14:07.068  4177  4189 D BluetoothAdapterProperties: Setting state to 11
,09-08 21:14:07.069  4177  4197 I bt_vendor: low_power_mode_cb
,09-08 21:14:07.069  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 21:14:07.089  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:07.089  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:07.091  4177  4177 D HeadsetService: Received start request. Starting profile...
09-08 21:14:07.093  4177  4177 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 21:14:07.094  4177  4177 D HeadsetStateMachine: make
,09-08 21:14:07.099  4177  4189 I BluetoothAdapterState: Entering PendingCommandState
,09-08 21:14:07.101  4177  4177 D HeadsetStateMachine: max_hf_connections = 1
09-08 21:14:07.101  4177  4177 I bt_bluedroid: get_profile_interface handsfree
,09-08 21:14:07.102  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 21:14:07.102  4177  4193 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-08 21:14:07.106  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:07.107  4177  4177 D A2dpService: Received start request. Starting profile...
09-08 21:14:07.107  4177  4177 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 21:14:07.108  4177  4177 I bt_bluedroid: get_profile_interface avrcp
,09-08 21:14:07.113  4177  4177 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 21:14:07.114  4177  4177 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 21:14:07.114  4177  4177 D A2dpStateMachine: make
,09-08 21:14:07.115  4177  4177 I bt_bluedroid: get_profile_interface a2dp
,09-08 21:14:07.115  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-08 21:14:07.117  4177  4208 D A2dpStateMachine: Enter Disconnected: -2
09-08 21:14:07.117  4177  4177 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 21:14:07.118  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
09-08 21:14:07.118  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 21:14:07.120  4177  4177 D HidService: Received start request. Starting profile...
09-08 21:14:07.120  4177  4177 I bt_bluedroid: get_profile_interface hidhost
09-08 21:14:07.121  4177  4193 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39993e5
09-08 21:14:07.121  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-08 21:14:07.121  4177  4177 D HidService: setHidService(): set to: null
,09-08 21:14:07.121  4177  4177 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 21:14:07.122  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f,
09-08 21:14:07.122  4177  4177 D HealthService: Received start request. Starting profile...
,09-08 21:14:07.124  4177  4177 I bt_bluedroid: get_profile_interface health
,09-08 21:14:07.124  4177  4177 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 21:14:07.125  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:07.125  4177  4177 D PanService: Received start request. Starting profile...
09-08 21:14:07.125  4177  4177 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 21:14:07.125  4177  4177 I bt_bluedroid: get_profile_interface pan
,09-08 21:14:07.126  4177  4193 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 21:14:07.128  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
09-08 21:14:07.128  4177  4177 D BluetoothMapService: Received start request. Starting profile...
,09-08 21:14:07.128  4177  4177 D BluetoothMapService: start()
,09-08 21:14:07.131  4177  4177 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 21:14:07.131  4177  4177 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 21:14:07.131  4177  4177 D BluetoothMapAppObserver: createReceiver()
,09-08 21:14:07.132  4177  4177 D BluetoothMapAppObserver: initObservers()
,09-08 21:14:07.132  4177  4177 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 21:14:07.140  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:14:07.141  4177  4177 V BluetoothAdapterState: isTurningOn()=true
09-08 21:14:07.141  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:14:07.141  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:14:07.142  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,09-08 21:14:07.142  4177  4177 V BluetoothAdapterState: isTurningOn()=true
09-08 21:14:07.142  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:14:07.143  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 21:14:07.143  4177  4206 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isTurningOff()=false
09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isTurningOn()=true
,09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isTurningOff()=false
09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isTurningOn()=true
09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 21:14:07.145  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isTurningOff()=false
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isTurningOn()=true
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false,
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isTurningOff()=false
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isTurningOn()=true
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
09-08 21:14:07.146  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false,
09-08 21:14:07.147  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 21:14:07.147  4177  4189 D BluetoothAdapterProperties: ScanMode =  20
,09-08 21:14:07.147  4177  4189 D BluetoothAdapterProperties: State =  11
,09-08 21:14:07.147  4177  4189 D BluetoothAdapterProperties: Setting state to 12
,09-08 21:14:07.147  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 21:14:07.148  4177  4189 I BluetoothAdapterState: Entering OnState
09-08 21:14:07.148  3884  3894 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 21:14:07.152  4177  4193 D BluetoothAdapterProperties: Scan Mode:21
09-08 21:14:07.152  4177  4193 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 21:14:07.155  1360  1716 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:14:07.156  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:14:07.157  3884  3894 D BluetoothPan: onBluetoothStateChange on: true
,09-08 21:14:07.158  4177  4177 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 21:14:07.158  3884  3895 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 21:14:07.158  4177  4177 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 21:14:07.159  3884  3894 D BluetoothMap: onBluetoothStateChange: up=true
09-08 21:14:07.160  4177  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:14:07.161  3884  3884 D BluetoothInputDevice: Proxy object connected
09-08 21:14:07.161  3884  3884 D HidProfile: Bluetooth service connected
09-08 21:14:07.161  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 21:14:07.161  1360  1378 D BluetoothPan: onBluetoothStateChange on: true
,09-08 21:14:07.162  1360  1372 D BluetoothMap: onBluetoothStateChange: up=true
09-08 21:14:07.163  4177  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 21:14:07.164   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:14:07.164  3884  3895 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 21:14:07.165  4177  4177 D ObexServerSockets: Succeed to create listening sockets 
09-08 21:14:07.165  4177  4177 D ObexServerSockets0: startAccept()
09-08 21:14:07.165   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:14:07.165  4177  4177 D ObexServerSockets0: prepareForNewConnect()
09-08 21:14:07.166  1998  2009 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:14:07.166   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 21:14:07.167  1360  1716 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 21:14:07.168  1360  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 21:14:07.169  1360  1360 D BluetoothInputDevice: Proxy object connected
,09-08 21:14:07.169  1360  1360 D HidProfile: Bluetooth service connected
09-08 21:14:07.170  3884  3894 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 21:14:07.170  1360  1716 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 21:14:07.171   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 21:14:07.171  4177  4177 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 21:14:07.171  4177  4177 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 21:14:07.172   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 21:14:07.172  4177  4214 D ObexServerSockets0: Accepting socket connection...
09-08 21:14:07.175  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:07.177  4177  4213 D ObexServerSockets0: Accepting socket connection...
,09-08 21:14:07.178   874   874 D BluetoothA2dp: Proxy object connected
,09-08 21:14:07.178  1360  1360 D BluetoothA2dp: Proxy object connected
,09-08 21:14:07.181  4177  4177 D BluetoothMapService: onReceive
,09-08 21:14:07.181  4177  4177 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 21:14:07.181  4177  4177 D BluetoothMapService: STATE_ON
,09-08 21:14:07.182  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 21:14:07.182  1360  1360 D PanProfile: Bluetooth service connected
,09-08 21:14:07.182  1360  1360 D BluetoothMap: Proxy object connected
09-08 21:14:07.182  3884  3884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 21:14:07.182  1360  1360 D MapProfile: Bluetooth service connected
09-08 21:14:07.183  1360  1360 D BluetoothMap: getConnectedDevices()
,09-08 21:14:07.187  3884  3884 D BluetoothA2dp: Proxy object connected
,09-08 21:14:07.190  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 21:14:07.191  3884  3884 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 21:14:07.191  3884  3884 D PanProfile: Bluetooth service connected
09-08 21:14:07.191  3884  3884 D BluetoothMap: Proxy object connected
,09-08 21:14:07.191  3884  3884 D MapProfile: Bluetooth service connected
,09-08 21:14:07.191  3884  3884 D BluetoothMap: getConnectedDevices()
,09-08 21:14:07.198  3884  3884 D DockEventReceiver: finishStartingService: stopping service
,09-08 21:14:07.199  3884  3884 D BluetoothPbap: Proxy object connected
,09-08 21:14:07.199  3884  3884 D PbapServerProfile: Bluetooth service connected
,09-08 21:14:07.211  1360  1360 D BluetoothPbap: Proxy object connected
,09-08 21:14:07.211  1360  1360 D PbapServerProfile: Bluetooth service connected
,09-08 21:14:07.213  4177  4219 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:14:07.217  4177  4177 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 21:14:07.217  4177  4177 D ObexServerSockets0: prepareForNewConnect()
,09-08 21:14:07.222  4177  4223 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 21:14:07.223  4177  4223 I BtOppRfcommListener: Accept thread started.
,09-08 21:14:07.266   874   874 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.267   874   874 D BluetoothHeadset: Proxy object connected
09-08 21:14:07.267  1998  3548 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.267  1360  1372 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.268  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-08 21:14:07.269  3884  3895 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.269  3884  3884 D HeadsetProfile: Bluetooth service connected
,09-08 21:14:07.269   874   874 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.270  3884  3894 D BluetoothHeadset: Proxy object connected
09-08 21:14:07.271  1360  1716 D BluetoothHeadset: Proxy object connected
09-08 21:14:07.271   874   891 D BluetoothHeadset: Proxy object connected
,09-08 21:14:07.274  3884  3884 D HeadsetProfile: Bluetooth service connected
09-08 21:14:07.277  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:14:07.636  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:14:07.644  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:14:07.648  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:07.649  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dad0de added. We now have 8 listener(s)
,09-08 21:14:07.649  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:14:07.655   874  1392 D WifiService: setWifiEnabled: false pid=3814, uid=10000
09-08 21:14:07.656   874  1392 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 21:14:07.668  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:07.669   874  2012 D WifiService: setWifiEnabled: true pid=3814, uid=10000
,09-08 21:14:07.670   874  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 21:14:07.684   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:14:07.702  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:14:07.705  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:14:07.721   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-08 21:14:07.722   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 21:14:07.723   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 21:14:07.724   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 21:14:07.724   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 21:14:07.724   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 21:14:07.724   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 21:14:07.740   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 21:14:07.741   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.26 delta 1000 -> 1000
,09-08 21:14:07.742   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 21:14:07.743   371   872 D CommandListener: Setting iface cfg
09-08 21:14:07.744   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 21:14:07.744   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 21:14:07.802   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 21:14:07.803   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-08 21:14:07.803   874  1316 E native  : do suspend true
,09-08 21:14:07.863   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 21:14:07.864   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 21:14:07.883   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 21:14:07.963   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 21:14:07.965  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 21:14:08.398  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 21:14:08.443  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 21:14:08.445  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 21:14:08.458   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 21:14:08.476   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 21:14:08.476   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 21:14:08.477   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 21:14:08.502   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 21:14:08.523   371   872 D CommandListener: Setting iface cfg
,09-08 21:14:08.524   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 21:14:08.538   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 21:14:08.561   874  4231 D DhcpClient: Receive thread started
,09-08 21:14:08.648   874  1316 E native  : do suspend false
,09-08 21:14:08.668   874  2144 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 21:14:08.681   874  4231 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-08 21:14:08.683   874  2144 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-08 21:14:08.688   874  2144 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:14:08.699  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 21:14:08.706   874  4231 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 21:14:08.706  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 21:14:08.707   874  2144 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 21:14:08.713   371   872 D CommandListener: Setting iface cfg
,09-08 21:14:08.721  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-08 21:14:08.724  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 21:14:08.726   874  2144 D DhcpClient: Scheduling renewal in 86399s
,09-08 21:14:08.728   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 21:14:08.729  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b0586b Bundle[{}]
09-08 21:14:08.729   874  1316 E native  : do suspend true
09-08 21:14:08.730  3814  3865 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 21:14:08.730  3814  3865 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 21:14:08.730  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 21:14:08.731  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 21:14:08.732  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 21:14:08.732  3814  3865 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 21:14:08.736  3814  3865 I System.out: Running OutgoingSocketThread
,09-08 21:14:08.739  3814  4232 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,09-08 21:14:08.741  3814  4232 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39278
,09-08 21:14:08.741  3814  4232 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 21:14:08.743   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 21:14:08.745   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 21:14:08.745   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 21:14:08.746   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 21:14:08.751   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 21:14:08.784   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 21:14:08.785   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 21:14:08.786   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 21:14:08.788   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 21:14:08.789   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 21:14:08.802   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 21:14:08.808   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 21:14:08.808   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 21:14:08.808   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 21:14:08.808   874  1318 D ConnectivityService:    accepting network in place of null
,09-08 21:14:08.808   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 21:14:08.809   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 21:14:08.810   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 21:14:08.827   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=163320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 21:14:08.855   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:14:08.902   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 21:14:08.908   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 21:14:08.908   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 21:14:08.911   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 21:14:08.917   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 21:14:08.922   874  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:08.937  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:14:08.939  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:14:08.954  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 21:14:08.958  1723  1723 D SystemUpdateService: onCreate
,09-08 21:14:08.958  3766  4241 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 21:14:08.962  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 21:14:08.974  1723  4242 I SystemUpdateService: active receiver: enabled
,09-08 21:14:08.984  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 21:14:08.991  1723  4242 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 21:14:08.993  1723  2528 I iu.UploadsManager: num queued entries: 0
,09-08 21:14:08.994  1723  2528 I iu.UploadsManager: num updated entries: 0
,09-08 21:14:08.994  1723  2528 I iu.SyncManager: NEXT; no task
09-08 21:14:08.995  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 21:14:08.997  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 21:14:08.998  3976  3976 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 21:14:09.002  1723  4245 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 21:14:09.003  1723  4245 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 21:14:09.004  3976  3976 D SprintDMHelper: simOperator: 
09-08 21:14:09.004  3976  3976 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 21:14:09.005   874  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 19:14:08 GMT], X-Android-Received-Millis=[1473362049004], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473362048966]}
,09-08 21:14:09.007   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 21:14:09.008   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-08 21:14:09.008   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 21:14:09.010   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 21:14:09.017  1723  4245 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 21:14:09.023  1723  4242 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 21:14:09.023  1723  4242 I SystemUpdateService: now status is 0 (complete)
,09-08 21:14:09.024  1723  4242 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 21:14:09.030  1723  4242 I SystemUpdateService: file has been verified
09-08 21:14:09.030  1723  4242 I SystemUpdateService: OTA package size = 12249756
,09-08 21:14:09.034  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:09.039  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:09.050  1723  4242 I SystemUpdateService: showing system update notification
,09-08 21:14:09.065  3766  4251 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 21:14:09.075  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 21:14:09.075  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 21:14:09.075  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:09.075  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:09.088  1723  1723 D SystemUpdateService: onDestroy
,09-08 21:14:09.096  1723  4245 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-08 21:14:09.100  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:14:09.100  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:14:09.100  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:09.100  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:09.137  3116  4248 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 21:14:09.152  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:14:09.152  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:14:09.152  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:14:09.152  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:09.169  3766  4251 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 21:14:09.170  3766  4241 E BooksSync: Soft error
09-08 21:14:09.170  3766  4241 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:14:09.170  3766  4241 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 21:14:09.170  3766  4241 E BooksSync: Sync error
09-08 21:14:09.170  3766  4241 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:14:09.170  3766  4241 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 21:14:09.171  3766  4241 I BooksSync: Finished books sync
,09-08 21:14:09.181   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162986, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:14:09.740  3814  3865 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
09-08 21:14:09.740  3814  3865 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,09-08 21:14:09.750  3814  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-08 21:14:09.752  3814  3865 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 21:14:09.753  3814  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-08 21:14:09.759  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 21:14:09.759  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82c2bf added. We now have 2 listener(s)
,09-08 21:14:09.761  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:14:09.761  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 21:14:09.761  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.761  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.761  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd4d8c added. We now have 9 listener(s)
,09-08 21:14:09.761  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.762  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 21:14:09.769  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:09.784  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:14:09.789  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:14:09.790  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:14:09.791  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 21:14:09.791  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf1cea added. We now have 3 listener(s)
,09-08 21:14:09.797  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:09.797  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:14:09.797  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 21:14:09.797  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.798  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:09.798  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2acbdb added. We now have 10 listener(s)
09-08 21:14:09.799  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.799  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 21:14:09.799  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:09.799  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:14:09.800  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.800  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.800  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 21:14:09.801  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 21:14:09.801  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82c2bf removed from the list
09-08 21:14:09.801  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.801  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd4d8c removed from the list
,09-08 21:14:09.804  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:09.805  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:14:09.805  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.806  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:14:09.806  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.809  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.810  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.810  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:14:09.810  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd4d8c not in the list
09-08 21:14:09.811  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.811  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.812  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.812  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:14:09.812  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.812  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2acbdb removed from the list
09-08 21:14:09.812  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 21:14:09.812  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:14:09.812  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:09.812  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:09.812  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf1cea removed from the list
,09-08 21:14:09.813  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.813  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7b678 added. We now have 2 listener(s)
09-08 21:14:09.815  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:14:09.815  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.815  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.815  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:09.815  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa17151 added. We now have 9 listener(s)
09-08 21:14:09.815  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.818  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 21:14:09.822  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:09.826  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:14:09.828  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:14:09.828  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:14:09.829  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.829  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5804ab7 added. We now have 3 listener(s)
,09-08 21:14:09.831  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:14:09.831  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:09.831  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.831  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 21:14:09.831  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.831  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eedc224 added. We now have 10 listener(s)
,09-08 21:14:09.831  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:14:09.831  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 21:14:09.831  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 21:14:09.831  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 21:14:09.831  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:14:09.831  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.833  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:09.836  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.836  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 21:14:09.841  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 21:14:09.842  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.842  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 21:14:09.844  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 21:14:09.844  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 21:14:09.845  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 21:14:09.845  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:14:09.847  4177  4188 D BtGatt.GattService: registerClient() - UUID=ba46e2fe-d26b-4c8d-a704-c6123f931912
,09-08 21:14:09.848  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=ba46e2fe-d26b-4c8d-a704-c6123f931912, clientIf=5
09-08 21:14:09.848  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 21:14:09.849  4177  4187 D BtGatt.GattService: start scan with filters
,09-08 21:14:09.851  4177  4196 D BtGatt.ScanManager: handling starting scan
,09-08 21:14:09.852  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 21:14:09.852  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 21:14:09.852  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:14:09.852  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 21:14:09.853  4177  4196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95a64f
,09-08 21:14:09.854  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:14:09.854  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:14:09.854  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 21:14:09.855  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 21:14:09.855  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.856  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 21:14:09.856  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 21:14:09.859  3814  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 21:14:09.859  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:09.859  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 21:14:09.859  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.859  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:14:09.859  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 21:14:09.859  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:14:09.859  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 21:14:09.859  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:14:09.859  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 21:14:09.859  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 21:14:09.860  3814  3865 D BluetoothAdapter: STATE_ON,
09-08 21:14:09.860  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:14:09.860  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.860  4177  4187 D BtGatt.GattService: stopScan() - queue size =1
,09-08 21:14:09.861  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:14:09.861  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 21:14:09.861  4177  4205 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 21:14:09.861  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:14:09.861  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:14:09.861  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 21:14:09.861  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 21:14:09.862  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 21:14:09.863  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 21:14:09.863  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.863  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:14:09.863  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 21:14:09.863  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.864  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.864  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:14:09.864  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:14:09.867  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.867  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:14:09.867  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:14:09.867  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:14:09.868  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:14:09.868  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:09.868  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:14:09.869  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.869  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.869  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-08 21:14:09.871  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:09.871  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7b678 removed from the list
,09-08 21:14:09.871  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.871  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:14:09.871  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa17151 removed from the list
,09-08 21:14:09.871  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:14:09.871  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.871  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 21:14:09.871  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.871  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.871  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:14:09.871  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:14:09.871  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 21:14:09.872  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.872  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 21:14:09.872  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.872  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.872  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.872  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.872  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:14:09.872  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa17151 not in the list
09-08 21:14:09.874  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.874  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.874  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.876  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 21:14:09.876  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:14:09.876  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.876  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.876  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
09-08 21:14:09.876  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:09.878  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:14:09.879  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.879  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:09.879  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 21:14:09.880  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.880  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:14:09.880  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 21:14:09.880  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.880  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.880  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 21:14:09.880  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eedc224 removed from the list
,09-08 21:14:09.880  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.880  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.880  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:09.880  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 21:14:09.880  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5804ab7 removed from the list
,09-08 21:14:09.881  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 21:14:09.881  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.881  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.881  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af531bc added. We now have 2 listener(s)
,09-08 21:14:09.881  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 21:14:09.883  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:14:09.883  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.883  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.883  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 21:14:09.883  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f5a545 added. We now have 9 listener(s)
09-08 21:14:09.883  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.883  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:14:09.885  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.885  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 21:14:09.886  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:09.889  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 21:14:09.890  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 21:14:09.890  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:14:09.891  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.891  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb261cb added. We now have 3 listener(s)
,09-08 21:14:09.892  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:14:09.892  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 21:14:09.892  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.892  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.893  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.893  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c1ada8 added. We now have 10 listener(s)
09-08 21:14:09.893  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.893  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:14:09.893  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:09.894  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:14:09.894  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 21:14:09.894  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 21:14:09.894  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.894  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 21:14:09.896  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.896  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 21:14:09.898  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 21:14:09.899  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.899  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 21:14:09.901  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 21:14:09.901  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 21:14:09.901  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 21:14:09.902  3814  3865 D BluetoothAdapter: STATE_ON
,09-08 21:14:09.903  4177  4188 D BtGatt.GattService: registerClient() - UUID=2c3f46ef-531a-438a-bfff-beb1411edff8
,09-08 21:14:09.904  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=2c3f46ef-531a-438a-bfff-beb1411edff8, clientIf=5
09-08 21:14:09.904  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 21:14:09.904  4177  4215 D BtGatt.GattService: start scan with filters
,09-08 21:14:09.906  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 21:14:09.906  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 21:14:09.906  4177  4196 D BtGatt.ScanManager: handling starting scan
09-08 21:14:09.906  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:14:09.906  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 21:14:09.908  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 21:14:09.908  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:14:09.909   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-08 21:14:09.909  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 21:14:09.910  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 21:14:09.910  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 21:14:09.910  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.910  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 21:14:09.912  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:14:09.912  3814  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 21:14:09.913  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:14:09.913  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:09.913  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 21:14:09.913  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.913  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.913  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:14:09.913  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 21:14:09.913  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af531bc removed from the list
09-08 21:14:09.913  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.913  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f5a545 removed from the list
09-08 21:14:09.913  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:14:09.913  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 21:14:09.914  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-08 21:14:09.914  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 21:14:09.914  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.914  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.914  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:14:09.914  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:14:09.914  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:14:09.915  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 21:14:09.915  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:14:09.915  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.915  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.916  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f5a545 not in the list
09-08 21:14:09.916  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:14:09.916  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 21:14:09.916  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:14:09.916  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 21:14:09.916  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 21:14:09.917  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.917  4177  4205 D BtGatt.GattService: stopScan() - queue size =1
,09-08 21:14:09.918  4177  4187 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 21:14:09.919  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:14:09.919  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:14:09.919  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 21:14:09.919  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 21:14:09.919  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 21:14:09.920  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:14:09.920  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.920  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:14:09.920  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 21:14:09.920  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:09.921  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.921  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.921  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.922  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:14:09.922  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.924  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.924  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:14:09.926  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 21:14:09.926  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.927  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:14:09.928  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.928  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:14:09.928  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.929  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.930  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.930  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.930  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.932  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.932  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:14:09.932  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.932  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.932  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
09-08 21:14:09.932  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.934  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:14:09.934  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.934  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.934  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:14:09.934  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:14:09.934  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.934  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.935  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.935  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Liste,ner org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c1ada8 removed from the list
09-08 21:14:09.935  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.935  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.935  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.935  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:09.935  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb261cb removed from the list
09-08 21:14:09.935  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.935  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46289c0 added. We now have 2 listener(s)
09-08 21:14:09.936  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:14:09.936  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.937  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.937  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.937  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d56f9 added. We now have 9 listener(s)
09-08 21:14:09.937  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.937  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:14:09.938  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.939  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 21:14:09.939  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.939  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:09.942  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:14:09.944  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 21:14:09.944  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.944  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:09.944  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:14:09.945  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.945  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@988c9f added. We now have 3 listener(s)
09-08 21:14:09.946  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:09.947  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:09.949  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:14:09.949  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.949  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.950  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.950  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc681ec added. We now have 10 listener(s)
09-08 21:14:09.950  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.951  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 21:14:09.951  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 21:14:09.951  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 21:14:09.951  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.951  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.953  3814  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.953  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:14:09.956  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 21:14:09.956  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.956  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:14:09.959  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 21:14:09.959  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 21:14:09.959  3814  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 21:14:09.960  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.961  4177  4188 D BtGatt.GattService: registerClient() - UUID=74cd5ac6-69b3-4b66-bdb3-791e55c3918f
09-08 21:14:09.962  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=74cd5ac6-69b3-4b66-bdb3-791e55c3918f, clientIf=5
09-08 21:14:09.962  3814  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 21:14:09.962  4177  4205 D BtGatt.GattService: start scan with filters
09-08 21:14:09.965  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 21:14:09.965  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 21:14:09.965  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 21:14:09.965  4177  4196 D BtGatt.ScanManager: handling starting scan
09-08 21:14:09.965  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 21:14:09.966  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:14:09.967  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 21:14:09.967  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 21:14:09.968  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 21:14:09.971  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:14:09.971  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:09.971  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:14:09.971  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.971  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.971  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 21:14:09.971  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:09.971  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46289c0 removed from the list
09-08 21:14:09.971  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.971  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d56f9 removed from the list
09-08 21:14:09.971  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:14:09.971  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.972  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.972  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 21:14:09.972  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.972  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:09.972  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.973  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.973  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.973  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d56f9 not in the list
09-08 21:14:09.973  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 21:14:09.973  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 21:14:09.973  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 21:14:09.973  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 21:14:09.973  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 21:14:09.973  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.974  4177  4215 D BtGatt.GattService: stopScan() - queue size =1
09-08 21:14:09.974  4177  4187 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 21:14:09.974  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:14:09.974  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 21:14:09.974  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 21:14:09.974  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 21:14:09.975  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 21:14:09.976  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:14:09.976  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.976  3814  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 21:14:09.976  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.977  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.977  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.977  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.978  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.978  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 21:14:09.978  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.978  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 21:14:09.981  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.981  3814  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 21:14:09.984  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 21:14:09.984  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 21:14:09.984  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 21:14:09.984  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.985  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.986  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 21:14:09.986  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:09.986  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 21:14:09.989  3814  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 21:14:09.989  3814  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 21:14:09.989  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 21:14:09.989  3814  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.989  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:09.989  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
09-08 21:14:09.989  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 21:14:09.991  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 21:14:09.991  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:09.992  3814  3865 D BluetoothAdapter: STATE_ON
09-08 21:14:09.992  3814  3865 D BluetoothLeScanner: could not find callback wrapper
09-08 21:14:09.992  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 21:14:09.992  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:09.992  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 21:14:09.992  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:09.992  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc681ec removed from the list
09-08 21:14:09.992  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:09.993  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:09.993  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:09.993  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:09.993  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@988c9f removed from the list
09-08 21:14:09.994  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:09.994  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d2284 added. We now have 2 listener(s)
09-08 21:14:09.995  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:14:09.996  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:09.996  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:09.996  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:09.996  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8841a6d added. We now have 9 listener(s)
09-08 21:14:09.996  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:09.996  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:14:10.000  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:14:10.004  3814  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:14:10.006  3814  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 21:14:10.007  3814  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:14:10.007  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 21:14:10.007  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea7f33 added. We now have 3 listener(s)
09-08 21:14:10.009  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 21:14:10.009  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:14:10.010  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:14:10.010  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 21:14:10.010  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70be2f0 added. We now have 10 listener(s)
09-08 21:14:10.010  3814  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:14:10.010  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 21:14:10.010  3814  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 21:14:10.010  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:10.010  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:10.010  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 21:14:10.011  3814  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 21:14:10.011  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:10.011  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:10.011  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 21:14:10.011  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:10.011  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d2284 removed from the list
09-08 21:14:10.011  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:10.011  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8841a6d removed from the list
09-08 21:14:10.012  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:14:10.012  3814  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:14:10.012  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:10.014  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:10.014  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:10.017  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 21:14:10.017  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:10.018  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:10.018  3814  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8841a6d not in the list
09-08 21:14:10.018  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:10.018  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:14:10.019  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 21:14:10.019  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:10.023  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 21:14:10.023  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 21:14:10.024  3814  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:14:10.024  3814  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70be2f0 removed from the list
09-08 21:14:10.024  3814  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:14:10.024  3814  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:14:10.024  3814  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 21:14:10.025  3814  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:14:10.025  3814  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea7f33 removed from the list
,09-08 21:14:10.028  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 21:14:10.028  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 21:14:10.028  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:10.028  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
09-08 21:14:10.028  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 21:14:10.028  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 21:14:10.028  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 21:14:10.029  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 21:14:10.029  3814  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 21:14:10.033  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 21:14:10.034  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 21:14:10.034  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 21:14:10.035  3814  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,09-08 21:14:10.036  3814  4256 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
,09-08 21:14:10.036  3814  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 21:14:10.039  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 21:14:10.039  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 21:14:10.040  3814  4257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,09-08 21:14:10.040  3814  4257 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-08 21:14:10.040  3814  4257 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 21:14:10.042  3814  3865 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-08 21:14:10.042  3814  3865 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-08 21:14:10.042  3814  3865 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-08 21:14:10.042  3814  3865 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-08 21:14:10.042  3814  3865 D com.test.thalitest.ThaliTestRunner: Total duration: 22943 ms
,09-08 21:14:10.044  3814  3865 I jxcore-log: Total number of executed tests:  80
09-08 21:14:10.044  3814  3865 I jxcore-log: 
09-08 21:14:10.044  3814  3865 I jxcore-log: Number of passed tests:  80
09-08 21:14:10.044  3814  3865 I jxcore-log: 
,09-08 21:14:10.044  3814  3865 I jxcore-log: Number of failed tests:  0
09-08 21:14:10.044  3814  3865 I jxcore-log: 
,09-08 21:14:10.045  3814  3865 I jxcore-log: Number of ignored tests:  0
09-08 21:14:10.045  3814  3865 I jxcore-log: 
09-08 21:14:10.045  3814  3865 I jxcore-log: Total duration:  22943
09-08 21:14:10.045  3814  3865 I jxcore-log: 
,09-08 21:14:10.047  3814  3865 I jxcore-log: Unit Test app is loaded
09-08 21:14:10.047  3814  3865 I jxcore-log: 
,09-08 21:14:10.054  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.054  3814  3865 I jxcore-log: 
,09-08 21:14:10.055  3814  3814 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,09-08 21:14:10.058  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.058  3814  3865 I jxcore-log: 
,09-08 21:14:10.059  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.059  3814  3865 I jxcore-log: 
,09-08 21:14:10.060  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.060  3814  3865 I jxcore-log: 
,09-08 21:14:10.060  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.060  3814  3865 I jxcore-log: 
,09-08 21:14:10.062  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.062  3814  3865 I jxcore-log: 
,09-08 21:14:10.064  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.064  3814  3865 I jxcore-log: 
,09-08 21:14:10.065  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.065  3814  3865 I jxcore-log: 
,09-08 21:14:10.066  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.066  3814  3865 I jxcore-log: 
,09-08 21:14:10.067  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 21:14:10.067  3814  3865 I jxcore-log: 
,09-08 21:14:10.068  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 21:14:10.068  3814  3865 I jxcore-log: 
,09-08 21:14:10.069  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 21:14:10.069  3814  3865 I jxcore-log: 
,09-08 21:14:10.069  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.069  3814  3865 I jxcore-log: 
,09-08 21:14:10.070  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.070  3814  3865 I jxcore-log: 
,09-08 21:14:10.071  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.071  3814  3865 I jxcore-log: 
,09-08 21:14:10.072  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.072  3814  3865 I jxcore-log: 
,09-08 21:14:10.072  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.072  3814  3865 I jxcore-log: 
09-08 21:14:10.073  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.073  3814  3865 I jxcore-log: 
,09-08 21:14:10.074  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.074  3814  3865 I jxcore-log: 
,09-08 21:14:10.074  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.074  3814  3865 I jxcore-log: 
,09-08 21:14:10.075  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.075  3814  3865 I jxcore-log: 
,09-08 21:14:10.076  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 21:14:10.076  3814  3865 I jxcore-log: 
,09-08 21:14:10.076  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 21:14:10.076  3814  3865 I jxcore-log: 
,09-08 21:14:10.077  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 21:14:10.077  3814  3865 I jxcore-log: 
,09-08 21:14:10.077  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.077  3814  3865 I jxcore-log: 
,09-08 21:14:10.078  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.078  3814  3865 I jxcore-log: 
,09-08 21:14:10.079  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.079  3814  3865 I jxcore-log: 
,09-08 21:14:10.079  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.079  3814  3865 I jxcore-log: 
,09-08 21:14:10.080  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.080  3814  3865 I jxcore-log: 
,09-08 21:14:10.081  3814  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 21:14:10.081  3814  3865 I jxcore-log: 
,09-08 21:14:10.084  3814  3865 I jxcore-log: My device name is: motorola-Nexus 6
09-08 21:14:10.084  3814  3865 I jxcore-log: 
,09-08 21:14:10.379  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 21:14:10.434  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 21:14:10.491  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 21:14:11.539   874  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-08 21:14:11.922  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:12.053  1509  4259 I VacuumService: Vacuum at: now=1473362052053 tag=VacuumService
,09-08 21:14:12.215  1509  4260 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 21:14:12.220  1509  4260 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 21:14:12.287  1509  4260 W Uploader:  no longer exists, so no auth token.
,09-08 21:14:12.319  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:12.342  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 21:14:12.343  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 21:14:12.343  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:12.343  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:12.371  3555  3555 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 21:14:12.371  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 21:14:12.372  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 21:14:12.636  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 21:14:12.636  3814  3865 I jxcore-log: 
,09-08 21:14:13.119  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 21:14:13.119  3814  3865 I jxcore-log: 
,09-08 21:14:13.146  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 21:14:13.146  3814  3865 I jxcore-log: 
,09-08 21:14:13.619  1509  4260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 21:14:13.619  1509  4260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 21:14:13.619  1509  4260 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:13.619  1509  4260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:13.637  1509  4260 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 21:14:13.637  1509  4260 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 21:14:13.637  1509  4260 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 21:14:13.971  1509  4260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 21:14:13.972  1509  4260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-08 21:14:13.972  1509  4260 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:13.972  1509  4260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:13.991  1509  4260 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 21:14:13.991  1509  4260 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 21:14:13.991  1509  4260 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 21:14:14.561  1509  4260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 21:14:14.562  1509  4260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 21:14:14.562  1509  4260 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-08 21:14:14.562  1509  4260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:14.581  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 21:14:14.581  3814  3865 I jxcore-log: 
,09-08 21:14:14.583  1509  4260 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 21:14:14.583  1509  4260 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 21:14:14.583  1509  4260 E Uploader: 	,at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 21:14:14.583  1509  4260 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 21:14:14.814  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 21:14:14.814  3814  3865 I jxcore-log: 
,09-08 21:14:14.819  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 21:14:14.819  3814  3865 I jxcore-log: 
,09-08 21:14:14.838  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 21:14:14.838  3814  3865 I jxcore-log: 
,09-08 21:14:14.843  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 21:14:14.843  3814  3865 I jxcore-log: 
,09-08 21:14:15.710  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 21:14:15.710  3814  3865 I jxcore-log: 
,09-08 21:14:15.724  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js
09-08 21:14:15.724  3814  3865 I jxcore-log: 
,09-08 21:14:15.897  3814  3865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 21:14:15.897  3814  3865 I jxcore-log: 
,09-08 21:14:16.112  3814  3865 W jxcore-log: !!! js_ReportOverRecursed called !!!
,09-08 21:14:16.171  4273  3865 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,09-08 21:14:16.172  4273  3865 W google-breakpad: O A arm 04 armv7l 3.10.40-geb6cc9d #1 SMP PREEMPT Wed Apr 20 00:05:01 UTC 2016
,09-08 21:14:16.172  4273  3865 W google-breakpad: S 0 98C67300 98C67000 00008000
,09-08 21:14:16.241  4273  3865 W google-breakpad: S 98C67000 2074C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,09-08 21:14:16.242  4273  3865 W google-breakpad: S 98C67180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DBC0FED4B61872C69880EFD19FC872C6982872C698986ED78B8472C69834126A9400000000000000000000000040B0D2902872C69801000000107FC698F6FFFFFF8CEFD19F0000000080EFD19F1872C6980300000008000000403FD79088FFFFFF40B0D29088FFFFFFE081B28C85FFFFFF48380196906ED78B0070A8984873C6980C83D5B64038019694B5D4B648380196906ED78B5BE2D2B6000000006C72C6980100000080EFD19F8472C698E4A85A949475C698B47EC69880EFD19F00000000B472C698ACFC5994906ED78BD072C69840B0D29069090000003BB79810709196DC72C69860EB3A94000000004873C6982C000000F872C698D072C6980700000058DBAA947C06959480EFD19F0000000085FFFFFF00D08B963473C69870F03A9400000000F872C69880EFD19F00000000740695944873C6987C0695943473C698
09-08 21:14:16.242  4273  3865 W google-breakpad: S 98C67300 07000000000000000000000090B8E0E61082B28C85FFFFFFE01DE19080EFD19FB873C6986473C6983C73C69885FFFFFF5C73C69870D5599400000000E01DE190220000002874C6986473C698B873C6987C0695941082B28C8473C698887E7B944CC74B8C000000000000000082FFFFFFB873C6982874C698A873C69880EFD19FEC73C6986C127494ECC7949458CB949458DBAA94220000004CC74B8C4449408C00000000BC73C6981082B28C85FFFFFF80EFD19F000000001082B28C85FFFFFF7074C6984075C698C0C3AB943874C69800000000010000002874C6981874C6982200000080EFD19F7C75C698783B7794806ED78BF6FFFFFF8CEFD19F0000000080EFD19F5074C698020000007074C69880BD988F88FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF80EFD19F000000000000000080EFD19F01000000A075C698B075C69801000000806ED78B0700000007000000010000008080B28C0000000080EFD19F000000000000000006000000E4C3AB94E4C3AB94
09-08 21:14:16.242  4273  3865 W google-breakpad: S 98C67480 06000000C0C3AB9400000000FFFFFFFF00000000886ED78B220000008880B28C0700000000000000010000001800E090503DCE9081FFFFFFDC74C69830526494070000008080B28C80EFD19F000000001000E090E874C6981C75C69838946494000000000000000000000000DCC437915075C698010000000000000060DD998CE01BE1908080B28C00000000FFFFFFFF503DCE9081FFFFFFB875C69880C537911076C6982C75C6987875C698000000000000000048C537914003000001000000FFFFFFFF81FFFFFF8080B28C85FFFFFF1000E09085FFFFFFB075C6984049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9081FFFFFFB875C69838DFEA98000000008C75C6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF8080B28C85FFFFFF1476C698C03DCE909002FE90010500008080B28C85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290
09-08 21:14:16.242  4273  3865 W google-breakpad: S 98C67600 F0D9E19085FFFFFF4476C6985C76C698000000003876C6988CE9EA98820100006086D690010000000000000082FFFFFF8080B28C85FFFFFFE476C698C015A390A425FD90010A00008080B28C85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFB0905A8902000000000000001077C6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFF8080B28C85FFFFFFA0EC468D88FFFFFF8477C69880E1578DCCD05A8981060000F0D9E19085FFFFFF8080B28C85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300006877C6980000000083FFFFFF68000000A05CD78C8880B28C0100000030000000A05CD78C
09-08 21:14:16.242  4273  3865 W google-breakpad: S 98C67780 00000000A877C6988CE9EA9882010000203E468D010000000000000082FFFFFF8080B28C85FFFFFF2C78C6987048C28C04C95A89810700008080B28C85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF4878C6984078C6983878C698AC78C69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F000000005078C6988CE9EA9882010000603E468D010000000000000082FFFFFF8080B28C85FFFFFFBC78C69898A1AF8CE4BE5A89010600008080B28C85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5D390C878C698E078C6980400000060000000A05CD78CE02D898C81FFFFFF4C79C698F89FEA9800000000E078C6988CE9EA9882010000803E468D010000000000000082FFFFFF8080B28C85FFFFFF4C79C69,89829A78CF0B55A89010600008080B28C85FFFFFF0000000082FFFFFF
09-08 21:14:16.243  4273  3865 W google-breakpad: S 98C67900 803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000DD998C00000000C8E8888E6000000030DD998C04000000B0905A895C79C698C8AB4694040000007079C6988CE9EA9882010000A03E468D010000000000000082FFFFFF00DD998C88FFFFFFEC79C698902C898CFCAC5A890107000000DD998C88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFF8080B28C85FFFFFF00000000E079C698DC79C69888FFFFFF70000000D0DC998C00C1BB8CD4885994000000000000000004000000107AC6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFF40D9998C88FFFFFF6C7AC6986021898C68A65A890105000040D9998C88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFF00C1BB8C010000009C7AC698B47AC69850000000701F6E8D0200000070CFA38F8C7AC69818AB469400000000A07AC6980CB58C8F82020000E05ED18C03000000
09-08 21:14:16.243  4273  3865 W google-breakpad: S 98C67A80 0000000082FFFFFF40D9998C88FFFFFF0000000081FFFFFF00C1BB8C88FFFFFF3C7BC698D00C3E8D0081858C0109000000C1BB8C88FFFFFF0000000081FFFFFF40D9998C88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFE079B98F88FFFFFF0000000082FFFFFF0900000081FFFFFF00C1BB8C88FFFFFF50C1BB8C000000006C7BC698C0D6D2909000000020C0D290B0905A890200000070B6748C81FFFFFF00000000607BC6988CE9EA9882010000B002D3900100000000C1BB8C88FFFFFFE05ED18C88FFFFFFE47BC69828BD748C38A05A8981070000E05ED18C88FFFFFF00C1BB8C88FFFFFFB002D39088FFFFFF50C1BB8C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFF50C1BB8C88FFFFFF0000000082FFFFFF087CC69838DFEA9800000000CC7BC69878000000701F6E8D00000000EC965A89420300000300000000000000107CC6988CE9EA9802020000005FD18C02000000C014138F88FFFFFF
09-08 21:14:16.243  4273  3865 W google-breakpad: S 98C67C00 80BD988F88FFFFFF00C1BB8C88FFFFFF7C7CC69878B0748CB89B5A890106000000C1BB8C88FFFFFF80BD988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFF487CC698D0B0D2908035D49088FFFFFF60000000701F6E8D8018E0909018598985FFFFFF7C7CC69800000000E036D49064235989000C0000405FD18C02000000E036D49088FFFFFF80BD988F88FFFFFF00DBBE8C88FFFFFFC081B28C85FFFFFFB0C0BB8C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFFC7CC69860DA998C00DBBE8C8035D490E09A658D8A00000010DC998CC081B28C00DBBE8C88FFFFFFB0C0BB8C00DBBE8C8035D490B081B28C8018E090409B658D0900000040EC468DD0B0D290D0B0D29000DBBE8C88FFFFFF090000004011E19009000000E036D49080BD988F10D9998C40EC468D88FFFFFF00000000BC9F818C60A1818C000400006036D49001000000E036D49088FFFFFF80BD988F88FFFFFF0000000082FFFFFF982DB49480BD988F
09-08 21:14:16.243  4273  3865 W google-breakpad: S 98C67D80 E0D8998CB0D8998C0000000087FFFFFFA00FD39080D8998CB0D8998C20EC468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFF80D8998C88FFFFFFC0FED4B680D8998C20D8998C50D8998C9CF1379180020000E036D4900000000020D8998C88FFFFFF000000000000000030243B8F8A0000000700000040B0D290D09A658DE036D4902018EA9803020000403FD7900100000040B0D29088FFFFFFD09A658D85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B6D87FC6980100000081FFFFFF307FC6989C7FC698646B4C94403FD7900000000000000000007FC698B47EC6983817EA9858DBAA9480EFD19F002B41912490C698000000000000000000000000010000000487C69880EFD19F000100000000000050F0379100000000403FD7909083C69802000000010000000000000000000000
,09-08 21:14:16.244  4273  3865 W google-breakpad: S 98C67F00 0100000081FFFFFF00000000000000006883C698F6FFFFFF8CEFD19F0100000080EFD19F307FC698000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000D87FC69880EFD19F203EB4940052DB9000000000786ED78B9C7FC698407067DB0000000080EFD19FD87FC698A07FC698403FD7900052DB9000000000786ED78BC47FC6987C0C6A94000000000000000000000000C0FED4B60100000080EFD19F9883C698D07FC6984C83C698740D6A9400000000000000009883C69801000000780BAA94010000000052DB90D07FC698000000000000000090EE129DCEEE129D0200000002000000010000000000000010B9A9945C0000000600000000000000108FC69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,09-08 21:14:16.244  4273  3865 W google-breakpad: S 98C68080 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E4129D0000000000000000010000000200000080EB468D0053DB906564D29F0000000000000000407067DB00000000C0FED4B60000000080EFD19F18625C947081C698EC84C698F80D6A9400000000000000009085C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.244  4273  3865 W google-breakpad: S 98C68200 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DBC0FED4B68883C69880EFD19F3884C6989883C698786ED78BF483C69834126A9400000000000000000000000040B0D2909883C698010000008090C698F6FFFFFF8CEFD19F0000000080EFD19F8883C698
,09-08 21:14:16.244  4273  3865 W google-breakpad: S 98C68380 0300000008000000403FD79088FFFFFF40B0D29088FFFFFFD09A658D85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000407067DB0400000080EFD19F4884C6983884C6984084C6983484C69882FFFFFF706ED78B2484C69888FC5994706ED78B4084C69840B0D29088FFFFFFA884C698B884C6989885C698010000005084C698000000008484C69850927B944084C698000000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000706ED78B0000000082FFFFFF80EFD19F0000000074069594B884C698A884C69880AD949E18B0949E80EFD19F9885C69874069594F484C69808A27294B884C6980C85C698070000004F000000CC73698CFCC64B8C00000000F0C64B8C40B0D29088FFFFFF80EFD19F00000000D09A658D85FFFFFF80EFD19F000000000885C698205F96941DC74B8C2885C6989885C6981885C69880EFD19F0C85C6982200000080AD949E5C85C6983C127494ECC7949458CB9494
09-08 21:14:16.245  4273  3865 W google-breakpad: S 98C68500 58DBAA9422000000FCC64B8C1449408C000000002C85C6982200000000000000B086C698000000004485C69864DC3194E085C698B086C698C0C3AB94A885C69800000000010000009885C6988885C6982200000080EFD19FEC86C698783B7794606ED78BF6FFFFFF8CEFD19F0000000080EFD19FC085C69802000000E085C69830BD988F88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080EFD19F010000001087C6982087C69801000000606ED78B0700000007000000010000007099658D0000000080EFD19F00000000B00A4C8F06000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000686ED78B220000007899658D0700000000000000010000001800E090503DCE9081FFFFFF4C86C69830526494070000007099658D80EFD19F000000001000E0905886C6988C86C69838946494000000000000000000000000DCC43791C086C6980100000000000000F0D7998CE01BE1907099658D00000000FFFFFFFF
,09-08 21:14:16.245  4273  3865 W google-breakpad: S 98C68680 503DCE9081FFFFFF2887C69880C537918087C6989C86C698E886C698000000000000000048C537914003000001000000FFFFFFFF81FFFFFF7099658D85FFFFFF1000E09085FFFFFF2087C6984049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9081FFFFFF2887C69838DFEA9800000000FC86C6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF7099658D85FFFFFF8487C698C03DCE909002FE90010500007099658D85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFFB487C698CC87C69800000000A887C6988CE9EA98820100006086D690010000000000000082FFFFFF7099658D85FFFFFF5488C698C015A390A425FD90010A00007099658D85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
,09-08 21:14:16.245  4273  3865 W google-breakpad: S 98C68800 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFB0905A8902000000000000008088C6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFF7099658D85FFFFFF00EC468D88FFFFFFF488C69880E1578DCCD05A8981060000F0D9E19085FFFFFF7099658D85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D888C6980000000083FFFFFF68000000A05CD78C7899658D0100000030000000A05CD78C000000001889C6988CE9EA9882010000203E468D010000000000000082FFFFFF7099658D85FFFFFF9C89C6987048C28C04C95A89810700007099658D85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB889C698B089C698A889C6981C8AC698
,09-08 21:14:16.245  4273  3865 W google-breakpad: S 98C68980 78000000A05CD78C0000000016AE488F58DBAA9480EFD19F00000000C089C6988CE9EA9882010000603E468D010000000000000082FFFFFF7099658D85FFFFFF2C8AC69898A1AF8CE4BE5A89010600007099658D85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5D390388AC698508AC6980400000060000000A05CD78CE02D898C81FFFFFFBC8AC698F89FEA9800000000508AC6988CE9EA9882010000803E468D010000000000000082FFFFFF7099658D85FFFFFFBC8AC6989829A78CF0B55A89010600007099658D85FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000090D7998C00000000C8E8888E60000000C0D7998C04000000B0905A89CC8AC698C8AB469404000000E08AC6988CE9EA9882010000A03E468D010000000000000082FFFFFF90D7998C88FFFFFF5C8BC698902C898CFCAC5A890107000090D7998C88FFFFFF0000000082FFFFFF
09-08 21:14:16.245  4273  3865 W google-breakpad: S 98C68B00 A03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFF7099658D85FFFFFF00000000508BC6984C8BC69888FFFFFF7000000060D7998C60DABE8CD4885994000000000000000004000000808BC6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFFA0D3998C88FFFFFFDC8BC6986021898C68A65A8901050000A0D3998C88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFF60DABE8C010000000C8CC698248CC69850000000701F6E8D0200000070CFA38FFC8BC69818AB469400000000108CC6980CB58C8F82020000E05ED18C030000000000000082FFFFFFA0D3998C88FFFFFF0000000081FFFFFF60DABE8C88FFFFFFAC8CC698D00C3E8D0081858C0109000060DABE8C88FFFFFF0000000081FFFFFFA0D3998C88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF7079B98F88FFFFFF0000000082FFFFFF0900000081FFFFFF60DABE8C88FFFFFF
,09-08 21:14:16.246  4273  3865 W google-breakpad: S 98C68C80 B0DABE8C00000000DC8CC698C0D6D2909000000020C0D290B0905A890200000070B6748C81FFFFFF00000000D08CC6988CE9EA9882010000B002D3900100000060DABE8C88FFFFFFE05ED18C88FFFFFF548DC69828BD748C38A05A8981070000E05ED18C88FFFFFF60DABE8C88FFFFFFB002D39088FFFFFFB0DABE8C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFFB0DABE8C88FFFFFF0000000082FFFFFF788DC69838DFEA98000000003C8DC69878000000701F6E8D00000000EC965A89420300000300000000000000808DC6988CE9EA9802020000005FD18C02000000C014138F88FFFFFF30BD988F88FFFFFF60DABE8C88FFFFFFEC8DC69878B0748CB89B5A890106000060DABE8C88FFFFFF30BD988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFFB88DC698D0B0D2908035D49088FFFFFF60000000701F6E8D8018E0909018598985FFFFFFEC8DC69800000000E036D49064235989000C0000405FD18C02000000
,09-08 21:14:16.246  4273  3865 W google-breakpad: S 98C68E00 E036D49088FFFFFF30BD988F88FFFFFF70D4BE8C88FFFFFFB09A658D85FFFFFF10DABE8C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF6C8EC698C0D4998C70D4BE8C8035D49030243B8F8A00000070D6998CB09A658D70D4BE8C88FFFFFF10DABE8C70D4BE8C8035D490A09A658D8018E09090243B8F09000000A0EB468DD0B0D290D0B0D29070D4BE8C88FFFFFF090000004011E19009000000E036D49030BD988F70D3998CA0EB468D88FFFFFF00000000BC9F818C60A1818C000400006036D49001000000E036D49088FFFFFF30BD988F88FFFFFF0000000082FFFFFF982DB49430BD988F40D3998C10D3998C0000000087FFFFFFA00FD390E0D2998C10D3998C80EB468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFFE0D2998C88FFFFFFC0FED4B6E0D2998C50D2998C80D2998C9CF1379180020000E036D4900000000050D2998C88FFFFFF000000000000000080FE46908A0000000700000040B0D29020243B8FE036D490
09-08 21:14:16.246  4273  3865 W google-breakpad: S 98C68F80 2018EA9803020000403FD7900100000040B0D29088FFFFFF20243B8F85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B64891C6980100000081FFFFFFA090C6980C91C698646B4C94403FD79000000000000000007090C6982490C6983817EA9858DBAA9480EFD19F002B419194A1C698000000000000000000000000010000007498C69880EFD19F000100000000000050F0379100000000403FD7900095C698020000000100000000000000000000000100000081FFFFFF0000000000000000D894C698F6FFFFFF8CEFD19F0100000080EFD19FA090C6980000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000004891C69880EFD19F203EB4940052DB9000000000586ED78B0C91C698407067DB0000000080EFD19F4891C6981091C698403FD7900052DB90
,09-08 21:14:16.246  4273  3865 W google-breakpad: S 98C69100 00000000586ED78B3491C6987C0C6A94000000000000000000000000C0FED4B60100000080EFD19F0895C6984091C698BC94C698740D6A9400000000000000000895C69801000000780BAA94010000000052DB904091C698000000000000000090EE129DCEEE129D0200000002000000010000000000000010B9A9945C000000060000000000000080A0C69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.247  4273  3865 W google-breakpad: S 98C69280 00000000000000000000000000E4129D00000000000000000100000002000000E0EA468D0053DB906564D29F0000000000000000407067DB00000000C0FED4B60000000080EFD19F18625C94E092C6985C96C698F80D6A9400000000000000000097C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.247  4273  3865 W google-breakpad: S 98C69400 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DBC0FED4B6F894C69880EFD19FA895C6980895C698586ED78B6495C69834126A9400000000000000000000000040B0D2900895C69801000000F0A1C698F6FFFFFF8CEFD19F0000000080EFD19FF894C6980300000008000000403FD79088FFFFFF40B0D29088FFFFFF20243B8F85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DB0000000080EFD19FB895C698A895C698B095C698A495C69882FFFFFF506ED78B9495C69888FC5994506ED78BB095C69840B0D29088FFFFFF1896C6982896C698
09-08 21:14:16.247  4273  3865 W google-breakpad: S 98C69580 0897C69801000000C095C69800000000F495C69850927B94B095C698000000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000506ED78B0000000082FFFFFF80EFD19F00000000740695942896C6981896C69880AD949E18B0949E80EFD19F0897C698740695946496C69808A272942896C6987C96C698070000004F000000CC73698CACC64B8C00000000A0C64B8C40B0D29088FFFFFF80EFD19F0000000020243B8F85FFFFFF80EFD19F000000007896C698205F9694CDC64B8C9896C6980897C6988896C69880EFD19F7C96C6982200000080AD949ECC96C6983C127494ECC7949458CB949458DBAA9422000000ACC64B8CE448408C000000009C96C69822000000000000002098C69800000000B496C69864DC31945097C6982098C698C0C3AB941897C69800000000010000000897C698F896C6982200000080EFD19F5C98C698783B7794406ED78BF6FFFFFF8CEFD19F0000000080EFD19F3097C698020000005097C698E0BC988F88FFFFFF0000000082FFFFFF
09-08 21:14:16.247  4273  3865 W google-breakpad: S 98C69700 0000000000010000220000000000000000000000000000000000000080EFD19F010000008098C6989098C69801000000406ED78B070000000700000001000000C0223B8F0000000080EFD19F000000000000000006000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000486ED78B22000000C8223B8F0700000000000000010000001800E090503DCE9081FFFFFFBC97C6983052649407000000C0223B8F80EFD19F000000001000E090C897C698FC97C69838946494000000000000000000000000DCC437913098C698010000000000000020D2998CE01BE190C0223B8F00000000FFFFFFFF503DCE9081FFFFFF9898C69880C53791F098C6980C98C6985898C698000000000000000048C537914003000001000000FFFFFFFF81FFFFFFC0223B8F85FFFFFF1000E09085FFFFFF9098C6984049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9081FFFFFF9898C69838DFEA98000000006C98C6988CE9EA9800000000000000009002FE904202000001000000
09-08 21:14:16.248  4273  3865 W google-breakpad: S 98C69880 4049D69088FFFFFF00EAD29088FFFFFFC0223B8F85FFFFFFF498C698C03DCE909002FE9001050000C0223B8F85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFF2499C6983C99C698000000001899C6988CE9EA98820100006086D690010000000000000082FFFFFFC0223B8F85FFFFFFC499C698C015A390A425FD90010A0000C0223B8F85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFB0905A890200000000000000F099C6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFFC0223B8F85FFFFFF60EB468D88FFFFFF649AC69880E1578DCCD05A8981060000
09-08 21:14:16.248  4273  3865 W google-breakpad: S 98C69A00 F0D9E19085FFFFFFC0223B8F85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000489AC6980000000083FFFFFF68000000A05CD78CC8223B8F0100000030000000A05CD78C00000000889AC6988CE9EA9882010000203E468D010000000000000082FFFFFFC0223B8F85FFFFFF0C9BC6987048C28C04C95A8981070000C0223B8F85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF289BC698209BC698189BC6988C9BC69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F00000000309BC6988CE9EA9882010000603E468D010000000000000082FFFFFFC0223B8F85FFFFFF9C9BC69898A1AF8CE4BE5A8901060000C0223B8F85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5D390A89BC698C09BC69804000000
09-08 21:14:16.248  4273  3865 W google-breakpad: S 98C69B80 60000000A05CD78CE02D898C81FFFFFF2C9CC698F89FEA9800000000C09BC6988CE9EA9882010000803E468D010000000000000082FFFFFFC0223B8F85FFFFFF2C9CC6989829A78CF0B55A8901060000C0223B8F85FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000C0D1998C00000000C8E8888E60000000F0D1998C04000000B0905A893C9CC698C8AB469404000000509CC6988CE9EA9882010000A03E468D010000000000000082FFFFFFC0D1998C88FFFFFFCC9CC698902C898CFCAC5A8901070000C0D1998C88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFFC0223B8F85FFFFFF00000000C09CC698BC9CC69888FFFFFF7000000090D1998CD0D3BE8CD4885994000000000000000004000000F09CC6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFFF00D8D8E88FFFFFF4C9DC6986021898C68A65A8901050000
09-08 21:14:16.248  4273  3865 W google-breakpad: S 98C69D00 F00D8D8E88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFFD0D3BE8C010000007C9DC698949DC69850000000701F6E8D0200000070CFA38F6C9DC69818AB469400000000809DC6980CB58C8F82020000E05ED18C030000000000000082FFFFFFF00D8D8E88FFFFFF0000000081FFFFFFD0D3BE8C88FFFFFF1C9EC698D00C3E8D0081858C01090000D0D3BE8C88FFFFFF0000000081FFFFFFF00D8D8E88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF0079B98F88FFFFFF0000000082FFFFFF0900000081FFFFFFD0D3BE8C88FFFFFF20D4BE8C000000004C9EC698C0D6D2909000000020C0D290B0905A890200000070B6748C81FFFFFF00000000409EC6988CE9EA9882010000B002D39001000000D0D3BE8C88FFFFFFE05ED18C88FFFFFFC49EC69828BD748C38A05A8981070000E05ED18C88FFFFFFD0D3BE8C88FFFFFFB002D39088FFFFFF20D4BE8C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF
09-08 21:14:16.248  4273  3865 W google-breakpad: S 98C69E80 0000000082FFFFFF20D4BE8C88FFFFFF0000000082FFFFFFE89EC69838DFEA9800000000AC9EC69878000000701F6E8D00000000EC965A89420300000300000000000000F09EC6988CE9EA9802020000005FD18C02000000C014138F88FFFFFFE0BC988F88FFFFFFD0D3BE8C88FFFFFF5C9FC69878B0748CB89B5A8901060000D0D3BE8C88FFFFFFE0BC988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFF289FC698D0B0D2908035D49088FFFFFF60000000701F6E8D8018E0909018598985FFFFFF5C9FC69800000000E036D49064235989000C0000405FD18C02000000E036D49088FFFFFFE0BC988F88FFFFFF90BCB58C88FFFFFF00243B8F85FFFFFF30D3BE8C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFDC9FC698100F8D8E90BCB58C8035D49080FE46908A000000D0D0998C00243B8F90BCB58C88FFFFFF30D3BE8C90BCB58C8035D490F0233B8F8018E090E0FE46900900000000EB468DD0B0D290D0B0D290
09-08 21:14:16.249  4273  3865 W google-breakpad: S 98C6A000 90BCB58C88FFFFFF090000004011E19009000000E036D490E0BC988FC00D8D8E00EB468D88FFFFFF00000000BC9F818C60A1818C000400006036D49001000000E036D49088FFFFFFE0BC988F88FFFFFF0000000082FFFFFF982DB494E0BC988F600D8D8E300D8D8E0000000087FFFFFFA00FD390000D8D8E300D8D8EE0EA468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFF000D8D8E88FFFFFFC0FED4B6000D8D8EA00C8D8ED00C8D8E9CF1379180020000E036D49000000000A00C8D8E88FFFFFF00000000000000009049D68D8A0000000700000040B0D29070FE4690E036D4902018EA9803020000403FD7900100000040B0D29088FFFFFF70FE469085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B6B8A2C6980100000081FFFFFF10A2C6987CA2C698646B4C94403FD79000000000
09-08 21:14:16.249  4273  3865 W google-breakpad: S 98C6A180 00000000E0A1C69894A1C6983817EA9858DBAA9480EFD19F002B419104B3C69800000000000000000000000001000000E4A9C69880EFD19F000100000000000050F0379100000000403FD79070A6C698020000000100000000000000000000000100000081FFFFFF000000000000000048A6C698F6FFFFFF8CEFD19F0100000080EFD19F10A2C698000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B8A2C69880EFD19F203EB4940052DB9000000000386ED78B7CA2C698407067DB0000000080EFD19FB8A2C69880A2C698403FD7900052DB9000000000386ED78BA4A2C6987C0C6A94000000000000000000000000C0FED4B60100000080EFD19F78A6C698B0A2C6982CA6C698740D6A94000000000000000078A6C69801000000780BAA94010000000052DB90B0A2C698000000000000000090EE129DCEEE129D0200000002000000010000000000000010B9A9945C0000000600000000000000F0B1C69800000000
09-08 21:14:16.249  4273  3865 W google-breakpad: S 98C6A300 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E4129D0000000000000000010000000200000040EA468D0053DB906564D29F0000000000000000407067DB00000000C0FED4B60000000080EFD19F18625C9450A4C698CCA7C698F80D6A94000000000000000070A8C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.249  4273  3865 W google-breakpad: S 98C6A480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.250  4273  3865 W google-breakpad: S 98C6A600 000000000000000000000000407067DBC0FED4B668A6C69880EFD19F18A7C69878A6C698386ED78BD4A6C69834126A9400000000000000000000000040B0D29078A6C6980100000060B3C698F6FFFFFF8CEFD19F0000000080EFD19F68A6C6980300000008000000403FD79088FFFFFF40B0D29088FFFFFF70FE469085FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DB0000000080EFD19F28A7C69818A7C69820A7C69814A7C69882FFFFFF306ED78B04A7C69888FC5994306ED78B20A7C69840B0D29088FFFFFF88A7C69898A7C69878A8C6980100000030A7C6980000000064A7C69850927B9420A7C698000000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000306ED78B0000000082FFFFFF80EFD19F000000007406959498A7C69888A7C69880AD949E18B0949E80EFD19F78A8C69874069594D4A7C69808A2729498A7C698ECA7C698070000004F000000CC73698C5CC64B8C
09-08 21:14:16.250  4273  3865 W google-breakpad: S 98C6A780 0000000050C64B8C40B0D29088FFFFFF80EFD19F0000000070FE469085FFFFFF80EFD19F00000000E8A7C698205F96947DC64B8C08A8C69878A8C698F8A7C69880EFD19FECA7C6982200000080AD949E3CA8C6983C127494ECC7949458CB949458DBAA94220000005CC64B8CB448408C000000000CA8C698220000000000000090A9C6980000000024A8C69864DC3194C0A8C69890A9C698C0C3AB9488A8C698000000000100000078A8C69868A8C6982200000080EFD19FCCA9C698783B7794206ED78BF6FFFFFF8CEFD19F0000000080EFD19FA0A8C69802000000C0A8C69890BC988F88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080EFD19F01000000F0A9C69800AAC69801000000206ED78B07000000070000000100000010FD46900000000080EFD19F000000000000000006000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000286ED78B2200000018FD46900700000000000000010000001800E090
09-08 21:14:16.250  4273  3865 W google-breakpad: S 98C6A900 503DCE9081FFFFFF2CA9C698305264940700000010FD469080EFD19F000000001000E09038A9C6986CA9C69838946494000000000000000000000000DCC43791A0A9C6980100000000000000700C8D8EE01BE19010FD469000000000FFFFFFFF503DCE9081FFFFFF08AAC69880C5379160AAC6987CA9C698C8A9C698000000000000000048C537914003000001000000FFFFFFFF81FFFFFF10FD469085FFFFFF1000E09085FFFFFF00AAC6984049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9081FFFFFF08AAC69838DFEA9800000000DCA9C6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF10FD469085FFFFFF64AAC698C03DCE909002FE900105000010FD469085FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFF94AAC698ACAAC6980000000088AAC6988CE9EA98820100006086D690010000000000000082FFFFFF
09-08 21:14:16.250  4273  3865 W google-breakpad: S 98C6AA80 10FD469085FFFFFF34ABC698C015A390A425FD90010A000010FD469085FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFB0905A89020000000000000060ABC6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFF10FD469085FFFFFFC0EA468D88FFFFFFD4ABC69880E1578DCCD05A8981060000F0D9E19085FFFFFF10FD469085FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B8ABC6980000000083FFFFFF68000000A05CD78C18FD46900100000030000000A05CD78C00000000F8ABC6988CE9EA9882010000203E468D010000000000000082FFFFFF10FD469085FFFFFF7CACC6987048C28C
09-08 21:14:16.250  4273  3865 W google-breakpad: S 98C6AC00 04C95A898107000010FD469085FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF98ACC69890ACC69888ACC698FCACC69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F00000000A0ACC6988CE9EA9882010000603E468D010000000000000082FFFFFF10FD469085FFFFFF0CADC69898A1AF8CE4BE5A890106000010FD469085FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5D39018ADC69830ADC6980400000060000000A05CD78CE02D898C81FFFFFF9CADC698F89FEA980000000030ADC6988CE9EA9882010000803E468D010000000000000082FFFFFF10FD469085FFFFFF9CADC6989829A78CF0B55A890106000010FD469085FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000100C8D8E00000000C8E8888E
09-08 21:14:16.251  4273  3865 W google-breakpad: S 98C6AD80 60000000400C8D8E04000000B0905A89ACADC698C8AB469404000000C0ADC6988CE9EA9882010000A03E468D010000000000000082FFFFFF100C8D8E88FFFFFF3CAEC698902C898CFCAC5A8901070000100C8D8E88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFF10FD469085FFFFFF0000000030AEC6982CAEC69888FFFFFF70000000E00B8D8EF0BBB58CD488599400000000000000000400000060AEC6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFF20088D8E88FFFFFFBCAEC6986021898C68A65A890105000020088D8E88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFFF0BBB58C01000000ECAEC69804AFC69850000000701F6E8D0200000070CFA38FDCAEC69818AB469400000000F0AEC6980CB58C8F82020000E05ED18C030000000000000082FFFFFF20088D8E88FFFFFF0000000081FFFFFFF0BBB58C88FFFFFF8CAFC698D00C3E8D0081858C01090000
09-08 21:14:16.251  4273  3865 W google-breakpad: S 98C6AF00 F0BBB58C88FFFFFF0000000081FFFFFF20088D8E88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF2078B98F88FFFFFF0000000082FFFFFF0900000081FFFFFFF0BBB58C88FFFFFF40BCB58C00000000BCAFC698C0D6D2909000000020C0D290B0905A890200000070B6748C81FFFFFF00000000B0AFC6988CE9EA9882010000B002D39001000000F0BBB58C88FFFFFFE05ED18C88FFFFFF34B0C69828BD748C38A05A8981070000E05ED18C88FFFFFFF0BBB58C88FFFFFFB002D39088FFFFFF40BCB58C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFF40BCB58C88FFFFFF0000000082FFFFFF58B0C69838DFEA98000000001CB0C69878000000701F6E8D00000000EC965A8942030000030000000000000060B0C6988CE9EA9802020000005FD18C02000000C014138F88FFFFFF90BC988F88FFFFFFF0BBB58C88FFFFFFCCB0C69878B0748CB89B5A8901060000F0BBB58C88FFFFFF90BC988F88FFFFFF
09-08 21:14:16.251  4273  3865 W google-breakpad: S 98C6B080 C014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFF98B0C698D0B0D2908035D49088FFFFFF60000000701F6E8D8018E0909018598985FFFFFFCCB0C69800000000E036D49064235989000C0000405FD18C02000000E036D49088FFFFFF90BC988F88FFFFFF60B5B58C88FFFFFF50FE469085FFFFFFA0BBB58C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF4CB1C69870098D8E60B5B58C8035D4909049D68D8A000000200B8D8E50FE469060B5B58C88FFFFFFA0BBB58C60B5B58C8035D49040FE46908018E090F049D68D0900000060EA468DD0B0D290D0B0D29060B5B58C88FFFFFF090000004011E19009000000E036D49090BC988FF0078D8E60EA468D88FFFFFF00000000BC9F818C60A1818C000400006036D49001000000E036D49088FFFFFF90BC988F88FFFFFF0000000082FFFFFF982DB49490BC988FC0078D8E90078D8E0000000087FFFFFFA00FD39060078D8E90078D8E40EA468D90028C8980020000A036D49002000000
09-08 21:14:16.251  4273  3865 W google-breakpad: S 98C6B200 0000000082FFFFFFA00FD39088FFFFFF60078D8E88FFFFFFC0FED4B660078D8E00078D8E30078D8E9CF1379180020000E036D4900000000000078D8E88FFFFFF0000000000000000F0647D8F8A0000000700000040B0D2908049D68DE036D4902018EA9803020000403FD7900100000040B0D29088FFFFFF8049D68D85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B628B4C6980100000081FFFFFF80B3C698ECB3C698646B4C94403FD790000000000000000050B3C69804B3C6983817EA9858DBAA9480EFD19F002B419174C4C6980000000000000000000000000100000054BBC69880EFD19F0001C6980000000050F0379100000000403FD790E0B7C6980200000001000000D4E0D38B000000000100000081FFFFFF00B8C69800001000B8B7C698F6FFFFFF8CEFD19F0100000080EFD19F80B3C6980000000008000000
09-08 21:14:16.252  4273  3865 W google-breakpad: S 98C6B380 3C0082E000000000ACB3C698644B7094000080002000000030B6C698D844DB90000010000100000028B4C69880EFD19F203EB4940052DB9000000000186ED78BECB3C698407067DB0000000080EFD19F28B4C698F0B3C698403FD7900052DB9000000000186ED78B14B4C6987C0C6A940000000040BC988F24B4C698C0FED4B60100000080EFD19FE8B7C69820B4C6989CB7C698740D6A9428B8C698000000E0E8B7C69801000000780BAA94010000000052DB9020B4C698000000000000000564B4C6989C4270940200000038000000C4E0D38B7C41709411B4C6983800000028B8C69811B6C6983C000000000000E0C0FED4B630B6C698C8B4C698D844DB9040BC988F0000000094E0D38B405F7094D8E0D38BA4B4C69801000000B4B4C698B4B4C698FFFFFF0001000000C4B4C69808000000DCE0D38BB0E0D38B44E05A8950E05A897027709428E05A89F0FFFFFFFFFFFFFF0000000030B6C698441F2C744838019600E0D38B0070A89848B8C69848380196006ED78B0070A89830B6C698
09-08 21:14:16.252  4273  3865 W google-breakpad: S 98C6B500 0C83D5B64038019694B5D4B648380196006ED78B5BE2D2B604000000DCB5C698E849308F60B5C69854B5C69898AF4F9444E05A8954E05A89F82E208CF82E208C64B5C69848B8C69801000000F82E208C80EFD19F30B6C69801000000F82E208C80EFD19F40BC988F40BC988F0000000084B5C6987C6A3C9460BDC69830B6C69894B5C69874124B9400000000C0FED4B61CC1C698ACE44F940020208CC4AF95940D00000064CD638C030000000000000000000000505250940020208C6CB29594A037598930B6C698010000000020208CE8B5C698D844DB9040BC988FB8C9A89441B0D2908422598910000000280000001C0000002C00000000000000F82E208C0D00000064CD638C03000000000000000D0000001C227094020000000100000030B6C69800000000000000000000000040B6C698000000000000000000000000000000000000000058B6C698000000000000000000000000000000000000000070B6C698000000000000000000000000000000000000000088B6C69800000000
09-08 21:14:16.252  4273  3865 W google-breakpad: S 98C6B680 000000000000000098B6C698000000000100000000000000A8B6C6980000000000000000000000000800000000000000C0B6C698000000000800000000000000D0B6C69800000000080000000000000008000000000000000800000000000000F0B6C69800000000000000000000000000B7C69800000000000000000500000010B7C6980000000000000000020000000200000000000000006ED78B010000000100000000000000000000000100000040B7C698000000000000000000000000200000000000000058B7C69800000000200000000000000068B7C698000000002000000005000000010000000500000080B7C6980200000001000000407067DBC0FED4B6D8B7C69880EFD19F88B8C698E8B7C698186ED78B44B8C69834126A940100000000000000B8B7C69840B0D290E8B7C69801000000D0C4C698F6FFFFFF8CEFD19F0000000080EFD19FD8B7C6980300000008000000403FD79088FFFFFF40B0D29088FFFFFF8049D68D85FFFFFF00B8C698000000002000000000000000
09-08 21:14:16.252  4273  3865 W google-breakpad: S 98C6B800 10B8C6980000000020000000B0E0D38B01E4D38B0000D38B0029A894407067DB01E4D38B80EFD19F98B8C69888B8C69890B8C69884B8C69882FFFFFF106ED78B74B8C69888FC5994106ED78B90B8C69840B0D29088FFFFFFF8B8C69808B9C698E8B9C69801000000A0B8C69800000000D4B8C69850927B9490B8C698080000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000106ED78B0000000082FFFFFF80EFD19F000000007406959408B9C698F8B8C69880AD949E18B0949E80EFD19FE8B9C6987406959444B9C69808A2729408B9C6985CB9C698070000004F000000CC73698C0CC64B8C0000000000C64B8C40B0D29088FFFFFF80EFD19F000000008049D68D85FFFFFF80EFD19F0000000058B9C698205F96942DC64B8C78B9C698E8B9C69868B9C69880EFD19F5CB9C6982200000080AD949EACB9C6983C127494ECC7949458CB949458DBAA94220000000CC64B8C8448408C000000007CB9C698220000000000000000BBC6980000000094B9C69864DC3194
09-08 21:14:16.252  4273  3865 W google-breakpad: S 98C6B980 30BAC69800BBC698C0C3AB94F8B9C6980000000001000000E8B9C698D8B9C6982200000080EFD19F3CBBC698783B7794006ED78BF6FFFFFF8CEFD19F0000000080EFD19F10BAC6980200000030BAC69840BC988F88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080EFD19F0100000060BBC69870BBC69801000000006ED78B0700000007000000010000001048D68D0000000080EFD19F000000000000000006000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000086ED78B220000001848D68D0700000000000000010000001800E090503DCE9081FFFFFF9CBAC69830526494070000001048D68D80EFD19F000000001000E090A8BAC698DCBAC698389464944410189DA853DDB4F482D5B6DCC4379110BBC69801000000AC0B2890D0068D8EE01BE1901048D68D00000000FFFFFFFF503DCE9081FFFFFF78BBC69880C53791D0BBC698ECBAC69838BBC698000000000000000048C537914003000001000000
09-08 21:14:16.253  4273  3865 W google-breakpad: S 98C6BB00 FFFFFFFF81FFFFFF1048D68D85FFFFFF1000E09085FFFFFF80BBC6984049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9081FFFFFF78BBC69838DFEA98000000004CBBC6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF1048D68D85FFFFFFD4BBC698C03DCE909002FE90010500001048D68D85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFF04BCC6981CBCC69800000000F8BBC6988CE9EA98820100006086D690010000000000000082FFFFFF1048D68D85FFFFFFA4BCC698C015A390A425FD90010A00001048D68D85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494
09-08 21:14:16.253  4273  3865 W google-breakpad: S 98C6BC80 F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFB0905A890200000000000000D0BCC6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFF1048D68D85FFFFFF20EA468D88FFFFFF44BDC69880E1578DCCD05A8981060000F0D9E19085FFFFFF1048D68D85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000028BDC6980000000083FFFFFF68000000A05CD78C1848D68D0100000030000000A05CD78C0000000068BDC6988CE9EA9882010000203E468D010000000000000082FFFFFF1048D68D85FFFFFFECBDC6987048C28C04C95A89810700001048D68D85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF08BEC69800BEC698F8BDC6986CBEC69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F0000000010BEC6988CE9EA9882010000603E468D01000000
09-08 21:14:16.253  4273  3865 W google-breakpad: S 98C6BE00 0000000082FFFFFF1048D68D85FFFFFF7CBEC69898A1AF8CE4BE5A89010600001048D68D85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5D39088BEC698A0BEC6980400000060000000A05CD78CE02D898C81FFFFFF0CBFC698F89FEA9800000000A0BEC6988CE9EA9882010000803E468D010000000000000082FFFFFF1048D68D85FFFFFF0CBFC6989829A78CF0B55A89010600001048D68D85FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000070068D8E00000000C8E8888E60000000A0068D8E04000000B0905A891CBFC698C8AB46940400000030BFC6988CE9EA9882010000A03E468D010000000000000082FFFFFF70068D8E88FFFFFFACBFC698902C898CFCAC5A890107000070068D8E88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFF1048D68D85FFFFFF
09-08 21:14:16.253  4273  3865 W google-breakpad: S 98C6BF80 00000000A0BFC6989CBFC69888FFFFFF7000000040068D8EC0B4B58CD4885994000000000000000004000000D0BFC6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFF80028D8E88FFFFFF2CC0C6986021898C68A65A890105000080028D8E88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFFC0B4B58C010000005CC0C69874C0C69850000000701F6E8D0200000070CFA38F4CC0C69818AB46940000000060C0C6980CB58C8F82020000E05ED18C030000000000000082FFFFFF80028D8E88FFFFFF0000000081FFFFFFC0B4B58C88FFFFFFFCC0C698D00C3E8D0081858C01090000C0B4B58C88FFFFFF0000000081FFFFFF80028D8E88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF4077B98F88FFFFFF0000000082FFFFFF0900000081FFFFFFC0B4B58C88FFFFFF10B5B58C000000002CC1C698C0D6D2909000000020C0D290B0905A890200000070B6748C81FFFFFF0000000020C1C698
09-08 21:14:16.254  4273  3865 W google-breakpad: S 98C6C100 8CE9EA9882010000B002D39001000000C0B4B58C88FFFFFFE05ED18C88FFFFFFA4C1C69828BD748C38A05A8981070000E05ED18C88FFFFFFC0B4B58C88FFFFFFB002D39088FFFFFF10B5B58C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFF10B5B58C88FFFFFF0000000082FFFFFFC8C1C69838DFEA98000000008CC1C69878000000701F6E8D00000000EC965A89420300000300000000000000D0C1C6988CE9EA9802020000005FD18C02000000C014138F88FFFFFF40BC988F88FFFFFFC0B4B58C88FFFFFF3CC2C69878B0748CB89B5A8901060000C0B4B58C88FFFFFF40BC988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFF08C2C698D0B0D2908035D49088FFFFFF60000000701F6E8D8018E0909018598985FFFFFF3CC2C69800000000E036D49064235989000C0000405FD18C02000000E036D49088FFFFFF40BC988F88FFFFFFC0EEB18C88FFFFFF6049D68D85FFFFFF70B4B58C88FFFFFF0900000081FFFFFF
09-08 21:14:16.254  4273  3865 W google-breakpad: S 98C6C280 0900000081FFFFFF0900000081FFFFFFBCC2C698A0038D8EC0EEB18C8035D490F0647D8F8A00000050058D8E6049D68DC0EEB18C88FFFFFF70B4B58CC0EEB18C8035D4905049D68D8018E09050657D8F09000000C0E9468DD0B0D290D0B0D290C0EEB18C88FFFFFF090000004011E19009000000E036D49040BC988F50028D8EC0E9468D88FFFFFF00000000BC9F818C60A1818C000400006036D49001000000E036D49088FFFFFF40BC988F88FFFFFF0000000082FFFFFF982DB49440BC988F20028D8EF0018D8E0000000087FFFFFFA00FD390C0018D8EF0018D8EA0E9468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFFC0018D8E88FFFFFF00000000C0018D8E60018D8E90018D8E9CF1379180020000E036D4900000000060018D8E88FFFFFF88CDC69848000000CCC3C69898CBC6984800000040B0D290E0647D8FE036D4902018EA9803020000403FD7900100000040B0D29088FFFFFFE0647D8F85FFFFFF00000000000000000000000000000000
09-08 21:14:16.254  4273  3865 W google-breakpad: S 98C6C400 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B698C5C6980100000081FFFFFFF0C4C6985CC5C698646B4C94403FD7900000000000000000C0C4C69874C4C6983817EA9858DBAA9480EFD19F002B4191DCD5C69800000000000000000000000001000000C4CCC69880EFD19F0001188D0000000050F0379100000000403FD79050C9C6980200000001000000887A748C000000000100000081FFFFFF0070A898985C518C28C9C698F6FFFFFF8CEFD19F0100000080EFD19FF0C4C69800000000080000005069188D3069188DD87A748C9F010000C870748C3069188DA069188D2A04000048C11E8C0100000098C5C69880EFD19F203EB4940052DB9000000000F86DD78B5CC5C698407067DB0000000080EFD19F98C5C69860C5C698403FD7900052DB9000000000F86DD78B84C5C6987C0C6A9400000000E0D8638C00000000C0FED4B60100000080EFD19F58C9C69890C5C698
09-08 21:14:16.254  4273  3865 W google-breakpad: S 98C6C580 0CC9C698740D6A9452EC129DFBED129D58C9C69801000000780BAA94010000000052DB9090C5C6980000000000EE129D0200000002000000010000000000000010B9A9945C0000000600000000000000C8D4C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E4129D00000000000000000100000002000000C0E4468D0053DB906564D29F0000000000000000407067DB
09-08 21:14:16.254  4273  3865 W google-breakpad: S 98C6C700 00000000C0FED4B60000000080EFD19F18625C9428C7C698A4CAC698F80D6A94000000000000000048CBC69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000BC00EC8B9810EC8B00000000008000009810EC8B97F3D1B6C0C8C69888C8C698DC00EC8B1008E88B0000000000100000
09-08 21:14:16.255  4273  3865 W google-breakpad: S 98C6C880 3813EC8B97F3D1B600C9C698A8C8C698A453DDB43813EC8B1008E88BA853DDB4F082D5B6BBF4D1B67404A08CFFFFFFFF78033C91FFFFFFFFF80D288FFFFFFFFF8814448EFFFFFFFFD002808DFFFFFFFF9411388DFFFFFFFF3015C48CFFFFFFFF6009708CFFFFFFFF2004608C407067DBC0FED4B648C9C69880EFD19FF8C9C69858C9C698F86DD78BB4C9C69834126A9400000000000000000000000040B0D29058C9C6980100000038D6C698F6FFFFFF8CEFD19F0000000080EFD19F48C9C6980300000008000000403FD79088FFFFFF40B0D29088FFFFFFE0647D8F85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000407067DB0400000080EFD19F08CAC698F8C9C69800CAC698F4C9C69882FFFFFFF06DD78BE4C9C69888FC5994F06DD78B00CAC69840B0D29088FFFFFF68CAC69878CAC69858CBC6980100000010CAC6980000000044CAC69850927B9400CAC698000000001800000040B0D290403FD79088FFFFFF
09-08 21:14:16.255  4273  3865 W google-breakpad: S 98C6CA00 0000000082FFFFFF01000000F06DD78B0000000082FFFFFF80EFD19F000000007406959478CAC69868CAC69880AD949E18B0949E80EFD19F58CBC69874069594B4CAC69808A2729478CAC698CCCAC698070000004F000000CC73698CCCC44B8C00000000C0C44B8C40B0D29088FFFFFF80EFD19F00000000E0647D8F85FFFFFF80EFD19F00000000C8CAC698205F9694EDC44B8CE8CAC69858CBC698D8CAC69880EFD19FCCCAC6982200000080AD949E1CCBC6983C127494ECC7949458CB949458DBAA9422000000CCC44B8C5448408CA075578CECCAC698220000000000000070CCC6980000000004CBC69864DC3194A0CBC69870CCC698C0C3AB9468CBC698000000000100000058CBC69848CBC6982200000080EFD19FACCCC698783B7794E06DD78B000000003812EF8B000000000000000080CBC6989CCBC698A0CBC698B8CBC698000000000000000082FFFFFF00000000000100002200000000000000000000000000000000CBC69880EFD19F01000000D0CCC698E0CCC69801100000
09-08 21:14:16.255  4273  3865 W google-breakpad: S 98C6CB80 E06DD78B07000000070000000100000080637D8F0000002080EFD19F4CC5C698985C518C06000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000D86DD78B2200000088637D8F0700000000000000010000001800E090503DCE90010000000CCCC698305264940700000080637D8F80EFD19F000000001000E09018CCC6984CCCC69838946494F0986B8C48996B8CA0996B8CDCC4379180CCC69801000000009B6B8C30018D8EE01BE19080637D8F00000000FFFFFFFF503DCE9001000000E8CCC69880C5379140CDC6985CCCC698A8CCC698000000000000000048C537914003000001000000FFFFFFFF81FFFFFF80637D8F85FFFFFF1000E09085FFFFFF40A36B8C4049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9001000000E8CCC69838DFEA9800000000BCCCC6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF80637D8F85FFFFFF44CDC698C03DCE909002FE900105000080637D8F85FFFFFF
09-08 21:14:16.255  4273  3865 W google-breakpad: S 98C6CD00 00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFF74CDC6988CCDC6980000000068CDC6988CE9EA98820100006086D690010000000000000082FFFFFF80637D8F85FFFFFF14CEC698C015A390A425FD90010A000080637D8F85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFFD03F858E030200000000000040CEC6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFF80637D8F85FFFFFF80E9468D88FFFFFFB4CEC69880E1578DCCD05A8981060000F0D9E19085FFFFFF80637D8F85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF
09-08 21:14:16.256  4273  3865 W google-breakpad: S 98C6CE80 0000000082FFFFFFC103000098CEC6980000000083FFFFFF68000000A05CD78C88637D8F0100000030000000A05CD78C00000000D8CEC6988CE9EA9882010000203E468D010000000000000082FFFFFF80637D8F85FFFFFF5CCFC6987048C28C04C95A898107000080637D8F85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF78CFC69870CFC69868CFC698DCCFC69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F0000000080CFC6988CE9EA9882010000603E468D010000000000000082FFFFFF80637D8F85FFFFFFECCFC69898A1AF8CE4BE5A890106000080637D8F85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F8CFC69810D0C6980400000060000000A05CD78CE02D898C010000007CD0C698F89FEA980000000010D0C6988CE9EA9882010000803E468D01000000
09-08 21:14:16.256  4273  3865 W google-breakpad: S 98C6D000 0000000082FFFFFF80637D8F85FFFFFF7CD0C6989829A78CF0B55A890106000080637D8F85FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D0008D8E00000000C8E8888E6000000000018D8E04000000D03F858E8CD0C698C8AB469404000000A0D0C6988CE9EA9882010000A03E468D010000000000000082FFFFFFD0008D8E88FFFFFF1CD1C698902C898CFCAC5A8901070000D0008D8E88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFF80637D8F85FFFFFF0000000010D1C6980CD1C69888FFFFFF70000000A0008D8E20EEB18CD488599400000000000000000400000040D1C6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFFA03C858E88FFFFFF9CD1C6986021898C68A65A8901050000A03C858E88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFF20EEB18C01000000CCD1C698E4D1C698
09-08 21:14:16.256  4273  3865 W google-breakpad: S 98C6D180 50000000701F6E8D0302000070CFA38FBCD1C69818AB469400000000D0D1C6980CB58C8F82020000E05ED18C030000000000000082FFFFFFA03C858E88FFFFFF0000000081FFFFFF20EEB18C88FFFFFF6CD2C698D00C3E8D0081858C0109000020EEB18C88FFFFFF0000000081FFFFFFA03C858E88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFD076B98F88FFFFFF0000000082FFFFFF0900000081FFFFFF20EEB18C88FFFFFF70EEB18C000000009CD2C698C0D6D2909000000020C0D290D03F858E0302000070B6748C010000000000000090D2C6988CE9EA9882010000B002D3900100000020EEB18C88FFFFFFE05ED18C88FFFFFF14D3C69828BD748C38A05A8981070000E05ED18C88FFFFFF20EEB18C88FFFFFFB002D39088FFFFFF70EEB18C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFF70EEB18C88FFFFFF0000000082FFFFFF38D3C69838DFEA9800000000FCD2C69878000000701F6E8D
09-08 21:14:16.256  4273  3865 W google-breakpad: S 98C6D300 00000000EC965A8942030000030000000000000040D3C6988CE9EA9802020000005FD18C02000000C014138F88FFFFFFF0BB988F88FFFFFF20EEB18C88FFFFFFACD3C69878B0748CB89B5A890106000020EEB18C88FFFFFFF0BB988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFFCC01EB98F4D3C698F8D3C698C0647D8F60000000701F6E8DE0D3C698C0647D8FD03F858E0302000000000000D8D3C6988CE9EA9802020000405FD18C02000000E036D49088FFFFFFF0BB988F88FFFFFF30E8B18C88FFFFFF74D4C698889FC58FB40AE2980109000030E8B18C88FFFFFFF0BB988F88FFFFFFE036D49088FFFFFF405FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFFC0647D8F85FFFFFFD0EDB18C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFA0E5468D88FFFFFFD03F858E88FFFFFF403FD7900100000090000000703C858E7CD4C6986CD4C698B027B4940000000004000000C4D6C69860A1818C00040000
09-08 21:14:16.257  4273  3865 W google-breakpad: S 98C6D480 6036D49001000000E036D49088FFFFFFF0BB988F88FFFFFF0000000082FFFFFF982DB494F0BB988F403C858E103C858E0000000087FFFFFFA00FD390E03B858E103C858EC0E4468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFFE03B858E88FFFFFF28D5C698E03B858E803B858EB03B858E9CF1379180020000E036D49000000000803B858E88FFFFFF70CEFE8D8A0000000700000080CEFE8D80EFD19F40B0D2905011A28EE036D4902018EA9803020000403FD7900100000040B0D29088FFFFFF5011A28E85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B600D7C6980100000081FFFFFF58D6C698C4D6C698646B4C94403FD790000000000000000028D6C698DCD5C6983817EA9858DBAA9480EFD19F002B419144E7C698000000000000000000000000010000002CDEC69880EFD19F
09-08 21:14:16.257  4273  3865 W google-breakpad: S 98C6D600 000100000000000050F0379100000000403FD790B8DAC698020000000100000000000000000000000100000081FFFFFF000000000000000090DAC698F6FFFFFF8CEFD19F0100000080EFD19F58D6C69800000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000000D7C69880EFD19F203EB4940052DB9000000000D86DD78BC4D6C698407067DB0000000080EFD19F00D7C698C8D6C698403FD7900052DB9000000000D86DD78BECD6C6987C0C6A94000000000000000000000000C0FED4B60100000080EFD19FC0DAC698F8D6C69874DAC698740D6A9452EC129DFBED129DC0DAC69801000000780BAA94010000000052DB90F8D6C6980000000000EE129D0200000002000000010000000000000010B9A9945C000000060000000000000030E6C6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.257  4273  3865 W google-breakpad: S 98C6D780 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E4129D0000000000000000010000000200000020E4468D0053DB906564D29F0000000000000000407067DB00000000C0FED4B60000000080EFD19F18625C9490D8C6980CDCC698F80D6A940000000000000000B0DCC698000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.257  4273  3865 W google-breakpad: S 98C6D900 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DBC0FED4B6B0DAC69880EFD19F60DBC698C0DAC698D86DD78B1CDBC69834126A940000000000000000
09-08 21:14:16.257  4273  3865 W google-breakpad: S 98C6DA80 0000000040B0D290C0DAC69801000000A0E7C698F6FFFFFF8CEFD19F0000000080EFD19FB0DAC6980300000008000000403FD79088FFFFFF40B0D29088FFFFFF5011A28E85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DB0000000080EFD19F70DBC69860DBC69868DBC6985CDBC69882FFFFFFD06DD78B4CDBC69888FC5994D06DD78B68DBC69840B0D29088FFFFFFD0DBC698E0DBC698C0DCC6980100000078DBC69800000000ACDBC69850927B9468DBC698000000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000D06DD78B0000000082FFFFFF80EFD19F0000000074069594E0DBC698D0DBC69880AD949E18B0949E80EFD19FC0DCC698740695941CDCC69808A27294E0DBC69834DCC698070000004F000000CC73698C7CC44B8C0000000070C44B8C40B0D29088FFFFFF80EFD19F000000005011A28E85FFFFFF80EFD19F0000000030DCC698205F96949DC44B8C50DCC698
09-08 21:14:16.258  4273  3865 W google-breakpad: S 98C6DC00 C0DCC69840DCC69880EFD19F34DCC6982200000080AD949E84DCC6983C127494ECC7949458CB949458DBAA94220000007CC44B8C2448408C0000000054DCC6982200000000000000D8DDC698000000006CDCC69864DC319408DDC698D8DDC698C0C3AB94D0DCC6980000000001000000C0DCC698B0DCC6982200000080EFD19F14DEC698783B7794C06DD78BFFFFFFFF8C13D48EFFFFFFFFC006288EE8DCC6983813848D08DDC6984C0E788DFFFFFFFF0000000082FFFFFF000000000001000022000000000000000000000000000000005ADDB480EFD19F0100000038DEC69848DEC69801000000C06DD78B070000000700000001000000E05FA58E0000000080EFD19F000000000000000006000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000C86DD78B22000000E85FA58E0700000000000000010000001800E090503DCE900100000074DDC6983052649407000000E05FA58E80EFD19F000000001000E09080DDC698B4DDC69838946494F482D5B6BBF4D1B6
09-08 21:14:16.258  4273  3865 W google-breakpad: S 98C6DD80 7404A08CDCC43791E8DDC69801000000A00E788C503B858EE01BE190E05FA58E00000000FFFFFFFF503DCE900100000050DEC69880C53791A8DEC698C4DDC69810DEC698000000000000000048C537914003000001000000FFFFFFFF81FFFFFFE05FA58E85FFFFFF1000E09085FFFFFFA453DDB44049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE900100000050DEC69838DFEA980000000024DEC6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFFE05FA58E85FFFFFFACDEC698C03DCE909002FE9001050000E05FA58E85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290F0D9E19085FFFFFFDCDEC698F4DEC69800000000D0DEC6988CE9EA98820100006086D690010000000000000082FFFFFFE05FA58E85FFFFFF7CDFC698C015A390A425FD90010A0000E05FA58E85FFFFFF0000000082FFFFFF6086D69088FFFFFF0000000082FFFFFF
09-08 21:14:16.258  4273  3865 W google-breakpad: S 98C6DF00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007E09085FFFFFFF0D9E19085FFFFFF82FFFFFF001BB494F0FBE190BC8F5A89A000000030BDD2900000000083FFFFFF003A858E0302000000000000A8DFC6988CE9EA9802020000A04CD69002000000A0C6D59088FFFFFFE05FA58E85FFFFFFA0E4468D88FFFFFF1CE0C69880E1578DCCD05A8981060000F0D9E19085FFFFFFE05FA58E85FFFFFFA0C6D59088FFFFFFA04CD69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000000E0C6980000000083FFFFFF68000000A05CD78CE85FA58E0100000030000000A05CD78C0000000040E0C6988CE9EA9882010000203E468D010000000000000082FFFFFFE05FA58E85FFFFFFC4E0C6987048C28C04C95A8981070000E05FA58E85FFFFFF0000000082FFFFFF203E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-08 21:14:16.258  4273  3865 W google-breakpad: S 98C6E080 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE0E0C698D8E0C698D0E0C69844E1C69878000000A05CD78C0000000016AE488F58DBAA9480EFD19F00000000E8E0C6988CE9EA9882010000603E468D010000000000000082FFFFFFE05FA58E85FFFFFF54E1C69898A1AF8CE4BE5A8901060000E05FA58E85FFFFFF0000000082FFFFFF603E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000060E1C69878E1C6980400000060000000A05CD78CE02D898C01000000E4E1C698F89FEA980000000078E1C6988CE9EA9882010000803E468D010000000000000082FFFFFFE05FA58E85FFFFFFE4E1C6989829A78CF0B55A8901060000E05FA58E85FFFFFF0000000082FFFFFF803E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F03A858E00000000C8E8888E60000000203B858E04000000003A858EF4E1C698C8AB46940400000008E2C6988CE9EA9882010000A03E468D010000000000000082FFFFFF
09-08 21:14:16.259  4273  3865 W google-breakpad: S 98C6E200 F03A858E88FFFFFF84E2C698902C898CFCAC5A8901070000F03A858E88FFFFFF0000000082FFFFFFA03E468D88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013E19085FFFFFFE05FA58E85FFFFFF0000000078E2C69874E2C69888FFFFFF70000000C03A858E90E7B18CD4885994000000000000000004000000A8E2C6988CE9EA9882010000203F468D01000000F0DA328E88FFFFFF3037858E88FFFFFF04E3C6986021898C68A65A89010500003037858E88FFFFFFF0DA328E88FFFFFF203F468D88FFFFFFC0D3E19085FFFFFF90E7B18C0100000034E3C6984CE3C69850000000701F6E8D0302000070CFA38F24E3C69818AB46940000000038E3C6980CB58C8F82020000E05ED18C030000000000000082FFFFFF3037858E88FFFFFF0000000081FFFFFF90E7B18C88FFFFFFD4E3C698D00C3E8D0081858C0109000090E7B18C88FFFFFF0000000081FFFFFF3037858E88FFFFFF0000000082FFFFFFE05ED18C88FFFFFF0900000084FFFFFF0000000082FFFFFF
09-08 21:14:16.259  4273  3865 W google-breakpad: S 98C6E380 0000000081FFFFFF6076B98F88FFFFFF0000000082FFFFFF0900000081FFFFFF90E7B18C88FFFFFFE0E7B18C0000000004E4C698C0D6D2909000000020C0D290003A858E0302000070B6748C0100000000000000F8E3C6988CE9EA9882010000B002D3900100000090E7B18C88FFFFFFE05ED18C88FFFFFF7CE4C69828BD748C38A05A8981070000E05ED18C88FFFFFF90E7B18C88FFFFFFB002D39088FFFFFFE0E7B18C88FFFFFFC0D6D29088FFFFFFC0D0D29088FFFFFF0000000082FFFFFFE0E7B18C88FFFFFF0000000082FFFFFFA0E4C69838DFEA980000000064E4C69878000000701F6E8D00000000EC965A89420300000300000000000000A8E4C6988CE9EA9802020000005FD18C02000000C014138F88FFFFFFA0BB988F88FFFFFF90E7B18C88FFFFFF14E5C69878B0748CB89B5A890106000090E7B18C88FFFFFFA0BB988F88FFFFFFC014138F88FFFFFF005FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFFCC01EB985CE5C69860E5C6983011A28E60000000701F6E8D
09-08 21:14:16.259  4273  3865 W google-breakpad: S 98C6E500 48E5C6983011A28E003A858E030200000000000040E5C6988CE9EA9802020000405FD18C02000000E036D49088FFFFFFA0BB988F88FFFFFF50E1B18C88FFFFFFDCE5C698889FC58FB40AE2980109000050E1B18C88FFFFFFA0BB988F88FFFFFFE036D49088FFFFFF405FD18C88FFFFFF0000000082FFFFFF0000000082FFFFFF3011A28E85FFFFFF40E7B18C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF40E4468D88FFFFFF003A858E88FFFFFF403FD79001000000900000000037858EE4E5C698D4E5C698B027B49400000000040000002CE8C69860A1818C000400006036D49001000000E036D49088FFFFFFA0BB988F88FFFFFF0000000082FFFFFF982DB494A0BB988FD036858E7036858E0000000087FFFFFFA00FD3904036858E7036858E20E4468D90028C8980020000A036D490020000000000000082FFFFFFA00FD39088FFFFFF4036858E88FFFFFF90E6C6984036858EE035858E1036858E9CF1379180020000E036D49000000000E035858E88FFFFFF
09-08 21:14:16.259  4273  3865 W google-breakpad: S 98C6E680 40BCF08C8A0000000700000050BCF08C80EFD19F40B0D29060CEFE8DE036D4902018EA9803020000403FD7900100000040B0D29088FFFFFF60CEFE8D85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080EFD19FC0FED4B668E8C6980100000081FFFFFFC0E7C6982CE8C698646B4C94403FD790000000000000000090E7C69844E7C6983817EA9858DBAA9480EFD19F002B4191ACF8C6980000000000000000000000000100000094EFC69880EFD19F000100000000000050F0379100000000403FD79020ECC698020000000100000000000000000000000100000081FFFFFF0000000000000000F8EBC698F6FFFFFF8CEFD19F0100000080EFD19FC0E7C69800000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000068E8C69880EFD19F203EB4940052DB9000000000B86DD78B
09-08 21:14:16.259  4273  3865 W google-breakpad: S 98C6E800 2CE8C698407067DB0000000080EFD19F68E8C69830E8C698403FD7900052DB9000000000B86DD78B54E8C6987C0C6A94000000000000000000000000C0FED4B60100000080EFD19F28ECC69860E8C698DCEBC698740D6A9452EC129DFBED129D28ECC69801000000780BAA94010000000052DB9060E8C6980000000000EE129D0200000002000000010000000000000010B9A9945C000000060000000000000098F7C69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.260  4273  3865 W google-breakpad: S 98C6E980 00000000000000000000000000000000000000000000000000000000000000000000000000E4129D0000000000000000010000000200000080E3468D0053DB906564D29F0000000000000000407067DB00000000C0FED4B60000000080EFD19F18625C94F8E9C69874EDC698F80D6A94000000000000000018EEC6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.260  4273  3865 W google-breakpad: S 98C6EB00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DBC0FED4B618ECC69880EFD19FC8ECC69828ECC698B86DD78B84ECC69834126A9400000000000000000000000040B0D29028ECC6980100000008F9C698F6FFFFFF8CEFD19F0000000080EFD19F18ECC6980300000008000000403FD79088FFFFFF40B0D29088FFFFFF60CEFE8D85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000407067DB0000000080EFD19FD8ECC698C8ECC698D0ECC698C4ECC69882FFFFFFB06DD78B
09-08 21:14:16.260  4273  3865 W google-breakpad: S 98C6EC80 B4ECC69888FC5994B06DD78BD0ECC69840B0D29088FFFFFF38EDC69848EDC69828EEC69801000000E0ECC6980000000014EDC69850927B94D0ECC698000000001800000040B0D290403FD79088FFFFFF0000000082FFFFFF01000000B06DD78B0000000082FFFFFF80EFD19F000000007406959448EDC69838EDC69880AD949E18B0949E80EFD19F28EEC6987406959484EDC69808A2729448EDC6989CEDC698070000004F000000CC73698C2CC44B8C0000000020C44B8C40B0D29088FFFFFF80EFD19F0000000060CEFE8D85FFFFFF80EFD19F0000000098EDC698205F96944DC44B8CB8EDC69828EEC698A8EDC69880EFD19F9CEDC6982200000080AD949EECEDC6983C127494ECC7949458CB949458DBAA94220000002CC44B8CF447408C00000000BCEDC698220000000000000040EFC69800000000D4EDC69864DC319470EEC69840EFC698C0C3AB9438EEC698000000000100000028EEC69818EEC6982200000080EFD19F7CEFC698783B7794506DD78B0000000080EFD19F08EEC698
09-08 21:14:16.260  4273  3865 W google-breakpad: S 98C6EE00 0200000050EEC69850BB988F70EEC6983031858E88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080EFD19F01000000A0EFC698B0EFC69801000000506DD78B07000000070000000100000000CDFE8D0000000080EFD19F000000000000000006000000E4C3AB94E4C3AB9406000000C0C3AB9400000000FFFFFFFF00000000A86DD78B2200000008CDFE8D0700000000000000010000001800E090503DCE9001000000DCEEC698305264940700000000CDFE8D80EFD19F000000001000E090E8EEC6981CEFC69838946494F482D5B6BBF4D1B67404A08CDCC4379150EFC69801000000E412448CB035858EE01BE19000CDFE8D00000000FFFFFFFF503DCE9001000000B8EFC69880C5379110F0C6982CEFC69878EFC698000000000000000048C537914003000001000000FFFFFFFF81FFFFFF00CDFE8D85FFFFFF1000E09085FFFFFFA453DDB44049D69088FFFFFF9002FE9000000000FFFFFFFFC03DCE9001000000B8EFC69838DFEA98
09-08 21:14:16.260  4273  3865 W google-breakpad: S 98C6EF80 000000008CEFC6988CE9EA9800000000000000009002FE9042020000010000004049D69088FFFFFF00EAD29088FFFFFF00CDFE8D85FFFFFF14F0C698C03DCE909002FE900105000000CDFE8D85FFFFFF00EAD29088FFFFFF4049D69088FFFFFF0000000082FFFFFF00000000E80C128C40020000000000005000000030BDD290
09-08 21:14:16.261  4273  3865 W google-breakpad: C 0600004000908B96000000003C73C698B873C6981073C6986473C69880EFD19F3C73C6981082B28C85FFFFFF80AD949E3473C698F872C6980073C698C8D05994CCD0599410000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-08 21:14:16.261  4273  3865 W google-breakpad: M B6FA8000 00000000 00005000 E72F8FF84F6E260968CCE78B856F06B70 app_process32
09-08 21:14:16.261  4273  3865 W google-breakpad: M 94055000 00000000 00A66000 886ECA16DD42F6E0428F775A7DA9BFB00 libjxcore.so
09-08 21:14:16.261  4273  3865 W google-breakpad: M A25BE000 007F2000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
09-08 21:14:16.261  4273  3865 W google-breakpad: M A89BE000 00000000 00006000 0D31362517BA6979AC917A35D240E1210 libwebviewchromium_loader.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A62000 00000000 00005000 590854A6A5B5D59683870D00EAE455310 libjnigraphics.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A67000 00000000 0000A000 4AE1FB560051D628B937E5D0F75C69F30 libcompiler_rt.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A71000 00000000 00011000 4CBE9A6CCCBDC8B3EF8B751BC123CEE50 libandroid.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A82000 00000000 0000C000 AFC34749768B41E8D431AF946E23577B0 libqservice.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A8E000 00000000 0000B000 356C1D2029892384AFE121956A0BB4EA0 libqdutils.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A99000 00000000 00005000 95E7634C1A490462E66752EC8939C4530 libqdMetaData.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8A9E000 00000000 00008000 9997EA703403C3035DE00C7EE7880E430 libmemalloc.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8AA6000 00000000 00008000 3FE99556F2945012B0CB1BE7C353A6540 gralloc.msm8084.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8AAE000 00000000 0000C000 A1BCE730F0644DAE1C5CBC146CD02BD90 eglSubDriverAndroid.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8ABA000 00000000 00027000 2A6DCFEF23E3A32055F90972FCABFED60 libGLESv1_CM_adreno.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A8AE1000 00000000 0073D000 2003920CF0749EC2675D7EE282DE502B0 libllvm-glnext.so
09-08 21:14:16.262  4273  3865 W google-breakpad: M A922F000 00000000 004AD000 3082CAE2C0BC6E87686AEAA07100FEDE0 libGLESv2_adreno.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M A96DE000 00000000 0003D000 44E63552D97113055F6017F152FAF0340 libgsl.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M A971B000 00000000 00007000 417C9A0548EF994318FDD8293BD2B4A90 libadreno_utils.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M A9724000 00000000 00013000 B4DF6A0A447291C436FE548566C498C00 libEGL_adreno.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB1AF000 00000000 0001B000 B0EFA02804790BBB6DE8B2B9095BE9CB0 libkeymaster1.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB1CA000 00000000 0000B000 D13E1014D51DECF5BF9D21E7C67666130 libkeymaster_messages.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB1D5000 00000000 00017000 6658C7A49E3552941CE5496BFD2B34980 libsoftkeymasterdevice.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB1EC000 00000000 0000E000 25D7B988B89B18BC0429BB562FA2DE990 libkeystore_binder.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB1FA000 00000000 00006000 B33B16D8A7ED9B8FFB7AA215D6923C4B0 libkeystore-engine.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB243000 00000000 00018000 CEF05C42255586B6905B0AF681C33D8C0 libjavacrypto.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB25B000 00000000 00010000 0C521B6A6E9E39A0E22193BB5D5525130 libstagefright_amrnb_common.so
09-08 21:14:16.263  4273  3865 W google-breakpad: M AB26B000 00000000 0002C000 582DF60B6AA35307BD7198E3A18119AB0 libexif.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M AB297000 00000000 0000D000 7CD678568D893C8FE9A4676BCD58F2AD0 libjhead.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M AB2A5000 00000000 00018000 ADA21AF62918F8A878B3FE4F2F0456580 libmtp.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M AB2BD000 00000000 00048000 0262207412DD5679BF20EB25407B7B440 libmedia_jni.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B070A000 00000000 00036000 E15D31AAB91199642EB180D3D4160C520 libjavacore.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B0780000 00000000 00006000 B37EB6398BB0DBE353FE8B1F1DEAB2EB0 memtrack.msm8084.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B36EC000 00000000 00007000 79903F128710C73A4159E0E685663A550 libwebviewchromium_plat_support.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B48A5000 00000000 00459000 D1BC38C6D191DBFC4B3B8BE9676A2FBB0 libart.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B4E24000 00000000 00005000 68126D6F94C506C8BE6DAA402968ABD50 libsigchain.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B4E4C000 00000000 00A5C000 0B64AEBAA12EA3FC8CB4E80A5310D9A20 libLLVM.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B58B1000 00000000 00038000 EB0128750F7A47E1274CC11D426A63840 libbcinfo.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B58E9000 00000000 0005B000 8D9A857B04F62EBCFEC94FC226C49F600 libbcc.so
09-08 21:14:16.264  4273  3865 W google-breakpad: M B5944000 00000000 0000E000 BD9845C69DC7ADC5D6D7E1756D34DD830 libcommon_time_client.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5953000 00000000 0001A000 9AC4BF2FD171753488B9C5DB621A9A240 libprotobuf-cpp-lite.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B596D000 00000000 00009000 9B164CEF29D3AA5EAF47FA86862586FF0 libstagefright_avc_common.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5976000 00000000 00005000 4AA290A61993A8A5677655D665763B3D0 libstagefright_enc_common.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B597B000 00000000 00007000 5146A8AEEE822B0CE87F523ABAE749F50 libpowermanager.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5982000 00000000 0001F000 EF15E47D9893659F6C584D4542F099490 libvorbisidec.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B59A1000 00000000 00007000 9C90BE63E61A2127D39B214E6F43AF350 libstagefright_yuv.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B59A9000 00000000 00032000 C3AC584E1FF634156E2797138D35375E0 libstagefright_omx.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B59DB000 00000000 0003D000 B85FA71D8415B28DE38A933B1508D9F00 libopus.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5A18000 00000000 0000A000 5BEFFA75C748ED7D23421EF091D1F1300 libmediautils.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5A22000 00000000 0001A000 64DF194390054DFAFF82926D89B359340 libdrmframework.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5A3C000 00000000 00021000 A395A730CEF4C5A1BB47058DE0D9186E0 libRScpp.so
09-08 21:14:16.265  4273  3865 W google-breakpad: M B5A5D000 00000000 00042000 70A461E7FEC54E6D7E1E5C66F936CE350 libRS.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5A9F000 00000000 00009000 FDC63F080EB6155F934F885DEB37E94E0 libspeexresampler.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5AA8000 00000000 0000B000 FFD2B97AE5B754AC2E9678225D23B75A0 libnbaio.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5AB3000 00000000 00014000 669F5236C39ADF5E46701FF6C9F768980 libpcre.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5AC9000 00000000 00007000 21F0774A2FE026AA52F7480655D27ABE0 libwpa_client.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5AD0000 00000000 00071000 C8703400FE46F435C2134FB0F3FDE9390 libGLES_trace.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5B41000 00000000 00067000 1821F1842FA60DF842F94DF364C495A10 libft2.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5BA8000 00000000 00027000 C5A689AFC30DE04B5E7E5ACBF12CA9330 libpng.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5BCF000 00000000 00005000 E0AD90DEBEAFB376EBAA5415267856B40 libsync.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5BD4000 00000000 00007000 F5424CDA56569E38CF2903ECFAFF296E0 libstdc++.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5BDB000 00000000 00012000 B4E430E8258C544A786360668D84BE8B0 libunwind.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5C33000 00000000 0000B000 96BB8488669F21FEDA8649403EB8BB0E0 libbase.so
09-08 21:14:16.266  4273  3865 W google-breakpad: M B5C3E000 00000000 00007000 D32E249CC58B3A22906A78EDFDD545460 libeffects.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5C46000 00000000 00006000 1964BC7CB1EF496E207C18FC55A57E6C0 libstagefright_http_support.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5C4C000 00000000 0001B000 4E010519E1AA1D9D10F586E0C0490F120 libstagefright_foundation.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5C67000 00000000 0015B000 009817DD6F2FD8255E5AAE0FDE05646B0 libstagefright.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5DC2000 00000000 00070000 4054B4690025F8746C0DC28CC9D69D870 libhwui.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E32000 00000000 00005000 9CA9EF8816A2E0C106C15197423A91AE0 libradio_metadata.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E37000 00000000 00006000 F1863EB76C05E59645A8AA848D1624570 libnativebridge.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E3D000 00000000 00006000 1D210F6A59079D7FD7F258724A88DEA70 libprocessgroup.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E43000 00000000 00011000 FDCAD8835C0C336BEB30CF765069FC3A0 libminikin.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E54000 00000000 0000E000 238BED0ADF305646BB994A7A676D0A1E0 libsoundtrigger.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E63000 00000000 0000E000 00FDCB77534A86A2594207ABA92E7FBF0 libradio.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E71000 00000000 00006000 BBCF64A69A9F42E7BC0E0BD423E728790 libnetd_client.so
09-08 21:14:16.267  4273  3865 W google-breakpad: M B5E77000 00000000 00010000 727E80AEB01F5239858F79470BB43E850 libimg_utils.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B5E87000 00000000 00420000 2D9D72FD541F8A7DFBF9302532B5F3870 libpdfium.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B62A8000 00000000 00009000 25B29975558839100CC6E366D29212350 libaudioutils.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B62B1000 00000000 0001D000 DFED0D6F37875A07335517F4E69925120 libz.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B62CF000 00000000 0004E000 66D92DD691765147492F9C21B6AD68960 libharfbuzz_ng.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B631D000 00000000 00007000 9008C23BFACF1EF1DDF142956BF976490 libusbhost.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B6324000 00000000 0003A000 2D00674AA1DD3C58C05B175DD18EE6050 libjpeg.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B635F000 00000000 000AD000 A52E62FD0AC67AE14A01E7E4847F17620 libmedia.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B640C000 00000000 0017F000 14D5DC468D2218AA5F70C2F6FC6EBBF90 libicui18n.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B658B000 00000000 00123000 0990D8BD31465D945F9282189239AB8F0 libicuuc.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B66B2000 00000000 00026000 C4AA0ABF6C41A8583C0E373BD8CA4EE70 libssl.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B66D8000 00000000 0009D000 A14F571CD9F3F8B6362ACC34BB5E42CA0 libcrypto.so
09-08 21:14:16.268  4273  3865 W google-breakpad: M B6775000 00000000 00056000 23B95E0161A14BC00A49FE4C0126E1CF0 libsonivox.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B67D0000 00000000 00011000 87F28481D7D1980E2971DFAD611952AA0 libselinux.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B67E1000 00000000 00008000 4E213F2F80F006F539A0A0DBEC2228870 libhardware_legacy.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B67EA000 00000000 00005000 4025C8440BDADD37826842A415EF9BFF0 libhardware.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B67EF000 00000000 00006000 0CBDCDD7DFB535EB3876F8035637EAC00 libETC1.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B67F5000 00000000 0000F000 A7B07D10AF426644931390FF2ABC2FEC0 libGLESv2.so
09-08 21:14:16.269  4273  3865 W goog,le-breakpad: M B6804000 00000000 0000A000 1B33374FB686F15B59530546D8DB39640 libGLESv1_CM.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B680E000 00000000 00068000 DAD11DC7527BFB7648299C3DE956986E0 libEGL.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B6879000 00000000 00065000 E94A253EBAA34A7F995352FCEE8DD0D50 libsqlite.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B68DF000 00000000 0026E000 71785D4C7316B73D74AB9E39653907830 libskia.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B6B51000 00000000 0000A000 306A2E96AB94641A8076D9195DA933FF0 libcamera_metadata.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B6B5B000 00000000 0002D000 7CA8B61C54BAAABF07F3C7847D490E9F0 libcamera_client.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B6B88000 00000000 00040000 6C63D1A1ED4626296733EE132307BF6E0 libinputflinger.so
09-08 21:14:16.269  4273  3865 W google-breakpad: M B6BC8000 00000000 0001F000 112B3314840A32B638874B51553126190 libinput.so
,09-08 21:14:16.269  4273  3865 W google-breakpad: M B6BE7000 00000000 0005A000 D55348C7DD771E9409BFBF09AB5AAD720 libgui.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6C41000 00000000 00010000 10F3AFD84F2FA6D8D59A78E2331D8AC50 libui.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6C51000 00000000 00009000 8AAEFDEA9747BCF61A977E5DDA0D22620 libnetutils.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6C5A000 00000000 00009000 6C034766ACADC7459DB1EE108B8DDDC70 libnativehelper.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6C63000 00000000 00017000 410352CE283FD8305E8A2FD783B3C8160 libexpat.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6C7A000 00000000 0002A000 41777DBC877E41A9712DDD4792610E7A0 libandroidfw.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6CA4000 00000000 00005000 EC03C38C8A2A3C11A25493EEEE8E58C20 libmemtrack.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6CA9000 00000000 0000B000 6AC6874E2835174DF0B2E6A2BB3511ED0 libbacktrace.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6CB4000 00000000 00022000 771243F4B38A04911D7E2EFFC103E81F0 libm.so
,09-08 21:14:16.270  4273  3865 W google-breakpad: M B6CD6000 00000000 00079000 C45DDC3AA3778947F27583335C11C7260 libc.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6D59000 00000000 0008E000 4F01D021AD7772AE25722B88EF500DF60 libc++.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6DE8000 00000000 0002D000 C02C38CB58D679FECB52E59A954B4AAD0 libwilhelm.so
09-08 21:14:16.270  4273  3865 W google-breakpad: M B6E15000 00000000 000DC000 ACD6E6927F2247CE8E5F68E6F5579F0E0 libandroid_runtime.so
09-08 21:14:16.271  4273  3865 W google-breakpad: M B6EF6000 00000000 0002E000 1E5AD4B0BC139C0D5814F52EEC059E2E0 libbinder.so
09-08 21:14:16.271  4273  3865 W google-breakpad: M B6F24000 00000000 0000A000 F2FDFCED2E85559AC020655D564D0FFC0 liblog.so
09-08 21:14:16.271  4273  3865 W google-breakpad: M B6F2E000 00000000 0001B000 4E3DF0460B95A69E7A1D4ABE2D8C0A690 libutils.so
09-08 21:14:16.271  4273  3865 W google-breakpad: M B6F49000 00000000 00011000 78F0BD9C3BF5DE7183A84BD26875408C0 libcutils.so
09-08 21:14:16.271  4273  3865 W google-breakpad: M B6F86000 00000000 00020000 C98C597B4AE800CFB3F0589DF3EDED980 linker
09-08 21:14:16.271  4273  3865 W google-breakpad: -----END BREAKPAD MICRODUMP-----
09-08 21:14:16.295  3814  3865 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-08 21:14:16.295  3814  3865 W google-breakpad: Chrome build fingerprint:
09-08 21:14:16.295  3814  3865 W google-breakpad: 0.0.1
09-08 21:14:16.295  3814  3865 W google-breakpad: 19
09-08 21:14:16.295  3814  3865 W google-breakpad: 6ec9b36e-71c4-4d7b-882c-6b145c858100
09-08 21:14:16.295  3814  3865 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
,09-08 21:14:16.295  3814  3865 E chromium: ### WebView Version 44.0.2403.117 (code 246011700)
--------- beginning of crash
09-08 21:14:16.296  3814  3865 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 3865 (Thread-330)
,09-08 21:14:16.407   372   372 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,09-08 21:14:16.407   372   372 F DEBUG   : Build fingerprint: 'google/shamu/shamu:6.0.1/MOB30M/2862625:user/release-keys'
09-08 21:14:16.408   372   372 F DEBUG   : Revision: '0'
09-08 21:14:16.408   372   372 F DEBUG   : ABI: 'arm'
09-08 21:14:16.409   372   372 F DEBUG   : pid: 3814, tid: 3865, name: Thread-330  >>> com.test.thalitest <<<
,09-08 21:14:16.410   372   372 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4,
,09-08 21:14:16.448   372   372 F DEBUG   :     r0 968b9000  r1 00000000  r2 98c6733c  r3 98c673b8,
09-08 21:14:16.448   372   372 F DEBUG   :     r4 98c67310  r5 98c67364  r6 9fd1ef80  r7 98c6733c
09-08 21:14:16.448   372   372 F DEBUG   :     r8 8cb28210  r9 ffffff85  sl 9e94ad80  fp 98c67334
09-08 21:14:16.448   372   372 F DEBUG   :     ip 98c672f8  sp 98c67300  lr 9459d0c8  pc 9459d0cc  cpsr 200f0010
,09-08 21:14:16.454   372   372 F DEBUG   : 
09-08 21:14:16.454   372   372 F DEBUG   : backtrace:
,09-08 21:14:16.454   372   372 F DEBUG   :     #00 pc 005480cc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
09-08 21:14:16.454   372   372 F DEBUG   :     #01 pc 0054856c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
09-08 21:14:16.455   372   372 F DEBUG   :     #02 pc 00762e84  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,09-08 21:14:16.815   874  1318 D ConnectivityService: handlePromptUnvalidated 102
,09-08 21:14:17.254   372   372 F DEBUG   : ,
09-08 21:14:17.254   372   372 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_03
,09-08 21:14:17.254   372   372 E DEBUG   : AM write failed: Broken pipe
,09-08 21:14:17.255   874   890 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,09-08 21:14:17.278   874  4274 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-08 21:14:17.280   278   278 E lowmemorykiller: Error writing /proc/3814/oom_score_adj; errno=22
,09-08 21:14:17.391   874   884 I WindowState: WIN DEATH: Window{ea19b0c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 21:14:17.395   874  1317 D WifiService: Client connection lost with reason: 4
,09-08 21:14:17.401   874  2074 D GraphicsStats: Buffer count: 2
,09-08 21:14:17.424   388   388 I Zygote  : Process 3814 exited due to signal (11)
,09-08 21:14:17.426   874  1392 I ActivityManager: Process com.test.thalitest (pid 3814) has died
,09-08 21:14:17.488   874  2072 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3814 uid 10000
,09-08 21:14:17.491  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-08 21:14:32.535  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:32.542  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:32.548  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:32.601  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 21:14:32.601  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 21:14:32.602  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:14:32.602  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:32.632  3555  3555 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 21:14:32.632  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 21:14:32.632  3555  3555 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 21:14:38.358   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:14:39.535  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:39.543  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:14:39.586  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 21:14:39.586  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:14:39.586  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:14:39.586  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:39.614  3023  4278 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 21:14:39.614  3023  4278 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at blb.a(PG:3937)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at czp.a(PG:18188)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:14:39.614  3023  4278 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	... 12 more
09-08 21:14:39.614  3023  4278 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at fal.a(PG:38)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:14:39.614  3023  4278 E HttpOperation: 	... 14 more
,09-08 21:14:39.664  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 21:14:39.664  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:14:39.665  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:14:39.665  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:39.708  3023  4278 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 21:14:39.708  3023  4278 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at hec.a(PG:42)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at hee.a(PG:102)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at czr.a(PG:65)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at kka.a(PG:108)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at czp.a(PG:19176)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:14:39.708  3023  4278 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	... 15 more
09-08 21:14:39.708  3023  4278 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at fal.a(PG:38)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:14:39.708  3023  4278 E HttpOperation: 	... 17 more
,09-08 21:14:39.708  3023  4278 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 21:14:39.708  3023  4278 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at hec.a(PG:42)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at hee.a(PG:102)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at czr.a(PG:65)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at kka.a(PG:108)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	... 15 more
09-08 21:14:39.708  3023  4278 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at fal.a(PG:38)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 21:14:39.708  3023  4278 E ExperimentLoader: 	... 17 more
,09-08 21:14:39.918   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 178667, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:14:39.942  3766  4280 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 21:14:39.959  3766  4281 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 21:14:39.995  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:14:39.995  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:14:39.995  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:14:39.995  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:40.059  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:14:40.060  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:14:40.060  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:14:40.060  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:14:40.074  3766  4281 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 21:14:40.075  3766  4280 E BooksSync: Soft error
09-08 21:14:40.075  3766  4280 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:14:40.075  3766  4280 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 21:14:40.075  3766  4280 E BooksSync: Sync error
09-08 21:14:40.075  3766  4280 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:14:40.075  3766  4280 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 21:14:40.075  3766  4280 I BooksSync: Finished books sync
,09-08 21:14:40.082   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194091, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:15:09.581  1509  2232 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 21:15:10.513  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:10.518  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:10.573  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:15:10.573  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:15:10.573  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:15:10.574  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:15:10.599  3023  4284 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 21:15:10.599  3023  4284 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at blb.a(PG:3937)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at czp.a(PG:18188)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:15:10.599  3023  4284 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	... 12 more
09-08 21:15:10.599  3023  4284 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at fal.a(PG:38)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:15:10.599  3023  4284 E HttpOperation: 	... 14 more
,09-08 21:15:10.653  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:15:10.653  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:15:10.654  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:15:10.654  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:15:10.667  3023  4284 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 21:15:10.667  3023  4284 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at hec.a(PG:42)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at hee.a(PG:102)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at czr.a(PG:65)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at kka.a(PG:108)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at czp.a(PG:19176)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:15:10.667  3023  4284 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	... 15 more
09-08 21:15:10.667  3023  4284 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at fal.a(PG:38)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:15:10.667  3023  4284 E HttpOperation: 	... 17 more
,09-08 21:15:10.668  3023  4284 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 21:15:10.668  3023  4284 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at hec.a(PG:42)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at hee.a(PG:102)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at czr.a(PG:65)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at kka.a(PG:108)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	... 15 more
09-08 21:15:10.668  3023  4284 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at fal.a(PG:38)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 21:15:10.668  3023  4284 E ExperimentLoader: 	... 17 more
,09-08 21:15:10.831   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 224571, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:15:17.532  1904  1964 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-08 21:15:17.533  1904  1964 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 21:15:17.567  1509  1509 I ConfigService: onCreate
,09-08 21:15:22.637  1509  1509 I ConfigService: onDestroy
,09-08 21:15:41.058  3766  4288 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 21:15:41.103  3766  4289 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 21:15:41.136  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:41.139  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:41.170  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 21:15:41.170  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 21:15:41.171  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:15:41.171  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:15:41.220  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:41.224  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:15:41.272  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:15:41.273  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:15:41.273  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:15:41.273  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:15:41.311  3766  4289 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 21:15:41.313  3766  4288 E BooksSync: Soft error
09-08 21:15:41.313  3766  4288 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:15:41.313  3766  4288 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 21:15:41.313  3766  4288 E BooksSync: Sync error
09-08 21:15:41.313  3766  4288 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:15:41.313  3766  4288 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 21:15:41.314  3766  4288 I BooksSync: Finished books sync
,09-08 21:15:41.328   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 255409, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:15:54.611   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=269104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:16:11.587  3065  4291 V KeepSync: Connecting to GoogleApiClient
,09-08 21:16:11.588   874  1712 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 21:16:11.686  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:16:11.688  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:16:11.727  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 21:16:11.727  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 21:16:11.727  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:16:11.727  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:11.746  1723  4294 V BaseAuthAsyncOperation: access token request failed
,09-08 21:16:11.747  3065  4291 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 21:16:11.789  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:16:11.789  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 21:16:11.790  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:16:11.790  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:11.825  3023  4293 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 21:16:11.825  3023  4293 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at blb.a(PG:3937)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at czp.a(PG:18188)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:16:11.825  3023  4293 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	... 12 more
09-08 21:16:11.825  3023  4293 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at fal.a(PG:38)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:16:11.825  3023  4293 E HttpOperation: 	... 14 more
,09-08 21:16:11.913  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:16:11.913  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 21:16:11.913  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:16:11.914  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:11.934  3023  4293 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 21:16:11.934  3023  4293 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at hec.a(PG:42)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at hee.a(PG:102)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at czr.a(PG:65)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at kka.a(PG:108)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at czp.a(PG:19176)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:16:11.934  3023  4293 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	... 15 more
09-08 21:16:11.934  3023  4293 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at fal.a(PG:38)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:16:11.934  3023  4293 E HttpOperation: 	... 17 more
,09-08 21:16:11.934  3023  4293 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 21:16:11.934  3023  4293 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at hec.a(PG:42)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at hee.a(PG:102)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at czr.a(PG:65)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at kka.a(PG:108)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	... 15 more
09-08 21:16:11.934  3023  4293 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at fal.a(PG:38)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 21:16:11.934  3023  4293 E ExperimentLoader: 	... 17 more
,09-08 21:16:11.980  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 21:16:11.980  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 21:16:11.980  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:16:11.980  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:12.000  3065  4291 E KeepSync: IOException
09-08 21:16:12.000  3065  4291 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 21:16:12.000  3065  4291 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:16:12.000  3065  4291 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 21:16:12.000  3065  4291 E KeepSync: 	... 10 more
,09-08 21:16:12.000  3065  4291 W KeepSync: Sync result 2
,09-08 21:16:12.012   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 259153, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:16:12.062   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 285644, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:16:18.358   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=292850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:16:44.319  3065  4301 V KeepSync: Connecting to GoogleApiClient
,09-08 21:16:44.320   874  1977 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 21:16:44.378  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:16:44.382  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:16:44.427  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 21:16:44.428  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 21:16:44.428  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:16:44.428  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:44.465  1723  4302 V BaseAuthAsyncOperation: access token request failed
,09-08 21:16:44.467  3065  4301 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 21:16:44.552  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 21:16:44.552  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 21:16:44.553  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:16:44.553  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:16:44.587  3065  4301 E KeepSync: IOException
09-08 21:16:44.587  3065  4301 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 21:16:44.587  3065  4301 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:16:44.587  3065  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 21:16:44.587  3065  4301 E KeepSync: 	... 10 more
,09-08 21:16:44.587  3065  4301 W KeepSync: Sync result 2
,09-08 21:16:44.600   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 318690, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:16:55.745   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:17:10.049  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:10.059  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:10.063  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:10.117  1509  3006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 21:17:10.117  1509  3006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 21:17:10.117  1509  3006 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:17:10.118  1509  3006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:17:10.141  1509  3006 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 21:17:10.141  1509  3006 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 21:17:10.147  3555  3586 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 21:17:10.147  3555  3586 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 21:17:10.147  3555  3586 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 21:17:10.147  3555  3586 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 21:17:10.147  3555  3586 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 21:17:10.147  3555  3586 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 21:17:10.147  3555  3586 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 21:17:34.146   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368638, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:17:43.062  3766  4310 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 21:17:43.095  3766  4311 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 21:17:43.114  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:43.123  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:43.178  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:17:43.178  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:17:43.179  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:17:43.179  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:17:43.218  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:43.222  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:17:43.262  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:17:43.262  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:17:43.262  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:17:43.263  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:17:43.299  3766  4311 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 21:17:43.300  3766  4310 E BooksSync: Soft error
09-08 21:17:43.300  3766  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:17:43.300  3766  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 21:17:43.301  3766  4310 E BooksSync: Sync error
09-08 21:17:43.301  3766  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:17:43.301  3766  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 21:17:43.301  3766  4310 I BooksSync: Finished books sync
,09-08 21:17:43.316   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 377490, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:17:56.867   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391359, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:18:13.783  3065  4313 V KeepSync: Connecting to GoogleApiClient
,09-08 21:18:13.784   874  1714 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 21:18:13.831  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:18:13.839  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:18:13.915  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 21:18:13.915  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 21:18:13.915  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:18:13.915  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:18:13.941  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 21:18:13.941  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 21:18:13.941  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:18:13.941  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:18:13.952  3023  4315 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 21:18:13.952  3023  4315 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at blb.a(PG:3937)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at czp.a(PG:18188)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:18:13.952  3023  4315 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	... 12 more
09-08 21:18:13.952  3023  4315 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at fal.a(PG:38)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:18:13.952  3023  4315 E HttpOperation: 	... 14 more
,09-08 21:18:14.033  1723  4316 V BaseAuthAsyncOperation: access token request failed
,09-08 21:18:14.034  3065  4313 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 21:18:14.100  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 21:18:14.100  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 21:18:14.100  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:18:14.100  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:18:14.136  3023  4315 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 21:18:14.136  3023  4315 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jdm.a(PG:82)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jcs.o(PG:406)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jcn.a(PG:1379)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jcs.i(PG:143)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at hec.a(PG:42)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at hee.a(PG:102)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at czr.a(PG:65)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at kka.a(PG:108)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at czp.a(PG:19176)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at czp.a(PG:9081)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at czq.run(PG:1686)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:18:14.136  3023  4315 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jdj.a(PG:4091)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jdj.a(PG:1125)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jdm.a(PG:77)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	... 15 more
09-08 21:18:14.136  3023  4315 E HttpOperation: Caused by: faj: BadAuthentication
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at fal.a(PG:38)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	at jdj.a(PG:4089)
09-08 21:18:14.136  3023  4315 E HttpOperation: 	... 17 more
,09-08 21:18:14.136  3023  4315 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 21:18:14.136  3023  4315 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at hec.a(PG:42)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at hee.a(PG:102)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at czr.a(PG:65)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at kka.a(PG:108)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	... 15 more
09-08 21:18:14.136  3023  4315 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at fal.a(PG:38)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 21:18:14.136  3023  4315 E ExperimentLoader: 	... 17 more
,09-08 21:18:14.211  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 21:18:14.212  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 21:18:14.212  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 21:18:14.212  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:18:14.239  3065  4313 E KeepSync: IOException
09-08 21:18:14.239  3065  4313 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 21:18:14.239  3065  4313 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:18:14.239  3065  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 21:18:14.239  3065  4313 E KeepSync: 	... 10 more
,09-08 21:18:14.239  3065  4313 W KeepSync: Sync result 2
,09-08 21:18:14.253   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 383461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:18:14.295   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 407196, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:18:32.868   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=427360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:19:14.011   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:19:37.719   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=492212, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:19:43.957   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=498450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:20:07.693   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=522185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:20:13.878   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=528370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:20:23.128  3065  4327 V KeepSync: Connecting to GoogleApiClient
,09-08 21:20:23.128   874  1714 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 21:20:23.208  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:20:23.216  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:20:23.276  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 21:20:23.277  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 21:20:23.277  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:20:23.278  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:20:23.330  1723  4328 V BaseAuthAsyncOperation: access token request failed
,09-08 21:20:23.333  3065  4327 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 21:20:23.426  1509  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 21:20:23.426  1509  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 21:20:23.426  1509  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:20:23.426  1509  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:20:23.458  3065  4327 E KeepSync: IOException
09-08 21:20:23.458  3065  4327 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 21:20:23.458  3065  4327 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 21:20:23.458  3065  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 21:20:23.458  3065  4327 E KeepSync: 	... 10 more
09-08 21:20:23.458  3065  4327 W KeepSync: Sync result 2
,09-08 21:20:23.472   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 537482, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:20:37.560   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=552052, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:21:15.573   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590065, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:21:39.320   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=613813, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:21:46.704  3766  4332 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 21:21:46.747  3766  4333 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 21:21:46.759  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:21:46.762  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:21:46.802  1509  2084 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 21:21:46.802  1509  2084 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:21:46.802  1509  2084 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:21:46.802  1509  2084 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:21:46.841  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:21:46.845  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 21:21:46.875  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 21:21:46.875  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 21:21:46.875  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 21:21:46.875  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 21:21:46.895  3766  4333 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 21:21:46.897  3766  4332 E BooksSync: Soft error
09-08 21:21:46.897  3766  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:21:46.897  3766  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 21:21:46.897  3766  4332 E BooksSync: Sync error
09-08 21:21:46.897  3766  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 21:21:46.897  3766  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 21:21:46.897  3766  4332 I BooksSync: Finished books sync
,09-08 21:21:46.914   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 621145, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 21:22:15.494   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=649986, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 21:22:39.159   874  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=673651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 21:31:44.421   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-08 21:37:00.968  4379  4379 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 21:37:00.972  4379  4379 D AndroidRuntime: CheckJNI is OFF
09-08 21:37:01.008  4379  4379 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 21:37:01.048  4379  4379 I Radio-JNI: register_android_hardware_Radio DONE
09-08 21:37:01.068  4379  4379 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 21:37:01.079   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 21:37:01.218   874   897 W PackageSettings: Skipping PackageSetting{84be200 com.example.hello/10273} due to missing metadata
09-08 21:37:01.255   874   897 I art     : Starting a blocking GC Explicit
09-08 21:37:01.312   874   897 I art     : Explicit concurrent mark sweep GC freed 17728(1169KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 750us total 57.036ms
09-08 21:37:01.332   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 21:37:01.339  4379  4379 I art     : System.exit called, status: 0
09-08 21:37:01.340  4379  4379 I AndroidRuntime: VM exiting with result code 0.
09-08 21:37:01.390   874   897 I ActivityManager: Start proc 4391:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-08 21:37:01.391   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 21:37:01.437  3655  3655 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 21:37:01.440  4177  4177 D BluetoothMapAppObserver: onReceive
09-08 21:37:01.440  4177  4177 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 21:37:01.442   874  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 21:37:01.443  1868  2226 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 21:37:01.450  1904  1904 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 21:37:01.453  1904  4406 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 21:37:01.465  1904  4406 I Decoder : createOrResetDecoder
09-08 21:37:01.466   874  2075 I ActivityManager: Start proc 4408:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 21:37:01.499  1998  1998 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 21:37:01.512  1509  1509 I ConfigService: onCreate
09-08 21:37:01.517  4408  4408 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 21:37:01.521  1509  4420 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 21:37:01.521  1509  4420 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:37:01.531  1509  4420 W SQLiteOpenHelper: Opened config.db in read-only mode
09-08 21:37:01.536   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 21:37:01.541  1904  4406 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 21:37:01.551  2011  2118 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 21:37:01.552   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 21:37:01.553   874   886 E PackageManager: Failed to write settings, restoring backup
09-08 21:37:01.553   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 21:37:01.553   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 21:37:01.553   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 21:37:01.553   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 21:37:01.553   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 21:37:01.553   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.553   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.553   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.557   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-08 21:37:01.557   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 21:37:01.557   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 21:37:01.557   874   887 E DropBoxManagerService: 	... 13 more
09-08 21:37:01.563   874  1693 I ActivityManager: Start proc 4421:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-08 21:37:01.564  2011  2118 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 21:37:01.564  2011  2118 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2011
09-08 21:37:01.564  2011  2118 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.564  2011  2118 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.565   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 21:37:01.566   874  4428 E DropBoxManagerService: Can't write: system_app_crash
09-08 21:37:01.566   874  4428 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 21:37:01.566   874  4428 E DropBoxManagerService: 	... 5 more
09-08 21:37:01.570  2011  2118 I Process : Sending signal. PID: 2011 SIG: 9
09-08 21:37:01.589  1904  4406 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 21:37:01.591  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 21:37:01.591  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 21:37:01.593  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 21:37:01.593  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 21:37:01.593  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 21:37:01.593  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 21:37:01.594  1904  4406 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 21:37:01.594  1904  4406 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 21:37:01.594  1904  4406 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 21:37:01.594  1904  4406 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 21:37:01.594  1904  4406 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 21:37:01.594  1904  4406 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 21:37:01.611  4408  4408 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 21:37:01.622  4408  4438 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 21:37:01.630   874  1392 D GraphicsStats: Buffer count: 1
09-08 21:37:01.630   874  2072 I WindowState: WIN DEATH: Window{fc3f388 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 21:37:01.631   874  2012 I ActivityManager: Start proc 4440:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 21:37:01.639   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2011) has died
09-08 21:37:01.640   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 21:37:01.641   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.649  4408  4436 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.649  4408  4436 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.657   874   887 I ActivityManager: Start proc 4452:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 21:37:01.685  4440  4440 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:37:01.707  4452  4452 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 21:37:01.708  4452  4452 D AndroidRuntime: Shutting down VM
09-08 21:37:01.714  4452  4452 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:37:01.714  4452  4452 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4452
09-08 21:37:01.714  4452  4452 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 21:37:01.714  4452  4452 E AndroidRuntime: 	... 10 more
09-08 21:37:01.715   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 21:37:01.716  4452  4452 I Process : Sending signal. PID: 4452 SIG: 9
09-08 21:37:01.717   874  4466 E DropBoxManagerService: Can't write: system_app_crash
09-08 21:37:01.717   874  4466 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 21:37:01.717   874  4466 E DropBoxManagerService: 	... 5 more
09-08 21:37:01.735  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 21:37:01.736  1509  1509 D AndroidRuntime: Shutting down VM
09-08 21:37:01.737  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:37:01.737  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
09-08 21:37:01.737  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 21:37:01.737  1509  1509 E AndroidRuntime: 	... 8 more
09-08 21:37:01.746   874  2116 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4452) has died
09-08 21:37:01.747   874  2116 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 21:37:01.754   874  4471 E DropBoxManagerService: Can't write: system_app_crash
09-08 21:37:01.754   874  4471 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 21:37:01.754   874  4471 E DropBoxManagerService: 	... 5 more
09-08 21:37:01.764   874   887 I ActivityManager: Start proc 4472:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 21:37:01.766  1509  1509 I Process : Sending signal. PID: 1509 SIG: 9
09-08 21:37:01.778   874  1714 I ActivityManager: Killing 3707:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-08 21:37:01.793  4408  4436 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.804  4408  4438 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 21:37:01.805  4408  4438 E AndroidRuntime: Process: android.process.acore, PID: 4408
09-08 21:37:01.805  4408  4438 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 21:37:01.805  4408  4438 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:37:01.806  4408  4436 I Process : Sending signal. PID: 4408 SIG: 9
09-08 21:37:01.822   874  1317 D WifiService: Client connection lost with reason: 4
09-08 21:37:01.824  1723  4467 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@9c7c4de

```
